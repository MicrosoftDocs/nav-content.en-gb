---
title: Automatic Breaking Bulk with Directed Put-away and Pick
description: For locations that use directed put-away and pick, you can break a larger unit of measure into smaller units of measure, when it creates warehouse instructions that fulfil the needs of source documents, production orders, or internal picks and put-aways.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/23/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 67b292438c0b262e7baecd622909ce3fc0f7f233
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-enable-automatic-breaking-bulk-with-directed-put-away-and-pick"></a>How to: Enable Automatic Breaking Bulk with Directed Put-away and Pick
For locations that use directed put-away and pick, [!INCLUDE[d365fin](includes/d365fin_md.md)] can, in various situations, automatically breakbulk, that is, break a larger unit of measure into smaller units of measure, when it creates warehouse instructions that fulfil the needs of source documents, production orders, or internal picks and put-aways. To breakbulk sometimes also means gathering smaller units of measure, if necessary, to meet outbound requests by breaking the larger unit of measure on the source document or production order into the smaller units of measure that are available in the warehouse.   

## <a name="breakbulking-in-picks"></a>Breakbulking in Picks  
If you want to store items in several different units of measure and allow them to be automatically combined as needed in the picking process, select the **Allow Breakbulk** field on the location card.  

To fulfill a task, the program automatically looks for an item in the same unit of measure. But if it cannot find this form of the item, and this field is selected, the program will suggest that you break a larger unit of measure into the unit of measure that is needed.  

If the system can only find smaller units of measure, it will suggest that you gather items to fulfil the quantity on the shipment or production order. In effect, it breaks the larger unit of measure on the source document into smaller units for picking.  

## <a name="breakbulking-in-put-aways"></a>Breakbulking in Put-aways  
In the warehouse put-away, the program automatically suggests Place action lines in the put-away unit of measure, for example, pieces, even though the items arrive in a different unit of measure.  

## <a name="breakbulking-in-movements"></a>Breakbulking in Movements  
The program also breakbulks automatically in replenishment movements, if the **Allow Breakbulk** field is selected on the **Option** FastTab in the **Calculate Bin Replenishment** window.  

You can view the results of the conversion process from one unit of measure to another as intermediate breakbulk lines in the put-away, pick, or movement instructions.  

> [!NOTE]  
>  If you select the **Set Breakbulk Filter** field on the warehouse instruction header, the program will hide the breakbulk lines whenever the larger unit of measure is going to be completely used. For example, if a pallet is 12 pieces and you are going to use all 12 pieces, the pick will then direct you to take 1 pallet and place 12 pieces. However, if you have to pick only 9 pieces, then the breakbulk lines will not be hidden, even if you have selected the **Breakbulk Filter** field, because you have to place the remaining three pieces somewhere in the warehouse.  

> [!NOTE]  
>  If you want your units of measure to perform optimally in the warehouse, also in connection with the breakbulk functionality, you should wherever possible try to:  
>   
> - Set up the base unit of measure for an item as the smallest unit of measure that you expect to handle in your warehouse processes.  
> - Set up your alternative units of measure for the item as multiples of the base unit of measure.  

## <a name="see-also"></a>See Also  
[Warehouse Management](warehouse-manage-warehouse.md)  
[Inventory](inventory-manage-inventory.md)  
[Setting Up Warehouse Management](warehouse-setup-warehouse.md)     
[Assembly Management](assembly-assemble-items.md)    
[Design Details: Warehouse Management](design-details-warehouse-management.md)  
[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)  

