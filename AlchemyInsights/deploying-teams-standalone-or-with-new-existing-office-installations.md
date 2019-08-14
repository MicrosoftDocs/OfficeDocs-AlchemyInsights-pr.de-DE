---
title: Bereitstellen von Teams als eigenständig oder mit neuen oder vorhandenen Office-Installationen
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 08/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: 3318e1b17cc99e927e1011f7ca9eca8dec616d59
ms.sourcegitcommit: 4600dd4fb577bf5f5482a24616c2d9a6b81e8052
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 08/01/2019
ms.locfileid: "36054230"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a>Bereitstellen von Teams als eigenständig oder mit neuen oder vorhandenen Office-Installationen

Microsoft Teams ist jetzt im Rahmen ***neuer Installationen*** von Office 365 ProPlus, Office 365 Business und Office für Mac enthalten. Weitere Informationen finden Sie unter [wann werden Microsoft Teams in neue Office-Installationen aufgenommen?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)

Außerdem werden Microsoft Teams ab Version 1906 im monatlichen Kanal ***vorhandenen Installationen*** von Office 365 ProPlus (und Office 365 Business) auf Geräten mit Windows hinzugefügt, wenn Sie die vorhandene Installation auf die neueste Version aktualisieren. Weitere Informationen finden Sie unter [Was ist mit vorhandenen Installationen von Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus)

> [!NOTE]
> Wenn Sie nicht auf diesen Rollout Zeitplan warten möchten, können Sie Microsoft Teams als eigenständig für Ihre Benutzer bereitstellen, indem Sie [diese Anweisungen](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) befolgen oder Ihre Benutzer Teams für sich [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads)selbst installieren lassen.

Wenn Ihre Organisation nicht bereit ist, Teams bereitzustellen, haben wir die Schritte, die Sie ausführen können, um Teams von [neuen](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) oder [vorhandenen](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) Installationen von Office auszuschließen. ****** Wenn Sie möchten, dass Teams installiert werden, Sie aber nicht möchten, dass Teams nach der Installation automatisch für den Benutzer gestartet werden, finden Sie unter [verhindern, dass Microsoft Teams automatisch nach der Installation](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation)gestartet wird.

Informationen zum ***Deinstallieren von Teams*** von einem Gerät mit Windows finden Sie unter Deinstallieren von [Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81). Informationen zum Bereinigen von Microsoft Teams von mehreren Zielcomputern oder Benutzern finden Sie unter Cleanup von [Microsoft Teams-Bereitstellung](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).

Wenn Sie freigegebene Computer, Remote Desktop Dienste (RDS) oder virtuelle Desktopinfrastruktur (VDI) verwenden, finden Sie weitere Informationen unter [Shared Computer and VDI Environments with Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).

Wenn Sie Office für Mac verwenden, finden Sie weitere Informationen unter [Microsoft Teams-Installationen auf einem Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).

> [!NOTE]
> Nachdem Microsoft Teams installiert wurde, wird es automatisch etwa alle zwei Wochen mit neuen Features und Qualitäts Updates [aktualisiert](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) . 