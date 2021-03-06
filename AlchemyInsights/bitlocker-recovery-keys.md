---
title: Bitlocker-Wiederherstellungsschlüssel
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1922"
- "9000220"
ms.openlocfilehash: ec90e412302c74748e253f2e5430fa4205466f0d
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51820285"
---
# <a name="accessing-bitlocker-recovery-keys"></a>Zugreifen auf Bitlocker-Wiederherstellungsschlüssel

Beim Konfigurieren der Intune Endpoint Protection-Richtlinie für Bitlockereinstellungen kann definiert werden, ob Bitlocker-Wiederherstellungsinformationen in Azure Active Directory gespeichert werden sollen.

Wenn diese Einstellung konfiguriert ist, sollten die gespeicherten Wiederherstellungsdaten für einen Intune-Administrator als Teil der Gerätedaten im Blatt Intune Devices auf zwei Arten sichtbar sein:

Geräte - Azure AD-Geräte -> "Gerät" ODER Geräte -> Alle Geräte -> "Device" -> Wiederherstellungsschlüssel

Wenn Administratorzugriff auf das Gerät selbst besteht, kann der Wiederherstellungsschlüssel (Password) durch Ausführen des folgenden Befehls an einer Eingabeaufforderung mit erhöhten Rechten angezeigt werden:

```
manage-bde -protectors c: -get
Example
Volume C: []
All Key Protectors
    TPM:
      ID: {8A5D13D6-7ED9-46C8-A74F-AC3ADF016EC8}
      PCR Validation Profile:
        0, 2, 4, 8, 9, 10, 11
    Numerical Password:
      ID: {DFA26333-XXXX-402C-YYYY-A8C40AF3ZZZZ}
      Password:
        393943-22222-281721-555554-577984-77777-194700-99999
```
Wenn das Gerät vor der Registrierung in Intune verschlüsselt wurde, wurde der Wiederherstellungsschlüssel möglicherweise dem "Microsoft Account" (MSA) zugeordnet, mit dem sich das Gerät während des OOBE-Prozesses anmeldete. Wenn dies der Fall war, sollten beim Zugriff und der Anmeldung mit dieser MSA die Geräte angezeigt werden, für die Wiederherstellungsschlüssel  https://onedrive.live.com/recoverykey gespeichert wurden.
 
Wenn das Gerät aufgrund der Konfiguration über eine domänenbasierte Gruppenrichtlinie verschlüsselt wurde, können die Wiederherstellungsinformationen im lokalen Active Directory gespeichert werden.

Wenn Sie die Endpoint Protection-Richtlinie so konfiguriert haben, dass der Wiederherstellungsschlüssel in Azure Active Directory gespeichert wird, der Schlüssel für ein bestimmtes Gerät jedoch nicht hochgeladen wurde, können Sie den Upload auslösen, indem Sie den Wiederherstellungsschlüssel für dieses Gerät aus der MEM-Konsole drehen. Weitere Informationen finden Sie unter [Rotate BitLocker recovery keys](https://docs.microsoft.com/mem/intune/protect/encrypt-devices#view-details-for-recovery-keys).

