---
title: 'Lync Server 2013 : affichage des informations de sous-réseau'
description: 'Lync Server 2013 : affichage des informations de sous-réseau.'
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: Viewing network subnet information
ms:assetid: 46f165f2-efe3-4cc1-9fee-a78b7f2ed41e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ688044(v=OCS.15)
ms:contentKeyID: 49733636
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 313135c43318817391d54f2fa3e73dd318f7a11f
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/26/2020
ms.locfileid: "49438854"
---
# <a name="viewing-network-subnet-information-in-lync-server-2013"></a><span data-ttu-id="5ddae-103">Affichage des informations de sous-réseau dans Lync Server 2013</span><span class="sxs-lookup"><span data-stu-id="5ddae-103">Viewing network subnet information in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="5ddae-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="5ddae-104">

<span> </span></span></span>

<span data-ttu-id="5ddae-105">_**Dernière modification de la rubrique :** 2013-02-23_</span><span class="sxs-lookup"><span data-stu-id="5ddae-105">_**Topic Last Modified:** 2013-02-23_</span></span>

<span data-ttu-id="5ddae-106">Vous pouvez utiliser la procédure suivante pour afficher un sous-réseau.</span><span class="sxs-lookup"><span data-stu-id="5ddae-106">You can use the following procedure to view a network subnet.</span></span> <span data-ttu-id="5ddae-107">Dans le panneau de configuration de Lync Server, vous pouvez créer, modifier ou supprimer un sous-réseau.</span><span class="sxs-lookup"><span data-stu-id="5ddae-107">From the Lync Server Control Panel, you can create, modify, or delete a network subnet.</span></span> <span data-ttu-id="5ddae-108">Pour plus d’informations sur la création et la modification de sous-réseaux réseau, voir [créer ou modifier des sous-réseaux dans Lync Server 2013](lync-server-2013-create-or-modify-network-subnets.md).</span><span class="sxs-lookup"><span data-stu-id="5ddae-108">For details about creating or modifying network subnets, see [Create or modify network subnets in Lync Server 2013](lync-server-2013-create-or-modify-network-subnets.md).</span></span>

<div>

## <a name="to-view-a-network-subnet"></a><span data-ttu-id="5ddae-109">Pour afficher un sous-réseau</span><span class="sxs-lookup"><span data-stu-id="5ddae-109">To view a network subnet</span></span>

1.  <span data-ttu-id="5ddae-110">À partir d’un compte d’utilisateur membre du groupe RTCUniversalServerAdmins (ou doté de droits d’utilisateur équivalents), ou affectées au rôle CsAdministrator, connectez-vous à n’importe quel ordinateur dans votre déploiement interne.</span><span class="sxs-lookup"><span data-stu-id="5ddae-110">From a user account that is a member of the RTCUniversalServerAdmins group (or has equivalent user rights), or is assigned to the CsAdministrator role, log on to any computer in your internal deployment.</span></span>

2.  <span data-ttu-id="5ddae-111">Ouvrez une fenêtre de navigateur, puis entrez l’URL d’administration pour ouvrir le panneau de configuration de Lync Server.</span><span class="sxs-lookup"><span data-stu-id="5ddae-111">Open a browser window, and then enter the Admin URL to open the Lync Server Control Panel.</span></span> <span data-ttu-id="5ddae-112">Pour plus d’informations sur les différentes méthodes que vous pouvez utiliser pour démarrer le panneau de configuration de Lync Server, voir [ouvrir les outils d’administration de Lync server 2013](lync-server-2013-open-lync-server-administrative-tools.md).</span><span class="sxs-lookup"><span data-stu-id="5ddae-112">For details about the different methods you can use to start Lync Server Control Panel, see [Open Lync Server 2013 administrative tools](lync-server-2013-open-lync-server-administrative-tools.md).</span></span>

3.  <span data-ttu-id="5ddae-113">Dans la barre de navigation de gauche, cliquez sur **configuration du réseau** , puis sur **sous-réseau**.</span><span class="sxs-lookup"><span data-stu-id="5ddae-113">In the left navigation bar, click **Network Configuration** and then click **Subnet**.</span></span>

4.  <span data-ttu-id="5ddae-114">Dans la page de **sous-réseau** , cliquez sur le sous-réseau que vous souhaitez afficher.</span><span class="sxs-lookup"><span data-stu-id="5ddae-114">On the **Subnet** page, click the subnet that you want to view.</span></span>
    
    <div>
    

    > [!NOTE]  
    > <span data-ttu-id="5ddae-115">Vous ne pouvez afficher qu’un seul sous-réseau à la fois.</span><span class="sxs-lookup"><span data-stu-id="5ddae-115">You can only view one subnet at a time.</span></span>

    
    </div>

