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
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: cd60cbc206b8e2cd6665b98ee49a5dc10c50fe08
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="managing-profiles-and-role-centers"></a><span data-ttu-id="a5665-103">Managing Profiles and Role Centres</span><span class="sxs-lookup"><span data-stu-id="a5665-103">Managing Profiles and Role Centers</span></span>
<span data-ttu-id="a5665-104">Profiles are collections of [!INCLUDE[navnow_md](includes/navnow_md.md)] users who share the same Role Center.</span><span class="sxs-lookup"><span data-stu-id="a5665-104">Profiles are collections of [!INCLUDE[navnow_md](includes/navnow_md.md)] users who share the same Role Center.</span></span> <span data-ttu-id="a5665-105">A Role Centre is a type of page on which you can place different parts.</span><span class="sxs-lookup"><span data-stu-id="a5665-105">A Role Center is a type of page on which you can place different parts.</span></span> <span data-ttu-id="a5665-106">Each part is a container in which you can host other pages or pre-defined system parts, such as an Outlook part or parts for adding tasks, notifications, or notes.</span><span class="sxs-lookup"><span data-stu-id="a5665-106">Each part is a container in which you can host other pages or pre-defined system parts, such as an Outlook part or parts for adding tasks, notifications, or notes.</span></span>  

## <a name="about-profiles-and-role-centers"></a><span data-ttu-id="a5665-107">About profiles and Role Centres</span><span class="sxs-lookup"><span data-stu-id="a5665-107">About profiles and Role Centers</span></span>
<span data-ttu-id="a5665-108">You use profiles to link users to pre-defined Role Centres.</span><span class="sxs-lookup"><span data-stu-id="a5665-108">You use profiles to link users to pre-defined Role Centers.</span></span> <span data-ttu-id="a5665-109">A Role Centre is a home page for all users of a profile, which has been configured to reflect the tasks and priorities of users of the profile.</span><span class="sxs-lookup"><span data-stu-id="a5665-109">A Role Center is a home page for all users of a profile, which has been configured to reflect the tasks and priorities of users of the profile.</span></span> <span data-ttu-id="a5665-110">For example, the Order Processor Role Centre has been configured to reflect the tasks and priorities of an order processor.</span><span class="sxs-lookup"><span data-stu-id="a5665-110">For example, the Order Processor Role Center has been configured to reflect the tasks and priorities of an order processor.</span></span> <span data-ttu-id="a5665-111">A Role Centre provides easy access to information users need to perform their daily work.</span><span class="sxs-lookup"><span data-stu-id="a5665-111">A Role Center provides easy access to information users need to perform their daily work.</span></span> <span data-ttu-id="a5665-112">For example, the Role Centre determines the Cues, or tile, that show when isers first sign in, and the links from the navigation page.</span><span class="sxs-lookup"><span data-stu-id="a5665-112">For example, the Role Center determines the Cues, or tile, that show when isers first sign in, and the links from the navigation page.</span></span>

<span data-ttu-id="a5665-113">The profile that is used appears in the header of the Role Centre’s main content area.</span><span class="sxs-lookup"><span data-stu-id="a5665-113">The profile that is used appears in the header of the Role Center’s main content area.</span></span> <span data-ttu-id="a5665-114">An administrator can customise this Role Centre to meet the needs of a specific role in a specific company.</span><span class="sxs-lookup"><span data-stu-id="a5665-114">An administrator can customize this Role Center to meet the needs of a specific role in a specific company.</span></span> <span data-ttu-id="a5665-115">The Order Processor Role Centre can then be further personalised on a single computer to meet the needs of a person who is carrying out the job as an order processor.</span><span class="sxs-lookup"><span data-stu-id="a5665-115">The Order Processor Role Center can then be further personalized on a single computer to meet the needs of a person who is carrying out the job as an order processor.</span></span> <span data-ttu-id="a5665-116">This person can personalise the Role Centre by saving queries, adding filters, and adding or removing fields.</span><span class="sxs-lookup"><span data-stu-id="a5665-116">This person can personalize the Role Center by saving queries, adding filters, and adding or removing fields.</span></span>

<span data-ttu-id="a5665-117">Profiles and Role Centres align with the roles and responsibilities in your organisation.</span><span class="sxs-lookup"><span data-stu-id="a5665-117">Profiles and Role Centers align with the roles and responsibilities in your organization.</span></span> [!INCLUDE[navnow_md](includes/navnow_md.md)]<span data-ttu-id="a5665-118"> provides a set of default profiles, which each correspond to and link to a Role Center.</span><span class="sxs-lookup"><span data-stu-id="a5665-118"> provides a set of default profiles, which each correspond to and link to a Role Center.</span></span> <span data-ttu-id="a5665-119">Administrators can modify existing profiles or create new ones.</span><span class="sxs-lookup"><span data-stu-id="a5665-119">Administrators can modify existing profiles or create new ones.</span></span>  
  
