---
title: 'How to: Transfer Bank Funds'
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: f34bef80c64cbad0a0b20d4d021cefbdc5a1cb64
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-transfer-bank-funds"></a>How to: Transfer Bank Funds
You may sometimes need to transfer an amount from one bank account to another. To do this, you must post the a transaction in the general journal. The task varies depending on whether the bank accounts use the same currency or different currencies.

## <a name="to-post-a-transfer-between-bank-accounts-with-the-same-currency-code"></a>To post a transfer between bank accounts with the same currency code
1. In the top right corner, choose the **Search for Page or Report** icon, enter **General Journal**, and then choose the related link.
2. On a journal line, fill in the **Posting Date** and **Document No.** fields.
3. In the **Account Type** field, select **Bank Account**.
4. In the **Account No.** field, select the bank from which you want to transfer the funds.
5. In the **Amount** field, enter the amount to be transferred.
6. In the **Bal. Account Type** field, select **Bank Account**.
7. In the **Bal. Account No.** field, select the bank account to which you want to transfer the funds.
8. Post the journal.

## <a name="to-post-a-transfer-between-bank-accounts-with-different-currency-codes"></a>To post a transfer between bank accounts with different currency codes
To transfer funds between bank accounts that use different currencies, you must post two general journal lines.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **General Journal**, and then choose the related link.
2. Create two journal lines, and fill in the **Posting Date** and **Document No.** fields.
3. On the first journal line, in the **Type** field, select **Bank Account**.
4. In the **Account No.** field, select the bank account from which you want to transfer the funds.
5. In the **Amount** field, enter the amount in the currency of the bank account. Enter credit amounts with a minus sign. Enter debit amounts without a minus sign.
6. In the **Bal. Account Type** field, select **Bank Account**.
7. In the **Bal. Account No.** field, select the bank account to which you want to transfer the funds.
8. On the second journal line, in the **Type** field, select **Bank Account**.
9. In the **Account No.** field, select the bank account to which you want to transfer the funds.
10. In the **Amount** field, enter the amount in the currency of the bank account. Enter credit amounts with a minus sign. Enter debit amounts without a minus sign.
11. In the **Bal. Account Type** field, select **Bank Account**.  
12. In the **Bal. Account No.** field, select the bank account from which you want to transfer the funds.

    **Note**: If the exchange rates used in the journal are different than the exchange rates in the **Currency Exchange Rates** window, enter a third line for the exchange rate gain or loss. Enter **G/L Account** in the **Account Type** field. Enter the G/L account number for exchange rate gain or loss in the **Account No.** field. Enter the exchange rate gain or loss in the **Amount** field with or without a minus sign for credits and debits respectively.
13. Post the journal.

## <a name="see-also"></a>See Also  
[Manage Bank Accounts](bank-manage-bank-accounts.md)  
[Set Up Banking](bank-setup-banking.md)  
[Work with General Journals](ui-work-general-journals.md)

