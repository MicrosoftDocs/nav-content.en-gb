---
title: 'How to: Connect and Disconnect Incoming Document Records from Documents and Entries'
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
ms.openlocfilehash: fece4e6e38075db6d394c71418fda82a7aa082e1
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-connect-and-disconnect-incoming-document-records-from-documents-and-entries"></a>How to: Connect and Disconnect Incoming Document Records from Documents and Entries
You can store external business documents in Dynamics NAV by attaching the document files to the related incoming document records. If the document, such as a purchase invoice, did not start its existence as an incoming document record, you can still create and connect an incoming document record to it later. You can also attach incoming document files to posted purchase and sales documents and to vendor, customer, and general ledger entries by using the **Incoming Document Files** FactBox in, for example, the **Posted Purchase Invoices** and **Vendor Ledger Entries** windows.

From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files. For more information, see [How to: Find Posted Documents without Incoming Document Records](across-how-find-posted-documents-without-income-document-records.md).

The following procedures show how to attach a file to an existing purchase invoice that was not created from an incoming document record and how to attach a file to a vendor ledger entry. Attaching a file to posted purchase or sales documents works in a similar way.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-purchase-invoice"></a>To create and connect an incoming document record from a purchase invoice
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.
2. Select the line for a purchase invoice that you want to attach a file to, and then choose the **Create Incoming Document from File** action.
3. Alternatively, select the line for a purchase invoice that you want to attach a file to, and then choose the **Attach File** action.
4. In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.

## <a name="to-create-and-connect-an-incoming-document-record-from-a-vendor-ledger-entry"></a>To create and connect an incoming document record from a vendor ledger entry
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Vendor Ledger Entries**, and then choose the related link.
2. Select a line for a vendor ledger entry that you want to attach a file to, and then choose the **Create Incoming Document from File** action.
3. Alternatively, select a line for a vendor ledger entry that you want to attach a file to, and then choose the **Attach File** action.
4. In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.

## <a name="to-remove-a-connection-from-an-incoming-document-record-to-a-posted-document"></a>To remove a connection from an incoming document record to a posted document
You can remove file attachments from non-posted documents at any time by deleting the related incoming document record. If the document is posted, then you must first remove the connection from the incoming document record.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.
2. Select the line for an incoming document record connected to a posted document that you want to remove, and then choose the **Remove Reference to Record** action.

The connection to the posted document is removed. You can now proceed to connect another incoming document record to the posted document as described in this topic.

## <a name="see-also"></a>See Also  
[Process Incoming Documents](across-process-income-documents.md)  
[Incoming Documents](across-income-documents.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Work With Dynamics NAV](ui-work-product.md)

