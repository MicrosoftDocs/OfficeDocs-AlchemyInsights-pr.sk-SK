---
title: Správa synchronizovaného používateľa
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
- "9000609"
- "2444"
ms.openlocfilehash: 7bf7d3f00308ff6bc973cd52e09ca51c5fd0f45b
ms.sourcegitcommit: 1fb324fd156008e77b7e2008af4b3dc1c0d0ea3e
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 10/13/2020
ms.locfileid: "48451415"
---
# <a name="unable-to-set-primary-email-address-change-user-attributes-or-removedelete-a-synchronized-user"></a>Nie je možné nastaviť primárnu e-mailovú adresu, zmeniť atribúty používateľa alebo odstrániť alebo odstrániť synchronizovaného používateľa

Ak je pre vaše prostredie povolená Synchronizácia adresárov, niektoré atribúty používateľa alebo objektu nie je možné zmeniť pomocou centra spravovania služby Microsoft 365.

Ak chcete plne spravovať synchronizovaných používateľov a všetky ich atribúty, použite lokálnu konzolu na správu používateľov a skupín služby Active Directory (Adsiedit. msc).  

Prípadne môžete zmeniť jednotlivých používateľov alebo atribúty pre synchronizovaných používateľov, ktorí používajú prostredie PowerShell, ako je to znázornené v týchto bežných príkladoch:

`Set-MsolUser -UserPrincipalName user@yourdomain.onmicrosoft.com -AlternateEmailAddresses user2@yourvanitydomain.onmicrosoft.com`

`Set-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com" -DisplayName "Test User" -LastName "User" -Title "Manager" -Department "HR"`

`Remove-MsolUser -UserPrincipalName "user@yourdomain.onmicrosoft.com`
