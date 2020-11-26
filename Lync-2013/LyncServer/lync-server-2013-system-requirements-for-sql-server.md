---
title: 'Lync Server 2013 : Configuration système requise pour SQL Server'
description: 'Lync Server 2013 : configuration système requise pour SQL Server.'
ms.reviewer: ''
ms.author: v-lanac
author: lanachin
f1.keywords:
- NOCSH
TOCTitle: System requirements for SQL Server
ms:assetid: 9c235085-cbfa-4e9e-9cec-3f5749039a6b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ205112(v=OCS.15)
ms:contentKeyID: 48184904
ms.date: 07/23/2014
manager: serdars
mtps_version: v=OCS.15
ms.openlocfilehash: 524136174be8798aed1dc7d5d236dbb45ab18330
ms.sourcegitcommit: 36fee89bb887bea4f18b19f17a8c69daf5bc423d
ms.translationtype: MT
ms.contentlocale: fr-FR
ms.lasthandoff: 11/26/2020
ms.locfileid: "49444552"
---
# <a name="system-requirements-for-sql-server-in-lync-server-2013"></a><span data-ttu-id="28e21-103">Configuration système requise pour SQL Server dans Lync Server 2013</span><span class="sxs-lookup"><span data-stu-id="28e21-103">System requirements for SQL Server in Lync Server 2013</span></span>

<div data-xmlns="http://www.w3.org/1999/xhtml">

<div class="topic" data-xmlns="http://www.w3.org/1999/xhtml" data-msxsl="urn:schemas-microsoft-com:xslt" data-cs="https://msdn.microsoft.com/">

<div data-asp="https://msdn2.microsoft.com/asp">



</div>

<div id="mainSection">

<div id="mainBody"><span data-ttu-id="28e21-104">

<span> </span></span><span class="sxs-lookup"><span data-stu-id="28e21-104">

<span> </span></span></span>

<span data-ttu-id="28e21-105">_**Dernière modification de la rubrique :** 2013-10-25_</span><span class="sxs-lookup"><span data-stu-id="28e21-105">_**Topic Last Modified:** 2013-10-25_</span></span>

<span data-ttu-id="28e21-106">Avant de déployer Enterprise Edition Server, installez Microsoft SQL Server 2008 R2 ou Microsoft SQL Server 2012 sur un ordinateur dédié qui répond à la configuration matérielle requise.</span><span class="sxs-lookup"><span data-stu-id="28e21-106">Before you deploy Enterprise Edition server, install Microsoft SQL Server 2008 R2 or Microsoft SQL Server 2012 on a dedicated computer that meets the hardware requirements.</span></span> <span data-ttu-id="28e21-107">Pour plus d’informations sur la configuration matérielle requise, voir [plates-formes matérielles pour Lync Server 2013](lync-server-2013-server-hardware-platforms.md) dans la documentation relative à la prise en charge.</span><span class="sxs-lookup"><span data-stu-id="28e21-107">For details about hardware requirements, see [Server hardware platforms for Lync Server 2013](lync-server-2013-server-hardware-platforms.md) in the Supportability documentation.</span></span> <span data-ttu-id="28e21-108">Pour plus d’informations sur la configuration logicielle requise, voir [prise en charge de logiciels de base de données dans Lync Server 2013](lync-server-2013-database-software-support.md) dans la documentation relative à la prise en charge.</span><span class="sxs-lookup"><span data-stu-id="28e21-108">For details about software requirements, see [Database software support in Lync Server 2013](lync-server-2013-database-software-support.md) in the Supportability documentation.</span></span> <span data-ttu-id="28e21-109">Pour plus d’informations sur les autorisations nécessaires pour le déploiement, voir [autorisations de déploiement pour SQL Server dans Lync server 2013](lync-server-2013-deployment-permissions-for-sql-server.md).</span><span class="sxs-lookup"><span data-stu-id="28e21-109">For information about the permissions necessary for deployment, see [Deployment permissions for SQL Server in Lync Server 2013](lync-server-2013-deployment-permissions-for-sql-server.md).</span></span>

<span data-ttu-id="28e21-110">Avant de créer le pool frontal, vous devez également configurer le pare-feu Windows pour autoriser l’accès de Lync Server 2013 à SQL Server sur des ports spécifiques en définissant des ports pour le serveur à l’aide du gestionnaire de configuration SQL Server et en ouvrant des ports dans le pare-feu Windows avec sécurité avancée.</span><span class="sxs-lookup"><span data-stu-id="28e21-110">Before you create the Front End pool, you must also configure Windows Firewall to allow Lync Server 2013 access to SQL Server over specific ports by defining ports for the server using SQL Server Configuration Manager and opening ports in Windows Firewall with Advanced Security.</span></span>

<span data-ttu-id="28e21-111"></div>

<span> </span>

</div>

</div>

</span><span class="sxs-lookup"><span data-stu-id="28e21-111"></div>

<span> </span>

</div>

</div>

</span></span></div>

