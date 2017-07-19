---
title: Create Number Series
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 22b3bcf71c99e106527d6bfa35478045d29b9629
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="create-number-series"></a>Create Number Series

For each company that you set up, you need to assign unique identification codes to things such as general ledger accounts, customer and vendor accounts, invoices, and documents. Numbering is important not only for identification. A well-designed numbering system also makes the company more manageable and easy to analyze, and can reduce the number of errors that occur in data entry.

You can set up a complete numbering system with an unlimited number of number series. You can use number series for all types of documents and journals, as well as for master data such as customers, items, and jobs.

You can combine the use of number series with manual numbering.

You create a numbering system by setting up one or more codes for each type of master data or document. For example, you can set up one code for numbering customers, another code for numbering sales invoices, and another code for numbering documents in general journals.

After you have set up a code, you set must set up at least one number series line. The number series line contains information such as the first and last number in the series and the starting date. You can set up more than one number series line per number series code, with a different starting date for each line. The series will be used consecutively, starting each series on the respective starting date.

If you want to use more than one number series code for one type of master data - for example, if you want to use different number series for different categories of items - you can use number series relationships.

In addition to the numbers that you assign manually or by use of the numbering system, all transactions (ledger entries) are automatically assigned consecutive numbers. These numbers can be seen in the **Entry No.** field in all the ledger entry windows. You cannot modify or delete these numbers.

## <a name="to-create-relationships-between-number-series"></a>To create relationships between number series
If you have set up more than one number series code for the same kind of basic information or transactions, you can create relationships between the codes. This feature can assist you in deciding among the codes when you use a number.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **No. Series**, and then choose the related link.
2. Select the line with the number series you want to create relationships for and then choose **Relationships**.
3. In the **Series Code** field, enter the code for the number series that you want to relate to the series you selected in step 2.
4. Add a line for each code that you want to relate to the selected number series.
5. Close the window.

Now when you set up something that requires a number, you can use the relationships you created to select among the related number series.

## <a name="see-also"></a>See Also
[Work with Dynamics NAV](ui-work-product.md)

