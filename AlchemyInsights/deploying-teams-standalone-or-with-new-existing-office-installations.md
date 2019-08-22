---
title: Nasadenie tímov ako samostatný alebo nových alebo existujúcich inštalácií balíka Office
ms.author: danbrown
author: DHB-MSFT
manager: laurawi
ms.date: 08/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000660"
- "2509"
ms.openlocfilehash: 3318e1b17cc99e927e1011f7ca9eca8dec616d59
ms.sourcegitcommit: 4600dd4fb577bf5f5482a24616c2d9a6b81e8052
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 08/01/2019
ms.locfileid: "36054245"
---
# <a name="deploying-teams-as-standalone-or-with-new-or-existing-office-installations"></a><span data-ttu-id="fe9a7-102">Nasadenie tímov ako samostatný alebo nových alebo existujúcich inštalácií balíka Office</span><span class="sxs-lookup"><span data-stu-id="fe9a7-102">Deploying Teams as standalone or with new or existing Office installations</span></span>

<span data-ttu-id="fe9a7-103">Microsoft Teams je teraz zahrnuté ako súčasť ***nových inštaláciách*** Office 365 ProPlus, Office 365 Business a Office for Mac.</span><span class="sxs-lookup"><span data-stu-id="fe9a7-103">Microsoft Teams is now included as part of ***new installations*** of Office 365 ProPlus, Office 365 Business, and Office for Mac.</span></span> <span data-ttu-id="fe9a7-104">Ďalšie informácie nájdete v téme [Kedy Microsoft Teams začne byť súčasťou novej inštalácie balíka Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)</span><span class="sxs-lookup"><span data-stu-id="fe9a7-104">For more information, see [When will Microsoft Teams start being included with new installations of Office?](https://docs.microsoft.com/deployoffice/teams-install#when-will-microsoft-teams-start-being-included-with-new-installations-of-office-365-proplus)</span></span>

<span data-ttu-id="fe9a7-105">Navyše, počnúc verziu 1906 v mesačných kanál, tímy bude ***pridaný do existujúcej inštalácie*** Office 365 ProPlus (a Office 365 Business) na zariadeniach so systémom Windows, keď aktualizujete existujúce zariadenie na najnovšiu verziu.</span><span class="sxs-lookup"><span data-stu-id="fe9a7-105">Additionally, starting with Version 1906 in Monthly Channel, Teams will be ***added to existing installations*** of Office 365 ProPlus (and Office 365 Business) on devices running Windows when you update your existing installation to the latest version.</span></span> <span data-ttu-id="fe9a7-106">Ďalšie informácie nájdete v téme [čo o existujúcej inštalácie balíka Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus)</span><span class="sxs-lookup"><span data-stu-id="fe9a7-106">For more information, see [What about existing installations of Office?](https://docs.microsoft.com/deployoffice/teams-install#what-about-existing-installations-of-office-365-proplus)</span></span>

> [!NOTE]
> <span data-ttu-id="fe9a7-107">Ak nechcete čakať na tento plán zavádzania, môžete nasadiť tímy ako samostatný používateľom podľa [týchto pokynov](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) alebo si môžete používateľom nainštalovať tímy pre seba z [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads).</span><span class="sxs-lookup"><span data-stu-id="fe9a7-107">If you don't want to wait for this rollout schedule, you can deploy Teams as standalone for your users by [following these instructions](https://docs.microsoft.com/MicrosoftTeams/msi-deployment) or you can have your users install Teams for themselves from [https://teams.microsoft.com/downloads](https://teams.microsoft.com/downloads).</span></span>

<span data-ttu-id="fe9a7-108">Ak vaša organizácia nie je pripravený na nasadenie tímov, máme možné kroky na ***vylúčenie tímy*** z [novej](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) alebo [existujúcej](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) inštalácie balíka Office.</span><span class="sxs-lookup"><span data-stu-id="fe9a7-108">If your organization isn't ready to deploy Teams, we have the steps you can take to ***exclude Teams*** from [new](https://docs.microsoft.com/deployoffice/teams-install#how-to-exclude-microsoft-teams-from-new-installations-of-office-365-proplus) or [existing](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-control-the-installation-of-microsoft-teams) installations of Office.</span></span> <span data-ttu-id="fe9a7-109">Ak chcete tímy nainštalované, ale chcem tímy začať automaticky pre používateľa po nainštalovaní, pozri [Zabrániť Microsoft tímy z začína automaticky po inštalácii](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).</span><span class="sxs-lookup"><span data-stu-id="fe9a7-109">If you want Teams to be installed, but don't want Teams to start automatically for the user after it's installed, see [Prevent Microsoft Teams from starting automatically after installation](https://docs.microsoft.com/deployoffice/teams-install#use-group-policy-to-prevent-microsoft-teams-from-starting-automatically-after-installation).</span></span>

<span data-ttu-id="fe9a7-110">***Odinštalovať tímy*** zo zariadenia so systémom Windows, pozrite si [Odinštalovať Microsoft tímov](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span><span class="sxs-lookup"><span data-stu-id="fe9a7-110">To ***uninstall Teams*** from a device running Windows, see [Uninstall Microsoft Teams](https://support.office.com/article/3b159754-3c26-4952-abe7-57d27f5f4c81).</span></span> <span data-ttu-id="fe9a7-111">Vyčistenie Microsoft Teams z viacerých cieľových počítačov alebo používateľov, nájdete [Microsoft tímy nasadenie vyčistiť](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span><span class="sxs-lookup"><span data-stu-id="fe9a7-111">To cleanup Microsoft Teams from multiple target machines or users, see [Microsoft Teams deployment clean up](https://docs.microsoft.com/microsoftteams/scripts/powershell-script-teams-deployment-clean-up).</span></span>

<span data-ttu-id="fe9a7-112">Ak používate zdieľané počítače, Remote Desktop Services (RDS) alebo Virtual Desktop Infrastructure (VDI), pozri [zdieľaný počítač a prostrediach VDI s tímami spoločnosti Microsoft](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).</span><span class="sxs-lookup"><span data-stu-id="fe9a7-112">If you're using shared computers, Remote Desktop Services (RDS), or Virtual Desktop Infrastructure (VDI), see [Shared computer and VDI environments with Microsoft Teams](https://docs.microsoft.com/deployoffice/teams-install#shared-computer-and-vdi-environments-with-microsoft-teams).</span></span>

<span data-ttu-id="fe9a7-113">Ak používate Office pre Mac, pozri [Microsoft tímy zariadenia do Macu](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span><span class="sxs-lookup"><span data-stu-id="fe9a7-113">If you're using Office for Mac, see [Microsoft Teams installations on a Mac](https://docs.microsoft.com/deployoffice/teams-install#microsoft-teams-installations-on-a-mac).</span></span>

> [!NOTE]
> <span data-ttu-id="fe9a7-114">Po nainštalovaní tímov je [automaticky aktualizovaná](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) približne každé dva týždne s nové funkcie a aktualizácie na zvýšenie kvality.</span><span class="sxs-lookup"><span data-stu-id="fe9a7-114">After Teams is installed, it's [automatically updated](https://docs.microsoft.com/deployoffice/teams-install#feature-and-quality-updates-for-microsoft-teams) approximately every two weeks with new features and quality updates.</span></span> 