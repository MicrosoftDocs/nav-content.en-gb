---
title: Apply Entries in Different Currencies
description: You can apply ledger entries in multiple currencies, for example, if you sell in one currency and receive payment in another.
documentationcenter: 
author: edupont04
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: multiple currencies, payment, reconcile
ms.date: 06/02/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: f323b98472f3e2ef0f28000f8a9140b066206945
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-application-of-ledger-entries-in-different-currencies"></a>How to: Enable Application of Ledger Entries in Different Currencies
If you purchase from a vendor in one currency and submit payment in another currency, you can apply the payment to the purchase.

Likewise, if you sell to a customer in one currency and receive payment in another currency, you can apply the payment to the sales invoice.

The following procedure describes how to set this up for vendor ledger entries in the **Purchases & Payables Setup** window. The setup is similar for customer ledger entries in the **Sales & Receivables Setup** window.

## <a name="to-enable-application-of-vendor-ledger-entries-in-different-currencies"></a>To enable application of vendor ledger entries in different currencies
1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Purchases & Payables Setup**, and then choose the related link.
2. In the **Appln. between Currencies** field, select one of the following options.

| Option | Description |
| --- | --- |
| None |Application between currencies is not allowed. |
| EMU |Application between EMU currencies is allowed. |
| All |Application between all currencies is allowed. |

## <a name="to-set-up-gl-accounts-for-currency-application-rounding-differences"></a>To set up G/L accounts for currency application rounding differences  
If you apply entries in different currencies, you must set up the general ledger accounts to which you want to post rounding differences.  

> [!NOTE]  
>  You must set up the general ledger accounts before you complete the task. For more information, see [Understanding the General Ledger and the Chart of Accounts](finance-general-ledger.md).

1. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customer Posting Groups**, and then choose the related link.  
2. In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.  
3. Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Vendor Posting Groups**, and then choose the related link.  
4. In the **Debit Curr. Appln. Rndg. Acc.** and **Credit Curr. Appln. Rndg. Acc.** fields, enter the relevant general ledger accounts to post rounding differences.  

## <a name="see-also"></a>See Also
[Managing Payables](payables-manage-payables.md)  
[Managing Receivables](receivables-manage-receivables.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

