---
title: 'How to: Maintain Fixed Assets'
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
ms.openlocfilehash: 58077a38433a73b981a6f3d05ce7ed106acf32f4
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-maintain-fixed-assets"></a>How to: Maintain Fixed Assets
Maintenance expenses are routine periodic costs undertaken to preserve the value of fixed assets. Unlike capital improvements, they do not increase values.

You can record and maintain an up-to-date file on maintenance and service of your fixed assets to have complete maintenance records on a fixed asset easily accessible. Each time a fixed asset is sent to service, you record all relevant information such as date of service, vendor number and service agent's phone number. Maintenance registration is recorded for each fixed asset from the relevant fixed asset card.

Indexation is used to adjust values for general price-level changes. The **Index Fixed Assets** batch job can be used to recalculate the maintenance costs.

## <a name="to-record-maintenance-work-on-a-fixed-asset"></a>To record maintenance work on a fixed asset  
Every time maintenance has been performed, such as a service visit, you can record it for the relevant fixed asset in the **Maintenance Registrations** window.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.  
2. Select the fixed asset that you want to record maintenance for, and then choose the **Maintenance Registration** action.
3. In the **Maintenance Registration** window, fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.  

## <a name="to-post-maintenance-costs-from-a-fixed-asset-gl-journal"></a>To post maintenance costs from a fixed asset G/L journal
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Depreciation Book List**, and then choose the related link.  
2. Select the depreciation book that is assigned to the fixed asset, and then choose the **Edit** action.
3. In the **Depreciation Book Card** window, make sure the **Maintenance** check box is not selected. This ensures that maintenance costs are not posted to the general ledger.
4. In the top right corner, choose the **Search for Page or Report** icon, enter **FA G/L Journals**, and then choose the related link.  
5. Create an initial journal line and fill in the fields as necessary.
6. In the **FA Posting Type** field, select **Maintenance**.
7. Choose the **Insert FA Bal. Account** action. A second journal line is created for the balancing account that is set up for maintenance posting.

    **Note**: Step 7 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Maintenance Account** field contains the general ledger debit account and the **Maintenance Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation. For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).
8. Choose the **Post** action.

## <a name="to-follow-up-on-fixed-assets-service-visits"></a>To follow up on fixed assets service visits
You can print the **Maintenance - Next Service** report to see which assets you have scheduled a service visit for. You can also use this report when you are updating the **Next Service Date** field on fixed asset cards.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Maintenance Next Service**, and then choose the related link.  
2. Fill in the **Starting Date** and **Ending Date** fields.  
3. Choose the **Print** or **Preview** button.

## <a name="to-monitor-maintenance-costs"></a>To monitor maintenance costs  
You can view the maintenance costs when you look at the statistics of a fixed asset.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.
2. Select the fixed asset you want to view maintenance costs for, and then choose the **Depreciation Books** action.
3. In the **FA Depreciation Books** window, select the relevant fixed asset depreciation book, and then choose the **Statistics** action.
4. In the **Fixed Asset Statistics** window, choose the **Maintenance** field.

The **Maintenance Ledger Entries** window opens showing the entries that make up the amount in the **Maintenance** field.

## <a name="to-view-or-print-maintenance-costs-for-multiple-fixed-assets"></a>To view or print maintenance costs for multiple fixed assets  
In the **Maintenance - Analysis** report, you can select to see maintenance based on one, two, or three maintenance codes for a specified date or period. You can see the total of all selected assets or a total for each asset.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Maintenance Analysis**, and then choose the related link.
2. Fill in the fields as necessary.
3. Choose the **Print** or **Preview** button.

## <a name="to-view-maintenance-ledger-entries"></a>To view maintenance ledger entries
You can also study maintenance costs by viewing the maintenance ledger entries.  
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Fixed Assets**, and then choose the related link.
2. Select the fixed asset that you want to view ledger entries for, and then choose the **Depreciation Books** action.
3. In the **FA Depreciation Books** window, select the relevant fixed asset depreciation book, and then choose the **Maintenance Ledger Entries** action.

## <a name="to-view-or-print-maintenance-ledger-entries-for-multiple-fixed-assets"></a>To view or print maintenance ledger entries for multiple fixed assets  
In the **Maintenance - Details** report, you can view or print maintenance ledger entries for one or many fixed assets.  

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Maintenance Details**, and then choose the related link.
2. Fill in the fields as necessary.
3. Choose the **Print** or **Preview** button.

## <a name="see-also"></a>See Also
[Manage Fixed Assets](fa-manage.md)  
[Set Up Fixed Assets](fa-setup.md)  
[Finance](finance-setup.md)  
[Welcome to Dynamics NAV](across-get-started.md)

