---
title: Otázky o tom, ako používať Office Deployment Tool (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: e91d40f872dd401ee210ac05eb39d64b6fb88027
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 02/12/2019
ms.locfileid: "29925359"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Otázky o tom, ako používať Office Deployment Tool (ODT)

Stiahnuť Office nasadenia nástroj z [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Po stiahnutí súboru, spustite samorozbaľovací spustiteľný súbor, ktorý obsahuje Office nasadenia nástroj spustiteľný (setup.exe) a ukážkový konfiguračný súbor (configuration.xml).
  
 **Ak chcete vylúčiť alebo odstrániť Office 365 ProPlus produkty z klientskych počítačov:**
  
Pri inštalácii balíka Office 365 ProPlus, môžete vylúčiť konkrétne produkty. Tak chcete urobiť, postupujte podľa krokov na inštaláciu balíka Office s ODT, ale obsahujú ExcludeApp prvok v konfiguračnom súbore. Napríklad tento konfiguračný súbor nainštaluje všetky Office 365 ProPlus výrobky okrem Vydavateľ:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Prehľad nástroja nasadenia Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

