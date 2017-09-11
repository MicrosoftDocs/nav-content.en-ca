---
title: 'How to: Register New Products'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: df84a4d3e15035cd956c7612a12069844f5601d2
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-products"></a><span data-ttu-id="356ab-102">How to: Register New Products</span><span class="sxs-lookup"><span data-stu-id="356ab-102">How to: Register New Products</span></span>

<span data-ttu-id="356ab-103">Products are the basis of your business, the goods or services that you trade in.</span><span class="sxs-lookup"><span data-stu-id="356ab-103">Products are the basis of your business, the goods or services that you trade in.</span></span> <span data-ttu-id="356ab-104">Each product must be registered as an item card.</span><span class="sxs-lookup"><span data-stu-id="356ab-104">Each product must be registered as an item card.</span></span>

<span data-ttu-id="356ab-105">**Note**: In Dynamics NAV, a product is referred to using the term “item”.</span><span class="sxs-lookup"><span data-stu-id="356ab-105">**Note**: In Dynamics NAV, a product is referred to using the term “item”.</span></span>

<span data-ttu-id="356ab-106">Item cards hold the information that is required to buy, store, sell, deliver, and account for products.</span><span class="sxs-lookup"><span data-stu-id="356ab-106">Item cards hold the information that is required to buy, store, sell, deliver, and account for products.</span></span>

<span data-ttu-id="356ab-107">The item card can be of type Inventory or Service to specify if the product is a physical unit or labour time unit.</span><span class="sxs-lookup"><span data-stu-id="356ab-107">The item card can be of type Inventory or Service to specify if the product is a physical unit or labor time unit.</span></span> <span data-ttu-id="356ab-108">Apart from some fields that relate to the physical aspects of an item, all fields on an item card function in the same way for inventory items and services.</span><span class="sxs-lookup"><span data-stu-id="356ab-108">Apart from some fields that relate to the physical aspects of an item, all fields on an item card function in the same way for inventory items and services.</span></span> <span data-ttu-id="356ab-109">For more information about selling an item, see [How to: Sell Products](sales-how-sell-products.md) or [How to: Invoice Sales](sales-how-invoice-sales.md).</span><span class="sxs-lookup"><span data-stu-id="356ab-109">For more information about selling an item, see [How to: Sell Products](sales-how-sell-products.md) or [How to: Invoice Sales](sales-how-invoice-sales.md).</span></span>

<span data-ttu-id="356ab-110">**Note**: If item templates exist for different item types, then a window appears when you create a new item card from where you can select an appropriate template.</span><span class="sxs-lookup"><span data-stu-id="356ab-110">**Note**: If item templates exist for different item types, then a window appears when you create a new item card from where you can select an appropriate template.</span></span> <span data-ttu-id="356ab-111">If only one item template exists, then new item cards always use that template.</span><span class="sxs-lookup"><span data-stu-id="356ab-111">If only one item template exists, then new item cards always use that template.</span></span>

## <a name="to-create-a-new-item-card"></a><span data-ttu-id="356ab-112">To create a new item card</span><span class="sxs-lookup"><span data-stu-id="356ab-112">To create a new item card</span></span>
1. <span data-ttu-id="356ab-113">On the Home page, choose the **Items** action to open the list of existing items.</span><span class="sxs-lookup"><span data-stu-id="356ab-113">On the Home page, choose the **Items** action to open the list of existing items.</span></span>  
2. <span data-ttu-id="356ab-114">In the **Items** window, choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="356ab-114">In the **Items** window, choose the **New** action.</span></span>

    <span data-ttu-id="356ab-115">If only one item template exists, then a new item card opens with some fields filled with information from the template.</span><span class="sxs-lookup"><span data-stu-id="356ab-115">If only one item template exists, then a new item card opens with some fields filled with information from the template.</span></span>
3. <span data-ttu-id="356ab-116">In the **Select a template for a new item** window, choose the template that you want to use for the new item card.</span><span class="sxs-lookup"><span data-stu-id="356ab-116">In the **Select a template for a new item** window, choose the template that you want to use for the new item card.</span></span>
4. <span data-ttu-id="356ab-117">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="356ab-117">Choose the **OK** button.</span></span> <span data-ttu-id="356ab-118">A new item card opens with some fields filled with information from the template.</span><span class="sxs-lookup"><span data-stu-id="356ab-118">A new item card opens with some fields filled with information from the template.</span></span>
5. <span data-ttu-id="356ab-119">Proceed to fill or change fields on the item card as necessary.</span><span class="sxs-lookup"><span data-stu-id="356ab-119">Proceed to fill or change fields on the item card as necessary.</span></span> <span data-ttu-id="356ab-120">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="356ab-120">Choose a field to read a short description of the field or link to more information.</span></span>

