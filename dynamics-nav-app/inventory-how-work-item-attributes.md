---
title: 'How to: Work with Item Attributes'
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
ms.openlocfilehash: eaf539f1d4d00c2cd5679f39f29a3428e33ee1fd
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-work-with-item-attributes"></a>How to: Work with Item Attributes
When customers inquire about an item, either in correspondence or in an integrated web shop, they may ask or search according to characteristics, such as height and model year. To provide this customer service, you can assign item attribute values of different types to your items, which can then be used when searching for items.

You can also assign item attributes to item categories, which then apply to the items that use the item categories. For more information, see [How to: Categorize Item](inventory-how-categorize-items.md).

## <a name="to-create-item-attributes"></a>To create item attributes
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Item Attributes**, and then choose the related link.
2. In the **Item Attributes** window, choose the **New** action.
3. In the **Item Attribute** window, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

**Note**: If you select **Option** in the **Type** field, then you can choose the **Item Attribute Values** action to create values for the item attribute. For more information, see the "To create values for item attributes of type Option" section.  

## <a name="to-create-values-for-item-attributes-of-type-option"></a>To create values for item attributes of type Option
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Item Attributes**, and then choose the related link.
2. In the **Item Attributes** window, select an item attribute of type Option that you want to create values for, and then choose the **Item Attribute Values** action.
3. In the **Item Attribute Values** window, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.

## <a name="to-assign-item-attributes-to-items"></a>To assign item attributes to items
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Items**, and then choose the related link.
2. In the **Items** window, select the item that you want to assign item attributes to, and then choose the **Attributes** action.
3. In the **Item Attribute Values** window, choose the **New** action.
4. Choose the AssistEdit button in the **Attribute** field and select an existing item attribute. Alternatively, choose the **New** action to first create a new item attribute as explained in the "To create item attributes" section.
5. In the **Value** field, enter the item attribute value, such as "2010" for the Model Year attribute.
6. For item attributes of type Option, choose the AssistEdit button in the **Value** field and select an item attribute value. Alternatively, choose the **New** action to first create a new item attribute value as explained in the "To create values for item attributes of type Option" section.
7. Repeat steps 4 through 6 for all item attributes that you want to assign to the item.

## <a name="to-assign-item-attributes-to-item-categories"></a>To assign item attributes to item categories
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Item Categories**, and then choose the related link.
2. In the **Item Categories** window, select the item category that you want to assign item attributes to, and then choose the **Edit** action.
3. In the **Item Category Card** window, on the **Attributes** FastTab, choose the **New** action.
4. Choose the AssistEdit button in the **Attribute** field and select an existing item attribute. Alternatively, choose the **New** action to first create a new item attribute as explained in the "To create an item attribute" section.
5. In the **Default Value** field, choose the AssistEdit button and select an item attribute value.
6. Repeat steps 4 and 5 for all item attributes that you want to assign to the item category.

**Note**: Item attributes for parent item categories will be inherited to child item categories. This is indicated by the **Inherited From** field on the **Attributes** FastTab. For more information, see [How to: Categorize Item](inventory-how-categorize-items.md).

## <a name="to-filter-by-item-attributes"></a>To filter by item attributes
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Items**, and then choose the related link.
2. In the **Items** window, choose the **Filter by Attributes** action.
3. In the **Filter Items by Attribute** window, choose the AssistEdit button in the **Attribute** field and select an item attribute.
4. In the **Value** field, choose the AssistEdit button and select an attribute value to filter items by.

    **Note**: You can only select values directly for item attributes that have fixed values, such as Colour. For item attributes that have variable values, such as Width, you must specify the item attribute value by first selecting a condition. See step 5.
5. In the **Value** field for a variable item attribute, choose the AssistEdit button.
6. In the **Specify Filter Value** window, in the **Condition** field, choose the drop-down arrow and select a condition.
7. In the **Value** field, enter an attribute value to filter items by.

    **Example**: To filter on items where the material description begins with "blue", fill in the fields as follows: **Attribute** field: Material Description, **Condition** field: Begins With, **Value** field: blue.
8. Choose the **OK** button.   

The items in the **Items** window are filtered by the specified item attribute values.

## <a name="see-also"></a>See Also
[How to: Categorize Item](inventory-how-categorize-items.md)    
[How to: Register New Products](inventory-how-register-new-products.md)  
[Manage Inventory](inventory-manage-inventory.md)  
[Work With Dynamics NAV](ui-work-product.md)

