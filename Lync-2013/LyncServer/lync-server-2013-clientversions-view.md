---
title: 'Affichage Lync Server 2013 : ClientVersions'
description: 'Affichage Lync Server 2013 : ClientVersions'
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: ClientVersions view
ms:assetid: caf7678f-83a0-46c8-83cc-fee4c3991f52
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ721891(v=OCS.15)
ms:contentKeyID: 49733825
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 42ede7107a59db3162ac7f5344e47e81a80d57df
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/26/2020
ms.locfileid: "49434731"
---
# <a name="clientversions-view-in-lync-server-2013"></a><span data-ttu-id="dbfb2-103">Affichage ClientVersions dans Lync Server 2013</span><span class="sxs-lookup"><span data-stu-id="dbfb2-103">ClientVersions view in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="dbfb2-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="dbfb2-104">

<span> </span></span></span>

<span data-ttu-id="dbfb2-105">_**Dernière modification de la rubrique :** 2012-10-01_</span><span class="sxs-lookup"><span data-stu-id="dbfb2-105">_**Topic Last Modified:** 2012-10-01_</span></span>

<span data-ttu-id="dbfb2-106">Le mode ClientVersions stocke les informations sur les différents types de clients et différentes versions ayant participé à des sessions enregistrées dans la base de données.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-106">The ClientVersions view stores information about the various client types and versions that have participated in sessions recorded in the database.</span></span> <span data-ttu-id="dbfb2-107">Chaque enregistrement dans la vue représente une version du client.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-107">Each record in the view represents one client version.</span></span> <span data-ttu-id="dbfb2-108">Cet affichage a été présenté dans Microsoft Lync Server 2013.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-108">This view was introduced in Microsoft Lync Server 2013.</span></span>

<div>


> [!NOTE]  
> <span data-ttu-id="dbfb2-109">Il peut y avoir plusieurs enregistrements pour certaines colonnes.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-109">There may be multiple records for certain columns.</span></span>



</div>


<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><span data-ttu-id="dbfb2-110">Colonne</span><span class="sxs-lookup"><span data-stu-id="dbfb2-110">Column</span></span></th>
<th><span data-ttu-id="dbfb2-111">Type de données</span><span class="sxs-lookup"><span data-stu-id="dbfb2-111">Data Type</span></span></th>
<th><span data-ttu-id="dbfb2-112">Détails</span><span class="sxs-lookup"><span data-stu-id="dbfb2-112">Details</span></span></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><span data-ttu-id="dbfb2-113"><strong>VersionId</strong></span><span class="sxs-lookup"><span data-stu-id="dbfb2-113"><strong>VersionId</strong></span></span></p></td>
<td><p><span data-ttu-id="dbfb2-114">int</span><span class="sxs-lookup"><span data-stu-id="dbfb2-114">int</span></span></p></td>
<td><p><span data-ttu-id="dbfb2-115">Numéro unique identifiant ce type et version de client.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-115">Unique number identifying this client type and version.</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="dbfb2-116"><strong>Version</strong></span><span class="sxs-lookup"><span data-stu-id="dbfb2-116"><strong>Version</strong></span></span></p></td>
<td><p><span data-ttu-id="dbfb2-117">nvarchar(256)</span><span class="sxs-lookup"><span data-stu-id="dbfb2-117">nvarchar(256)</span></span></p></td>
<td><p><span data-ttu-id="dbfb2-118">Représente l’agent utilisateur.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-118">Represents the user agent.</span></span></p></td>
</tr>
<tr class="odd">
<td><p><span data-ttu-id="dbfb2-119"><strong>TypeClient</strong></span><span class="sxs-lookup"><span data-stu-id="dbfb2-119"><strong>ClientType</strong></span></span></p></td>
<td><p><span data-ttu-id="dbfb2-120">int</span><span class="sxs-lookup"><span data-stu-id="dbfb2-120">int</span></span></p></td>
<td><p><span data-ttu-id="dbfb2-121">Type de client.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-121">Type of client.</span></span></p></td>
</tr>
<tr class="even">
<td><p><span data-ttu-id="dbfb2-122"><strong>ClientCategory</strong></span><span class="sxs-lookup"><span data-stu-id="dbfb2-122"><strong>ClientCategory</strong></span></span></p></td>
<td><p><span data-ttu-id="dbfb2-123">nvarchar (64)</span><span class="sxs-lookup"><span data-stu-id="dbfb2-123">nvarchar(64)</span></span></p></td>
<td><p><span data-ttu-id="dbfb2-124">Catégorie à laquelle le client appartient.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-124">Category that the client belongs to.</span></span> <span data-ttu-id="dbfb2-125">Par exemple, le client Conferencing_Attendant_1.0 appartient au CAA ClientCategory.</span><span class="sxs-lookup"><span data-stu-id="dbfb2-125">For example, the client Conferencing_Attendant_1.0 belongs to the ClientCategory CAA.</span></span></p></td>
</tr>
</tbody>
</table><span data-ttu-id="dbfb2-126">


</div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="dbfb2-126">


</div>

<span> </span>

</div>

</div>

</span></span></div>

