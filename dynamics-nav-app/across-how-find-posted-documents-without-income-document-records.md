---
title: 'How to: Find Posted Documents without Incoming Document Records'
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
ms.openlocfilehash: eb65922decc86ca6834cae4cf46c6f2ff492e29c
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-find-posted-documents-without-incoming-document-records"></a>How to: Find Posted Documents without Incoming Document Records
From the **Chart of Accounts** and **General Ledger Entries** windows, you can use a search function to find general ledger entries for posted purchase and sales documents that do not have incoming document records and then centrally link to existing records or create new ones with attached document files.

## <a name="to-find-posted-documents-without-incoming-document-records"></a>To find posted documents without incoming document records
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.
2. Select a line for a G/L account for whose general ledger entries you want to see posted purchase and sales documents without incoming document records, and then choose the **Posted Documents without Incoming Document** action.
3. Alternatively, choose the **Ledger Entries** action.
4. In the **General Ledger Entries** window, choose the **Posted Documents without Incoming Documents** action.

The **Posted Documents without Incoming Document** window opens showing posted purchase and sales documents without incoming document records represented by general ledger entries on the G/L account that you opened the window for. The window can show a maximum of 1000 lines. By default, the **Date Filter** field therefore contains a filter that limits the lines to entries with posting dates from the beginning of the accounting period to the work date.

## <a name="to-connect-found-documents-to-existing-incoming-document-records"></a>To connect found documents to existing incoming document records
1. In the **Posted Documents without Incoming Document** window, select the line for a posted document that you want to connect to an existing incoming document record, and then choose the **Select Incoming Document** action.
2. In the **Incoming Documents** window, select the incoming document record that you want to connect to posted document found, and then choose the **OK** button.
3. In the **Posted Documents without Incoming Document** window, the selected incoming document record is now connected to the posted document, as you can see in the **Incoming Document Files** FactBox.

If a relevant incoming document record does not exist in the **Incoming Documents** window, then you can create it. For more information, see [How to: Create Incoming Document Records](across-how-create-income-document-records.md).

## <a name="see-also"></a>See Also  
[Process Incoming Documents](across-process-income-documents.md)  
[Incoming Documents](across-income-documents.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)  
[Work With Dynamics NAV](ui-work-product.md)

