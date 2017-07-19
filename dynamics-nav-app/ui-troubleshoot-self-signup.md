---
title: Troubleshooting Self-Service Sign-Up
author: SusanneWindfeldPedersen
ms.custom: na
ms.date: 09/22/2016
ms.reviewer: na
ms.suite: na
ms.tgt_pltfrm: na
ms.topic: article
ms.prod: dynamics-nav-2017
ms.translationtype: Human Translation
ms.sourcegitcommit: 51adfb3588099c496f0946ff71da5c6fe518f070
ms.openlocfilehash: 931c427518694cbd0003ea82735292a019b388d5
ms.contentlocale: en-gb
ms.lasthandoff: 06/26/2017

---

# <a name="troubleshooting-self-service-sign-up"></a>Troubleshooting Self-Service Sign-Up
Signing up for Dynamics NAV is easy and can be done very quickly. You can create a free account even if you are an existing organisation. This article addresses issues that you may have during signup.

## <a name="what-email-address-can-i-use-with-dynamics-nav"></a>What email address can I use with Dynamics NAV?
Dynamics NAV requires that you use a work, or school, email address to sign up. Dynamics NAV does not support email addresses provided by consumer email services or telecommunication providers. This includes outlook.com, hotmail.com, gmail.com, and others.

If you try to sign up with a personal email address, you will get a message indicating to use a work or school email address.

## <a name="troubleshooting"></a>Troubleshooting
In many cases, registering for Dynamics NAV can be achieved by following the sign-up process. However, there are several reasons why you may not be able to complete self-service signup. The table below summarizes some of the most common reasons you may not be able to complete signup and ways you can workaround these issues.

|Symptom/Error Message                                                                             |Cause and Workaround|
|--------------------------------------------------------------------------------------------------|--------------------|
|For Office 365 email addresses that are not registered in the US, you receive a message like the following during signup: <br>**That didn't work, we don't support your country or region yet.**<br> |Dynamics NAV currently only supports Office 365 US registered email accounts.|
|Personal email addresses such as nancy@gmail.com are not supported. You receive a message like the following during signup: <br>**You entered a personal email address: Please enter your work email address so we can securely store your company's data.**<br> or <br> **That looks like a personal email address. Enter your work address so we can connect you with others in your company. And don’t worry. We won’t share your address with anyone.** | Dynamics NAV does not support email addresses provided by consumer email services or telecommunications providers. To complete signup, try again using an email address assigned by your work or school. If you still cannot sign up and are willing to complete a more advanced setup process, you can register for a new Office 365 trial subscription and use that email address to sign up.
|.gov or .mil email addresses You receive a message like the following during signup: <br>**Dynamics NAV unavailable: Dynamics NAV is not available for users with .gov or .mil email addresses at this time. Use another work email address or check back later.** <br>or <br>**We can't finish signing you up. It looks like Dynamics NAV isn't currently available for your work or school.**|Dynamics NAV does not support .gov or .mil addresses at this time.|
|Self-service signup is not enabled. You receive a message like the following during signup: <br>**We can't finish signing you up. Your IT department has turned off signup for Dynamics NAV. Contact them to complete signup.** <br>or <br> **That looks like a personal email address. Enter your work address so we can connect you with others in your company. And don’t worry. We won’t share your address with anyone.**|Your organisation’s IT administrator has disabled self-service signup for Dynamics NAV. To complete signup, contact your IT administrator and ask them to follow the instructions on the page below to allow existing users to sign up for Dynamics NAV and to allow new users to join your existing tenant. You may also experience this problem if you signed up for Office 365 through a partner.|
|Email address is not an Office 365 ID. You receive a message like the following during signup: <br>**We can't find you at contoso.com. Do you use a different ID at work or school? Try signing in with that, and if it doesn't work, contact your IT department.**|Your organisation uses IDs to sign in to Office 365 and other Microsoft services that are different than your email address. For example, your email address might be Nancy.Smith@contoso.com but your ID is nancys@contoso.com. To complete signup, use the ID that your organisation has assigned to for signing in to Office 365 or other Microsoft services. If you do not know what this is, contact your IT administrator. If you still cannot sign up and are able to complete a more advanced setup process, you can register for a new Office 365 trial subscription and use that email address to sign up.|


## <a name="see-also"></a>See Also
[Welcome to Dynamics NAV](across-get-started.md)  
[Work With Dynamics NAV](ui-work-product.md)




