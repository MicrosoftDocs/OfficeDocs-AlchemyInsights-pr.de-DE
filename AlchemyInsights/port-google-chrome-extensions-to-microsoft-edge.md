---
title: Portierung von Google Chrome-Erweiterungen zu Microsoft Edge (Chromium)
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004032"
- "7102"
- "8297"
- "9004617"
ms.openlocfilehash: 1c71d74d01c1e38e4c7789aea2c0b43701b3a5de
ms.sourcegitcommit: 7b2e5078dd65f11af6650e692a7ea48e91f544e0
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/02/2021
ms.locfileid: "51505283"
---
# <a name="port-google-chrome-extensions-to-microsoft-edge-chromium"></a>Portierung von Google Chrome-Erweiterungen zu Microsoft Edge (Chromium)

Es ist einfach, [Google Chrome-Erweiterungen auf Microsoft Edge (Chromium) zu porten.](https://docs.microsoft.com/microsoft-edge/extensions-chromium/developer-guide/port-chrome-extension) In den meisten Fällen sind nur minimale Änderungen erforderlich, um diese Erweiterungen auf Microsoft Edge ausführen zu können.

Die von Google Chrome unterstützten Erweiterungs-APIs und Manifestschlüssel sind codekompatibel mit Microsoft Edge. Microsoft Edge unterstützt jedoch nicht die Erweiterungs-APIs chrome.gcm, chrome.identity.getAccounts, chrome.identity.getAuthToken und chrome.instanceID.