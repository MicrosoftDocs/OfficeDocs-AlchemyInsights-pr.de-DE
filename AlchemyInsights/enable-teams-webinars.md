---
title: Aktivieren von Teams-Webinaren
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 06/02/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "11513"
- "9006672"
ms.openlocfilehash: 5a732e6746e9fd23e54a0b2ffeabb59623012a0e
ms.sourcegitcommit: 9de78b30602f917d58705057cdcce31fec349969
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/04/2021
ms.locfileid: "52760837"
---
# <a name="enable-teams-webinars"></a>Aktivieren von Teams-Webinaren

Webinare sind standardmäßig aktiviert. Mithilfe der Teams PowerShell-Befehlen können Sie verwalten, wer Teams-Webinare planen und sich für diese registrieren kann.

- Alle Benutzer, die Besprechungen erstellen können, können auch Webinarbesprechungen erstellen. Um zu verwalten, wer Teams-Webinare planen kann, verwenden Sie *AllowMeetingRegistration*. 
- Standardmäßig ist *WhoCanRegister* aktiviert und auf **Jeder** festgelegt. Wenn Sie die Besprechungsregistrierung deaktivieren möchten, legen Sie *AllowMeetingRegistration* auf **False** fest.

Um diese Einstellungen zu ändern, müssen Sie [Teams PowerShell](/microsoftteams/teams-powershell-install) installieren. Außerdem werden Besprechungsrichtlinien in Teams-Webinaren erzwungen. Wenn der anonyme Beitritt beispielsweise in den Besprechungseinstellungen deaktiviert ist, können anonyme Benutzer nicht an Webinaren teilnehmen.

Weitere Informationen dazu, wie Sie konfigurieren können, wer sich für Webinare registrieren kann, finden Sie unter [Konfigurieren, wer sich für Webinare registrieren kann](/microsoftteams/set-up-webinars?source=docs#configure-who-can-register-for-webinars). Weitere Informationen zu den Einstellungen für Microsoft Listen finden Sie unter [Steuern der Einstellungen für Microsoft Listen](/sharepoint/control-lists).