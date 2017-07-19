---
title: Synchronising Contacts With Customers, Vendors, and Bank Accounts
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
ms.openlocfilehash: ea22e27e3dd5a5698a37113cb1df3e408e544ddd
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---
# <a name="synchronizing-contacts-with-customers-vendors-and-bank-accounts"></a>Synchronising Contacts With Customers, Vendors, and Bank Accounts
If some of your contacts are also customers, vendors, or bank accounts, you can synchronise the contact information with the related customer, vendor, or bank account. Synchronisation makes information that is common between contacts and customers, vendors, or bank account the same.  

Before you can synchronise your contacts with customers, vendors, or bank accounts, you must specify a business relation code for customers, vendors, and bank accounts in the **Marketing Setup** window. For more information, see [Set Up Marketing and Contact Management](marketing-setup-marketing.md).

## <a name="different-ways-to-synchronize-contacts-with-customers-vendors-and-bank-accounts"></a>Different Ways to Synchronise Contacts with Customers, Vendors and Bank Accounts
You can synchronise your contacts with customers, vendors, or bank accounts by three methods:

* Link contacts with existing customers, vendors, or bank accounts from the contact card. For more information, see [How to: Link Contacts With Customers, Vendors, and Bank Accounts](marketing-how-link-contact.md).
* Create customers, vendors, or bank accounts from the contact. For more information, see [Create a Customer, Vendor, or Bank Account From a Contact](marketing-how-create-contacts-new-customers-vendors-bank-accounts.md).
*  Create contacts from customers, vendors or bank accounts. For more information, see [Create a Company Contact From a Customer, Vendor, or Bank Account](marketing-how-create-contact-companies.md).

## <a name="consequences-of-synchronization"></a>Consequences of Synchronisation
When the contact is synchronised with the customer, vendor, bank account:

* You only have to update information in one place. For example, if you modify the phone number on the contact, the phone number is automatically updated with the same modification on the customer, the vendor, or the bank account.
* If you have specified a number series for contacts, when you create a customer card, a vendor card, or a bank account card, a contact card is automatically created for the customer, vendor or bank account.
* You can create sales quotes and orders, and purchase quotes and orders from the contact.
*  You can have your interactions recorded when you perform actions such as printing orders, blanket orders, creating sales service orders, sending e-mails, and so on.
* If you delete a contact linked to a customer, vendor or bank account, only the contact is removed. The customer, vendor, or bank account remains.
* If you delete a customer, vendor, bank account linked to a contact, the contact remains.

**Note**: Some details, such as invoicing and posting details, do not appear on the contact card. Therefore, you may want to add them manually on the customer card, vendor card, or bank account card when you create contacts as customers, vendors or bank accounts.

##<a name="see-also"></a>See Also
[Manage Contacts](marketing-contacts.md)

