---
title: Entering Criteria in Filters
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
ms.openlocfilehash: df386e1195db385ee053b69fec0f5082d8df4116
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---

# <a name="entering-criteria-in-filters"></a><span data-ttu-id="f0883-102">Entering Criteria in Filters</span><span class="sxs-lookup"><span data-stu-id="f0883-102">Entering Criteria in Filters</span></span>
<span data-ttu-id="f0883-103">When you want to search for data, such as customer names, addresses, or product groups, you enter criteria.</span><span class="sxs-lookup"><span data-stu-id="f0883-103">When you want to search for data, such as customer names, addresses, or product groups, you enter criteria.</span></span> <span data-ttu-id="f0883-104">In search criteria you can use all the numbers and letters that you normally use in the specific field.</span><span class="sxs-lookup"><span data-stu-id="f0883-104">In search criteria you can use all the numbers and letters that you normally use in the specific field.</span></span> <span data-ttu-id="f0883-105">In addition, you can use special symbols to further filter the results.</span><span class="sxs-lookup"><span data-stu-id="f0883-105">In addition, you can use special symbols to further filter the results.</span></span>

## <a name="searching-using-the-quick-filter"></a><span data-ttu-id="f0883-106">Searching using the Quick Filter</span><span class="sxs-lookup"><span data-stu-id="f0883-106">Searching using the Quick Filter</span></span>
<span data-ttu-id="f0883-107">You can add filters to all pages by using the Quick Filter.</span><span class="sxs-lookup"><span data-stu-id="f0883-107">You can add filters to all pages by using the Quick Filter.</span></span> <span data-ttu-id="f0883-108">The Quick Filter is enabled by choosing the magnifier icon in the top right corner of a page.</span><span class="sxs-lookup"><span data-stu-id="f0883-108">The Quick Filter is enabled by choosing the magnifier icon in the top right corner of a page.</span></span> <span data-ttu-id="f0883-109">This filtering type is used for a fast entry of criteria.</span><span class="sxs-lookup"><span data-stu-id="f0883-109">This filtering type is used for a fast entry of criteria.</span></span>

<span data-ttu-id="f0883-110">**Important**: The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options.</span><span class="sxs-lookup"><span data-stu-id="f0883-110">**Important**: The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options.</span></span> <span data-ttu-id="f0883-111">Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.</span><span class="sxs-lookup"><span data-stu-id="f0883-111">Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.</span></span>  
- <span data-ttu-id="f0883-112">If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.</span><span class="sxs-lookup"><span data-stu-id="f0883-112">If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.</span></span>  
- <span data-ttu-id="f0883-113">If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive.</span><span class="sxs-lookup"><span data-stu-id="f0883-113">If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive.</span></span>

### <a name="quick-filter-criteria"></a><span data-ttu-id="f0883-114">Quick filter criteria</span><span class="sxs-lookup"><span data-stu-id="f0883-114">Quick filter criteria</span></span>
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH><span data-ttu-id="f0883-115">Search Criteria</span><span class="sxs-lookup"><span data-stu-id="f0883-115">Search Criteria</span></span></TH>
    <TH><span data-ttu-id="f0883-116">Interpreted as...</span><span class="sxs-lookup"><span data-stu-id="f0883-116">Interpreted as...</span></span></TH>
    <TH><span data-ttu-id="f0883-117">Returns...</span><span class="sxs-lookup"><span data-stu-id="f0883-117">Returns...</span></span></TH>
  </TR>
  <TR>
    <TD><span data-ttu-id="f0883-118">>man</span><span class="sxs-lookup"><span data-stu-id="f0883-118">>man</span></span></TD>
    <TD><span data-ttu-id="f0883-119">@*man*</span><span class="sxs-lookup"><span data-stu-id="f0883-119">@*man*</span></span></TD>
    <TD><span data-ttu-id="f0883-120">All records that contain the text man and case insensitive.</span><span class="sxs-lookup"><span data-stu-id="f0883-120">All records that contain the text man and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="f0883-121">>se</span><span class="sxs-lookup"><span data-stu-id="f0883-121">>se</span></span></TD>
    <TD><span data-ttu-id="f0883-122">@*se*</span><span class="sxs-lookup"><span data-stu-id="f0883-122">@*se*</span></span></TD>
    <TD><span data-ttu-id="f0883-123">All records that contain the text se and case insensitive.</span><span class="sxs-lookup"><span data-stu-id="f0883-123">All records that contain the text se and case insensitive.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="f0883-124">>Man*</span><span class="sxs-lookup"><span data-stu-id="f0883-124">>Man*</span></span></TD>
    <TD><span data-ttu-id="f0883-125">Starts with Man and case sensitive.</span><span class="sxs-lookup"><span data-stu-id="f0883-125">Starts with Man and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="f0883-126">All records that start with the text Man.</span><span class="sxs-lookup"><span data-stu-id="f0883-126">All records that start with the text Man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="f0883-127">'man'</span><span class="sxs-lookup"><span data-stu-id="f0883-127">'man'</span></span></TD>
    <TD><span data-ttu-id="f0883-128">An exact text and case sensitive.</span><span class="sxs-lookup"><span data-stu-id="f0883-128">An exact text and case sensitive.</span></span></TD>
    <TD><span data-ttu-id="f0883-129">All records that match man exactly.</span><span class="sxs-lookup"><span data-stu-id="f0883-129">All records that match man exactly.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="f0883-130">@*man</span><span class="sxs-lookup"><span data-stu-id="f0883-130">@*man</span></span></TD>
    <TD><span data-ttu-id="f0883-131">Ends with and case insensitive.</span><span class="sxs-lookup"><span data-stu-id="f0883-131">Ends with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="f0883-132">All records that end with man.</span><span class="sxs-lookup"><span data-stu-id="f0883-132">All records that end with man.</span></span></TD>
  </TR>
  <TR>
    <TD><span data-ttu-id="f0883-133">@man*</span><span class="sxs-lookup"><span data-stu-id="f0883-133">@man*</span></span></TD>
    <TD><span data-ttu-id="f0883-134">Starts with and case insensitive.</span><span class="sxs-lookup"><span data-stu-id="f0883-134">Starts with and case insensitive.</span></span></TD>
    <TD><span data-ttu-id="f0883-135">All records that start with man.</span><span class="sxs-lookup"><span data-stu-id="f0883-135">All records that start with man.</span></span></TD>
  </TR>
</TABLE>

<span data-ttu-id="f0883-136">**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders.</span><span class="sxs-lookup"><span data-stu-id="f0883-136">**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders.</span></span> <span data-ttu-id="f0883-137">To enter a filter for this type of field, you can enter the numeric value as a filtering parameter.</span><span class="sxs-lookup"><span data-stu-id="f0883-137">To enter a filter for this type of field, you can enter the numeric value as a filtering parameter.</span></span> <span data-ttu-id="f0883-138">For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.</span><span class="sxs-lookup"><span data-stu-id="f0883-138">For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.</span></span>  

## <a name="see-also"></a><span data-ttu-id="f0883-139">See Also</span><span class="sxs-lookup"><span data-stu-id="f0883-139">See Also</span></span>
[<span data-ttu-id="f0883-140">Work with Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="f0883-140">Work with Dynamics NAV</span></span>](ui-work-product.md)

