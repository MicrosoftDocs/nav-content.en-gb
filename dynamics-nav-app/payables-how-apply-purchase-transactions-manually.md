---
title: 'How to: Apply Vendor Payments Manually'
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
ms.openlocfilehash: d3aaafc9ac3dcfd1fba3802b1158bde890e09110
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-apply-vendor-payments-manually"></a>How to: Apply Vendor Payments Manually

When you send a payment or receive a refund from a vendor, you must decide whether to apply the payment or refund to one or more open entries. You can specify the exact amount that you want to apply to the payment receipt or refund, and then only partially apply vendor ledger entries. You must apply all vendor ledger entries to obtain correct vendor statistics and reports of the account statements and finance-setup charges.

**Note**: Vendors may sometimes give a payment refund instead of a credit memo to offset against future invoices, especially when you return items that you have already paid for or when you have overpaid an invoice.

You can apply vendor ledger entries in three different ways:

- By entering information in dedicated windows, such as the **Payment Journal** window and the **Payment Reconciliation Journal** window.
- From purchase credit memo documents.
- From vendor ledger entries after purchase documents are posted but not applied.

**Note**: If the **Application Method** field on the vendor card contains **Apply to Oldest**, then payments will automatically be applied to the oldest open credit entry if you do not manually specify which entry to apply to. If the application method for a customer is **Manual**, then you must apply entries manually.

You can apply vendor payments manually to their related purchase documents when you post the payments in the **Payment Journal** window. For information about filling the payment journal, see [How to: Make Payments](payables-make-payments.md).

You can also apply vendor payments, and customer payments, after the payments appear as negative bank transactions at your bank. In the **Payment Reconciliation Journal** window, you can use functions for bank statement import, automatic application, and bank account reconciliation. For more information, see [Reconcile Payments Using Automatic Application](receivables-how-reconcile-payments-auto-application.md).

## <a name="to-apply-a-payment-to-a-single-or-multiple-vendor-ledger-entries"></a>To apply a payment to a single or multiple vendor ledger entries
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journal**, and then choose the related link.
2. In the **Payment Journal** window, on the first journal line, enter the relevant information about the payment entry.
3. To apply a single vendor ledger entry:
4. In the **Applies-to Doc. No.** field, choose the field to open the **Apply Vendor Entries** window.
5. In the **Apply Vendor Entries** window, select the entry to apply the payment to.
6. On the line in the **Amount to Apply** field, enter the amount to apply to the entry.
7. Or, to apply multiple vendor ledger entries:
8. Choose the **Apply Entries** action.
9. In the **Apply Vendor Entries** window, select the lines with the entries to apply the payment to.
10. Choose the **Set Applies-to ID** action.  
11. On each line in the **Amount to Apply** field, enter the amount to apply to the individual entry.

    If you do not enter an amount, then the maximum amount is automatically applied. At the bottom of the **Apply Vendor Entries** window, you can see the amount in the Applied Amount field, and you can see whether the application balances.
12. Choose the **OK** button.
13. Choose the **Post** action to post the payment journal.

## <a name="to-apply-a-credit-memo-to-a-single-or-multiple-vendor-ledger-entries"></a>To apply a credit memo to a single or multiple vendor ledger entries
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Purchase Credit Memo**, and then choose the related link.
2. Open the credit memo that you want to apply.
3. Enter the relevant information in the header.
4. To apply a single vendor ledger entry:
5. On the **Application** FastTab, in the **Applies-to Doc. No.** field, select the entry to apply the credit to.
6. On the line in the **Amount to Apply** field, enter the amount to apply to the entry.
7. Or, to apply multiple vendor ledger entries:
8. Choose the **Apply Entries** action.
9. Select the lines with the entries to apply the credit memo to.
10. Choose the **Set Applies-to ID** action.  
11. On each line in the **Amount to Apply** field, enter the amount to apply to the individual entry.

    If you do not enter an amount, then the maximum amount is automatically applied. At the bottom of the **Apply Vendor Entries** window, you can see the amount in the **Applied Amount** field, and you can see whether the application balances.
