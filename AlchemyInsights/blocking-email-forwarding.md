---
title: 726 blokovanie preposielania e-mailov
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "726"
- "1200004"
ms.assetid: 8865c68e-7e8a-4135-a254-d7f69f1ded30
ms.openlocfilehash: 610013c4f46e999f1a8715aea14dd557ed8b0e2a
ms.sourcegitcommit: 88f24bb6ced16842de165af416e3f21feae13063
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 10/15/2020
ms.locfileid: "48478329"
---
# <a name="blocking-or-unblocking-email-forwarding"></a>Blokovanie alebo odblokovanie preposielania e-mailov

Ak chcete zapnúť alebo vypnúť presmerovanie e-mailov pre konkrétnu poštovú schránku, prečítajte si tému [Konfigurácia preposielania](https://docs.microsoft.com/microsoft-365/admin/email/configure-email-forwarding)

Na úrovni nájomníka sa kontrola externého preposielania uskutočňuje pomocou politiky odchádzajúcej pošty. Odchádzajúca politika filtrovania nevyžiadanej pošty môžete skontrolovať [v centre zabezpečenia](https://protection.office.com/antispam) a dodržiavania súladu alebo pomocou [príkazu Get-HostedOutboundSpamFilterPolicy](https://docs.microsoft.com/powershell/module/exchange/get-hostedoutboundspamfilterpolicy).

Ak sa zobrazuje nasledujúca chyba: **"550 5.7.520 Access bol odmietnutý, vaša organizácia nepovoľuje externé preposielanie"**, skontrolujte, či je politika nakonfigurovaná na povolenie externého automatického preposielania.

**Poznámka:** Odporúča sa ponechať externé automatické preposielanie vypnuté v predvolenej politike filtra odchádzajúcich nevyžiadanej pošty a povoliť ho len používateľom, ktorí potrebujú externé preposielanie, a to vytvorením vlastnej politiky pre týchto používateľov. Ďalšie informácie nájdete v téme [Konfigurácia externého preposielania e-mailov v Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/external-email-forwarding).