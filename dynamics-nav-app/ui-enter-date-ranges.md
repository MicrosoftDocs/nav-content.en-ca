---
title: Setting date ranges in Dynamics NAV
description: Learn about getting a report to show data from specific time periods using date ranges in Dynamics NAV.
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: dates, reporting, filter
ms.date: 05/29/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 2773a1ce91ecd8e1216ffd9fdd5c3ceeb490e9e3
ms.contentlocale: en-ca
ms.lasthandoff: 12/01/2017

---
# <a name="entering-date-ranges-in-dynamics-nav"></a><span data-ttu-id="1265c-103">Entering Date Ranges in Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="1265c-103">Entering Date Ranges in Dynamics NAV</span></span>
<span data-ttu-id="1265c-104">You can set filters containing a start date and an end date to display only the data contained in that date range or time interval.</span><span class="sxs-lookup"><span data-stu-id="1265c-104">You can set filters containing a start date and an end date to display only the data contained in that date range or time interval.</span></span> <span data-ttu-id="1265c-105">Special rules apply to the way you set date ranges.</span><span class="sxs-lookup"><span data-stu-id="1265c-105">Special rules apply to the way you set date ranges.</span></span> <span data-ttu-id="1265c-106">Let's take the **Customer Top 10** as an example:</span><span class="sxs-lookup"><span data-stu-id="1265c-106">Let's take the **Customer Top 10** as an example:</span></span>

![Setting a date range in the request page for the Customer Top 10 list](./media/ui-enter-date-ranges/customer-top10-list.png)

<span data-ttu-id="1265c-108">Here you can limit the report to a date range such as the past 2 weeks, or a total of 6 weeks, or whatever range you want.</span><span class="sxs-lookup"><span data-stu-id="1265c-108">Here you can limit the report to a date range such as the past 2 weeks, or a total of 6 weeks, or whatever range you want.</span></span> <span data-ttu-id="1265c-109">To set date ranges, you enter dates and then use either **..**</span><span class="sxs-lookup"><span data-stu-id="1265c-109">To set date ranges, you enter dates and then use either **..**</span></span> <span data-ttu-id="1265c-110">or **|** to set the range.</span><span class="sxs-lookup"><span data-stu-id="1265c-110">or **|** to set the range.</span></span> <span data-ttu-id="1265c-111">In our example, to show the top 10 customers for the first two weeks of May, you would set the date filter to *05 01 17..05 14 17*.</span><span class="sxs-lookup"><span data-stu-id="1265c-111">In our example, to show the top 10 customers for the first two weeks of May, you would set the date filter to *05 01 17..05 14 17*.</span></span>
<span data-ttu-id="1265c-112">Here are a couple of other examples:</span><span class="sxs-lookup"><span data-stu-id="1265c-112">Here are a couple of other examples:</span></span>

| <span data-ttu-id="1265c-113">Meaning</span><span class="sxs-lookup"><span data-stu-id="1265c-113">Meaning</span></span> | <span data-ttu-id="1265c-114">Example</span><span class="sxs-lookup"><span data-stu-id="1265c-114">Example</span></span> | <span data-ttu-id="1265c-115">Entries included</span><span class="sxs-lookup"><span data-stu-id="1265c-115">Entries included</span></span> |
|---|---|---|
|<span data-ttu-id="1265c-116">Equal to</span><span class="sxs-lookup"><span data-stu-id="1265c-116">Equal to</span></span>| <span data-ttu-id="1265c-117">12 15 16</span><span class="sxs-lookup"><span data-stu-id="1265c-117">12 15 16</span></span> |<span data-ttu-id="1265c-118">Only those posted on December 15 2016.</span><span class="sxs-lookup"><span data-stu-id="1265c-118">Only those posted on December 15 2016.</span></span>|
|<span data-ttu-id="1265c-119">Interval</span><span class="sxs-lookup"><span data-stu-id="1265c-119">Interval</span></span>| <span data-ttu-id="1265c-120">12 15 16..01 15 17</span><span class="sxs-lookup"><span data-stu-id="1265c-120">12 15 16..01 15 17</span></span><br /><br /><span data-ttu-id="1265c-121">..12 15 16</span><span class="sxs-lookup"><span data-stu-id="1265c-121">..12 15 16</span></span>|<span data-ttu-id="1265c-122">Those posted on dates between and including December 15 2016 and January 15 2017.</span><span class="sxs-lookup"><span data-stu-id="1265c-122">Those posted on dates between and including December 15 2016 and January 15 2017.</span></span><br /><br /><span data-ttu-id="1265c-123">Those posted on December 15 2016 or earlier.</span><span class="sxs-lookup"><span data-stu-id="1265c-123">Those posted on December 15 2016 or earlier.</span></span>|
|<span data-ttu-id="1265c-124">Either/or</span><span class="sxs-lookup"><span data-stu-id="1265c-124">Either/or</span></span>|<span data-ttu-id="1265c-125">12 15 16&#124;12 16 16</span><span class="sxs-lookup"><span data-stu-id="1265c-125">12 15 16&#124;12 16 16</span></span>|<span data-ttu-id="1265c-126">Those posted on either December 15 or December 16 2016.</span><span class="sxs-lookup"><span data-stu-id="1265c-126">Those posted on either December 15 or December 16 2016.</span></span> <span data-ttu-id="1265c-127">If there are entries posted on both days, they will all be displayed.</span><span class="sxs-lookup"><span data-stu-id="1265c-127">If there are entries posted on both days, they will all be displayed.</span></span>|

