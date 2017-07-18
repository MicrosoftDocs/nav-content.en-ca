---
title: 'How to: Set Up a Coloured Indicator on Cues'
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 04272431b01c0ab398618d9878b90d73e6324abe
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---
    
# <a name="how-to-set-up-a-colored-indicator-on-cues"></a>How to: Set Up a Coloured Indicator on Cues
You can set up Cues that appear on the **Home** page to include an indicator that changes colour based on the data values in the Cues. 

The indicator appears as a coloured bar along the top border of the Cue tile. It provides a visual signal of the status of the Cue's activity, which can indicate favourable or unfavourable conditions to prompt the user to take action. For example, if a Cue displays ongoing sales invoices, you can set up the indicator to appear green (favourable) when total number of ongoing sales invoices is below 10, and appears red (unfavourable) when the total is greater than 20.

From the **Cue Setup** window, you set up indicators for all the Cues that are available in the company database.

To set up the indicator, you specify up to two threshold values that define three ranges of data values (low, middle, and high) to which you can apply a different colour (or style).

## <a name="to-set-up-colored-indicators-on-cues"></a>To set up coloured indicators on Cues
1. Under **Activities** on your **Home** page, choose **Set Up Cues**.  
The **Cue Setup** window appears. The window lists the indicators that are currently setup up on Cues.
2. To modify an indicator, edit the fields and modify, for example, the values for the different thresholds.  

The following table lists the colours that correspond to the options of the **Low Range Style**, **Middle Range Style**, and **High Range Style** fields.

|Option|Colour|
|------|-----|
|**None**|No colour (same colour as the Cue tile|
|**Favorable**|Green|
|**Unfavorable**|Red|
|**Ambiguous**|Yellow|
|**Subordinate**|Grey|

## <a name="see-also"></a>See Also
[Work with Dynamics NAV](ui-work-product.md)


