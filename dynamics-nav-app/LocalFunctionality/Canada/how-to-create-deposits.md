---
title: How to Create Deposits
description: You can make deposits to maintain a transaction record that contains information that can be applied to outstanding invoices and credit memos.
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8ef541f705342dd63c2d44bedb62245b80d24ba5
ms.contentlocale: en-ca
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-create-deposits"></a>How to: Create Deposits
You can make deposits to maintain a transaction record that contains information that can be applied to outstanding invoices and credit memos.  

## <a name="to-create-a-deposit"></a>To create a deposit  
1.  Choose the ![Search for Page or Report](../../media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Deposits**, and then choose the related link.  
2.  Choose the **New** action.  
3.  On the **General** FastTab, fill in the required fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**No.**|The unique identification number for the deposit.|  
    |**Bank Account No.**|The bank account number for the deposit.|  
    |**Total Deposit Amount**|The total deposit amount posted to the bank ledger.<br /><br /> You can post this deposit only if the sum of the deposit lines is equal to the value in this field.|  
    |**Posting Date**|The posting date for the deposit.|  
    |**Document Date**|The deposit document date.|  
4.  On the **Lines** FastTab, fill in the required fields as described in the following table.  

    |Field|Description|  
    |---------------------------------|---------------------------------------|  
    |**Account Type**|The account type.|  
    |**Account No.**|The unique identification account number that is associated with the selected account type, to which the entry will be posted.|  
    |**Description**|The journal line entry description.|  
    |**Document Date**|The journal line entry document date.|  
    |**Document Type**|The journal line entry document type.|  
    |**Document No.**|The journal line entry document number.|  
    |**Credit Amount**|The total credit amount on the journal line.|  

5.  Optionally, on the **Navigate** tab, choose **Dimensions**, and then add relevant dimensions in the **Dimension Set Entries** window.  

After you have created a deposit, you must post it.  

## <a name="to-post-a-deposit"></a>To post a deposit  
1. Choose the **Post** action.  

    > [!NOTE]  
    >  You can post a deposit only if the amount displayed in the **Total Deposit Lines** field is equal to the amount in the **Total Deposit Amount** field.  

Next, you can use the Deposit Test Report and Deposit reports to reconcile your posted deposits with outstanding invoices and credit memos.  

## <a name="see-also"></a>See Also  
[Canada Local Functionality](canada-local-functionality.md)  
[Finance](../../finance.md)  
[Setting Up Finance](../../finance.md)  

