---
title: Kód chyby 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Ak sa zobrazuje chyba pri aktivácii služieb Office 2013 v rámci nasadenia služby Remote Desktop Services (RDS), zvážte možnosť povoliť ADAL úpravou databázy Registry.
ms.openlocfilehash: deb2ac4b0fb6a7b2e0045ff1b0ba95ad6e5e4a3a
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 09/14/2020
ms.locfileid: "47709202"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Chyba pri aktivácii služieb Office 2013 v službách vzdialenej pracovnej plochy

Ak sa zobrazuje chyba pri aktivácii služieb Office 2013 v rámci nasadenia služby Remote Desktop Services (RDS), zvážte možnosť povoliť ADAL úpravou databázy Registry.
  
|**Kľúč databázy Registry**|**Zadajte**|**Hodnotu**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER \Software\Microsoft\Office\15.0\Common\Identity\EnableADAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Ďalšie informácie nájdete v téme [povolenie moderného overovania pre Office 2013 v zariadeniach s Windowsom](https://docs.microsoft.com/microsoft-365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  Funkcia ADAL je predvolene povolená v aplikáciách Microsoft 365 pre podniky a Office 2016. Služby Remote Desktop Services (RDS) sa predtým nazývali terminálové služby.
  