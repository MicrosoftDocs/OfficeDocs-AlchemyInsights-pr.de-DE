---
title: Zulassen oder Deaktivieren von IP-Video in Teams
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
- "9002537"
- "5617"
ms.openlocfilehash: 059d7a1ad619e25f14bc6f561693b6fe24355132
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51826342"
---
# <a name="teams-allow-or-disable-ip-video"></a><span data-ttu-id="8a817-102">Zulassen oder Deaktivieren von IP-Video in Teams</span><span class="sxs-lookup"><span data-stu-id="8a817-102">Teams allow or disable IP video</span></span>

<span data-ttu-id="8a817-103">**Ändern oder Erstellen einer Besprechungsrichtlinie**</span><span class="sxs-lookup"><span data-stu-id="8a817-103">**Change or create a meeting policy**</span></span>

<span data-ttu-id="8a817-104">Um eine Besprechungsrichtlinie zu ändern oder zu erstellen, wechseln Sie zu **Microsoft Teams Admin Center > Besprechungen > Besprechungsrichtlinien**.</span><span class="sxs-lookup"><span data-stu-id="8a817-104">To change or create a meeting policy, go to the **Microsoft Teams admin center > Meetings > Meeting policies**.</span></span> <span data-ttu-id="8a817-105">Wählen Sie in der Liste eine Richtlinie aus, oder klicken Sie auf **Hinzufügen**.</span><span class="sxs-lookup"><span data-stu-id="8a817-105">Select a policy from the list or click **Add**.</span></span> <span data-ttu-id="8a817-106">Wenn Sie eine neue Richtlinie erstellen, fügen Sie einen Namen und eine Beschreibung hinzu.</span><span class="sxs-lookup"><span data-stu-id="8a817-106">If you're creating a new policy, add a name and description.</span></span> <span data-ttu-id="8a817-107">Der Name darf keine Sonderzeichen enthalten und nicht mehr als 64 Zeichen lang sein.</span><span class="sxs-lookup"><span data-stu-id="8a817-107">The name can't contain special characters or be longer than 64 characters.</span></span> <span data-ttu-id="8a817-108">Wählen Sie die gewünschten Einstellungen aus, und klicken Sie dann auf **Speichern**.</span><span class="sxs-lookup"><span data-stu-id="8a817-108">Choose your settings, and then click **Save**.</span></span>

<span data-ttu-id="8a817-109">Nehmen wir beispielsweise an, Sie haben viele Benutzer, und Sie möchten die Bandbreite begrenzen, die für deren Besprechung erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="8a817-109">For example, say you have many users and you want to limit the amount of bandwidth that their meeting would require.</span></span> <span data-ttu-id="8a817-110">Sie erstellen dann eine neue benutzerdefinierte Richtlinie namens „begrenzte Bandbreite“ und deaktivieren die folgenden Einstellungen:</span><span class="sxs-lookup"><span data-stu-id="8a817-110">You would create a new custom policy named "Limited bandwidth" and disable the following settings:</span></span>

<span data-ttu-id="8a817-111">Unter **Audio & Video**:</span><span class="sxs-lookup"><span data-stu-id="8a817-111">Under **Audio & video**:</span></span>

- <span data-ttu-id="8a817-112">Deaktivieren Sie Cloud-Aufzeichnung zulassen.</span><span class="sxs-lookup"><span data-stu-id="8a817-112">Turn off Allow cloud recording.</span></span>
- <span data-ttu-id="8a817-113">Deaktivieren Sie IP-Video zulassen.</span><span class="sxs-lookup"><span data-stu-id="8a817-113">Turn off Allow IP video.</span></span>

<span data-ttu-id="8a817-114">Weisen Sie dann die Richtlinie den Nutzern zu.</span><span class="sxs-lookup"><span data-stu-id="8a817-114">Then assign the policy to the users.</span></span>

<span data-ttu-id="8a817-115">**Nutzern eine Besprechungsrichtlinie zuweisen**</span><span class="sxs-lookup"><span data-stu-id="8a817-115">**Assign a meeting policy to users**</span></span>

1. <span data-ttu-id="8a817-116">Wechseln Sie in der linken Navigation des Microsoft Teams Admin Centers zu **Nutzer**, und klicken Sie dann den gewünschten Nutzer an.</span><span class="sxs-lookup"><span data-stu-id="8a817-116">In the left navigation of the Microsoft Teams admin center, go to **Users**, and then click the user.</span></span>
2. <span data-ttu-id="8a817-117">Wählen Sie den Nutzer aus, indem Sie links neben den Nutzernamen klicken, und klicken Sie dann auf **Einstellungen bearbeiten**.</span><span class="sxs-lookup"><span data-stu-id="8a817-117">Select the user by clicking to the left of the user name, and then click **Edit settings**.</span></span>
3. <span data-ttu-id="8a817-118">Wählen Sie unter **Besprechungsrichtlinie** die Richtlinie aus, die Sie zuweisen möchten, und klicken Sie dann auf **Übernehmen**.</span><span class="sxs-lookup"><span data-stu-id="8a817-118">Under **Meeting policy**, select the policy you want to assign and then click **Apply**.</span></span>

<span data-ttu-id="8a817-119">Weitere Informationen finden Sie unter [Besprechungsrichtlinien in Teams verwalten](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span><span class="sxs-lookup"><span data-stu-id="8a817-119">For more information, see [Manage meeting policies in Teams](https://docs.microsoft.com/microsoftteams/meeting-policies-in-teams).</span></span>
