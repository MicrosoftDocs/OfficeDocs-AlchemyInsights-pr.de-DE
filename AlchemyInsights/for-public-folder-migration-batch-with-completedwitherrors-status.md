---
title: Für Migrationsbatch für öffentliche Ordner mit Dem Status CompletedWithErrors
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
- "3500007"
- "3532"
ms.openlocfilehash: 9ed21bfb9069b56a4fc59b201bb3ad94c6bb6712
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51812463"
---
# <a name="for-public-folder-migration-batch-with-completedwitherrors-status"></a>Für Migrationsbatch für öffentliche Ordner mit Dem Status CompletedWithErrors

Führen Sie die folgenden Schritte aus, um den Batch zu vervollständigen, und überspringen Sie die großen/ungültigen Elemente: 
1. Genehmigen der übersprungenen Elemente im Migrationsbatch:

    `Set-MigrationBatch \<batchname> -ApproveSkippedItems` 
2. Verwenden Sie den folgenden Befehl, um die übersprungenen Elemente für Migrationsanforderungen zu genehmigen, die zwar synchronisiert, aber nicht abgeschlossen sind:

    `$pf=Get-PublicFolderMailboxMigrationRequest | Get-PublicFolderMailboxMigrationRequestStatistics -IncludeReport; ForEach ($i in $pf) {if ($i.LargeItemsEncountered -gt 0 -or $i.BadItemsEncountered -gt 0) {Set-PublicFolderMailboxMigrationRequest $i.Identity.IdentifyingGuid -SkippedItemApprovalTime $([DateTime]::UtcNow)}}`
3. Der Migrationsbatch und die Anforderungen sollten in wenigen Minuten fortgesetzt und abgeschlossen werden.

