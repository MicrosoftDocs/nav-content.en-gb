---
title: 'How to: Invoice Jobs'
author: SorenGP
ms.custom: na
ms.date: 11/01/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: c0dcce83dfba30af38f33a6bf814b15862d5fc19
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="how-to-invoice-jobs"></a><span data-ttu-id="9ef5f-102">How to: Invoice Jobs</span><span class="sxs-lookup"><span data-stu-id="9ef5f-102">How to: Invoice Jobs</span></span>
<span data-ttu-id="9ef5f-103">During the project, job costs from resource usage, materials, and job-related purchases can accumulate.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-103">During the project, job costs from resource usage, materials, and job-related purchases can accumulate.</span></span> <span data-ttu-id="9ef5f-104">As the job progresses, these transactions get posted to the job journal.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-104">As the job progresses, these transactions get posted to the job journal.</span></span> <span data-ttu-id="9ef5f-105">It is important that all costs get recorded in the job journal before you invoice the customer.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-105">It is important that all costs get recorded in the job journal before you invoice the customer.</span></span>

<span data-ttu-id="9ef5f-106">You can invoice the whole job from the **Job Task Lines** window or only invoice selected billable lines from the **Planning Lines** window.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-106">You can invoice the whole job from the **Job Task Lines** window or only invoice selected billable lines from the **Planning Lines** window.</span></span> <span data-ttu-id="9ef5f-107">Invoicing can be done after the job is finished or at certain intervals during the job's progress based on an invoicing schedule.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-107">Invoicing can be done after the job is finished or at certain intervals during the job's progress based on an invoicing schedule.</span></span>

<span data-ttu-id="9ef5f-108">**Note**: If you select **Billable** in the **Job Line Type** field on the purchase documents for job-related purchases, then job planning lines that are ready to be invoiced to the customer are created.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-108">**Note**: If you select **Billable** in the **Job Line Type** field on the purchase documents for job-related purchases, then job planning lines that are ready to be invoiced to the customer are created.</span></span> <span data-ttu-id="9ef5f-109">For more information, see [How to: Manage Project Supplies](projects-how-manage-project-supplies.md).</span><span class="sxs-lookup"><span data-stu-id="9ef5f-109">For more information, see [How to: Manage Project Supplies](projects-how-manage-project-supplies.md).</span></span>

## <a name="to-create-and-post-a-job-sales-invoice"></a><span data-ttu-id="9ef5f-110">To create and post a job sales invoice</span><span class="sxs-lookup"><span data-stu-id="9ef5f-110">To create and post a job sales invoice</span></span>  
<span data-ttu-id="9ef5f-111">You can create an invoice for a job or for one or more job tasks for a customer when either the work to be invoiced is complete or the date for invoicing based on an invoicing schedule has been reached.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-111">You can create an invoice for a job or for one or more job tasks for a customer when either the work to be invoiced is complete or the date for invoicing based on an invoicing schedule has been reached.</span></span>

<span data-ttu-id="9ef5f-112">From the **Jobs** window, you can invoice a customer by selecting the job, and then choosing the **Create Job Sales Invoice** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-112">From the **Jobs** window, you can invoice a customer by selecting the job, and then choosing the **Create Job Sales Invoice** action.</span></span> <span data-ttu-id="9ef5f-113">The following procedure shows how to use a batch job to invoice multiple jobs.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-113">The following procedure shows how to use a batch job to invoice multiple jobs.</span></span>  

1. <span data-ttu-id="9ef5f-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Job Create Sales Invoice**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Job Create Sales Invoice**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9ef5f-115">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-115">Fill in the fields as necessary.</span></span> <span data-ttu-id="9ef5f-116">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-116">Choose a field to read a short description of the field or link to more information.</span></span>
3. <span data-ttu-id="9ef5f-117">Set filters if you want to limit the jobs that the batch job will process.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-117">Set filters if you want to limit the jobs that the batch job will process.</span></span>
3. <span data-ttu-id="9ef5f-118">Choose the **OK** button to create the invoices.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-118">Choose the **OK** button to create the invoices.</span></span>  

## <a name="to-create-multiple-job-sales-invoices-from-job-planning-lines"></a><span data-ttu-id="9ef5f-119">To create multiple job sales invoices from job planning lines</span><span class="sxs-lookup"><span data-stu-id="9ef5f-119">To create multiple job sales invoices from job planning lines</span></span>  
<span data-ttu-id="9ef5f-120">You can create an invoice from a job planning lines, and indicate at that time the quantity of the item, resource, or general ledger account that you want to invoice.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-120">You can create an invoice from a job planning lines, and indicate at that time the quantity of the item, resource, or general ledger account that you want to invoice.</span></span>

1. <span data-ttu-id="9ef5f-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-121">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>
2. <span data-ttu-id="9ef5f-122">Open a relevant job.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-122">Open a relevant job.</span></span>
3. <span data-ttu-id="9ef5f-123">Select a job task for which the **Job Task Type** field contains **Posting**, and then choose the **Job Planning Lines** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-123">Select a job task for which the **Job Task Type** field contains **Posting**, and then choose the **Job Planning Lines** action.</span></span>  
4. <span data-ttu-id="9ef5f-124">On a job planning line, in the **Qty. To Transfer to Invoice** field, enter the quantity of the item, resource, general ledger account type that you want to invoice.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-124">On a job planning line, in the **Qty. To Transfer to Invoice** field, enter the quantity of the item, resource, general ledger account type that you want to invoice.</span></span>  
5. <span data-ttu-id="9ef5f-125">Choose the **Create Sales Invoice** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-125">Choose the **Create Sales Invoice** action.</span></span>
6. <span data-ttu-id="9ef5f-126">In the **Job Create Sales Invoice** window, enter the posting date and whether you want to create a new invoice or append this invoice to an existing one.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-126">In the **Job Create Sales Invoice** window, enter the posting date and whether you want to create a new invoice or append this invoice to an existing one.</span></span>
7. <span data-ttu-id="9ef5f-127">Choose the **OK** button.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-127">Choose the **OK** button.</span></span>

    <span data-ttu-id="9ef5f-128">On the job planning line, in the **Qty. Transferred to Invoice** field, you can see the quantity.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-128">On the job planning line, in the **Qty. Transferred to Invoice** field, you can see the quantity.</span></span>

