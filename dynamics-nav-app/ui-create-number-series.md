---
title: Create Number Series
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
ms.openlocfilehash: e42e5ed139b2487fea13ef0fd57757035764addd
ms.contentlocale: en-ca
ms.lasthandoff: 07/19/2017

---

# <a name="create-number-series"></a><span data-ttu-id="d8a97-102">Create Number Series</span><span class="sxs-lookup"><span data-stu-id="d8a97-102">Create Number Series</span></span>

<span data-ttu-id="d8a97-103">For each company that you set up, you need to assign unique identification codes to things such as general ledger accounts, customer and vendor accounts, invoices, and documents.</span><span class="sxs-lookup"><span data-stu-id="d8a97-103">For each company that you set up, you need to assign unique identification codes to things such as general ledger accounts, customer and vendor accounts, invoices, and documents.</span></span> <span data-ttu-id="d8a97-104">Numbering is important not only for identification.</span><span class="sxs-lookup"><span data-stu-id="d8a97-104">Numbering is important not only for identification.</span></span> <span data-ttu-id="d8a97-105">A well-designed numbering system also makes the company more manageable and easy to analyse, and can reduce the number of errors that occur in data entry.</span><span class="sxs-lookup"><span data-stu-id="d8a97-105">A well-designed numbering system also makes the company more manageable and easy to analyze, and can reduce the number of errors that occur in data entry.</span></span>

<span data-ttu-id="d8a97-106">You can set up a complete numbering system with an unlimited number of number series.</span><span class="sxs-lookup"><span data-stu-id="d8a97-106">You can set up a complete numbering system with an unlimited number of number series.</span></span> <span data-ttu-id="d8a97-107">You can use number series for all types of documents and journals, as well as for master data such as customers, items, and jobs.</span><span class="sxs-lookup"><span data-stu-id="d8a97-107">You can use number series for all types of documents and journals, as well as for master data such as customers, items, and jobs.</span></span>

<span data-ttu-id="d8a97-108">You can combine the use of number series with manual numbering.</span><span class="sxs-lookup"><span data-stu-id="d8a97-108">You can combine the use of number series with manual numbering.</span></span>

<span data-ttu-id="d8a97-109">You create a numbering system by setting up one or more codes for each type of master data or document.</span><span class="sxs-lookup"><span data-stu-id="d8a97-109">You create a numbering system by setting up one or more codes for each type of master data or document.</span></span> <span data-ttu-id="d8a97-110">For example, you can set up one code for numbering customers, another code for numbering sales invoices, and another code for numbering documents in general journals.</span><span class="sxs-lookup"><span data-stu-id="d8a97-110">For example, you can set up one code for numbering customers, another code for numbering sales invoices, and another code for numbering documents in general journals.</span></span>

<span data-ttu-id="d8a97-111">After you have set up a code, you set must set up at least one number series line.</span><span class="sxs-lookup"><span data-stu-id="d8a97-111">After you have set up a code, you set must set up at least one number series line.</span></span> <span data-ttu-id="d8a97-112">The number series line contains information such as the first and last number in the series and the starting date.</span><span class="sxs-lookup"><span data-stu-id="d8a97-112">The number series line contains information such as the first and last number in the series and the starting date.</span></span> <span data-ttu-id="d8a97-113">You can set up more than one number series line per number series code, with a different starting date for each line.</span><span class="sxs-lookup"><span data-stu-id="d8a97-113">You can set up more than one number series line per number series code, with a different starting date for each line.</span></span> <span data-ttu-id="d8a97-114">The series will be used consecutively, starting each series on the respective starting date.</span><span class="sxs-lookup"><span data-stu-id="d8a97-114">The series will be used consecutively, starting each series on the respective starting date.</span></span>

<span data-ttu-id="d8a97-115">If you want to use more than one number series code for one type of master data - for example, if you want to use different number series for different categories of items - you can use number series relationships.</span><span class="sxs-lookup"><span data-stu-id="d8a97-115">If you want to use more than one number series code for one type of master data - for example, if you want to use different number series for different categories of items - you can use number series relationships.</span></span>

<span data-ttu-id="d8a97-116">In addition to the numbers that you assign manually or by use of the numbering system, all transactions (ledger entries) are automatically assigned consecutive numbers.</span><span class="sxs-lookup"><span data-stu-id="d8a97-116">In addition to the numbers that you assign manually or by use of the numbering system, all transactions (ledger entries) are automatically assigned consecutive numbers.</span></span> <span data-ttu-id="d8a97-117">These numbers can be seen in the **Entry No.**</span><span class="sxs-lookup"><span data-stu-id="d8a97-117">These numbers can be seen in the **Entry No.**</span></span> <span data-ttu-id="d8a97-118">field in all the ledger entry windows.</span><span class="sxs-lookup"><span data-stu-id="d8a97-118">field in all the ledger entry windows.</span></span> <span data-ttu-id="d8a97-119">You cannot modify or delete these numbers.</span><span class="sxs-lookup"><span data-stu-id="d8a97-119">You cannot modify or delete these numbers.</span></span>

## <a name="to-create-relationships-between-number-series"></a><span data-ttu-id="d8a97-120">To create relationships between number series</span><span class="sxs-lookup"><span data-stu-id="d8a97-120">To create relationships between number series</span></span>
<span data-ttu-id="d8a97-121">If you have set up more than one number series code for the same kind of basic information or transactions, you can create relationships between the codes.</span><span class="sxs-lookup"><span data-stu-id="d8a97-121">If you have set up more than one number series code for the same kind of basic information or transactions, you can create relationships between the codes.</span></span> <span data-ttu-id="d8a97-122">This feature can assist you in deciding among the codes when you use a number.</span><span class="sxs-lookup"><span data-stu-id="d8a97-122">This feature can assist you in deciding among the codes when you use a number.</span></span>

1. <span data-ttu-id="d8a97-123">In the top right corner, choose the **Search for Page or Report** icon, enter **No. Series**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="d8a97-123">In the top right corner, choose the **Search for Page or Report** icon, enter **No. Series**, and then choose the related link.</span></span>
2. <span data-ttu-id="d8a97-124">Select the line with the number series you want to create relationships for and then choose **Relationships**.</span><span class="sxs-lookup"><span data-stu-id="d8a97-124">Select the line with the number series you want to create relationships for and then choose **Relationships**.</span></span>
3. <span data-ttu-id="d8a97-125">In the **Series Code** field, enter the code for the number series that you want to relate to the series you selected in step 2.</span><span class="sxs-lookup"><span data-stu-id="d8a97-125">In the **Series Code** field, enter the code for the number series that you want to relate to the series you selected in step 2.</span></span>
4. <span data-ttu-id="d8a97-126">Add a line for each code that you want to relate to the selected number series.</span><span class="sxs-lookup"><span data-stu-id="d8a97-126">Add a line for each code that you want to relate to the selected number series.</span></span>
5. <span data-ttu-id="d8a97-127">Close the window.</span><span class="sxs-lookup"><span data-stu-id="d8a97-127">Close the window.</span></span>

<span data-ttu-id="d8a97-128">Now when you set up something that requires a number, you can use the relationships you created to select among the related number series.</span><span class="sxs-lookup"><span data-stu-id="d8a97-128">Now when you set up something that requires a number, you can use the relationships you created to select among the related number series.</span></span>

## <a name="see-also"></a><span data-ttu-id="d8a97-129">See Also</span><span class="sxs-lookup"><span data-stu-id="d8a97-129">See Also</span></span>
[<span data-ttu-id="d8a97-130">Work with Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="d8a97-130">Work with Dynamics NAV</span></span>](ui-work-product.md)

