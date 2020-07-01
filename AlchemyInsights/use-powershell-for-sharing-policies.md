---
title: Verwenden von PowerShell für Freigaberichtlinien und Organisationsbeziehungen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3800014"
- "898"
ms.openlocfilehash: 717cdd6827e243ac6bf375209a911937c97088d2
ms.sourcegitcommit: 722e9a0ed058cb1eab2dd053be2418b60f7d4aac
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/23/2020
ms.locfileid: "44854004"
---
# <a name="use-powershell-for-sharing-policies-and-organization-relationships"></a>Verwenden von PowerShell für Freigaberichtlinien und Organisationsbeziehungen


Informationen zu Organisationsbeziehungen finden Sie in den detaillierten Syntax- und Parameterinformationen für: [Get-FederationInformation](https://docs.microsoft.com/powershell/module/exchange/get-federationinformation), [New-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/new-organizationrelationship), [Set-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/set-organizationrelationship) UND [Remove-OrganizationRelationship](https://docs.microsoft.com/powershell/module/exchange/remove-organizationrelationship).

Zum Erstellen einer Freigaberichtlinie verwenden Sie [New-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/new-sharingpolicy). Um [eine Freigaberichtlinie auf ein Postfach oder einen Benutzer anzuwenden](https://docs.microsoft.com/exchange/sharing/sharing-policies/apply-a-sharing-policy%23use-exchange-online-powershell-to-apply-a-sharing-policy-to-one-or-more-mailboxes), müssen Sie eine Kombination aus [Set-Mailbox](https://docs.microsoft.com/powershell/module/exchange/set-mailbox) und [Get-Mailbox](https://docs.microsoft.com/powershell/module/exchange/get-mailbox) mit der neu erstellten Richtlinie verwenden. Zum [Ändern, Deaktivieren oder Entfernen einer Freigaberichtlinie](https://docs.microsoft.com/exchange/sharing/sharing-policies/modify-a-sharing-policy) müssen Sie [Set-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/set-sharingpolicy) and [Remove-SharingPolicy](https://docs.microsoft.com/powershell/module/exchange/remove-sharingpolicy) verwenden.

**Für vollständige Informationen zu diesem Thema lesen Sie:**

[Freigabe in Exchange Online](https://docs.microsoft.com/exchange/sharing/sharing)