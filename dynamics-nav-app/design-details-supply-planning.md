---
title: Design Details - Supply Planning
description: This topic provides an overview of the the concepts and principles that are used within the Supply Planning features in [!INCLUDE[d365fin](includes/d365fin_md.md)].
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: design, supply, planning, reordering, replenishment
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: a362452c7ee7a115751ce665e5ea6c3c96b1f27c
ms.contentlocale: en-ca
ms.lasthandoff: 12/01/2017

---
# <a name="design-details-supply-planning"></a><span data-ttu-id="8d954-103">Design Details: Supply Planning</span><span class="sxs-lookup"><span data-stu-id="8d954-103">Design Details: Supply Planning</span></span>
<span data-ttu-id="8d954-104">This documentation provides detailed technical insight to the concepts and principles that are used within the Supply Planning features in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span><span class="sxs-lookup"><span data-stu-id="8d954-104">This documentation provides detailed technical insight to the concepts and principles that are used within the Supply Planning features in [!INCLUDE[d365fin](includes/d365fin_md.md)].</span></span>  

<span data-ttu-id="8d954-105">It explains how the planning system works and how to adjust the algorithms to meet planning requirements in different environments.</span><span class="sxs-lookup"><span data-stu-id="8d954-105">It explains how the planning system works and how to adjust the algorithms to meet planning requirements in different environments.</span></span> <span data-ttu-id="8d954-106">It first introduces central solution concepts and then describes the logic of the central mechanism, supply balancing, before proceeding to explain how inventory planning is performed with the use of reordering policies.</span><span class="sxs-lookup"><span data-stu-id="8d954-106">It first introduces central solution concepts and then describes the logic of the central mechanism, supply balancing, before proceeding to explain how inventory planning is performed with the use of reordering policies.</span></span>  

## <a name="in-this-section"></a><span data-ttu-id="8d954-107">In This Section</span><span class="sxs-lookup"><span data-stu-id="8d954-107">In This Section</span></span>  
[<span data-ttu-id="8d954-108">Design Details: Central Concepts of the Planning System</span><span class="sxs-lookup"><span data-stu-id="8d954-108">Design Details: Central Concepts of the Planning System</span></span>](design-details-central-concepts-of-the-planning-system.md)  
[<span data-ttu-id="8d954-109">Design Details: Reservation, Order Tracking, and Action Messaging</span><span class="sxs-lookup"><span data-stu-id="8d954-109">Design Details: Reservation, Order Tracking, and Action Messaging</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
[<span data-ttu-id="8d954-110">Design Details: Balancing Demand and Supply</span><span class="sxs-lookup"><span data-stu-id="8d954-110">Design Details: Balancing Demand and Supply</span></span>](design-details-balancing-demand-and-supply.md)  
[<span data-ttu-id="8d954-111">Design Details: Handling Reordering Policies</span><span class="sxs-lookup"><span data-stu-id="8d954-111">Design Details: Handling Reordering Policies</span></span>](design-details-handling-reordering-policies.md)  
[<span data-ttu-id="8d954-112">Design Details: Planning Parameters</span><span class="sxs-lookup"><span data-stu-id="8d954-112">Design Details: Planning Parameters</span></span>](design-details-planning-parameters.md)  
[<span data-ttu-id="8d954-113">Design Details: Planning Assignment Table</span><span class="sxs-lookup"><span data-stu-id="8d954-113">Design Details: Planning Assignment Table</span></span>](design-details-planning-assignment-table.md)  
[<span data-ttu-id="8d954-114">Design Details: Demand at Blank Location</span><span class="sxs-lookup"><span data-stu-id="8d954-114">Design Details: Demand at Blank Location</span></span>](design-details-demand-at-blank-location.md)  
[<span data-ttu-id="8d954-115">Design Details: Transfers in Planning</span><span class="sxs-lookup"><span data-stu-id="8d954-115">Design Details: Transfers in Planning</span></span>](design-details-transfers-in-planning.md)