<span data-ttu-id="1265c-128">You can also combine the various format types.</span><span class="sxs-lookup"><span data-stu-id="1265c-128">You can also combine the various format types.</span></span>

| <span data-ttu-id="1265c-129">Example</span><span class="sxs-lookup"><span data-stu-id="1265c-129">Example</span></span> | <span data-ttu-id="1265c-130">Entries included</span><span class="sxs-lookup"><span data-stu-id="1265c-130">Entries included</span></span> |
|---|---|
|<span data-ttu-id="1265c-131">12 15 16&#124;12 01 16..05 31 17</span><span class="sxs-lookup"><span data-stu-id="1265c-131">12 15 16&#124;12 01 16..05 31 17</span></span> | <span data-ttu-id="1265c-132">Entries posted either on December 15 2016 or on dates between and including December 01 2016 and May 31 2017.</span><span class="sxs-lookup"><span data-stu-id="1265c-132">Entries posted either on December 15 2016 or on dates between and including December 01 2016 and May 31 2017.</span></span> |
|<span data-ttu-id="1265c-133">..12 14 16&#124;12 30 16..</span><span class="sxs-lookup"><span data-stu-id="1265c-133">..12 14 16&#124;12 30 16..</span></span> | <span data-ttu-id="1265c-134">Entries posted on December 14 or earlier, or entries posted on December 30 or later - that is, all entries except those posted on dates between and including December 15 and 29.</span><span class="sxs-lookup"><span data-stu-id="1265c-134">Entries posted on December 14 or earlier, or entries posted on December 30 or later - that is, all entries except those posted on dates between and including December 15 and 29.</span></span> |

<span data-ttu-id="1265c-135">Note that we have used the US date format MMDDYY here.</span><span class="sxs-lookup"><span data-stu-id="1265c-135">Note that we have used the US date format MMDDYY here.</span></span> <span data-ttu-id="1265c-136">As [!INCLUDE[d365fin](includes/d365fin_md.md)] becomes available in other markets, you'll be able to use the formats that you are used to.</span><span class="sxs-lookup"><span data-stu-id="1265c-136">As [!INCLUDE[d365fin](includes/d365fin_md.md)] becomes available in other markets, you'll be able to use the formats that you are used to.</span></span>

## <a name="see-also"></a><span data-ttu-id="1265c-137">See Also</span><span class="sxs-lookup"><span data-stu-id="1265c-137">See Also</span></span>
<span data-ttu-id="1265c-138">[Working with [!INCLUDE[d365fin](includes/d365fin_long_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="1265c-138">[Working with [!INCLUDE[d365fin](includes/d365fin_long_md.md)]](ui-work-product.md)</span></span>  
[<span data-ttu-id="1265c-139">Entering Criteria in Filters</span><span class="sxs-lookup"><span data-stu-id="1265c-139">Entering Criteria in Filters </span></span>](ui-enter-criteria-filters.md)  
[<span data-ttu-id="1265c-140">General Business Functionality</span><span class="sxs-lookup"><span data-stu-id="1265c-140">General Business Functionality</span></span>](ui-across-business-areas.md)

