---
title: Oprava pravidiel prenosu
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 635009ed4b78d2b05b0eef1f3298765b10f86ede
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 03/11/2021
ms.locfileid: "50750575"
---
# <a name="fix-transport-rules"></a><span data-ttu-id="7b857-102">Oprava pravidiel prenosu</span><span class="sxs-lookup"><span data-stu-id="7b857-102">Fix transport rules</span></span>

<span data-ttu-id="7b857-103">Táto správa ovplyvnila vlastné pravidlo toku pošty.</span><span class="sxs-lookup"><span data-stu-id="7b857-103">A custom mail flow rule affected this message.</span></span> <span data-ttu-id="7b857-104">Ak chcete skontrolovať presné pravidlo, postupujte takto:</span><span class="sxs-lookup"><span data-stu-id="7b857-104">To review the exact rule, do the following:</span></span>

1. <span data-ttu-id="7b857-105">Vo výsledkoch odosielania v časti **Ďalšie informácie** si všimnite **identifikátor GUID** alebo **názov politiky**.</span><span class="sxs-lookup"><span data-stu-id="7b857-105">In the submission results, under **Additional information**, note the **GUID** or the **Policy Name**.</span></span>
2. <span data-ttu-id="7b857-106">Spustite prostredie Exchange Management Shell.</span><span class="sxs-lookup"><span data-stu-id="7b857-106">Launch Exchange Management Shell.</span></span> <span data-ttu-id="7b857-107">Ďalšie informácie nájdete v téme [Otvorenie prostredia Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span><span class="sxs-lookup"><span data-stu-id="7b857-107">For more information, see [Open the Exchange Management Shell](https://go.microsoft.com/fwlink/?linkid=2101432).</span></span>
3. <span data-ttu-id="7b857-108">Spustite tento príkaz (pomocou identifikátora GUID z vášho odoslania):  **Get-TransportRule-identity "GUID" | FL \* Popis**\*</span><span class="sxs-lookup"><span data-stu-id="7b857-108">Run this command (using the GUID from your submission):  **Get-TransportRule -identity "GUID" | fl \* Description**\*</span></span>
4. <span data-ttu-id="7b857-109">Prezrite si popis a zobrazia sa nakonfigurované podmienky, ktoré ovplyvnili správu.</span><span class="sxs-lookup"><span data-stu-id="7b857-109">Review the description to see the configured conditions that affected the message.</span></span>

<span data-ttu-id="7b857-110">Ďalšie informácie nájdete v téme [Get-TransportRule](https://go.microsoft.com/fwlink/?linkid=2101523).</span><span class="sxs-lookup"><span data-stu-id="7b857-110">To learn more, see [Get-TransportRule](https://go.microsoft.com/fwlink/?linkid=2101523).</span></span>