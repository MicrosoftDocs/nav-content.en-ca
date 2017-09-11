---
title: 'How to: Record Sales Prices and Discounts'
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
ms.openlocfilehash: 80a0ac1edc994f44795f7f907a647b269578bc47
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a><span data-ttu-id="886f6-102">How to: Record Sales Prices and Discounts</span><span class="sxs-lookup"><span data-stu-id="886f6-102">How to: Record Sales Prices and Discounts</span></span>
<span data-ttu-id="886f6-103">The different price and discount agreements that apply when selling to different customers must be defined so that the agreed rules and values are applied to sales documents that you create for the customers.</span><span class="sxs-lookup"><span data-stu-id="886f6-103">The different price and discount agreements that apply when selling to different customers must be defined so that the agreed rules and values are applied to sales documents that you create for the customers.</span></span>

<span data-ttu-id="886f6-104">Concerning prices, you can have a special sales price inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span><span class="sxs-lookup"><span data-stu-id="886f6-104">Concerning prices, you can have a special sales price inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span>

<span data-ttu-id="886f6-105">Concerning discounts, you can set up and use two types of sales discounts:</span><span class="sxs-lookup"><span data-stu-id="886f6-105">Concerning discounts, you can set up and use two types of sales discounts:</span></span>

|<span data-ttu-id="886f6-106">Discount Type</span><span class="sxs-lookup"><span data-stu-id="886f6-106">Discount Type</span></span> |<span data-ttu-id="886f6-107">Description</span><span class="sxs-lookup"><span data-stu-id="886f6-107">Description</span></span> |
|--------------|------------|
|<span data-ttu-id="886f6-108">**Sales Line Discount**</span><span class="sxs-lookup"><span data-stu-id="886f6-108">**Sales Line Discount**</span></span>|<span data-ttu-id="886f6-109">An amount discount that is inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span><span class="sxs-lookup"><span data-stu-id="886f6-109">An amount discount that is inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.</span></span> <span data-ttu-id="886f6-110">This works in the same way as for sales prices.</span><span class="sxs-lookup"><span data-stu-id="886f6-110">This works in the same way as for sales prices.</span></span>|
|<span data-ttu-id="886f6-111">**Invoice Discount**</span><span class="sxs-lookup"><span data-stu-id="886f6-111">**Invoice Discount**</span></span>|<span data-ttu-id="886f6-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a sales document exceeds a certain minimum.</span><span class="sxs-lookup"><span data-stu-id="886f6-112">A percentage discount that is subtracted from the document total if the value amount of all lines on a sales document exceeds a certain minimum.</span></span>|

<span data-ttu-id="886f6-113">Because sales prices and sales line discounts are based on a combination of item and customer, you can also perform this configuration from the item card of the item where the rules and values apply.</span><span class="sxs-lookup"><span data-stu-id="886f6-113">Because sales prices and sales line discounts are based on a combination of item and customer, you can also perform this configuration from the item card of the item where the rules and values apply.</span></span>

## <a name="to-set-up-a-sales-price-for-a-customer"></a><span data-ttu-id="886f6-114">To set up a sales price for a customer</span><span class="sxs-lookup"><span data-stu-id="886f6-114">To set up a sales price for a customer</span></span>
1. <span data-ttu-id="886f6-115">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="886f6-115">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="886f6-116">Open the relevant customer card, and then choose the **Prices** action.</span><span class="sxs-lookup"><span data-stu-id="886f6-116">Open the relevant customer card, and then choose the **Prices** action.</span></span>

    <span data-ttu-id="886f6-117">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span><span class="sxs-lookup"><span data-stu-id="886f6-117">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3. <span data-ttu-id="886f6-118">Fill in the fields on the line as necessary.</span><span class="sxs-lookup"><span data-stu-id="886f6-118">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="886f6-119">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="886f6-119">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="886f6-120">Fill a line for each combination that will grant a special sales price to the customer.</span><span class="sxs-lookup"><span data-stu-id="886f6-120">Fill a line for each combination that will grant a special sales price to the customer.</span></span>

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a><span data-ttu-id="886f6-121">To set up a sales line discount for a customer</span><span class="sxs-lookup"><span data-stu-id="886f6-121">To set up a sales line discount for a customer</span></span>
1. <span data-ttu-id="886f6-122">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="886f6-122">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="886f6-123">Open the relevant customer card, and then choose the **Line Discounts** action.</span><span class="sxs-lookup"><span data-stu-id="886f6-123">Open the relevant customer card, and then choose the **Line Discounts** action.</span></span>

    <span data-ttu-id="886f6-124">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span><span class="sxs-lookup"><span data-stu-id="886f6-124">The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.</span></span>
