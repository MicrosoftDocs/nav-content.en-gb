---
title: How to Verify VAT Registration Numbers
description: You can use an EU web service to verify that VAT registration numbers that you enter on customer, vendor, or contact cards are valid.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 08/10/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 8ed345e346ba32a38ebb2738afbe6c12749842ff
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="how-to-verify-vat-registration-numbers"></a><span data-ttu-id="a8403-103">How to: Verify VAT Registration Numbers</span><span class="sxs-lookup"><span data-stu-id="a8403-103">How to: Verify VAT Registration Numbers</span></span>
<span data-ttu-id="a8403-104">You can use an EU web service to verify that VAT registration numbers that you enter on customer, vendor, or contact cards are valid.</span><span class="sxs-lookup"><span data-stu-id="a8403-104">You can use an EU web service to verify that VAT registration numbers that you enter on customer, vendor, or contact cards are valid.</span></span>  

 <span data-ttu-id="a8403-105">When you modify the **VAT Registration No.** field on a card where the value in the **Country/Region Code** field is an EU country/region, then the new VAT registration number and your user ID are logged in the **VAT Registration Log** window.</span><span class="sxs-lookup"><span data-stu-id="a8403-105">When you modify the **VAT Registration No.** field on a card where the value in the **Country/Region Code** field is an EU country/region, then the new VAT registration number and your user ID are logged in the **VAT Registration Log** window.</span></span> <span data-ttu-id="a8403-106">You verify a VAT registration number by choosing the **Verify Registration No.** button in the **VAT Registration Log** window.</span><span class="sxs-lookup"><span data-stu-id="a8403-106">You verify a VAT registration number by choosing the **Verify Registration No.** button in the **VAT Registration Log** window.</span></span> <span data-ttu-id="a8403-107">A new line is created every time you use the verification function.</span><span class="sxs-lookup"><span data-stu-id="a8403-107">A new line is created every time you use the verification function.</span></span> <span data-ttu-id="a8403-108">If the number could be verified, the **Status** field contains **Valid**.</span><span class="sxs-lookup"><span data-stu-id="a8403-108">If the number could be verified, the **Status** field contains **Valid**.</span></span> <span data-ttu-id="a8403-109">If the number could not be verified, the **Status** field contains **Invalid**, and you must then change the number in the **VAT Registration No.** field on the card and start the verification function again.</span><span class="sxs-lookup"><span data-stu-id="a8403-109">If the number could not be verified, the **Status** field contains **Invalid**, and you must then change the number in the **VAT Registration No.** field on the card and start the verification function again.</span></span>  

 <span data-ttu-id="a8403-110">The URL of the default web service is set up in the **VAT Reg. No. Validation URL** field in the **General Ledger Setup** window.</span><span class="sxs-lookup"><span data-stu-id="a8403-110">The URL of the default web service is set up in the **VAT Reg. No. Validation URL** field in the **General Ledger Setup** window.</span></span>  

 <span data-ttu-id="a8403-111">In the **VAT Registration No. Format** table, you can change for each country/region the different formats of VAT registration number that users are allowed to enter in the **VAT Registration No.** field.</span><span class="sxs-lookup"><span data-stu-id="a8403-111">In the **VAT Registration No. Format** table, you can change for each country/region the different formats of VAT registration number that users are allowed to enter in the **VAT Registration No.** field.</span></span>  

> [!WARNING]  
>  <span data-ttu-id="a8403-112">This web service uses the http protocol, which means that data transferred through the service is not encrypted.</span><span class="sxs-lookup"><span data-stu-id="a8403-112">This web service uses the http protocol, which means that data transferred through the service is not encrypted.</span></span>  

> [!NOTE]  
>  <span data-ttu-id="a8403-113">You may experience downtime for this service for which Microsoft is not responsible, as the service is part of a broad EU network of national VAT registers.</span><span class="sxs-lookup"><span data-stu-id="a8403-113">You may experience downtime for this service for which Microsoft is not responsible, as the service is part of a broad EU network of national VAT registers.</span></span>  

