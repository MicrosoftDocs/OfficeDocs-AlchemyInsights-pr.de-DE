---
title: Mehrere Objekte haben die gleiche E-Mail-Adresse als Identität
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1834"
- "9000247"
ms.openlocfilehash: 05fb43133bc68b71ccdbab44d28679a1f659e762
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47724614"
---
# <a name="multiple-objects-have-the-same-email-address-as-identity"></a>Mehrere Objekte haben die gleiche E-Mail-Adresse als Identität

**Mehrere Objekte**

Einer häufiger Grund für diesen Fehler ist, dass eine Outlook Web Access-Anforderung bei Vorhandensein mehrerer Objekte mit derselben E-Mail-Adresse als Identität nicht korrekt weitergeleitet werden kann. Um diese Objekte zu finden, führen Sie die folgenden Befehle aus:

· Get-Recipient <email address>

· Get-User <email address>

· Get-User <email address> -SoftDeletedUser

· Get-Contact <email address>

· Get-Mailbox <email address> -PublicFolder

· Get-Mailbox <email address> -IncludeSoftDeletedMailbox

· Get-Mailbox <email address> -InactiveMailboxOnly

Um das Problem zu beheben, entfernen Sie mehrere Objekte mit derselben E-Mail-Identität, und stellen Sie sicher, dass es immer nur ein einziges Objekt mit einer bestimmten E-Mail-Identität gibt und dass sein Empfängertyp "UserMailbox" ist.

**Dieselbe Adresse wird für Postfächer von Unternehmen und Privatpersonen verwendet**

Eine weitere Ursache ist, wenn dieselbe Adresse für Postfächer von Unternehmen und Privatkunden verwendet wird. In diesem Fall muss der Benutzer seinen primären Verbraucheralias ändern, bis Cafe dieses Szenario unterstützt. Dies ist ein permanenter Fehler, der nicht ohne Intervention verschwindet.

Ausführliche Informationen finden Sie unter [Ändern der E-Mail-Adresse oder Telefonnummer für Ihr Microsoft-Konto](https://support.microsoft.com/help/11545/microsoft-account-rename-your-personal-account).