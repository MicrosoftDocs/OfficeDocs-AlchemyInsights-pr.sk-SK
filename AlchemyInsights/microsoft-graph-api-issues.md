---
title: Problémy s rozhraním Microsoft Graph API
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
- "9004345"
- "7759"
ms.openlocfilehash: a856094d9152568c3c067da5856153230d6590a6
ms.sourcegitcommit: 9d03083ea6e18070296b87a1b02339ca4d8e6064
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 01/29/2021
ms.locfileid: "50714520"
---
# <a name="microsoft-graph-api-issues"></a><span data-ttu-id="62095-102">Problémy s rozhraním Microsoft Graph API</span><span class="sxs-lookup"><span data-stu-id="62095-102">Microsoft Graph API issues</span></span>

<span data-ttu-id="62095-103">Táto téma sa môže vzťahovať aj na vývojárov, ktorí stále používajú rozhranie API služby Azure AD Graph.</span><span class="sxs-lookup"><span data-stu-id="62095-103">This topic may also apply to developers still using Azure AD Graph API.</span></span> <span data-ttu-id="62095-104">**Dôrazne** sa však odporúča používať program Microsoft Graph na všetky scenáre v adresári, identite a Accesse.</span><span class="sxs-lookup"><span data-stu-id="62095-104">However, it is **strongly** recommended that you use Microsoft Graph for all your directory, identity, and access management scenarios.</span></span>

<span data-ttu-id="62095-105">**Problémy s overovaním alebo autorizáciou**</span><span class="sxs-lookup"><span data-stu-id="62095-105">**Authentication or authorization issues**</span></span>

- <span data-ttu-id="62095-106">Ak vaša aplikácia **nedokáže získať tokeny** na volanie do programu Microsoft Graph, vyberte **problém s použitím kategórie accessových tokenov (Authentication)** pre Microsoft Graph a získajte konkrétnu pomoc a podporu v tejto téme.</span><span class="sxs-lookup"><span data-stu-id="62095-106">If your app is **unable to acquire tokens** to call Microsoft Graph, pick **Problem with getting an access token (Authentication)** Microsoft Graph category to get more specific help and support on this topic.</span></span>
- <span data-ttu-id="62095-107">Ak vaša aplikácia **prijíma chyby autorizácie 401 alebo 403** pri volaní programu Microsoft Graph, vyberte položku **získať chybu odmietnutia prístupu (autorizácia)** Microsoft Graphu API, aby ste získali konkrétnu pomoc a podporu v tejto téme.</span><span class="sxs-lookup"><span data-stu-id="62095-107">If your app is **receiving 401 or 403 authorization errors** when calling Microsoft Graph, pick the **Getting an access denied error (Authorization)** Microsoft Graph API category to get more specific help and support on this topic.</span></span>

<span data-ttu-id="62095-108">**Chcem použiť Microsoft Graph, ale nie ste si istí, kde začať**</span><span class="sxs-lookup"><span data-stu-id="62095-108">**I want to use Microsoft Graph, but not sure where to start**</span></span>

