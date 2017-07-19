---
title: 'How to: Prioritize Vendors'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 3b89bf07e1e9d1839b6c86a01111e936fb62c9f3
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-prioritize-vendors"></a>How to: Prioritize Vendors
Dynamics NAV can suggest various payments to vendors, for example, payments that will be due soon or payments where a discount is available. for more information, see [How to: Suggest Vendor Payments](payables-how-suggest-vendor-payments.md).

First, you must prioritize your vendors by assigning numbers to them.

## <a name="to-prioritize-vendors"></a>To prioritize vendors
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.
2. Select the relevant vendor, and then choose **Edit**.
3. In the **Priority** field, enter a number.

Dynamics NAV considers the lowest number, except 0, to have the highest priority. So, for example, if you use 1, 2, and 3, then 1 will have the highest priority.

If you do not want to prioritize a vendor, leave the **Priority** field blank. Then, if you use the payment suggestion feature, the vendor will be listed after all the vendors that have a priority number. You can enter as many priority levels as necessary.

## <a name="see-also"></a>See Also
[Set Up Purchasing](purchasing-setup-purchasing.md)  
[Manage Payables](payables-manage-payables.md)

