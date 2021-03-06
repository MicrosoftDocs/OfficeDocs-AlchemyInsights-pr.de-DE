---
title: Problembehandlung bei einmaligem Anmelden für Azure AD-beigetretene Geräte
ms.author: v-jmathew
author: v-jmathew
manager: scotv
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003246"
- "9327"
ms.openlocfilehash: d11c24719eb2db9e9fd87c158c80cec5cb75b946
ms.sourcegitcommit: c08bed4071baa3bb5879496df3ed44fb828c8367
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/19/2021
ms.locfileid: "50898084"
---
# <a name="troubleshoot-single-sign-on-for-azure-ad-joined-devices"></a>Problembehandlung bei einmaligem Anmelden für Azure AD-beigetretene Geräte

Wenn Sie über eine lokale Active Directory (AD)-Umgebung verfügen und Ihre mit der AD-Domäne beigetretenen Computer zu Azure AD hinzufügen möchten, können Sie dies erreichen, indem Sie azure AD hybrid beitreten. [How To: Plan your hybrid Azure Active Directory join implementation](https://docs.microsoft.com/azure/active-directory/devices/hybrid-azuread-join-plan) provides you with the related steps to implement a hybrid Azure AD join in your environment.

Weitere Informationen finden Sie unter [Configure Azure AD joined devices for On-premises Single-Sign On using Windows Hello for Business](https://docs.microsoft.com/windows/security/identity-protection/hello-for-business/hello-hybrid-aadj-sso-base).

**Probleme mit dem primären Aktualisierungstoken (Primary Refresh Token, PRT)**

Ein primäres Aktualisierungstoken (Primary Refresh Token, PRT) ist ein Schlüsselartefakte der Azure AD-Authentifizierung auf Windows 10-, Windows Server 2016- und höher-, iOS- und Android-Geräten. Es handelt sich um ein JSON-Webtoken (JWT), das speziell für Tokenbroker von Microsoft first party ausgegeben wurde, um einmaliges Anmelden (Single Sign-On, SSO) für die Anwendungen zu aktivieren, die auf diesen Geräten verwendet werden. Weitere Informationen dazu, wie ein PRT auf Windows 10-Geräten ausgegeben, verwendet und geschützt wird, finden Sie unter [Was ist ein primäres Aktualisierungstoken?](https://docs.microsoft.com/azure/active-directory/devices/concept-primary-refresh-token).

**WamDefaultSet: JA und AzureADPrt: JA**

Diese Felder geben an, ob sich der Benutzer erfolgreich bei Azure AD authentifiziert hat, wenn er sich beim Gerät anmeldet. Wenn die Werte **NO sind,** kann dies auf:

- Ungültiger Speicherschlüssel im TPM, das dem Gerät bei der Registrierung zugeordnet ist (überprüfen Sie den KeySignTest während der Ausführung mit erhöhten Rechten)
- Alternative Anmelde-ID
- HTTP-Proxy nicht gefunden

Informationen zur Problembehandlung von Geräten mithilfe des Befehls dsregcmd finden Sie unter [SSO-Status](https://docs.microsoft.com/azure/active-directory/devices/troubleshoot-device-dsregcmd#sso-state).
