---
title: Einmaliges Anmelden – Konfigurationsprobleme
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/17/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7760"
- "9004346"
ms.openlocfilehash: 5ab56ec1eda10ea059e600e8933ce85bb143b76e
ms.sourcegitcommit: 6d02eb533fd74199af6b20f714b3720991da2c4a
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/18/2021
ms.locfileid: "49886857"
---
# <a name="sso-configuration-issues"></a>Einmaliges Anmelden – Konfigurationsprobleme

1. Folgen Sie den Anweisungen unter [Schnellstart: Konfigurieren von Eigenschaften für eine Anwendung](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure) zum Konfigurieren Ihrer Anwendung.
2. Folgen Sie je nach Anwendung und der gewählten [Option für das einmalige Anmelden](https://docs.microsoft.com/azure/active-directory/manage-apps/sso-options) den entsprechenden Anweisungen unten: a. Informationen zum Konfigurieren einer **lokalen Anwendung** für **SAML-basiertes einmaliges Anmelden (SSO)** finden Sie unter [SAML-basiertes einmaliges Anmelden (SSO) für lokale Anwendungen mit Anwendungsproxy](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-on-premises-apps).
    b. Informationen zum Konfigurieren einer **Cloudanwendung** für **kennwortbasiertes einmaliges Anmelden** finden Sie unter [Konfigurieren des kennwortbasierten einmaligen Anmeldens](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-password-single-sign-on-non-gallery-applications).
    c. Informationen zum Konfigurieren einer **lokalen Anwendung** für das **einmalige Anmelden über Anwendungsproxy** finden Sie unter [Kennworttresore (Password Vaulting) für einmaliges Anmelden mit Anwendungsproxy](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-password-vaulting).
3. **Behandlung von Problemen mit Anwendungsproxys**: Es wird empfohlen, mit dem Problembehandlungsablauf – [Debuggen von Problemen mit Anwendungsproxyconnectors](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-debug-connectors) – zu beginnen, um zu ermitteln, ob Anwendungsproxyconnectors ordnungsgemäß konfiguriert sind. Wenn weiterhin Probleme beim Herstellen einer Verbindung mit der Anwendung bestehen, führen Sie die Schritte zur Problembehandlung unter [Debuggen von Problemen mit Anwendungsproxyanwendungen](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-debug-apps) aus. [CORS-Probleme](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-understand-cors-issues#understand-and-identify-cors-issues) können Sie ermitteln, indem Sie die folgenden Schritte zum Debuggen über den Browser ausführen: a. Starten Sie den Browser, und navigieren Sie zu der Web-App.
    b. Drücken Sie **F12**, um die Debuggingkonsole zu öffnen.
    c. Versuchen Sie, die Transaktion zu reproduzieren, und überprüfen Sie die Konsolenmeldung. Eine CORS-Verletzung führt zu einem Konsolenfehler hinsichtlich des Ursprungs.
    d. Bestimmte CORS-Probleme können nicht behoben werden, wie etwa das Ablaufen des Zugriffstokens, wenn Ihre App zur Authentifizierung zu login.microsoftonline.com umleitet. Infolge des Ablaufs des Zugriffstokens schlägt der CORS-Aufruf dann fehl. Eine Problemumgehung für dieses Szenario besteht im Verlängern der Gültigkeit des Zugriffstokens, um zu verhindern, dass es während einer Benutzersitzung abläuft. Weitere Informationen dazu finden Sie unter [Konfigurierbare Tokengültigkeitsdauer auf der Microsoft Identity Platform](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes).
4. **Problembehandlung bei SAML-basiertem einmaligem Anmelden**: Lösungen für die am wahrscheinlichsten auftretenden Probleme finden Sie unter [Probleme beim Anmelden bei Apps, die für SAML-basiertes einmaliges Anmelden konfiguriert sind](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery).
5. **Problembehandlung bei kennwortbasiertem einmaligem Anmelden**: Lösungen für die am wahrscheinlichsten auftretenden Probleme finden Sie unter [Problembehandlung bei kennwortbasiertem einmaligem Anmelden in Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso).
6. **Ich habe eine Meldung zu einem Konfigurationsfehler erhalten**: Zum Beheben von Konfigurationsfehlern empfehlen wir, die folgenden Artikel zu lesen: a. [Probleme beim Anmelden bei Apps, die für SAML-basiertes einmaliges Anmelden konfiguriert sind](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-federated-sso-gallery) b. [Anmeldeinformationen werden ausgefüllt, aber von der Erweiterung nicht übermittelt](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso#credentials-are-filled-in-but-the-extension-does-not-submit-them) c. [Anmeldeinformationen werden ausgefüllt und übermittelt, aber auf der Seite wird angegeben, dass die Anmeldeinformationen falsch sind](https://docs.microsoft.com/azure/active-directory/manage-apps/troubleshoot-password-based-sso) d. [Auf einer App-Seite wird eine Fehlermeldung angezeigt, nachdem sich der Benutzer angemeldet hat](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-problem-application-error)
7. **Ich habe Probleme bei der Integration von nahtlosem einmaligem Anmelden in meine lokalen Apps**: Um Probleme im Zusammenhang mit der Integration von nahtlosem einmaligem Anmelden in lokale Apps zu behandeln, sollten Sie die folgenden Artikel lesen: a. [Informationen zum Konfigurieren des einmaligen Anmeldens bei einer Anwendungsproxyanwendung](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-config-sso-how-to) b. [SAML-basiertes einmaliges Anmelden für lokale Anwendungen mit Anwendungsproxy](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-single-sign-on-on-premises-apps) c. [Verstehen und Lösen von CORS-Problemen mit Azure Active Directory-Proxys](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-understand-cors-issues#solutions-for-application-proxy-cors-issues) d. [Problembehandlung bei eingeschränkten Kerberos-Delegierungskonfigurationen für Anwendungsproxys](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-back-end-kerberos-constrained-delegation-how-to)
8. **Ich muss die Ansprüche korrigieren oder die Gültigkeitsdauer eines Tokens verlängern. Ich muss die Dauer einer Sitzung ändern.**: Zu diesem Zweck empfehlen wir, die folgenden Artikel zu lesen: a. [Anpassen von SAML-Ansprüchen, die an eine Anwendung gesendet werden](https://docs.microsoft.com/azure/active-directory/develop/active-directory-claims-mapping) b. [Arbeiten mit anspruchsfähigen Apps](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-for-claims-aware-applications) c. [Konfigurierbare Token-Gültigkeitsdauer auf der Microsoft Identity Platform](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) d. [Konfigurieren der Verwaltung von Authentifizierungssitzungen mit bedingtem Zugriff](https://docs.microsoft.com/azure/active-directory/conditional-access/howto-conditional-access-session-lifetime) e. [Cookieeinstellungen für den Zugriff auf lokale Anwendungen](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-cookie-settings)
9. **Ich brauche Hilfe beim Verwalten des (B2B-) Zugriffs meiner Benutzer und Gastbenutzer**: Ausführliche Informationen zum Verwalten des Zugriffs von Benutzern und Gastbenutzern finden Sie in den folgenden Artikeln: a. [Verwalten des Zugriffs auf Apps](https://docs.microsoft.com/azure/active-directory/manage-apps/what-is-access-management) b. [Verwalten von Benutzerzuweisungen für eine App in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/assign-user-or-group-access-portal) c. [Konfigurieren von SaaS-Apps für die B2B-Zusammenarbeit](https://docs.microsoft.com/azure/active-directory/external-identities/configure-saas-apps) d. [B2B-Benutzern in Azure AD Zugriff auf Ihre lokalen Anwendungen erteilen](https://docs.microsoft.com/azure/active-directory/external-identities/configure-saas-apps) e. [Lokal verwalteten Partnerkonten Zugriff auf Cloudressourcen mithilfe der Azure AD B2B-Zusammenarbeit gewähren](https://docs.microsoft.com/azure/active-directory/external-identities/hybrid-on-premises-to-cloud)
10. **Ich möchte meine Apps anpassen**: Detaillierte Informationen zum Anpassen von Apps finden Sie in den folgenden Artikeln: a. [Konfigurieren benutzerdefinierter Domänen mit Azure AD-Anwendungsproxys](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-custom-domain) b. [Festlegen einer benutzerdefinierten Startseite für veröffentlichte Apps](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-configure-custom-home-page) c. [Platzhalteranwendungen](https://docs.microsoft.com/azure/active-directory/manage-apps/application-proxy-wildcard)
11. **Ich habe Probleme beim Migrieren meiner App von AD FS zu Azure**: Um Probleme zu behandeln, die während der Migration Ihrer App von AD FS zu Azure aufgetreten sind, sollten Sie die folgenden Artikel lesen: a. [Ändern der Anwendungsauthentifizierung von Active Directory-Verbunddiensten (AD FS) zu Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/migrate-adfs-apps-to-azure) b. [Ressourcen zum Migrieren von Anwendungen zu Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/migration-resources)
