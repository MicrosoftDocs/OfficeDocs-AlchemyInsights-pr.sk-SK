---
title: nástroj na exportovanie eDiscovery
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
- "263"
- "928"
- "1100001"
- "3100022"
ms.assetid: b16d310d-1134-4959-be68-d1c0ad463930
ms.openlocfilehash: 67e59182a5053111a08f5fb2be814931a1aa815d
ms.sourcegitcommit: fbe6925797cab0b38172386f1b059dc122e452a4
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 09/25/2020
ms.locfileid: "48277934"
---
# <a name="cant-install-or-run-the-ediscovery-export-tool"></a>Nedá sa nainštalovať alebo spustiť nástroj na exportovanie elektronického vyhľadávania?

Ak nemôžete nainštalovať alebo spustiť nástroj na exportovanie eDiscovery na stiahnutie výsledkov vyhľadávania, pozrite si nasledujúce skutočnosti:
  
- Počítač, ktorý používate, spĺňa tieto požiadavky:

  - 32 alebo 64-bitové verzie Windowsu 7 a novších verzií

  - Microsoft .NET Framework 4.7

  - Podporovaný prehliadač:

  - Microsoft Edge

    Alebo

  - Internet Explorer 10 a novšie verzie

    Ďalšie prehliadače, ako je napríklad Google Chrome a Mozilla Firefox, nie sú podporované.

- Vaša organizácia sa môže pripojiť ku koncovému bodu v Azure, ktorý je ** \* . blob.Core.Windows.net** (zástupný znak predstavuje jedinečný identifikátor pre úlohu exportu).

- Ste priradili rolu exportu v &amp; Centre zabezpečenia dodržiavania súladu pre Microsoft 365. Predvolene je táto rola priradená k skupine rolí správcu eDiscovery. Pozrite si tému [Priradenie povolení pre eDiscovery](https://docs.microsoft.com/microsoft-365/compliance/assign-ediscovery-permissions).

Ďalšie informácie nájdete v téme [exportovanie výsledkov vyhľadávania obsahu](https://docs.microsoft.com/microsoft-365/compliance/export-search-results).

Ak exportujete viac než 100K poštových schránok, budete musieť použiť nasledujúce prostredie PowerShell na stiahnutie výsledkov exportu:  [exportovanie výsledkov z viac ako 100k poštových schránok](https://docs.microsoft.com/microsoft-365/compliance/export-search-results?view=o365-worldwide%23exporting-results-from-more-than-100000-mailboxes).