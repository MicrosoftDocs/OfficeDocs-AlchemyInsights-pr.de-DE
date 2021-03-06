---
title: Mikroverzögerungen oder Drosselung in Exchange Online PowerShell
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
- "3500011"
- "5106"
ms.openlocfilehash: 204e0248bc2f07f14fa789d1d2999495910ee034
ms.sourcegitcommit: d2108b13acc44e26b65f9a2739cbce9bf98959a5
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/28/2021
ms.locfileid: "52702125"
---
# <a name="micro-delays-or-throttling-in-exchange-online-powershell"></a>Mikroverzögerungen oder Drosselung in Exchange Online PowerShell

Möglicherweise wird beim Ausführen von Skripts und Cmdlets in Exchange Online die Warnung "Mikroverzögerung angewendet" angezeigt. Hier sind einige Vorschläge, wie Sie das Problem lösen können:

- Bitte führen Sie unsere Diagnose aus, um die PowerShell-Drosselungsrichtlinien Ihres Mandanten zu entspannen. Diese Lösung wird das Problem für die meisten Personen lösen.
- Wenn das Problem noch nicht behoben ist, verwenden Sie das [Exchange Online v2 PowerShell-Modul](/powershell/exchange/exchange-online/exchange-online-powershell-v2/exchange-online-powershell-v2?view=exchange-ps&preserve-view=true), das Cmdlets enthält, die auf REST-API basieren und wesentlich performanter sind. Dies kann eine großartige Lösung für viele Get-Cmdlets sein, die häufig verwendet werden.
- Wenn Sie CMDlets verwenden müssen, die nicht im v2-Modul abgedeckt sind, lesen Sie bitte [Ausführen von PowerShell-Cmdlets für eine große Anzahl von Benutzern in Office 365](https://techcommunity.microsoft.com/t5/exchange-team-blog/updated-running-powershell-cmdlets-for-large-numbers-of-users-in/ba-p/1000628#), in dem beschrieben wird, wie Sie die PowerShell-Drosselungsgrenzen in Exchange Online umgehen können.
