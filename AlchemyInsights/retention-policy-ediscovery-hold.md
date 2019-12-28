---
title: 2609-Retention-oder-eDiscovery-Hold
ms.author: markjjo
author: markjjo
manager: lauraw
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2609"
- "9000048"
ms.openlocfilehash: 85c41995545efd8e1526d9f7dce4a23929f85be5
ms.sourcegitcommit: 24e8248b0f061a76af50bf566d7a13fc24d29d99
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 11/05/2019
ms.locfileid: "37994064"
---
# <a name="unable-to-delete-items-in-sharepoint-online-or-onedrive-for-business"></a><span data-ttu-id="f1c44-102">Elemente konnten in SharePoint Online oder OneDrive für Unternehmen nicht gelöscht werden.</span><span class="sxs-lookup"><span data-stu-id="f1c44-102">Unable to delete items in SharePoint Online or OneDrive for Business</span></span>

<span data-ttu-id="f1c44-103">Möglicherweise können Sie oder Ihre Benutzer keine Elemente in SharePoint Online oder OneDrive für Unternehmen löschen, da eine Aufbewahrungsrichtlinie, eine Aufbewahrungs Bezeichnung oder ein eDiscovery-Speicher auf eine SharePoint-Website von OneDrive oder auf ein bestimmtes Element angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="f1c44-103">You or your users may be unable to delete items in SharePoint Online or OneDrive for Business because a retention policy, retention label, or eDiscovery hold is applied to a SharePoint of OneDrive site or to a specific item.</span></span> <span data-ttu-id="f1c44-104">Dazu gehört auch, dass Sie ein Dokument, eine Dokumentversion, einen Ordner, eine Dokumentbibliothek, eine Liste, eine APP, eine Website oder eine Websitesammlung nicht löschen können.</span><span class="sxs-lookup"><span data-stu-id="f1c44-104">This includes being unable to delete a document, a document version, a folder, a document library, a list, an app, a site, or a site collection.</span></span> <span data-ttu-id="f1c44-105">Im folgenden finden Sie einige Beispiele für Fehlermeldungen, die Sie erhalten können, wenn Sie versuchen, ein Element zu löschen, das beibehalten wird:</span><span class="sxs-lookup"><span data-stu-id="f1c44-105">Here are some examples of the error messages you may received if you try to delete an item that is being retained:</span></span>

- <span data-ttu-id="f1c44-106">"Diese Website kann nicht gelöscht werden, da Sie in einer eDiscovery-halte-oder Aufbewahrungsrichtlinie enthalten ist."</span><span class="sxs-lookup"><span data-stu-id="f1c44-106">"This site cannot be deleted because it is included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="f1c44-107">"Auf dieser Website ist eine Konformitätsrichtlinie zum Blockieren des Löschvorgangs festgelegt."</span><span class="sxs-lookup"><span data-stu-id="f1c44-107">"This site has a compliance policy set to block deletion"</span></span>
- <span data-ttu-id="f1c44-108">"Eine Konformitätsrichtlinie blockiert derzeit die Löschung dieser Website"</span><span class="sxs-lookup"><span data-stu-id="f1c44-108">"A compliance policy is currently blocking this site deletion"</span></span>
- <span data-ttu-id="f1c44-109">"Diese Websitesammlung kann nicht gelöscht werden, da Sie Websites enthält, die in einer eDiscovery-halte-oder Aufbewahrungsrichtlinie enthalten sind."</span><span class="sxs-lookup"><span data-stu-id="f1c44-109">"This site collection can’t be deleted because it contains sites that are included in an eDiscovery hold or retention policy"</span></span>
- <span data-ttu-id="f1c44-110">"Sie müssen alle Elemente in diesem Ordner löschen, bevor Sie den Ordner löschen."</span><span class="sxs-lookup"><span data-stu-id="f1c44-110">"You have to delete all the items in this folder before you delete the folder"</span></span>
- <span data-ttu-id="f1c44-111">"Versionen dieses Elements können nicht gelöscht werden, da es gespeichert ist oder Aufbewahrungsrichtlinie"</span><span class="sxs-lookup"><span data-stu-id="f1c44-111">"Versions of this item cannot be deleted because it is on hold or retention policy"</span></span>
- <span data-ttu-id="f1c44-112">"Element kann nicht gelöscht werden, während es gespeichert wird"</span><span class="sxs-lookup"><span data-stu-id="f1c44-112">"Item cannot be deleted while on hold"</span></span>
- <span data-ttu-id="f1c44-113">"Die Beschriftung, die auf dieses Element angewendet wird, verhindert, dass Sie bearbeitet oder gelöscht wird."</span><span class="sxs-lookup"><span data-stu-id="f1c44-113">"The label that's applied to this item prevents it from being edited or deleted"</span></span>
- <span data-ttu-id="f1c44-114">"Liste kann nicht gelöscht werden, wenn Sie gespeichert ist oder Aufbewahrungsrichtlinie"</span><span class="sxs-lookup"><span data-stu-id="f1c44-114">"List cannot be deleted while on hold or retention policy"</span></span>
- <span data-ttu-id="f1c44-115">"Die Liste kann nicht gelöscht werden, wenn Sie blockiert wird oder wenn eine Aufbewahrungsrichtlinie auf Sie angewendet wird."</span><span class="sxs-lookup"><span data-stu-id="f1c44-115">"The list cannot be deleted if it is blocked or if a retention policy is applied to it"</span></span>

