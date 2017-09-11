---
title: 'How to: Use Allocation Keys in General Journals'
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: ca21d9d129dbc98d75371d1b2b7a0ffad4aa2848
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---

#  <a name="how-to-use-allocation-keys-in-general-journals"></a><span data-ttu-id="2a38c-102">How to: Use Allocation Keys in General Journals</span><span class="sxs-lookup"><span data-stu-id="2a38c-102">How to: Use Allocation Keys in General Journals</span></span>
<span data-ttu-id="2a38c-103">You can allocate an entry in a general journal to several different accounts when you post the journal.</span><span class="sxs-lookup"><span data-stu-id="2a38c-103">You can allocate an entry in a general journal to several different accounts when you post the journal.</span></span> <span data-ttu-id="2a38c-104">The allocation can be made by quantity, percentage, or amount.</span><span class="sxs-lookup"><span data-stu-id="2a38c-104">The allocation can be made by quantity, percentage, or amount.</span></span>

## <a name="to-set-up-allocation-keys"></a><span data-ttu-id="2a38c-105">To set up allocation keys</span><span class="sxs-lookup"><span data-stu-id="2a38c-105">To set up allocation keys</span></span> 
1. <span data-ttu-id="2a38c-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="2a38c-106">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="2a38c-107">Choose the **Batch Name** field to open the **General Journal Batches** window.</span><span class="sxs-lookup"><span data-stu-id="2a38c-107">Choose the **Batch Name** field to open the **General Journal Batches** window.</span></span>
3. <span data-ttu-id="2a38c-108">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span><span class="sxs-lookup"><span data-stu-id="2a38c-108">You can either modify allocations on an existing batch in the list or create a new batch with allocations.</span></span>
  * <span data-ttu-id="2a38c-109">To create a new batch, choose the **New** action, and go to the next step.</span><span class="sxs-lookup"><span data-stu-id="2a38c-109">To create a new batch, choose the **New** action, and go to the next step.</span></span>
  * <span data-ttu-id="2a38c-110">To change the allocations of an existing journal, select the journal and go to step 7.</span><span class="sxs-lookup"><span data-stu-id="2a38c-110">To change the allocations of an existing journal, select the journal and go to step 7.</span></span>    
4. <span data-ttu-id="2a38c-111">In the **Name** field, enter a name for the batch, such as CLEANING.</span><span class="sxs-lookup"><span data-stu-id="2a38c-111">In the **Name** field, enter a name for the batch, such as CLEANING.</span></span> <span data-ttu-id="2a38c-112">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span><span class="sxs-lookup"><span data-stu-id="2a38c-112">In the **Description** field, enter a description, such as Cleaning Expenses Journal.</span></span>
5. <span data-ttu-id="2a38c-113">When you are done, close the window.</span><span class="sxs-lookup"><span data-stu-id="2a38c-113">When you are done, close the window.</span></span> <span data-ttu-id="2a38c-114">A new, empty recurring journal opens.</span><span class="sxs-lookup"><span data-stu-id="2a38c-114">A new, empty recurring journal opens.</span></span> 
6. <span data-ttu-id="2a38c-115">Fill in the fields in the line.</span><span class="sxs-lookup"><span data-stu-id="2a38c-115">Fill in the fields in the line.</span></span>
7. <span data-ttu-id="2a38c-116">Choose the **Allocations** action.</span><span class="sxs-lookup"><span data-stu-id="2a38c-116">Choose the **Allocations** action.</span></span> 
8. <span data-ttu-id="2a38c-117">Add a line for each allocation.</span><span class="sxs-lookup"><span data-stu-id="2a38c-117">Add a line for each allocation.</span></span> <span data-ttu-id="2a38c-118">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span><span class="sxs-lookup"><span data-stu-id="2a38c-118">You must fill in either the **Allocation %**, **Allocation Quantity**, or **Amount** field.</span></span> <span data-ttu-id="2a38c-119">You must also fill in the **Account No.**</span><span class="sxs-lookup"><span data-stu-id="2a38c-119">You must also fill in the **Account No.**</span></span> <span data-ttu-id="2a38c-120">field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span><span class="sxs-lookup"><span data-stu-id="2a38c-120">field and, if you are allocating the transaction among global dimensions, the global dimension fields.</span></span>
9. <span data-ttu-id="2a38c-121">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span><span class="sxs-lookup"><span data-stu-id="2a38c-121">If you enter a percentage on a line, the amount in the **Amount** field is calculated automatically.</span></span> <span data-ttu-id="2a38c-122">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span><span class="sxs-lookup"><span data-stu-id="2a38c-122">These amounts have the opposite sign from the total amount in the **Amount** field in the recurring journal.</span></span>
10. <span data-ttu-id="2a38c-123">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span><span class="sxs-lookup"><span data-stu-id="2a38c-123">After entering the allocations lines, choose **OK** to return to the **Recurring General Journal** window.</span></span> <span data-ttu-id="2a38c-124">The **Allocated Amt. (CAD)** field is filled in and matches the **Amount** field.</span><span class="sxs-lookup"><span data-stu-id="2a38c-124">The **Allocated Amt. (USD)** field is filled in and matches the **Amount** field.</span></span>
11. <span data-ttu-id="2a38c-125">Post the journal.</span><span class="sxs-lookup"><span data-stu-id="2a38c-125">Post the journal.</span></span>

## <a name="to-change-an-allocation-key-that-has-already-been-set-up"></a><span data-ttu-id="2a38c-126">To change an allocation key that has already been set up</span><span class="sxs-lookup"><span data-stu-id="2a38c-126">To change an allocation key that has already been set up</span></span>
1. <span data-ttu-id="2a38c-127">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="2a38c-127">In the top right corner, choose the **Search for Page or Report** icon, enter **Recurring General Journal**, and then choose the related link.</span></span>
2. <span data-ttu-id="2a38c-128">In the **Recurring General Journal** window, select the journal with the allocation.</span><span class="sxs-lookup"><span data-stu-id="2a38c-128">In the **Recurring General Journal** window, select the journal with the allocation.</span></span>
3. <span data-ttu-id="2a38c-129">Choose the line with the allocation, and then choose **Allocations** action.</span><span class="sxs-lookup"><span data-stu-id="2a38c-129">Choose the line with the allocation, and then choose **Allocations** action.</span></span>
4. <span data-ttu-id="2a38c-130">Change the relevant fields, and close the window.</span><span class="sxs-lookup"><span data-stu-id="2a38c-130">Change the relevant fields, and close the window.</span></span>

## <a name="see-also"></a><span data-ttu-id="2a38c-131">See Also</span><span class="sxs-lookup"><span data-stu-id="2a38c-131">See Also</span></span>
[<span data-ttu-id="2a38c-132">Work With General Journals</span><span class="sxs-lookup"><span data-stu-id="2a38c-132">Work With General Journals</span></span>](ui-work-general-journals.md)  
[<span data-ttu-id="2a38c-133">Post Documents and Journals</span><span class="sxs-lookup"><span data-stu-id="2a38c-133">Post Documents and Journals</span></span>](ui-post-documents-journals.md)




