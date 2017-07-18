---
title: 'How to: Reconcile Customer Payments Manually'
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
ms.openlocfilehash: de0c94386ad5a0bbfba5cc0516fa7faa5cdcc0b4
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-reconcile-customer-payments-manually"></a>How to: Reconcile Customer Payments Manually
When you receive a cash receipt from a customer or you make a cash refund to a customer, you must decide whether to apply the payment or refund to one or more open debit or credit entries. You can specify the exact amount you want to apply. For example, you may only want to apply part of the payment and thereby only partly apply customer ledger entries. It is important at some stage to close (apply) all customer ledger entries in order to obtain correct customer statistics and printouts of the account statements and finance-setup charges.

You can apply customer ledger entries in three different ways:

- By entering information in dedicated windows, such as the **Cash Receipt Journal** window and the **Payment Reconciliation Journal** window.
- From sales credit memo documents.
- From customer ledger entries after sales documents are posted but not applied.

**Note**: If the **Application Method** field on the customer card contains **Apply to Oldest**, then payments will automatically be applied to the oldest open credit entry if you do not manually specify which entry to apply to. If the application method for a customer is **Manual**, then you must apply entries manually.

You can apply customer payments manually in the **Cash Receipt Journal** window. A cash receipt journal is a type of general journal, so you can use it to post transactions to general ledger, bank, customer, vendor, and fixed assets accounts. You can apply the payment to one or more debit entries when you post the payment, or you can apply from the posted entries later.

You can also apply customer payments, and vendor payments, in the **Payment Reconciliation Journal** window using functions for bank statement import, automatic application, and bank account reconciliation. For more information, see [Reconcile Payments Using Automatic Application](receivables-how-reconcile-payments-auto-application.md). Alternatively, you can reconcile customer payments based on a list of unpaid sales documents in the **Payment Registration** window. For more information, see [How to: Reconcile Customer Payments From a List of Unpaid Sales Documents](receivables-how-reconcile-customer-payments-list-unpaid-sales-documents.md).

## <a name="to-fill-and-post-a-cash-receipt-journal"></a>To fill and post a cash receipt journal
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Cash Receipt Journal**, and then choose the related link.
2. Select the relevant batch in the **Batch Name** field.
3. Fill in the **Posting Date** field.  
4. In the **Document Type** field, select **Payment**.

    The **Document No.** field is filled by the number series assigned to the batch.
5. Use the **External Document No.** field to store an identifier, such as the customer's cheque number.
6. In the **Account Type** field, select **Customer**.
7. In the **Account No.** field, select the relevant G/L account.
8. If you want to post the application at the same time as you post the journal, do one of the following.
9. In the **Balancing Account Type** field, select **G/L Account** for cash payments, and **Bank Account** for other payments.
10. In the **Balancing Account No.** field, select the cash account for cash payments, or the relevant bank account for other payments.
11. Post the journal.

## <a name="to-apply-a-payment-to-a-single-customer-ledger-entry"></a>To apply a payment to a single customer ledger entry
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Cash Receipt Journal** and choose the related link.
2. On the first journal line, enter the relevant information about the entry to be applied.
3. In the **Document Type** field, enter **Payment**.
4. In the **Account Type** field, enter **Customer**.
5. In the **Bal. Account Type** field, enter **Bank Account**.
6. In the **Applies-to Doc. No.** field, choose the field to open the **Apply Customer Entries** window.
7. In the **Apply Customer Entries** window, select the entry to apply the payment to.
8. In the **Amount to Apply** field, enter the amount you want to apply to the entry. If you do not enter an amount, the maximum amount is applied.

    At the bottom of the **Apply Customer Entries** window, you can see the specific amount in the **Applied Amount** field and also whether the application balances.
9. Choose the **OK** button. The **Cash Receipt Journal** window now shows the entry you have selected entered in the **Applies-to Doc. Type** and **Applies-to Doc. No.** fields.
10. Post the cash receipt journal.

## <a name="to-apply-a-payment-to-multiple-customer-ledger-entries"></a>To apply a payment to multiple customer ledger entries
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Cash Receipt Journal**, and choose the related link.
2. On the first journal line, enter the relevant information about the entry to be applied.
3. In the **Document Type** field, enter **Payment**.
4. In the **Account Type** field, enter **Customer**.
5. In the **Bal. Account Type** field, enter **Bank Account**.
6. In the **Amount** field, enter the full payment as a negative amount.
7. To apply the payment to multiple customer ledger entries when posting, choose the **Apply Entries** action.
8. Select the lines with the entries that you want the applying entry to be applied to, and then choose the **Set Applies-to ID** action.
9. On each line, in the **Amount to Apply** field, enter the amount you want to apply to the individual entry. If you do not enter an amount, the maximum amount is applied.

    At the bottom of the **Apply Customer Entries** window, you can see the specific amount in the **Applied Amount** field and also whether the application balances.
10. Choose the **OK** button.
11. Post the cash receipt journal.

## <a name="to-apply-a-credit-memo-to-a-single-customer-ledger-entry"></a>To apply a credit memo to a single customer ledger entry
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Credit Memos**, and choose the related link.
2. Open the relevant sales credit memo.
3. To apply the credit memo to a single customer ledger entry when posting, in the **Applies-to Doc. No.** field, select the entry to which you want to apply the payment.
4. On the line in the **Amount to Apply** field, enter the amount you want to apply to the entry.

    If you do not enter an amount, the program automatically applies the maximum amount. At the bottom of the **Apply Customer Entries** window, you can see the specific amount in the **Applied Amount** field and also whether the application balances.
