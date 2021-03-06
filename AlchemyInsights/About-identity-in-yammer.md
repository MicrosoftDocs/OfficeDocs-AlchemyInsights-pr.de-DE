---
title: Informationen zur Identität in Yammer
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/15/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6039"
- "9003111"
ms.openlocfilehash: f417117acac4c3040932fc0a35e5d0b1c3709cd5
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47664169"
---
# <a name="about-identity-in-yammer"></a>Informationen zur Identität in Yammer

Es wird empfohlen, dass für alle Netzwerke die folgenden Schritte ausgeführt werden, um identitätsbezogene Probleme zu vermeiden:

1. Erzwingen Sie die Office 365-Identität nach der Bereitstellung von Microsoft 365-Konten für Benutzer in Azure AD, um sicherzustellen, dass alle Benutzer sich mit ihrem Microsoft 365-Hauptkonto anmelden. Weitere Informationen finden Sie unter [Erzwingen der Office 365-Identität für Yammer-Benutzer](https://docs.microsoft.com/yammer/configure-your-yammer-network/enforce-office-365-identity).
2. Konsolidieren Sie mehrerer Yammer-Netzwerke. Älteren Yammer-Konfigurationen erlauben, dass mehrere Yammer-Netzwerke mit einem Mandanten verbunden werden. Weitere Informationen finden Sie unter [Netzwerkmigration: Konsolidieren von mehreren Yammer-Netzwerken](https://docs.microsoft.com/yammer/configure-your-yammer-network/consolidate-multiple-yammer-networks).
3. Optional können Sie eine Lizenz für Yammer erzwingen, um die Verwendung von Yammer für Benutzer ohne Lizenz zu sperren. Weitere Informationen finden Sie unter [Verwalten von Yammer-Benutzerlizenzen in Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365).
4. Überprüfen Sie abschließend die Benutzerliste für ältere Yammer-Netzwerke, und sperren Sie Legacybenutzer. Es wird empfohlen, die Benutzer auszusetzen (zu deaktivieren), statt sie zu löschen, da das Löschen nicht rückgängig gemacht werden kann. Weitere Informationen finden Sie unter [Überwachen von Yammer-Benutzern in mit Office 365 verbundenen Netzwerken](https://docs.microsoft.com/yammer/manage-yammer-users/audit-users-connected-to-office-365) und [Entfernen von Benutzern](https://docs.microsoft.com/yammer/manage-yammer-users/add-block-or-remove-users#remove-users).

Indem Sie Yammer mit diesen Schritten konfigurieren, sind Sie auch bereit, Ihr Yammer Netzwerk für Microsoft 365 für den nativen Modus zu konfigurieren. Weitere Informationen finden Sie unter [Konfigurieren eines Yammer-Netzwerks für den nativen Modus für Microsoft 365](https://docs.microsoft.com/yammer/configure-your-yammer-network/native-mode).