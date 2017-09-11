---
title: 'How to: Work with Nonstock Items'
author: SorenGP
ms.custom: na
ms.date: 09/29/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: 6d99e06c167d3b86db97883c02c8bf5cd746ae10
ms.contentlocale: en-gb
ms.lasthandoff: 07/19/2017

---

# How to: Work with Nonstock Items
You can offer certain items to your customers for their convenience, which you do not want to maintain in inventory until you start selling them. When you want to start maintaining such items in inventory, you can convert them to normal item cards in two ways.

- From a nonstock item card, create a new item card based on a template.
- From a sales order line with an empty **Item** field, select a nonstock item. When you post the sale, an item card is automatically created for the nonstock item.

**Note**: You cannot select a nonstock item from the **Sales Invoice** window. You can select a nonstock item from the **Sales Quote** window, but the nonstock item will not be converted to a normal item when you use the **Make Order** function.

A nonstock item typically has the item number of the vendor who supplies it. To enable conversion of a nonstock item card to a normal item card, you must first set up how vendor item numbering is converted to your own item numbering.   

## To create a nonstock item
Nonstock item cards have much less information than normal item cards because you only use them to offer on quotes and in other ways. For that reason, they must be converted to normal item cards before you can post sales transactions for them.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Nonstock Items**, and then choose the related link.
2. Choose the **New** action.
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

## To set up how nonstock item numbers are converted to your own numbering  
To enable conversion of a nonstock item card to a normal item card, you must first set up how the vendor's item numbering is converted to your own item number format.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Nonstock Item Setup**, and then choose the related link.
2. Fill in the fields as necessary.

## To convert a nonstock item to a normal item
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Nonstock Items**, and then choose the related link.
2. Open the card for a nonstock item that you want to convert to a normal item.
3. In the **Nonstock Item Card** window, choose the **Create Item** action.

A new item card prefilled with information from the nonstock item and a relevant item template is created. You can then fill or edit fields on the new item card as necessary. For more information, see [How to: Register New Products](inventory-how-register-new-products.md).

## To sell a nonstock item, and convert it to a normal item
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Orders**, and then choose the related link.
2. Choose the **New** action. fill in the fields on the **General** FastTab as for any sales order.
3. On a new sales line, leave the **Item** field empty, choose **Line**, **Functions**, and then choose **Nonstock Items**.

    The nonstock item is converted to a normal item. A new item card prefilled with information from the nonstock item and a relevant item template is created.
4. In the **Nonstock Items** window, select the nonstock item that you want to sell, and then choose the **OK** button.
5. When the sales order is complete, choose the **Post** action.

You can then fill or edit fields on the new item card as necessary. For more information, see [How to: Register New Products](inventory-how-register-new-products.md).

**Note**: A Item cross reference record is automatically created for the vendor of the item between the vendor's item number and your new item number.

## See Also
[How to: Register New Products](inventory-how-register-new-products.md)  
[Manage Inventory](inventory-manage-inventory.md)  
[Work With Dynamics NAV](ui-work-product.md)

