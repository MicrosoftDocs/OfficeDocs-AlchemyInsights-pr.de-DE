---
title: Behandeln von Problemen bei der Registrierung von Windows-Geräten in Microsoft Intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 20e9bd42-2db0-4dd7-b480-966571494dd9
ms.custom:
- "784"
- "6200002"
ms.openlocfilehash: a456cc8f2336e6b902de0b7873cb233f4b846140
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 04/15/2021
ms.locfileid: "51808970"
---
# <a name="troubleshoot-issues-with-enrolling-windows-devices-in-microsoft-intune"></a><span data-ttu-id="553b5-102">Behandeln von Problemen bei der Registrierung von Windows-Geräten in Microsoft Intune</span><span class="sxs-lookup"><span data-stu-id="553b5-102">Troubleshoot issues with enrolling Windows devices in Microsoft Intune</span></span>

<span data-ttu-id="553b5-103">Überprüfen Sie die unten aufgeführten Ressourcen, um Ihr Problem jetzt zu beheben.</span><span class="sxs-lookup"><span data-stu-id="553b5-103">Review the resources listed below to resolve your issue now.</span></span>
  
<span data-ttu-id="553b5-104">Einige häufige Fehlermeldungen und Lösungsschritte:</span><span class="sxs-lookup"><span data-stu-id="553b5-104">Some common error messages and resolution steps:</span></span>
  
 <span data-ttu-id="553b5-105">**Die Software kann nicht installiert werden, 0x80cf4017:** Ihr Kontozertifikat ist abgelaufen.</span><span class="sxs-lookup"><span data-stu-id="553b5-105">**The software cannot be installed, 0x80cf4017:** Your account certificate has expired.</span></span> <span data-ttu-id="553b5-106">Laden Sie das PC-Client-Softwarepaket erneut in der Intune Admin Console herunter.</span><span class="sxs-lookup"><span data-stu-id="553b5-106">Re-download the PC Client software package in the Intune Admin Console.</span></span> <span data-ttu-id="553b5-107">Weitere Informationen finden Sie in dieser Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="553b5-107">Review this documentation for more information.</span></span>
  
 <span data-ttu-id="553b5-108">**Fehlercode 0x801c0003:** Der Fehler kann in den folgenden Szenarien auftreten:</span><span class="sxs-lookup"><span data-stu-id="553b5-108">**Error code 0x801c0003:** The error can occur in the following scenarios:</span></span>
  
-  <span data-ttu-id="553b5-109">Der Benutzer hat mehr Geräte als das Gerätelimit registriert.</span><span class="sxs-lookup"><span data-stu-id="553b5-109">The user has more devices enrolled than the device limit.</span></span> <span data-ttu-id="553b5-110">Überprüfen Sie diese Dokumente, [um ein Gerät zu entfernen oder](https://docs.microsoft.com/intune/devices-wipe) das [Gerätelimit zu ändern.](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions)</span><span class="sxs-lookup"><span data-stu-id="553b5-110">Review these documents to [remove a device](https://docs.microsoft.com/intune/devices-wipe) or [change the device limit](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).</span></span>

-  <span data-ttu-id="553b5-111">"Benutzer können Geräte zu Azure AD beitreten" ist auf "keine" festgelegt.</span><span class="sxs-lookup"><span data-stu-id="553b5-111">"Users may join devices to Azure AD" is set to "none."</span></span> <span data-ttu-id="553b5-112">Legen Sie es auf alle Benutzer oder wählen Sie Benutzer aus.</span><span class="sxs-lookup"><span data-stu-id="553b5-112">Set it to all or select users.</span></span> <span data-ttu-id="553b5-113">Weitere [Informationen finden](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) Sie in dieser Dokumentation.</span><span class="sxs-lookup"><span data-stu-id="553b5-113">Review [this documentation](https://docs.microsoft.com/azure/active-directory/device-management-azure-portal#configure-device-settings) for more information.</span></span>

-  <span data-ttu-id="553b5-114">Das Gerät wurde bereits von einem anderen Benutzer registriert.</span><span class="sxs-lookup"><span data-stu-id="553b5-114">The device is already enrolled by another user.</span></span> <span data-ttu-id="553b5-115">Wenn dies der Fall ist, entfernen Sie das Gerät aus der Azure Intune-Konsole, oder entrollen Sie das Gerät manuell, bevor Sie es erneut versuchen.</span><span class="sxs-lookup"><span data-stu-id="553b5-115">If that's the case, remove the device from the Azure Intune console or manually unenroll the device before trying again.</span></span>

-  <span data-ttu-id="553b5-116">Das Gerät ist Windows 10 Home.</span><span class="sxs-lookup"><span data-stu-id="553b5-116">The device is Windows 10 Home.</span></span> <span data-ttu-id="553b5-117">Nur Windows 10 Pro-, Education- und Enterprise-SKUs können Azure Active Directory beitreten.</span><span class="sxs-lookup"><span data-stu-id="553b5-117">Only Windows 10 Pro, Education and Enterprise SKUs can join Azure Active Directory.</span></span>

<span data-ttu-id="553b5-118">Zusätzliche Ressourcen zur Lösung Ihres Problems:</span><span class="sxs-lookup"><span data-stu-id="553b5-118">Additional resources to help resolve your issue:</span></span>
  
-  <span data-ttu-id="553b5-119">Verwenden [Sie das Intune-Problembehandlungsportal,](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) um häufige Registrierungsfehler zu diagnostizieren und zu beheben.</span><span class="sxs-lookup"><span data-stu-id="553b5-119">Use [Intune Troubleshooting Portal](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) to diagnose and resolve common enrollment failures.</span></span> <span data-ttu-id="553b5-120">Weitere [Informationen finden](https://docs.microsoft.com/intune/help-desk-operators) Sie in diesem Dokument.</span><span class="sxs-lookup"><span data-stu-id="553b5-120">Review [this document](https://docs.microsoft.com/intune/help-desk-operators) for more details.</span></span>

-  <span data-ttu-id="553b5-121">Sehen Sie sich diese Dokumente an, um eine Liste häufig auftretender Fehler, die die Registrierung verhindern, sowie Lösungen dafür zu finden: [Anleitung zur Problembehandlung](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) und [Problembehandlungsdokument](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-device-enrollment-in-intune).</span><span class="sxs-lookup"><span data-stu-id="553b5-121">Review these documents for a list of common errors that prevent enrollment and resolutions to each: [Troubleshooting guide](https://support.microsoft.com/help/4089533/troubleshooting-windows-device-enrollment-problems-in-microsoft-intune) and [Troubleshooting doc](https://docs.microsoft.com/troubleshoot/mem/intune/troubleshoot-device-enrollment-in-intune).</span></span>

<span data-ttu-id="553b5-122">[Erfahren Sie, wie Sie Windows-Geräte in Microsoft Intune registrieren.](https://docs.microsoft.com/intune/windows-enroll)</span><span class="sxs-lookup"><span data-stu-id="553b5-122">[Learn how to enroll Windows devices in Microsoft Intune](https://docs.microsoft.com/intune/windows-enroll).</span></span>
