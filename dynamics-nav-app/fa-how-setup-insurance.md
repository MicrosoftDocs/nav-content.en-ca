---
title: 'How to: Set Up Fixed Asset Insurance'
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
ms.openlocfilehash: 44bb5f20702a01d9fbbc025889ec2bc3191813be
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-fixed-asset-insurance"></a>How to: Set Up Fixed Asset Insurance
To manage fixed asset insurance coverage, you must first set up some general insurance information and an insurance card per policy.

## <a name="to-set-up-general-insurance-information"></a>To set up general insurance information  
To use the insurance features in Dynamics NAV, you must set up some general insurance information.  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **FA Setups**, and then choose the related link.  
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.  

## <a name="to-set-up-insurance-types"></a>To set up insurance types  
You can group your insurance policies into categories, such as insurance against theft or fire insurance. The insurance types are used on the insurance card.
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Types**, and then choose the related link.  
2. Fill in the fields as necessary.

## <a name="to-set-up-insurance-cards"></a>To set up insurance cards  
You may accumulate information about each insurance policy on the insurance card.  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance**, and then choose the related link.  
2. In the **Insurance** window, choose the **New** action to create a  new insurance card.  
3. Fill in the fields as necessary.

## <a name="to-set-up-insurance-journal-templates"></a>To set up insurance journal templates  
Dynamics NAV automatically creates an insurance journal template the first time that you open the **Insurance Journal** window, but you can set up additional journal templates. For more information, see [Work with General Journals](ui-work-general-journals.md).  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Journal Templates**, and then choose the related link.  
2. Fill in the fields as necessary.

## <a name="to-set-up-insurance-journal-batches"></a>To set up insurance journal batches  
You can set up batches in an insurance journal template. The values in the journal batch are used as default values if the fields are not filled in on the journal lines. For more information, see [Work with General Journals](ui-work-general-journals.md)  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Insurance Journal Templates**, and then choose the related link.  
2. Select an insurance journal template, and then choose the **Batches** action.
3. In the **Insurance Journal Batches** window, fill in the fields as necessary.

**NOTE**: Numbers have a special function in journal names. If a journal template name or journal batch name contains a number, the number automatically advances by one every time that the journal is posted. For example, if HH1 is entered in the **Name** field, the journal name will change to HH2 after the journal named HH1 has been posted.

## <a name="see-also"></a>See Also
[Set Up Fixed Assets](fa-setup.md)  
[Manage Fixed Assets](fa-manage.md)  
[Finance](finance-setup.md)  
[Welcome to Dynamics NAV](across-get-started.md)

