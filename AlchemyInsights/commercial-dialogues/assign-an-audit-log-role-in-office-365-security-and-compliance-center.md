---
title: Zuweisen einer Überwachungsprotokoll-Rolle im Office 365 Security & Compliance Center
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/21/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7363"
- "9000722"
ms.openlocfilehash: 0eb470b6c17def5517db2f866ef40898b36662ed
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/11/2021
ms.locfileid: "50736848"
---
# <a name="assign-an-audit-log-role-in-the-office-365-security--compliance-center"></a><span data-ttu-id="e94b3-102">Zuweisen einer Überwachungsprotokoll-Rolle im Office 365 Security & Compliance Center</span><span class="sxs-lookup"><span data-stu-id="e94b3-102">Assign an Audit Log role in the Office 365 Security & Compliance Center</span></span>

<span data-ttu-id="e94b3-103">Einem Administrator muss in Exchange Online entweder die Rolle **Überwachungsprotokolle nur anzeigen** oder die Rolle **Überwachungsprotokolle** zugewiesen werden, damit er das Office 365-Überwachungsprotokoll durchsuchen kann.</span><span class="sxs-lookup"><span data-stu-id="e94b3-103">To search the Office 365 audit log, an administrator must be assigned the **View-Only Audit Logs** role or the **Audit Logs** role in Exchange Online.</span></span> <span data-ttu-id="e94b3-104">Standardmäßig sind diese Rollen den Rollengruppen „Complianceverwaltung“ und „Organisationsverwaltung“ zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="e94b3-104">These roles are assigned to the Compliance Management and Organization Management role groups by default.</span></span> <span data-ttu-id="e94b3-105">Globale Administratoren in Office 365 und Microsoft 365 sind automatisch Mitglieder der Rollengruppe „Organisationsverwaltung“.</span><span class="sxs-lookup"><span data-stu-id="e94b3-105">Global administrators in Office 365 and Microsoft 365 are automatically added as members of the Organization Management role group.</span></span>

<span data-ttu-id="e94b3-106">Damit ein Benutzer das Überwachungsprotokoll mit minimalen Rechten durchsuchen kann, erstellen Sie in Exchange Online eine benutzerdefinierte Rollengruppe, fügen ihr die Rolle **Überwachungsprotokolle nur anzeigen** oder die Rolle **Überwachungsprotokolle** hinzu und fügen den Benutzer dann als Mitglied der neuen Rollengruppe hinzu.</span><span class="sxs-lookup"><span data-stu-id="e94b3-106">To enable a user to search with the minimum level of privileges, create a custom role group in Exchange Online, add the **View-Only Audit Logs** role or **Audit Logs** role, and then add the user as a member of the new role group.</span></span>

<span data-ttu-id="e94b3-107">Weitere Informationen finden Sie unter [Verwalten von Rollengruppen in Exchange Online](https://docs.microsoft.com/Exchange/permissions-exo/role-groups) und [Durchsuchen des Überwachungsprotokolls im Security & Compliance Center](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance).</span><span class="sxs-lookup"><span data-stu-id="e94b3-107">For more information, see [Manage role groups in Exchange Online](https://docs.microsoft.com/Exchange/permissions-exo/role-groups) and [Search the audit log in the Security & Compliance Center](https://docs.microsoft.com/microsoft-365/compliance/search-the-audit-log-in-security-and-compliance).</span></span>