---
title: Change the Way a Report Looks by Selecting a Different Layout
description: You can use different layouts for a report, and switch between layouts to change how a report looks.
documentationcenter: 
author: jswymer
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: customized report, document layout, logo, personalize
ms.date: 03/29/2017
ms.author: jswymer
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: e3c919930421bcbb57a7452b80b69880f8859d7b
ms.contentlocale: en-gb
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-change-which-layout-is-currently-used-on-a-report"></a><span data-ttu-id="93699-103">How to: Change Which Layout is Currently Used on a Report</span><span class="sxs-lookup"><span data-stu-id="93699-103">How to: Change Which Layout is Currently Used on a Report</span></span>
<span data-ttu-id="93699-104">A report can be set up with more than one report layout, which you can then switch among as needed.</span><span class="sxs-lookup"><span data-stu-id="93699-104">A report can be set up with more than one report layout, which you can then switch among as needed.</span></span>

<span data-ttu-id="93699-105">Depending on the layouts that are available for a report, you can choose to use a built-in RDLC report layout, a built-in Word report layout, or a custom layout.</span><span class="sxs-lookup"><span data-stu-id="93699-105">Depending on the layouts that are available for a report, you can choose to use a built-in RDLC report layout, a built-in Word report layout, or a custom layout.</span></span> <span data-ttu-id="93699-106">For more information about RDLC and Word report layouts, built-in and custom layouts, and more, see [Manage Report Layouts](ui-manage-report-layouts.md).</span><span class="sxs-lookup"><span data-stu-id="93699-106">For more information about RDLC and Word report layouts, built-in and custom layouts, and more, see [Manage Report Layouts](ui-manage-report-layouts.md).</span></span>

## <a name="to-change-the-layout-that-is-used-on-a-report"></a><span data-ttu-id="93699-107">To change the layout that is used on a report</span><span class="sxs-lookup"><span data-stu-id="93699-107">To change the layout that is used on a report</span></span>
1. <span data-ttu-id="93699-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Report Layout Selection**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="93699-108">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Report Layout Selection**, and then choose the related link.</span></span>  
   <span data-ttu-id="93699-109">The **Report Layout Selection** window lists all the reports that are available for the company that is specified in the Company field at the top of the window.</span><span class="sxs-lookup"><span data-stu-id="93699-109">The **Report Layout Selection** window lists all the reports that are available for the company that is specified in the Company field at the top of the window.</span></span> <span data-ttu-id="93699-110">The Selected Layout field specifies the layout that is currently used on the report.</span><span class="sxs-lookup"><span data-stu-id="93699-110">The Selected Layout field specifies the layout that is currently used on the report.</span></span>