> [!NOTE]  
>  <span data-ttu-id="a5665-120">Profiles are not explicitly linked to the roles and permissions that constitute the security system, but profile users must have permissions that align with their roles in the security system.</span><span class="sxs-lookup"><span data-stu-id="a5665-120">Profiles are not explicitly linked to the roles and permissions that constitute the security system, but profile users must have permissions that align with their roles in the security system.</span></span> <span data-ttu-id="a5665-121">For more information, see [Security in the Role Tailored Environment](http://go.microsoft.com/fwlink?LinkId=147633) in the MSDN Library.</span><span class="sxs-lookup"><span data-stu-id="a5665-121">For more information, see [Security in the Role Tailored Environment](http://go.microsoft.com/fwlink?LinkId=147633) in the MSDN Library.</span></span> 

## <a name="to-create-a-profile"></a><span data-ttu-id="a5665-122">To create a profile</span><span class="sxs-lookup"><span data-stu-id="a5665-122">To create a profile</span></span>
1.  <span data-ttu-id="a5665-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Profiles**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="a5665-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Profiles**, and then choose the related link.</span></span>  
  
2.  <span data-ttu-id="a5665-124">Choose the **New** action to open the **New Profile Card** window.</span><span class="sxs-lookup"><span data-stu-id="a5665-124">Choose the **New** action to open the **New Profile Card** window.</span></span>  
  
3.  <span data-ttu-id="a5665-125">In the **Profile ID** field, enter a name that describes the intended role of the user.</span><span class="sxs-lookup"><span data-stu-id="a5665-125">In the **Profile ID** field, enter a name that describes the intended role of the user.</span></span>  
  
4.  <span data-ttu-id="a5665-126">In the **Description** field, enter a description of the Profile ID, for example, **Order Processor**.</span><span class="sxs-lookup"><span data-stu-id="a5665-126">In the **Description** field, enter a description of the Profile ID, for example, **Order Processor**.</span></span>  
  
5.  <span data-ttu-id="a5665-127">Set the **Role Centre ID** field to the Role Centre that you want to assign to the profile.</span><span class="sxs-lookup"><span data-stu-id="a5665-127">Set the **Role Center ID** field to the Role Center that you want to assign to the profile.</span></span>  
  
6.  <span data-ttu-id="a5665-128">To make this Role Centre the default for the profile, select the **Default Role Centre** chack box.</span><span class="sxs-lookup"><span data-stu-id="a5665-128">To make this Role Center the default for the profile, select the **Default Role Center** chack box.</span></span>  
  
7.  <span data-ttu-id="a5665-129">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="a5665-129">Choose the **OK** button.</span></span> <span data-ttu-id="a5665-130">.</span><span class="sxs-lookup"><span data-stu-id="a5665-130">.</span></span>  
  
<span data-ttu-id="a5665-131">The procedure for modifying an existing profile is the same, except you select an existing profile in the Profiles page instead of clicking **New**.</span><span class="sxs-lookup"><span data-stu-id="a5665-131">The procedure for modifying an existing profile is the same, except you select an existing profile in the Profiles page instead of clicking **New**.</span></span>  


##<a name="copying-a-profile"></a><span data-ttu-id="a5665-132">Copying a profile</span><span class="sxs-lookup"><span data-stu-id="a5665-132">Copying a profile</span></span> 
<span data-ttu-id="a5665-133">Copying a profile can save you time if you want to use similar settings on a profile and you only want to change a few settings.</span><span class="sxs-lookup"><span data-stu-id="a5665-133">Copying a profile can save you time if you want to use similar settings on a profile and you only want to change a few settings.</span></span>

1.  <span data-ttu-id="a5665-134">Open the profile that you want to copy, and then choose the **Copy Profile** action.</span><span class="sxs-lookup"><span data-stu-id="a5665-134">Open the profile that you want to copy, and then choose the **Copy Profile** action.</span></span>

2.  <span data-ttu-id="a5665-135">In **New Profile ID** field, enter a name for the profile that you want to copy.</span><span class="sxs-lookup"><span data-stu-id="a5665-135">In **New Profile ID** field, enter a name for the profile that you want to copy.</span></span> 

3.  <span data-ttu-id="a5665-136">Set the **New Profile Scope** field to one of the following:</span><span class="sxs-lookup"><span data-stu-id="a5665-136">Set the **New Profile Scope** field to one of the following:</span></span>

    - <span data-ttu-id="a5665-137">**System** to make the new profile available to all tenant databases that use the application.</span><span class="sxs-lookup"><span data-stu-id="a5665-137">**System** to make the new profile available to all tenant databases that use the application.</span></span>
    - <span data-ttu-id="a5665-138">**Tenant** to make the new profile available to just the current tenant database.</span><span class="sxs-lookup"><span data-stu-id="a5665-138">**Tenant** to make the new profile available to just the current tenant database.</span></span> 
4. <span data-ttu-id="a5665-139">Choose the **OK** buttom when done.</span><span class="sxs-lookup"><span data-stu-id="a5665-139">Choose the **OK** buttom when done.</span></span>

## <span data-ttu-id="a5665-140"><a name="ExportImportProfile"></a>Exporting and importing profiles</span><span class="sxs-lookup"><span data-stu-id="a5665-140"><a name="ExportImportProfile"></a>Exporting and importing profiles</span></span>

<span data-ttu-id="a5665-141">You can export and import profiles as XML files to and from the a [!INCLUDE[d365fin](includes/d365fin_md.md)] database.</span><span class="sxs-lookup"><span data-stu-id="a5665-141">You can export and import profiles as XML files to and from the a [!INCLUDE[d365fin](includes/d365fin_md.md)] database.</span></span> <span data-ttu-id="a5665-142">Exporting and importing a profile can save you time when configuring the user interface because you reuse an existing profile configuration instead of having to configure a profile from scratch.</span><span class="sxs-lookup"><span data-stu-id="a5665-142">Exporting and importing a profile can save you time when configuring the user interface because you reuse an existing profile configuration instead of having to configure a profile from scratch.</span></span> <span data-ttu-id="a5665-143">If you have a profile that is configured in a [!INCLUDE[d365fin](includes/d365fin_md.md)] database and you would like to reuse all or some of the same profile configurations in another database, you can export the profile to an XML file.</span><span class="sxs-lookup"><span data-stu-id="a5665-143">If you have a profile that is configured in a [!INCLUDE[d365fin](includes/d365fin_md.md)] database and you would like to reuse all or some of the same profile configurations in another database, you can export the profile to an XML file.</span></span> <span data-ttu-id="a5665-144">Then, you can import the profile XML file into the other database.</span><span class="sxs-lookup"><span data-stu-id="a5665-144">Then, you can import the profile XML file into the other database.</span></span>

-   <span data-ttu-id="a5665-145">To export a profile, open search for and open the **Export Profiles** page, select the profile from the list, and then choose the **Export** action.</span><span class="sxs-lookup"><span data-stu-id="a5665-145">To export a profile, open search for and open the **Export Profiles** page, select the profile from the list, and then choose the **Export** action.</span></span> <span data-ttu-id="a5665-146">Save the XML file to a location on your computer or network.</span><span class="sxs-lookup"><span data-stu-id="a5665-146">Save the XML file to a location on your computer or network.</span></span> 
  
-   <span data-ttu-id="a5665-147">To import a profile, open search for and open the **Import Profiles** page, select the profile XML file, and then choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="a5665-147">To import a profile, open search for and open the **Import Profiles** page, select the profile XML file, and then choose the **OK** button.</span></span> 

    > [!NOTE]  
    >  <span data-ttu-id="a5665-148">You cannot import a profile that already exists in the database, even though the XML file is named differently or has different content.</span><span class="sxs-lookup"><span data-stu-id="a5665-148">You cannot import a profile that already exists in the database, even though the XML file is named differently or has different content.</span></span> <span data-ttu-id="a5665-149">You must delete the existing profile before you can import the new profile.</span><span class="sxs-lookup"><span data-stu-id="a5665-149">You must delete the existing profile before you can import the new profile.</span></span> 



## <a name="see-also"></a><span data-ttu-id="a5665-150">See Also</span><span class="sxs-lookup"><span data-stu-id="a5665-150">See Also</span></span>  
[<span data-ttu-id="a5665-151">How to: Manage Users and Permissions</span><span class="sxs-lookup"><span data-stu-id="a5665-151">How to: Manage Users and Permissions</span></span>](ui-how-users-permissions.md)  
[<span data-ttu-id="a5665-152">Customising the User Interface</span><span class="sxs-lookup"><span data-stu-id="a5665-152">Customizing the User Interface</span></span>](ui-customizing-overview.md)   
<!--[Security Overview](../Security%20Overview.md)-->

