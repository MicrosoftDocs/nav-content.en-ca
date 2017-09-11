---
title: 'How to: Make Drop Shipments'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: a726c8c24d8f843b33b4df4d85ad2b5eab3790e7
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-make-drop-shipments"></a><span data-ttu-id="46cdd-102">How to: Make Drop Shipments</span><span class="sxs-lookup"><span data-stu-id="46cdd-102">How to: Make Drop Shipments</span></span>
<span data-ttu-id="46cdd-103">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span><span class="sxs-lookup"><span data-stu-id="46cdd-103">A drop shipment is the shipment of items from one of your vendors directly to one of your customers.</span></span>

<span data-ttu-id="46cdd-104">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span><span class="sxs-lookup"><span data-stu-id="46cdd-104">When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.**</span></span> <span data-ttu-id="46cdd-105">field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span><span class="sxs-lookup"><span data-stu-id="46cdd-105">field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.</span></span>

## <a name="to-create-a-sales-order-for-drop-shipment"></a><span data-ttu-id="46cdd-106">To create a sales order for drop shipment</span><span class="sxs-lookup"><span data-stu-id="46cdd-106">To create a sales order for drop shipment</span></span>
<span data-ttu-id="46cdd-107">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span><span class="sxs-lookup"><span data-stu-id="46cdd-107">To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.</span></span>

1. <span data-ttu-id="46cdd-108">Create a sales order for an item.</span><span class="sxs-lookup"><span data-stu-id="46cdd-108">Create a sales order for an item.</span></span> <span data-ttu-id="46cdd-109">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="46cdd-109">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
2. <span data-ttu-id="46cdd-110">On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.</span><span class="sxs-lookup"><span data-stu-id="46cdd-110">On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.</span></span>

## <a name="to-create-the-purchase-order-for-drop-shipment"></a><span data-ttu-id="46cdd-111">To create the purchase order for drop shipment</span><span class="sxs-lookup"><span data-stu-id="46cdd-111">To create the purchase order for drop shipment</span></span>
<span data-ttu-id="46cdd-112">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span><span class="sxs-lookup"><span data-stu-id="46cdd-112">To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.</span></span>

1. <span data-ttu-id="46cdd-113">Create a purchase order.</span><span class="sxs-lookup"><span data-stu-id="46cdd-113">Create a purchase order.</span></span> <span data-ttu-id="46cdd-114">Do not fill any fields on the lines.</span><span class="sxs-lookup"><span data-stu-id="46cdd-114">Do not fill any fields on the lines.</span></span> <span data-ttu-id="46cdd-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span><span class="sxs-lookup"><span data-stu-id="46cdd-115">For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).</span></span>
2. <span data-ttu-id="46cdd-116">In the **Sell-to Customer No.**</span><span class="sxs-lookup"><span data-stu-id="46cdd-116">In the **Sell-to Customer No.**</span></span> <span data-ttu-id="46cdd-117">field, select the customer that you are selling to.</span><span class="sxs-lookup"><span data-stu-id="46cdd-117">field, select the customer that you are selling to.</span></span>
3. <span data-ttu-id="46cdd-118">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span><span class="sxs-lookup"><span data-stu-id="46cdd-118">Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.</span></span>
4. <span data-ttu-id="46cdd-119">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span><span class="sxs-lookup"><span data-stu-id="46cdd-119">In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.</span></span>
5. <span data-ttu-id="46cdd-120">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="46cdd-120">Choose the **OK** button.</span></span>

<span data-ttu-id="46cdd-121">The line information from the sales order is inserted on the purchase order line(s).</span><span class="sxs-lookup"><span data-stu-id="46cdd-121">The line information from the sales order is inserted on the purchase order line(s).</span></span>

<span data-ttu-id="46cdd-122">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span><span class="sxs-lookup"><span data-stu-id="46cdd-122">You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.</span></span>     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a><span data-ttu-id="46cdd-123">To view the linked purchase order from the sales order</span><span class="sxs-lookup"><span data-stu-id="46cdd-123">To view the linked purchase order from the sales order</span></span>
1. <span data-ttu-id="46cdd-124">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span><span class="sxs-lookup"><span data-stu-id="46cdd-124">Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.</span></span>

<span data-ttu-id="46cdd-125">The linked purchase order opens.</span><span class="sxs-lookup"><span data-stu-id="46cdd-125">The linked purchase order opens.</span></span>

## <a name="to-post-a-drop-shipment"></a><span data-ttu-id="46cdd-126">To post a drop shipment</span><span class="sxs-lookup"><span data-stu-id="46cdd-126">To post a drop shipment</span></span>
<span data-ttu-id="46cdd-127">When the vendor has shipped the items, you can post the sales order as shipped.</span><span class="sxs-lookup"><span data-stu-id="46cdd-127">When the vendor has shipped the items, you can post the sales order as shipped.</span></span> <span data-ttu-id="46cdd-128">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span><span class="sxs-lookup"><span data-stu-id="46cdd-128">You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.</span></span>
1. <span data-ttu-id="46cdd-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="46cdd-129">In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.</span></span>
2. <span data-ttu-id="46cdd-130">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span><span class="sxs-lookup"><span data-stu-id="46cdd-130">Open the sales order that you created in the "To create a sales order for a drop shipment" section.</span></span>
3. <span data-ttu-id="46cdd-131">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span><span class="sxs-lookup"><span data-stu-id="46cdd-131">In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.</span></span>
3. <span data-ttu-id="46cdd-132">Choose the **Post** or **Post and Send** action.</span><span class="sxs-lookup"><span data-stu-id="46cdd-132">Choose the **Post** or **Post and Send** action.</span></span>
4. <span data-ttu-id="46cdd-133">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span><span class="sxs-lookup"><span data-stu-id="46cdd-133">Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.</span></span>

## <a name="see-also"></a><span data-ttu-id="46cdd-134">See Also</span><span class="sxs-lookup"><span data-stu-id="46cdd-134">See Also</span></span>
<span data-ttu-id="46cdd-135">[How to: Sell Products](sales-how-sell-products.md)  </span><span class="sxs-lookup"><span data-stu-id="46cdd-135">[How to: Sell Products](sales-how-sell-products.md)  </span></span>  
[<span data-ttu-id="46cdd-136">How to: Record Purchases</span><span class="sxs-lookup"><span data-stu-id="46cdd-136">How to: Record Purchases</span></span>](purchasing-how-record-purchases.md)  
[<span data-ttu-id="46cdd-137">Manage Sales</span><span class="sxs-lookup"><span data-stu-id="46cdd-137">Manage Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="46cdd-138">[Manage Inventory](inventory-manage-inventory.md)    </span><span class="sxs-lookup"><span data-stu-id="46cdd-138">[Manage Inventory](inventory-manage-inventory.md)    </span></span>  
[<span data-ttu-id="46cdd-139">Work with Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="46cdd-139">Work with Dynamics NAV</span></span>](ui-work-product.md)

