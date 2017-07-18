---
title: 'How to: Create a Custom Report Layout'
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 90136439e09deb00a9aed9344fc5f89812caef3a
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-create-a-custom-report-layout"></a>How to: Create a Custom Report Layout
By default, a report will have a built-in report layout, which can be either an RDLC report layout or Word report layout, or both. You cannot modify built-in layouts. However, you can create your own custom layouts that enable you to change the appearance of report when it is viewed, printed or saved. You can create multiple custom report layouts for the same report, and then switch the layout that is used by a report as needed.

To create a custom layout, you can either make a copy of an existing custom layout or add a new custom layout, which in most cases is based on a built-in layout. When you add a new custom layout, you can choose to add an RDLC report layout type, Word report layout type, or both. The new custom layout will automatically be based on the built-in layout for the report if one is available. If there is no built-in layout for the type, then a new blank layout is a created, which you will have to modify and design from scratch. For more information about RDLC and Word report layouts, built-in and custom layouts, and more, see [Manage Report Layouts](ui-manage-report-layouts.md).  

## <a name="to-create-a-custom-layout"></a>To create a custom layout
1. In the top right corner, choose the **Search for Page or Report** icon, enter **Report Layout Selection**, and then choose the related link.  
The** Report Layout Selection** window lists all the reports that are available in the company that is specified in the Company field at the top of the window.
2. Set the **Company** field to the company in which you want to create the report layout.
3. Select the row for the report that you want to create the layout for, and then choose **Custom Layouts**.  
The **Custom Report Layouts** window appears and lists all the custom layouts that are available for the selected report.
4. If you want to create a copy of an existing custom layout, select the existing custom layout in the list, and then choose **Copy**.  
The copy of the custom layout appears in the **Custom Report Layouts** window and has the words Copy of in the Description field.
5. If you want to add a new custom layout that is based on a built-in layout, do the following:  
    1. Choose **New**. The **Insert Built-in Layout for a Report** window appears. The **ID** and **Name** fields are automatically filled in.
    2. To add a custom Word report layout type, then select the **Insert Word Layout** check box.
    3. To add a custom RDLC report layout type, then select the **Insert RDLC Layout** check box.
    4. Choose the **OK** button.  
    The new custom layouts appear in the **Custom Report Layouts** window. If a new layout is based on a built-in layout, then it has the words **Copy of a Built-in Layout** in the **Description** field. If there was no built-in layout for the report, then the new layout has the words **New Layout** in the **Description** field, which indicates that custom layout is blank.
6. By default, the **Company Name** field is blank, which means that the custom layout will be available for the report in all companies. To make the custom layout available in a specific company only, choose **Edit**, and then set the **Company Name** field to the company that you want.

## <a name="see-also"></a>See Also
[Manage Report Layouts](ui-manage-report-layouts.md)  
[How to: Change Which Layout is Currently Used on a Report](ui-how-change-layout-currently-used-report.md)

