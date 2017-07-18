---
title: Work with General Journals
author: edupont04
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 2dc2b22fbc0ff70addd16ca14e8c5416c49915e7
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---

# <a name="work-with-general-journals"></a>Work with General Journals
You use general journals to post financial transactions to general ledger accounts and other accounts, such as bank, customer, and vendor accounts. Posting with a general journal always creates entries on general ledger accounts. This is true even when, for example, you post a journal line to a customer account, because an entry is posted to a general ledger receivables account through a posting group.

The information that you enter in a journal is temporary and can be changed while it is in the journal. When you post the journal, the information is transferred to entries on individual accounts, where it cannot be changed. You can, however, unapply posted entries, and you can post reversing or correcting entries.

## <a name="journal-templates-and-batches"></a>Journal templates and batches
There are several general journal templates. Each journal template is represented by a dedicated window with particular functions and the fields that are required to support those functions, such as the **Payment Reconciliation Journal** window to process bank payments and the **Payment Journal** window to pay your vendors.

For each journal template, you can set up your own personal journal as a journal batch. For example, you can define your own journal batch for the payment journal that has your personal layout and settings.

**Note**: An example of a personal setting that you can define on your general journal batch is to have the system help you fill amount fields. If you select the **Suggest Balancing Amount** check box on the line for your batch in the **General Journal Batches** window, then the **Amount** field on, for example, general journal lines for the same document number is automatically prefilled with the value that is required to balance the document. For more information, see [Letting Dynamics NAV Suggest Values](ui-let-system-suggest-values.md).

## <a name="main-accounts-and-balancing-accounts"></a>Main accounts and balancing accounts
If you have set up default balancing accounts for the journal batches, the balancing account will be filled in automatically when you fill in the **Account No.** field. Otherwise, fill in both the **Account No.** field and the **Bal. Account No.** field manually. A positive amount in the **Amount** field is debited to the main account and credited to the balancing account. A negative amount is credited to the main account and debited to the balancing account.

**Note**: Tax is calculated separately for the main account and the balancing account, so they can use different Tax percentage rates.

## <a name="recurring-journals"></a>Recurring journals
A recurring journal is a general journal with specific fields for managing transactions that you post frequently with few or no changes. Using these fields for recurring transactions, you can post both fixed and variable amounts. You can also specify automatic reversal entries for the day after the posting date and use allocation keys with the recurring entries.

## <a name="see-also"></a>See Also
[How to: Use Allocation Keys in General Journals](ui-how-use-allocation-keys-general-journals.md)  
[Finance](finance-setup.md)  
[Work with Dynamics NAV](ui-work-product.md)

