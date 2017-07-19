---
title: Entering Criteria in Filters
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
ms.openlocfilehash: 8eab393a0a77f9f1595ca1247c7549e68b491cb2
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="entering-criteria-in-filters"></a>Entering Criteria in Filters
When you want to search for data, such as customer names, addresses, or product groups, you enter criteria. In search criteria you can use all the numbers and letters that you normally use in the specific field. In addition, you can use special symbols to further filter the results.

## <a name="searching-using-the-quick-filter"></a>Searching using the Quick Filter
You can add filters to all pages by using the Quick Filter. The Quick Filter is enabled by choosing the magnifier icon in the top right corner of a page. This filtering type is used for a fast entry of criteria.

**Important**: The Quick Filter provides an easy access to filter data by entering plain text, but does also provide a lot of search criteria options. Depending on whether you enter plain text or text including symbols, the Quick Filter behaves differently.  
- If you enter plain text in the search criteria, the search criteria is interpreted as a case insensitive search that contains certain text.  
- If you enter text including symbols in the search criteria, the search criteria is interpreted exactly as you entered it, and the search is case sensitive.

### <a name="quick-filter-criteria"></a>Quick filter criteria
<!-- html syntax because symbols conflict with MarkDown syntax -->
<TABLE>
  <TR>
    <TH>Search Criteria</TH>
    <TH>Interpreted as...</TH>
    <TH>Returns...</TH>
  </TR>
  <TR>
    <TD>>man</TD>
    <TD>@*man*</TD>
    <TD>All records that contain the text man and case insensitive.</TD>
  </TR>
  <TR>
    <TD>>se</TD>
    <TD>@*se*</TD>
    <TD>All records that contain the text se and case insensitive.</TD>
  </TR>
  <TR>
    <TD>>Man*</TD>
    <TD>Starts with Man and case sensitive.</TD>
    <TD>All records that start with the text Man.</TD>
  </TR>
  <TR>
    <TD>'man'</TD>
    <TD>An exact text and case sensitive.</TD>
    <TD>All records that match man exactly.</TD>
  </TR>
  <TR>
    <TD>@*man</TD>
    <TD>Ends with and case insensitive.</TD>
    <TD>All records that end with man.</TD>
  </TR>
  <TR>
    <TD>@man*</TD>
    <TD>Starts with and case insensitive.</TD>
    <TD>All records that start with man.</TD>
  </TR>
</TABLE>

**Note**: You cannot use a wildcard when filtering on enumeration fields, such as the **Status** field on sales orders. To enter a filter for this type of field, you can enter the numeric value as a filtering parameter. For example, in the **Status** field on a sales order that has the values **Open**, **Released**, **Pending Approval**, and **Pending Prepayment**, use the values **0**, **1**, **2**, and **3** to filter for these options.  

## <a name="see-also"></a>See Also
[Work with Dynamics NAV](ui-work-product.md)

