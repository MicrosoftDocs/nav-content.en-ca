---
title: 'How to: Dispose of or Retire Fixed Assets'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 795bb23e7c0b46be095b2bbdfe7705b3d7b1e4ee
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-dispose-of-or-retire-fixed-assets"></a><span data-ttu-id="5d18e-102">How to: Dispose of or Retire Fixed Assets</span><span class="sxs-lookup"><span data-stu-id="5d18e-102">How to: Dispose of or Retire Fixed Assets</span></span>
<span data-ttu-id="5d18e-103">When you sell or otherwise dispose of a fixed asset, the disposal value must be posted to calculate and record the gain or loss.</span><span class="sxs-lookup"><span data-stu-id="5d18e-103">When you sell or otherwise dispose of a fixed asset, the disposal value must be posted to calculate and record the gain or loss.</span></span> <span data-ttu-id="5d18e-104">A disposal entry must be the last entry posted for a fixed asset.</span><span class="sxs-lookup"><span data-stu-id="5d18e-104">A disposal entry must be the last entry posted for a fixed asset.</span></span> <span data-ttu-id="5d18e-105">For partially disposed fixed assets, you can post more than one disposal entry.</span><span class="sxs-lookup"><span data-stu-id="5d18e-105">For partially disposed fixed assets, you can post more than one disposal entry.</span></span> <span data-ttu-id="5d18e-106">The total of all posted disposal amounts must be a credit amount.</span><span class="sxs-lookup"><span data-stu-id="5d18e-106">The total of all posted disposal amounts must be a credit amount.</span></span>

 <span data-ttu-id="5d18e-107">**NOTE**: If you trade in a fixed asset for another one, you must record both the sale of the old asset (disposal) and the purchase of the new one (acquisition).</span><span class="sxs-lookup"><span data-stu-id="5d18e-107">**NOTE**: If you trade in a fixed asset for another one, you must record both the sale of the old asset (disposal) and the purchase of the new one (acquisition).</span></span> <span data-ttu-id="5d18e-108">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="5d18e-108">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a><span data-ttu-id="5d18e-109">To post a disposal from the fixed asset G/L journal</span><span class="sxs-lookup"><span data-stu-id="5d18e-109">To post a disposal from the fixed asset G/L journal</span></span>  
1. <span data-ttu-id="5d18e-110">In the top right corner, choose the **Search for Page or Report** icon, enter **FA G/L Journals**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5d18e-110">In the top right corner, choose the **Search for Page or Report** icon, enter **FA G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="5d18e-111">Create an initial journal line and fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="5d18e-111">Create an initial journal line and fill in the fields as necessary.</span></span> <span data-ttu-id="5d18e-112">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="5d18e-112">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="5d18e-113">In the **FA Posting Type** field, select **Disposal**.</span><span class="sxs-lookup"><span data-stu-id="5d18e-113">In the **FA Posting Type** field, select **Disposal**.</span></span>
4. <span data-ttu-id="5d18e-114">Choose the **Insert FA Bal. Account** action.</span><span class="sxs-lookup"><span data-stu-id="5d18e-114">Choose the **Insert FA Bal. Account** action.</span></span> <span data-ttu-id="5d18e-115">A second journal line is created for the balancing account that is set up for disposal posting.</span><span class="sxs-lookup"><span data-stu-id="5d18e-115">A second journal line is created for the balancing account that is set up for disposal posting.</span></span>

    <span data-ttu-id="5d18e-116">**Note**: Step 4 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Disposal Account** field contains the general ledger debit account and the **Disposal Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation.</span><span class="sxs-lookup"><span data-stu-id="5d18e-116">**Note**: Step 4 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Disposal Account** field contains the general ledger debit account and the **Disposal Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation.</span></span> <span data-ttu-id="5d18e-117">For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="5d18e-117">For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).</span></span>
5. <span data-ttu-id="5d18e-118">Choose the **Post** action.</span><span class="sxs-lookup"><span data-stu-id="5d18e-118">Choose the **Post** action.</span></span>

<span data-ttu-id="5d18e-119">If you sell or dispose of part of a fixed asset, you must split up the asset before you can record the disposal transaction.</span><span class="sxs-lookup"><span data-stu-id="5d18e-119">If you sell or dispose of part of a fixed asset, you must split up the asset before you can record the disposal transaction.</span></span> <span data-ttu-id="5d18e-120">For more information, see [How to: Transfer, Split, or Combine Fixed Assets](fa-how-trans-split-combine.md).</span><span class="sxs-lookup"><span data-stu-id="5d18e-120">For more information, see [How to: Transfer, Split, or Combine Fixed Assets](fa-how-trans-split-combine.md).</span></span>

## <a name="to-view-disposal-ledger-entries"></a><span data-ttu-id="5d18e-121">To view disposal ledger entries</span><span class="sxs-lookup"><span data-stu-id="5d18e-121">To view disposal ledger entries</span></span>  
<span data-ttu-id="5d18e-122">When you sell or dispose of a fixed asset, the disposal value is posted to the general ledger where you can view the result.</span><span class="sxs-lookup"><span data-stu-id="5d18e-122">When you sell or dispose of a fixed asset, the disposal value is posted to the general ledger where you can view the result.</span></span>   

1. <span data-ttu-id="5d18e-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="5d18e-123">In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.</span></span>  
2. <span data-ttu-id="5d18e-124">Select the fixed asset that you want to view entries for, and then choose the **Depreciation Books** action.</span><span class="sxs-lookup"><span data-stu-id="5d18e-124">Select the fixed asset that you want to view entries for, and then choose the **Depreciation Books** action.</span></span>
3. <span data-ttu-id="5d18e-125">Select the depreciation book that you want to view entries for, and then choose the **Ledger Entries** action.</span><span class="sxs-lookup"><span data-stu-id="5d18e-125">Select the depreciation book that you want to view entries for, and then choose the **Ledger Entries** action.</span></span>
4. <span data-ttu-id="5d18e-126">Select a line with **Disposal** in the **FA Posting Category** field, and then choose the **Navigate** action.</span><span class="sxs-lookup"><span data-stu-id="5d18e-126">Select a line with **Disposal** in the **FA Posting Category** field, and then choose the **Navigate** action.</span></span>  
5. <span data-ttu-id="5d18e-127">In the **Navigate** window, select the general ledger entry line, and then choose the **Show** action.</span><span class="sxs-lookup"><span data-stu-id="5d18e-127">In the **Navigate** window, select the general ledger entry line, and then choose the **Show** action.</span></span>
<span data-ttu-id="5d18e-128">The **General Ledger Entries** window opens where you can see the entries that the disposal posting resulted in.</span><span class="sxs-lookup"><span data-stu-id="5d18e-128">The **General Ledger Entries** window opens where you can see the entries that the disposal posting resulted in.</span></span>

## <a name="see-also"></a><span data-ttu-id="5d18e-129">See Also</span><span class="sxs-lookup"><span data-stu-id="5d18e-129">See Also</span></span>
[<span data-ttu-id="5d18e-130">Manage Fixed Assets</span><span class="sxs-lookup"><span data-stu-id="5d18e-130">Manage Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="5d18e-131">Set Up Fixed Assets</span><span class="sxs-lookup"><span data-stu-id="5d18e-131">Set Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="5d18e-132">Finance</span><span class="sxs-lookup"><span data-stu-id="5d18e-132">Finance</span></span>](finance-setup.md)  
[<span data-ttu-id="5d18e-133">Welcome to Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="5d18e-133">Welcome to Dynamics NAV</span></span>](across-get-started.md)

