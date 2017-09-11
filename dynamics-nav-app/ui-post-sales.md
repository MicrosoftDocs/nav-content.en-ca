---
title: Posting Sales
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: e87dd5faf7713aecfbe7209d00bb8076fcae9d25
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---

# <a name="posting-sales"></a><span data-ttu-id="47cfa-102">Posting Sales</span><span class="sxs-lookup"><span data-stu-id="47cfa-102">Posting Sales</span></span>
<span data-ttu-id="47cfa-103">In the **Posting group** on a sales document, you can choose between the following posting functions:</span><span class="sxs-lookup"><span data-stu-id="47cfa-103">In the **Posting group** on a sales document, you can choose between the following posting functions:</span></span>

- <span data-ttu-id="47cfa-104">**Post**</span><span class="sxs-lookup"><span data-stu-id="47cfa-104">**Post**</span></span>
- <span data-ttu-id="47cfa-105">**Test Report**</span><span class="sxs-lookup"><span data-stu-id="47cfa-105">**Test Report**</span></span>
- <span data-ttu-id="47cfa-106">**Post and Send**</span><span class="sxs-lookup"><span data-stu-id="47cfa-106">**Post and Send**</span></span>
- <span data-ttu-id="47cfa-107">**Post and Print**</span><span class="sxs-lookup"><span data-stu-id="47cfa-107">**Post and Print**</span></span>
- <span data-ttu-id="47cfa-108">**Post and Email**</span><span class="sxs-lookup"><span data-stu-id="47cfa-108">**Post and Email**</span></span>
- <span data-ttu-id="47cfa-109">**Post Batch**</span><span class="sxs-lookup"><span data-stu-id="47cfa-109">**Post Batch**</span></span>
- <span data-ttu-id="47cfa-110">**Preview Posting**</span><span class="sxs-lookup"><span data-stu-id="47cfa-110">**Preview Posting**</span></span>

<span data-ttu-id="47cfa-111">When you have completed all the lines and entered all the information on the sales order, you can post it.</span><span class="sxs-lookup"><span data-stu-id="47cfa-111">When you have completed all the lines and entered all the information on the sales order, you can post it.</span></span> <span data-ttu-id="47cfa-112">This creates a shipment and an invoice.</span><span class="sxs-lookup"><span data-stu-id="47cfa-112">This creates a shipment and an invoice.</span></span>

<span data-ttu-id="47cfa-113">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span><span class="sxs-lookup"><span data-stu-id="47cfa-113">When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.</span></span>

<span data-ttu-id="47cfa-114">For each sales order, a sales entry is created in the **G/L Entry** table.</span><span class="sxs-lookup"><span data-stu-id="47cfa-114">For each sales order, a sales entry is created in the **G/L Entry** table.</span></span> <span data-ttu-id="47cfa-115">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span><span class="sxs-lookup"><span data-stu-id="47cfa-115">An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account.</span></span> <span data-ttu-id="47cfa-116">In addition, posting the order may result in a Tax entry and a general ledger entry for the discount amount.</span><span class="sxs-lookup"><span data-stu-id="47cfa-116">In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount.</span></span> <span data-ttu-id="47cfa-117">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span><span class="sxs-lookup"><span data-stu-id="47cfa-117">Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.</span></span>

<span data-ttu-id="47cfa-118">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span><span class="sxs-lookup"><span data-stu-id="47cfa-118">For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account).</span></span> <span data-ttu-id="47cfa-119">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span><span class="sxs-lookup"><span data-stu-id="47cfa-119">In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.</span></span>

<span data-ttu-id="47cfa-120">**Important**: When you post an order, you can create both a shipment and an invoice.</span><span class="sxs-lookup"><span data-stu-id="47cfa-120">**Important**: When you post an order, you can create both a shipment and an invoice.</span></span> <span data-ttu-id="47cfa-121">These can be done at the same time or independently.</span><span class="sxs-lookup"><span data-stu-id="47cfa-121">These can be done at the same time or independently.</span></span> <span data-ttu-id="47cfa-122">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span><span class="sxs-lookup"><span data-stu-id="47cfa-122">You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post.</span></span> <span data-ttu-id="47cfa-123">Note that you cannot create an invoice for something that is not shipped.</span><span class="sxs-lookup"><span data-stu-id="47cfa-123">Note that you cannot create an invoice for something that is not shipped.</span></span> <span data-ttu-id="47cfa-124">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span><span class="sxs-lookup"><span data-stu-id="47cfa-124">That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time.</span></span> 

<span data-ttu-id="47cfa-125">When the posting is completed, the posted sales lines are removed from the order.</span><span class="sxs-lookup"><span data-stu-id="47cfa-125">When the posting is completed, the posted sales lines are removed from the order.</span></span> <span data-ttu-id="47cfa-126">A message tells you when the posting is completed.</span><span class="sxs-lookup"><span data-stu-id="47cfa-126">A message tells you when the posting is completed.</span></span> <span data-ttu-id="47cfa-127">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span><span class="sxs-lookup"><span data-stu-id="47cfa-127">After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.</span></span>

## <a name="see-also"></a><span data-ttu-id="47cfa-128">See Also</span><span class="sxs-lookup"><span data-stu-id="47cfa-128">See Also</span></span>
[<span data-ttu-id="47cfa-129">How to: Send Documents by Email</span><span class="sxs-lookup"><span data-stu-id="47cfa-129">How to: Send Documents by Email</span></span>](ui-how-send-documents-email.md)

