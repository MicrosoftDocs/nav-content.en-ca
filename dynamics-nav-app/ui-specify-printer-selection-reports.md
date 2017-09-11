---
title: Specify Printer Selection for Reports
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
ms.openlocfilehash: 56a5c1428651162293e56d71e2369fe55d291594
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---
    
# <a name="specify-printer-selection-for-reports"></a><span data-ttu-id="9ae51-102">Specify Printer Selection for Reports</span><span class="sxs-lookup"><span data-stu-id="9ae51-102">Specify Printer Selection for Reports</span></span>
<span data-ttu-id="9ae51-103">You can set up reports so that they must be printed on a specific printer.</span><span class="sxs-lookup"><span data-stu-id="9ae51-103">You can set up reports so that they must be printed on a specific printer.</span></span> <span data-ttu-id="9ae51-104">The following are some uses of printer selection:</span><span class="sxs-lookup"><span data-stu-id="9ae51-104">The following are some uses of printer selection:</span></span> 

- <span data-ttu-id="9ae51-105">You can print reports on special company letterhead.</span><span class="sxs-lookup"><span data-stu-id="9ae51-105">You can print reports on special company letterhead.</span></span>
- <span data-ttu-id="9ae51-106">You can print reports on different paper sizes.</span><span class="sxs-lookup"><span data-stu-id="9ae51-106">You can print reports on different paper sizes.</span></span>
- <span data-ttu-id="9ae51-107">You can print reports on the default printer of a specified employee.</span><span class="sxs-lookup"><span data-stu-id="9ae51-107">You can print reports on the default printer of a specified employee.</span></span>

<span data-ttu-id="9ae51-108">You use the **Printer Selections** window to set different values to obtain different output.</span><span class="sxs-lookup"><span data-stu-id="9ae51-108">You use the **Printer Selections** window to set different values to obtain different output.</span></span> <span data-ttu-id="9ae51-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span><span class="sxs-lookup"><span data-stu-id="9ae51-109">If you set a specific printer selection, then it takes precedence over a more general printer selection.</span></span> <span data-ttu-id="9ae51-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span><span class="sxs-lookup"><span data-stu-id="9ae51-110">For example, you can set a printer selection that has values in the **User ID**, **Report ID**, and **Printer Name** fields.</span></span> <span data-ttu-id="9ae51-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span><span class="sxs-lookup"><span data-stu-id="9ae51-111">This printer selection takes precedence over a printer selection that has blank entries in the **User ID** or **Report ID** fields.</span></span> 

<span data-ttu-id="9ae51-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span><span class="sxs-lookup"><span data-stu-id="9ae51-112">The following table describes the combination of values to specify when you set up printer selections for a report.</span></span>

|<span data-ttu-id="9ae51-113">To</span><span class="sxs-lookup"><span data-stu-id="9ae51-113">To</span></span>                                                 |<span data-ttu-id="9ae51-114">Set the following values</span><span class="sxs-lookup"><span data-stu-id="9ae51-114">Set the following values</span></span>                                             |
|---------------------------------------------------|---------------------------------------------------------------------|
|<span data-ttu-id="9ae51-115">Print a report to a specific printer for all users</span><span class="sxs-lookup"><span data-stu-id="9ae51-115">Print a report to a specific printer for all users</span></span> |<span data-ttu-id="9ae51-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span><span class="sxs-lookup"><span data-stu-id="9ae51-116">Specify values in the **Report ID** and **Printer Name** fields and leave the **User ID** field blank.</span></span>|
|<span data-ttu-id="9ae51-117">Print all reports to a specific printer for a specific user</span><span class="sxs-lookup"><span data-stu-id="9ae51-117">Print all reports to a specific printer for a specific user</span></span>|<span data-ttu-id="9ae51-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span><span class="sxs-lookup"><span data-stu-id="9ae51-118">Specify values in the **User ID** and **Printer Name** fields and leave the **Report ID** field blank.</span></span>|
|<span data-ttu-id="9ae51-119">Set the default printer for all reports</span><span class="sxs-lookup"><span data-stu-id="9ae51-119">Set the default printer for all reports</span></span>|<span data-ttu-id="9ae51-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span><span class="sxs-lookup"><span data-stu-id="9ae51-120">Specify a value in the **Printer Name** field and leave the **User ID** and **Report ID** fields blank.</span></span>|
|<span data-ttu-id="9ae51-121">Print a specific report to the user’s default printer</span><span class="sxs-lookup"><span data-stu-id="9ae51-121">Print a specific report to the user’s default printer</span></span>|<span data-ttu-id="9ae51-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span><span class="sxs-lookup"><span data-stu-id="9ae51-122">Specify a value in the **Report ID** field and leave the **Printer Name** and **User ID** fields blank.</span></span>|
|<span data-ttu-id="9ae51-123">Print a specific report to a specific printer for a specific user</span><span class="sxs-lookup"><span data-stu-id="9ae51-123">Print a specific report to a specific printer for a specific user</span></span>|<span data-ttu-id="9ae51-124">Specify values in all three fields.</span><span class="sxs-lookup"><span data-stu-id="9ae51-124">Specify values in all three fields.</span></span>|

## <a name="see-also"></a><span data-ttu-id="9ae51-125">See Also</span><span class="sxs-lookup"><span data-stu-id="9ae51-125">See Also</span></span>
[<span data-ttu-id="9ae51-126">Work with Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="9ae51-126">Work with Dynamics NAV</span></span>](ui-work-product.md)

