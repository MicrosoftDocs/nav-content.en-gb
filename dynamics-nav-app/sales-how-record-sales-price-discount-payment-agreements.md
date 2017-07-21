---
title: 'How to: Record Sales Prices and Discounts'
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
ms.openlocfilehash: 2d6438108fb2c36bb6f0d44efddc053bd628d068
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-record-sales-prices-and-discounts"></a>How to: Record Sales Prices and Discounts
The different price and discount agreements that apply when selling to different customers must be defined so that the agreed rules and values are applied to sales documents that you create for the customers.

Concerning prices, you can have a special sales price inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists.

Concerning discounts, you can set up and use two types of sales discounts:

|Discount Type |Description |
|--------------|------------|
|**Sales Line Discount**|An amount discount that is inserted on sales lines if a certain combination of customer, item, minimum quantity, unit of measure, or starting/ending date exists. This works in the same way as for sales prices.|
|**Invoice Discount**|A percentage discount that is subtracted from the document total if the value amount of all lines on a sales document exceeds a certain minimum.|

Because sales prices and sales line discounts are based on a combination of item and customer, you can also perform this configuration from the item card of the item where the rules and values apply.

## <a name="to-set-up-a-sales-price-for-a-customer"></a>To set up a sales price for a customer
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.
2. Open the relevant customer card, and then choose the **Prices** action.

    The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.
3. Fill in the fields on the line as necessary. Choose a field to read a short description of the field or link to more information.
4. Fill a line for each combination that will grant a special sales price to the customer.

## <a name="to-set-up-a-sales-line-discount-for-a-customer"></a>To set up a sales line discount for a customer
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.
2. Open the relevant customer card, and then choose the **Line Discounts** action.

    The **Sales Type** field is prefilled with **Customer**, and the **Sales Code** field is prefilled with the customer number.
3.  Fill in the fields on the line as necessary. Choose a field to read a short description of the field or link to more information.
4. Fill a line for each combination that will grant a sales line discount to the customer.

## <a name="to-set-up-an-invoice-discount-for-a-customer"></a>To set up an invoice discount for a customer
When you have decided which customers are eligible for invoice discounts, enter the invoice discount code on the customer cards and set up the terms for each code.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.
2. Open the customer card for a customer that will be eligible for invoice discounts.
3. In the **Invoice Disc. Code** field, select a code for the relevant invoice discount terms to use to calculate invoice discounts for the customer.

    **Note**: Invoice discount codes are represented by existing customer cards. This enables you to quickly assign invoice discount terms to customers by picking the name of another customer who will have the same terms.

    Proceed to set up new the sales invoice discount terms.
4. In the **Customer Card** window, choose the **Invoice Discounts** action. The **Cust. Invoice Discounts** window opens.
5. In the **Currency Code** field, enter the code for a currency that the invoice discount terms on the line applies to. Leave the field blank to set up invoice discount terms in GBP.
6. In the **Minimum Amount** field, enter the minimum amount that an invoice must have to be eligible for the discount.
7. In the **Discount %** field, enter the invoice discount as a percentage of the invoice amount.
8. Repeat steps 5 through 7 for each currency that the customer will receive a different invoice discount for.

The invoice discount is now set up and assigned to the customer in question. When you select the customer code in the **Invoice Disc. Code** field on other customer cards, the same invoice discount is assigned to those customers.

## <a name="see-also"></a>See Also  
[Set Up Sales](sales-setup-sales.md)  
[Manage Sales](sales-manage-sales.md)

