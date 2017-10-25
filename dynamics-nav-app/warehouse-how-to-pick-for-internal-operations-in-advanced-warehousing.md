---
title: How to Pick for Internal Operations in Advanced Warehouse Configurations
description: In advanced warehouse configurations where the location is set up to use picking as well as shipping, you can pick components for production and assembly activities with the **Warehouse Pick** window.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/06/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 4ae74ab552f39642344acc1ab54296994598c377
ms.contentlocale: en-ca
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-pick-for-assembly-or-production-in-advanced-warehouse-configurations"></a><span data-ttu-id="408a4-103">How to: Pick for Assembly or Production in Advanced Warehouse Configurations</span><span class="sxs-lookup"><span data-stu-id="408a4-103">How to: Pick for Assembly or Production in Advanced Warehouse Configurations</span></span>
<span data-ttu-id="408a4-104">In advanced warehouse configurations where the location is set up to use picking as well as shipping, you can pick components for production and assembly activities with the **Warehouse Pick** window.</span><span class="sxs-lookup"><span data-stu-id="408a4-104">In advanced warehouse configurations where the location is set up to use picking as well as shipping, you can pick components for production and assembly activities with the **Warehouse Pick** window.</span></span>  

<span data-ttu-id="408a4-105">Alternatively, you can use the **Movement Worksheet** window to move items between bins ad hoc, meaning without reference to a source document.</span><span class="sxs-lookup"><span data-stu-id="408a4-105">Alternatively, you can use the **Movement Worksheet** window to move items between bins ad hoc, meaning without reference to a source document.</span></span> <span data-ttu-id="408a4-106">For more information, see [How to: Move Items in advanced warehouse configurations](warehouse-how-to-move-items-in-advanced-warehousing.md).</span><span class="sxs-lookup"><span data-stu-id="408a4-106">For more information, see [How to: Move Items in advanced warehouse configurations](warehouse-how-to-move-items-in-advanced-warehousing.md).</span></span>  

<span data-ttu-id="408a4-107">For information about picking items for internal operations in basic warehouse locations that are set up for picking only, see [How to: Move Components to an Operation Area in Basic Warehouse Configurations](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md).</span><span class="sxs-lookup"><span data-stu-id="408a4-107">For information about picking items for internal operations in basic warehouse locations that are set up for picking only, see [How to: Move Components to an Operation Area in Basic Warehouse Configurations](warehouse-how-to-move-components-to-an-operation-area-in-basic-warehousing.md).</span></span>  

<span data-ttu-id="408a4-108">You cannot create a warehouse pick document from scratch because a pick activity is always part of a workflow, either in a pull or a push scenario.</span><span class="sxs-lookup"><span data-stu-id="408a4-108">You cannot create a warehouse pick document from scratch because a pick activity is always part of a workflow, either in a pull or a push scenario.</span></span>  

