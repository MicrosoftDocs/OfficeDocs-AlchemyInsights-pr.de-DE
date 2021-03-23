---
title: Freigeben von Speicherplatz in Windows 10
ms.author: pebaum
author: pebaum
manager: dansimp
ms.date: 03/16/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9771"
- "9005403"
ms.openlocfilehash: 3838f3db3bc5f54bcb1a2558484056f3194b76e1
ms.sourcegitcommit: c08bed4071baa3bb5879496df3ed44fb828c8367
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/19/2021
ms.locfileid: "50898350"
---
# <a name="free-up-drive-space-in-windows-10"></a><span data-ttu-id="6ef9a-102">Freigeben von Speicherplatz in Windows 10</span><span class="sxs-lookup"><span data-stu-id="6ef9a-102">Free up drive space in Windows 10</span></span>

<span data-ttu-id="6ef9a-103">Hier finden Sie zwei Optionen, um Speicherplatz in Windows freizugeben:</span><span class="sxs-lookup"><span data-stu-id="6ef9a-103">Here are two options to free up drive space in Windows:</span></span>

- <span data-ttu-id="6ef9a-104">Geben Sie Speicherplatz in Windows 10 frei.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-104">Free up drive space in Windows 10.</span></span>
- <span data-ttu-id="6ef9a-105">Geben Sie Speicherplatz für Windows 10-Updates mit einem externen Speichergerät frei.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-105">Free up space for Windows 10 updates with external storage device.</span></span>

<span data-ttu-id="6ef9a-106">Wenn Sie nach der Verwendung der Datenträgerbereinigung immer noch wenig Speicherplatz haben, füllt sich Ihr Ordner für temporäre Dateien möglicherweise schnell mit Anwendungsdateien (.appx), die vom Microsoft Store verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-106">If you still have low disk space after using Disk Cleanup, it’s possible that your Temp folder is quickly filling up with application (.appx) files used by Microsoft Store.</span></span> <span data-ttu-id="6ef9a-107">Um dieses Problem zu beheben, setzen Sie den Store zurück, löschen Sie den Store-Cache und führen Sie dann die Windows Update-Problembehandlung durch.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-107">To fix this problem, reset the Store, clear the Store cache, and then run the Windows Update troubleshooter.</span></span> <span data-ttu-id="6ef9a-108">Stellen Sie sicher, dass der Microsoft Store geschlossen ist, bevor Sie mit diesen Schritten fortfahren.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-108">Make sure Microsoft Store is closed before you proceed with these steps.</span></span>

<span data-ttu-id="6ef9a-109">**Schritt 1: Zurücksetzen des Microsoft Store**</span><span class="sxs-lookup"><span data-stu-id="6ef9a-109">**Step 1: Reset Microsoft Store**</span></span>

<span data-ttu-id="6ef9a-110">**Hinweis**: Dies löscht die App-Daten auf dem Gerät endgültig, einschließlich Ihrer Einstellungen und Anmeldedetails.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-110">**Note** This permanently deletes the app data on the device, including your preferences and sign-in details.</span></span>

1. <span data-ttu-id="6ef9a-111">Wählen Sie **Start** > **Einstellungen** > **Apps** > **Apps & Features** aus.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-111">Select **Start** > **Settings** > **Apps** > **Apps & features**.</span></span>

1. <span data-ttu-id="6ef9a-112">Suchen Sie in der Liste der Apps den Microsoft Store und wählen Sie ihn aus.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-112">In the list of apps, locate and select Microsoft Store.</span></span>

1. <span data-ttu-id="6ef9a-113">Wählen Sie **Erweiterte Optionen** aus.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-113">Select **Advanced options**.</span></span>

1. <span data-ttu-id="6ef9a-114">Blättern Sie nach unten und wählen Sie **Zurücksetzen** aus und dann **Zurücksetzen bestätigen**.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-114">Scroll down and select **Reset**, and then **Confirm Reset**.</span></span>

<span data-ttu-id="6ef9a-115">**Schritt 2: Löschen des Microsoft Store-Cache**</span><span class="sxs-lookup"><span data-stu-id="6ef9a-115">**Step 2: Clear the Microsoft Store cache**</span></span>

1. <span data-ttu-id="6ef9a-116">Drücken Sie die WINDOWS-TASTE+R, um das Dialogfeld „Ausführen“ zu öffnen.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-116">Press the Windows Logo Key + R to open the Run dialog box.</span></span>

1. <span data-ttu-id="6ef9a-117">Geben Sie wsreset.exe ein und wählen Sie **OK**.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-117">Type wsreset.exe and select **OK**.</span></span>

1. <span data-ttu-id="6ef9a-118">Ein leeres Eingabeaufforderungsfenster wird geöffnet.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-118">A blank Command Prompt window opens.</span></span> <span data-ttu-id="6ef9a-119">Nach ungefähr 10 Sekunden schließt sich das Fenster und der Store wird automatisch geöffnet.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-119">After about 10 seconds, the window closes and the Store opens automatically.</span></span>

<span data-ttu-id="6ef9a-120">**Schritt 3: Zurücksetzen von Windows Update**</span><span class="sxs-lookup"><span data-stu-id="6ef9a-120">**Step 3: Reset Windows Update**</span></span>

1. <span data-ttu-id="6ef9a-121">Wählen Sie **Start** > **Einstellungen** > **Update & Sicherheit** > **Problembehandlung** aus.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-121">Select **Start** > **Settings** > **Update & Security** > **Troubleshoot**.</span></span>

1. <span data-ttu-id="6ef9a-122">Blättern Sie nach unten und wählen Sie **Windows Update** aus der Liste aus, und wählen Sie **Problembehandlung ausführen** aus.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-122">Scroll down and select **Windows Update** from the list, and select **Run the troubleshooter**.</span></span>

1. <span data-ttu-id="6ef9a-123">Starten Sie Ihren Computer neu und prüfen Sie, ob das Problem weiterhin auftritt.</span><span class="sxs-lookup"><span data-stu-id="6ef9a-123">Reboot your computer and check whether you're still experiencing the issue.</span></span>
