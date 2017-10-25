---
title: Configuring the User Interface (UI) for Users
description: "As an administrator, configure the company’s default user interfaces by customising page layouts for different user profiles in the company."
author: jswymer
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customize pages, configure user interface, customize UI
ms.date: 07/01/2017
ms.author: jswymer
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 7ba3d45a856eb38fe99fc5012b4e2f2d8609f9ce
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="configuring-the-user-interface-ui-for-users"></a>Configuring the User Interface (UI) for Users
As an administrator, you configure the company’s default user interfaces by customising page layouts for different user profiles in the company. To perform this work, you must be an administrator with the SUPER permission set. In addition, profiles must be set up and the appropriate users assigned to them. For more information, see [Managing Users, Profiles, and Role Centres](admin-users-profiles-roles.md).  
  
You configure the user interface for multiple users by customising pages for a particular profile that the users are assigned to. You do this by using the [!INCLUDE[nav_windows](includes/nav_windows_md.md)], and customising the same way that individual users personalise their own workspaces, that is, by using the **Customise** feature. The difference is that you open the [!INCLUDE[nav_windows](includes/nav_windows_md.md)] in the configuration mode. Typical customisations include which actions to include on the ribbon, how fields are placed on FastTabs or in FactBoxes, and which menu items to include in the navigation pane. 

