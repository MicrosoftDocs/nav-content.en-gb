---
title: Sales and Inventory Forecast
author: edupont04
ms.custom: na
ms.date: 09/23/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms-prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 765527ed4f4800acec20f0abbd4374e95c9c36dc
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="sales-and-inventory-forecast-for-dynamics-nav"></a>Sales and Inventory Forecast for Dynamics NAV
Inventory management is a trade-off between customer service and managing your cost. On one hand, a low inventory requires less working capital, but, on the other hand, stock-outs potentially lead to missed sales. The Sales and Inventory Forecast extension predicts potential sales using historical data and gives a clear overview of expected stock-outs. Based on the forecast, the extension helps create replenishment requests to your vendors and saves you time.  

## <a name="setting-up-forecasting"></a>Setting up forecasting
In Dynamics NAV, you must set up the connection to Azure Machine Learning (Azure ML). For more information, see [How to: Register Dynamics NAV in the Azure Management Portal](ui-how-register-dynamics-nav-azure.md). Once you have established the connection, you can configure the forecast to use a different type of period to report by, such as changing from forecasting by month to forecasting by quarter. You can also choose the number of periods to calculate the forecast by, depending on how granular you want the forecast to be. We suggest that you forecast by month and with a 12 month horizon for the forecast.  

## <a name="using-the-forecasts"></a>Using the forecasts
The extension uses Azure ML capabilities to predict future sales based on your sales history to help you avoid inventory shortage. For example, when you choose an item in the **Items** window, the chart in the **Item Forecast** pane shows the estimated sales of this item in the coming period. This way you can see if you are likely to run out of stock of the item soon.  

You can also use the extension to suggest when to stock up on inventory. For example, if you crate a purchase order for Fabrikam because you want to buy their new desk chair, the Sales and Inventory Forecast extension will suggest that you also restock on the LONDON swivel chair that you usually buy from this vendor. This is because the extension forecasts that you will run out of stock of the LONDON swivel chair in the coming two months, so you might want to order more chairs already now.  

## <a name="see-also"></a>See Also
[Manage Sales](sales-manage-sales.md)  
[Manage Inventory](inventory-manage-inventory.md)  
[Customizing Dynamics NAV Using Extensions](ui-extensions.md)  
[How to: Register Dynamics NAV in the Azure Management Portal](ui-how-register-dynamics-nav-azure.md)  

