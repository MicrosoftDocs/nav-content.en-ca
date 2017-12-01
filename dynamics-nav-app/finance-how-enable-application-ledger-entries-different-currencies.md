---
title: Apply Entries in Different Currencies
description: You can apply ledger entries in multiple currencies, for example, if you sell in one currency and receive payment in another.
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 2146d80becea5e0c52b04b85aab7890566443be9
ms.contentlocale: en-ca
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a><span data-ttu-id="61752-103">How to: Enable Application of Ledger Entries in Different Currencies</span><span class="sxs-lookup"><span data-stu-id="61752-103">How to: Enable Application of Ledger Entries in Different Currencies</span></span>
<span data-ttu-id="61752-104">If you purchase from a vendor in one currency and submit payment in another currency, you can apply the payment to the purchase.</span><span class="sxs-lookup"><span data-stu-id="61752-104">If you purchase from a vendor in one currency and submit payment in another currency, you can apply the payment to the purchase.</span></span>

<span data-ttu-id="61752-105">Likewise, if you sell to a customer in one currency and receive payment in another currency, you can apply the payment to the sales invoice.</span><span class="sxs-lookup"><span data-stu-id="61752-105">Likewise, if you sell to a customer in one currency and receive payment in another currency, you can apply the payment to the sales invoice.</span></span>

<span data-ttu-id="61752-106">The following procedure describes how to set this up for vendor ledger entries in the **Purchases & Payables Setup** window.</span><span class="sxs-lookup"><span data-stu-id="61752-106">The following procedure describes how to set this up for vendor ledger entries in the **Purchases & Payables Setup** window.</span></span> <span data-ttu-id="61752-107">The setup is similar for customer ledger entries in the **Sales & Receivables Setup** window.</span><span class="sxs-lookup"><span data-stu-id="61752-107">The setup is similar for customer ledger entries in the **Sales & Receivables Setup** window.</span></span>

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a><span data-ttu-id="61752-108">To enable application of vendor ledger entries in different currencies</span><span class="sxs-lookup"><span data-stu-id="61752-108">To enable application of vendor ledger entries in different currencies</span></span>
1. <span data-ttu-id="61752-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="61752-109">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="61752-110">In the **Appln. between Currencies** field, select one of the following options.</span><span class="sxs-lookup"><span data-stu-id="61752-110">In the **Appln. between Currencies** field, select one of the following options.</span></span>

| <span data-ttu-id="61752-111">Option</span><span class="sxs-lookup"><span data-stu-id="61752-111">Option</span></span> | <span data-ttu-id="61752-112">Description</span><span class="sxs-lookup"><span data-stu-id="61752-112">Description</span></span> |
| --- | --- |
| <span data-ttu-id="61752-113">None</span><span class="sxs-lookup"><span data-stu-id="61752-113">None</span></span> |<span data-ttu-id="61752-114">Application between currencies is not allowed.</span><span class="sxs-lookup"><span data-stu-id="61752-114">Application between currencies is not allowed.</span></span> |
| <span data-ttu-id="61752-115">EMU</span><span class="sxs-lookup"><span data-stu-id="61752-115">EMU</span></span> |<span data-ttu-id="61752-116">Application between EMU currencies is allowed.</span><span class="sxs-lookup"><span data-stu-id="61752-116">Application between EMU currencies is allowed.</span></span> |
| <span data-ttu-id="61752-117">All</span><span class="sxs-lookup"><span data-stu-id="61752-117">All</span></span> |<span data-ttu-id="61752-118">Application between all currencies is allowed.</span><span class="sxs-lookup"><span data-stu-id="61752-118">Application between all currencies is allowed.</span></span> |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a><span data-ttu-id="61752-119">To set up G/L accounts for currency application rounding differences</span><span class="sxs-lookup"><span data-stu-id="61752-119">To set up G/L accounts for currency application rounding differences</span></span>  
<span data-ttu-id="61752-120">If you apply entries in different currencies, you must set up the general ledger accounts to which you want to post rounding differences.</span><span class="sxs-lookup"><span data-stu-id="61752-120">If you apply entries in different currencies, you must set up the general ledger accounts to which you want to post rounding differences.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="61752-121">You must set up the general ledger accounts before you complete the task.</span><span class="sxs-lookup"><span data-stu-id="61752-121">You must set up the general ledger accounts before you complete the task.</span></span> <span data-ttu-id="61752-122">For more information, see [Understanding the General Ledger and the Chart of Accounts](finance-general-ledger.md).</span><span class="sxs-lookup"><span data-stu-id="61752-122">For more information, see [Understanding the General Ledger and the Chart of Accounts](finance-general-ledger.md).</span></span>

1. <span data-ttu-id="61752-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer Posting Groups**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="61752-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer Posting Groups**, and then choose the related link.</span></span>  
2. <span data-ttu-id="61752-124">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span><span class="sxs-lookup"><span data-stu-id="61752-124">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  
3. <span data-ttu-id="61752-125">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Posting Groups**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="61752-125">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Posting Groups**, and then choose the related link.</span></span>  
4. <span data-ttu-id="61752-126">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span><span class="sxs-lookup"><span data-stu-id="61752-126">In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.</span></span>  

## <a name="see-also"></a><span data-ttu-id="61752-127">See Also</span><span class="sxs-lookup"><span data-stu-id="61752-127">See Also</span></span>
[<span data-ttu-id="61752-128">Managing Payables</span><span class="sxs-lookup"><span data-stu-id="61752-128">Managing Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="61752-129">Managing Receivables</span><span class="sxs-lookup"><span data-stu-id="61752-129">Managing Receivables</span></span>](receivables-manage-receivables.md)  
<span data-ttu-id="61752-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="61752-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