3.  <span data-ttu-id="886f6-125">Fill in the fields on the line as necessary.</span><span class="sxs-lookup"><span data-stu-id="886f6-125">Fill in the fields on the line as necessary.</span></span> <span data-ttu-id="886f6-126">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="886f6-126">Choose a field to read a short description of the field or link to more information.</span></span>
4. <span data-ttu-id="886f6-127">Fill a line for each combination that will grant a sales line discount to the customer.</span><span class="sxs-lookup"><span data-stu-id="886f6-127">Fill a line for each combination that will grant a sales line discount to the customer.</span></span>

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a><span data-ttu-id="886f6-128">To set up an invoice discount for a customer</span><span class="sxs-lookup"><span data-stu-id="886f6-128">To set up an invoice discount for a customer</span></span>
<span data-ttu-id="886f6-129">When you have decided which customers are eligible for invoice discounts, enter the invoice discount code on the customer cards and set up the terms for each code.</span><span class="sxs-lookup"><span data-stu-id="886f6-129">When you have decided which customers are eligible for invoice discounts, enter the invoice discount code on the customer cards and set up the terms for each code.</span></span>

1. <span data-ttu-id="886f6-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="886f6-130">In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.</span></span>
2. <span data-ttu-id="886f6-131">Open the customer card for a customer that will be eligible for invoice discounts.</span><span class="sxs-lookup"><span data-stu-id="886f6-131">Open the customer card for a customer that will be eligible for invoice discounts.</span></span>
3. <span data-ttu-id="886f6-132">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the customer.</span><span class="sxs-lookup"><span data-stu-id="886f6-132">In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the customer.</span></span>

    <span data-ttu-id="886f6-133">**Note**: Invoice discount codes are represented by existing customer cards.</span><span class="sxs-lookup"><span data-stu-id="886f6-133">**Note**: Invoice discount codes are represented by existing customer cards.</span></span> <span data-ttu-id="886f6-134">This enables you to quickly assign invoice discount terms to customers by picking the name of another customer who will have the same terms.</span><span class="sxs-lookup"><span data-stu-id="886f6-134">This enables you to quickly assign invoice discount terms to customers by picking the name of another customer who will have the same terms.</span></span>

    <span data-ttu-id="886f6-135">Proceed to set up new the sales invoice discount terms.</span><span class="sxs-lookup"><span data-stu-id="886f6-135">Proceed to set up new the sales invoice discount terms.</span></span>
4. <span data-ttu-id="886f6-136">In the **Customer Card** window, choose the **Invoice Discounts** action.</span><span class="sxs-lookup"><span data-stu-id="886f6-136">In the **Customer Card** window, choose the **Invoice Discounts** action.</span></span> <span data-ttu-id="886f6-137">The **Cust. Invoice Discounts** window opens.</span><span class="sxs-lookup"><span data-stu-id="886f6-137">The **Cust. Invoice Discounts** window opens.</span></span>
5. <span data-ttu-id="886f6-138">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span><span class="sxs-lookup"><span data-stu-id="886f6-138">In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to.</span></span> <span data-ttu-id="886f6-139">Leave the field blank to set up invoice discount terms in CAD.</span><span class="sxs-lookup"><span data-stu-id="886f6-139">Leave the field blank to set up invoice discount terms in USD.</span></span>
6. <span data-ttu-id="886f6-140">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span><span class="sxs-lookup"><span data-stu-id="886f6-140">In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.</span></span>
7. <span data-ttu-id="886f6-141">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span><span class="sxs-lookup"><span data-stu-id="886f6-141">In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.</span></span>
8. <span data-ttu-id="886f6-142">Repeat steps 5 through 7 for each currency that the customer will receive a different invoice discount for.</span><span class="sxs-lookup"><span data-stu-id="886f6-142">Repeat steps 5 through 7 for each currency that the customer will receive a different invoice discount for.</span></span>

<span data-ttu-id="886f6-143">The invoice discount is now set up and assigned to the customer in question.</span><span class="sxs-lookup"><span data-stu-id="886f6-143">The invoice discount is now set up and assigned to the customer in question.</span></span> <span data-ttu-id="886f6-144">When you select the customer code in the **Invoice Disc. Code** field on other customer cards, the same invoice discount is assigned to those customers.</span><span class="sxs-lookup"><span data-stu-id="886f6-144">When you select the customer code in the **Invoice Disc. Code** field on other customer cards, the same invoice discount is assigned to those customers.</span></span>

## <a name="see-also"></a><span data-ttu-id="886f6-145">See Also</span><span class="sxs-lookup"><span data-stu-id="886f6-145">See Also</span></span>  
[<span data-ttu-id="886f6-146">Set Up Sales</span><span class="sxs-lookup"><span data-stu-id="886f6-146">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="886f6-147">Manage Sales</span><span class="sxs-lookup"><span data-stu-id="886f6-147">Manage Sales</span></span>](sales-manage-sales.md)

