---
title: Close Periods
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: ac1ed2d1dcf8bf780bda91fbf0a04e5c5e8d106a
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---
# <a name="close-periods"></a><span data-ttu-id="796be-102">Close Periods</span><span class="sxs-lookup"><span data-stu-id="796be-102">Close Periods</span></span>
<span data-ttu-id="796be-103">The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want.</span><span class="sxs-lookup"><span data-stu-id="796be-103">The application does not force you to close periods, however, there are many period-end (month-end) activities that can be performed in the application if you want.</span></span> <span data-ttu-id="796be-104">This topic provides an overview of these processes and activities, which may or may not be necessary for your company.</span><span class="sxs-lookup"><span data-stu-id="796be-104">This topic provides an overview of these processes and activities, which may or may not be necessary for your company.</span></span>

## <a name="general-ledger"></a><span data-ttu-id="796be-105">General Ledger</span><span class="sxs-lookup"><span data-stu-id="796be-105">General Ledger</span></span>
* <span data-ttu-id="796be-106">Specify system-wide and user-specific posting period.</span><span class="sxs-lookup"><span data-stu-id="796be-106">Specify system-wide and user-specific posting period.</span></span>

    <span data-ttu-id="796be-107">This specifies the dates between which postings are allowed.</span><span class="sxs-lookup"><span data-stu-id="796be-107">This specifies the dates between which postings are allowed.</span></span> <span data-ttu-id="796be-108">Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period.</span><span class="sxs-lookup"><span data-stu-id="796be-108">Depending on your business needs, you may want to restrict user posting date ranges at the start of the period-end process or at later time towards the end of the period.</span></span> <span data-ttu-id="796be-109">For more information, see [How to: Specify Posting Periods](finance-setup-how-specify-posting-periods.md).</span><span class="sxs-lookup"><span data-stu-id="796be-109">For more information, see [How to: Specify Posting Periods](finance-setup-how-specify-posting-periods.md).</span></span>
* <span data-ttu-id="796be-110">Make all necessary G/L adjustments.</span><span class="sxs-lookup"><span data-stu-id="796be-110">Make all necessary G/L adjustments.</span></span>
* <span data-ttu-id="796be-111">Update and post Recurring Journals.</span><span class="sxs-lookup"><span data-stu-id="796be-111">Update and post Recurring Journals.</span></span>
<!--* Process Consolidations-->
* <span data-ttu-id="796be-112">Run account schedules as follows:</span><span class="sxs-lookup"><span data-stu-id="796be-112">Run account schedules as follows:</span></span>
  1. <span data-ttu-id="796be-113">Open the **Account Schedule** window, and choose the **Print** action.</span><span class="sxs-lookup"><span data-stu-id="796be-113">Open the **Account Schedule** window, and choose the **Print** action.</span></span>
  2. <span data-ttu-id="796be-114">Fill the **Account Schedule** request window and choose the **Print** action.</span><span class="sxs-lookup"><span data-stu-id="796be-114">Fill the **Account Schedule** request window and choose the **Print** action.</span></span>

## <a name="sales--receivables"></a><span data-ttu-id="796be-115">Sales & Receivables</span><span class="sxs-lookup"><span data-stu-id="796be-115">Sales & Receivables</span></span>
* <span data-ttu-id="796be-116">Post all sales orders, invoices, credit memos, and return orders.</span><span class="sxs-lookup"><span data-stu-id="796be-116">Post all sales orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="796be-117">Post all cash receipt journals.</span><span class="sxs-lookup"><span data-stu-id="796be-117">Post all cash receipt journals.</span></span>
* <span data-ttu-id="796be-118">Update and post recurring journals that are related to Sales & Receivables.</span><span class="sxs-lookup"><span data-stu-id="796be-118">Update and post recurring journals that are related to Sales & Receivables.</span></span>
* <span data-ttu-id="796be-119">Reconcile accounts receivable to the general ledger.</span><span class="sxs-lookup"><span data-stu-id="796be-119">Reconcile accounts receivable to the general ledger.</span></span>
* <span data-ttu-id="796be-120">Run the **Delete Invoiced Sales Orders** batch job.</span><span class="sxs-lookup"><span data-stu-id="796be-120">Run the **Delete Invoiced Sales Orders** batch job.</span></span>

## <a name="purchases--payables"></a><span data-ttu-id="796be-121">Purchases & Payables</span><span class="sxs-lookup"><span data-stu-id="796be-121">Purchases & Payables</span></span>
* <span data-ttu-id="796be-122">Post all purchase orders, invoices, credit memos, and return orders.</span><span class="sxs-lookup"><span data-stu-id="796be-122">Post all purchase orders, invoices, credit memos, and return orders.</span></span>
* <span data-ttu-id="796be-123">Post all payment journals.</span><span class="sxs-lookup"><span data-stu-id="796be-123">Post all payment journals.</span></span>
* <span data-ttu-id="796be-124">Update and post recurring journals that are related to purchases & payables.</span><span class="sxs-lookup"><span data-stu-id="796be-124">Update and post recurring journals that are related to purchases & payables.</span></span>
* <span data-ttu-id="796be-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span><span class="sxs-lookup"><span data-stu-id="796be-125">Run the **Aged Accounts Payable** report and reconcile accounts payable to the general ledger.</span></span>
* <span data-ttu-id="796be-126">Run the **Delete Invoiced Purchase Orders** batch job.</span><span class="sxs-lookup"><span data-stu-id="796be-126">Run the **Delete Invoiced Purchase Orders** batch job.</span></span>

<!-- ### Fixed Assets
* Post all maintenance costs have been posted through the fixed asset journals or invoices.
* Post adjustments.
* Post appreciation.
* Post depreciation.
* Update and post the recurring fixed asset journal.-->

<!--### Intercompany
* Process Intercompany Postings.-->

## <a name="calculate-and-process-sales-tax"></a><span data-ttu-id="796be-127">Calculate and Process Sales Tax</span><span class="sxs-lookup"><span data-stu-id="796be-127">Calculate and Process Sales Tax</span></span>
*  <span data-ttu-id="796be-128">Complete Tax Statements.</span><span class="sxs-lookup"><span data-stu-id="796be-128">Complete Tax Statements.</span></span>

## <a name="see-also"></a><span data-ttu-id="796be-129">See Also</span><span class="sxs-lookup"><span data-stu-id="796be-129">See Also</span></span>
[<span data-ttu-id="796be-130">Closing Years and Periods</span><span class="sxs-lookup"><span data-stu-id="796be-130">Closing Years and Periods</span></span>](year-close-years-periods.md)  
[<span data-ttu-id="796be-131">Close Books</span><span class="sxs-lookup"><span data-stu-id="796be-131">Close Books</span></span>](year-close-books.md)

