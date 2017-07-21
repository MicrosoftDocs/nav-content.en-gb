---
title: Set Up Business Relations on Contact Companies
author: jswymer
ms.custom: na
ms.date: 09/16/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 20abe2f08fc726a008719f94389579d02ecbd275
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---
# <a name="set-up-business-relations-on-contact-companies"></a>Set Up Business Relations on Contact Companies
You can use business relations to indicate the business relationship you have with your contacts, for example, a prospect, bank, consultant, service supplier, and so on.

Using business relations on contacts is a two-step process. First, you define the business relation code. You only have to perform this step one time for each business relation. Once you have a business relation code, you can start to assign the code to contact companies.

**Note**: If you plan to synchronise your contacts with vendors, customers, or bank accounts in other parts of the application, you may want to set up a business relation for them.

## <a name="define-a-business-relation-code"></a>Define a Business Relation Code
The business relation code defines a category or type of the business relationship, such as BANK or LAW. You can have several business relation codes. To define the business relation, you use the **Business Relations** window.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Business Relations**, and then choose the related link.
2. Choose the **New** action, and fill in a code and description. The code can be a maximum of 11 characters, and can be any combination of numbers and letters.

## <a name="assign-business-relations-to-a-contact"></a>Assign Business Relations to a Contact
You cannot assign business relations to a contact person - only companies.

1. Open the contact.
2. Choose the **Company** action, and then the **Business Relations** action.

    The **Contact Business Relations** window opens.
3. In the **Business Relation Code** field, select the business relation you want to assign.

Repeat these steps to assign as many business relations as you want. You can also assign business relations from the contact list by following the same procedure.

The number of business relations you have assigned to the contact is displayed in the **No. of Business Relations** field in the **Segmentation** section in the **Contact** window.

After you have assigned business relations to your contacts, you can use this information to select contacts for your segments. For more information, see [How to: Add Contacts to Segments](marketing-add-contact-segment.md).

##<a name="see-also"></a>See Also
[Create Contact Companies](marketing-create-contact-companies.md)

