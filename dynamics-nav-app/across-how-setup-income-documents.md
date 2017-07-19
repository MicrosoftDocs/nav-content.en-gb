---
title: 'How to: Set Up Incoming Documents'
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
ms.openlocfilehash: 2bce97c76876c86a576ec6a281a306a46881027c
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-incoming-documents"></a>How to: Set Up Incoming Documents
If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.

If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.

To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.

When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines. The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries. For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).

## <a name="to-set-up-the-incoming-documents-feature"></a>To set up the Incoming Documents feature
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

## <a name="to-set-up-approvers-of-incoming-document-records"></a>To set up approvers of incoming document records
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.  
2. In the **Incoming Documents Setup** window, choose the **Approvers** action.

    The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .  
3. Select one or more users that can approve an incoming document before a related document or journal line can be created.

When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.

**Note**: This approval setup is not related to approval workflows. For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).

## <a name="to-set-up-an-ocr-service"></a>To set up an OCR service
1. In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.


## <a name="to-encrypt-your-login-information"></a>To encrypt your login information
It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window. You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.

1. In the **OCR Service Setup** window, choose the **Encryption Management** action.
2. In the **Data Encryption Management** window, enable encryption of your data.

## <a name="see-also"></a>See Also  
[Process Incoming Documents](across-process-income-documents.md)  
[Incoming Documents](across-income-documents.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Work With Dynamics NAV](ui-work-product.md)

