---
title: Kalendersymbol wird im Teams-Client nicht angezeigt
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001219"
- "4375"
ms.openlocfilehash: 6a3f02b69d160c7dce68ed03df59c0d7d1f32f0f
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51819952"
---
# <a name="calendar-icon-not-showing-in-teams-client"></a><span data-ttu-id="02963-102">Kalendersymbol wird im Teams-Client nicht angezeigt</span><span class="sxs-lookup"><span data-stu-id="02963-102">Calendar icon not showing in Teams client</span></span>

<span data-ttu-id="02963-103">Die Registerkarte „Kalender“ in Teams muss über Exchange-Webdienste auf ein Exchange-Postfach zugreifen können.</span><span class="sxs-lookup"><span data-stu-id="02963-103">The Calendar Tab in Teams requires access to an Exchange mailbox via Exchange Web Services.</span></span> <span data-ttu-id="02963-104">Das Exchange-Postfach kann online oder lokal sein.</span><span class="sxs-lookup"><span data-stu-id="02963-104">The Exchange mailbox can be Online or On-Premises.</span></span> <span data-ttu-id="02963-105">Vergewissern Sie sich für Onlinebenutzer, für die die Registerkarte „Kalender“ nicht angezeigt wird, dass [ sie für ein Exchange Online-Postfach lizenziert sind und das Postfach aktiviert](https://docs.microsoft.com/exchange/recipients-in-exchange-online/create-user-mailboxes) ist.</span><span class="sxs-lookup"><span data-stu-id="02963-105">For Online users who do not see the Calendar Tab, make sure they [are licensed for an Exchange Online mailbox and the mailbox is enabled](https://docs.microsoft.com/exchange/recipients-in-exchange-online/create-user-mailboxes).</span></span>

<span data-ttu-id="02963-106">Wenn der Benutzer über ein gültiges Postfach in Exchange Online verfügt, die Registerkarte „Kalender“ aber immer noch nicht angezeigt wird, tritt möglicherweise ein Netzwerkproblem auf.</span><span class="sxs-lookup"><span data-stu-id="02963-106">If the user has a valid mailbox in Exchange Online, but still cannot see the Calendar tab, you may be experiencing a network issue.</span></span> <span data-ttu-id="02963-107">Verwenden Sie die [Microsoft-Remoteverbindungsuntersuchung](https://testconnectivity.microsoft.com/), und führen Sie die **Verbindungstests für Microsoft Exchange-Webdienste** für den betroffenen Benutzer durch.</span><span class="sxs-lookup"><span data-stu-id="02963-107">Use the [Microsoft Remote Connectivity Analyzer](https://testconnectivity.microsoft.com/) and run the **Microsoft Exchange Web Services Connectivity Tests** for the impacted user.</span></span>

<span data-ttu-id="02963-108">Überprüfen Sie schließlich die [Teams-Apps –-App-Setup-Richtlinien](https://admin.teams.microsoft.com/policies/app-setup), um sicherzustellen, dass die Kalender-App nicht aus der auf den Benutzer angewendeten Richtlinie entfernt wurde (höchstwahrscheinlich die globale Richtlinie (organisationsweiter Standard).</span><span class="sxs-lookup"><span data-stu-id="02963-108">Finally check the [Teams Apps – App setup policies](https://admin.teams.microsoft.com/policies/app-setup) to ensure the Calendar app has not been removed from the policy applied to the user (most likely the **Global (Org-wide default)**.</span></span>

<span data-ttu-id="02963-109">Wenn Ihre Benutzer lokal sind, müssen Sie sicherstellen, dass Ihre Hybridkonfiguration fehlerfrei ist.</span><span class="sxs-lookup"><span data-stu-id="02963-109">If your users are homed On-Premises, you need to confirm your Hybrid configuration is healthy.</span></span> <span data-ttu-id="02963-110">Verwenden Sie den [Assistenten für die Hybridkonfiguration](https://docs.microsoft.com/exchange/hybrid-deployment/hybrid-agent) zur Problembehandlung.</span><span class="sxs-lookup"><span data-stu-id="02963-110">Use the [Hybrid Configuration Wizard](https://docs.microsoft.com/exchange/hybrid-deployment/hybrid-agent) to troubleshoot.</span></span>

<span data-ttu-id="02963-111">Beachten Sie, dass für [Teams Exchange 2016 CU3 oder höher erforderlich ist](https://docs.microsoft.com/microsoftteams/exchange-teams-interact).</span><span class="sxs-lookup"><span data-stu-id="02963-111">Note that [Teams requires Exchange 2016 CU3 or higher](https://docs.microsoft.com/microsoftteams/exchange-teams-interact).</span></span>
