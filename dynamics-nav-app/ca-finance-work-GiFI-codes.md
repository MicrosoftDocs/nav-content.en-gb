---
title: 'How to: Work With GIFI Codes in Canada'
author: SorenGP
ms.custom: na
ms.date: 09/21/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 695bca0a6836c47610210b759ae48af27484761f
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

#<a name="how-to-work-with-gifi-codes-in-canada"></a><span data-ttu-id="4abb7-102">How to: Work With GIFI Codes in Canada</span><span class="sxs-lookup"><span data-stu-id="4abb7-102">How to: Work With GIFI Codes in Canada</span></span>
<span data-ttu-id="4abb7-103">Fiscal information can include general ledger accounts, reports, income statements, balance sheets, and statements of retained earnings.</span><span class="sxs-lookup"><span data-stu-id="4abb7-103">Fiscal information can include general ledger accounts, reports, income statements, balance sheets, and statements of retained earnings.</span></span> <span data-ttu-id="4abb7-104">Fiscal information is classified using codes.</span><span class="sxs-lookup"><span data-stu-id="4abb7-104">Fiscal information is classified using codes.</span></span> <span data-ttu-id="4abb7-105">The use of codes helps the government to process information, prepare for electronic filing, and validate tax information electronically.</span><span class="sxs-lookup"><span data-stu-id="4abb7-105">The use of codes helps the government to process information, prepare for electronic filing, and validate tax information electronically.</span></span> <span data-ttu-id="4abb7-106">The use of codes also helps statistical organizations to work more efficiently, as financial information is more readily available.</span><span class="sxs-lookup"><span data-stu-id="4abb7-106">The use of codes also helps statistical organizations to work more efficiently, as financial information is more readily available.</span></span> <span data-ttu-id="4abb7-107">For more information, see the [Canada Revenue Agency website](http://www.cra-arc.gc.ca/).</span><span class="sxs-lookup"><span data-stu-id="4abb7-107">For more information, see the [Canada Revenue Agency website](http://www.cra-arc.gc.ca/).</span></span>

<span data-ttu-id="4abb7-108">The Canada Revenue Agency uses General Index of Financial Information (GIFI) codes to collect, validate, and process financial and tax information electronically.</span><span class="sxs-lookup"><span data-stu-id="4abb7-108">The Canada Revenue Agency uses General Index of Financial Information (GIFI) codes to collect, validate, and process financial and tax information electronically.</span></span> <span data-ttu-id="4abb7-109">It is a best practice to assign GIFI codes only to posting accounts, so that all totalling is done by your tax preparation software.</span><span class="sxs-lookup"><span data-stu-id="4abb7-109">It is a best practice to assign GIFI codes only to posting accounts, so that all totaling is done by your tax preparation software.</span></span>

<span data-ttu-id="4abb7-110">When an account is associated with a GIFI code, it is reported to the revenue agency under that code.</span><span class="sxs-lookup"><span data-stu-id="4abb7-110">When an account is associated with a GIFI code, it is reported to the revenue agency under that code.</span></span> <span data-ttu-id="4abb7-111">Multiple accounts can all have the same GIFI code, but each account can have only one GIFI code.</span><span class="sxs-lookup"><span data-stu-id="4abb7-111">Multiple accounts can all have the same GIFI code, but each account can have only one GIFI code.</span></span>

<span data-ttu-id="4abb7-112">You can export balance information by GIFI code and save the exported file in Excel, which is useful for transferring information to your tax preparation software.</span><span class="sxs-lookup"><span data-stu-id="4abb7-112">You can export balance information by GIFI code and save the exported file in Excel, which is useful for transferring information to your tax preparation software.</span></span>

## <a name="to-set-up-gifi-codes"></a><span data-ttu-id="4abb7-113">To set up GIFI codes</span><span class="sxs-lookup"><span data-stu-id="4abb7-113">To set up GIFI codes</span></span>
<span data-ttu-id="4abb7-114">In Dynamics NAV, you must set up GIFI codes for general ledger accounts, reports, balance sheets, income sheets, and statements of retained earnings.</span><span class="sxs-lookup"><span data-stu-id="4abb7-114">In Dynamics NAV, you must set up GIFI codes for general ledger accounts, reports, balance sheets, income sheets, and statements of retained earnings.</span></span>

1. <span data-ttu-id="4abb7-115">In the top right corner, choose the **Search for Page or Report** icon, enter **GIFI Codes**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="4abb7-115">In the top right corner, choose the **Search for Page or Report** icon, enter **GIFI Codes**, and then choose the related link.</span></span>
2. <span data-ttu-id="4abb7-116">In the **GIFI Codes** window, choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="4abb7-116">In the **GIFI Codes** window, choose the **New** action.</span></span>
3. <span data-ttu-id="4abb7-117">Set up GIFI codes by filling the fields.</span><span class="sxs-lookup"><span data-stu-id="4abb7-117">Set up GIFI codes by filling the fields.</span></span> <span data-ttu-id="4abb7-118">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="4abb7-118">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-associate-gifi-codes-with-gl-accounts"></a><span data-ttu-id="4abb7-119">To associate GIFI codes with G/L accounts</span><span class="sxs-lookup"><span data-stu-id="4abb7-119">To associate GIFI codes with G/L accounts</span></span>
<span data-ttu-id="4abb7-120">To report financial information by GIFI code, each GIFI code must be associated with the appropriate accounts in the chart of accounts.</span><span class="sxs-lookup"><span data-stu-id="4abb7-120">To report financial information by GIFI code, each GIFI code must be associated with the appropriate accounts in the chart of accounts.</span></span>

1. <span data-ttu-id="4abb7-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="4abb7-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Chart of Accounts**, and then choose the related link.</span></span>
2. <span data-ttu-id="4abb7-122">Select a relevant general ledger account, and then choose the **Edit** action.</span><span class="sxs-lookup"><span data-stu-id="4abb7-122">Select a relevant general ledger account, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="4abb7-123">On the **Cost Accounting** FastTab, in the **GIFI Code** field, select an appropriate GIFI code.</span><span class="sxs-lookup"><span data-stu-id="4abb7-123">On the **Cost Accounting** FastTab, in the **GIFI Code** field, select an appropriate GIFI code.</span></span>

## <a name="to-view-account-balances-using-the-gifi-code-report"></a><span data-ttu-id="4abb7-124">To view account balances using the GIFI code report</span><span class="sxs-lookup"><span data-stu-id="4abb7-124">To view account balances using the GIFI code report</span></span>
<span data-ttu-id="4abb7-125">You can review your account balances by GIFI code by using the **Account Balances by GIFI Code** report.</span><span class="sxs-lookup"><span data-stu-id="4abb7-125">You can review your account balances by GIFI code by using the **Account Balances by GIFI Code** report.</span></span>

1. <span data-ttu-id="4abb7-126">In the top right corner, choose the **Search for Page or Report** icon, enter **Account Balances by GIFI Code**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="4abb7-126">In the top right corner, choose the **Search for Page or Report** icon, enter **Account Balances by GIFI Code**, and then choose the related link.</span></span>
2. <span data-ttu-id="4abb7-127">Specify what to include in the report by filling the fields.</span><span class="sxs-lookup"><span data-stu-id="4abb7-127">Specify what to include in the report by filling the fields.</span></span> <span data-ttu-id="4abb7-128">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="4abb7-128">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="4abb7-129">Choose the **Print** or the **Preview** button.</span><span class="sxs-lookup"><span data-stu-id="4abb7-129">Choose the **Print** or the **Preview** button.</span></span>

## <a name="to-export-balance-information-using-gifi-codes"></a><span data-ttu-id="4abb7-130">To export balance information using GIFI codes</span><span class="sxs-lookup"><span data-stu-id="4abb7-130">To export balance information using GIFI codes</span></span>
<span data-ttu-id="4abb7-131">You can export balance information using GIFI codes and save the exported file in Excel.</span><span class="sxs-lookup"><span data-stu-id="4abb7-131">You can export balance information using GIFI codes and save the exported file in Excel.</span></span> <span data-ttu-id="4abb7-132">You can modify, save, or delete the file.</span><span class="sxs-lookup"><span data-stu-id="4abb7-132">You can modify, save, or delete the file.</span></span> <span data-ttu-id="4abb7-133">You can use the file to transfer information to your tax preparation software.</span><span class="sxs-lookup"><span data-stu-id="4abb7-133">You can use the file to transfer information to your tax preparation software.</span></span>

1. <span data-ttu-id="4abb7-134">In the top right corner, choose the **Search for Page or Report** icon, enter **Export GIFI Info. to Excel**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="4abb7-134">In the top right corner, choose the **Search for Page or Report** icon, enter **Export GIFI Info. to Excel**, and then choose the related link.</span></span>
2. <span data-ttu-id="4abb7-135">Specify what to export to Excel by filling the fields.</span><span class="sxs-lookup"><span data-stu-id="4abb7-135">Specify what to export to Excel by filling the fields.</span></span> <span data-ttu-id="4abb7-136">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="4abb7-136">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="4abb7-137">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="4abb7-137">Choose the **OK** button.</span></span>

<span data-ttu-id="4abb7-138">**Note:** The Excel file has the following characteristics:</span><span class="sxs-lookup"><span data-stu-id="4abb7-138">**Note:** The Excel file has the following characteristics:</span></span>

* <span data-ttu-id="4abb7-139">The balance is rounded to the nearest percentage, but the cell value maintains the same percentage as it does in the general ledger.</span><span class="sxs-lookup"><span data-stu-id="4abb7-139">The balance is rounded to the nearest percentage, but the cell value maintains the same percentage as it does in the general ledger.</span></span>

* <span data-ttu-id="4abb7-140">Negative numbers are represented as positive number in brackets.</span><span class="sxs-lookup"><span data-stu-id="4abb7-140">Negative numbers are represented as positive number in brackets.</span></span> <span data-ttu-id="4abb7-141">Accordingly, -123 is represented as (123).</span><span class="sxs-lookup"><span data-stu-id="4abb7-141">Accordingly, -123 is represented as (123).</span></span>

## <a name="see-also"></a><span data-ttu-id="4abb7-142">See Also</span><span class="sxs-lookup"><span data-stu-id="4abb7-142">See Also</span></span>
<span data-ttu-id="4abb7-143">[Finance](finance-setup.md) </span><span class="sxs-lookup"><span data-stu-id="4abb7-143">[Finance](finance-setup.md) </span></span>  
[<span data-ttu-id="4abb7-144">Set Up Core Financial Processes</span><span class="sxs-lookup"><span data-stu-id="4abb7-144">Set Up Core Financial Processes</span></span>](finance-setup-setup-finance-setup.md)

