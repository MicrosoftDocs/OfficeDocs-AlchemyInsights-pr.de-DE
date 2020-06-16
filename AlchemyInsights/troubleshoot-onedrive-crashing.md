---
title: Fehlerbehandlung bei OneDrive-Abstürzen
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003084"
- "5885"
ms.openlocfilehash: 7fbc4617a0426eb11359339edc950a108f782750
ms.sourcegitcommit: 462522e6bccde76f6c46795b0eca71320c5d442d
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/15/2020
ms.locfileid: "44735390"
---
# <a name="troubleshoot-onedrive-crashes"></a><span data-ttu-id="5a8ab-102">Fehlerbehandlung bei OneDrive-Abstürzen</span><span class="sxs-lookup"><span data-stu-id="5a8ab-102">Troubleshoot OneDrive crashes</span></span>

<span data-ttu-id="5a8ab-103">Wenn OneDrive wiederholt abstürzt, versuchen Sie die folgenden Schritte zur Problembehandlung:</span><span class="sxs-lookup"><span data-stu-id="5a8ab-103">If OneDrive repeatedly crashes, try these troubleshooting steps:</span></span>

<span data-ttu-id="5a8ab-104">**Stellen Sie sicher, dass die Registrierungsschlüssel nicht festgelegt sind:**</span><span class="sxs-lookup"><span data-stu-id="5a8ab-104">**Ensure registry keys aren’t set:**</span></span>

1. <span data-ttu-id="5a8ab-105">Navigieren Sie mithilfe des Registrierungs-Editors zu HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\OneDrive</span><span class="sxs-lookup"><span data-stu-id="5a8ab-105">Using Registry Editor, navigate to HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\OneDrive</span></span>
2. <span data-ttu-id="5a8ab-106">Wenn „DisableFileSyncNGSC“ vorhanden und auf „1“ festgelegt ist, öffnen Sie den Schlüssel und ändern Sie den Wert auf „0“.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-106">If DisableFileSyncNGSC is present and set to 1, open the key and change the value to 0.</span></span>
3. <span data-ttu-id="5a8ab-107">Starten Sie OneDrive manuell, indem Sie zu „Start“ wechseln.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-107">Manually launch OneDrive by going to Start</span></span> ![Drücken Sie die WINDOWS-TASTE,](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAOCAYAAADJ7fe0AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAADxSURBVDhPY/wPBAx4wR+Gd6/fM7x9/ZTh9ZuXDGdPnWE4tH0rw/UHDxlaVp9kCDCSYWABKfv35wfD+/cfGV4+fcLw5uVjhlOXzzFsX/qWYebmZAZPWWOGO2DD8ACQS9Y3e4Bcg4Y9/t94fPa/CoY4Aq8/+xik/T8TkEMxGDyGgANWwSqeobvbGSyAADIM3BwCDKXd3QyfoCLoQEGAA0xTxSWjsYMJwLHjkruU4UXSJ4YnT54x3Dh/luHmjfMMmw9wMjCDlRAGBDPgjy8fGT5//8rw9P4Thge3zzNcvXmDYevmfQzXb1xlmH/0ATADyjAAAKdWkD3ZSwNeAAAAAElFTkSuQmCC)<span data-ttu-id="5a8ab-109">geben Sie im Suchfeld den Namen OneDrive ein und klicken Sie dann auf die OneDrive Desktop-App.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-109">, type OneDrive in the search box, and then click on the OneDrive desktop app.</span></span>

<span data-ttu-id="5a8ab-110">**OneDrive zurücksetzen:**</span><span class="sxs-lookup"><span data-stu-id="5a8ab-110">**Reset OneDrive:**</span></span>

<span data-ttu-id="5a8ab-111">Hinweise:</span><span class="sxs-lookup"><span data-stu-id="5a8ab-111">Notes:</span></span>

