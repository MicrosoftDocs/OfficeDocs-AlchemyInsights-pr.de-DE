---
title: SharePoint Online auf den klassischen Modus beschränken
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.custom:
- "1835"
- "1889"
- "9000225"
ms.openlocfilehash: 1887bf64df98bf90a1902250633d5774178dfa2f
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47751421"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a>SharePoint Online auf den klassischen Modus beschränken

Einige Organisationen benötigen weiterhin die klassische Modus-Erfahrung. Es gibt zwar keine Pläne, den klassischen Modus auf granularer Ebene zu entfernen, es ist jedoch nicht mehr möglich, eine gesamte Organisation (einen Mandanten) auf den klassischen Modus für Listen und Bibliotheken zu beschränken.

Der Administrator verfügt über die folgenden Optionen zum Verwalten einzelner Listen und Bibliotheken im klassischen Modus mithilfe von granularen Opt-out-Switches, die auf den folgenden Ebenen bereitgestellt werden:

- Websitesammlung
- Website
- Liste
- Bibliothek

Außerdem werden Listen, die bestimmte Features und Anpassungen verwenden, die nicht von modern unterstützt werden, weiterhin automatisch in den klassischen Modus umgeschaltet.

Ab dem 1. April 2019 wird der Vorgang zum Deaktivieren der Mandantenebene aus modernen Listen und Bibliotheken gestartet und wird bis zum 31. Mai 2019 fortgesetzt.  Die Listen und Bibliotheken, die sich im klassischen Modus infolge eines Mandanten Abmeldens befinden, werden automatisch auf modern verschoben.

Wenn Sie den klassischen Modus benötigen, lesen Sie hier [Weitere Informationen und](https://techcommunity.microsoft.com/t5/Microsoft-SharePoint-Blog/Delivering-SharePoint-modern-experiences/ba-p/315023) hier finden Sie die PNP-PowerShell-Anweisung, in der Optionen und Tools beschrieben [werden, die](https://docs.microsoft.com/sharepoint/dev/transform/modernize-userinterface-lists-and-libraries-optout) Sie heute verwenden können, um die klassische Benutzeroberfläche zu verwenden.
