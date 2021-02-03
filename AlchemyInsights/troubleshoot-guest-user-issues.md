---
title: Riešenie problémov s hosťujúcimi používateľmi
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/18/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004358"
- "7822"
ms.openlocfilehash: 0f2a10b918fee067b167ab58ac2544a89e0c8ea1
ms.sourcegitcommit: 7b213fd5e8a3fdb5c602673dc194d576d372ac96
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 01/18/2021
ms.locfileid: "49901589"
---
# <a name="troubleshoot-guest-user-issues"></a><span data-ttu-id="ea323-102">Riešenie problémov s hosťujúcimi používateľmi</span><span class="sxs-lookup"><span data-stu-id="ea323-102">Troubleshoot guest user issues</span></span>

1. <span data-ttu-id="ea323-103">Pokyny na spravovanie hosťovského prístupu k aplikáciám nájdete v téme [spravovanie hosťovského prístupu pomocou recenzií Azure AD Accessu](https://docs.microsoft.com/azure/active-directory/governance/manage-guest-access-with-access-reviews).</span><span class="sxs-lookup"><span data-stu-id="ea323-103">For guidance on managing guest access to applications, see [Manage guest access with Azure AD access reviews](https://docs.microsoft.com/azure/active-directory/governance/manage-guest-access-with-access-reviews).</span></span>
1. <span data-ttu-id="ea323-104">[Pridanie hosťovských používateľov do adresára na portáli Azure](https://docs.microsoft.com/azure/active-directory/external-identities/b2b-quickstart-add-guest-users-portal): v tomto rýchlym pridávate nového hosťovského používateľa do adresára služby Azure AD prostredníctvom portálu Azure, odošlite pozvánku a zistite, ako vyzerá proces vyplatenia pozvania používateľa.</span><span class="sxs-lookup"><span data-stu-id="ea323-104">[Add guest users to your directory in the Azure portal](https://docs.microsoft.com/azure/active-directory/external-identities/b2b-quickstart-add-guest-users-portal): In this quickstart, you'll add a new guest user to your Azure AD directory via the Azure portal, send an invitation, and see what the guest user's invitation redemption process looks like.</span></span>
1. <span data-ttu-id="ea323-105">[Pridanie hosťujúceho používateľa s prostredím PowerShell](https://docs.microsoft.com/azure/active-directory/external-identities/b2b-quickstart-invite-powershell): v tomto rýchlym vykonaním použite príkaz New-AzureADMSInvitation na pridanie jedného hosťujúceho používateľa do nájomníka Azure.</span><span class="sxs-lookup"><span data-stu-id="ea323-105">[Add a guest user with PowerShell](https://docs.microsoft.com/azure/active-directory/external-identities/b2b-quickstart-invite-powershell): In this quickstart, you’ll use the New-AzureADMSInvitation command to add one guest user to your Azure tenant.</span></span>
1. <span data-ttu-id="ea323-106">Informácie o priradení používateľov a skupín k podnikovým aplikáciám v službe Azure Active Directory (Azure AD), a to buď z portálu Azure alebo pomocou prostredia PowerShell, nájdete [v téme Správa používateľských priradení aplikácie v službe Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/assign-user-or-group-access-portal).</span><span class="sxs-lookup"><span data-stu-id="ea323-106">To learn how to assign users, and groups, to enterprise applications in Azure Active Directory (Azure AD), either from within the Azure portal or by using PowerShell, see [Manage user assignment for an app in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/assign-user-or-group-access-portal).</span></span> 
1. <span data-ttu-id="ea323-107">Služby Azure Active Directory (Azure AD) B2B spolupráca spolupracuje s väčšinou aplikácií, ktoré integrujú s Azúrovou REKLAMou.</span><span class="sxs-lookup"><span data-stu-id="ea323-107">Azure Active Directory (Azure AD) B2B collaboration works with most apps that integrate with Azure AD.</span></span> <span data-ttu-id="ea323-108">V tomto [článku](https://docs.microsoft.com/azure/active-directory/external-identities/configure-saas-apps)prechádzame pokynmi na konfigurovanie niektorých obľúbených aplikácií SaaS na použitie so službou Azure AD B2B.</span><span class="sxs-lookup"><span data-stu-id="ea323-108">In this [article](https://docs.microsoft.com/azure/active-directory/external-identities/configure-saas-apps), we walk through instructions for configuring some popular SaaS apps for use with Azure AD B2B.</span></span>
1. <span data-ttu-id="ea323-109">Ako organizácia využívajúca funkcie na spoluprácu v službe Azure Active Directory (Azure AD) na pozvanie hosťujúcich používateľov z partnerských organizácií na vašu službu Azure AD teraz môžete týmto používateľom B2B poskytnúť prístup k lokálnym aplikáciám.</span><span class="sxs-lookup"><span data-stu-id="ea323-109">As an organization that uses Azure Active Directory (Azure AD) B2B collaboration capabilities to invite guest users from partner organizations to your Azure AD, you can now provide these B2B users access to on-premises apps.</span></span> <span data-ttu-id="ea323-110">Tieto lokálne aplikácie môžu používať overovanie na základe SAML alebo integrované overovanie systému Windows (IWA) s delegovanou delegovanou protokolom Kerberos (KCD).</span><span class="sxs-lookup"><span data-stu-id="ea323-110">These on-premises apps can use SAML-based authentication or Integrated Windows Authentication (IWA) with Kerberos constrained delegation (KCD).</span></span> <span data-ttu-id="ea323-111">Ďalšie informácie nájdete v téme [udelenie prístupu používateľom B2B v službe Azure AD Accessu do lokálnych aplikácií](https://docs.microsoft.com/azure/active-directory/external-identities/hybrid-cloud-to-on-premises).</span><span class="sxs-lookup"><span data-stu-id="ea323-111">For more information, see [Grant B2B users in Azure AD access to your on-premises applications](https://docs.microsoft.com/azure/active-directory/external-identities/hybrid-cloud-to-on-premises).</span></span>
1. <span data-ttu-id="ea323-112">Zistite, ako [udeliť lokálne spravovaným partnerom kontá prístup k cloudovým zdrojom pomocou služby Azure AD B2B Collaboration](https://docs.microsoft.com/azure/active-directory/external-identities/hybrid-on-premises-to-cloud).</span><span class="sxs-lookup"><span data-stu-id="ea323-112">Learn how to [grant locally-managed partner accounts access to cloud resources using Azure AD B2B collaboration](https://docs.microsoft.com/azure/active-directory/external-identities/hybrid-on-premises-to-cloud).</span></span>