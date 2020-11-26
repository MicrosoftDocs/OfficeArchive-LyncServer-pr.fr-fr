---
title: 'Lync Server 2013 : affichage UserAgent'
description: 'Lync Server 2013 : affichage UserAgent.'
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: UserAgent view
ms:assetid: b986f76f-f16e-4e5e-96cb-6e8f7f9b42ee
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ721862(v=OCS.15)
ms:contentKeyID: 49733795
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 9fc5ef2ec01b50f3714dca3690d0844286baaef5
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/26/2020
ms.locfileid: "49439050"
---
# <a name="useragent-view-in-lync-server-2013"></a><span data-ttu-id="f47e7-103">Affichage UserAgent dans Lync Server 2013</span><span class="sxs-lookup"><span data-stu-id="f47e7-103">UserAgent view in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="f47e7-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="f47e7-104">

<span> </span></span></span>

<span data-ttu-id="f47e7-105">_**Dernière modification de la rubrique :** 2012-10-03_</span><span class="sxs-lookup"><span data-stu-id="f47e7-105">_**Topic Last Modified:** 2012-10-03_</span></span>

<span data-ttu-id="f47e7-106">L’affichage UserAgent stocke les informations sur les agents utilisateur impliqués dans les sessions qui contiennent des enregistrements dans la base de données.</span><span class="sxs-lookup"><span data-stu-id="f47e7-106">The UserAgent View stores information about the user agents that have been involved in sessions that have records in the database.</span></span> <span data-ttu-id="f47e7-107">Cet affichage a été présenté dans Microsoft Lync Server 2013.</span><span class="sxs-lookup"><span data-stu-id="f47e7-107">This view was introduced in Microsoft Lync Server 2013.</span></span>


<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="f47e7-108">Colonne</span><span class="sxs-lookup"><span data-stu-id="f47e7-108">Column</span></span></th>
<th><span data-ttu-id="f47e7-109">Type de données</span><span class="sxs-lookup"><span data-stu-id="f47e7-109">Data Type</span></span></th>
<th><span data-ttu-id="f47e7-110">Détails</span><span class="sxs-lookup"><span data-stu-id="f47e7-110">Details</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><span data-ttu-id="f47e7-111">UserAgentKey</span><span class="sxs-lookup"><span data-stu-id="f47e7-111">UserAgentKey</span></span></p></td>
<td><p><span data-ttu-id="f47e7-112">int</span><span class="sxs-lookup"><span data-stu-id="f47e7-112">int</span></span></p></td>
<td><p><span data-ttu-id="f47e7-113">Numéro unique identifiant cet agent utilisateur.</span><span class="sxs-lookup"><span data-stu-id="f47e7-113">Unique number identifying this user agent.</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="f47e7-114">UserAgent</span><span class="sxs-lookup"><span data-stu-id="f47e7-114">UserAgent</span></span></p></td>
<td><p><span data-ttu-id="f47e7-115">nvarchar(256)</span><span class="sxs-lookup"><span data-stu-id="f47e7-115">nvarchar(256)</span></span></p></td>
<td><p><span data-ttu-id="f47e7-116">Chaîne de l’agent utilisateur.</span><span class="sxs-lookup"><span data-stu-id="f47e7-116">User agent string.</span></span></p></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="f47e7-117">UAType</span><span class="sxs-lookup"><span data-stu-id="f47e7-117">UAType</span></span></p></td>
<td><p><span data-ttu-id="f47e7-118">type</span><span class="sxs-lookup"><span data-stu-id="f47e7-118">smallint</span></span></p></td>
<td><p><span data-ttu-id="f47e7-119">Type d’agent utilisateur.</span><span class="sxs-lookup"><span data-stu-id="f47e7-119">Type of user agent.</span></span> <span data-ttu-id="f47e7-120">Pour plus d’informations, voir la <a href="lync-server-2013-useragent-table.md">table UserAgent dans Lync Server 2013</a> .</span><span class="sxs-lookup"><span data-stu-id="f47e7-120">See the <a href="lync-server-2013-useragent-table.md">UserAgent table in Lync Server 2013</a> for more details.</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="f47e7-121">UACategory</span><span class="sxs-lookup"><span data-stu-id="f47e7-121">UACategory</span></span></p></td>
<td><p><span data-ttu-id="f47e7-122">nvarchar (64)</span><span class="sxs-lookup"><span data-stu-id="f47e7-122">nvarchar(64)</span></span></p></td>
<td><p><span data-ttu-id="f47e7-123">Catégorie à laquelle l’agent utilisateur appartient.</span><span class="sxs-lookup"><span data-stu-id="f47e7-123">Category that the user agent belongs to.</span></span> <span data-ttu-id="f47e7-124">Par exemple, l’agent utilisateur Conferencing_Attendant_1.0 appartient au CAA UACategory.</span><span class="sxs-lookup"><span data-stu-id="f47e7-124">For example, the user agent Conferencing_Attendant_1.0 belongs to the UACategory CAA.</span></span></p></td>
</tr>
</tbody>
</table><span data-ttu-id="f47e7-125">


</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="f47e7-125">


</div>

<span> </span>

</div>

</div>

</span></span></div>

