---
title: Anweisungen zum Ausblenden/Entfernen einer Gruppe aus der Adressliste
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
- "1200024"
- "3161"
ms.openlocfilehash: 4d55866700b9b8494f1f692cd3b865116b96a1bc
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51831877"
---
# <a name="hide-microsoft-365-group-from-address-list-gal"></a><span data-ttu-id="fb5b0-102">Ausblenden der Microsoft 365-Gruppe aus der Adressliste (GAL)</span><span class="sxs-lookup"><span data-stu-id="fb5b0-102">Hide Microsoft 365 group from address list (GAL)</span></span>

<span data-ttu-id="fb5b0-103">Verwenden Sie den folgenden Befehl in der EXO-Shell, um eine Microsoft 365-Gruppe aus Adresslisten (GAL) von Exchange-Clients (z. B. Outlook oder OWA) auszublenden:</span><span class="sxs-lookup"><span data-stu-id="fb5b0-103">To hide a Microsoft 365 group from address lists (GAL) of Exchange clients (such as Outlook or OWA), use the following command in EXO shell:</span></span>

`Set-UnifiedGroup -Identity GroupName -HiddenFromAddressListsEnabled:$true`

<span data-ttu-id="fb5b0-104">Verwenden Sie den folgenden Befehl in der EXO-Shell, um die Microsoft 365-Gruppe für Exchange-Clients nicht sichtbar zu machen:</span><span class="sxs-lookup"><span data-stu-id="fb5b0-104">To hide the Microsoft 365 group from being visible to Exchange clients, use the following command in EXO shell:</span></span>

`Set-unifiedGroup -Identity GroupName -HiddenFromExchangeClientsEnabled:$true
Check this article for detailed instructions`

