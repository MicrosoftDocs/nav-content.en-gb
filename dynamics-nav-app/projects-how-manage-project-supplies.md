---
title: 'How to: Manage Project Supplies'
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 00b9ed8480f6b5ab9265beb0fe2dc0060b1c3192
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-job-supplies"></a>How to: Manage Job Supplies
Managing project supplies of items, services, and expenses is an integral and critical aspect of the execution of all jobs. You can use inventory quantities or make job-specific purchases using purchase orders or purchase invoices. For example, a service job on a computer requires a new disk. You create a purchase invoice to buy a new disk and record the job that it will be used on.

If the purchase process does not require that the physical transaction be recorded separately, then a purchase may be processed in the **Job G/L Journal** window. For more information, see [How to: Record Usage for Jobs](projects-how-record-job-usage.md).

## <a name="to-purchase-items-or-services-for-a-job"></a>To purchase items or services for a job
The following procedure shows how to use a purchase invoice to purchase products for a job. The same steps apply when using a purchase order.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Invoices**, and then choose the related link.  
2. Choose the **New** action and fill in the fields as necessary. For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).
3. In the **Job No.** and **Job Task No.** fields, select the information of the job that you want to purchase items or services for.  

    The value that you select in the **Job Line Type** field defines whether a planning line is created when you post the usage of the item. If the field contains **Billable**, then job planning lines that are ready to be invoiced to the customer are created. For more information, see [How to: Invoice Jobs](projects-how-invoice-jobs.md).

4. Choose the **Post** action.

## <a name="to-view-the-value-of-purchases-for-a-job"></a>To view the value of purchases for a job  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.
2. Open a relevant job card.

    On the **Tasks** FastTab, the **Outstanding Orders** field shows the total outstanding amount, in local currency, of inventory items and services on purchase documents for the job task line.  

    The **Amt. Rec. Not Invoiced** field shows the value of items delivered on purchase documents, but not yet invoiced.  

3. Choose either of the fields to open the **Purchase Lines** window where you can review information about the related purchase document lines, including which items or services have been received.

## <a name="to-post-a-job-related-expense"></a>To post a job-related expense  
If you incur extraordinary or one-time job expenses, you can use the **Job G/L Journal** window to post them directly to the relevant job account.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Job G/L Journals**, and then choose the related link.  
2. Create a new line and enter information about the expense, including information in the **Job No.** and **Job Task No** fields.  
3. When the journal is complete, choose the **Post** action.


## <a name="see-also"></a>See Also
[Manage Projects](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics NAV](ui-work-product.md)  

