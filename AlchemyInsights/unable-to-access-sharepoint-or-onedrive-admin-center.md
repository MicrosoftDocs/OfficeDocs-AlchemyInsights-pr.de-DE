---
title: Zugriff auf SharePoint oder OneDrive Admin Center nicht möglich
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
- "9001459"
- "5638"
ms.openlocfilehash: 7ba4a9c6995c03dd21e0e1aa387e407d41a08fb1
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51824434"
---
# <a name="unable-to-access-sharepoint-or-onedrive-admin-center"></a>Zugriff auf SharePoint oder OneDrive Admin Center nicht möglich

- Wenn Ihre SharePoint oder OneDrive Admin Center-Website nicht zugänglich oder nicht verfügbar ist, kann es ein vorübergehendes Serviceproblem geben, bei dem Benutzer beim Zugriff auf SharePoint-Websites oder OneDrive-Inhalte zeitweilige Verzögerungen oder Navigationsfehler feststellen. Schauen Sie im [Dienststatus-Dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) nach, ob Ihre Organisation davon betroffen ist.

- Globalen Administratoren und SharePoint-Administratoren muss eine SharePoint-Lizenz zugewiesen werden. Neu erstellte Konten, denen nur eine SharePoint-Lizenz oder nur die Administratorrolle zugewiesen wird, können Probleme beim Zugriff auf SharePoint feststellen, z. B. "Zugriff verweigert" oder "Benutzer nicht gefunden". Warten Sie mindestens 24 Stunden, bis die Synchronisierung zwischen unseren Systemen abgeschlossen ist. Wir verstehen, dass Ihnen 24 Stunden lang vorkommen mag. In vielen Fällen arbeiten wir bereits an einer Lösung.

- Benutzern von Privileged Identity Management ([PIM](https://docs.microsoft.com/azure/active-directory/privileged-identity-management/pim-how-to-add-role-to-user?tabs=new)) kann der Zugriff verweigert werden, wenn das Zeitfenster für den erlaubten Zugriff sehr klein ist, siehe [Zugriff auf PIM-Konten verweigert](https://docs.microsoft.com/sharepoint/troubleshoot/administration/access-denied-to-pim-user-accounts).