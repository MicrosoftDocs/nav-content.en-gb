---
title: Workflow
description: You can set up and use workflows that connect business-process tasks performed by different users. System tasks, such as automatic posting, can be included as steps in workflows, preceded or followed by user tasks. Requesting and granting approval to create new records are typical workflow steps.
documentationcenter: 
author: SorenGP
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 07/01/2017
ms.author: sgroespe
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: e1efc43df4e0676c8c8bd704c58458ab9398cbe1
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="workflow"></a><span data-ttu-id="eceac-105">Workflow</span><span class="sxs-lookup"><span data-stu-id="eceac-105">Workflow</span></span>
<span data-ttu-id="eceac-106">You can set up and use workflows that connect business-process tasks performed by different users.</span><span class="sxs-lookup"><span data-stu-id="eceac-106">You can set up and use workflows that connect business-process tasks performed by different users.</span></span> <span data-ttu-id="eceac-107">System tasks, such as automatic posting, can be included as steps in workflows, preceded or followed by user tasks.</span><span class="sxs-lookup"><span data-stu-id="eceac-107">System tasks, such as automatic posting, can be included as steps in workflows, preceded or followed by user tasks.</span></span> <span data-ttu-id="eceac-108">Requesting and granting approval to create new records are typical workflow steps.</span><span class="sxs-lookup"><span data-stu-id="eceac-108">Requesting and granting approval to create new records are typical workflow steps.</span></span>  

 <span data-ttu-id="eceac-109">In the **Workflow** window, you create a workflow by listing the involved steps on the lines.</span><span class="sxs-lookup"><span data-stu-id="eceac-109">In the **Workflow** window, you create a workflow by listing the involved steps on the lines.</span></span> <span data-ttu-id="eceac-110">Each step consists of a workflow event, moderated by event conditions, and a workflow response, moderated by response options.</span><span class="sxs-lookup"><span data-stu-id="eceac-110">Each step consists of a workflow event, moderated by event conditions, and a workflow response, moderated by response options.</span></span> <span data-ttu-id="eceac-111">You define workflow steps by filling fields on workflow lines from fixed lists of event and response values representing scenarios that are supported by the application code.</span><span class="sxs-lookup"><span data-stu-id="eceac-111">You define workflow steps by filling fields on workflow lines from fixed lists of event and response values representing scenarios that are supported by the application code.</span></span>  

 <span data-ttu-id="eceac-112">The generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)] includes a number of preconfigured workflows represented by workflow templates that you can copy to create workflows.</span><span class="sxs-lookup"><span data-stu-id="eceac-112">The generic version of [!INCLUDE[d365fin](includes/d365fin_md.md)] includes a number of preconfigured workflows represented by workflow templates that you can copy to create workflows.</span></span> <span data-ttu-id="eceac-113">The code for workflow templates that are added by Microsoft are prefixed with “MS-“.</span><span class="sxs-lookup"><span data-stu-id="eceac-113">The code for workflow templates that are added by Microsoft are prefixed with “MS-“.</span></span> <span data-ttu-id="eceac-114">For more information, see the list of workflow templates in the Workflow Templates window.</span><span class="sxs-lookup"><span data-stu-id="eceac-114">For more information, see the list of workflow templates in the Workflow Templates window.</span></span>  

 <span data-ttu-id="eceac-115">If a business scenario requires a workflow event or response that is not supported, a Microsoft partner must implement them by customising the application code.</span><span class="sxs-lookup"><span data-stu-id="eceac-115">If a business scenario requires a workflow event or response that is not supported, a Microsoft partner must implement them by customizing the application code.</span></span> <span data-ttu-id="eceac-116">For more information, see [Walkthrough: Implementing New Workflow Events and Responses](https://msdn.microsoft.com/en-us/library/mt574349.aspx) on MSDN.</span><span class="sxs-lookup"><span data-stu-id="eceac-116">For more information, see [Walkthrough: Implementing New Workflow Events and Responses](https://msdn.microsoft.com/en-us/library/mt574349.aspx) on MSDN.</span></span>  

 <span data-ttu-id="eceac-117">The following table describes a sequence of tasks, with links to the topics that describe them.</span><span class="sxs-lookup"><span data-stu-id="eceac-117">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>  

|<span data-ttu-id="eceac-118">**To**</span><span class="sxs-lookup"><span data-stu-id="eceac-118">**To**</span></span>|<span data-ttu-id="eceac-119">**See**</span><span class="sxs-lookup"><span data-stu-id="eceac-119">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="eceac-120">Set up workflow users, specify how users get notified, and create new workflows.</span><span class="sxs-lookup"><span data-stu-id="eceac-120">Set up workflow users, specify how users get notified, and create new workflows.</span></span> <span data-ttu-id="eceac-121">For new workflows for unsupported scenarios, implement the required workflow elements by customising the application code.</span><span class="sxs-lookup"><span data-stu-id="eceac-121">For new workflows for unsupported scenarios, implement the required workflow elements by customizing the application code.</span></span>|[<span data-ttu-id="eceac-122">Setting Up Workflows</span><span class="sxs-lookup"><span data-stu-id="eceac-122">Setting Up Workflows</span></span>](across-set-up-workflows.md)|  
|<span data-ttu-id="eceac-123">Enable workflows, act on workflow notifications, including request approvals and approve requests to perform a workflow step.</span><span class="sxs-lookup"><span data-stu-id="eceac-123">Enable workflows, act on workflow notifications, including request approvals and approve requests to perform a workflow step.</span></span> <span data-ttu-id="eceac-124">Archive and delete workflows.</span><span class="sxs-lookup"><span data-stu-id="eceac-124">Archive and delete workflows.</span></span>|[<span data-ttu-id="eceac-125">Using Workflows</span><span class="sxs-lookup"><span data-stu-id="eceac-125">Using Workflows</span></span>](across-use-workflows.md)|  

## <a name="see-also"></a><span data-ttu-id="eceac-126">See Also</span><span class="sxs-lookup"><span data-stu-id="eceac-126">See Also</span></span>  
[<span data-ttu-id="eceac-127">Sales</span><span class="sxs-lookup"><span data-stu-id="eceac-127">Sales</span></span>](sales-manage-sales.md)  
[<span data-ttu-id="eceac-128">Purchasing</span><span class="sxs-lookup"><span data-stu-id="eceac-128">Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="eceac-129">Managing Projects</span><span class="sxs-lookup"><span data-stu-id="eceac-129">Managing Projects</span></span>](projects-manage-projects.md)  
<span data-ttu-id="eceac-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="eceac-130">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>

