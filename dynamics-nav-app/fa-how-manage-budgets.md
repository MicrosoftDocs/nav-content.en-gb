---
title: 'How to: Manage Budgets for Fixed Assets'
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
ms.openlocfilehash: 47b5e0abcae4fab92da5dd9c1bda350a37ec0358
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-manage-budgets-for-fixed-assets"></a>How to: Manage Budgets for Fixed Assets
You can set up budgeted fixed assets. This makes it possible to include any anticipated acquisitions and sales in reports.  

 To prepare your budgeted income statement, budgeted balance sheet and cash budget, you need information about future investments, disposals and depreciation of fixed assets. You can get this information from the **Fixed Asset - Projected Value** report. Before you print this report, you must prepare the budget.  

## <a name="to-budget-the-acquisition-cost-of-a-fixed-asset"></a>To budget the acquisition cost of a fixed asset
To prepare a budget, you have to set up fixed asset cards for fixed assets that you intend to buy in the future. The budget fixed assets are set up as ordinary fixed assets, but it must be set up to not post to the general ledger.

When you post the acquisition cost, you enter the number of the budgeted fixed asset in the **Budgeted FA No.** field. This will post an acquisition cost with an opposite sign for the budgeted asset. This means that the total acquisition cost on the budgeted asset is the difference between the budgeted and the actual acquisition cost.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.
2. Choose the **New** action to create a new fixed asset card for the budgeted fixed asset.
3. Select the **Budgeted Asset** check box to prevent posting to the general ledger.
4. Fill in the remaining fields, assign a depreciation book, and then post the first acquisition cost with the budgeted fixed asset entered in the **Budgeted FA No.** field on the journal line. For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).

## <a name="to-budget-the-disposal-of-a-fixed-asset"></a>To budget the disposal of a fixed asset
If you plan to sell assets within the budget period, you can enter information about sales price and sales date.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.
2. Select the fixed asset to be disposed of, and then choose the **Depreciation Books** action.
3. In the **FA Depreciation Books** window, fill in the **Projected Disposal Date** and **Projected Proceeds on Disposal** fields. Choose a field to read a short description of the field or link to more information.

## <a name="to-view-projected-disposal-values"></a>To view projected disposal values
To see the projected disposal values and have the gain and loss calculated, you can use the **FA Projected Value** report.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **FA Projected Value**, and then choose the related link.
2. Fill in the fields as necessary.
3. Choose the **Print** or **Preview** button.

## <a name="to-budget-depreciation"></a>To budget depreciation
You can use the **Fixed Asset - Projected Value** report to calculate future depreciation. The report shows the book value and accumulated depreciation at the start of the selected period, changes during the period, and the book value and accumulated depreciation at the end of the selected period.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **FA Projected Value**, and then choose the related link.
2. Fill in the fields as necessary.
3. To see total values for all assets, clear the **Print per Fixed Asset** check box.
4. Leave the **Fixed Asset** FastTab blank to have all assets included. In the **Budgeted Asset** field, enter **No** to exclude budgeted assets or **Yes** to see budgeted assets only.
5. Choose the **Print** or **Preview** button.

## <a name="see-also"></a>See Also
[Manage Fixed Assets](fa-manage.md)  
[Set Up Fixed Assets](fa-setup.md)  
[Finance](finance-setup.md)  
[Welcome to Dynamics NAV](across-get-started.md)

