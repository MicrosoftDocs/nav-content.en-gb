---
title: Multiple Interest Rates Overview
description: For each finance charge term code, you can specify multiple interest rates so that you can calculate finance charges with multiple interest rates for a specific period. This is helpful if you charge different interest on payments that are late. The interest calculation is the same for each financial charge, with variation only in the rate of interest for a specific period.
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
ms.openlocfilehash: c2244a1adda1dd4e1140e94cc0d0c3a6b0831e42
ms.contentlocale: en-gb
ms.lasthandoff: 10/16/2017

---
# <a name="multiple-interest-rates-overview"></a>Multiple Interest Rates Overview
For each finance charge term code, you can specify multiple interest rates so that you can calculate finance charges with multiple interest rates for a specific period. This is helpful if you charge different interest on payments that are late. The interest calculation is the same for each financial charge, with variation only in the rate of interest for a specific period.  

## <a name="creating-finance-charges"></a>Creating Finance Charges  
 When you create a finance charge memo, the memo lines show the finance charges with different interest rates for each time period. For finance charge terms, you can define descriptions for each term, and you can define a description that is used when multiple interest rates are used.  

 To use multiple interest rates, you must first define a finance charge term, and you must then add multiple interest rate lines to the terms. For more information, see [How to: Set Up Multiple Interest Rates](how-to-set-up-multiple-interest-rates.md).  

 If no multiple interest rates exist, [!INCLUDE[navnow](../../includes/navnow_md.md)] will use the interest rate and period that is defined in the **Finance Charge Terms** window for the whole period of calculation.  

## <a name="delayed-payments"></a>Delayed Payments  
 Multiple interest rates are used for different periods for delayed payments in trade transactions. For example, a government specifies the maximum interest to be levied for a consumer. This interest rate can be changed twice a year on 01 January and 01 July. The interest rate between businesses (B2B) is agreed by the parties and there is no limit to that customer group. The announced rate is usually four percent more than the normal bank interest.  

## <a name="see-also"></a>See Also  
[United Kingdom Local Functionality](united-kingdom-local-functionality.md)  
 [How to: Set Up Multiple Interest Rates](how-to-set-up-multiple-interest-rates.md)   
 [How to: Collect Outstanding balances](../../receivables-collect-outstanding-balances.md)

