---
title: Posting Sales
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 0ce8b5d9e77d40a5f10c9242e7368add5b75b12a
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="posting-sales"></a>Posting Sales
In the **Posting group** on a sales document, you can choose between the following posting functions:

- **Post**
- **Test Report**
- **Post and Send**
- **Post and Print**
- **Post and Email**
- **Post Batch**
- **Preview Posting**

When you have completed all the lines and entered all the information on the sales order, you can post it. This creates a shipment and an invoice.

When a sales order is posted, the customer's account, the general ledger, and the item ledger entries are updated.

For each sales order, a sales entry is created in the **G/L Entry** table. An entry is also created in the customer's account in the **Cust. Ledger Entry** table and a general ledger entry is created in the relevant receivables account. In addition, posting the order may result in a VAT entry and a general ledger entry for the discount amount. Whether an entry for the discount is posted depends on the contents of the **Discount Posting** field in the **Sales & Receivables Setup** window.

For each sales order line, an item ledger entry will be created in the **Item Ledger Entry** table (if the sales lines contain item numbers) or a general ledger entry will be created in the **G/L Entry** table (if the sales lines contain a general ledger account). In addition to this, sales orders are always recorded in the **Sales Shipment Header** and **Sales Invoice Header** tables.

**Important**: When you post an order, you can create both a shipment and an invoice. These can be done at the same time or independently. You can also create a partial shipment and a partial invoice by completing the **Qty. to Ship** and **Qty. to Invoice** fields on the individual sales order lines before you post. Note that you cannot create an invoice for something that is not shipped. That is, before you can invoice, you must have recorded a shipment, or you must choose to ship and invoice at the same time. 

When the posting is completed, the posted sales lines are removed from the order. A message tells you when the posting is completed. After this, you will be able to see the posted entries in the various windows that contain posted entries, such as the **Cust. Ledger Entries**, **G/L Entries**, **Item Ledger Entries**, **Posted Sales Shipments**, and **Posted Sales Invoices** windows.

## <a name="see-also"></a>See Also
[How to: Send Documents by Email](ui-how-send-documents-email.md)

