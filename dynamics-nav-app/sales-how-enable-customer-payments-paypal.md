---
title: 'How to: Enable Customer Payments Through PayPal'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: HT
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 15f30a03c3e7ccc865ef527a707794c2c6428b2f
ms.contentlocale: en-ca
ms.lasthandoff: 10/16/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a>How to: Enable Customer Payments Through PayPal#
As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.

When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale. The customer can then pay the invoice as any other PayPal payment.

To enable customer payments through PayPal, you must do the following:

1. Set up PayPal Payments Standard as a payment service in the **Payments Services** window.
2. Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.

The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled. For more information, see [Customizing Dynamics NAV Using Extensions](ui-extensions.md).

## <a name="to-enable-the-paypal-payments-standard-service"></a>To enable the PayPal Payments Standard service
1. In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.  
2. In the **Payment Services** window, choose the **New** action.
3. Select **PayPal Standard**, and then close the window.
4. In the **Payment Services** window, choose the **Setup** action.
5. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

    **Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.

6. Close the window.

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a>To select PayPal Payments Standard on a sales invoice
1. On the Home page, choose **Sales Invoices**.
2. Open the sales invoice that you want to enable PayPal payments for.
3. In the **Payment Service** field, choose PayPal Payments Standard.

**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.   

## <a name="see-also"></a>See Also  
[Set Up Sales](sales-setup-sales.md)  
[Manage Sales](sales-manage-sales.md)  
[Customizing Dynamics NAV Using Extensions](ui-extensions.md)

