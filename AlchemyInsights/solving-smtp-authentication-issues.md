---
title: Beheben von Problemen mit der SMTP-Authentifizierung
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "3000003"
- "5652"
ms.openlocfilehash: 814c49e8e65966a0c9f927b1f7bfb03d3dc3d637
ms.sourcegitcommit: 0e43e19448705f151846e9e9e1e0f47e12938fdf
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/15/2020
ms.locfileid: "44264429"
---
# <a name="solving-smtp-authentication-issues"></a>Beheben von Problemen mit der SMTP-Authentifizierung

Wenn Sie beim Versuch, eine SMTP-E-Mail zu versenden und diese über einen Client oder eine Anwendung zu authentifizieren, die Fehlermeldungen 5.7.57 oder 5.7.3 erhalten, sollten Sie Folgendes überprüfen:

- Die authentifizierte SMTP-Übermittlung ist möglicherweise in Ihrem Mandanten oder dem Postfach, das Sie verwenden möchten, deaktiviert (überprüfen Sie beide Einstellungen). Weitere Informationen finden Sie unter [Authentifizierte Client-SMTP-Übermittlung aktivieren oder deaktivieren](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/authenticated-client-smtp-submission).

- Überprüfen Sie, ob [Azure Sicherheitsvorgaben](https://docs.microsoft.com/azure/active-directory/fundamentals/concept-fundamentals-security-defaults) für Ihren Mandanten aktiviert sind. Wenn diese Option aktiviert ist, schlägt die SMTP-Authentifizierung mithilfe der Standardauthentifizierung (auch als „Legacy-Authentifizierung“ bekannt; diese verwendet Benutzernamen und Kennwort) fehl.