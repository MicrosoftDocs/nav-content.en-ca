---
title: Design Details - Expected Cost Posting
description: "Expected costs represent the estimation of, for example, a purchased item’s cost that you record before you receive the invoice for the item."
documentationcenter: 
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
ms.openlocfilehash: 0b14943e1bb214c26dfbae765a2467df1d06e50b
ms.contentlocale: en-ca
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-expected-cost-posting"></a>Design Details: Expected Cost Posting
Expected costs represent the estimation of, for example, a purchased item’s cost that you record before you receive the invoice for the item.  

 You can post expected cost to inventory and to the general ledger. When you post a quantity that is only received or shipped but not invoiced, then a value entry is created with the expected cost. This expected cost affects the inventory value, but is not posted to the general ledger unless you set up the system up to do so.  

> [!NOTE]  
>  Expected costs are only managed for item transactions. Expected costs are not for immaterial transaction types, such as capacity and item charges.  

 If only the quantity part of an inventory increase has been posted, then the inventory value in the general ledger does not change unless you have selected the **Expected Cost Posting to G/L** check box in the **Inventory Setup** window. In that case, the expected cost is posted to interim accounts at the time of receipt. After the receipt has been fully invoiced, the interim accounts are then balanced and the actual cost is posted to the inventory account.  

 To support reconciliation and traceability work, the invoiced value entry shows the expected cost amount that has been posted to balance the interim accounts.  

## <a name="example"></a>Example  
 The following example shows expected cost if the **Automatic Cost Posting** check box and the **Expected Cost Posting to G/L** check box are selected in the **Inventory Setup** window.  

 You post a purchase order as received. The expected cost is $ 95.00.  

 **Value Entries**  

|Posting Date|Entry Type|Cost Amount (Expected)|Expected Cost Posted to G/L|Expected Cost|Item Ledger Entry No.|Entry No.|  
|------------------|----------------|------------------------------|----------------------------------|-------------------|---------------------------|---------------|  
|01-01-20|Direct Cost|95.00|95.00|Yes|1|1|  

 **Relation Entries in the G/L – Item Ledger Relation Table**  

|G/L Entry No.|Value Entry No.|G/L Register No.|  
|--------------------|---------------------|-----------------------|  
|1|1|1|  
|2|1|1|  

 **General Ledger Entries**  

|Posting Date|G/L Account|Account No. (En-US Demo)|Amount|Entry No.|  
|------------------|------------------|---------------------------------|------------|---------------|  
|01-01-20|Inventory Accrual Account (Interim)|5530|-95.00|2|  
|01-01-20|Inventory Account (Interim)|2131|95.00|1|  

 At a later date, you post the purchase order as invoiced. The invoiced cost is $ 100.00.  

 **Value Entries**  

|Posting Date|Cost Amount (Actual)|Cost Amount (Expected)|Cost Posted to G/L|Expected Cost|Item Ledger Entry No.|Entry No.|  
|------------------|----------------------------|------------------------------|-------------------------|-------------------|---------------------------|---------------|  
|01-15-20|100.00|-95.00|100.00|No|1|2|  

 **Relation Entries in the G/L – Item Ledger Relation Table**  

|G/L Entry No.|Value Entry No.|G/L Register No.|  
|--------------------|---------------------|-----------------------|  
|3|2|2|  
|4|2|2|  
|5|2|2|  
|6|2|2|  

 **General Ledger Entries**  

|Posting Date|G/L Account|Account No. (En-US Demo)|Amount|Entry No.|  
|------------------|------------------|---------------------------------|------------|---------------|  
|01-15-20|Inventory Accrual Account (Interim)|5530|95.00|4|  
|01-15-20|Inventory Account (Interim)|2131|-95.00|3|  
|01-15-20|Direct Cost Applied Account|7291|-100|6|  
|01-15-20|Inventory Account|2130|100|5|  

## <a name="see-also"></a>See Also
 [Design Details: Inventory Costing](design-details-inventory-costing.md)   
 [Design Details: Cost Adjustment](design-details-cost-adjustment.md)   
 [Design Details: Reconciliation with the General Ledger](design-details-reconciliation-with-the-general-ledger.md)   
 [Design Details: Inventory Posting](design-details-inventory-posting.md)   
 [Design Details: Variance](design-details-variance.md)  
 [Managing Inventory Costs](finance-manage-inventory-costs.md)  
 [Finance](finance.md)  
 [Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