<span data-ttu-id="356ab-121">On the **Sales Prices** FastTab, you can view special prices or discounts that you grant for the item if certain criteria are met, such as customer, minimum order quantity, or ending date.</span><span class="sxs-lookup"><span data-stu-id="356ab-121">On the **Sales Prices** FastTab, you can view special prices or discounts that you grant for the item if certain criteria are met, such as customer, minimum order quantity, or ending date.</span></span> <span data-ttu-id="356ab-122">Each row represents a special price or line discount.</span><span class="sxs-lookup"><span data-stu-id="356ab-122">Each row represents a special price or line discount.</span></span> <span data-ttu-id="356ab-123">Each column represents a criterion that must apply to warrant the special price that you enter in the **Unit Price** field, or the line discount that you enter in the **Line Discount %** field.</span><span class="sxs-lookup"><span data-stu-id="356ab-123">Each column represents a criterion that must apply to warrant the special price that you enter in the **Unit Price** field, or the line discount that you enter in the **Line Discount %** field.</span></span> <span data-ttu-id="356ab-124">For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).</span><span class="sxs-lookup"><span data-stu-id="356ab-124">For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).</span></span>

<span data-ttu-id="356ab-125">The item is now registered, and the item card is ready to be used on purchase and sales documents.</span><span class="sxs-lookup"><span data-stu-id="356ab-125">The item is now registered, and the item card is ready to be used on purchase and sales documents.</span></span>

<span data-ttu-id="356ab-126">If you want to use this item card as a template when you create new item cards, you can save it as a template.</span><span class="sxs-lookup"><span data-stu-id="356ab-126">If you want to use this item card as a template when you create new item cards, you can save it as a template.</span></span> <span data-ttu-id="356ab-127">For more information, see the following section.</span><span class="sxs-lookup"><span data-stu-id="356ab-127">For more information, see the following section.</span></span>

## <a name="to-save-the-item-card-as-a-template"></a><span data-ttu-id="356ab-128">To save the item card as a template</span><span class="sxs-lookup"><span data-stu-id="356ab-128">To save the item card as a template</span></span>
1. <span data-ttu-id="356ab-129">In the **Item Card** window, choose the **Save as Template** action.</span><span class="sxs-lookup"><span data-stu-id="356ab-129">In the **Item Card** window, choose the **Save as Template** action.</span></span> <span data-ttu-id="356ab-130">The **Item Template** window opens showing the item card as a template.</span><span class="sxs-lookup"><span data-stu-id="356ab-130">The **Item Template** window opens showing the item card as a template.</span></span>
2. <span data-ttu-id="356ab-131">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="356ab-131">Fill in the fields as necessary.</span></span> <span data-ttu-id="356ab-132">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="356ab-132">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="356ab-133">To reuse dimensions in templates, choose the **Dimensions** action.</span><span class="sxs-lookup"><span data-stu-id="356ab-133">To reuse dimensions in templates, choose the **Dimensions** action.</span></span> <span data-ttu-id="356ab-134">The **Dimension Templates** window opens showing any dimension codes that are set up for the item.</span><span class="sxs-lookup"><span data-stu-id="356ab-134">The **Dimension Templates** window opens showing any dimension codes that are set up for the item.</span></span>
4. <span data-ttu-id="356ab-135">Edit or enter dimension codes that will apply to new item cards created by using the template.</span><span class="sxs-lookup"><span data-stu-id="356ab-135">Edit or enter dimension codes that will apply to new item cards created by using the template.</span></span>
5. <span data-ttu-id="356ab-136">When you have completed the new item template, choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="356ab-136">When you have completed the new item template, choose the **OK** button.</span></span>

<span data-ttu-id="356ab-137">The item template is added to the list of item templates, so that you can use it to create new item cards.</span><span class="sxs-lookup"><span data-stu-id="356ab-137">The item template is added to the list of item templates, so that you can use it to create new item cards.</span></span>

## <a name="see-also"></a><span data-ttu-id="356ab-138">See Also</span><span class="sxs-lookup"><span data-stu-id="356ab-138">See Also</span></span>
  [<span data-ttu-id="356ab-139">Manage Inventory</span><span class="sxs-lookup"><span data-stu-id="356ab-139">Manage Inventory</span></span>](inventory-manage-inventory.md)  
<span data-ttu-id="356ab-140">  [Manage Purchasing](purchasing-manage-purchasing.md)</span><span class="sxs-lookup"><span data-stu-id="356ab-140">  [Manage Purchasing](purchasing-manage-purchasing.md)</span></span>  
<span data-ttu-id="356ab-141">  [Manage Sales](sales-manage-sales.md)</span><span class="sxs-lookup"><span data-stu-id="356ab-141">  [Manage Sales](sales-manage-sales.md)</span></span>