8. <span data-ttu-id="9ef5f-129">In the **Job Planning Lines** window, choose the **Sales Invoices/Credit Memos** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-129">In the **Job Planning Lines** window, choose the **Sales Invoices/Credit Memos** action.</span></span>

    <span data-ttu-id="9ef5f-130">The **Sales Invoice** window opens, showing the quantity that you have transferred to the invoice.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-130">The **Sales Invoice** window opens, showing the quantity that you have transferred to the invoice.</span></span>  
9. <span data-ttu-id="9ef5f-131">Make any additional changes, and then choose the **Post** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-131">Make any additional changes, and then choose the **Post** action.</span></span>

<span data-ttu-id="9ef5f-132">**Note**: The above procedure is similar for creating, reviewing, and posting a job-related sales credit memo.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-132">**Note**: The above procedure is similar for creating, reviewing, and posting a job-related sales credit memo.</span></span>

## <a name="to-calculate-and-post-job-completion-entries"></a><span data-ttu-id="9ef5f-133">To calculate and post job completion entries</span><span class="sxs-lookup"><span data-stu-id="9ef5f-133">To calculate and post job completion entries</span></span>  
<span data-ttu-id="9ef5f-134">When you have completed all activities for a job, including usage posting and invoicing, you must update the job to have a **Status** of **Completed**.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-134">When you have completed all activities for a job, including usage posting and invoicing, you must update the job to have a **Status** of **Completed**.</span></span> <span data-ttu-id="9ef5f-135">Then, you must reverse any WIP that has been posted to the general ledger.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-135">Then, you must reverse any WIP that has been posted to the general ledger.</span></span>

1. <span data-ttu-id="9ef5f-136">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-136">In the top right corner, choose the **Search for Page or Report** icon, enter **Jobs**, and then choose the related link.</span></span>  
2. <span data-ttu-id="9ef5f-137">Select an open job, and then choose the **Edit** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-137">Select an open job, and then choose the **Edit** action.</span></span>
3. <span data-ttu-id="9ef5f-138">In the **Status** field, select **Completed**.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-138">In the **Status** field, select **Completed**.</span></span>
4. <span data-ttu-id="9ef5f-139">Follow the assistance steps to calculate and post WIP.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-139">Follow the assistance steps to calculate and post WIP.</span></span> <span data-ttu-id="9ef5f-140">Alternatively, follows steps 5 and 6 to do so manually.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-140">Alternatively, follows steps 5 and 6 to do so manually.</span></span>  
5. <span data-ttu-id="9ef5f-141">Choose the **Calculate WIP** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-141">Choose the **Calculate WIP** action.</span></span>
6. <span data-ttu-id="9ef5f-142">In the **Job Calculate WIP** window, fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-142">In the **Job Calculate WIP** window, fill in the fields as necessary.</span></span>  

     <span data-ttu-id="9ef5f-143">The job WIP entries created by running the batch job will have the **Job Complete** check box selected to show that they are completion entries.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-143">The job WIP entries created by running the batch job will have the **Job Complete** check box selected to show that they are completion entries.</span></span>  

7. <span data-ttu-id="9ef5f-144">Choose the **Job Post WIP to G/L** action.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-144">Choose the **Job Post WIP to G/L** action.</span></span>
8. <span data-ttu-id="9ef5f-145">In the **Job Post WIP to G/L** window, fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-145">In the **Job Post WIP to G/L** window, fill in the fields as necessary.</span></span>  

     <span data-ttu-id="9ef5f-146">The job WIP general ledger entries created by running the batch job will have the **Job Complete** check box selected to show they are completion entries.</span><span class="sxs-lookup"><span data-stu-id="9ef5f-146">The job WIP general ledger entries created by running the batch job will have the **Job Complete** check box selected to show they are completion entries.</span></span>

## <a name="see-also"></a><span data-ttu-id="9ef5f-147">See Also</span><span class="sxs-lookup"><span data-stu-id="9ef5f-147">See Also</span></span>
[<span data-ttu-id="9ef5f-148">Manage Projects</span><span class="sxs-lookup"><span data-stu-id="9ef5f-148">Manage Projects</span></span>](projects-manage-projects.md)  
[<span data-ttu-id="9ef5f-149">Finance</span><span class="sxs-lookup"><span data-stu-id="9ef5f-149">Finance</span></span>](finance-setup.md)  
<span data-ttu-id="9ef5f-150">[Manage Purchasing](purchasing-manage-purchasing.md)       </span><span class="sxs-lookup"><span data-stu-id="9ef5f-150">[Manage Purchasing](purchasing-manage-purchasing.md)       </span></span>  
<span data-ttu-id="9ef5f-151">[Manage Sales](sales-manage-sales.md)    </span><span class="sxs-lookup"><span data-stu-id="9ef5f-151">[Manage Sales](sales-manage-sales.md)    </span></span>  
[<span data-ttu-id="9ef5f-152">Work With Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="9ef5f-152">Work With Dynamics NAV</span></span>](ui-work-product.md)  

