---
title: 'How to: Send Documents by Email'
author: SorenGP
ms.custom: na
ms.date: 11/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: e4476c2ab903001017dcd6c8bdaa84892ba79c9e
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-send-documents-by-email"></a>How to: Send Documents by Email
To communicate the contents of business documents quickly to your business partners, such as the payment information on sales documents to customers, you can use the Report Layout feature to define document-specific content that gets inserted in email bodies automatically.

To enable emails from within Dynamics NAV, start the **Set Up Email** assisted setup on the Home page.

You can email practically all document types as attachments to email messages directly from the window that shows the document. In addition to the attachment, you can set up document-specific email bodies with core information from the document preceded by standard text that greets the mail recipient and introduces the document in question. To offer your customers to pay for sales electronically using a payment service, such as PayPal, you can also have the PayPal information and hyperlink inserted in the email body.

From all supported documents, you initiate emailing by choosing the **Send** action, on posted documents, or the **Post and Send** action, on non-posted documents.

If the **Email** field in the **Send Document To** window is set to **Yes (Prompt for Settings)**, then the **Send Email** window opens prefilled with the contact person in the **To:** field and the document attached as a PDF file. In the **Body** field, you can either enter text manually or you can have the field filled with a document-specific email body that you have set up.

The following procedure describes how to set the **Sales - Invoice** report up to be used for document-specific email bodies when you email posted sales invoices.

## <a name="to-set-up-a-document-specific-email-body-for-sales-invoices"></a>To set up a document-specific email body for sales invoices
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Report Selections Sales**, and then choose the related link.
2. In the **Report Selection - Sales** window, in the **Usage** field, select **Invoice**.
3. On a new line, in the **Report ID** field, select, for example, standard report 1306.
4. Select the **Use for mail Body** check box.
5. Choose the **Email Body Layout ID** field, and then select one of the available layouts from the **Custom Report Layouts** window.
6. Report layouts define both the style and the content of the email body, including the standard text that precedes the core document information in the email body.
7. To view or edit the layout that the email body is based on, in the **Custom Report Layouts** window, choose the **Edit Layout** action.
8. If you want to offer customers to pay for sales electronically, you can set up the related payment service, such as PayPal, and then have the PayPal information and hyperlink inserted in the email body as well. For more information, see [How to: Enable Customer Payments Through PayPal](sales-how-enable-customer-payments-paypal.md).
9. Choose the **OK** button.

Now, when you choose, for example, the Send action in the **Posted Sales Invoice** window, the email body will contain the document information of report 1306 preceded by styled standard text according to the report layout that you selected in step 5.

The following procedure describes how to send a posted sales invoice as an email message with the document attached as a PDF file and with a document-specific email body.
## <a name="to-send-documents-by-email"></a>To send documents by email
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Posted Sales Invoices**, and then choose the related link.
2. Select the relevant sales invoice, choose the **Send** action. The **Send Document to** window opens.
3. In the **Email** field, select **Yes (Prompt for Settings)**. For more information, see [How to: Set Up Document Sending Profiles](sales-how-setup-document-send-profiles.md).
4. Choose the **OK** button. The **Send Email** window opens.
5. In the **To:** field, enter a valid email address. The default value is the customer email address.
6. In the **Cc:** field, specify an email address to have a copy of the email message sent to another recipient.
7. In the **Bcc:** field, specify an email address to have a copy of the email sent to another recipient without that email address and name appearing to other recipients.
8. In the **Subject** field, enter a descriptive subject text. The default value is the customer name and invoice number.
9. In the **Attachment** field, the generated invoice is attached by default as a PDF file. Choose the lookup button to open the file or attach another one.
10. In the **Body** field, enter a short message to the recipient.

    If a document-specific email body is set up in the **Report Selection - Sales** window, then the **Body** field is filled automatically. For more information, see the “To set up a document-specific email body for sales invoices” section in this topic.
11. Select the **Edit in Outlook Web App** check box to open the email message in the email app for Office 365.
12. Choose the **OK** button to send the email message.

**Note**: If you do not need to specify email settings each time you email a document, you can select the **Yes (Use Default Settings)** option in the Email field in the **Send Document To** window. In that case, the **Send Email** window will not open. See Step 4. For more information, see [How to: Set Up Document Sending Profiles](sales-how-setup-document-send-profiles.md).

## <a name="see-also"></a>See Also  
[Work with Dynamics NAV](ui-work-product.md)  
[How to: Invoice Sales](sales-how-invoice-sales.md)

