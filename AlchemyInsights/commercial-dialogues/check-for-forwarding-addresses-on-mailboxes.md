---
title: Überprüfen der Weiterleitung von Adressen für Postfächer
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 17/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002486"
- "7524"
ms.openlocfilehash: 1b0a6c8fe368196f2d1f9811aea895c2c024b2e6
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2021
ms.locfileid: "50464763"
---
# <a name="check-for-forwarding-addresses-on-mailboxes"></a><span data-ttu-id="07fc1-102">Überprüfen der Weiterleitung von Adressen für Postfächer</span><span class="sxs-lookup"><span data-stu-id="07fc1-102">Check for forwarding addresses on mailboxes</span></span>

<span data-ttu-id="07fc1-103">Manchmal werden die E-Mail-Nachrichten von Benutzern von Hackern an sich selbst weitergeleitet, daher prüfen wir zunächst, ob Adressen und Regeln für das Postfach weitergeleitet werden.</span><span class="sxs-lookup"><span data-stu-id="07fc1-103">Sometimes hackers forward users' email messages to themselves, so first we'll check for forwarding addresses and rules on the mailbox.</span></span> <span data-ttu-id="07fc1-104">Anschließend überprüfen wir die Überwachungsprotokolle.</span><span class="sxs-lookup"><span data-stu-id="07fc1-104">Then we'll check the audit logs.</span></span> <span data-ttu-id="07fc1-105">Hier erfahren Sie, wie Sie nach Weiterleitungsadressen suchen:</span><span class="sxs-lookup"><span data-stu-id="07fc1-105">Here's how to check for forwarding addresses:</span></span>

1. <span data-ttu-id="07fc1-106">Wählen Sie **Benutzer**  >  **Aktive Benutzer aus.**</span><span class="sxs-lookup"><span data-stu-id="07fc1-106">Select **Users** > **Active users**.</span></span>
1. <span data-ttu-id="07fc1-107">Wählen Sie den Benutzer aus, dessen Konto gefährdet wurde.</span><span class="sxs-lookup"><span data-stu-id="07fc1-107">Select the user whose account has been compromised.</span></span>
1. <span data-ttu-id="07fc1-108">Erweitern Sie im angezeigten Flyout die **E-Mail-Einstellungen,** und klicken Sie dann auf **Bearbeiten** für **E-Mail-Weiterleitung.**</span><span class="sxs-lookup"><span data-stu-id="07fc1-108">In the flyout that appears, expand **Mail Settings**, and then click **Edit** for **Email forwarding**.</span></span>
1. <span data-ttu-id="07fc1-109">Entfernen Sie alle Weiterleitungsadressen, die Sie nicht erkennen.</span><span class="sxs-lookup"><span data-stu-id="07fc1-109">Remove any forwarding addresses you don't recognize.</span></span>