5. Choose the **OK** button. The **Sales Credit Memo** window now shows the entry you have selected entered in the **Applies-to Doc. Type** and **Applies-to Doc. No.** fields. And the amount of the credit memo to be posted, adjusted for any possible payment discounts.
6. Post the credit memo.

## <a name="to-apply-a-credit-memo-to-multiple-customer-ledger-entries"></a>To apply a credit memo to multiple customer ledger entries
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Sales Credit Memos**, and choose the related link.
2. Open the relevant sales credit memo.
3. To apply the credit memo to multiple customer ledger entries when posting, choose the **Apply Entries** action.
4. Select the lines with the entries that you want the applying entry to be applied to, and then choose the **Set Applies-to ID** action.
5. On each line, in the **Amount to Apply** field, enter the amount you want to apply to the individual entry. If you do not enter an amount, the maximum amount is applied.

  At the bottom of the **Apply Customer Entries** window, you can see the specific amount in the **Applied Amount** field and also whether the application balances.
6. Choose the **OK** button. The **Sales Credit Memo** window now shows the amount of the credit memo to be posted, adjusted for any possible payment discounts.
7. Post the credit memo.

## <a name="to-apply-posted-customer-ledger-entries"></a>To apply posted customer ledger entries
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and choose the related link.
2. Open the customer card for the customer with entries that you want to apply.
3. Choose the **Ledger Entries** action, and then select the line with the entry that will be the applying entry.
4. Choose the **Apply Entries** action. The **Apply Customer Entries** window opens showing the open entries for the customer.
5. Select the lines with the entries that you want the applying entry to be applied to, and then choose the **Set Applies-to ID.** action.
6. For each line in the **Amount to Apply** field, enter the amount you want to apply to the individual entry. If you do not enter an amount, the maximum amount is applied.

    At the bottom of the **Apply Customer Entries** window, you can see the specific amount in the **Applied Amount** field.
7. Choose the **Post Application** action. The **Post Application** window appears with the document number of the applying entry and the posting date of the entry with the most recent posting date.  
8. Choose the **OK** button to post the application.

    If the posted application has resulted in closed customer ledger entries, the **Open** field is cleared for these ledger entries.
9. To see the ledger entries, in the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and choose the related link. Browse to the card for the relevant customer to see the ledger entries.

On the ledger entry list, on the line that contains the ledger entry that was fully applied to, you can see that the **Open** check box is not selected.  

**Note**: After you have selected an entry from the **Apply Customer Entries** window, or several entries by setting the **Applies-to ID**, the **Applied Amount** field on the journal line will contain the sum of the remaining amounts for the posted entries you have selected, unless the field contains something already. If you select **Apply to Oldest** in the **Application Method** field on the customer card, the application occurs automatically.

## <a name="to-apply-customer-ledger-entries-in-different-currencies-to-one-another"></a>To apply customer ledger entries in different currencies to one another
If you sell to a customer in one currency and receive payment in another currency, you can still apply the invoice to the payment.

If you apply an entry (Entry 1) in one currency to an entry (Entry 2) in a different currency, the posting date on Entry 1 is used to find the relevant exchange rate to convert amounts on Entry 2. The relevant exchange rate is found in the **Currency Exchange Rates** window.

Applying customer ledger entries in different currencies must be enabled. For more information, see [How to: Enable Application of Ledger Entries in Different Currencies](finance-setup-how-enable-application-ledger-entries-different-currencies.md).

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Cash Receipts Journal**, and choose the related link.
2. Open the journal you want, and fill the first empty journal line using a currency code.
3. Choose the **Apply Entries** action.
4. Select the line with the entry you want to apply to the entry in the cash receipt journal, choose the **Set Applies-to ID** action, and then select the entry you want to apply to.
5. Choose the **OK** button to return to the cash receipt journal.
6. Post the sales journal.

**Important**: When you apply entries in different currencies to one another, the entries are converted to GBP. Even though the exchange rates for the two relevant currencies are fixed, for example between GBP and EUR, there may be a small residual amount when these foreign-currency amounts are converted to GBP. These small residual amounts are posted as gains and losses to the account specified in the **Realised Gains Account** or **Realised Losses Account** field in the **Currencies** window. The **Amount (GBP)** field is also adjusted on the relevant vendor ledger entries.

## <a name="to-unapply-an-application-of-customer-entries"></a>To unapply an application of customer entries
When you unapply an erroneous application, correcting entries that are identical to the original entry but with opposite sign in the amount field are created and posted for all entries, including all general ledger posting derived from the application, such as payment discount and currency gains/losses. The entries that were closed by the application are reopened.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Customers**, and then choose the related link.
2. Open the relevant customer card.
3. Choose the **Ledger Entries** action.
4. Select the relevant ledger entry, and then choose the **Unapply Entries** action.
5. Alternatively, choose the **Detailed Ledger Entry** action.
6. Select the application entry, and then choose the **Unapply Entries** action.
7. Fill in the fields in the header, and then choose the **Unapply** action.

**Important**: If an entry has been applied by more than one application entry, you must unapply the latest application entry first.

## <a name="see-also"></a>See Also
[Manage Receivables](receivables-manage-receivables.md)  
[Manage Sales](sales-manage-sales.md)

