---
title: Arbeiten mit IOS VPP-Anwendungen Regelkennung 1018
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1018"
- "6700004"
ms.assetid: 2e51ae64-8ba2-42e1-9e3e-f4aad102c391
ms.openlocfilehash: 67800b261e7d670181b17783bc81e276d75026e0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47688945"
---
# <a name="working-with-ios-vpp-applications"></a>Arbeiten mit IOS-VPP-Anwendungen

In diesem Artikel erfahren Sie, [wie Sie IOS-apps verwalten können, die über ein Volumen Einkaufsprogramm mit Microsoft InTune erworben](https://docs.microsoft.com/intune/vpp-apps-ios) wurden, um sich über Features, Einschränkungen und Schritte für die Verwendung des Apple Volume Purchase-Programms und dessen Unterstützung in Microsoft InTune zu informieren.
  
 **Häufige Probleme:** "Ich habe meinen Benutzern eine IOS VPP-App zugewiesen, aber die Installation ist fehlgeschlagen."
  
- Dies kann vorkommen, wenn ein einzelnes VPP-Token für mehrere Anbieter für die Verwaltung mobiler Geräte verwendet wird. VPP-Token von Apple dürfen nur mit einem Anbieter verwendet werden. Wenn Sie ein VPP-Token mit mehreren Anbietern verwendet haben, müssen Sie das Token erneut in InTune hochladen.

- Die Installation kann auch fehlschlagen, wenn die Gesamtanzahl der Installationen die Anzahl der Lizenzen überschreitet. Um einen Verwendungsbericht für Ihre Lizenzen anzuzeigen, wechseln Sie zur Seite **InTune Mobile Apps** - \> **App-Lizenzen** . Informationen zum Freigeben von Lizenzen in use finden Sie in [diesem Artikel.](https://docs.microsoft.com/intune/vpp-apps-ios#revoking-app-licenses-and-deleting-tokens)
