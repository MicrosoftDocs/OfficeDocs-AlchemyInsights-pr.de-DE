---
title: Probleme beim Erstellen von Live-Ereignissen in Yammer
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9002495"
- "5112"
ms.openlocfilehash: 35cddfee1a78fd6e1e502871bd5b56d786bf300a
ms.sourcegitcommit: fbaa2ce2cfb4d56d8c4cf2fa2d95489bdfcb7ff0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/30/2020
ms.locfileid: "43947829"
---
# <a name="live-events-in-yammer-creation-errors"></a><span data-ttu-id="c4aed-102">Probleme beim Erstellen von Live-Ereignissen in Yammer</span><span class="sxs-lookup"><span data-stu-id="c4aed-102">Live events in Yammer creation errors</span></span>

<span data-ttu-id="c4aed-103">**Erstellen von Live-Ereignissen in Yammer**</span><span class="sxs-lookup"><span data-stu-id="c4aed-103">**Yammer Live Event creation**</span></span>

<span data-ttu-id="c4aed-104">In Yammer wird jederzeit die Option zum Erstellen eines Live-Ereignisses angezeigt.</span><span class="sxs-lookup"><span data-stu-id="c4aed-104">Yammer will show the option to create a live event at all times.</span></span> <span data-ttu-id="c4aed-105">In einigen Fällen erfüllt ein Benutzer möglicherweise nicht die Voraussetzungen für die Erstellung eines Live-Ereignisses und erhält eine Fehlermeldung, wenn er versucht, ein Live-Ereignis zu erstellen.</span><span class="sxs-lookup"><span data-stu-id="c4aed-105">In some cases, a user may not meet the prerequisites for creating a live event and receive an error when they attempt to create it.</span></span> <span data-ttu-id="c4aed-106">Die folgenden Elemente behandeln häufige Ursachen für dieses Problem und bieten Möglichkeiten zur Behebung des Problems für Endbenutzer.</span><span class="sxs-lookup"><span data-stu-id="c4aed-106">The items below cover common reasons for this problem and provide ways to resolve it for end users.</span></span>

<span data-ttu-id="c4aed-107">**Wer kann Liveereignisse erstellen**</span><span class="sxs-lookup"><span data-stu-id="c4aed-107">**Who can create live events**</span></span>
- <span data-ttu-id="c4aed-108">Eine Lizenz für Office 365 Enterprise E1, E3 oder E5 oder eine Lizenz für Office 365 A3 oder A5.</span><span class="sxs-lookup"><span data-stu-id="c4aed-108">An Office 365 Enterprise E1, E3, or E5 license or an Office 365 A3 or A5 license.</span></span>
- <span data-ttu-id="c4aed-109">Die Berechtigung zum Erstellen von Live-Ereignissen im Microsoft Teams Admin Center.</span><span class="sxs-lookup"><span data-stu-id="c4aed-109">Permission to create live events in Microsoft Teams admin center.</span></span>
- <span data-ttu-id="c4aed-110">Die Berechtigung zum Erstellen von Live Ereignissen in Microsoft Stream (für Ereignisse, die mit einer externen Broadcasting-App oder einem externen Gerät erstellt wurden).</span><span class="sxs-lookup"><span data-stu-id="c4aed-110">Permission to create live events in Microsoft Stream (for events produced using an external broadcasting app or device).</span></span>
- <span data-ttu-id="c4aed-111">Vollständige Teammitgliedschaft in der Organisation (darf kann kein Gast oder jemand von einer anderen Organisation sein)</span><span class="sxs-lookup"><span data-stu-id="c4aed-111">Full team membership in the org (can’t be a guest or from another org).</span></span>
- <span data-ttu-id="c4aed-112">Planung von privaten Besprechungen, Screensharing und IP-Videofreigabe – in der Team-Besprechungsrichtlinie aktiviert.</span><span class="sxs-lookup"><span data-stu-id="c4aed-112">Private meeting scheduling, screensharing, and IP video sharing, turned on in Team meeting policy.</span></span>

<span data-ttu-id="c4aed-113">**Richtlinien zur Erstellung von Liveereignissen**</span><span class="sxs-lookup"><span data-stu-id="c4aed-113">**Live event creation policies**</span></span>

<span data-ttu-id="c4aed-114">Yammer folgt den Richtlinien für Live-Ereignisse, die in Ihrem Office 365-Mandanten für Stream festgelegt sind.</span><span class="sxs-lookup"><span data-stu-id="c4aed-114">Yammer follows the Live Event policies set in your Office 365 tenant for Stream.</span></span> <span data-ttu-id="c4aed-115">Standardmäßig kann jeder in Ihrer Organisation ein Live-Event erstellen.</span><span class="sxs-lookup"><span data-stu-id="c4aed-115">By default, everyone in your organization can create a live event.</span></span> <span data-ttu-id="c4aed-116">Administratoren können [möglicherweise Änderungen an dieser Einstellung vornehmen, wodurch Benutzer daran gehindert werden, ein Live Ereignis zu erstellen](https://docs.microsoft.com/stream/live-event-administration#enabling-and-restricting-users-to-creating).</span><span class="sxs-lookup"><span data-stu-id="c4aed-116">Administrators may [make changes to this setting which may prevent users from creating a live event](https://docs.microsoft.com/stream/live-event-administration#enabling-and-restricting-users-to-creating).</span></span> <span data-ttu-id="c4aed-117">Es ist wichtig, zu überprüfen, ob die Benutzer über die Berechtigung zum Erstellen von Live-Ereignissen verfügen, wenn sie einen Richtlinienfehler erhalten.</span><span class="sxs-lookup"><span data-stu-id="c4aed-117">It is important to check that users have permissions to create live events if they receive a policy error.</span></span>