## <a name="to-verify-a-vat-registration-number-from-a-customer-card"></a><span data-ttu-id="a8403-114">To verify a VAT registration number from a customer card</span><span class="sxs-lookup"><span data-stu-id="a8403-114">To verify a VAT registration number from a customer card</span></span>  
<span data-ttu-id="a8403-115">The following describes how to verify a VAT registration number for a customer.</span><span class="sxs-lookup"><span data-stu-id="a8403-115">The following describes how to verify a VAT registration number for a customer.</span></span> <span data-ttu-id="a8403-116">The steps are similar for a vendor and a contact.</span><span class="sxs-lookup"><span data-stu-id="a8403-116">The steps are similar for a vendor and a contact.</span></span>   
1.  <span data-ttu-id="a8403-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="a8403-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Customers**, and then choose the related link.</span></span>  

2.  <span data-ttu-id="a8403-118">Open the card of a customer where you want to verify the VAT registration number.</span><span class="sxs-lookup"><span data-stu-id="a8403-118">Open the card of a customer where you want to verify the VAT registration number.</span></span>  

    > [!NOTE]  
    >  <span data-ttu-id="a8403-119">The **Country/Region Code** field on the customer card must contain an EU country/region.</span><span class="sxs-lookup"><span data-stu-id="a8403-119">The **Country/Region Code** field on the customer card must contain an EU country/region.</span></span>  
3.  <span data-ttu-id="a8403-120">On the **Invoicing** FastTab, choose the DrillDown button next to the **VAT Registration No.** field.</span><span class="sxs-lookup"><span data-stu-id="a8403-120">On the **Invoicing** FastTab, choose the DrillDown button next to the **VAT Registration No.** field.</span></span>  

    <span data-ttu-id="a8403-121">The **VAT Registration Log** window opens showing one line where the **Status** field contains **Not Verified**.</span><span class="sxs-lookup"><span data-stu-id="a8403-121">The **VAT Registration Log** window opens showing one line where the **Status** field contains **Not Verified**.</span></span>  
4.  <span data-ttu-id="a8403-122">Choose the **Verify Registration No.** action.</span><span class="sxs-lookup"><span data-stu-id="a8403-122">Choose the **Verify Registration No.** action.</span></span>  

     <span data-ttu-id="a8403-123">A new line is created where the **Status** field contains either **Valid** or **Invalid**.</span><span class="sxs-lookup"><span data-stu-id="a8403-123">A new line is created where the **Status** field contains either **Valid** or **Invalid**.</span></span>  
5.  <span data-ttu-id="a8403-124">If the **Status** field contains **Invalid**, change the number in the **VAT Registration No.** field on the card, and then repeat steps 3 through 4.</span><span class="sxs-lookup"><span data-stu-id="a8403-124">If the **Status** field contains **Invalid**, change the number in the **VAT Registration No.** field on the card, and then repeat steps 3 through 4.</span></span>  

## <a name="see-also"></a><span data-ttu-id="a8403-125">See Also</span><span class="sxs-lookup"><span data-stu-id="a8403-125">See Also</span></span>  
[<span data-ttu-id="a8403-126">Finance</span><span class="sxs-lookup"><span data-stu-id="a8403-126">Finance</span></span>](finance.md)  
[<span data-ttu-id="a8403-127">How to: Register New Customers</span><span class="sxs-lookup"><span data-stu-id="a8403-127">How to: Register New Customers</span></span>](sales-how-register-new-customers.md)  
[<span data-ttu-id="a8403-128">How to: Register New Vendors</span><span class="sxs-lookup"><span data-stu-id="a8403-128">How to: Register New Vendors</span></span>](purchasing-how-register-new-vendors.md)  
<span data-ttu-id="a8403-129">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="a8403-129">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

