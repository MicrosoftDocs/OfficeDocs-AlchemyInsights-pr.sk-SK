---
title: Oprava aplikácií balíka Office nemohla nájsť priradenú správu licencií balíka Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3421"
- "9001426"
ms.openlocfilehash: 1820cdb83a1adf36b4e7d0898ecdf8097eb6f0f3
ms.sourcegitcommit: 358e7ed05c262f909bfa9ed0df730e1fd89266b8
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 11/27/2019
ms.locfileid: "39627933"
---
# <a name="fixing-the-office-apps-couldnt-find-office-licenses-associated-message"></a>Oprava aplikácií balíka Office "Nepodarilo sa nájsť Office licencie súvisiace" správa

Ak sa zobrazí toto hlásenie, vyskúšajte nasledujúce kroky:

1. Skontrolujte, či brána firewall, antivírusový softvér a nastavenia servera proxy potvrdia, že neblokujú prístup na internet k aplikáciám balíka Office. Pozrite si [Office 365 adresy URL a rozsahy adries IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).
2. Odstráňte a [priraďte licenciu balíka Office](https://docs.microsoft.com/office365/admin/manage/assign-licenses-to-users) pre príslušného používateľa. 
3. Otvorte aplikáciu balíka Office a [odhláste sa](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) z existujúcich používateľských kont.
4. Prejdite na nastavenia systému Windows > **kontá** > **e-mailové & kontá**a odstráňte všetky pracovné kontá okrem príslušného konta.
5. Prejdite na nastavenia systému Windows > **kontá** > **prístup k práci alebo škole**, a odpojte všetky pracovné účty okrem príslušného konta.
6. Obnoviť stav aktivácie balíka Office. [Prečítajte si, ako](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state).
7. [Prihláste](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) sa pomocou príslušného používateľského konta.

Ďalšie riešenia na riešenie problémov nájdete [v téme nelicencované produkty a chyby aktivácie v balíku Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380).