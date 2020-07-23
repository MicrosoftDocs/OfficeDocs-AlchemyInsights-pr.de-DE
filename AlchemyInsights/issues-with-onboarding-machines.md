---
title: Probleme mit dem Onboarding-Computern
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/14/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6023"
- "9002913"
ms.openlocfilehash: 19b516dc21472e2c80a8b9046f802b329d15e4d6
ms.sourcegitcommit: 45c2aaeee58c0be466b76c7f0cd71e796d3c8f76
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/15/2020
ms.locfileid: "45139025"
---
# <a name="issues-with-onboarding-machines"></a><span data-ttu-id="5425c-102">Probleme mit dem Onboarding-Computern</span><span class="sxs-lookup"><span data-stu-id="5425c-102">Issues with onboarding machines</span></span>

<span data-ttu-id="5425c-103">Möglicherweise haben Sie Probleme mit Onboarding-Computern beim MDATP-Dienst.</span><span class="sxs-lookup"><span data-stu-id="5425c-103">You might have issues with onboarding machines to MDATP service.</span></span> <span data-ttu-id="5425c-104">Wenn Sie auf den Endbenutzercomputer zugreifen können, führen Sie die folgenden Schritte aus:</span><span class="sxs-lookup"><span data-stu-id="5425c-104">If you can access the end-user machine, follow these steps:</span></span>

1. <span data-ttu-id="5425c-105">Laden Sie das [Clientverbindungsuntersuchung](https://aka.ms/mdatpanalyzer)-Diagnosetool herunter.</span><span class="sxs-lookup"><span data-stu-id="5425c-105">Download the [Client Connectivity Analyzer](https://aka.ms/mdatpanalyzer) diagnostic tool.</span></span>
2. <span data-ttu-id="5425c-106">Extrahieren Sie MDATPAnalyzer.cmd, und führen Sie es aus.</span><span class="sxs-lookup"><span data-stu-id="5425c-106">Extract and run MDATPAnalyzer.cmd.</span></span>
3. <span data-ttu-id="5425c-107">Suchen Sie das Diagnoseprotokoll im Ordner „MDATPClientAnalyzerResult“, dem gleichen Ordner, in dem das Untersuchungstool heruntergeladen wird.</span><span class="sxs-lookup"><span data-stu-id="5425c-107">Locate the diagnostic log in the folder called MDATPClientAnalyzerResult, the same folder where the Analyzer tool is downloaded.</span></span>
4. <span data-ttu-id="5425c-108">Überprüfen Sie die Protokolldatei „MDATPClientAnalyzer.txt“, um Probleme mit der Verbindung oder Internetproxyeinstellungen zu finden.</span><span class="sxs-lookup"><span data-stu-id="5425c-108">Review the log file, MDATPClientAnalyzer.txt, to find connectivity or internet proxy settings issues.</span></span>