---
title: Probleme mit der SSO-Verbindung
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004357"
- "7810"
ms.openlocfilehash: 33074d70377866332feeccfb8b6400eff2de5a73
ms.sourcegitcommit: e188ec7a583837a3e07880d05b3607b8bdac729c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 01/21/2021
ms.locfileid: "49918140"
---
# <a name="sso-connection-issues"></a>Probleme mit der SSO-Verbindung

1. Folgen Sie den Anweisungen unter [Schnellstart: Konfigurieren von Eigenschaften für eine Anwendung](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure) zum Konfigurieren Ihrer Anwendung.
2. Befolgen Sie in Abhängigkeit von der gewählten Anwendungs- und [Einmaliges Anmelden-Option](https://docs.microsoft.com/azure/active-directory/manage-apps/sso-options) die entsprechenden Anweisungen unten:
    - Informationen zum Konfigurieren **einer lokalen** Anwendung für **SAML-basiertes** einmaliges Anmelden finden Sie unter "EINMALIGES ANMELDEN" für lokale Anwendungen [mit Anwendungsproxy.](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-on-premises-apps)
    - Informationen zum Konfigurieren einer **Cloudanwendung** für **kennwortbasierte einmaliges** Anmelden finden Sie unter "Konfigurieren des einmaligen Anmeldens [für Kennwörter".](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications)
    - Informationen zum Konfigurieren einer  **lokalen** Anwendung für einmaliges Anmelden über Anwendungsproxy finden Sie unter Kennworttresor für einmaliges Anmelden [mit Anwendungsproxy.](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting)
3. **Behandlung von Anwendungsproxyproblemen:** Es wird empfohlen, dass Sie mit der Überprüfung des Problembehandlungsflusses, des Debuggens von Problemen mit dem Anwendungsproxyconnector beginnen, um zu ermitteln, ob Anwendungsproxyconnectors ordnungsgemäß konfiguriert sind. [](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-debug-connectors) Wenn sie weiterhin Probleme beim Herstellen einer Verbindung mit der Anwendung haben, folgen Sie dem Problembehandlungsablauf unter Debuggen von [Anwendungsproxyanwendungsproblemen.](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-debug-apps) Sie können [CORS-Probleme mithilfe](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-understand-cors-issues#understand-and-identify-cors-issues) von Browserdebuggertools identifizieren:
    - Starten Sie den Browser, und navigieren Sie zu der Web-App.
    - Drücken Sie **F12**, um die Debuggingkonsole zu öffnen.
    - Versuchen Sie, die Transaktion zu reproduzieren, und überprüfen Sie die Konsolenmeldung. Eine CORS-Verletzung führt zu einem Konsolenfehler hinsichtlich des Ursprungs.
    - Einige CORS-Probleme können nicht behoben werden, z. B. wenn Ihre App login.microsoft.com Authentifizierung umleitiert und das Zugriffstoken abläuft. Der CORS-Aufruf schlägt dann fehl. Eine Problemumgehung für dieses Szenario besteht im Verlängern der Gültigkeit des Zugriffstokens, um zu verhindern, dass es während einer Benutzersitzung abläuft. Weitere Informationen dazu finden Sie unter [Konfigurierbare Tokengültigkeitsdauer auf der Microsoft Identity Platform](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes).
4. **Problembehandlung beim SAML-basierten** einmaligen Anmelden: Es wird empfohlen, probleme beim Anmelden bei [saml-basierten](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery)apps für einmaliges Anmelden zu überprüfen, um die Lösungen für die Probleme zu finden, die wahrscheinlich auftreten.
5. **Problembehandlung beim kennwortbasierten** einmaligen Anmelden: Wir empfehlen, die Problembehandlung für kennwortbasierte einmaliges Anmelden [in Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso)zu überprüfen, um die Lösungen für die Probleme zu finden, die wahrscheinlich auftreten.
6. Informationen zu Verbindungsprobleme bei der Verwendung eines VPN finden Sie unter "Verwenden des einmaligen Anmeldens [(Single Sign On, SSO) über VPN](https://docs.microsoft.com/windows/security/identity-protection/vpn/how-to-use-single-sign-on-sso-over-vpn-and-wi-fi-connections)und Wi-Fi Verbindungen.
