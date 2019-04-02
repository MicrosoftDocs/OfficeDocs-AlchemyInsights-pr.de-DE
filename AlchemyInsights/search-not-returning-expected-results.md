---
title: 1491-Suche-nicht-Rückgabe-erwartete-Ergebnisse
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 1491
ms.assetid: ''
ms.openlocfilehash: 517d9b75fc3aef09c0c2d5870aa695cc0ab10f06
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776081"
---
# <a name="content-search-not-returning-expected-results"></a><span data-ttu-id="b77f6-102">Die Inhaltssuche gibt keine erwarteten Ergebnisse zurück</span><span class="sxs-lookup"><span data-stu-id="b77f6-102">Content Search not returning expected results</span></span>

<span data-ttu-id="b77f6-103">Wenn Sie die Inhaltssuche im Office 365 Security & Compliance Center durchführen, werden möglicherweise unerwartete Suchergebnisse angezeigt.</span><span class="sxs-lookup"><span data-stu-id="b77f6-103">When running Content Searches from the Office 365 Security & Compliance Center, you may receive unexpected search results.</span></span> <span data-ttu-id="b77f6-104">Berücksichtigen Sie die folgenden Aspekte, die sich auf Ihre Suchergebnisse auswirken können:</span><span class="sxs-lookup"><span data-stu-id="b77f6-104">Consider the following things that can affect your search results:</span></span>

- <span data-ttu-id="b77f6-105">**Inhaltsspeicherorte und Suchbedingungen**: Vergewissern Sie sich, dass Sie die richtigen inhaltsspeicherorte und Suchbedingungen ausgewählt haben.</span><span class="sxs-lookup"><span data-stu-id="b77f6-105">**Content locations and search conditions**: Make sure you have selected the proper content locations and search conditions.</span></span> <span data-ttu-id="b77f6-106">Wenn Sie eine große Suche (mit vielen Speicherorten) ausgeführt haben, sollten Sie Sie in mehrere Suchvorgänge aufteilen.</span><span class="sxs-lookup"><span data-stu-id="b77f6-106">If you ran a large search (with many locations), consider splitting it into multiple searches.</span></span>

- <span data-ttu-id="b77f6-107">**Teilweise indizierte Elemente**: [teilweise indizierte Elemente](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) aus Postfächern sind in den geschätzten Suchergebnissen enthalten.</span><span class="sxs-lookup"><span data-stu-id="b77f6-107">**Partially indexed items**:  [Partially indexed items](https://docs.microsoft.com/office365/securitycompliance/partially-indexed-items-in-content-search) from mailboxes are included in the estimated search results.</span></span> <span data-ttu-id="b77f6-108">Teilweise indizierte Elemente aus Websites in SharePoint und OneDrive sind jedoch nicht in der Such Schätzung enthalten.</span><span class="sxs-lookup"><span data-stu-id="b77f6-108">However, partially indexed items from sites in SharePoint and OneDrive aren't included in the search estimate.</span></span>

- <span data-ttu-id="b77f6-109">**Such**Fehler: beim Durchsuchen einer hohen Anzahl von Postfächern (über 100.000 Postfächer) können Suchfehler mit Fehlercodes wie CS008-009 und CS012-002 angezeigt werden.</span><span class="sxs-lookup"><span data-stu-id="b77f6-109">**Search failures**: When searching a large number of mailboxes (over 100,000 mailboxes), you may get search errors, with error codes such as CS008-009 and CS012-002).</span></span> <span data-ttu-id="b77f6-110">Wiederholen Sie in diesem Fall die Suche nur für die fehlerhaften inhaltsspeicherorte.</span><span class="sxs-lookup"><span data-stu-id="b77f6-110">In this case, retry the search only for the failed content locations.</span></span> <span data-ttu-id="b77f6-111">Weitere Informationen finden Sie in [diesem Artikel](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) .</span><span class="sxs-lookup"><span data-stu-id="b77f6-111">See  [this article](https://docs.microsoft.com/office365/securitycompliance/retry-failed-content-search) for more information.</span></span>