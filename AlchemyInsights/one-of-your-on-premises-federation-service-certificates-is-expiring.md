---
title: Medzi lokálnym federácia služby certifikátov končí
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 3/20/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 9e2e1a1dd2993b2a02b4405db8a707b23ff4af16
ms.sourcegitcommit: 0ae6cbb8cf2836da98300767ed81b411d6551bee
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 01/30/2019
ms.locfileid: "29658922"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a><span data-ttu-id="c253a-102">Medzi lokálnym federácia služby certifikátov končí</span><span class="sxs-lookup"><span data-stu-id="c253a-102">One of your on-premises Federation Service Certificates is expiring</span></span>

<span data-ttu-id="c253a-103">Ak chcete vyriešiť tento problém, postupujte nasledovne:</span><span class="sxs-lookup"><span data-stu-id="c253a-103">To resolve this issue, follow these steps:</span></span>
  
- <span data-ttu-id="c253a-p101">Nainštalovať Microsoft Azure Active Directory modul pre Windows PowerShell na počítači (Ak modul nie je už nainštalovaný). Chcete urobiť, prejdite na [Azure Active Directory PowerShell pre graf](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span><span class="sxs-lookup"><span data-stu-id="c253a-p101">Install the Microsoft Azure Active Directory Module for Windows PowerShell on the computer (if the module isn't already installed). To do this, go to [Azure Active Directory PowerShell for Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)</span></span>
    
- <span data-ttu-id="c253a-106">Postupujte podľa "Scenár 1: AD FS tokenu podpisovanie certifikátu skončila" časti ["Tam bol problém s prístupom k lokalite" chyba z AD FS pri združenej používateľ prihlasuje do Office 365, Azure, alebo Windows Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span><span class="sxs-lookup"><span data-stu-id="c253a-106">Follow the steps in the "Scenario 1: The AD FS token-signing certificate expired" section of ["There was a problem accessing the site" error from AD FS when a federated user signs in to Office 365, Azure, or Intune](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat).</span></span>
    
- <span data-ttu-id="c253a-107">Postupujte podľa t[ako aktualizovať alebo opraviť nastavenia združenú doménu v Office 365, Azure, alebo Windows Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span><span class="sxs-lookup"><span data-stu-id="c253a-107">Follow the steps in t[How to update or repair the settings of a federated domain in Office 365, Azure, or Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).</span></span>
    
<span data-ttu-id="c253a-108">Ďalšie informácie o obnovení federácie certifikáty, pozrite si [obnovenie certifikátu pre služby O365 a Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span><span class="sxs-lookup"><span data-stu-id="c253a-108">For more information about renewing Federation certificates, see [Certificate renewal for O365 and Azure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).</span></span>
  

