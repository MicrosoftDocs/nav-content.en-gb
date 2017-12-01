---
title: How to Create Special Orders
description: You can create a special order for a specific nonstock item to be shipped to a specific customer. Your vendor ships the item to your warehouse and you can then ship the item on to your customer either independently or together with other items on another order.
author: SorenGP
ms.prod: dynamics-nav-2018
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/08/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 1dfba8b14019991c95f40ffd5f7fbaed5df414eb
ms.openlocfilehash: 596b9a5638e551a8165429308a68a4c8dddb6a06
ms.contentlocale: en-gb
ms.lasthandoff: 12/01/2017

---
# <a name="how-to-create-special-orders"></a><span data-ttu-id="cdb7c-104">How to: Create Special Orders</span><span class="sxs-lookup"><span data-stu-id="cdb7c-104">How to: Create Special Orders</span></span>
<span data-ttu-id="cdb7c-105">You can create a special order for a specific nonstock item to be shipped to a specific customer.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-105">You can create a special order for a specific nonstock item to be shipped to a specific customer.</span></span> <span data-ttu-id="cdb7c-106">Your vendor ships the item to your warehouse and you can then ship the item on to your customer either independently or together with other items on another order.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-106">Your vendor ships the item to your warehouse and you can then ship the item on to your customer either independently or together with other items on another order.</span></span>  

<span data-ttu-id="cdb7c-107">Special orders imply that the purchase and sales order are linked to ensure that the specific nonstock item is picked and delivered to the customer.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-107">Special orders imply that the purchase and sales order are linked to ensure that the specific nonstock item is picked and delivered to the customer.</span></span>  

<span data-ttu-id="cdb7c-108">Before you can use this feature, you must first set up the customer, vendor, and item cards necessary for the order.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-108">Before you can use this feature, you must first set up the customer, vendor, and item cards necessary for the order.</span></span>  

## <a name="to-create-a-special-order"></a><span data-ttu-id="cdb7c-109">To create a special order</span><span class="sxs-lookup"><span data-stu-id="cdb7c-109">To create a special order</span></span>  
1.  <span data-ttu-id="cdb7c-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Order**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-110">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Sales Order**, and then choose the related link.</span></span>  
2. <span data-ttu-id="cdb7c-111">Choose the **New** action.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-111">Choose the **New** action.</span></span> <span data-ttu-id="cdb7c-112">Create and fill in a  sales order for the item.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-112">Create and fill in a  sales order for the item.</span></span> <span data-ttu-id="cdb7c-113">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span><span class="sxs-lookup"><span data-stu-id="cdb7c-113">For more information, see [How to: Sell Products](sales-how-sell-products.md).</span></span>
3.  <span data-ttu-id="cdb7c-114">On the **Lines** FastTab, fill in the sales line.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-114">On the **Lines** FastTab, fill in the sales line.</span></span> <span data-ttu-id="cdb7c-115">In the **Purchasing Code** field, select a purchasing code that has the **Special Order** field selected.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-115">In the **Purchasing Code** field, select a purchasing code that has the **Special Order** field selected.</span></span>

    <span data-ttu-id="cdb7c-116">You must now create a purchase order from a requisition worksheet.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-116">You must now create a purchase order from a requisition worksheet.</span></span>  