5.  <span data-ttu-id="5ddae-116">Dans le menu **édition** , cliquez sur **afficher les détails.**</span><span class="sxs-lookup"><span data-stu-id="5ddae-116">On the **Edit** menu, click **Show details…**.</span></span>

</div>

<div>

## <a name="viewing-network-subnet-configuration-information-by-using-windows-powershell-cmdlets"></a><span data-ttu-id="5ddae-117">Affichage des informations de configuration de sous-réseau en utilisant des applets de cmdlet Windows PowerShell</span><span class="sxs-lookup"><span data-stu-id="5ddae-117">Viewing Network Subnet Configuration Information by Using Windows PowerShell Cmdlets</span></span>

<span data-ttu-id="5ddae-118">Les informations de sous-réseau peuvent être affichées à l’aide de Windows PowerShell et de l’applet de connexion Get-CsNetworkSubnet.</span><span class="sxs-lookup"><span data-stu-id="5ddae-118">Network subnet information can be viewed by using Windows PowerShell and the Get-CsNetworkSubnet cmdlet.</span></span> <span data-ttu-id="5ddae-119">Cette applet de commande peut être exécutée à partir de Lync Server 2013 Management Shell ou d’une session distante de Windows PowerShell.</span><span class="sxs-lookup"><span data-stu-id="5ddae-119">This cmdlet can be run either from the Lync Server 2013 Management Shell or from a remote session of Windows PowerShell.</span></span> <span data-ttu-id="5ddae-120">Pour plus d’informations sur l’utilisation de Windows PowerShell distant pour vous connecter à Lync Server, voir l’article de blog Lync Server Windows PowerShell « démarrage rapide : gestion de Microsoft Lync Server 2010 à l’aide de Remote PowerShell » [https://go.microsoft.com/fwlink/p/?linkId=255876](https://go.microsoft.com/fwlink/p/?linkid=255876) .</span><span class="sxs-lookup"><span data-stu-id="5ddae-120">For details about using remote Windows PowerShell to connect to Lync Server, see the Lync Server Windows PowerShell blog article "Quick Start: Managing Microsoft Lync Server 2010 Using Remote PowerShell" at [https://go.microsoft.com/fwlink/p/?linkId=255876](https://go.microsoft.com/fwlink/p/?linkid=255876).</span></span>

<div>

## <a name="to-view-network-subnet-information"></a><span data-ttu-id="5ddae-121">Pour afficher les informations de sous-réseau</span><span class="sxs-lookup"><span data-stu-id="5ddae-121">To view network subnet information</span></span>

  - <span data-ttu-id="5ddae-122">Pour afficher des informations sur tous les sous-réseaux de votre réseau, tapez la commande suivante dans Lync Server Management Shell, puis appuyez sur entrée :</span><span class="sxs-lookup"><span data-stu-id="5ddae-122">To view information about all your network subnets, type the following command in the Lync Server Management Shell and then press ENTER:</span></span>
    
        Get-CsNetworkSubnet
    
    <span data-ttu-id="5ddae-123">Vous obtiendrez des indications semblables à ceci :</span><span class="sxs-lookup"><span data-stu-id="5ddae-123">That will return information similar to this:</span></span>
    
        Identity      : 172.11.15.0
        MaskBits      : 28
        Description   :
        NetworkSiteID : Redmond
        SubnetID      : 172.11.15.0

</div>

<span data-ttu-id="5ddae-124">Pour plus d’informations, consultez la rubrique d’aide de l’applet de passe [Get-CsNetworkSubnet](https://docs.microsoft.com/powershell/module/skype/Get-CsNetworkSubnet) .</span><span class="sxs-lookup"><span data-stu-id="5ddae-124">For more information, see the help topic for the [Get-CsNetworkSubnet](https://docs.microsoft.com/powershell/module/skype/Get-CsNetworkSubnet) cmdlet.</span></span>

</div>

<div>

## <a name="see-also"></a><span data-ttu-id="5ddae-125">Voir aussi</span><span class="sxs-lookup"><span data-stu-id="5ddae-125">See Also</span></span>


[<span data-ttu-id="5ddae-126">Créer ou modifier des sous-réseaux réseau dans Lync Server 2013</span><span class="sxs-lookup"><span data-stu-id="5ddae-126">Create or modify network subnets in Lync Server 2013</span></span>](lync-server-2013-create-or-modify-network-subnets.md)  
[<span data-ttu-id="5ddae-127">Supprimer des sous-réseaux réseau dans Lync Server 2013</span><span class="sxs-lookup"><span data-stu-id="5ddae-127">Deleting network subnets in Lync Server 2013</span></span>](lync-server-2013-deleting-network-subnets.md)  
  

<span data-ttu-id="5ddae-128"></div>

</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="5ddae-128"></div>

</div>

<span> </span>

</div>

</div>

</span></span></div>