2. <span data-ttu-id="93699-111">Set the **Company** field at the top of the window to the company that includes the report.</span><span class="sxs-lookup"><span data-stu-id="93699-111">Set the **Company** field at the top of the window to the company that includes the report.</span></span>
3. <span data-ttu-id="93699-112">To change the layout that is used by a report, in the row for the report in the list, set the **Selected Layout** field to one of the following options:</span><span class="sxs-lookup"><span data-stu-id="93699-112">To change the layout that is used by a report, in the row for the report in the list, set the **Selected Layout** field to one of the following options:</span></span>
   * <span data-ttu-id="93699-113">RDLC (built-in), uses the built-in RDLC report layout on the report.</span><span class="sxs-lookup"><span data-stu-id="93699-113">RDLC (built-in), uses the built-in RDLC report layout on the report.</span></span>
   * <span data-ttu-id="93699-114">Word (built-in), uses the built-in Word report layout on the report.</span><span class="sxs-lookup"><span data-stu-id="93699-114">Word (built-in), uses the built-in Word report layout on the report.</span></span>
   * <span data-ttu-id="93699-115">Custom, uses a custom layout on the report.</span><span class="sxs-lookup"><span data-stu-id="93699-115">Custom, uses a custom layout on the report.</span></span>  
     <span data-ttu-id="93699-116">You can see which custom layouts are available for the report in the Report Layouts Part FactBox.</span><span class="sxs-lookup"><span data-stu-id="93699-116">You can see which custom layouts are available for the report in the Report Layouts Part FactBox.</span></span> <span data-ttu-id="93699-117">If there are no custom layouts for the report, then you will have to create one first.</span><span class="sxs-lookup"><span data-stu-id="93699-117">If there are no custom layouts for the report, then you will have to create one first.</span></span> <span data-ttu-id="93699-118">If you choose this option, go to the next procedure to specify the custom layout that you want to use.</span><span class="sxs-lookup"><span data-stu-id="93699-118">If you choose this option, go to the next procedure to specify the custom layout that you want to use.</span></span>

    > [!NOTE]  
    >   <span data-ttu-id="93699-119">If you choose **RDLC (built-in)** or **Word (built-in)** and you get an error message that the report does not have a layout of the specified type, then you must choose another layout option or create a custom report layout of the type that you want to use.</span><span class="sxs-lookup"><span data-stu-id="93699-119">If you choose **RDLC (built-in)** or **Word (built-in)** and you get an error message that the report does not have a layout of the specified type, then you must choose another layout option or create a custom report layout of the type that you want to use.</span></span>

<span data-ttu-id="93699-120">If you selected a built-in RDLC or Word report layout, then no further action is required and the layout will be used the next time the report is run.</span><span class="sxs-lookup"><span data-stu-id="93699-120">If you selected a built-in RDLC or Word report layout, then no further action is required and the layout will be used the next time the report is run.</span></span>

## <a name="to-specify-a-custom-layout-on-a-report"></a><span data-ttu-id="93699-121">To specify a custom layout on a report</span><span class="sxs-lookup"><span data-stu-id="93699-121">To specify a custom layout on a report</span></span>
1. <span data-ttu-id="93699-122">You specify which custom layout to use on the report from the **Custom Report Layouts** window.</span><span class="sxs-lookup"><span data-stu-id="93699-122">You specify which custom layout to use on the report from the **Custom Report Layouts** window.</span></span> <span data-ttu-id="93699-123">If the **Custom Report Layouts** window is not open, then in the **Report Layout Description** field, choose the lookup button.</span><span class="sxs-lookup"><span data-stu-id="93699-123">If the **Custom Report Layouts** window is not open, then in the **Report Layout Description** field, choose the lookup button.</span></span>
2. <span data-ttu-id="93699-124">In the **Custom Report Layouts** window, select the row for custom layout that you want to use, and then close the window.</span><span class="sxs-lookup"><span data-stu-id="93699-124">In the **Custom Report Layouts** window, select the row for custom layout that you want to use, and then close the window.</span></span>

<span data-ttu-id="93699-125">You return to the **Report Layout Selection** window.</span><span class="sxs-lookup"><span data-stu-id="93699-125">You return to the **Report Layout Selection** window.</span></span> <span data-ttu-id="93699-126">The name of the selected custom layout displays in the **Custom Layout Description** field.</span><span class="sxs-lookup"><span data-stu-id="93699-126">The name of the selected custom layout displays in the **Custom Layout Description** field.</span></span> <span data-ttu-id="93699-127">The custom layout will be used the next time that you run the report.</span><span class="sxs-lookup"><span data-stu-id="93699-127">The custom layout will be used the next time that you run the report.</span></span>

## <a name="see-also"></a><span data-ttu-id="93699-128">See Also</span><span class="sxs-lookup"><span data-stu-id="93699-128">See Also</span></span>
[<span data-ttu-id="93699-129">Managing Report Layouts</span><span class="sxs-lookup"><span data-stu-id="93699-129">Managing Report Layouts</span></span>](ui-manage-report-layouts.md)  
<span data-ttu-id="93699-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="93699-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

