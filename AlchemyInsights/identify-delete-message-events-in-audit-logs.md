---
title: Identifikáciu odstrániť správu udalostí v denníkoch auditu
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1370
ms.assetid: ''
ms.openlocfilehash: 93f8a192af6e689e2b2d04013f35b8da2b69e607
ms.sourcegitcommit: ffe2f489b1ac3aae62aa784c959da6a41c3261eb
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 04/17/2019
ms.locfileid: "31909541"
---
# <a name="audit-logs-for-deleted-email-messages"></a>Denníky pre audit odstránených e-mailových správ

Od januára 2019, Microsoft je odbočka na poštovej schránky auditu zapisovania do denníka v predvolenom nastavení. Inak, skontrolujte odstrániť hlásenie udalosti pre konkrétneho používateľa, musíte manuálne povoliť akcie delete pre auditovanie. Ak poštová schránka pre audit sú už povolené pre organizáciu alebo pre konkrétneho používateľa, postupujte podľa nasledujúcich krokov.

1. Prihláste sa do [Centrum Office 365 zabezpečenia & súlad](https://protection.office.com/)

2. Kliknite na položku **vyhľadávanie a vyšetrovanie** a vyberte **Vyhľadávanie denník auditu**.

3. Vyberte rozsah dátumov v poliach **Počiatočný dátum** a **Koncový dátum** . Zadajte meno používateľa, ktorý chcete preskúmať (používateľa, ktorý odstránil položky). V oblasti **aktivity** vyberte **odstránené správy z priečinka Odstránené položky** a **správy presunuté do priečinka Odstránené položky**.

4. Kliknite na tlačidlo **Hľadať**.

V zozname výsledkov vyberte auditný záznam. V rozbaľovacie tlačidlo Podrobnosti, kliknite na **Viac informácií**. Ďalšie informácie o odstránených položiek (napríklad, predmet a umiestnenie položky, keď sa odstránil) je zobrazené v poli **AffectedItems** . Vlastnosť **ClientInfoString** zobrazí, ak odstránenia sa vyskytla v programe Outlook, Outlook web (predtým označované ako aplikácie Outlook Web App) alebo akékoľvek iné zariadenie.

Pre viac informácií, pozri [určenie kto nastaviť preposielanie pre poštovú schránku](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-deleted-email-items).

**Poznámka**: nemožno obnoviť odstránené položky pomocou audit log funkcie. Obnoviť odstránené položky v programe Outlook na webe, nájdete v téme [Obnovenie odstránených položiek v aplikácii Outlook Web App](https://support.office.com/article/C3D8FC15-EEEF-4F1C-81DF-E27964B7EDD4).