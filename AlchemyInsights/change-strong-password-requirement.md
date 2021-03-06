---
title: Zmena požiadavky na silné heslo
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 8ce331275e066b5a4f177ae27178ec726f90762f
ms.sourcegitcommit: aa35d2e1829f7d07f64fb891bf73b1fd80f0864c
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 10/30/2020
ms.locfileid: "48804438"
---
# <a name="change-strong-password-requirement"></a>Zmena požiadavky na silné heslo

Spoločnosť Microsoft vyžaduje na základe predvoleného nastavenia silné heslá.

Pomocou prostredia PowerShell môžete vypnúť silné heslá pre konkrétnych používateľov s týmito príkazmi:

`Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false`

Ak chcete vypnúť silné heslá pre všetkých používateľov, použite tento postup:

`Get-MsolUser | Set-MsolUser -StrongPasswordRequired $false`

- [Ďalšie informácie o politike hesiel](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [Pripojenie k službe Microsoft 365 s prostredím PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [Ďalšie informácie o príkazoch prostredia PowerShell MsolUser](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)
