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

# <a name="how-to-work-with-checks"></a>How to: Work With Cheques
Dynamics NAV supports electronic and manual cheque issuance. Both methods use the payment journal to issue cheques to vendors. You can also void cheques and view cheque ledger entries.

The process of issuing cheques suggests payments, creates ledger entries, and prints the computer cheques.

Your printer must be correctly set up with the cheque forms, and you must define which cheque layout to use. For more information, see [How to: Define Cheque Layouts](finance-setup-how-define-check-layouts.md)

## <a name="to-issue-checks"></a>To issue cheques
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.
2. Fill in the journal with relevant payments, for example by using the Suggest Vendor Payments function. For more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).
3. In the **Bank Payment Type** field on journal lines for payment that you want to make with cheques, select one of the following options:

 - **Computer Cheque**: Select this option if you want to print a cheque for the amount on the payment journal line. You must print the cheques before you can post the journal lines. You can only select **Computer Cheque** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.

 - **Manual Cheque**: Select this option if you have created a cheque manually and want to create a corresponding cheque ledger entry for this amount. By using this option, you cannot print cheques from Dynamics NAV. You can only select **Manual Cheque** if the **Bal. Account Type** or the **Account Type** is **Bank Account**.

    **Note**: You must print computer cheques before you post the related journal lines.
4. In case of computer cheques, choose **Print Cheque**.
5. In the **Check** window, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.
6. Choose the **Print** button.

**Note**: If you want to print cheques in more than one currency from different bank accounts, you must run the **Print Cheque** batch job separately for each currency and specify the appropriate bank account.

## <a name="to-cancel-printed-checks-that-are-not-posted"></a>To cancel printed cheques that are not posted
You can cancel non-posted cheques after they have been printed by using the **Void Cheque** action in the **Payment Journal** window.
1. In the **Payment Journal** window, choose the **Void Cheque**, and then choose which cheques to cancel.

## <a name="to-void-checks"></a>To void cheques
When cheque payment have been posted, you can only cancel (void) cheques from the resulting bank ledger entries.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Bank Accounts**, and then choose the related link.
2. Select the relevant bank account, choose the **Edit** action, and then choose the **Cheque Ledger Entries** action.
3. In the **Cheque Ledger Entries** window, choose the **Void Cheque** action.
4. Select the **Void Cheque Only** check box.
5. Choose the **OK**button.

## <a name="see-also"></a>See Also
[Manage Payables](payables-manage-payables.md)  
[Set Up Banking](bank-setup-banking.md)  

