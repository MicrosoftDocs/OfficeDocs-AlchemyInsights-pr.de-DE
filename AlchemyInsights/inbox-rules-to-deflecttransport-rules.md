---
title: 929 postEingangsregeln für deflectTransport-Regeln
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 6/15/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 929
ms.assetid: 9733ef4e-db8d-4345-a072-c251480875a1
ms.openlocfilehash: 9b78dea8557c68d23cf1409ebd6f7c7aab46f1be
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: de-DE
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776851"
---
# <a name="mail-flow-rules-also-known-as-transport-rules"></a><span data-ttu-id="fdd73-102">Nachrichtenfluss Regeln (auch als Transportregeln bezeichnet)</span><span class="sxs-lookup"><span data-stu-id="fdd73-102">Mail flow rules (also known as transport rules)</span></span>

- <span data-ttu-id="fdd73-103">Allgemeine Übersicht über Nachrichtenfluss Regeln: [Nachrichtenfluss Regeln (Transportregeln) in Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span><span class="sxs-lookup"><span data-stu-id="fdd73-103">General overview of mail flow rules: [Mail flow rules (transport rules) in Exchange Online](https://technet.microsoft.com/library/jj919238.aspx)</span></span>
    
- <span data-ttu-id="fdd73-104">Einrichten von Nachrichtenfluss Regeln: [Nachrichtenfluss Regelverfahren in Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span><span class="sxs-lookup"><span data-stu-id="fdd73-104">Setup mail flow rules: [Mail flow rule procedures in Exchange Online](https://technet.microsoft.com/library/dn600436.aspx)</span></span>
    
- <span data-ttu-id="fdd73-105">Erstellen, ändern und Löschen von Nachrichtenfluss Regeln: [Verwalten von Nachrichtenfluss Regeln](https://technet.microsoft.com/library/jj657505.aspx)</span><span class="sxs-lookup"><span data-stu-id="fdd73-105">Create, modify, and delete mail flow rules: [Manage mail flow rules](https://technet.microsoft.com/library/jj657505.aspx)</span></span>
    
<span data-ttu-id="fdd73-106">Sie können auch Nachrichtenfluss Regeln in Exchange Online PowerShell verwalten.</span><span class="sxs-lookup"><span data-stu-id="fdd73-106">You can also manage mail flow rules in Exchange Online PowerShell.</span></span> <span data-ttu-id="fdd73-107">Weitere Informationen finden Sie unter [Get-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (View), [New-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (Create), [Remove-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (Delete), [Set-](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) TransportRule (modify existing), [Disable-](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) TransportRule (Disable existing) und [Enable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (vorhandenes aktivieren).</span><span class="sxs-lookup"><span data-stu-id="fdd73-107">For more information, see [Get-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrule) (view), [New-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/new-transportrule) (create), [Remove-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/remove-transportrule) (delete), [Set-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/set-transportrule) (modify existing), [Disable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/disable-transportrule) (disable existing), and [Enable-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/enable-transportrule) (enable existing).</span></span> 
  
<span data-ttu-id="fdd73-108">Weitere Cmdlets für die Nachrichtenfluss Regel: [Get-TransportRule](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) Action (Listen der verfügbaren Aktionen), [Get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (Liste der verfügbaren Bedingungen und Ausnahmen), [Export-](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) TransportRuleCollection (Exportregeln) und [ Import-](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) TransportRuleCollection (Import Rules).</span><span class="sxs-lookup"><span data-stu-id="fdd73-108">Additional mail flow rule cmdlets: [Get-TransportRuleAction](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportruleaction) (list available actions), [Get-TransportRulePredicate](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/get-transportrulepredicate) (list available conditions and exceptions), [Export-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/export-transportrulecollection) (export rules), and [Import-TransportRuleCollection](https://docs.microsoft.com/powershell/module/exchange/policy-and-compliance/import-transportrulecollection) (import rules).</span></span> 
  
