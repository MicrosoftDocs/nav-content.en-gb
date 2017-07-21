---
title: Manage Incoming Documents
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 49acc3549180b73dada6415f3ea40f17c1dd9e4c
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="manage-incoming-documents"></a>Manage Incoming Documents
Some business transactions are not recorded in Dynamics NAV from the outset. Instead, an external business document comes into your company as an e-mail attachment or a paper copy that you scan to file. This is typical of purchases, where such incoming document files represent payment receipts for expenses or small purchases.

From PDF or image files representing incoming documents, you can have an external OCR service (Optical Character Recognition) generate electronic documents that can then be converted to document records inside Dynamics NAV.

In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines. The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.

The incoming document process can consist of the following main activities:

* Record the external documents inside Dynamics NAV by creating lines in the **Incoming Documents** window in either of the following ways:
    * Manually, by using simple functions, either from a PC or from a mobile device, in one of the following ways:
        * Use the **Create from File** button, and then fill relevant fields in the **Incoming Document** window. The file is automatically attached.  
        * Use the **New** button, and then fill relevant fields in the **Incoming Document** window and manually attach the related file.
        * From a tablet or phone, use the **Create from Camera** button to create a new incoming document record, and then send the image to the OCR service, for example.
    * Automatically, by receiving the document from the OCR service as an electronic document after you have e-mailed the related PDF or image file to the OCR service. The **Financial Information** FastTab is automatically filled in the **Incoming Document** window.
* Use the OCR service to have PDF or image files turned into electronic documents that can be converted to document records in Dynamics NAV.
* Create new documents or general journal lines for incoming document records by entering the information as you read it from incoming document files.
* Attach incoming document files to purchase and sales documents of any status, including to the vendor, customer, and general ledger entries that result from posting.
* View incoming document records and their attachments from any purchase and sales document or entry, or find all general ledger entries without incoming document records from the **Chart of Accounts** window.


|To |See |
|---|----|
|Set up the Incoming Documents feature and set up the OCR service.|[How to: Set Up Incoming Documents](across-how-setup-income-documents.md)|
|Create incoming document records, attach files, use OCR to turn PDF files into electronic documents, convert electronic documents to document records, audit incoming document records from posted sales and purchase documents.|[Process Incoming Documents](across-process-income-documents.md)|

## <a name="see-also"></a>See Also  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Work With Dynamics NAV](ui-work-product.md)

