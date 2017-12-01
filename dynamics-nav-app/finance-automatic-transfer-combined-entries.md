---
title: Automatic Transfer and Combined Entries
description: In cost accounting, you can transfer general ledger entries to a cost type by using a combined posting. You can specify if a cost type receives combined entries in the **Combine Entries** field in the cost type definition. The following table describes the different options.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 638fc123d4113695d70102a94b9fce0bff6b43fa
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="automatic-transfer-and-combined-entries"></a>Automatic Transfer and Combined Entries
In cost accounting, you can transfer general ledger entries to a cost type by using a combined posting. You can specify if a cost type receives combined entries in the **Combine Entries** field in the cost type definition. The following table describes the different options.  

|Combine entries|Description|  
|---------------------|-----------------|  
|None|Each general ledger entry is transferred individually to the corresponding cost type.|  
|Day|General ledger entries with the same posting date are transferred as one entry to the corresponding cost type.|  
|Month|All general ledger entries in the same calendar month are transferred as one entry to the corresponding cost type.|  

> [!IMPORTANT]  
>  If you have selected the **Auto Transfer from G/L** check box in the **Cost Accounting Setup** window, [!INCLUDE[d365fin](includes/d365fin_md.md)] updates the cost accounting after every posting in the general ledger. Combined entries are not possible.  

## <a name="see-also"></a>See Also  
 [How to: Transfer General Ledger Entries to Cost Entries](finance-how-to-transfer-general-ledger-entries-to-cost-entries.md)   
 [Criteria for Transferring General Ledger Entries to Cost Entries](finance-criteria-for-transferring-general-ledger-entries-to-cost-entries.md)   
 [Results of the Transfer](finance-results-of-the-transfer.md)   
 [Transferring and Posting Cost Entries](finance-transfer-and-post-cost-entries.md)  
 [Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)

