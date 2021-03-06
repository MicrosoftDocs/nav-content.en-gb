---
title: Results of the Transfer
description: This topic describes what happens after you transfer general ledger entries to cost entries.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: general ledger, transfer, cost entries
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 05da79520b5568a8b8e63f10efce9c8b3c5395b8
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="results-of-transferring-general-ledger-entries-to-cost-entries"></a>Results of Transferring General Ledger Entries to Cost Entries
During the transfer of general ledger entries to cost entries, [!INCLUDE[d365fin](includes/d365fin_md.md)] creates connections in the entries in the **G/L Entry** table, the **Cost Entry** table, and the **Cost Register** table to make it possible to trace the connections between cost entries and general ledger entries.  

## <a name="general-ledger-entries"></a>General Ledger Entries  
For each general ledger entry that is transferred to cost accounting, [!INCLUDE[d365fin](includes/d365fin_md.md)] fills the cost **Entry No.** field.  

## <a name="cost-entries"></a>Cost Entries  
For each cost entry, [!INCLUDE[d365fin](includes/d365fin_md.md)] saves the entry number of the corresponding general ledger entry in the **G/L Entry No.** field in the **Cost Entry** table.  

For combined cost entries, [!INCLUDE[d365fin](includes/d365fin_md.md)] saves the entry number of the last general ledger entry, which is the entry with the highest entry number.  

The **G/L Account** field in the **Cost Entry** table contains the number of the general ledger account that the cost entry came from.  

For single cost entries, [!INCLUDE[d365fin](includes/d365fin_md.md)] transfers the posting text from the general ledger entry to the **Description** text field. For combined entries, the text field shows these entries are transferred as combined entries. For example, for a combined entry for the month of October in 2013, the text can be **Combined Entries, October 2013**.  

## <a name="cost-register"></a>Cost Register  
In the **Cost Register** table, [!INCLUDE[d365fin](includes/d365fin_md.md)] creates an entry with the source transfer from general ledger. The entry records the first and last entry numbers of the general ledger entries that are transferred, in addition to the first and last entry numbers of the cost entries that are created.  

## <a name="see-also"></a>See Also  
[How to: Transfer General Ledger Entries to Cost Entries](finance-how-to-transfer-general-ledger-entries-to-cost-entries.md)   
[Criteria for Transferring General Ledger Entries to Cost Entries](finance-criteria-for-transferring-general-ledger-entries-to-cost-entries.md)   
[Automatic Transfer and Combined Entries](finance-automatic-transfer-combined-entries.md)   
[Transferring and Posting Cost Entries](finance-transfer-and-post-cost-entries.md)  

