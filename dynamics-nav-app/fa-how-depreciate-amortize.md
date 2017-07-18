---
title: 'How to: Depreciate or Amortise Fixed Assets'
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
ms.openlocfilehash: af71f30681d436ed5da1cd6cb3c2e13f86558631
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-depreciate-or-amortize-fixed-assets"></a>How to: Depreciate or Amortise Fixed Assets
Depreciation is used to allocate the cost of fixed assets, such as machinery and equipment, over their depreciable life. For each fixed asset, you must define how it will be depreciated.  

 There are two ways to post depreciation:
- Automatically, by running the **Calculate Depreciation** batch job.
- Manually, by using the fixed asset G/L journal.  

Dynamics NAV can calculate daily depreciation, which allows you to calculate depreciation for any period. You can therefore analyse current operating results on, for example, a monthly, quarterly, or annual basis. The calculation uses a standard year of 360 days and a standard month of 30 days. For more information, see [Depreciation Methods](fa-depreciation-methods.md).

If a fixed asset is used by several departments, periodic depreciation can be automatically allocated to these departments according to a user-defined allocation table.  

You can cancel incorrect depreciation entries with the **Cancel FA Ledger Entries** batch job. After this, you can post the correct amount of depreciation by running the **Calculate Depreciation** batch job again. When you correct errors, they are posted as fixed asset error ledger entries.  

Indexation is used to adjust values for general price-level changes. The **Index Fixed Assets** batch job can be used to recalculate the depreciation amounts.  

## <a name="to-calculate-a-depreciation-automatically"></a>To calculate a depreciation automatically
Once a month, or whenever you choose, you can run the **Calculate Depreciation** batch job. Fixed assets that have been sold, assets that are blocked or inactive, and fixed assets that use the manual depreciation method are ignored.    

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Calculate Depreciation**, and then choose the related link.  
2. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.
3. Choose the **OK** button.  

    The batch job calculates the depreciation and creates lines in the fixed asset G/L journal.  
4. In the top right corner, choose the **Search for Page or Report** icon, enter **FA G/L Journals**, and then choose the related link.

    In the **Fixed Asset G/L Journal** window, in the **No. of Depreciation Days** field you can see how many days of depreciation have been calculated.  
5. Choose the **Post** action.

## <a name="to-post-a-depreciation-manually-from-the-fixed-asset-gl-journal"></a>To post a depreciation manually from the fixed asset G/L journal
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Asset G/L Journal**, and then choose the related link.  
2. Create an initial journal line and fill in the fields as necessary.
3. In the **FA Posting Type** field, select **Depreciation**.
4. Choose the **Insert FA Bal. Account** action. A second journal line is created for the balancing account that is set up for depreciation posting. For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).
5. On the **Home** tab, choose **Post** to post the journal.

If you have set up fixed asset allocation keys to allocate amounts to different departments or projects, then the amounts will be allocated during posting. For more information, see [How to: Set Up General Fixed Assets Information](fa-how-setup-general.md).

## <a name="to-calculate-allocations-in-the-fixed-asset-gl-journal"></a>To calculate allocations in the fixed asset G/L journal
If a fixed asset is used by several departments, periodic depreciation can be automatically allocated to these departments according to a user-defined allocation table.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Asset G/L Journal**, and then choose the related link.   
Create an initial line and fill in the fields as necessary.
3. In the **FA Posting Type** field, select **Allocation**.
4. Choose the **Insert FA Bal. Account** action. A second journal line is created for the balancing account that is set up for allocation posting.
5. On the **Home** tab, choose **Post** to post the journal.

## <a name="use-duplication-lists-to-prepare-to-post-to-multiple-depreciation-books"></a>Use duplication lists to prepare to post to multiple depreciation books  
When you fill in journal lines to be posted to a depreciation book, you can duplicate the lines in a separate journal, after which they can be posted to a different depreciation book. For more information, see the "To post entries to different depreciation books" section.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Depreciation Books**, and then choose the related link.  
2. Open the relevant depreciation book, and then select the **Part of Duplication List** check box.  

**Important**: If you have selected the **Use Duplication List** field, do not use number series on the journal. The reason is that the number series for the fixed asset G/L journal does not the number series for the fixed asset journal.

## <a name="to-post-entries-to-different-depreciation-books"></a>To post entries to different depreciation books  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Asset G/L Journal**, and then choose the related link.
2. In the journal that you want to post depreciation with, select the **Use Duplication List** check box.
3. Fill in the remaining fields as necessary.
4. Choose the **Post** action.
5. In the top right corner, choose the **Search for Page or Report** icon, enter **FA Journals**, and then choose the related link.

    The **Fixed Asset Journal** window contains new lines for different depreciation books according to the duplication list.   

6. Review or edit the lines, and then choose the **Post** action.

**Note**: Another way to duplicate an entry in a separate book is to enter a depreciation book code in the **Duplicate in Depreciation Book** field when you fill in a journal line.

You can copy entries from one depreciation book to another with the **Copy Depreciation Book** batch job. The batch job creates journal lines in the journal batch that you have specified in the **FA Journal Setup** window for the depreciation book that you want to copy to. For more information, see the following procedure.

## <a name="to-copy-fixed-asset-ledger-entries-between-depreciation-books"></a>To copy fixed asset ledger entries between depreciation books  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Depreciation Books**, and then choose the related link.
2. Open the relevant depreciation book card, and then choose the **Copy Depreciation Book** action.  
3. In the **Copy Depreciation Book** window, fill in the fields as necessary.  
4. Choose the **OK** button.  

The copied lines are created in either the fixed asset G/L journal or the fixed asset journal, depending on whether the depreciation book that you are copying has integration to the general ledger.

## <a name="see-also"></a>See Also
[Manage Fixed Assets](fa-manage.md)  
[Set Up Fixed Assets](fa-setup.md)  
[Finance](finance-setup.md)  
[Welcome to Dynamics NAV](across-get-started.md)

