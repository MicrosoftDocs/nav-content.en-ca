---
title: Saved Settings on Reports
author: jswymer
ms.custom: na
ms.date: 09/26/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 545a7875ef666e33ed6f519226ce32d6602cae9c
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---
# <a name="saved-settings-on-reports"></a><span data-ttu-id="43914-102">Saved Settings on Reports</span><span class="sxs-lookup"><span data-stu-id="43914-102">Saved Settings on Reports</span></span>
<span data-ttu-id="43914-103">Depending on the report that is run, you might be presented with a page that lets you to set certain options and filters for changing the data that is included in the generated report.</span><span class="sxs-lookup"><span data-stu-id="43914-103">Depending on the report that is run, you might be presented with a page that lets you to set certain options and filters for changing the data that is included in the generated report.</span></span> <span data-ttu-id="43914-104">This page is known as the report request page.</span><span class="sxs-lookup"><span data-stu-id="43914-104">This page is known as the report request page.</span></span> <span data-ttu-id="43914-105">A report can include one or more *saved settings* that you can apply to the report from the request page.</span><span class="sxs-lookup"><span data-stu-id="43914-105">A report can include one or more *saved settings* that you can apply to the report from the request page.</span></span> <span data-ttu-id="43914-106">*Saved settings* are basically predefined options and filters.</span><span class="sxs-lookup"><span data-stu-id="43914-106">*Saved settings* are basically predefined options and filters.</span></span> <span data-ttu-id="43914-107">Using saved settings is a fast and reliable way to consistently generate reports that contain the correct data.</span><span class="sxs-lookup"><span data-stu-id="43914-107">Using saved settings is a fast and reliable way to consistently generate reports that contain the correct data.</span></span>

<span data-ttu-id="43914-108">You can see the saved settings that are available to you for a report in **Saved Settings** section of the report request page.</span><span class="sxs-lookup"><span data-stu-id="43914-108">You can see the saved settings that are available to you for a report in **Saved Settings** section of the report request page.</span></span>

## <a name="to-apply-saved-settings-to-a-report"></a><span data-ttu-id="43914-109">To apply saved settings to a report</span><span class="sxs-lookup"><span data-stu-id="43914-109">To apply saved settings to a report</span></span>
1.  <span data-ttu-id="43914-110">Open the report.</span><span class="sxs-lookup"><span data-stu-id="43914-110">Open the report.</span></span>

    <span data-ttu-id="43914-111">The report request page appears.</span><span class="sxs-lookup"><span data-stu-id="43914-111">The report request page appears.</span></span>    
2.  <span data-ttu-id="43914-112">In the **Saved Settings** section of the page, set the **Name** field  to the saved settings that you want to use.</span><span class="sxs-lookup"><span data-stu-id="43914-112">In the **Saved Settings** section of the page, set the **Name** field  to the saved settings that you want to use.</span></span>

    <span data-ttu-id="43914-113">The **Saved Settings** section only appears if the report has been run before or if there are existing saved settings entries.</span><span class="sxs-lookup"><span data-stu-id="43914-113">The **Saved Settings** section only appears if the report has been run before or if there are existing saved settings entries.</span></span> <span data-ttu-id="43914-114">The saved settings entry called **Last used options and filters** is always available.</span><span class="sxs-lookup"><span data-stu-id="43914-114">The saved settings entry called **Last used options and filters** is always available.</span></span> <span data-ttu-id="43914-115">These settings are the option and filter values that were used the last time you ran the report.</span><span class="sxs-lookup"><span data-stu-id="43914-115">These settings are the option and filter values that were used the last time you ran the report.</span></span>

## <a name="administer-saved-report-settings-for-users"></a><span data-ttu-id="43914-116">Administer saved report settings for users</span><span class="sxs-lookup"><span data-stu-id="43914-116">Administer saved report settings for users</span></span>
<span data-ttu-id="43914-117">If you have the proper permissions, you can view, create, and modify the saved settings for all reports for all users in company.</span><span class="sxs-lookup"><span data-stu-id="43914-117">If you have the proper permissions, you can view, create, and modify the saved settings for all reports for all users in company.</span></span> <span data-ttu-id="43914-118">You can assign saved settings for a report to individual users or all users in the company.</span><span class="sxs-lookup"><span data-stu-id="43914-118">You can assign saved settings for a report to individual users or all users in the company.</span></span>

<span data-ttu-id="43914-119">You manage saved settings from page 1506 **Reports Settings**.</span><span class="sxs-lookup"><span data-stu-id="43914-119">You manage saved settings from page 1506 **Reports Settings**.</span></span> <span data-ttu-id="43914-120">To open this page, in the top right corner, choose the **Search for Page or Report** icon, enter **Report Settings**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="43914-120">To open this page, in the top right corner, choose the **Search for Page or Report** icon, enter **Report Settings**, and then choose the related link.</span></span> 

<span data-ttu-id="43914-121">From the **Report Settings** page, you can create a new settings from scratch or you can make a copy and modify existing settings.</span><span class="sxs-lookup"><span data-stu-id="43914-121">From the **Report Settings** page, you can create a new settings from scratch or you can make a copy and modify existing settings.</span></span> <span data-ttu-id="43914-122">To modify the options and filters for a settings, choose the **Edit** action.</span><span class="sxs-lookup"><span data-stu-id="43914-122">To modify the options and filters for a settings, choose the **Edit** action.</span></span>

<span data-ttu-id="43914-123">**Notes**:</span><span class="sxs-lookup"><span data-stu-id="43914-123">**Notes**:</span></span>
-    <span data-ttu-id="43914-124">The saved settings feature on reports is only relevant when the SaveValues property of the request page is set to Yes.</span><span class="sxs-lookup"><span data-stu-id="43914-124">The saved settings feature on reports is only relevant when the SaveValues property of the request page is set to Yes.</span></span> <span data-ttu-id="43914-125">The SaveValues property property is set in the development environment.</span><span class="sxs-lookup"><span data-stu-id="43914-125">The SaveValues property property is set in the development environment.</span></span>
-    <span data-ttu-id="43914-126">If you create a saved settings item for all users, and it has the same name as an existing saved settings for a specific user, then that user will not be able to use the saved settings that is assigned to everyone.</span><span class="sxs-lookup"><span data-stu-id="43914-126">If you create a saved settings item for all users, and it has the same name as an existing saved settings for a specific user, then that user will not be able to use the saved settings that is assigned to everyone.</span></span>  <span data-ttu-id="43914-127">In the Saved Settings field on the report request page, the user will see two saved settings options with the same name.</span><span class="sxs-lookup"><span data-stu-id="43914-127">In the Saved Settings field on the report request page, the user will see two saved settings options with the same name.</span></span> <span data-ttu-id="43914-128">However, no matter which option he chooses, the user-specific saved settings will be used.</span><span class="sxs-lookup"><span data-stu-id="43914-128">However, no matter which option he chooses, the user-specific saved settings will be used.</span></span>

## <a name="see-also"></a><span data-ttu-id="43914-129">See Also</span><span class="sxs-lookup"><span data-stu-id="43914-129">See Also</span></span>
[<span data-ttu-id="43914-130">Schedule a Rpeort to Run</span><span class="sxs-lookup"><span data-stu-id="43914-130">Schedule a Rpeort to Run</span></span>](ui-schedule-report.md)

