---
title: Dispose or Retire FA
description: You must post a disposal value when you scrap, sell, or retire a fixed asset.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: scrap
ms.date: 06/02/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 38753282687aafa1d06542ba265225eb30720c20
ms.contentlocale: en-gb
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-dispose-of-or-retire-fixed-assets"></a><span data-ttu-id="9abf4-103">How to: Dispose of or Retire Fixed Assets</span><span class="sxs-lookup"><span data-stu-id="9abf4-103">How to: Dispose of or Retire Fixed Assets</span></span>
<span data-ttu-id="9abf4-104">When you sell or otherwise dispose of a fixed asset, the disposal value must be posted to calculate and record the gain or loss.</span><span class="sxs-lookup"><span data-stu-id="9abf4-104">When you sell or otherwise dispose of a fixed asset, the disposal value must be posted to calculate and record the gain or loss.</span></span> <span data-ttu-id="9abf4-105">A disposal entry must be the last entry posted for a fixed asset.</span><span class="sxs-lookup"><span data-stu-id="9abf4-105">A disposal entry must be the last entry posted for a fixed asset.</span></span> <span data-ttu-id="9abf4-106">For partially disposed fixed assets, you can post more than one disposal entry.</span><span class="sxs-lookup"><span data-stu-id="9abf4-106">For partially disposed fixed assets, you can post more than one disposal entry.</span></span> <span data-ttu-id="9abf4-107">The total of all posted disposal amounts must be a credit amount.</span><span class="sxs-lookup"><span data-stu-id="9abf4-107">The total of all posted disposal amounts must be a credit amount.</span></span>  

> [!NOTE]  
>   <span data-ttu-id="9abf4-108">If you trade-in a fixed asset for another one, you must record both the sale of the old asset (disposal) and the purchase of the new one (acquisition).</span><span class="sxs-lookup"><span data-stu-id="9abf4-108">If you trade-in a fixed asset for another one, you must record both the sale of the old asset (disposal) and the purchase of the new one (acquisition).</span></span> <span data-ttu-id="9abf4-109">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span><span class="sxs-lookup"><span data-stu-id="9abf4-109">For more information, see [How to: Acquire Fixed Assets](fa-how-acquire.md).</span></span>  

## <a name="to-post-a-disposal-from-the-fixed-asset-gl-journal"></a><span data-ttu-id="9abf4-110">To post a disposal from the fixed asset G/L journal</span><span class="sxs-lookup"><span data-stu-id="9abf4-110">To post a disposal from the fixed asset G/L journal</span></span>
1. <span data-ttu-id="9abf4-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="9abf4-111">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **FA G/L Journals**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9abf4-112">Create an initial journal line and fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="9abf4-112">Create an initial journal line and fill in the fields as necessary.</span></span> [!INCLUDE[tooltip-inline-tip](includes/tooltip-inline-tip_md.md)]  
3. <span data-ttu-id="9abf4-113">In the **FA Posting Type** field, select **Disposal**.</span><span class="sxs-lookup"><span data-stu-id="9abf4-113">In the **FA Posting Type** field, select **Disposal**.</span></span>  
4. <span data-ttu-id="9abf4-114">Choose the **Insert FA Bal. Account** action.</span><span class="sxs-lookup"><span data-stu-id="9abf4-114">Choose the **Insert FA Bal. Account** action.</span></span> <span data-ttu-id="9abf4-115">A second journal line is created for the balancing account that is set up for disposal posting.</span><span class="sxs-lookup"><span data-stu-id="9abf4-115">A second journal line is created for the balancing account that is set up for disposal posting.</span></span>  

    > [!NOTE]  