<span data-ttu-id="408a4-109">You can create the warehouse pick document in a push fashion by selecting **Create Whse. Pick** on the source document, such as a released assembly order or warehouse shipment.</span><span class="sxs-lookup"><span data-stu-id="408a4-109">You can create the warehouse pick document in a push fashion by selecting **Create Whse. Pick** on the source document, such as a released assembly order or warehouse shipment.</span></span> <span data-ttu-id="408a4-110">For more information, see [[How to: Pick Items with Warehouse Picks](warehouse-how-to-pick-items-for-warehouse-shipment.md).</span><span class="sxs-lookup"><span data-stu-id="408a4-110">For more information, see [[How to: Pick Items with Warehouse Picks](warehouse-how-to-pick-items-for-warehouse-shipment.md).</span></span>  

<span data-ttu-id="408a4-111">Alternatively, you can create the warehouse pick document in a pull fashion by using the **Pick Worksheet** window to detect pick requests, both for shipment and internal operations, and then create the required warehouse pick documents.</span><span class="sxs-lookup"><span data-stu-id="408a4-111">Alternatively, you can create the warehouse pick document in a pull fashion by using the **Pick Worksheet** window to detect pick requests, both for shipment and internal operations, and then create the required warehouse pick documents.</span></span>  

<span data-ttu-id="408a4-112">The following procedure explains a pull scenario where you pick components for a released production order through the **Pick Worksheet** window.</span><span class="sxs-lookup"><span data-stu-id="408a4-112">The following procedure explains a pull scenario where you pick components for a released production order through the **Pick Worksheet** window.</span></span> <span data-ttu-id="408a4-113">The procedure also applies for an assembly order.</span><span class="sxs-lookup"><span data-stu-id="408a4-113">The procedure also applies for an assembly order.</span></span>  

<span data-ttu-id="408a4-114">To create pick requests, both for pull and for push scenarios, the source documents in question must be released.</span><span class="sxs-lookup"><span data-stu-id="408a4-114">To create pick requests, both for pull and for push scenarios, the source documents in question must be released.</span></span> <span data-ttu-id="408a4-115">Release source documents for internal operations in the following ways.</span><span class="sxs-lookup"><span data-stu-id="408a4-115">Release source documents for internal operations in the following ways.</span></span>  

|<span data-ttu-id="408a4-116">Source Document</span><span class="sxs-lookup"><span data-stu-id="408a4-116">Source Document</span></span>|<span data-ttu-id="408a4-117">Release Method</span><span class="sxs-lookup"><span data-stu-id="408a4-117">Release Method</span></span>|  
|---------------------|--------------------|  
|<span data-ttu-id="408a4-118">Production Order</span><span class="sxs-lookup"><span data-stu-id="408a4-118">Production Order</span></span>|<span data-ttu-id="408a4-119">Change order type to released production order.</span><span class="sxs-lookup"><span data-stu-id="408a4-119">Change order type to released production order.</span></span>|  
|<span data-ttu-id="408a4-120">Assembly Order</span><span class="sxs-lookup"><span data-stu-id="408a4-120">Assembly Order</span></span>|<span data-ttu-id="408a4-121">Change status to Released.</span><span class="sxs-lookup"><span data-stu-id="408a4-121">Change status to Released.</span></span>|  

## <a name="to-pick-components-using-the-pick-worksheet"></a><span data-ttu-id="408a4-122">To pick components using the pick worksheet</span><span class="sxs-lookup"><span data-stu-id="408a4-122">To pick components using the pick worksheet</span></span>  
1.  <span data-ttu-id="408a4-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Pick Worksheet**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="408a4-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Pick Worksheet**, and then choose the related link.</span></span>  
2.  <span data-ttu-id="408a4-124">Choose the **Get Warehouse Documents** action, and then select the component lines from the released production order.</span><span class="sxs-lookup"><span data-stu-id="408a4-124">Choose the **Get Warehouse Documents** action, and then select the component lines from the released production order.</span></span>  
3.  <span data-ttu-id="408a4-125">Inspect the lines, sort them to ensure an efficient picking round, and combine them with other worksheet lines if necessary to make best use of employee time.</span><span class="sxs-lookup"><span data-stu-id="408a4-125">Inspect the lines, sort them to ensure an efficient picking round, and combine them with other worksheet lines if necessary to make best use of employee time.</span></span>  
4.  <span data-ttu-id="408a4-126">Choose the **Create Pick** action.</span><span class="sxs-lookup"><span data-stu-id="408a4-126">Choose the **Create Pick** action.</span></span>  
5.  <span data-ttu-id="408a4-127">Define how to create the warehouse pick documents and how to sort pick lines by filling fields in the **Create Pick** window.</span><span class="sxs-lookup"><span data-stu-id="408a4-127">Define how to create the warehouse pick documents and how to sort pick lines by filling fields in the **Create Pick** window.</span></span>  
6.  <span data-ttu-id="408a4-128">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="408a4-128">Choose the **OK** button.</span></span> <span data-ttu-id="408a4-129">Warehouse pick documents are created with pick lines for each component that is required in the internal operation.</span><span class="sxs-lookup"><span data-stu-id="408a4-129">Warehouse pick documents are created with pick lines for each component that is required in the internal operation.</span></span>  

<span data-ttu-id="408a4-130">If the internal operation area, such as a production shop floor, is set up with a default bin for placement of components to be used in the operation, then that bin code is inserted in the Place lines on the warehouse pick document to instruct warehouse workers where to place the items.</span><span class="sxs-lookup"><span data-stu-id="408a4-130">If the internal operation area, such as a production shop floor, is set up with a default bin for placement of components to be used in the operation, then that bin code is inserted in the Place lines on the warehouse pick document to instruct warehouse workers where to place the items.</span></span> <span data-ttu-id="408a4-131">For more information, see the **To-Production Bin Code** or the **To-Assembly Bin Code** field.</span><span class="sxs-lookup"><span data-stu-id="408a4-131">For more information, see the **To-Production Bin Code** or the **To-Assembly Bin Code** field.</span></span>

## <a name="filling-the-consumption-bin"></a><span data-ttu-id="408a4-132">Filling the Consumption Bin</span><span class="sxs-lookup"><span data-stu-id="408a4-132">Filling the Consumption Bin</span></span>
<span data-ttu-id="408a4-133">This flow chart shows how the **Bin Code** field on production order component lines is filled according to your location setup.</span><span class="sxs-lookup"><span data-stu-id="408a4-133">This flow chart shows how the **Bin Code** field on production order component lines is filled according to your location setup.</span></span>

<span data-ttu-id="408a4-134">![Bin flow chart](media/binflow.png "BinFlow")</span><span class="sxs-lookup"><span data-stu-id="408a4-134">![Bin flow chart](media/binflow.png "BinFlow")</span></span>  

## <a name="see-also"></a><span data-ttu-id="408a4-135">See Also</span><span class="sxs-lookup"><span data-stu-id="408a4-135">See Also</span></span>
[<span data-ttu-id="408a4-136">Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="408a4-136">Warehouse Management</span></span>](warehouse-manage-warehouse.md)  
[<span data-ttu-id="408a4-137">Qty. on Hand</span><span class="sxs-lookup"><span data-stu-id="408a4-137">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="408a4-138">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span><span class="sxs-lookup"><span data-stu-id="408a4-138">[Setting Up Warehouse Management](warehouse-setup-warehouse.md)   </span></span>  
<span data-ttu-id="408a4-139">[Assembly Management](assembly-assemble-items.md)  </span><span class="sxs-lookup"><span data-stu-id="408a4-139">[Assembly Management](assembly-assemble-items.md)  </span></span>  
[<span data-ttu-id="408a4-140">Design Details: Warehouse Management</span><span class="sxs-lookup"><span data-stu-id="408a4-140">Design Details: Warehouse Management</span></span>](design-details-warehouse-management.md)  
<span data-ttu-id="408a4-141">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="408a4-141">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

