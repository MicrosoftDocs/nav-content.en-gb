---
title: Design Details - Handling Reordering Policies
description: Overview of tasks for defining a reorder policy in supply planning.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 2cd1d0e770e5fd7daa92e98486038aefdb678c5a
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="design-details-handling-reordering-policies"></a>Design Details: Handling Reordering Policies
For an item to participate in supply planning, a reorder policy must be defined. The following four reordering policies exist:  
  
* Fixed Reorder Qty.  
* Maximum Qty.  
* Order  
* Lot-for-Lot  
  
Fixed Reorder Qty. and Maximum Qty. policies relate to inventory planning. Although inventory planning is technically simpler than the balancing procedure, these policies must coexist with the step-by-step balancing of supply and order tracking. To control the integration between the two, and to provide visibility into the involved planning logic, strict principles govern how reordering policies are handled.  
  
## <a name="in-this-section"></a>In This Section  
[Design Details: The Role of the Reorder Point](design-details-the-role-of-the-reorder-point.md)  
[Design Details: Monitoring the Projected Inventory Level and the Reorder Point](design-details-monitoring-the-projected-inventory-level-and-the-reorder-point.md)  
[Design Details: The Role of the Time Bucket](design-details-the-role-of-the-time-bucket.md)  
[Design Details: Staying under the Overflow Level](design-details-staying-under-the-overflow-level.md)  
[Design Details: Handling Projected Negative Inventory](design-details-handling-projected-negative-inventory.md)  
[Design Details: Reordering Policies](design-details-reordering-policies.md)  
  
## <a name="see-also"></a>See Also  
[Design Details: Planning Parameters](design-details-planning-parameters.md)   
[Design Details: Planning Assignment Table](design-details-planning-assignment-table.md)   
[Design Details: Central Concepts of the Planning System](design-details-central-concepts-of-the-planning-system.md)   
[Design Details: Balancing Demand and Supply](design-details-balancing-demand-and-supply.md)   
[Design Details: Supply Planning](design-details-supply-planning.md)
