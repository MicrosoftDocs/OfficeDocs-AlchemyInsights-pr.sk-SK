---
title: Problémy s hlavným zdrojom alebo službou
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004336"
- "7741"
ms.openlocfilehash: 9c37ad8e4dfecdb59a37d767f8eb4a5d99be7fa1
ms.sourcegitcommit: d13f23fb7994871d4e0e6e3e43672a101bd779e8
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 01/28/2021
ms.locfileid: "50714085"
---
# <a name="issues-with-a-resource-or-service-principal"></a><span data-ttu-id="51f3d-102">Problémy s hlavným zdrojom alebo službou</span><span class="sxs-lookup"><span data-stu-id="51f3d-102">Issues with a Resource or Service Principal</span></span>

1. <span data-ttu-id="51f3d-103">Ak práve začínate, [hlavné objekty aplikácií a služieb v službe Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/app-objects-and-service-principals) popisujú registráciu aplikácií, objekty aplikácií a princípy služieb v službe Azure Active Directory: čo sú, ako sa používajú a ako sa navzájom súvisia.</span><span class="sxs-lookup"><span data-stu-id="51f3d-103">If you are just getting started, [Application and service principal objects in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/app-objects-and-service-principals) describes application registration, application objects, and service principals in Azure Active Directory: what they are, how they are used, and how they are related to each other.</span></span> <span data-ttu-id="51f3d-104">Na ilustráciu vzťahu medzi objektom aplikácie aplikácie a zodpovedajúcimi hlavnými objektmi služby je prezentovaný aj príklad scenára s viacerými nájomníkmi.</span><span class="sxs-lookup"><span data-stu-id="51f3d-104">A multi-tenant example scenario is also presented to illustrate the relationship between an application's application object and corresponding service principal objects.</span></span>
2. <span data-ttu-id="51f3d-105">Ďalšie informácie o vzťahoch medzi aplikáciami a princípmi služieb nájdete v téme čítanie [aplikácií a hlavných objektov služby v službe Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/app-objects-and-service-principals).</span><span class="sxs-lookup"><span data-stu-id="51f3d-105">You can learn more about the relationship between applications and service principals by reading [applications and service principal objects in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/develop/app-objects-and-service-principals).</span></span>
3. <span data-ttu-id="51f3d-106">[Ako na to: použitie portálu na vytvorenie aplikácie Azure AD a hlavné služby, ktoré môžu získať prístup k prostriedkom](https://docs.microsoft.com/azure/active-directory/develop/howto-create-service-principal-portal) , vám ukáže, ako vytvoriť novú aplikáciu Azure Active Directory (Azure AD), ktorá môže byť použitá s ovládacím prvkom riadenia prístupu na základe rolí.</span><span class="sxs-lookup"><span data-stu-id="51f3d-106">[How to: Use the portal to create an Azure AD application and service principal that can access resources](https://docs.microsoft.com/azure/active-directory/develop/howto-create-service-principal-portal) shows you how to create a new Azure Active Directory (Azure AD) application and service principal that can be used with the role-based access control.</span></span>
4. <span data-ttu-id="51f3d-107">Pomocou [hlavného rozhrania API služby](https://docs.microsoft.com/graph/api/resources/serviceprincipal)môžete pomocou programovania spravovať inštancie aplikácií a riadiť, čo môže aplikácia vykonávať v rámci vášho nájomníka.</span><span class="sxs-lookup"><span data-stu-id="51f3d-107">With the [service principal API](https://docs.microsoft.com/graph/api/resources/serviceprincipal), you can programmatically manage instances of applications and control what an application can do within your tenant.</span></span>
5. <span data-ttu-id="51f3d-108">[Typ zdroja servicePrincipal](https://docs.microsoft.com/graph/api/resources/serviceprincipal) obsahuje všetky vlastnosti a metódy pre typ zdroja servicePrincipal.</span><span class="sxs-lookup"><span data-stu-id="51f3d-108">[servicePrincipal resource type](https://docs.microsoft.com/graph/api/resources/serviceprincipal) lists all properties and methods for the servicePrincipal resource type.</span></span>
6. <span data-ttu-id="51f3d-109">[Rozdiely v type zdroja medzi Azure AD graphom a Microsoft graphom](https://docs.microsoft.com/graph/migrate-azure-ad-graph-resource-differences) zvýrazňujú rozdiely medzi Azure AD Graph a Microsoft Graph Resources.</span><span class="sxs-lookup"><span data-stu-id="51f3d-109">[Resource type differences between Azure AD Graph and Microsoft Graph](https://docs.microsoft.com/graph/migrate-azure-ad-graph-resource-differences) highlights differences between Azure AD Graph and Microsoft Graph resources.</span></span> <span data-ttu-id="51f3d-110">Zobrazuje zdroje, ktoré majú rôzne názvy alebo nie sú k dispozícii; vyzdvihuje tiež zdroje dostupné v beta verzii programu Microsoft Graph, ale nie v verzii v 1.0.</span><span class="sxs-lookup"><span data-stu-id="51f3d-110">It shows resources that have different names or are not available; it also highlights resources available in the beta version of Microsoft Graph but not in the v1.0 version.</span></span>

<span data-ttu-id="51f3d-111">**Problémy s hosťujúcimi používateľmi**</span><span class="sxs-lookup"><span data-stu-id="51f3d-111">**Issues with Guest Users**</span></span>

- <span data-ttu-id="51f3d-112">Rýchly štart [: Pridanie hosťujúcich používateľov do adresára na portáli Azure](https://docs.microsoft.com/azure/active-directory/external-identities/b2b-quickstart-add-guest-users-portal#prerequisites) vám ukáže, ako pridať nového hosťujúceho používateľa do adresára služby Azure AD prostredníctvom portálu Azure, Odoslať pozvánku a zistiť, ako vyzerá proces vyplatenia používateľa hosťa.</span><span class="sxs-lookup"><span data-stu-id="51f3d-112">[Quickstart: Add guest users to your directory in the Azure portal](https://docs.microsoft.com/azure/active-directory/external-identities/b2b-quickstart-add-guest-users-portal#prerequisites) shows you how to add a new guest user to your Azure AD directory via the Azure portal, send an invitation, and see what the guest user's invitation redemption process looks like.</span></span>
- <span data-ttu-id="51f3d-113">[Kurz: Vytvorenie používateľských tokov v službe Azure Active Directory B2C](https://docs.microsoft.com/azure/active-directory-b2c/tutorial-create-user-flows) vám ukáže, ako vytvoriť niektoré Odporúčané toky používateľov pomocou portálu Azure.</span><span class="sxs-lookup"><span data-stu-id="51f3d-113">[Tutorial: Create user flows in Azure Active Directory B2C](https://docs.microsoft.com/azure/active-directory-b2c/tutorial-create-user-flows) shows you how to create some recommended user flows by using the Azure portal.</span></span> <span data-ttu-id="51f3d-114">Ak hľadáte informácie o tom, ako v aplikácii nastaviť tok údajov vlastníka hesla vlastníka prostriedku (ROPC), prečítajte si tému Konfigurácia toku poverení hesla vlastníka prostriedku v službe Azure AD B2C.</span><span class="sxs-lookup"><span data-stu-id="51f3d-114">If you are looking for information about how to set up a resource owner password credentials (ROPC) flow in your application, see Configure the resource owner password credentials flow in Azure AD B2C.</span></span>