- [<span data-ttu-id="62095-109">Prehľad programu Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="62095-109">Overview of Microsoft Graph</span></span>](https://docs.microsoft.com/graph/overview)
- [<span data-ttu-id="62095-110">Prehľad identity a riadenia prístupu v programe Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="62095-110">Overview of Identity and Access Management in Microsoft Graph</span></span>](https://docs.microsoft.com/graph/azuread-identity-access-management-concept-overview)
- [<span data-ttu-id="62095-111">Začíname s budovaním aplikácií Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="62095-111">Getting started building Microsoft Graph apps</span></span>](https://docs.microsoft.com/graph/)
- <span data-ttu-id="62095-112">**Microsoft Graph Explorer** – testovanie API programu Microsoft Graph v nájomníkovi alebo ukážkovom nájomníkovi</span><span class="sxs-lookup"><span data-stu-id="62095-112">**Microsoft Graph Explorer** - Test Microsoft Graph APIs in your tenant or a demo tenant</span></span>

<span data-ttu-id="62095-113">**Chcem používať Microsoft Graph, ale podporuje to rozhrania v 1.0 Directory API, ktoré potrebujem?**</span><span class="sxs-lookup"><span data-stu-id="62095-113">**I want to use Microsoft Graph, but does it support the v1.0 directory APIs I need?**</span></span>

<span data-ttu-id="62095-114">Microsoft Graph je odporúčaný API pre adresár, identitu a riadenie prístupu.</span><span class="sxs-lookup"><span data-stu-id="62095-114">Microsoft Graph is the recommended API for directory, identity, and access management.</span></span> <span data-ttu-id="62095-115">Existuje však niekoľko rozdielov medzi tým, čo je možné v službe Azure AD Graph a Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="62095-115">However, there are still a few gaps between what is possible in Azure AD Graph and Microsoft Graph.</span></span> <span data-ttu-id="62095-116">Pozrite si nasledujúce články, ktoré zvýrazňujú najaktuálnejšie rozdiely na pomoc pri výbere:</span><span class="sxs-lookup"><span data-stu-id="62095-116">Review the following articles, which highlight the most up-to-date differences to assist in your choice:</span></span>

- [<span data-ttu-id="62095-117">Rozdiely v type zdroja medzi Azure AD Graph a Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="62095-117">Resource type differences between Azure AD Graph and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-resource-differences)
- [<span data-ttu-id="62095-118">Rozdiely medzi vlastnosťami medzi Azure AD Graphom a Microsoft Graphom</span><span class="sxs-lookup"><span data-stu-id="62095-118">Property differences between Azure AD Graph and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-property-differences)
- [<span data-ttu-id="62095-119">Rozdiely v metóde medzi službou Azure AD a programom Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="62095-119">Method differences between Azure AD and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-method-differences)

<span data-ttu-id="62095-120">**Volanie rozhrania API nefunguje – kde môžem vykonať ďalšie testovanie?**</span><span class="sxs-lookup"><span data-stu-id="62095-120">**The API I am calling doesn't work - where can I do more testing?**</span></span>

<span data-ttu-id="62095-121">**Microsoft Graph Explorer** – otestujte rozhrania API programu Microsoft Graph v nájomníkovi alebo ukážkovom nájomníkovi a pozrite si aj **vzorové dotazy** v programe Microsoft Graph Explorer.</span><span class="sxs-lookup"><span data-stu-id="62095-121">**Microsoft Graph Explorer** - Test Microsoft Graph APIs in your tenant or a demo tenant and also check out the **sample queries** in Microsoft Graph Explorer.</span></span>

<span data-ttu-id="62095-122">**Moja aplikácia je príliš pomalá a je tiež stále obmedzovaná. Aké vylepšenia môžem urobiť?**</span><span class="sxs-lookup"><span data-stu-id="62095-122">**My app is too slow and is also getting throttled. What improvements can I make?**</span></span>

<span data-ttu-id="62095-123">V závislosti od vášho scenára je k dispozícii široká škála možností, ktoré vám pomôžu vyrobiť svoju aplikáciu, a v niektorých prípadoch menej náchylné na obmedzovanie službou (pri vykonaní príliš veľkého počtu hovorov).</span><span class="sxs-lookup"><span data-stu-id="62095-123">Depending on your scenario, there are a variety of options at your disposal to make your application more performant, and in some cases, less prone to being throttled by the service (when you are making too many calls).</span></span>

- [<span data-ttu-id="62095-124">Najvhodnejšie postupy v programe Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="62095-124">Microsoft Graph best practices</span></span>](https://docs.microsoft.com/graph/best-practices-concept)
- [<span data-ttu-id="62095-125">Požiadavky na dávkovanie</span><span class="sxs-lookup"><span data-stu-id="62095-125">Batching requests</span></span>](https://docs.microsoft.com/graph/json-batching)
- [<span data-ttu-id="62095-126">Sledovanie zmien prostredníctvom Delta dotazu</span><span class="sxs-lookup"><span data-stu-id="62095-126">Track changes through delta query</span></span>](https://docs.microsoft.com/graph/delta-query-overview)
- [<span data-ttu-id="62095-127">Upozornenia na zmeny prostredníctvom webhookov</span><span class="sxs-lookup"><span data-stu-id="62095-127">Get notified of changes through webhooks</span></span>](https://docs.microsoft.com/graph/webhooks)
- [<span data-ttu-id="62095-128">Usmernenie o obmedzovaní</span><span class="sxs-lookup"><span data-stu-id="62095-128">Throttling guidance</span></span>](https://docs.microsoft.com/graph/throttling)

<span data-ttu-id="62095-129">**Kde nájdem ďalšie informácie o chybách a známych problémoch?**</span><span class="sxs-lookup"><span data-stu-id="62095-129">**Where can I find more information on errors and known issues?**</span></span>

- [<span data-ttu-id="62095-130">Informácie o odpovedaní na chyby v Microsoft Graphe</span><span class="sxs-lookup"><span data-stu-id="62095-130">Microsoft Graph error response information</span></span>](https://docs.microsoft.com/graph/errors)
- [<span data-ttu-id="62095-131">Známe problémy s aplikáciou Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="62095-131">Known issues with Microsoft Graph</span></span>](https://docs.microsoft.com/graph/known-issues)

<span data-ttu-id="62095-132">**Kde môžem skontrolovať stav dostupnosti a pripojenia služby?**</span><span class="sxs-lookup"><span data-stu-id="62095-132">**Where can I check status of service availability and connectivity?**</span></span>

<span data-ttu-id="62095-133">Dostupnosť služieb a pripojenie k základným službám, ku ktorým je možné získať prístup prostredníctvom programu Microsoft Graph, môže mať vplyv na celkovú dostupnosť a výkon programu Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="62095-133">The service availability and connectivity of the underlying services that can be accessed through Microsoft Graph can impact the overall availability and performance of Microsoft Graph.</span></span>

- <span data-ttu-id="62095-134">Ak ide o stav služby Azure Active Directory, pozrite si stav služieb **zabezpečenia a identít** uvedených na [stránke stavu Azure](https://azure.microsoft.com/status/).</span><span class="sxs-lookup"><span data-stu-id="62095-134">For Azure Active Directory service health, check the status of **Security + Identity** services listed in the [Azure status page](https://azure.microsoft.com/status/).</span></span>
- <span data-ttu-id="62095-135">V prípade služieb Office, ktoré prispievajú do programu Microsoft Graph, skontrolujte stav služieb uvedených v časti [Tabuľa stavu služieb balíka Office](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="62095-135">For Office services that contribute to Microsoft Graph, check the status of services listed in the [Office Service Health Dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>

<span data-ttu-id="62095-136">Chyby autorizácie v programe Microsoft Graph môžu byť výsledkom niekoľkých rôznych problémov, z ktorých väčšina vygeneruje chybu 401 alebo 403.</span><span class="sxs-lookup"><span data-stu-id="62095-136">Microsoft Graph authorization errors can be a result of several different issues, most of which generate a 401 or 403 error.</span></span> <span data-ttu-id="62095-137">Tieto chyby môžu viesť napríklad k chybám autorizácie:</span><span class="sxs-lookup"><span data-stu-id="62095-137">For example, the following can all lead to authorization errors:</span></span>

- <span data-ttu-id="62095-138">Nesprávne [toky akvizície prístupového tokenu](https://docs.microsoft.com/azure/active-directory/develop/active-directory-authentication-scenarios)</span><span class="sxs-lookup"><span data-stu-id="62095-138">Incorrect [access token acquisition flows](https://docs.microsoft.com/azure/active-directory/develop/active-directory-authentication-scenarios)</span></span>
- <span data-ttu-id="62095-139">Zle nakonfigurované [rozsahy povolení](https://docs.microsoft.com/azure/active-directory/develop/active-directory-v2-scopes)</span><span class="sxs-lookup"><span data-stu-id="62095-139">Poorly configured [permission scopes](https://docs.microsoft.com/azure/active-directory/develop/active-directory-v2-scopes)</span></span>
- <span data-ttu-id="62095-140">Chýbajúci [súhlas](https://docs.microsoft.com/azure/active-directory/develop/active-directory-devhowto-multi-tenant-overview#understanding-user-and-admin-consent)</span><span class="sxs-lookup"><span data-stu-id="62095-140">Lack of [consent](https://docs.microsoft.com/azure/active-directory/develop/active-directory-devhowto-multi-tenant-overview#understanding-user-and-admin-consent)</span></span>

<span data-ttu-id="62095-141">\**_Ukončenie podpory pre križnicu Azure Active Directory Authentication Library (ADAL) a rozhranie Azure AD Graph API (AAD Graph)_* _</span><span class="sxs-lookup"><span data-stu-id="62095-141">\**_End of support for Azure Active Directory Authentication Library (ADAL) and Azure AD Graph API (AAD Graph)_* _</span></span>

<span data-ttu-id="62095-142">_ \* Od 30. júna 2020 \* \* už nebudeme pridávať žiadne nové funkcie do služby ADAL a Azure AD Graph.</span><span class="sxs-lookup"><span data-stu-id="62095-142">_\*Starting June 30th, 2020\*\*, we will no longer add any new features to ADAL and Azure AD Graph.</span></span> <span data-ttu-id="62095-143">Naďalej budeme poskytovať technickú podporu a aktualizácie zabezpečenia, ale už nebudeme poskytovať aktualizácie funkcií.</span><span class="sxs-lookup"><span data-stu-id="62095-143">We will continue to provide technical support and security updates but will no longer provide feature updates.</span></span>

<span data-ttu-id="62095-144">**Od 30. júna 2022**, ukončíme podporu pre ADAL a Azure AD Graph a už nebude poskytovať technickú podporu ani aktualizácie zabezpečenia.</span><span class="sxs-lookup"><span data-stu-id="62095-144">**Starting June 30th, 2022**, we will end support for ADAL and Azure AD Graph and will no longer provide technical support or security updates.</span></span>

<span data-ttu-id="62095-145">Aplikácie, ktoré používajú ADAL v existujúcich verziách operačného systému, budú fungovať aj po tomto čase, nebudú však *mať žiadne technické podpory ani aktualizácie zabezpečenia*.</span><span class="sxs-lookup"><span data-stu-id="62095-145">Apps using ADAL on existing OS versions will continue to work after this time but will not *get any technical support or security updates*.</span></span>

<span data-ttu-id="62095-146">Aplikácie využívajúce Azure AD Graph po uplynutí tohto času už nemusia dostávať odpovede z koncového bodu služby Azure AD Graphu.</span><span class="sxs-lookup"><span data-stu-id="62095-146">Apps using Azure AD Graph after this time may no longer receive responses from the Azure AD Graph endpoint.</span></span>

<span data-ttu-id="62095-147">**Migrácia ADAL**</span><span class="sxs-lookup"><span data-stu-id="62095-147">**ADAL Migration**</span></span>

<span data-ttu-id="62095-148">Odporúčame aktualizovať na [Microsoft Authentication Library (MSAL)](https://docs.microsoft.com/azure/active-directory/develop/v2-overview) s najnovšími funkciami a aktualizáciami zabezpečenia.</span><span class="sxs-lookup"><span data-stu-id="62095-148">We recommend updating to the [Microsoft Authentication Library (MSAL)](https://docs.microsoft.com/azure/active-directory/develop/v2-overview), which has the latest features and security updates.</span></span>

<span data-ttu-id="62095-149">Ak používate aplikácie spoločnosti Microsoft, viem, že spoločnosť Microsoft je v procese migrácie svojich aplikácií, aby MSAL podľa termínu ukončenia podpory, čím zabezpečí, že budú profitovať z priebežných vylepšení zabezpečenia a funkcií MSAL.</span><span class="sxs-lookup"><span data-stu-id="62095-149">If you are using Microsoft apps, know that Microsoft is in the process of migrating its applications to MSAL by the end-of-support deadline, ensuring they'll benefit from MSAL's ongoing security and feature improvements.</span></span>

1. [<span data-ttu-id="62095-150">Prečítajte si najčastejšie otázky o ADAL</span><span class="sxs-lookup"><span data-stu-id="62095-150">Read the ADAL FAQ</span></span>](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq)
2. [<span data-ttu-id="62095-151">Informácie o migrácii aplikácií na platforme</span><span class="sxs-lookup"><span data-stu-id="62095-151">Learn about how to migrate apps on a per-platform basis</span></span>](https://docs.microsoft.com/azure/active-directory/develop/msal-migration#frequently-asked-questions-faq)
3. <span data-ttu-id="62095-152">Ak potrebujete pomoc s pochopením, ktoré z vašich aplikácií používajú ADAL, odporúčame vám skontrolovať všetky zdrojové kódy aplikácií a prípadne osloviť všetkých nezávislých poskytovateľov služieb alebo poskytovateľov aplikácií.</span><span class="sxs-lookup"><span data-stu-id="62095-152">If you need help understanding which of your apps use ADAL, we recommend you review all of your apps' source code, and if applicable, reach out to any ISVs or app providers.</span></span> <span data-ttu-id="62095-153">Podpora spoločnosti Microsoft vám tiež môže poskytnúť zoznam všetkých aplikácií v nájomníkovi, ktoré nie sú aplikácie ADAL od spoločnosti Microsoft.</span><span class="sxs-lookup"><span data-stu-id="62095-153">Microsoft support can also provide you with a list of all non-Microsoft ADAL apps in your tenant.</span></span>

<span data-ttu-id="62095-154">**Migrácia AAD Graph**</span><span class="sxs-lookup"><span data-stu-id="62095-154">**AAD Graph Migration**</span></span>

<span data-ttu-id="62095-155">V prípade aplikácií, ktoré používajú Azure AD Graph, postupujte podľa pokynov na [migráciu aplikácií služby Azure AD Graph do programu Microsoft Graph](https://docs.microsoft.com/graph/migrate-azure-ad-graph-overview).</span><span class="sxs-lookup"><span data-stu-id="62095-155">For applications that are using Azure AD Graph, follow our guidance to [migrate Azure AD Graph apps to Microsoft Graph](https://docs.microsoft.com/graph/migrate-azure-ad-graph-overview).</span></span>

1. <span data-ttu-id="62095-156">[Náš kontrolný zoznam migrácie obsahuje informácie na začiatok](https://docs.microsoft.com/graph/migrate-azure-ad-graph-planning-checklist).</span><span class="sxs-lookup"><span data-stu-id="62095-156">[Our migration checklist provides a getting started point](https://docs.microsoft.com/graph/migrate-azure-ad-graph-planning-checklist).</span></span>
2. <span data-ttu-id="62095-157">Portál registrácie aplikácie Azure zobrazuje aplikácie, ktoré používajú AAD Graph.</span><span class="sxs-lookup"><span data-stu-id="62095-157">Your Azure app registration portal shows which applications are using AAD Graph.</span></span> <span data-ttu-id="62095-158">Odporúčame vám skontrolovať zdrojový kód všetkých aplikácií a v prípade potreby kontaktovať poskytovateľov internetových služieb alebo poskytovateľov aplikácií.</span><span class="sxs-lookup"><span data-stu-id="62095-158">We recommend you review all of your apps' source code, and if applicable, reach out to any ISVs or app providers.</span></span> <span data-ttu-id="62095-159">Technická podpora spoločnosti Microsoft vám tiež môže poskytnúť zoznam všetkých použití AAD grafov v nájomníkovi.</span><span class="sxs-lookup"><span data-stu-id="62095-159">Microsoft support can also provide you with a list of all AAD Graph usage in your tenant.</span></span>
3. <span data-ttu-id="62095-160">Pre aplikáciu na prístup k údajom v programe Microsoft Graph musí používateľ alebo správca udeliť správne povolenia prostredníctvom procesu súhlasu.</span><span class="sxs-lookup"><span data-stu-id="62095-160">For your app to access data in Microsoft Graph, the user or administrator must grant it the correct permissions via a consent process.</span></span> <span data-ttu-id="62095-161">V [odkaze na povolenia programu Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference) sú uvedené povolenia priradené k jednotlivým hlavným množinám rozhraní API programu Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="62095-161">The [Microsoft Graph permissions reference](https://docs.microsoft.com/graph/permissions-reference) lists the permissions associated with each major set of Microsoft Graph APIs.</span></span> <span data-ttu-id="62095-162">Poskytuje aj usmernenie o tom, ako používať povolenia.</span><span class="sxs-lookup"><span data-stu-id="62095-162">It also provides guidance about how to use the permissions.</span></span>