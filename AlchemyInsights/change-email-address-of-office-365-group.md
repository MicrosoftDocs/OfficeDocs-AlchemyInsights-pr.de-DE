---
title: Ändern der E-Mail-Adresse einer Microsoft 365-Gruppe
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
- "1200024"
- "4704"
ms.openlocfilehash: 8eaafae8650a8072cdfbec281afe6d5e93fea655
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51819043"
---
# <a name="change-email-address-of-a-microsoft-365-group"></a>Ändern der E-Mail-Adresse einer Microsoft 365-Gruppe

Sie können die E-Mail-Adresse einer Microsoft 365-Gruppe über das Admin Center ändern. Wählen Sie einfach die betreffende Gruppe und dann @bearbeiten E-Mail-Adresse aus.

Sie können auch den folgenden EXO PowerShell-Befehl verwenden, um die primäre SMTP-Adresse einer Microsoft 365-Gruppe zu ändern:

Set-UnifiedGroup <Group Name> -PrimarySmtpAddress <new SMTP Address>

Beispiel:

```
    Set-UnifiedGroup Marketing -PrimarySmtpAddress marketing@contoso.com
```
