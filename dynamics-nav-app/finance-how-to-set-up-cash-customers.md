---
title: How to Set Up Cash Customers
description: This topic describes the steps to set up customer who pays in cash.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/11/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: dca1e2b58d22a9d27766a731a085278f1200b570
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-set-up-cash-customers"></a>How to: Set Up Cash Customers
You cannot create an invoice without a customer number. This is true, even if you make a cash sale and do not have anything to record in a customer account.  

## <a name="to-set-up-a-cash-customer"></a>To set up a cash customer  
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer**, and then choose the related link.  
2.  Create a new **Customer** card. For more information, see [How to: Register New Customers](sales-how-register-new-customers.md).
3.  In the **No.** field, enter **Cash**, for example.  
4.  In the **Name** field, enter **Cash Sale**, for example.  
5.  On the **Invoicing** FastTab, fill in the **Customer Posting Group** and the **Gen. Bus. Posting Group** fields.  

 Now you have set up a customer that contains sufficient information for invoicing.  

> [!NOTE]  
>  You may have chosen a posting group that is also used for domestic credit sales. If you want to maintain separate data on cash sales, for example, with a special sales or receivables account, you can set up an extra posting group for this purpose.  
>   
>  You must enter a number for a receivables account for the posting group, even though the balance in this account will always be 0 after you post an invoice.  

## <a name="see-also"></a>See Also
[Managing Receivables](receivables-manage-receivables.md)  
[How to: Register New Customers](sales-how-register-new-customers.md)    
[Finance](finance.md)  


