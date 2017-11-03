---
title: Managing Profiles and Role Centres
description: Learn how to manage users and Role Centres in Dynamics NAV.
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: profiles, roles, role centers, user roles
ms.date: 09/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: a16640e014e157d4dbcaabc53d0df2d3e063f8f9
ms.openlocfilehash: a657c409c9cd361a505f1fd61dbb5254b25c5144
ms.contentlocale: en-gb
ms.lasthandoff: 10/26/2017

---
# <a name="managing-profiles-and-role-centers"></a>Managing Profiles and Role Centres
Profiles are collections of [!INCLUDE[navnow_md](includes/navnow_md.md)] users who share the same Role Center. A Role Centre is a type of page on which you can place different parts. Each part is a container in which you can host other pages or pre-defined system parts, such as an Outlook part or parts for adding tasks, notifications, or notes.  

## <a name="about-profiles-and-role-centers"></a>About profiles and Role Centres
You use profiles to link users to pre-defined Role Centres. A Role Centre is a home page for all users of a profile, which has been configured to reflect the tasks and priorities of users of the profile. For example, the Order Processor Role Centre has been configured to reflect the tasks and priorities of an order processor. A Role Centre provides easy access to information users need to perform their daily work. For example, the Role Centre determines the Cues, or tile, that show when isers first sign in, and the links from the navigation page.

The profile that is used appears in the header of the Role Centre’s main content area. An administrator can customise this Role Centre to meet the needs of a specific role in a specific company. The Order Processor Role Centre can then be further personalised on a single computer to meet the needs of a person who is carrying out the job as an order processor. This person can personalise the Role Centre by saving queries, adding filters, and adding or removing fields.

Profiles and Role Centres align with the roles and responsibilities in your organisation. [!INCLUDE[navnow_md](includes/navnow_md.md)] provides a set of default profiles, which each correspond to and link to a Role Center. Administrators can modify existing profiles or create new ones.  

> [!NOTE]  
>  Profiles are not explicitly linked to the roles and permissions that constitute the security system, but profile users must have permissions that align with their roles in the security system. For more information, see [Security in the Role Tailored Environment](http://go.microsoft.com/fwlink?LinkId=147633) in the MSDN Library.

## <a name="to-create-a-profile"></a>To create a profile
1.  Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Profiles**, and then choose the related link.  

2.  Choose the **New** action to open the **New Profile Card** window.  

3.  In the **Profile ID** field, enter a name that describes the intended role of the user.  

4.  In the **Description** field, enter a description of the Profile ID, for example, **Order Processor**.  

5.  Set the **Role Centre ID** field to the Role Centre that you want to assign to the profile.  

6.  To make this Role Centre the default for the profile, select the **Default Role Centre** check box.  

7.  Choose the **OK** button. .  

The procedure for modifying an existing profile is the same, except you select an existing profile in the Profiles page instead of choosing the **New** action.  


##<a name="copying-a-profile"></a>Copying a profile
Copying a profile can save you time if you want to use similar settings on a profile and you only want to change a few settings.

1.  Open the profile that you want to copy, and then choose the **Copy Profile** action.

2.  In **New Profile ID** field, enter a name for the profile that you want to copy.

3.  Set the **New Profile Scope** field to one of the following:

    - **System** to make the new profile available to all tenant databases that use the application.
    - **Tenant** to make the new profile available to just the current tenant database.
4. Choose the **OK** buttom when done.

## <a name="ExportImportProfile"></a>Exporting and importing profiles

You can export and import profiles as XML files to and from the a [!INCLUDE[d365fin](includes/d365fin_md.md)] database. Exporting and importing a profile can save you time when configuring the user interface because you reuse an existing profile configuration instead of having to configure a profile from scratch. If you have a profile that is configured in a [!INCLUDE[d365fin](includes/d365fin_md.md)] database and you would like to reuse all or some of the same profile configurations in another database, you can export the profile to an XML file. Then, you can import the profile XML file into the other database.

-   To export a profile, open search for and open the **Export Profiles** page, select the profile from the list, and then choose the **Export** action. Save the XML file to a location on your computer or network.

-   To import a profile, open search for and open the **Import Profiles** page, select the profile XML file, and then choose the **OK** button.

    > [!NOTE]  
    >  You cannot import a profile that already exists in the database, even though the XML file is named differently or has different content. You must delete the existing profile before you can import the new profile.



## <a name="see-also"></a>See Also  
[How to: Manage Users and Permissions](ui-how-users-permissions.md)  
[Customising the User Interface](ui-customizing-overview.md)   
<!--[Security Overview](../Security%20Overview.md)-->

