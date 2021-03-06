---
title: Outlook-Desktop Rückruf oder Ersetzen einer e-Mail-Nachricht
ms.author: daeite
author: daeite
manager: joallard
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ms.custom: 9000260
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.openlocfilehash: 578e2690061286bde74ee0b4b74a197630716f59
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47663989"
---
# <a name="recall-or-replace-an-outlook-email-message"></a>Rückruf oder Ersetzen einer Outlook-e-Mail-Nachricht

- Als Administrator können Sie **Nachrichten im Namen von Benutzern mithilfe von PowerShell abrufen**. Sie können keine Nachrichten aus dem Admin Center abrufen.
- Sie können **nur Nachrichten abrufen, die an Personen in Ihrer Organisation gesendet werden**. Wenn die Nachricht beispielsweise an eine gmail-Adresse gesendet wurde, können Sie Sie nicht mehr abrufen.
- Sie können **nur Nachrichten abrufen, die von Outlook 2016 auf dem PC gesendet wurden**. Wenn ein Benutzer eine Nachricht mit Outlook für Mac oder Outlook im Internet sendet, kann er nicht mehr daran erinnert werden.

So rufen Sie eine e-Mail-Nachricht auf oder ersetzen Sie:

1. Wählen Sie im Ordnerbereich auf der linken Seite des Outlook-Fensters den Ordner "Gesendete Elemente" aus.
1. Doppelklicken Sie auf die Nachricht, die Sie abrufen möchten, um Sie zu öffnen.
1. Wählen Sie die Registerkarte **Nachricht** aus, und wählen Sie dann **Aktionen**  >  **Rückruf dieser Nachricht**aus.
1. Wählen Sie **Ungelesene Kopien dieser Nachricht löschen** oder **Ungelesene Kopien löschen aus, und ersetzen Sie Sie durch eine neue Nachricht**, und wählen Sie dann **OK**aus.
1. Wenn Sie eine Ersatznachricht senden, verfassen Sie die Nachricht, und wählen Sie dann **senden**aus.
1. Der Erfolg oder Misserfolg eines Nachrichtenrückrufs hängt von den Einstellungen des Empfängers in Outlook ab. Schritte zum Überprüfen des Rückrufs finden Sie in [diesem Artikel](https://support.office.com/article/35027f88-d655-4554-b4f8-6c0729a723a0).

Suchen nach und Löschen von E-Mail-Nachrichten in der Organisation

- Wenn Sie kein globaler Administrator sind, muss Ihr Konto zur eDiscovery-Manager-Rolle oder zur Verwaltungsrolle "Compliance Search" hinzugefügt werden, um nach Nachrichten zu suchen. Wenn Sie Nachrichten löschen möchten, müssen Sie der Rollengruppe "Organisationsverwaltung" oder der Rolle "Such-und Lösch Verwaltung" beitreten. Berechtigungen für diese Rollen werden im [Security and Compliance Center](https://go.microsoft.com/fwlink/?linkid=2083731)zugewiesen.
- [Erstellen Sie eine Inhaltssuche](https://docs.microsoft.com/microsoft-365/compliance/content-search) , um die zu löschende Nachricht zu suchen.
- Stellen [Sie eine Verbindung mit Security and Compliance Center PowerShell her](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/connect-to-scc-powershell?view=exchange-ps).

Wenn Sie die mehrstufige Authentifizierung verwenden, lesen Sie die Informationen unter [Connect to Microsoft 365 Security and Compliance Center PowerShell using Multi-Factor Authentication](https://docs.microsoft.com/powershell/exchange/office-365-scc/connect-to-scc-powershell/mfa-connect-to-scc-powershell?view=exchange-ps).