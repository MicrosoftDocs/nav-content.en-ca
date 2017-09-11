---
title: 'How to: Work With Cheques'
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
ms.openlocfilehash: 421516a7580a90d6eabc8ecfcc841215839994c9
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-checks"></a><span data-ttu-id="31b27-102">How to: Work With Cheques</span><span class="sxs-lookup"><span data-stu-id="31b27-102">How to: Work With Checks</span></span>
<span data-ttu-id="31b27-103">Dynamics NAV supports electronic and manual cheque issuance.</span><span class="sxs-lookup"><span data-stu-id="31b27-103">Dynamics NAV supports electronic and manual check issuance.</span></span> <span data-ttu-id="31b27-104">Both methods use the payment journal to issue cheques to vendors.</span><span class="sxs-lookup"><span data-stu-id="31b27-104">Both methods use the payment journal to issue checks to vendors.</span></span> <span data-ttu-id="31b27-105">You can also void cheques and view cheque ledger entries.</span><span class="sxs-lookup"><span data-stu-id="31b27-105">You can also void checks and view check ledger entries.</span></span>

<span data-ttu-id="31b27-106">The process of issuing cheques suggests payments, creates ledger entries, and prints the computer cheques.</span><span class="sxs-lookup"><span data-stu-id="31b27-106">The process of issuing checks suggests payments, creates ledger entries, and prints the computer checks.</span></span>

<span data-ttu-id="31b27-107">Your printer must be correctly set up with the cheque forms, and you must define which cheque layout to use.</span><span class="sxs-lookup"><span data-stu-id="31b27-107">Your printer must be correctly set up with the check forms, and you must define which check layout to use.</span></span> <span data-ttu-id="31b27-108">For more information, see [How to: Define Cheque Layouts](finance-setup-how-define-check-layouts.md)</span><span class="sxs-lookup"><span data-stu-id="31b27-108">For more information, see [How to: Define Check Layouts](finance-setup-how-define-check-layouts.md)</span></span>

## <a name="to-issue-checks"></a><span data-ttu-id="31b27-109">To issue cheques</span><span class="sxs-lookup"><span data-stu-id="31b27-109">To issue checks</span></span>
1. <span data-ttu-id="31b27-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="31b27-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.</span></span>
2. <span data-ttu-id="31b27-111">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span><span class="sxs-lookup"><span data-stu-id="31b27-111">Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function.</span></span> <span data-ttu-id="31b27-112">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span><span class="sxs-lookup"><span data-stu-id="31b27-112">For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).</span></span>
3. <span data-ttu-id="31b27-113">In the **Bank Payment Type** field on journal lines for payment that you want to make with cheques, select one of the following options:</span><span class="sxs-lookup"><span data-stu-id="31b27-113">In the **Bank Payment Type** field on journal lines for payment that you want to make with checks, select one of the following options:</span></span>

 - <span data-ttu-id="31b27-114">**Computer Cheque**: Select this option if you want to print a cheque for the amount on the payment journal line.</span><span class="sxs-lookup"><span data-stu-id="31b27-114">**Computer Check**: Select this option if you want to print a check for the amount on the payment journal line.</span></span> <span data-ttu-id="31b27-115">You must print the cheques before you can post the journal lines.</span><span class="sxs-lookup"><span data-stu-id="31b27-115">You must print the checks before you can post the journal lines.</span></span> <span data-ttu-id="31b27-116">You can only select **Computer Cheque** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span><span class="sxs-lookup"><span data-stu-id="31b27-116">You can only select **Computer Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

 - <span data-ttu-id="31b27-117">**Manual Cheque**: Select this option if you have created a cheque manually and want to create a corresponding cheque ledger entry for this amount.</span><span class="sxs-lookup"><span data-stu-id="31b27-117">**Manual Check**: Select this option if you have created a check manually and want to create a corresponding check ledger entry for this amount.</span></span> <span data-ttu-id="31b27-118">By using this option, you cannot print cheques from Dynamics NAV.</span><span class="sxs-lookup"><span data-stu-id="31b27-118">By using this option, you cannot print checks from Dynamics NAV.</span></span> <span data-ttu-id="31b27-119">You can only select **Manual Cheque** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span><span class="sxs-lookup"><span data-stu-id="31b27-119">You can only select **Manual Check** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.</span></span>

    <span data-ttu-id="31b27-120">**Note**: You must print computer cheques before you post the related journal lines.</span><span class="sxs-lookup"><span data-stu-id="31b27-120">**Note**: You must print computer checks before you post the related journal lines.</span></span>
