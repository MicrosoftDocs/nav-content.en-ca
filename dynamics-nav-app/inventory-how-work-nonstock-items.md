---
title: Create and Manage Nonstock Items
description: Describes how to trade non-inventoriable items or items that are not maintained in your inventory.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: non-inventoriable
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: dee8b9ec3b47760f0ececc0a13f68c0039ad4c1a
ms.contentlocale: en-ca
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-work-with-nonstock-items"></a><span data-ttu-id="524df-103">How to: Work with Nonstock Items</span><span class="sxs-lookup"><span data-stu-id="524df-103">How to: Work with Nonstock Items</span></span>
<span data-ttu-id="524df-104">You can offer certain items to your customers for their convenience, which you do not want to maintain in inventory until you start selling them.</span><span class="sxs-lookup"><span data-stu-id="524df-104">You can offer certain items to your customers for their convenience, which you do not want to maintain in inventory until you start selling them.</span></span> <span data-ttu-id="524df-105">When you want to start maintaining such items in inventory, you can convert them to normal item cards in two ways.</span><span class="sxs-lookup"><span data-stu-id="524df-105">When you want to start maintaining such items in inventory, you can convert them to normal item cards in two ways.</span></span>

* <span data-ttu-id="524df-106">From a nonstock item card, create a new item card based on a template.</span><span class="sxs-lookup"><span data-stu-id="524df-106">From a nonstock item card, create a new item card based on a template.</span></span>
* <span data-ttu-id="524df-107">From a sales order line of type **Item** with an empty **No* field, select a nonstock item.</span><span class="sxs-lookup"><span data-stu-id="524df-107">From a sales order line of type **Item** with an empty **No* field, select a nonstock item.</span></span> <span data-ttu-id="524df-108">An item card is automatically created for the nonstock item.</span><span class="sxs-lookup"><span data-stu-id="524df-108">An item card is automatically created for the nonstock item.</span></span>

> [!NOTE]  
>   <span data-ttu-id="524df-109">You cannot select a nonstock item from the **Sales Invoice** window.</span><span class="sxs-lookup"><span data-stu-id="524df-109">You cannot select a nonstock item from the **Sales Invoice** window.</span></span> <span data-ttu-id="524df-110">You can select a nonstock item from the **Sales Quote** window, but the nonstock item will not be converted to a normal item when you use the **Make Order** function.</span><span class="sxs-lookup"><span data-stu-id="524df-110">You can select a nonstock item from the **Sales Quote** window, but the nonstock item will not be converted to a normal item when you use the **Make Order** function.</span></span>

<span data-ttu-id="524df-111">A nonstock item typically has the item number of the vendor who supplies it.</span><span class="sxs-lookup"><span data-stu-id="524df-111">A nonstock item typically has the item number of the vendor who supplies it.</span></span> <span data-ttu-id="524df-112">To enable conversion of a nonstock item card to a normal item card, you must first set up how vendor item numbering is converted to your own item numbering.</span><span class="sxs-lookup"><span data-stu-id="524df-112">To enable conversion of a nonstock item card to a normal item card, you must first set up how vendor item numbering is converted to your own item numbering.</span></span>   

## <a name="to-create-a-nonstock-item"></a><span data-ttu-id="524df-113">To create a nonstock item</span><span class="sxs-lookup"><span data-stu-id="524df-113">To create a nonstock item</span></span>
<span data-ttu-id="524df-114">Nonstock item cards have much less information than normal item cards because you only use them to offer on quotes and in other ways.</span><span class="sxs-lookup"><span data-stu-id="524df-114">Nonstock item cards have much less information than normal item cards because you only use them to offer on quotes and in other ways.</span></span> <span data-ttu-id="524df-115">For that reason, they must be converted to normal item cards before you can post sales transactions for them.</span><span class="sxs-lookup"><span data-stu-id="524df-115">For that reason, they must be converted to normal item cards before you can post sales transactions for them.</span></span>

1. <span data-ttu-id="524df-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Items**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="524df-116">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="524df-117">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="524df-117">Choose the **New** action.</span></span>
3. <span data-ttu-id="524df-118">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="524df-118">Fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]

## <a name="to-set-up-how-nonstock-item-numbers-are-converted-to-your-own-numbering"></a><span data-ttu-id="524df-119">To set up how nonstock item numbers are converted to your own numbering</span><span class="sxs-lookup"><span data-stu-id="524df-119">To set up how nonstock item numbers are converted to your own numbering</span></span>
<span data-ttu-id="524df-120">To enable conversion of a nonstock item card to a normal item card, you must first set up how the vendor's item numbering is converted to your own item number format.</span><span class="sxs-lookup"><span data-stu-id="524df-120">To enable conversion of a nonstock item card to a normal item card, you must first set up how the vendor's item numbering is converted to your own item number format.</span></span>

1. <span data-ttu-id="524df-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Item Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="524df-121">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Item Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="524df-122">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="524df-122">Fill in the fields as necessary.</span></span>

