---
title: 'How to: Suggest Vendor Payments'
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
ms.openlocfilehash: 11bfba9f279f6bd84c5d169f6f97fd48759bc6df
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-suggest-vendor-payments"></a>How to: Suggest Vendor Payments
In the **Payment Journal** window, you can use a function to suggest payment lines according to your settings, such as payments that are due soon or payments where a payment discount is available.

To benefit fully from the Suggest Vendor Payments function, you must first prioritise your vendors. For more information, see [How to: Prioritise Vendors](purchasing-how-prioritize-vendors.md).

Vendor entries that are not marked **On Hold** are not included in the batch job.  

**Important**: If you want to take advantage of payment discounts and have entered an available amount, the amount will be used for prioritised overdue vendor entries first in order of priority, and then for overdue vendor entries that are not prioritised, and finally for open vendor entries that qualify for payment discounts in order of vendor number.

## <a name="to-use-the-suggest-vendor-payments-function"></a>To use the Suggest Vendor Payments function
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journals**, and then choose the related link.
2. Open the relevant journal, and then choose the **Suggest Vendor Payments** action.
3. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.
4. Choose the **OK** button.

## <a name="to-insert-the-due-date-as-posting-date-on-payment-journal-lines"></a>To insert the due date as posting date on payment journal lines
When you use the **Suggest Vendor Payments** batch job to create payment lines for your vendors, you can fill two special fields to make sure that the generated lines use the due date to calculate the posting date. These fields are **Calculate Posting Date from Applies-to-Doc Due Date** and **Applies-to-Doc Due Date Offset**.

**Important**: You cannot use the **Calculate Posting Date from Applies-to-Doc Due Date** field together with the **Find Payment Discounts** field or the **Summarise per Vendor** field. The reason is that if the posting date is based on the due date, then some payment discount may not be calculated correctly, because the posting date could occur after the payment discount date.
Also, if the calculated posting date occurs in the past, then the posting date will be moved up to the work date, and a warning is displayed.

Alternatively, you can also manually create payment lines using the due date to calculate the posting date. After you have applied vendor ledger entries, you can use the **Calculate Posting Date** action. This will update the posting date on the journal line with the due date of the related purchase invoice. For more information, see [How to: Apply Purchase Transactions Manually](payables-how-apply-purchase-transactions-manually.md).  

**Note**: If the purchase invoice is overdue, then the posting date will be set to the work date, and the font on the line will change to red colour.

## <a name="see-also"></a>See Also
[Manage Payables](payables-manage-payables.md)  
[Make Payments](payables-make-payments.md)  
[Work with General Journals](ui-work-general-journals.md)

