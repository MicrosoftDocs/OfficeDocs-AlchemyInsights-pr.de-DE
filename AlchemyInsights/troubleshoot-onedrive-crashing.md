---
title: Fehlerbehandlung bei OneDrive-Abstürzen
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
- "9003084"
- "5885"
ms.openlocfilehash: 4bf45e7780dcbabb95b3eecfb2df55beffde11d6
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51826198"
---
# <a name="troubleshoot-onedrive-crashes"></a>Fehlerbehandlung bei OneDrive-Abstürzen

Wenn OneDrive wiederholt abstürzt, versuchen Sie die folgenden Schritte zur Problembehandlung:

**Stellen Sie sicher, dass die Registrierungsschlüssel nicht festgelegt sind:**

1. Navigieren Sie mithilfe des Registrierungs-Editors zu HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\OneDrive
2. Wenn „DisableFileSyncNGSC“ vorhanden und auf „1“ festgelegt ist, öffnen Sie den Schlüssel und ändern Sie den Wert auf „0“.
3. Starten Sie OneDrive manuell, indem Sie zu „Start“ wechseln. ![Drücken Sie die WINDOWS-TASTE,](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAOCAYAAADJ7fe0AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAADxSURBVDhPY/wPBAx4wR+Gd6/fM7x9/ZTh9ZuXDGdPnWE4tH0rw/UHDxlaVp9kCDCSYWABKfv35wfD+/cfGV4+fcLw5uVjhlOXzzFsX/qWYebmZAZPWWOGO2DD8ACQS9Y3e4Bcg4Y9/t94fPa/CoY4Aq8/+xik/T8TkEMxGDyGgANWwSqeobvbGSyAADIM3BwCDKXd3QyfoCLoQEGAA0xTxSWjsYMJwLHjkruU4UXSJ4YnT54x3Dh/luHmjfMMmw9wMjCDlRAGBDPgjy8fGT5//8rw9P4Thge3zzNcvXmDYevmfQzXb1xlmH/0ATADyjAAAKdWkD3ZSwNeAAAAAElFTkSuQmCC)geben Sie im Suchfeld den Begriff OneDrive ein und klicken Sie dann auf die OneDrive Desktop-App.

**OneDrive zurücksetzen:**

Hinweise:

- Beim Zurücksetzen von OneDrive werden alle Ihre bestehenden Synchronisierungsverbindungen (einschließlich – sofern eingerichtet – Ihr persönliches OneDrive) getrennt.
- Wenn Sie OneDrive auf Ihrem Computer zurücksetzen, gehen keine Dateien oder Daten verloren.

**Zurücksetzen von OneDrive:**

1. Öffnen Sie ein Dialogfeld „Ausführen“, indem Sie die WINDOWS-TASTE und R drücken.
2. Geben Sie „%localappdata%\Microsoft\OneDrive\onedrive.exe /reset“ ein und klicken Sie auf OK. Möglicherweise wird kurz ein Befehlsfenster eingeblendet.
3. Starten Sie OneDrive manuell, indem Sie zu „Start“ wechseln. ![Drücken Sie die WINDOWS-TASTE,](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAOCAYAAADJ7fe0AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAADxSURBVDhPY/wPBAx4wR+Gd6/fM7x9/ZTh9ZuXDGdPnWE4tH0rw/UHDxlaVp9kCDCSYWABKfv35wfD+/cfGV4+fcLw5uVjhlOXzzFsX/qWYebmZAZPWWOGO2DD8ACQS9Y3e4Bcg4Y9/t94fPa/CoY4Aq8/+xik/T8TkEMxGDyGgANWwSqeobvbGSyAADIM3BwCDKXd3QyfoCLoQEGAA0xTxSWjsYMJwLHjkruU4UXSJ4YnT54x3Dh/luHmjfMMmw9wMjCDlRAGBDPgjy8fGT5//8rw9P4Thge3zzNcvXmDYevmfQzXb1xlmH/0ATADyjAAAKdWkD3ZSwNeAAAAAElFTkSuQmCC)geben Sie im Suchfeld den Begriff OneDrive ein und klicken Sie dann auf die OneDrive Desktop-App.

Hinweise:

- Wenn Sie vor dem Zurücksetzen ausgewählt hatten, dass nur einige Ordner synchronisiert werden sollen, müssen Sie dies nach Abschluss der Synchronisierung erneut tun. Weitere Informationen finden Sie unter  [Auswählen der OneDrive-Ordner, die mit Ihrem Computer synchronisiert werden sollen](https://support.office.com/article/98b8b011-8b94-419b-aa95-a14ff2415e85) .
- Sie müssen dies für Ihr persönliches OneDrive und für OneDrive for Business ausführen.