- <span data-ttu-id="5a8ab-112">Beim Zurücksetzen von OneDrive werden alle Ihre bestehenden Synchronisierungsverbindungen (einschließlich – sofern eingerichtet – Ihr persönliches OneDrive) getrennt.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-112">Resetting OneDrive disconnects all your existing sync connections (including your personal OneDrive if set up).</span></span>
- <span data-ttu-id="5a8ab-113">Wenn Sie OneDrive auf Ihrem Computer zurücksetzen, gehen keine Dateien oder Daten verloren.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-113">You won't lose files or data by resetting OneDrive on your computer.</span></span>

<span data-ttu-id="5a8ab-114">**Zurücksetzen von OneDrive:**</span><span class="sxs-lookup"><span data-stu-id="5a8ab-114">**To reset OneDrive:**</span></span>

1. <span data-ttu-id="5a8ab-115">Öffnen Sie ein Dialogfeld „Ausführen“, indem Sie die WINDOWS-TASTE und R drücken.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-115">Open a Run dialog by pressing Windows key    and R.</span></span>
2. <span data-ttu-id="5a8ab-116">Geben Sie „%localappdata%\Microsoft\OneDrive\onedrive.exe /reset“ ein und klicken Sie auf OK.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-116">Type %localappdata%\Microsoft\OneDrive\onedrive.exe /reset and press OK.</span></span> <span data-ttu-id="5a8ab-117">Möglicherweise wird ein Befehlsfenster kurz eingeblendet.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-117">A Command window may appear briefly.</span></span>
3. <span data-ttu-id="5a8ab-118">Starten Sie OneDrive manuell, indem Sie zu „Start“ wechseln.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-118">Manually launch OneDrive by going to Start</span></span> ![Drücken Sie die WINDOWS-TASTE,](data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABEAAAAOCAYAAADJ7fe0AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsQAAA7EAZUrDhsAAADxSURBVDhPY/wPBAx4wR+Gd6/fM7x9/ZTh9ZuXDGdPnWE4tH0rw/UHDxlaVp9kCDCSYWABKfv35wfD+/cfGV4+fcLw5uVjhlOXzzFsX/qWYebmZAZPWWOGO2DD8ACQS9Y3e4Bcg4Y9/t94fPa/CoY4Aq8/+xik/T8TkEMxGDyGgANWwSqeobvbGSyAADIM3BwCDKXd3QyfoCLoQEGAA0xTxSWjsYMJwLHjkruU4UXSJ4YnT54x3Dh/luHmjfMMmw9wMjCDlRAGBDPgjy8fGT5//8rw9P4Thge3zzNcvXmDYevmfQzXb1xlmH/0ATADyjAAAKdWkD3ZSwNeAAAAAElFTkSuQmCC)<span data-ttu-id="5a8ab-120">geben Sie im Suchfeld den Namen OneDrive ein und klicken Sie dann auf die OneDrive Desktop-App.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-120">, type OneDrive in the search box, and then click on the OneDrive desktop app.</span></span>

<span data-ttu-id="5a8ab-121">Hinweise:</span><span class="sxs-lookup"><span data-stu-id="5a8ab-121">Notes:</span></span>

- <span data-ttu-id="5a8ab-122">Wenn Sie vor dem Zurücksetzen ausgewählt hatten, dass nur einige Ordner synchronisiert werden sollen, müssen Sie dies nach Abschluss der Synchronisierung erneut tun.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-122">If you had chosen to sync only some folders before the reset, you will need to do that again once sync has completed.</span></span> <span data-ttu-id="5a8ab-123">Weitere Informationen finden Sie unter  [Auswählen der OneDrive-Ordner, die mit Ihrem Computer synchronisiert werden sollen](https://support.office.com/article/98b8b011-8b94-419b-aa95-a14ff2415e85) .</span><span class="sxs-lookup"><span data-stu-id="5a8ab-123">Read [Choose which OneDrive folders to sync to your computer](https://support.office.com/article/98b8b011-8b94-419b-aa95-a14ff2415e85) for more information.</span></span>
- <span data-ttu-id="5a8ab-124">Sie müssen dies für Ihr persönliches OneDrive und für OneDrive for Business ausführen.</span><span class="sxs-lookup"><span data-stu-id="5a8ab-124">You will need to complete this for your personal OneDrive and OneDrive for Business.</span></span>