---
title: Richtlinien für bedingten Zugriff
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002357"
- "4583"
ms.openlocfilehash: 8ce41d007988f2a45f1ded385ae50ac3def97c1b
ms.sourcegitcommit: 9923ce61344e22c4490549b12f65fa2896490b1f
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/01/2020
ms.locfileid: "43100447"
---
# <a name="conditional-access-policies"></a><span data-ttu-id="08077-102">Richtlinien für bedingten Zugriff</span><span class="sxs-lookup"><span data-stu-id="08077-102">Conditional Access policies</span></span>

<span data-ttu-id="08077-103">Der bedingte Zugriff ist eine Funktion von Azure AD, die es Ihnen ermöglicht, eine Steuerung des Zugriffs auf Apps in Ihrer Umgebung zu erzwingen – basierend auf spezifischen Bedingungen und verwaltet von einem zentralen Ort aus.</span><span class="sxs-lookup"><span data-stu-id="08077-103">Conditional Access is a capability of Azure AD that enables you to enforce controls on the access to apps in your environment, all based on specific conditions and managed from a central location.</span></span>

<span data-ttu-id="08077-104">Erfahren Sie mehr über den [bedingten Zugriff mit Azure AD](https://docs.microsoft.com/azure/active-directory/conditional-access/).</span><span class="sxs-lookup"><span data-stu-id="08077-104">Learn more about [Azure AD Conditional Access](https://docs.microsoft.com/azure/active-directory/conditional-access/).</span></span>  

<span data-ttu-id="08077-105">**Hinweis**: Wenn Ihr Mandant nach dem 21. Oktober 2019 erstellt wurde und Sie unerwartete MFA-Aufforderungen erhalten, haben Sie wahrscheinlich [Sicherheitsstandards](http://aka.ms/securitydefaults) in Ihrem Mandanten aktiviert.</span><span class="sxs-lookup"><span data-stu-id="08077-105">**Note**: If your tenant was created after October 21st, 2019 and you're unexpectedly getting prompted for MFA, you likely have [security defaults](http://aka.ms/securitydefaults) enabled in your tenant.</span></span>

<span data-ttu-id="08077-106">**So verwalten Sie Sicherheitsstandards**</span><span class="sxs-lookup"><span data-stu-id="08077-106">**To Manage security defaults**</span></span>

1. <span data-ttu-id="08077-107">Melden Sie sich mit Ihren globalen Administratoranmeldeinformationen beim [Admin Center](https://go.microsoft.com/fwlink/p/?linkid=834822) an.</span><span class="sxs-lookup"><span data-stu-id="08077-107">Sign in to the [admin center](https://go.microsoft.com/fwlink/p/?linkid=834822) with your Global admin credentials.</span></span>

2. <span data-ttu-id="08077-108">Wechseln Sie zu [Azure Active Directory-Eigenschaften](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties).</span><span class="sxs-lookup"><span data-stu-id="08077-108">Go to [Azure Active Directory Properties](https://portal.azure.com/#blade/Microsoft_AAD_IAM/ActiveDirectoryMenuBlade/Properties).</span></span>

3. <span data-ttu-id="08077-109">Klicken Sie am unteren Rand der Seite auf **Sicherheitsstandards verwalten**.</span><span class="sxs-lookup"><span data-stu-id="08077-109">At the bottom of the page, click **Manage Security defaults**.</span></span>

4. <span data-ttu-id="08077-110">Klicken Sie auf **Ja**, um Sicherheitsstandards zu aktivieren, oder auf **Nein**, um Sicherheitsstandards zu deaktivieren.</span><span class="sxs-lookup"><span data-stu-id="08077-110">Click **Yes** to enable security defaults or **No** to disable security defaults.</span></span>