<span data-ttu-id="f1c44-116">Zum Löschen von Elementen in einem dieser Szenarien müssen die Aufbewahrungsrichtlinie, die Aufbewahrungs Bezeichnung oder der eDiscovery-Speicher entfernt werden (oder eine Website muss von einer Aufbewahrungsrichtlinie ausgeschlossen werden).</span><span class="sxs-lookup"><span data-stu-id="f1c44-116">To delete items in one of these scenarios, the retention policy, retention label, or eDiscovery hold has to be removed (or a site has to be excluded from a retention policy).</span></span> <span data-ttu-id="f1c44-117">Sie müssen entweder deaktivieren oder den entsprechenden Haltebereich ausschließen, der dieses Problem verursacht.</span><span class="sxs-lookup"><span data-stu-id="f1c44-117">You need to either disable or exclude respective hold that's causing this issue.</span></span> <span data-ttu-id="f1c44-118">Nach dem Entfernen einer Aufbewahrungsrichtlinie oder eines Haltestatus kann es bis zu 24 Stunden dauern, bis die Änderung wirksam wird.</span><span class="sxs-lookup"><span data-stu-id="f1c44-118">After a retention policy or hold is removed, it may take up to 24 hours for the change to take effect.</span></span> 

<span data-ttu-id="f1c44-119">Informationen zu den verschiedenen Archivierungs-und Aufbewahrungsfunktionen, die auf SharePoint-Websites und OneDrive-Konten angewendet werden können, finden Sie in einem der folgenden Themen.</span><span class="sxs-lookup"><span data-stu-id="f1c44-119">For information about about the different retention and hold features that can be applied to SharePoint sites and OneDrive accounts, see one of the following topics.</span></span>

- [<span data-ttu-id="f1c44-120">Übersicht über Aufbewahrungsrichtlinien</span><span class="sxs-lookup"><span data-stu-id="f1c44-120">Overview of retention policies</span></span>](https://docs.microsoft.com/microsoft-365/compliance/retention-policies)

- [<span data-ttu-id="f1c44-121">Übersicht über Aufbewahrungsbezeichnungen</span><span class="sxs-lookup"><span data-stu-id="f1c44-121">Overview of retention labels</span></span>](https://docs.microsoft.com/microsoft-365/compliance/labels)

- [<span data-ttu-id="f1c44-122">Manage Holds in Advanced eDiscovery</span><span class="sxs-lookup"><span data-stu-id="f1c44-122">Manage holds in Advanced eDiscovery</span></span>](https://docs.microsoft.com/microsoft-365/compliance/managing-holds)

- [<span data-ttu-id="f1c44-123">eDiscovery-Aufbewahrung</span><span class="sxs-lookup"><span data-stu-id="f1c44-123">eDiscovery holds</span></span>](https://docs.microsoft.com/microsoft-365/compliance/ediscovery-cases#step-4-place-content-locations-on-hold)

- [<span data-ttu-id="f1c44-124">Veraltete Website Schließungs-und Löschrichtlinien</span><span class="sxs-lookup"><span data-stu-id="f1c44-124">Legacy site closure and deletion policies</span></span>](https://support.office.com/article/Use-policies-for-site-closure-and-deletion-A8280D82-27FD-48C5-9ADF-8A5431208BA5)