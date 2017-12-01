---
title: 'How to: Enable Customer Payments Through PayPal'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2018
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 92b00332f3fb5adff12d518ca2af4aa4093fbf7a
ms.contentlocale: en-gb
ms.lasthandoff: 12/01/2017

---

# <a name="how-to-enable-customer-payments-through-paypal"></a><span data-ttu-id="1371d-102">How to: Enable Customer Payments Through PayPal#</span><span class="sxs-lookup"><span data-stu-id="1371d-102">How to: Enable Customer Payments Through PayPal#</span></span>
<span data-ttu-id="1371d-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span><span class="sxs-lookup"><span data-stu-id="1371d-103">As an alternative to collecting payments through bank transfer or credit cards, you can offer your customers to pay you through their PayPal account.</span></span>

<span data-ttu-id="1371d-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span><span class="sxs-lookup"><span data-stu-id="1371d-104">When a customer chooses the PayPal link on a sales invoice or sales order document, the service page for their PayPal account appears showing the payment details for the sale.</span></span> <span data-ttu-id="1371d-105">The customer can then pay the invoice as any other PayPal payment.</span><span class="sxs-lookup"><span data-stu-id="1371d-105">The customer can then pay the invoice as any other PayPal payment.</span></span>

<span data-ttu-id="1371d-106">To enable customer payments through PayPal, you must do the following:</span><span class="sxs-lookup"><span data-stu-id="1371d-106">To enable customer payments through PayPal, you must do the following:</span></span>

1. <span data-ttu-id="1371d-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span><span class="sxs-lookup"><span data-stu-id="1371d-107">Set up PayPal Payments Standard as a payment service in the **Payments Services** window.</span></span>
2. <span data-ttu-id="1371d-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span><span class="sxs-lookup"><span data-stu-id="1371d-108">Select PayPal Payments Standard in the **Payment Service** field on the sales document in question.</span></span>

<span data-ttu-id="1371d-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span><span class="sxs-lookup"><span data-stu-id="1371d-109">The PayPal Payments Standard service is installed as an extension to Dynamics NAV and ready to enabled.</span></span> <span data-ttu-id="1371d-110">For more information, see [Customizing Dynamics NAV Using Extensions](ui-extensions.md).</span><span class="sxs-lookup"><span data-stu-id="1371d-110">For more information, see [Customizing Dynamics NAV Using Extensions ](ui-extensions.md).</span></span>

## <a name="to-enable-the-paypal-payments-standard-service"></a><span data-ttu-id="1371d-111">To enable the PayPal Payments Standard service</span><span class="sxs-lookup"><span data-stu-id="1371d-111">To enable the PayPal Payments Standard service</span></span>
1. <span data-ttu-id="1371d-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="1371d-112">In the top right corner, choose the **Search for Page or Report** icon, **Payment Services**, and then choose the related link.</span></span>  
2. <span data-ttu-id="1371d-113">In the **Payment Services** window, choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="1371d-113">In the **Payment Services** window, choose the **New** action.</span></span>
3. <span data-ttu-id="1371d-114">Select **PayPal Standard**, and then close the window.</span><span class="sxs-lookup"><span data-stu-id="1371d-114">Select **PayPal Standard**, and then close the window.</span></span>
4. <span data-ttu-id="1371d-115">In the **Payment Services** window, choose the **Setup** action.</span><span class="sxs-lookup"><span data-stu-id="1371d-115">In the **Payment Services** window, choose the **Setup** action.</span></span>
5. <span data-ttu-id="1371d-116">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="1371d-116">Fill in the fields as necessary.</span></span> <span data-ttu-id="1371d-117">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="1371d-117">Choose a field to read a short description of the field or link to more information.</span></span>

    <span data-ttu-id="1371d-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span><span class="sxs-lookup"><span data-stu-id="1371d-118">**Note**: Select the **Always Include on Documents** check box if the hyperlink for the PayPal payment service should always be visible on sales documents where payment through PayPal is enabled.</span></span>

6. <span data-ttu-id="1371d-119">Close the window.</span><span class="sxs-lookup"><span data-stu-id="1371d-119">Close the window.</span></span>

## <a name="to-select-paypal-payments-standard-on-a-sales-invoice"></a><span data-ttu-id="1371d-120">To select PayPal Payments Standard on a sales invoice</span><span class="sxs-lookup"><span data-stu-id="1371d-120">To select PayPal Payments Standard on a sales invoice</span></span>
1. <span data-ttu-id="1371d-121">On the Home page, choose **Sales Invoices**.</span><span class="sxs-lookup"><span data-stu-id="1371d-121">On the Home page, choose **Sales Invoices**.</span></span>
2. <span data-ttu-id="1371d-122">Open the sales invoice that you want to enable PayPal payments for.</span><span class="sxs-lookup"><span data-stu-id="1371d-122">Open the sales invoice that you want to enable PayPal payments for.</span></span>
3. <span data-ttu-id="1371d-123">In the **Payment Service** field, choose PayPal Payments Standard.</span><span class="sxs-lookup"><span data-stu-id="1371d-123">In the **Payment Service** field, choose PayPal Payments Standard.</span></span>

<span data-ttu-id="1371d-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span><span class="sxs-lookup"><span data-stu-id="1371d-124">**Note**: The **Payment Service** field is only visible if the PayPal Payments Standard service is enabled.</span></span>   

## <a name="see-also"></a><span data-ttu-id="1371d-125">See Also</span><span class="sxs-lookup"><span data-stu-id="1371d-125">See Also</span></span>  
[<span data-ttu-id="1371d-126">Set Up Sales</span><span class="sxs-lookup"><span data-stu-id="1371d-126">Set Up Sales</span></span>](sales-setup-sales.md)  
[<span data-ttu-id="1371d-127">Manage Sales</span><span class="sxs-lookup"><span data-stu-id="1371d-127">Manage Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="1371d-128">Customizing Dynamics NAV Using Extensions</span><span class="sxs-lookup"><span data-stu-id="1371d-128">Customizing Dynamics NAV Using Extensions</span></span>](ui-extensions.md)

