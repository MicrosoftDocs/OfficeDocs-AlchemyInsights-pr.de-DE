---
title: 2419-nicht aktivierbar-Überwachung
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 2419
ms.assetid: ''
ms.openlocfilehash: 81fd8e33feb2f2b10b04cc7cdc746a8603aa366b
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 09/15/2020
ms.locfileid: "47767598"
---
# <a name="unable-to-enable-unified-auditing"></a>Die vereinheitlichte Überwachung kann nicht aktiviert werden.

Wenn Sie versuchen, die vereinheitlichte Überwachung für Ihre Organisation zu aktivieren, erhalten Sie möglicherweise eine ähnliche Fehlermeldung wie die folgende:

```
Request: /api/adminauditlogconfig/EnableUnifiedAuditLogIngestion Status code: 500 Exception message: {"Message":"The command you tried to run isn't currently allowed in your organization. To run this command, you first need to run the command: Enable-OrganizationCustomization."
```

Führen Sie die folgenden Schritte aus, um dieses Problem zu beheben:

1. Stellen [Sie eine Verbindung mit Exchange Online PowerShell her](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell).

2. Führen Sie das folgende Cmdlet aus:

   ```
   Enable-OrganizationCustomization
   ```

3. Warten Sie auf 60 Minuten, bis die vorherige Einstellung wirksam wird.

4. Führen Sie den folgenden Befehl in Exchange Online PowerShell aus:

   ```
   Set-AdminAuditLogConfig -UnifiedAuditLogIngestionEnabled $true
   ```

Weitere Informationen finden Sie in den folgenden Artikeln:

- [Verbinden mit Exchange Online PowerShell per mehrstufiger Authentifizierung](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)

-  [Aktivieren oder Deaktivieren der Überwachungsprotokollsuche](https://docs.microsoft.com/microsoft-365/compliance/turn-audit-log-search-on-or-off)
