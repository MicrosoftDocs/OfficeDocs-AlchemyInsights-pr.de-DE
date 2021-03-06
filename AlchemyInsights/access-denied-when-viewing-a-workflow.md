---
title: Zugriff verweigert beim Anzeigen eines Workflows
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 710775e8b2dee98969df7a4c8410a3e61181aaf6
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/14/2020
ms.locfileid: "47688801"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Zugriff verweigert beim Anzeigen eines Workflows

SharePoint 2013 Workflows, die versuchen, eine e-Mail an eine SharePoint-Gruppe zu senden, können mit der Fehlermeldung "Zugriff verweigert" fehlschlagen, wenn die Mitgliedschaft in der SharePoint-Gruppe nicht auf jeder festgelegt ist.
  
 **Führen Sie die folgenden Schritte aus, um dieses Problem zu beheben:**
  
 1. Lassen Sie alle Mitglieder der SharePoint-Gruppe anzeigen.
  
 2. Entfernen Sie die SharePoint-Gruppe aus der an-oder CC-Zeile der e-Mail.
  
 3. Fügen Sie die Benutzer explizit zur Zeile "an" oder "CC" hinzu, wenn die Mitgliedschafts Sichtbarkeit für SharePoint-Gruppe nicht geändert werden kann.
  
Weitere Informationen finden Sie unter [http Authorized to/_vti_bin/Client.svc/SP.Utilities.Utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  