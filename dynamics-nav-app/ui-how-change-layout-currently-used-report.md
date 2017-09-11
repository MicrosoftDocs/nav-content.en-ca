---
title: 'How to: Change Which Layout is Currently Used on a Report'
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
ms.openlocfilehash: a97caf4b123ffcb21099d73044370bcb20ea1750
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-change-which-layout-is-currently-used-on-a-report"></a><span data-ttu-id="98073-102">How to: Change Which Layout is Currently Used on a Report</span><span class="sxs-lookup"><span data-stu-id="98073-102">How to: Change Which Layout is Currently Used on a Report</span></span>
<span data-ttu-id="98073-103">A report can be set up with more than one report layout, which you can then switch among as needed.</span><span class="sxs-lookup"><span data-stu-id="98073-103">A report can be set up with more than one report layout, which you can then switch among as needed.</span></span>

<span data-ttu-id="98073-104">Depending on the layouts that are available for a report, you can choose to use a built-in RDLC report layout, a built-in Word report layout, or a custom layout.</span><span class="sxs-lookup"><span data-stu-id="98073-104">Depending on the layouts that are available for a report, you can choose to use a built-in RDLC report layout, a built-in Word report layout, or a custom layout.</span></span> <span data-ttu-id="98073-105">For more information about RDLC and Word report layouts, built-in and custom layouts, and more, see [Manage Report Layouts](ui-manage-report-layouts.md).</span><span class="sxs-lookup"><span data-stu-id="98073-105">For more information about RDLC and Word report layouts, built-in and custom layouts, and more, see [Manage Report Layouts](ui-manage-report-layouts.md).</span></span>

## <a name="to-change-the-layout-that-is-used-on-a-report"></a><span data-ttu-id="98073-106">To change the layout that is used on a report</span><span class="sxs-lookup"><span data-stu-id="98073-106">To change the layout that is used on a report</span></span>
1. <span data-ttu-id="98073-107">In the top right corner, choose the **Search for Page or Report** icon, enter **Report Layout Selection**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="98073-107">In the top right corner, choose the **Search for Page or Report** icon, enter **Report Layout Selection**, and then choose the related link.</span></span>  
<span data-ttu-id="98073-108">The **Report Layout Selection** window lists all the reports that are available for the company that is specified in the Company field at the top of the window.</span><span class="sxs-lookup"><span data-stu-id="98073-108">The **Report Layout Selection** window lists all the reports that are available for the company that is specified in the Company field at the top of the window.</span></span> <span data-ttu-id="98073-109">The Selected Layout field specifies the layout that is currently used on the report.</span><span class="sxs-lookup"><span data-stu-id="98073-109">The Selected Layout field specifies the layout that is currently used on the report.</span></span>
2. <span data-ttu-id="98073-110">Set the **Company** field at the top of the window to the company that includes the report.</span><span class="sxs-lookup"><span data-stu-id="98073-110">Set the **Company** field at the top of the window to the company that includes the report.</span></span>
3. <span data-ttu-id="98073-111">To change the layout that is used by a report, in the row for the report in the list, set the **Selected Layout** field to one of the following options:</span><span class="sxs-lookup"><span data-stu-id="98073-111">To change the layout that is used by a report, in the row for the report in the list, set the **Selected Layout** field to one of the following options:</span></span>
    - <span data-ttu-id="98073-112">RDLC (built-in), uses the built-in RDLC report layout on the report.</span><span class="sxs-lookup"><span data-stu-id="98073-112">RDLC (built-in), uses the built-in RDLC report layout on the report.</span></span>
    - <span data-ttu-id="98073-113">Word (built-in), uses the built-in Word report layout on the report.</span><span class="sxs-lookup"><span data-stu-id="98073-113">Word (built-in), uses the built-in Word report layout on the report.</span></span>
    - <span data-ttu-id="98073-114">Custom, uses a custom layout on the report.</span><span class="sxs-lookup"><span data-stu-id="98073-114">Custom, uses a custom layout on the report.</span></span>  
    <span data-ttu-id="98073-115">You can see which custom layouts are available for the report in the Report Layouts Part FactBox.</span><span class="sxs-lookup"><span data-stu-id="98073-115">You can see which custom layouts are available for the report in the Report Layouts Part FactBox.</span></span> <span data-ttu-id="98073-116">If there are no custom layouts for the report, then you will have to create one first.</span><span class="sxs-lookup"><span data-stu-id="98073-116">If there are no custom layouts for the report, then you will have to create one first.</span></span> <span data-ttu-id="98073-117">If you choose this option, go to the next procedure to specify the custom layout that you want to use.</span><span class="sxs-lookup"><span data-stu-id="98073-117">If you choose this option, go to the next procedure to specify the custom layout that you want to use.</span></span>
<span data-ttu-id="98073-118">**Note**: If you choose **RDLC (built-in)** or **Word (built-in)** and you get an error message that the report does not have a layout of the specified type, then you must choose another layout option or create a custom report layout of the type that you want to use.</span><span class="sxs-lookup"><span data-stu-id="98073-118">**Note**: If you choose **RDLC (built-in)** or **Word (built-in)** and you get an error message that the report does not have a layout of the specified type, then you must choose another layout option or create a custom report layout of the type that you want to use.</span></span>

<span data-ttu-id="98073-119">If you selected a built-in RDLC or Word report layout, then no further action is required and the layout will be used the next time the report is run.</span><span class="sxs-lookup"><span data-stu-id="98073-119">If you selected a built-in RDLC or Word report layout, then no further action is required and the layout will be used the next time the report is run.</span></span>

## <a name="to-specify-a-custom-layout-on-a-report"></a><span data-ttu-id="98073-120">To specify a custom layout on a report</span><span class="sxs-lookup"><span data-stu-id="98073-120">To specify a custom layout on a report</span></span>
1. <span data-ttu-id="98073-121">You specify which custom layout to use on the report from the **Custom Report Layouts** window.</span><span class="sxs-lookup"><span data-stu-id="98073-121">You specify which custom layout to use on the report from the **Custom Report Layouts** window.</span></span> <span data-ttu-id="98073-122">If the **Custom Report Layouts** window is not open, then in the **Report Layout Description** field, choose the lookup button.</span><span class="sxs-lookup"><span data-stu-id="98073-122">If the **Custom Report Layouts** window is not open, then in the **Report Layout Description** field, choose the lookup button.</span></span>
2. <span data-ttu-id="98073-123">In the **Custom Report Layouts** window, select the row for custom layout that you want to use, and then choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="98073-123">In the **Custom Report Layouts** window, select the row for custom layout that you want to use, and then choose the **OK** button.</span></span>

<span data-ttu-id="98073-124">You return to the **Report Layout Selection** window.</span><span class="sxs-lookup"><span data-stu-id="98073-124">You return to the **Report Layout Selection** window.</span></span> <span data-ttu-id="98073-125">The name of the selected custom layout displays in the **Custom Layout Description** field.</span><span class="sxs-lookup"><span data-stu-id="98073-125">The name of the selected custom layout displays in the **Custom Layout Description** field.</span></span> <span data-ttu-id="98073-126">The custom layout will be used the next time that you run the report.</span><span class="sxs-lookup"><span data-stu-id="98073-126">The custom layout will be used the next time that you run the report.</span></span>

## <a name="see-also"></a><span data-ttu-id="98073-127">See Also</span><span class="sxs-lookup"><span data-stu-id="98073-127">See Also</span></span>
[<span data-ttu-id="98073-128">Manage Report Layouts</span><span class="sxs-lookup"><span data-stu-id="98073-128">Manage Report Layouts</span></span>](ui-manage-report-layouts.md)

