---
title: Design Details - Cost Components
description: Cost components are different types of costs that make up the value of an inventory increase or decrease.
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
ms.openlocfilehash: 2971e080c0acd47bff6d7ba6f21e1a366a6de5e8
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-cost-components"></a>Design Details: Cost Components
Cost components are different types of costs that make up the value of an inventory increase or decrease.  

 The following table shows the different cost components and any subordinate cost components that they consist of.  

|Cost Component|Subordinate Cost Component|Description|  
|--------------------|--------------------------------|---------------------------------------|  
|Direct cost|Unit cost (direct purchase price)|Cost that can be traced to a cost object.|  
|Direct cost|Freight cost (item charge)|Cost that can be traced to a cost object.|  
|Direct cost|Insurance cost (item charge)|Cost that can be traced to a cost object.|  
|Indirect cost||Cost that cannot be traced to a cost object.|  
|Variance|Purchase variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Material variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Capacity variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Subcontracted variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Capacity overhead variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Variance|Manufacturing overhead variance|The difference between actual and standard costs, which is only posted for items using the **Standard** costing method.|  
|Revaluation||A depreciation or appreciation of the current inventory value.|  
|Rounding||Residuals caused by the way in which valuation of inventory decreases are calculated.|  

> [!NOTE]  
>  Freight and insurance costs are item charges that can be added to an item’s cost at any time. When you run the **Adjust Cost - Item Entries** batch job, the value of any related inventory decreases are updated accordingly.  

## <a name="see-also"></a>See Also  
 [Design Details: Inventory Costing](design-details-inventory-costing.md)   
 [Design Details: Variance](design-details-variance.md) [Managing Inventory Costs](finance-manage-inventory-costs.md)  
 [Finance](finance.md)  
 [Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

