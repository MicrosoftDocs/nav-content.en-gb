---
title: 'How to: Set Up Resources'
author: SorenGP
ms.custom: na
ms.date: 12/14/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 72f5304e6a69a736c9df2cbb9ca64c5f3c5261a2
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-set-up-resources"></a>How to: Set Up Resources
To correctly manage resource activities, you must set up your resources and the related costs and prices. The job-related prices, discounts, and cost factor rules are set up on the job card. You can specify the costs and prices for individual resources, resource groups, or all available resources of the company.

When resources are used or sold in a job, the prices and costs associated with them are retrieved from the information that you set up.

You specify the default amount per hour when the resource is created. For example, if you use a specific machine on a job for five hours, the job would be calculated based on the amount per hour.

## <a name="to-set-up-a-resource"></a>To set up a resource
Create a card for each resource that you want to use in projects.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link.
2. Choose the **New** action.
3. Fill in the fields as necessary. Choose a field to read a short description of the field or link to more information.  

## <a name="to-set-up-a-resource-group"></a>To set up a resource group
You can combine several resources in one resource group. All capacities and budgets of resource groups are accumulated from the individual resources. It is also possible to enter capacities for resource groups either independently of the accumulated values or in addition to them.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resource groups**, and then choose the related link.
2. Choose the **New** action.
3. Fill in the fields as necessary.

## <a name="to-set-capacity-for-a-resource"></a>To set capacity for a resource 
To calculate how much time a resource can spend on jobs, their capacity must first be set up as available time per period on the work calendar. This setup is used when you fill in job planning lines that contain the resource. For more information, see [How to: Create Jobs](projects-how-create-jobs.md).

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link.
2. Open the relevant resource card, and then choose the **Resource Capacity** action.
3. In the **Resource Capacity** window, in the **View By** field, specify the length of the period, such as **Day**, that is shown on columns on the **Resource Capacity Matrix** FastTab.
4. For each resource on a line, specify for each period on the columns the number of hours that the resource is available.
5. Alternatively, to detail the resource's weekly capacity within a starting and ending date, choose the **Set Capacity** action.
6. In the **Resource Capacity Settings** window, fill in the fields as necessary.
7. Choose the **Update Capacity** action. The **Resource Capacity** window is updated with the entered capacity.
8. Close the window.

## <a name="to-set-up-alternate-resource-costs"></a>To set up alternate resource costs
In addition to the cost specified on the resource card, you can set up alternate costs for each resource. For example, if you pay an employee a higher hourly rate for overtime, you can set up a resource cost for the overtime rate. The alternate cost that you set up for the resource will override the cost on the resource card when you use the resource in the resource journal.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link.  
2. Select the resource for that you want to set up one or more alternate costs for, and then choose the **Costs** action.  
3. In the **Resource Costs** window, fill in the fields on a line as necessary.  
4. Repeat step 3 for each alternate resource cost that you want to set up.

**Note**. To set up resource costs that will apply to all resources and resource groups, open the **Resource Costs** window and fill in the fields.

## <a name="to-set-up-alternate-resource-prices"></a>To set up alternate resource prices  
In addition to price specified on the resource card, you can set up alternate prices for each resource. These alternate prices can be conditional. They can depend on whether the resource is used with a specific job or work type.

1. In the top right corner, choose the **Search for Page or Report** icon, enter **Resources**, and then choose the related link.
2. Select the resource for that you want to set up one or more alternate prices for, and then choose the **Prices** action.
3. In the **Resource Prices** window, fill in the fields on a line as necessary.
4. Repeat step 3 for each alternate resource price that you want to set up.

## <a name="see-also"></a>See Also
[Set Up Project Management](projects-setup-projects.md)  
[Manage Projects](projects-manage-projects.md)  
[Finance](finance-setup.md)  
[Manage Purchasing](purchasing-manage-purchasing.md)         
[Manage Sales](sales-manage-sales.md)      
[Work With Dynamics NAV](ui-work-product.md)  