> [!TIP]  
>  A quick way to implement UI configurations for a profile is if you already have a configured profile in another [!INCLUDE[d365fin](includes/d365fin_md.md)] database. You can then export that profile, and then import it into the current database. For more information, see [Exporting and Importing Profiles](admin-profiles.md#ExportImportProfile).  
  
## <a name="general-information"></a>General information
Consider the following information before you begin to configure the UI:
-   Before you begin to configure the UI, the application can be configured to show and hide UI elements (such as fields, FastTabs, and FactBoxes) based on licence or user permissions. For more information about how this is done, see [Removing Elements from the User Interface According to Permissions](https://msdn.microsoft.com/en-us/dynamics-nav/removing-elements-from-the-user-interface-according-to-permissions).

    To see the effect of the UI Elements Removal option, you can log on as a test user with the permission set of the profile you are configuring. The reason is that you as the administrator have the SUPER permission set, and you can therefore not see and test the resulting user interface during your own logon.    
-   When you make UI configuration changes for a page that a user has personalised, the user’s UI personalisation is preserved, and is not overwritten by the new page configuration. Likewise, when you cancel your UI configuration of a page that a user has since personalised, the user’s UI personalisation is not cancelled.
-   The only situation where UI configuration does overwrite UI personalisation is when a UI element is removed by configuration. For example, if the administrator removes a field that the user has renamed or moved, then the field is still removed from the user’s user interface.
-   You can record UI configurations of the same page based on different access points to the page. For example, the **Sales Orders** window can be customised to look different when opened from the **Customer Card** window than when opened from the **Sales Order Processor** Role Centre. The point from which you access the page to be customised is recorded in that specific page customisation. Accordingly, there may be multiple page customization records in the database, as you can be seen in the **Delete Profile Configuration** window.  
-   Unlike when users change the size of windows or the width of columns on their own computer, any such basic view changes that you make during your configuration of the UI for a profile are not saved to the profile and will not be available for users assigned to the profile. Basic view changes are computer-specific.   

## <a name="configure-a-profile-with-the-includenavwindowsincludesnavwindowsmdmd-in-configuration-mode"></a>Configure a profile with the [!INCLUDE[nav_windows](includes/nav_windows_md.md)] in configuration mode
1.  Open a command prompt, and type the following command to change to the installation folder of the [!INCLUDE[nav_windows](includes/nav_windows_md.md)]. For example:  
  
    ```  
    cd C:\Program Files\(x86)\Microsoft Dynamics NAV\110\RoleTailored Client  
    ```  
  
2.  Type the following command to start the [!INCLUDE[nav_windows](includes/nav_windows_md.md)] in the configuration mode for a specific profile:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"profileid"  
    ```  
  
     Replace **profileid** with the name of the profile that you want to configure.  
  
     For example, to configure the Accounting Manager profile, use this command:  
  
    ```  
    Microsoft.Dynamics.Nav.Client.exe -configure -profile:"Accounting Manager"  
    ``` 

3. You are now ready to start configuring the UI, which you do the same way as individual users personalise their own workspaces. For more information, see [Personalising Your Workspace in the [!INCLUDE[nav_windows](includes/nav_windows_md.md)]](ui-personalization-windows-client.md). 

## <a name="cancel-ui-configuration"></a>Cancel UI Configuration
You can cancel UI customisations that you have made as configuration for a profile in three ways:  
  
-   Cancel all UI customisation that you have made for a profile by using the **Clear Configured Pages** button in the **Profile Card** window.  
  
-   Cancel UI customization that you have made for specific pages for a profile by deleting rows in the **Delete Profile Configuration** window.  
  
-   Cancel UI customisation that you have made for a specific UI area for a specific page for a profile by using the **Restore Defaults** button in the **Customise** window.  
  
### <a name="general-information"></a>General information  
-   Users can make UI customisations under their own user logon to personalise their user interface. When you cancel your UI configuration of a page that a user has since personalised, the user’s UI personalisation is not cancelled. Likewise, when you make new UI configuration for a page that a user has personalised, the user’s UI personalisation is preserved, and is not overwritten by the new page configuration.  

    The only situation where UI configuration does overwrite UI personalisation is when a UI element is removed by configuration. For example, if the administrator removes a field that the user has renamed or moved, then the field is still removed from the user’s UI.  
  
-   In the **Delete User Personalization** window and with the **Restore Defaults** button in the **Customize** window, users can cancel UI customization that they have made to pages under their own user logon. When they do so, the layout of those pages is reset to any UI customisation that the administrator has configured for the profile. If the profile has not been configured, then the layout of the user’s pages is reset to the default profile configuration. For more information about how users cancel personalisation, see [Cancelling Personalisation](ui-personalization-windows-client.md#CancelPersonalization).
  
### <a name="to-cancel-all-ui-customization-that-you-have-made-for-a-profile"></a>To cancel all UI customisation that you have made for a profile  
  
1.  In the **Search** box,, enter **Profiles**, and then choose the related link.  
  
2.  Select the profile for which you want to cancel all UI customisations, and then, on the **Home** tab, in the **Manage** group, choose **Edit**.  
  
3.  In the **Profile Card** window, on the **Actions** tab, in the **Functions** group, choose **Clear Configured Pages**.  
  
> [!NOTE]  
>  All UI customisations for the profile, both those installed with the application and those made by the administrator, are cancelled. No page layouts specific to the profile remain in the database.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-specific-page-for-a-profile"></a>To cancel UI customisation that you have made for specific page for a profile  
  
1.  In the **Search** box,, enter **Delete Profile Configuration**, and then choose the related link.  
  
2.  Select the profile/page set for which you want to cancel your UI customisation, and then, on the **Home** tab, in the **Manage** group, choose **Delete**.  
  
    > [!IMPORTANT]  
    >  If you have configured different UI customisations of the same page based on different navigation paths to the page, then each page customisation will be listed in the **Delete Profile Configuration** window with the same information. There is no information to identify which row relates to which navigation path. Therefore, you must either delete rows one by one followed by visual checks on the page, or you can delete all rows with UI customisations for the profile/page.
    >    
    >  All UI customisation for the page for the profile that you have ever made on the installation or since you last used the **Delete Profile Configuration** window is cancelled. The layout of the page is reset to the standard layout of the page object.  
  
### <a name="to-cancel-ui-customization-that-you-have-made-for-a-specific-ui-area-for-a-specific-page-for-a-profile"></a>To cancel UI customisation that you have made for a specific UI area for a specific page for a profile  
  
You can undo changes for that you have made to individual UI areas, such as a ribbon, by using the **Restore Defaults** button in the **Customise** window. Alternatively, you can undo all UI changes that you have made for a profile by using the **Delete Profile Configuration** window.  
  
The UI customisation for the profile of the particular UI area on the particular page is cancelled. The layout of the UI area on the page is reset to the default configuration, as made either by the administrator or as installed with the application.  
  
## <a name="see-also"></a>See Also  
[Customising [!INCLUDE[navnow_md](includes/navnow_md.md)]](ui-customizing-overview.md)   
