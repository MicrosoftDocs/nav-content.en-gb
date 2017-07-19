---
title: 'How to: Create Incoming Document Records'
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
ms.openlocfilehash: 10ba191b197be8b98b2d5d5ab9ac4bc3baf0d82b
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-incoming-document-records"></a>How to: Create Incoming Document Records
In the **Incoming Documents** window, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines. The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.

To record an external document in Dynamics NAV, you must first create or complete an incoming document record. You can do this manually, or you can take a photo of the external document and then create the incoming document record with the image file attached.

Before you can use the Incoming Documents feature, you must perform the required setup. For more information, see [How to: Set Up Incoming Documents](across-how-setup-income-documents.md).

## <a name="to-approve-or-reject-an-incoming-document"></a>To approve or reject an incoming document
If you do want to allow users to create invoices or general journal lines from incoming document records unless they are approved, you can set up approvers who must approve the records before they can be processed.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.
2. Select the line with the document that you want to approve or reject, and then choose the **Approve** or **Reject** actions.

If you approve the incoming document record, the **Released** check box on the incoming document line is selected. The user in charge of creating, for example, purchase invoices can proceed to process the record.

## <a name="to-create-an-incoming-document-record-by-taking-a-photo"></a>To create an incoming document record by taking a photo
**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.

1. On the app bar, choose the **Create Incoming Document from Camera** tile, and then go to step 4.
2. Alternatively, on the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.
3. In the **Incoming Documents** window, choose the ellipsis button, and then choose **Create from Camera**. The camera on the tablet or phone is activated.
4. Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.

A new incoming document record is created, with the image attached.

## <a name="to-attach-an-image-to-an-incoming-document-record-by-taking-a-photo"></a>To attach an image to an incoming document record by taking a photo
**Note**: The following procedure only applies to the Dynamics NAV Tablet and Phone clients.

1. On the app bar, choose the options button, choose **Incoming Documents**, and then choose **All**.
2. Open the card for an existing incoming document record.
3. In the **Incoming Document** window, choose the ellipsis button, and then choose **Attach Image from Camera**. The camera on the tablet or phone is activated.
4. Take a photo of a document, such as a purchase receipt, that you want to process as an incoming document, and then choose the **OK** button.

The image is attached to the incoming document record.

## <a name="to-create-an-incoming-document-record-manually"></a>To create an incoming document record manually
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Documents**, and then choose the related link.
2. Choose the **Create from File** action.  
3. In the **Insert File** window, select a file, and then choose **Open**.

    The file is automatically attached.
4. Alternatively, choose the **New** action.
5. To attach a file, choose the **Attach File** action.
6. In the **Insert File** window, select the file that represents the incoming document in question, and then choose the **Open** button.
7. In the **Incoming Document** window, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

##<a name="see-also"></a>See Also  
[Process Incoming Documents](across-process-income-documents.md)  
[Incoming Documents](across-income-documents.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Work With Dynamics NAV](ui-work-product.md)