4. <span data-ttu-id="31b27-121">In case of computer cheques, choose **Print Cheque**.</span><span class="sxs-lookup"><span data-stu-id="31b27-121">In case of computer checks, choose **Print Check**.</span></span>
5. <span data-ttu-id="31b27-122">In the **Check** window, fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="31b27-122">In the **Check** window, fill in the fields as necessary.</span></span> <span data-ttu-id="31b27-123">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="31b27-123">Choose a field to read a short description of the field or link to more information.</span></span>
6. <span data-ttu-id="31b27-124">Choose the **Print** button.</span><span class="sxs-lookup"><span data-stu-id="31b27-124">Choose the **Print** button.</span></span>

<span data-ttu-id="31b27-125">**Note**: If you want to print cheques in more than one currency from different bank accounts, you must run the **Print Cheque** batch job separately for each currency and specify the appropriate bank account.</span><span class="sxs-lookup"><span data-stu-id="31b27-125">**Note**: If you want to print checks in more than one currency from different bank accounts, you must run the **Print Check** batch job separately for each currency and specify the appropriate bank account.</span></span>

## <a name="to-cancel-printed-checks-that-are-not-posted"></a><span data-ttu-id="31b27-126">To cancel printed cheques that are not posted</span><span class="sxs-lookup"><span data-stu-id="31b27-126">To cancel printed checks that are not posted</span></span>
<span data-ttu-id="31b27-127">You can cancel non-posted cheques after they have been printed by using the **Void Cheque** action in the **Payment Journal** window.</span><span class="sxs-lookup"><span data-stu-id="31b27-127">You can cancel non-posted checks after they have been printed by using the **Void Check** action in the **Payment Journal** window.</span></span>
1. <span data-ttu-id="31b27-128">In the **Payment Journal** window, choose the **Void Cheque**, and then choose which cheques to cancel.</span><span class="sxs-lookup"><span data-stu-id="31b27-128">In the **Payment Journal** window, choose the **Void Check**, and then choose which checks to cancel.</span></span>

## <a name="to-void-checks"></a><span data-ttu-id="31b27-129">To void cheques</span><span class="sxs-lookup"><span data-stu-id="31b27-129">To void checks</span></span>
<span data-ttu-id="31b27-130">When cheque payment have been posted, you can only cancel (void) cheques from the resulting bank ledger entries.</span><span class="sxs-lookup"><span data-stu-id="31b27-130">When check payment have been posted, you can only cancel (void) checks from the resulting bank ledger entries.</span></span>

1. <span data-ttu-id="31b27-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="31b27-131">In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="31b27-132">Select the relevant bank account, choose the **Edit** action, and then choose the **Cheque Ledger Entries** action.</span><span class="sxs-lookup"><span data-stu-id="31b27-132">Select the relevant bank account, choose the **Edit** action, and then choose the **Check Ledger Entries** action.</span></span>
3. <span data-ttu-id="31b27-133">In the **Cheque Ledger Entries** window, choose the **Void Cheque** action.</span><span class="sxs-lookup"><span data-stu-id="31b27-133">In the **Check Ledger Entries** window, choose the **Void Check** action.</span></span>
4. <span data-ttu-id="31b27-134">Select the **Void Cheque Only** check box.</span><span class="sxs-lookup"><span data-stu-id="31b27-134">Select the **Void Check Only** check box.</span></span>
5. <span data-ttu-id="31b27-135">Choose the **OK**button.</span><span class="sxs-lookup"><span data-stu-id="31b27-135">Choose the **OK**button.</span></span>

## <a name="see-also"></a><span data-ttu-id="31b27-136">See Also</span><span class="sxs-lookup"><span data-stu-id="31b27-136">See Also</span></span>
[<span data-ttu-id="31b27-137">Manage Payables</span><span class="sxs-lookup"><span data-stu-id="31b27-137">Manage Payables</span></span>](payables-manage-payables.md)  
[<span data-ttu-id="31b27-138">Set Up Banking</span><span class="sxs-lookup"><span data-stu-id="31b27-138">Set Up Banking</span></span>](bank-setup-banking.md)  

