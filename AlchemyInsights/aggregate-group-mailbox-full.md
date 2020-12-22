---
title: AggregateGroupMailbox vollständiger NDR für e-Mails, die an die Microsoft 365-Gruppe gesendet wurden
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004286"
- "7656"
ms.openlocfilehash: 9de09ab4cbd2f09648305b11da6273ed990907cf
ms.sourcegitcommit: 2ffdf6096de5608b117c6677d3cd7dd4c23ea024
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 12/18/2020
ms.locfileid: "49715698"
---
# <a name="aggregategroupmailbox-full-ndr-received-for-email-sent-to-microsoft-365-group"></a><span data-ttu-id="40bb9-102">AggregateGroupMailbox vollständiger NDR für e-Mails, die an die Microsoft 365-Gruppe gesendet wurden</span><span class="sxs-lookup"><span data-stu-id="40bb9-102">AggregateGroupMailbox full NDR received for email sent to Microsoft 365 group</span></span>

<span data-ttu-id="40bb9-103">Verwenden Sie den folgenden Exo-Shell-Befehl, um eine Exchange-Transportregel zum automatischen ablegen von e-Mails zu erstellen, die an das Aggregat Gruppenpostfach gesendet werden:</span><span class="sxs-lookup"><span data-stu-id="40bb9-103">Use the following EXO Shell command to create an Exchange transport rule to silently drop emails sent to aggregate group mailbox:</span></span>

`New-TransportRule -SentTo @("AggregateGroupMailbox.A.201708181918@contoso.onmicrosoft.com") -DeleteMessage:$true -Name 'Agg1' -StopRuleProcessing:$false -Mode 'Enforce' -Comments '' -RuleErrorAction 'Ignore' -SenderAddressLocation 'Header'`

> [!NOTE]
> <span data-ttu-id="40bb9-104">Ersetzen Sie die SMTP-Adresse in **-SentTo** durch die SMTP-Adresse des Aggregat Gruppen Postfachs in Ihrem Mandanten.</span><span class="sxs-lookup"><span data-stu-id="40bb9-104">Replace the SMTP address in **-SentTo** with SMTP address of aggregate group mailbox in your tenant.</span></span> <span data-ttu-id="40bb9-105">Sie können die SMTP-Adresse des Aggregat Gruppen Postfachs aus dem empfangenen Unzustellbarkeitsbericht abrufen.</span><span class="sxs-lookup"><span data-stu-id="40bb9-105">You can get the SMTP address of aggregate group mailbox from the NDR received.</span></span>


