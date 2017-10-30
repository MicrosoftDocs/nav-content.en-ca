---
title: How to Put Items Away with Warehouse Put-aways
description: When your location is set up to require warehouse put-away processing and warehouse receive processing, you use the warehouse put-away documents function to control the putting away of items.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/31/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 88a9513f12adf76cae8aabe8cbf58da0ac2b4ff3
ms.contentlocale: en-ca
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-put-items-away-with-warehouse-put-aways"></a>How to: Put Items Away with Warehouse Put-aways
When your location is set up to require warehouse put-away processing and warehouse receive processing, you use the warehouse put-away documents function to control the putting away of items.  

When you post a warehouse receipt, the source documents, such as purchase, inbound transfer, or sales return orders, are updated, the quantity received is posted to the item ledger, and the lines about the items received are sent to the put-away function in the warehouse. If you have internal put-away and pick, the internal put-away can also create lines for put-away.  

Depending on the warehouse setup, the lines are either made available to the put-away worksheet or used to generate put-away instructions immediately. For more information, see [How to: Plan Put-aways in Worksheets](warehouse-how-to-plan-put-aways-in-worksheets.md).  

In addition to the standard ways to create warehouse put-aways that are described in this topic, you can create the put-away from the related posted warehouse receipt. This is useful if you have deleted put-away lines, or if you use directed put-away and pick and have decided not to use the put-away worksheet, because you can create or recreate put-away instructions from the posted receipt lines.  

## <a name="to-put-items-away-without-directed-put-away-and-pick"></a>To put items away without directed put-away and pick  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Put-aways**, and then choose the related link.  
2.  Open the warehouse put-away that is ready to handle.  

    You can sort the put-away lines by various criteria, for example, by item, shelf number, or due date, and thereby optimize the put-away process.  
3.  On each line, in the **Qty. to Handle** field, enter the quantity you want to put away.  
4.  After you have completed putting the items away, choose the **Register Put-away** action to record the completion of the activity and make the items available for picking.  

## <a name="to-put-items-away-with-directed-put-away-and-pick"></a>To put items away with directed put-away and pick  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Put-aways**, and then choose the related link.
    If put-away instructions have been created, a warehouse put-away is visible.  
2.  Open the warehouse put-away that you want to work on.  
3.  If your warehouse requires, enter your user ID on the **General** FastTab when you begin work on a particular put-away.  
4.  Perform the take and place actions indicated in the **Action Type** field on the lines.  

    Note that each receipt line has become at least two lines in the warehouse put-away:  

    -   The first line, with **Take** in the **Action Type** field, indicates where the items are located in the receiving area. You cannot change the zone and bin field on this line.  
    -   The next line, with **Place** in the **Action Type** field, shows where you must place the items in warehouse storage. If the warehouse has received a large number of items on one receipt line, they may have to be put away in several bins, so there is a Place line for each bin.  

        If the Take and Place lines for each receipt line do not immediately follow one another, and you want them to do so, you can sort the lines by selecting **Item** in the **Sorting Method** field on the **General** FastTab.  

        If the physical layout of the warehouse reflects the bin rankings, you can use the **Bin Ranking** sorting method to prepare a put-away round that will minimize your steps through the warehouse.  

5.  When you have placed all the items in bins as instructed, choose the **Register Put-away** action.  

At locations that are set up to use directed put-away and pick, the following settings are prerequisites for the procedure above:  

- A put-away template is set up. For more information, see [How to: Set Up Put-away Templates](warehouse-how-to-set-up-put-away-templates.md).  
- The weight, cubage, and special storage requirements of the item or stockkeeping unit are defined. For more information, see Gross Weight.  
- The capacity, bin type, and bin ranking of the bins. For more information, see Bin Ranking.  

The bin ranking is taken into consideration when more than one bin matches put-away template criteria. If both the put-away template criteria and the bin ranking are the same for more than one bin, the bin with the highest number is selected.

## <a name="to-create-a-put-away-from-a-posted-receipt"></a>To create a put-away from a posted receipt  
 If your location uses both put-away processing and receive processing and you have deleted put-away lines, or if you use directed put-away and pick and have decided not to use the put-away worksheet, you can create or recreate put-away instructions for the posted receipt lines.

1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Posted Whse. Receipts**, and then choose the related link.  
2.  Select a posted receipt that might need to be put away.  
3.  Choose the **Card** action.  

    If the **Document Status** field is blank, the receipt has not been put away at all. Otherwise, the field indicates the receipt is partially put-away or completely put-away.  

4.  If the receipt is partially put away or not put away at all, choose the **Create Put-away** action.  
5.  Fill in the batch job request window to create the put-away, and then choose the **OK** button.   

## <a name="see-also"></a>See Also  
[Warehouse Management](warehouse-manage-warehouse.md)  
[Qty. on Hand](inventory-manage-inventory.md)  
[Setting Up Warehouse Management](warehouse-setup-warehouse.md)     
[Assembly Management](assembly-assemble-items.md)    
[Design Details: Warehouse Management](design-details-warehouse-management.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)
