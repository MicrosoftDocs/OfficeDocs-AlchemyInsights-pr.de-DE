---
title: Doppelter Gerätedatensatz im Portal
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9001495"
- "4386"
ms.openlocfilehash: 277afc59705e6040f0f9ae0c8cad965bd7d3ef65
ms.sourcegitcommit: 89ae9e8b36d1980f89f07b016fff0ec48f96b620
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/23/2020
ms.locfileid: "43789861"
---
# <a name="duplicate-device-record-in-the-portal"></a>Doppelter Gerätedatensatz im Portal

Sie sehen möglicherweise zwei Datensätze für ein Gerät im Portal, wenn das Gerät den Co-Verwaltungsstatus nicht korrekt an die Configuration-Manager-Site meldet. Um den Co-Verwaltungsstatus eines Geräts zu überprüfen, überprüfen Sie die Spalte **Co-verwaltet** auf das Gerät in der Configuration Manager-Konsole. Wenn die Spalte nicht sichtbar ist, können Sie sie hinzufügen, indem Sie mit der rechten Maustaste auf eine der Spaltenüberschriften klicken und sie aus der Liste auswählen.

Der Wert für „Co-verwaltet“ muss **Ja** lauten. Wenn der Wert **Nein** lautet, öffnen Sie das Configuration Manager-Client-Applet auf dem Client-Gerät, und aktivieren Sie die Eigenschaft **Co-Verwaltung** auf der Registerkarte „Allgemein“.

- Wenn der Wert **Aktiviert** lautet, bedeutet dies, dass es Probleme mit der Kommunikation des Clients mit dem Verwaltungspunkt gibt. Bitte lesen Sie auf dem Gerät die Datei **CcmMessaging.log** durch, um mögliche Verbindungsprobleme zu untersuchen.

- Wenn der Wert **Deaktiviert** lautet und das Gerät bei Intune angemeldet ist, stellen Sie bitte sicher, dass das Gerät die Co-Verwaltungsrichtlinie erhalten hat, indem Sie die Datei **CoManagementHandler.log** auf dem Gerät überprüfen.