>   <span data-ttu-id="9abf4-116">Step 4 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Disposal Account** field contains the general ledger debit account and the **Disposal Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation.</span><span class="sxs-lookup"><span data-stu-id="9abf4-116">Step 4 only works if you have set up the following: In the **FA Posting Group Card** window for the posting group of the fixed asset, the **Disposal Account** field contains the general ledger debit account and the **Disposal Bal. Account** field contains the general ledger account to which you want to post balancing entries for appreciation.</span></span> <span data-ttu-id="9abf4-117">For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).</span><span class="sxs-lookup"><span data-stu-id="9abf4-117">For more information, see the "To set up fixed asset posting groups" section in [How to: Set Up General Fixed Asset Information](fa-how-setup-general.md).</span></span>  
5. <span data-ttu-id="9abf4-118">Choose the **Post** action.</span><span class="sxs-lookup"><span data-stu-id="9abf4-118">Choose the **Post** action.</span></span>  

    <span data-ttu-id="9abf4-119">If you sell or dispose of part of a fixed asset, you must split up the asset before you can record the disposal transaction.</span><span class="sxs-lookup"><span data-stu-id="9abf4-119">If you sell or dispose of part of a fixed asset, you must split up the asset before you can record the disposal transaction.</span></span> <span data-ttu-id="9abf4-120">For more information, see [How to: Transfer, Split, or Combine Fixed Assets](fa-how-trans-split-combine.md).</span><span class="sxs-lookup"><span data-stu-id="9abf4-120">For more information, see [How to: Transfer, Split, or Combine Fixed Assets](fa-how-trans-split-combine.md).</span></span>  

## <a name="to-view-disposal-ledger-entries"></a><span data-ttu-id="9abf4-121">To view disposal ledger entries</span><span class="sxs-lookup"><span data-stu-id="9abf4-121">To view disposal ledger entries</span></span>
<span data-ttu-id="9abf4-122">When you sell or dispose of a fixed asset, the disposal value is posted to the general ledger where you can view the result.</span><span class="sxs-lookup"><span data-stu-id="9abf4-122">When you sell or dispose of a fixed asset, the disposal value is posted to the general ledger where you can view the result.</span></span>  

1. <span data-ttu-id="9abf4-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="9abf4-123">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Fixed Assets**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9abf4-124">Select the fixed asset that you want to view entries for, and then choose the **Depreciation Books** action.</span><span class="sxs-lookup"><span data-stu-id="9abf4-124">Select the fixed asset that you want to view entries for, and then choose the **Depreciation Books** action.</span></span>  
3. <span data-ttu-id="9abf4-125">Select the depreciation book that you want to view entries for, and then choose the **Ledger Entries** action.</span><span class="sxs-lookup"><span data-stu-id="9abf4-125">Select the depreciation book that you want to view entries for, and then choose the **Ledger Entries** action.</span></span>  
4. <span data-ttu-id="9abf4-126">Select a line with **Disposal** in the **FA Posting Category** field, and then choose the **Navigate** action.</span><span class="sxs-lookup"><span data-stu-id="9abf4-126">Select a line with **Disposal** in the **FA Posting Category** field, and then choose the **Navigate** action.</span></span>  
5. <span data-ttu-id="9abf4-127">In the **Navigate** window, select the general ledger entry line, and then choose the **Show** action.</span><span class="sxs-lookup"><span data-stu-id="9abf4-127">In the **Navigate** window, select the general ledger entry line, and then choose the **Show** action.</span></span>  

<span data-ttu-id="9abf4-128">The **General Ledger Entries** window opens where you can see the entries that the disposal posting resulted in.</span><span class="sxs-lookup"><span data-stu-id="9abf4-128">The **General Ledger Entries** window opens where you can see the entries that the disposal posting resulted in.</span></span>  

## <a name="see-also"></a><span data-ttu-id="9abf4-129">See Also</span><span class="sxs-lookup"><span data-stu-id="9abf4-129">See Also</span></span>
[<span data-ttu-id="9abf4-130">Fixed Assets</span><span class="sxs-lookup"><span data-stu-id="9abf4-130">Fixed Assets</span></span>](fa-manage.md)  
[<span data-ttu-id="9abf4-131">Setting Up Fixed Assets</span><span class="sxs-lookup"><span data-stu-id="9abf4-131">Setting Up Fixed Assets</span></span>](fa-setup.md)  
[<span data-ttu-id="9abf4-132">Finance</span><span class="sxs-lookup"><span data-stu-id="9abf4-132">Finance</span></span>](finance.md)  
<span data-ttu-id="9abf4-133">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="9abf4-133">[Welcome to [!INCLUDE[d365fin_long](includes/d365fin_long_md.md)]](index.md)</span></span>  
<span data-ttu-id="9abf4-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="9abf4-134">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

