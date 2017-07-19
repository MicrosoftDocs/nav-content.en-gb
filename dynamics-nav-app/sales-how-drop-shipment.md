---
title: 'How to: Make Drop Shipments'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f636de789dc6b006a449ec59c390fab85e62b443
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-make-drop-shipments"></a>How to: Make Drop Shipments
A drop shipment is the shipment of items from one of your vendors directly to one of your customers.

When a sales order is marked for drop shipment, and you create a purchase order specifying the customer in the **Sell-to Customer No.** field, then you can link the two documents and thereby instruct the vendor to ship directly to the customer.

## <a name="to-create-a-sales-order-for-drop-shipment"></a>To create a sales order for drop shipment
To prepare a drop shipment, you create a sales order for an item as normal, except you must indicate on the sales line that the sale requires drop shipment.

1. Create a sales order for an item. For more information, see [How to: Sell Products](sales-how-sell-products.md).
2. On the sales order line for the drop-shipment item, select the **Drop Shipment** check box.

## <a name="to-create-the-purchase-order-for-drop-shipment"></a>To create the purchase order for drop shipment
To prepare a drop shipment for the item to be sold, you create a purchase order as normal, except you must indicate on the purchase order that it must be shipped to your customer, not to yourself.

1. Create a purchase order. Do not fill any fields on the lines. For more information, see [How to: Record Purchases](purchasing-how-record-purchases.md).
2. In the **Sell-to Customer No.** field, select the customer that you are selling to.
3. Choose the **Drop Shipments** action, and then choose the **Get Sales Order** action.
4. In the **Sales List** window, select the sales order that you prepared in the "To create a sales order for drop shipment" section.
5. Choose the **OK** button.

The line information from the sales order is inserted on the purchase order line(s).

You can now instruct the vendor to ship the items to your customer, for example, by mailing the purchase order as a PDF.     

## <a name="to-view-the-linked-purchase-order-from-the-sales-order"></a>To view the linked purchase order from the sales order
1. Select the drop-shipment sales order line, choose the **Order** action, choose the **Drop Shipment** action, and then choose the **Purchase Order** action.

The linked purchase order opens.

## <a name="to-post-a-drop-shipment"></a>To post a drop shipment
When the vendor has shipped the items, you can post the sales order as shipped. You can also post the purchase order, but only with the **Receive** option until the sales order has been invoiced.
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Sales orders**, and then choose the related link.
2. Open the sales order that you created in the "To create a sales order for a drop shipment" section.
3. In the **Qty. to Ship** field, specify how many of the order quantity to ship, the full or a partial order quantity.
3. Choose the **Post** or **Post and Send** action.
4. Choose either the **Ship** option to invoice later, or the **Ship and Invoice** option to invoice immediately.

## <a name="see-also"></a>See Also
[How to: Sell Products](sales-how-sell-products.md)    
[How to: Record Purchases](purchasing-how-record-purchases.md)  
[Manage Sales](sales-manage-sales.md)  
[Manage Inventory](inventory-manage-inventory.md)      
[Work with Dynamics NAV](ui-work-product.md)

