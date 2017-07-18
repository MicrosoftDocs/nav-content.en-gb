---
title: 'How to: Register New Products'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: df84a4d3e15035cd956c7612a12069844f5601d2
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-register-new-products"></a>How to: Register New Products

Products are the basis of your business, the goods or services that you trade in. Each product must be registered as an item card.

**Note**: In Dynamics NAV, a product is referred to using the term “item”.

Item cards hold the information that is required to buy, store, sell, deliver, and account for products.

The item card can be of type Inventory or Service to specify if the product is a physical unit or labour time unit. Apart from some fields that relate to the physical aspects of an item, all fields on an item card function in the same way for inventory items and services. For more information about selling an item, see [How to: Sell Products](sales-how-sell-products.md) or [How to: Invoice Sales](sales-how-invoice-sales.md).

**Note**: If item templates exist for different item types, then a window appears when you create a new item card from where you can select an appropriate template. If only one item template exists, then new item cards always use that template.

## <a name="to-create-a-new-item-card"></a>To create a new item card
1. On the Home page, choose the **Items** action to open the list of existing items.  
2. In the **Items** window, choose the **New** action.

    If only one item template exists, then a new item card opens with some fields filled with information from the template.
3. In the **Select a template for a new item** window, choose the template that you want to use for the new item card.
4. Choose the **OK** button. A new item card opens with some fields filled with information from the template.
5. Proceed to fill or change fields on the item card as necessary. Choose a field to read a short description of the field or link to more information.

On the **Sales Prices** FastTab, you can view special prices or discounts that you grant for the item if certain criteria are met, such as customer, minimum order quantity, or ending date. Each row represents a special price or line discount. Each column represents a criterion that must apply to warrant the special price that you enter in the **Unit Price** field, or the line discount that you enter in the **Line Discount %** field. For more information, see [Record Sales Price, Discount, and Payment Agreements](sales-how-record-sales-price-discount-payment-agreements.md).

The item is now registered, and the item card is ready to be used on purchase and sales documents.

If you want to use this item card as a template when you create new item cards, you can save it as a template. For more information, see the following section.

## <a name="to-save-the-item-card-as-a-template"></a>To save the item card as a template
1. In the **Item Card** window, choose the **Save as Template** action. The **Item Template** window opens showing the item card as a template.
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.
3. To reuse dimensions in templates, choose the **Dimensions** action. The **Dimension Templates** window opens showing any dimension codes that are set up for the item.
4. Edit or enter dimension codes that will apply to new item cards created by using the template.
5. When you have completed the new item template, choose the **OK** button.

The item template is added to the list of item templates, so that you can use it to create new item cards.

## <a name="see-also"></a>See Also
  [Manage Inventory](inventory-manage-inventory.md)  
  [Manage Purchasing](purchasing-manage-purchasing.md)  
  [Manage Sales](sales-manage-sales.md)