4. <span data-ttu-id="cdb7c-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Requisition Worksheet**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-117">Choose the ![Search for Page or Report](media/ui-search/search_small.png "Search for Page or Report icon") icon, enter **Requisition Worksheet**, and then choose the related link.</span></span>  
5. <span data-ttu-id="cdb7c-118">Choose the **Special Order** action, and then choose the **Get Sales Orders** action.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-118">Choose the **Special Order** action, and then choose the **Get Sales Orders** action.</span></span>  
6.  <span data-ttu-id="cdb7c-119">In the **Get Sales Orders** window, show results where the **Document No.** is the sales order number.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-119">In the **Get Sales Orders** window, show results where the **Document No.** is the sales order number.</span></span> <span data-ttu-id="cdb7c-120">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-120">Choose the **OK** button.</span></span> <span data-ttu-id="cdb7c-121">A requisition worksheet line is created for the item.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-121">A requisition worksheet line is created for the item.</span></span>  
7.  <span data-ttu-id="cdb7c-122">On the requisition worksheet line, in the **Action Message** field, select **New**.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-122">On the requisition worksheet line, in the **Action Message** field, select **New**.</span></span>  
8.  <span data-ttu-id="cdb7c-123">In the **Req. Worksheet** window, choose the **Carry Out Action Message** action.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-123">In the **Req. Worksheet** window, choose the **Carry Out Action Message** action.</span></span> <span data-ttu-id="cdb7c-124">The **Carry Out Action Msg. - Req.** window opens.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-124">The **Carry Out Action Msg. - Req.** window opens.</span></span> <span data-ttu-id="cdb7c-125">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-125">Choose the **OK** button.</span></span>  

    <span data-ttu-id="cdb7c-126">A message appears telling you that the purchase orders have been created.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-126">A message appears telling you that the purchase orders have been created.</span></span> <span data-ttu-id="cdb7c-127">Choost the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-127">Choost the **OK** button.</span></span>  

<span data-ttu-id="cdb7c-128">A purchase order created as a special order for a sales order is respected by the planning system as it balances demand and supply.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-128">A purchase order created as a special order for a sales order is respected by the planning system as it balances demand and supply.</span></span> <span data-ttu-id="cdb7c-129">That is, the purchase order (supply) remains linked to the sales order (demand), even if that purchase order could supply another earlier demand.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-129">That is, the purchase order (supply) remains linked to the sales order (demand), even if that purchase order could supply another earlier demand.</span></span> <span data-ttu-id="cdb7c-130">For more information, see [Design Details: Reordering Policies](design-details-reservation-order-tracking-and-action-messaging.md).</span><span class="sxs-lookup"><span data-stu-id="cdb7c-130">For more information, see [Design Details: Reordering Policies](design-details-reservation-order-tracking-and-action-messaging.md).</span></span>  

> [!NOTE]  
>  <span data-ttu-id="cdb7c-131">You cannot use the special order functionality if the item is already reserved.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-131">You cannot use the special order functionality if the item is already reserved.</span></span> <span data-ttu-id="cdb7c-132">Therefore, for items that are sold on special orders, make sure the **Reserve** field on the item card is not set to **Always**.</span><span class="sxs-lookup"><span data-stu-id="cdb7c-132">Therefore, for items that are sold on special orders, make sure the **Reserve** field on the item card is not set to **Always**.</span></span>  

## <a name="see-also"></a><span data-ttu-id="cdb7c-133">See Also</span><span class="sxs-lookup"><span data-stu-id="cdb7c-133">See Also</span></span>  
[<span data-ttu-id="cdb7c-134">How to: Work with Nonstock Items</span><span class="sxs-lookup"><span data-stu-id="cdb7c-134">How to: Work with Nonstock Items</span></span>](inventory-how-work-nonstock-items.md)  
[<span data-ttu-id="cdb7c-135">Sales</span><span class="sxs-lookup"><span data-stu-id="cdb7c-135">Sales</span></span>](sales-manage-sales.md)  
<span data-ttu-id="cdb7c-136">[How to: Make Drop Shipments](sales-how-drop-shipment.md) </span><span class="sxs-lookup"><span data-stu-id="cdb7c-136">[How to: Make Drop Shipments](sales-how-drop-shipment.md) </span></span>  
[<span data-ttu-id="cdb7c-137">Design Details: Reordering Policies</span><span class="sxs-lookup"><span data-stu-id="cdb7c-137">Design Details: Reordering Policies</span></span>](design-details-reservation-order-tracking-and-action-messaging.md)  
<span data-ttu-id="cdb7c-138">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="cdb7c-138">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