## <a name="to-convert-a-nonstock-item-to-a-normal-item"></a><span data-ttu-id="524df-123">To convert a nonstock item to a normal item</span><span class="sxs-lookup"><span data-stu-id="524df-123">To convert a nonstock item to a normal item</span></span>
1. <span data-ttu-id="524df-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Items**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="524df-124">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Nonstock Items**, and then choose the related link.</span></span>
2. <span data-ttu-id="524df-125">Open the card for a nonstock item that you want to convert to a normal item.</span><span class="sxs-lookup"><span data-stu-id="524df-125">Open the card for a nonstock item that you want to convert to a normal item.</span></span>
3. <span data-ttu-id="524df-126">In the **Nonstock Item Card** window, choose the **Create Item** action.</span><span class="sxs-lookup"><span data-stu-id="524df-126">In the **Nonstock Item Card** window, choose the **Create Item** action.</span></span>

<span data-ttu-id="524df-127">A new item card prefilled with information from the nonstock item and a relevant item template is created.</span><span class="sxs-lookup"><span data-stu-id="524df-127">A new item card prefilled with information from the nonstock item and a relevant item template is created.</span></span> <span data-ttu-id="524df-128">You can then fill or edit fields on the new item card as necessary.</span><span class="sxs-lookup"><span data-stu-id="524df-128">You can then fill or edit fields on the new item card as necessary.</span></span> <span data-ttu-id="524df-129">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="524df-129">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>

## <a name="to-sell-a-nonstock-item-and-convert-it-to-a-normal-item"></a><span data-ttu-id="524df-130">To sell a nonstock item, and convert it to a normal item</span><span class="sxs-lookup"><span data-stu-id="524df-130">To sell a nonstock item, and convert it to a normal item</span></span>
1. <span data-ttu-id="524df-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="524df-131">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="524df-132">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="524df-132">Choose the **New** action.</span></span> <span data-ttu-id="524df-133">Fill in the fields on the **General** FastTab as for any sales order.</span><span class="sxs-lookup"><span data-stu-id="524df-133">Fill in the fields on the **General** FastTab as for any sales order.</span></span> <span data-ttu-id="524df-134">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="524df-134">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
3. <span data-ttu-id="524df-135">On a new sales line, in the **Type** field, select **Item**, but leave the **No.**</span><span class="sxs-lookup"><span data-stu-id="524df-135">On a new sales line, in the **Type** field, select **Item**, but leave the **No.**</span></span> <span data-ttu-id="524df-136">field empty.</span><span class="sxs-lookup"><span data-stu-id="524df-136">field empty.</span></span>
4. <span data-ttu-id="524df-137">Choose the **Line** action, and then choose the **Select Nonstock Items** action.</span><span class="sxs-lookup"><span data-stu-id="524df-137">Choose the **Line** action, and then choose the **Select Nonstock Items** action.</span></span>

    <span data-ttu-id="524df-138">The nonstock item is converted to a normal item.</span><span class="sxs-lookup"><span data-stu-id="524df-138">The nonstock item is converted to a normal item.</span></span> <span data-ttu-id="524df-139">A new item card prefilled with information from the nonstock item and a relevant item template is created.</span><span class="sxs-lookup"><span data-stu-id="524df-139">A new item card prefilled with information from the nonstock item and a relevant item template is created.</span></span>
5. <span data-ttu-id="524df-140">In the **Nonstock Items** window, select the nonstock item that you want to sell, and then choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="524df-140">In the **Nonstock Items** window, select the nonstock item that you want to sell, and then choose the **OK** button.</span></span>
6. <span data-ttu-id="524df-141">When the sales order is complete, choose the **Post** action.</span><span class="sxs-lookup"><span data-stu-id="524df-141">When the sales order is complete, choose the **Post** action.</span></span>

<span data-ttu-id="524df-142">You can then fill or edit fields on the new item card as necessary.</span><span class="sxs-lookup"><span data-stu-id="524df-142">You can then fill or edit fields on the new item card as necessary.</span></span> <span data-ttu-id="524df-143">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span><span class="sxs-lookup"><span data-stu-id="524df-143">For more information, see [How to: Register New Items](inventory-how-register-new-items.md).</span></span>

> [!NOTE]  
>   <span data-ttu-id="524df-144">An Item cross reference record is automatically created for the vendor of the item between the vendor's item number and your new item number.</span><span class="sxs-lookup"><span data-stu-id="524df-144">An Item cross reference record is automatically created for the vendor of the item between the vendor's item number and your new item number.</span></span>

## <a name="see-also"></a><span data-ttu-id="524df-145">See Also</span><span class="sxs-lookup"><span data-stu-id="524df-145">See Also</span></span>
[<span data-ttu-id="524df-146">How to: Register New Items</span><span class="sxs-lookup"><span data-stu-id="524df-146">How to: Register New Items</span></span>](inventory-how-register-new-items.md)  
<span data-ttu-id="524df-147">[How to: Create Special Orders](sales-how-to-create-special-orders.md)|</span><span class="sxs-lookup"><span data-stu-id="524df-147">[How to: Create Special Orders](sales-how-to-create-special-orders.md)|</span></span>  
[<span data-ttu-id="524df-148">Qty. on Hand</span><span class="sxs-lookup"><span data-stu-id="524df-148">Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="524df-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="524df-149">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

