---
title: Zakázanie externých skupín
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: f7a1bbda3a54d2662bdfe21cda961c32456edb82
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 09/14/2020
ms.locfileid: "47704143"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="0f1ea-102">Zakázanie externých skupín</span><span class="sxs-lookup"><span data-stu-id="0f1ea-102">How to disable External Groups</span></span>

<span data-ttu-id="0f1ea-103">Externé správy v Yammeri používajú pravidlá prenosu systému Exchange (ETRs), množinu proaktívnych ovládacích prvkov, aby sa predišlo zdieľaniu informácií o spoločnosti.</span><span class="sxs-lookup"><span data-stu-id="0f1ea-103">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared.</span></span> <span data-ttu-id="0f1ea-104">Ak chcete obmedziť používateľov na vytváranie externých skupín, musíte nakonfigurovať pravidlo prenosu služby Exchange (ETR) a potom nakonfigurovať Yammer na blokovanie externých správ pomocou pravidla prenosu Exchangeu.</span><span class="sxs-lookup"><span data-stu-id="0f1ea-104">In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span>
  
<span data-ttu-id="0f1ea-105">Po vytvorení pravidla v centre spravovania služby Exchange Online postupujte podľa týchto krokov na nastavenie ETR na použitie v Yammeri:</span><span class="sxs-lookup"><span data-stu-id="0f1ea-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="0f1ea-106">Prihláste sa do Yammera ako overený správca a v **centre spravovania služby Yammer**prejdite na **položky C obsah a zabezpečenie zabezpečenia \> .**</span><span class="sxs-lookup"><span data-stu-id="0f1ea-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **Content and Security \> Security Settings.**</span></span>

- <span data-ttu-id="0f1ea-107">V časti **externé správy**vyberte **v Yammeri položku vynútiť pravidlá prenosu Exchange Online Exchange (ETRs).**</span><span class="sxs-lookup"><span data-stu-id="0f1ea-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>

- <span data-ttu-id="0f1ea-108">Vyberte položku **Uložiť**.</span><span class="sxs-lookup"><span data-stu-id="0f1ea-108">Choose **Save**.</span></span>

<span data-ttu-id="0f1ea-109">Ďalšie informácie nájdete v téme [Vypnutie externých správ v sieti Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span><span class="sxs-lookup"><span data-stu-id="0f1ea-109">For more information, see [Disable external messaging in a Yammer network](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span></span>
  