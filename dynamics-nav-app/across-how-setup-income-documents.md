---
title: 'How to: Set Up Incoming Documents'
author: SorenGP
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 6b60b1344a1e18ad91863046110df880f75f7c04
ms.openlocfilehash: d55329b571e4c59d4821a86a39362ea58480b86a
ms.contentlocale: en-gb
ms.lasthandoff: 07/19/2017

---

# <a name="how-to-set-up-incoming-documents"></a><span data-ttu-id="69f77-102">How to: Set Up Incoming Documents</span><span class="sxs-lookup"><span data-stu-id="69f77-102">How to: Set Up Incoming Documents</span></span>
<span data-ttu-id="69f77-103">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span><span class="sxs-lookup"><span data-stu-id="69f77-103">If you create general journal lines from incoming document records, you must specify in the **Incoming Documents Setup** window which journal template and batch to use.</span></span>

<span data-ttu-id="69f77-104">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span><span class="sxs-lookup"><span data-stu-id="69f77-104">If you do not want users to create invoices or general journal lines from incoming document records unless the documents are first approved, you must set up approvers in the **Incoming Document Approvers** window.</span></span>

<span data-ttu-id="69f77-105">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.</span><span class="sxs-lookup"><span data-stu-id="69f77-105">To turn PDF and image files into electronic documents that you can convert to, for example, purchase invoices inside Dynamics NAV, you must first set up the OCR feature and enable the service.</span></span>

<span data-ttu-id="69f77-106">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span><span class="sxs-lookup"><span data-stu-id="69f77-106">When the Incoming Documents feature is set up, you can use different functions to review expense receipts, manage OCR tasks, and convert incoming document files, manually or automatically, to the relevant documents or journal lines.</span></span> <span data-ttu-id="69f77-107">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span><span class="sxs-lookup"><span data-stu-id="69f77-107">The external files can be attached at any process stage, including to posted documents and to the resulting vendor, customer, and general ledger entries.</span></span> <span data-ttu-id="69f77-108">For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).</span><span class="sxs-lookup"><span data-stu-id="69f77-108">For more information, see [How to: Process Incoming Documents](across-process-income-documents.md).</span></span>

## <a name="to-set-up-the-incoming-documents-feature"></a><span data-ttu-id="69f77-109">To set up the Incoming Documents feature</span><span class="sxs-lookup"><span data-stu-id="69f77-109">To set up the Incoming Documents feature</span></span>
1. <span data-ttu-id="69f77-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="69f77-110">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="69f77-111">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="69f77-111">Fill in the fields as necessary.</span></span> <span data-ttu-id="69f77-112">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="69f77-112">Choose a field to read a short description of the field or link to more information.</span></span>

## <a name="to-set-up-approvers-of-incoming-document-records"></a><span data-ttu-id="69f77-113">To set up approvers of incoming document records</span><span class="sxs-lookup"><span data-stu-id="69f77-113">To set up approvers of incoming document records</span></span>
1. <span data-ttu-id="69f77-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="69f77-114">In the top right corner, choose the **Search for Page or Report** icon, enter **Incoming Document Setup**, and then choose the related link.</span></span>  
2. <span data-ttu-id="69f77-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span><span class="sxs-lookup"><span data-stu-id="69f77-115">In the **Incoming Documents Setup** window, choose the **Approvers** action.</span></span>

    <span data-ttu-id="69f77-116">The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .</span><span class="sxs-lookup"><span data-stu-id="69f77-116">The **Incoming Document Approvers** window shows all users that are set up in your Dynamics NAV .</span></span>  
3. <span data-ttu-id="69f77-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span><span class="sxs-lookup"><span data-stu-id="69f77-117">Select one or more users that can approve an incoming document before a related document or journal line can be created.</span></span>

<span data-ttu-id="69f77-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span><span class="sxs-lookup"><span data-stu-id="69f77-118">When approvers have been set up in the **Incoming Document Approvers** window, only those users can approve an incoming document if the **Require Approval To Create** check box in the **Incoming Documents Setup** window is selected.</span></span>

<span data-ttu-id="69f77-119">**Note**: This approval setup is not related to approval workflows.</span><span class="sxs-lookup"><span data-stu-id="69f77-119">**Note**: This approval setup is not related to approval workflows.</span></span> <span data-ttu-id="69f77-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span><span class="sxs-lookup"><span data-stu-id="69f77-120">For more information, see [How to: Use Approval Workflows](across-how-use-approval-workflows.md).</span></span>

## <a name="to-set-up-an-ocr-service"></a><span data-ttu-id="69f77-121">To set up an OCR service</span><span class="sxs-lookup"><span data-stu-id="69f77-121">To set up an OCR service</span></span>
1. <span data-ttu-id="69f77-122">In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.</span><span class="sxs-lookup"><span data-stu-id="69f77-122">In the top right corner, choose the **Search for Page or Report** icon, enter **OCR Service Setup**, and then choose the related link.</span></span>
2. <span data-ttu-id="69f77-123">Fill in the fields as necessary.</span><span class="sxs-lookup"><span data-stu-id="69f77-123">Fill in the fields as necessary.</span></span> <span data-ttu-id="69f77-124">Choose a field to read a short description of the field or link to more information.</span><span class="sxs-lookup"><span data-stu-id="69f77-124">Choose a field to read a short description of the field or link to more information.</span></span>


## <a name="to-encrypt-your-login-information"></a><span data-ttu-id="69f77-125">To encrypt your login information</span><span class="sxs-lookup"><span data-stu-id="69f77-125">To encrypt your login information</span></span>
<span data-ttu-id="69f77-126">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span><span class="sxs-lookup"><span data-stu-id="69f77-126">It is recommended that you protect the logon information that you enter in the **OCR Service Setup** window.</span></span> <span data-ttu-id="69f77-127">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span><span class="sxs-lookup"><span data-stu-id="69f77-127">You can encrypt data on the server by generating new or importing existing encryption keys that you enable on the server instance that connects to the database.</span></span>

1. <span data-ttu-id="69f77-128">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span><span class="sxs-lookup"><span data-stu-id="69f77-128">In the **OCR Service Setup** window, choose the **Encryption Management** action.</span></span>
2. <span data-ttu-id="69f77-129">In the **Data Encryption Management** window, enable encryption of your data.</span><span class="sxs-lookup"><span data-stu-id="69f77-129">In the **Data Encryption Management** window, enable encryption of your data.</span></span>

## <a name="see-also"></a><span data-ttu-id="69f77-130">See Also</span><span class="sxs-lookup"><span data-stu-id="69f77-130">See Also</span></span>  
[<span data-ttu-id="69f77-131">Process Incoming Documents</span><span class="sxs-lookup"><span data-stu-id="69f77-131">Process Incoming Documents</span></span>](across-process-income-documents.md)  
[<span data-ttu-id="69f77-132">Incoming Documents</span><span class="sxs-lookup"><span data-stu-id="69f77-132">Incoming Documents</span></span>](across-income-documents.md)  
[<span data-ttu-id="69f77-133">Manage Purchasing</span><span class="sxs-lookup"><span data-stu-id="69f77-133">Manage Purchasing</span></span>](purchasing-manage-purchasing.md)  
[<span data-ttu-id="69f77-134">Work With Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="69f77-134">Work With Dynamics NAV</span></span>](ui-work-product.md)