12. Choose the **OK** button.  
The **Purchase Credit Memo** window shows the entry that you have selected in the **Applies-to Doc. Type** field and the **Applies-to Doc. No.** field. The window also shows the amount of the credit memo to be posted, adjusted for any payment discounts.
13. Choose the **Post** button to post the purchase credit memo.

## <a name="to-apply-posted-vendor-ledger-entries"></a>To apply posted vendor ledger entries

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.
2. Open the relevant vendor with entries that have already been posted.
3. Choose the **Ledger Entries** action, and then choose the **Apply Entries** action.
4. In the **Apply Vendor Entries** window, you can see the open entries for the vendor.
5. Select the line with the entry that will be applied.
6. Choose the **Set Applies-to ID** action.
7. The **Applies-to ID** field displays three asterisks if you work in a single-user system or your user ID if you work in a multiuser system.  
8. For each line in the **Amount to Apply** field, enter the amount to apply to the individual entry.

    If you do not enter an amount, then the maximum amount is automatically applied. You can see the amount in the **Applied Amount** field at the bottom of the **Apply Vendor Entries** window.
9. Choose the **Post Application** action.  
The **Post Application** window opens with the document number of the applying entry and the posting date of the entry with the most recent posting date.
10. Choose the **OK** button to post the application.

## <a name="to-apply-vendor-ledger-entries-in-different-currencies-to-one-another"></a>To apply vendor ledger entries in different currencies to one another
If you buy from a vendor in one currency and make payment in another currency, you can still apply the invoice to the payment.

If you apply an entry (Entry 1) in one currency to an entry (Entry 2) in a different currency, the posting date on Entry 1 is used to find the relevant exchange rate to convert amounts on Entry 2. The relevant exchange rate is found in the **Currency Exchange Rates** window.

Applying vendor ledger entries in different currencies must be enabled. For more information, see [How to: Enable Application of Ledger Entries in Different Currencies](finance-setup-how-enable-application-ledger-entries-different-currencies.md)

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Payment Journal**, and choose the related link.
2. Open the journal you want, and fill in the first empty journal line using a currency code.
3. Choose the **Apply Entries** action.
4. Select the line with the entry you want to apply to the entry in the payment journal, choose the **Set Applies-to ID** action, and then select the entry you want to apply to.
5. Choose the **OK** button to return to the payment journal.
6. Post the payment journal.

**Important**: When you apply entries in different currencies to one another, the entries are converted to GBP. Even though the exchange rates for the two relevant currencies are fixed, for example between GBP and EUR, there may be a small residual amount when these foreign-currency amounts are converted to GBP. These small residual amounts are posted as gains and losses to the account specified in the **Realised Gains Account** or **Realised Losses Account** field in the **Currencies** window. The **Amount (GBP)** field is also adjusted on the relevant vendor ledger entries.

## <a name="to-unapply-an-application-of-vendor-entries"></a>To unapply an application of vendor entries
When you unapply an erroneous application, correcting entries that are identical to the original entry but with opposite sign in the amount field are created and posted for all entries, including all general ledger posting derived from the application, such as payment discount and currency gains/losses. The entries that were closed by the application are reopened.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Vendors**, and then choose the related link.
2. Open the relevant vendor card.
3. Choose the **Ledger Entries** action.
4. Select the relevant ledger entry, and then choose the **Unapply Entries** action.
5. Alternatively, choose the **Detailed Ledger Entry** action.
6. Select the application entry, and then choose the **Unapply Entries** action.
7. Fill in the fields in the header, and then choose the **Unapply** action.

**Important**: If an entry has been applied by more than one application entry, you must unapply the latest application entry first.

## <a name="see-also"></a>See Also
[Payables](payables-manage-payables.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)

