---
title: Problembehandlung für SSPR
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 03/04/2021
ms.topic: article
ms.audience: Admin
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003259"
- "6128"
ms.openlocfilehash: 85bfc812dcffce008a6fa5394a6069bd64c514d6
ms.sourcegitcommit: f4ba304b92ed01e35273ecda67e9dc3ad9d475c1
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/04/2021
ms.locfileid: "50428693"
---
# <a name="troubleshoot-sspr"></a><span data-ttu-id="d41f3-102">Problembehandlung für SSPR</span><span class="sxs-lookup"><span data-stu-id="d41f3-102">Troubleshoot SSPR</span></span>

<span data-ttu-id="d41f3-103">**Probleme beim Konfigurieren der Kennwortzurücksetzung**</span><span class="sxs-lookup"><span data-stu-id="d41f3-103">**I'm having trouble configuring password reset**</span></span>

- <span data-ttu-id="d41f3-104">Wenn Sie Administrator sind und suchen, wie Sie die Self-Service-Kennwortzurücksetzung aktivieren möchten, lesen Sie Lernprogramm aktivieren [SSPR](https://docs.microsoft.com/azure/active-directory/authentication/tutorial-enable-sspr), um die Kennwortzurücksetzung für Ihre Organisation zu konfigurieren.</span><span class="sxs-lookup"><span data-stu-id="d41f3-104">If you are administrator and looking for how to enable self-service password reset, see [Tutorial enable SSPR](https://docs.microsoft.com/azure/active-directory/authentication/tutorial-enable-sspr), to configure password reset for your organization.</span></span> <span data-ttu-id="d41f3-105">Möglicherweise möchten Sie auch die [Lizenzierungsanforderungen überprüfen.](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-licensing?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="d41f3-105">You may also want to review the [licensing requirements](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-licensing?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span> <span data-ttu-id="d41f3-106">In Ihrer Organisation muss mindestens eine Lizenz zugewiesen sein.</span><span class="sxs-lookup"><span data-stu-id="d41f3-106">You must have at least one license assigned in your organization.</span></span>
    - <span data-ttu-id="d41f3-107">**Nur Cloudbenutzer** – Office 365 (O365) kostenpflichtige SKU oder Azure AD Basic</span><span class="sxs-lookup"><span data-stu-id="d41f3-107">**Cloud only users** - Any Office 365 (O365) paid SKU, or Azure AD Basic</span></span>
    - <span data-ttu-id="d41f3-108">**Cloud- und/oder lokale Benutzer** – Azure AD Premium P1 oder P2, Enterprise Mobility + Security (EMS) oder Secure Productive Enterprise (SPE)</span><span class="sxs-lookup"><span data-stu-id="d41f3-108">**Cloud and/or on-premises users** - Azure AD Premium P1 or P2, Enterprise Mobility + Security (EMS), or Secure Productive Enterprise (SPE)</span></span>
- <span data-ttu-id="d41f3-109">Weitere Fragen zur Self-Service-Kennwortzurücksetzung finden Sie [in den häufig gestellten Fragen](https://docs.microsoft.com/azure/active-directory/authentication/active-directory-passwords-faq?WT.mc_id=Portal-Microsoft_Azure_Support).</span><span class="sxs-lookup"><span data-stu-id="d41f3-109">For additional questions about self-service password reset, review [our FAQ](https://docs.microsoft.com/azure/active-directory/authentication/active-directory-passwords-faq?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>

<span data-ttu-id="d41f3-110">**Ich bekommt eine Fehlermeldung**</span><span class="sxs-lookup"><span data-stu-id="d41f3-110">**I'm getting an error message**</span></span>

<span data-ttu-id="d41f3-111">Lesen Sie diesen Artikel, um häufige Fehler und deren Lösungen zu finden: Problembehandlung bei der [Self-Service-Kennwortzurücksetzung](https://docs.microsoft.com/azure/active-directory/authentication/active-directory-passwords-troubleshoot?WT.mc_id=Portal-Microsoft_Azure_Support)</span><span class="sxs-lookup"><span data-stu-id="d41f3-111">Review this article to find common errors and their solutions: [Troubleshoot self-service password reset](https://docs.microsoft.com/azure/active-directory/authentication/active-directory-passwords-troubleshoot?WT.mc_id=Portal-Microsoft_Azure_Support)</span></span>

<span data-ttu-id="d41f3-112">**Ich habe ein Problem mit meiner Kennwortzurücksetzungsrichtlinie**</span><span class="sxs-lookup"><span data-stu-id="d41f3-112">**I'm having a problem with my password reset policy**</span></span>

- <span data-ttu-id="d41f3-113">Wenn Ihre Kennwortzurücksetzungsrichtlinie nicht wie erwartet ausgeführt wird oder Wenn Sie Fragen zu Kennwortzurücksetzungsrichtlinien haben, lesen Sie diesen Artikel: [Kennwortrichtlinien](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support)und Einschränkungen in Azure Active Directory .</span><span class="sxs-lookup"><span data-stu-id="d41f3-113">If your password reset policy is not behaving as expected, or if you have questions about password reset policies, review this article: [Password policies and restrictions in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support).</span></span>
- <span data-ttu-id="d41f3-114">Richtlinien für die Kennwortzurücksetzung gelten nicht für Administratoren.</span><span class="sxs-lookup"><span data-stu-id="d41f3-114">Password reset policies do not apply to administrators.</span></span> <span data-ttu-id="d41f3-115">Microsoft erzwingt eine starke standardmäßige Zwei-Tore-Kennwortzurücksetzungsrichtlinie für alle Azure-Administratorrolle.</span><span class="sxs-lookup"><span data-stu-id="d41f3-115">Microsoft enforces a strong default two-gate password reset policy for any Azure administrator role.</span></span> <span data-ttu-id="d41f3-116">Stellen Sie sicher, dass Sie mit einem Benutzer testen, der kein Administrator ist.</span><span class="sxs-lookup"><span data-stu-id="d41f3-116">Make sure that you are testing with a user who is not an administrator.</span></span> <span data-ttu-id="d41f3-117">Weitere Informationen zur Administratorzurücksetzungsrichtlinie finden Sie in diesem Artikel: Unterschiede zwischen [den Richtlinien für die Administratorzurücksetzung](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#administrator-reset-policy-differences).</span><span class="sxs-lookup"><span data-stu-id="d41f3-117">For more information on the administrator reset policy, see this article: [Administrator reset policy differences](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy?WT.mc_id=Portal-Microsoft_Azure_Support#administrator-reset-policy-differences).</span></span>

<span data-ttu-id="d41f3-118">**Ich möchte nicht, dass meine Benutzer zusätzliche Sicherheitsinformationen für die Kennwortzurücksetzung registrieren.**</span><span class="sxs-lookup"><span data-stu-id="d41f3-118">**I don't want my users to register additional security info for password reset**</span></span>

<span data-ttu-id="d41f3-119">Sie können Daten (E-Mail- und Telefonattribute) für Ihre Benutzer vorab mithilfe einer API, PowerShell oder Azure AD Connect auffüllen.</span><span class="sxs-lookup"><span data-stu-id="d41f3-119">You can pre-populate data (email and phone attributes) for your users using an API, PowerShell, or Azure AD Connect.</span></span> <span data-ttu-id="d41f3-120">So erfahren Sie, wie Sie lesen:</span><span class="sxs-lookup"><span data-stu-id="d41f3-120">To learn how read:</span></span>

- [<span data-ttu-id="d41f3-121">Bereitstellen der Kennwortzurücksetzung, ohne dass Benutzer sich registrieren müssen</span><span class="sxs-lookup"><span data-stu-id="d41f3-121">Deploying password reset without requiring users to register</span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-data?WT.mc_id=Portal-Microsoft_Azure_Support#set-and-read-authentication-data-using-powershell)
- [<span data-ttu-id="d41f3-122">Welche Daten bei der Kennwortzurücksetzung verwendet werden</span><span class="sxs-lookup"><span data-stu-id="d41f3-122">What data is used by password reset</span></span>](https://docs.microsoft.com/azure/active-directory/active-directory-passwords-data?WT.mc_id=Portal-Microsoft_Azure_Support)

<span data-ttu-id="d41f3-123">**Ich möchte, dass meine Benutzer ihre zusätzlichen Sicherheitsinformationen für die Kennwortzurücksetzung registrieren.**</span><span class="sxs-lookup"><span data-stu-id="d41f3-123">**I want my users to register their additional security info for password reset**</span></span>

1. <span data-ttu-id="d41f3-124">Lassen Sie Ihre Benutzer ihre Sicherheitsinformationen für die Self-Service-Kennwortzurücksetzung registrieren, indem sie sie [an](https://mysignins.microsoft.com/security-info)aka.ms/ssprsetup.</span><span class="sxs-lookup"><span data-stu-id="d41f3-124">Have your users register their security info for self service password reset by directing them to [aka.ms/ssprsetup](https://mysignins.microsoft.com/security-info).</span></span>
1. <span data-ttu-id="d41f3-125">Nachdem Daten für den Benutzer (vom Benutzer oder vom Administrator) aufgefüllt wurden, müssen Sie den Benutzer an aka.ms/sspr damit Ihre Benutzer ihre eigenen Kennwörter zurücksetzen können. [](https://passwordreset.microsoftonline.com/)</span><span class="sxs-lookup"><span data-stu-id="d41f3-125">After data is populated for the user (by the user or by the admin), direct your user to [aka.ms/sspr](https://passwordreset.microsoftonline.com/) so your users can be empowered to reset their own passwords.</span></span>
1. <span data-ttu-id="d41f3-126">Wenn Benutzer weiterhin Probleme haben, handelt es sich höchstwahrscheinlich um **Synchronisierte** Benutzer mit Verbund- oder **Kennworthash.**</span><span class="sxs-lookup"><span data-stu-id="d41f3-126">If users are still experiencing problems they are most likely **federated** or **password hash synched** users.</span></span> <span data-ttu-id="d41f3-127">Dies bedeutet, dass es wahrscheinlich ein Problem mit dem Kennwortrückschreibendienst gibt.</span><span class="sxs-lookup"><span data-stu-id="d41f3-127">This means there is likely a problem with the Password Writeback service.</span></span>