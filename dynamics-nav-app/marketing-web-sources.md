---
title: Set Up Web Sources for Contact Companies
author: edupont04
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 98e70d4dd5022a69e8ba5e53ad32c00d12578e31
ms.contentlocale: en-ca
ms.lasthandoff: 06/26/2017

---
# <a name="set-up-web-sources-for-contact-companies"></a>Set Up Web Sources for Contact Companies
You can use web sources with your contact companies to identify, for example, search engines and web sites, on the Internet that you want to use to search for information about the contacts. When assigning web sources, you specify which search engine and search word the application will use to find the requested information.

Using web sources on contacts is a two-step process. First, you define the web source code. You only have to perform this step one time for each web source. Once you have a web source code, you can start to assign the code to contact persons.

## <a name="define-a-web-source-code"></a>Define a Web Source Code
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Web Sources**, and then choose the related link.
2. Choose the **New** actions.
3. Fill in the **Code**, **Description**, and **URL** fields.

  Type %1 in the **URL** field to insert a placeholder for a search word in the URL. When you launch the web source from a contact, the %1 is replaced with the search word, for example, the name of the company that you have entered in the **Contact Web Sources** window.

Repeat these steps to set up as many web sources as you want.

## <a name="assign-web-sources-to-a-contact-company"></a>Assign Web Sources to a Contact Company
When assigning web sources, you specify which search engine and search word that the application will use to find the requested information.

1. Open the contact.
2. Choose the **Company** action, and then choose the **Web Sources** action. The **Contact Web Sources** window opens.
3. In the **Web Source Code** field, choose the web source you want to assign.
4. In the **Search Word** field, enter the search word that you want to use to find the information.

Repeat these steps to assign as many web sources as you want.

You can also assign web sources from the **Contact List** window by following the same procedure.

##<a name="see-also"></a>See Also
[Create Contact Companies](marketing-create-contact-companies.md)

