---
title: 'How to: Reconcile Payments That Cannot be Applied Automatically'
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
ms.openlocfilehash: f9fd7c2958aaa359d2f6af5dde2e8be81349e900
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-payments-that-cannot-be-applied-automatically"></a>How to: Reconcile Payments That Cannot be Applied Automatically
You may sometimes have to handle payments to your bank account that cannot be applied to a related open customer, vendor or bank account ledger entry. Reasons may be that no document exists in Dynamics NAV that the payment can be applied to, or the related document in Dynamics NAV has a different amount than the transaction amount, for example, because of currency exchange. In the **Payment Reconciliation Journal** window, all transaction amounts for payments that are not yet applied appear in the **Difference** field, including amounts that cannot be applied because of reasons such as the above.

Payments that cannot be applied can appear on payment reconciliation journal lines in the following different ways:

- The value in the **Difference** field is equal to the value in the **Transaction Amount** field, which indicates that no part of the payment can be applied to a related open customer, vendor, or bank account ledger entry.

- The value in the **Difference** field is lower than the value in the **Transaction Amount** field, which indicates that a part of the payment can be applied to a related open customer, vendor, or bank account ledger entry. The remaining part of the payment cannot be applied and must be reconciled manually or by posting it directly to an account.

To reconcile such payments, you can choose the Transfer Difference to Account button and then specify to which account the amount in the Difference field will be posted when you post the payment reconciliation journal.

**Note**: Similar functionality exists to set up automatic reconciliation of recurring payments that cannot be applied to related open customer, vendor, or bank account ledger entries. [For more information, see How to: Map Text on Recurring Payments to Accounts for Automatic Reconciliation](receivables-how-map-text-recurring-payments-accounts-auto-reconcilliation.md).

## <a name="to-reconcile-payments-that-cannot-be-applied"></a>To reconcile payments that cannot be applied
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Reconciliation Journals**, and then choose the related link.
2. Open a payment reconciliation journal. For more information, see [How to: Reconcile Payments Using Automatic Application](receivables-how-reconcile-payments-auto-application.md).
3. Choose the **Transfer Difference to Account**. The **Transfer Difference to Account** 3. window opens.
4. In the **Account Type** field, specify if the type of account that the payment amount will be posted to.
5. In the **Account No.** field, specify the account that the payment amount will be posted to.
6. In the **Description** field, specify text that describes this direct payment posting. By default, the text in the **Transaction Text** field on the payment reconciliation journal line is inserted.
7. Choose the **OK** button.

If the value in the **Difference** field was equal to the value in the **Transaction Amount** field when you post the payment reconciliation journal, the whole payment on the journal line will be posted directly to the specified balancing account.

If the value in the **Difference** field was lower than the value in the **Transaction Amount** field, then an additional journal line will be created with the same text and date and with the difference inserted in the **Transaction Amount** field. On the original journal line, the difference will be deducted from the value in the **Transaction Amount** field, and the payment will remain applied to its related customer, vendor, or bank account ledger entry. When you post the payment reconciliation journal, one part of the payment will be posted as an applied payment. The other part of the payment will be posted directly to the specified account.

## <a name="see-also"></a>See Also
[Manage Receivables](receivables-manage-receivables.md)  
[Manage Sales](sales-manage-sales.md)

