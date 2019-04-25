---
title: Riešenie problémov s chyba 404 súbor nebol nájdený
ms.author: kirks
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 1b15444c-367b-4523-8e08-1c77bbea7524
ms.openlocfilehash: 467feb3cb436a2e0135162657876e5c45d8d56bd
ms.sourcegitcommit: 03258ec4f5476a1ea6dd3a31d17bda815bc5a18a
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 04/24/2019
ms.locfileid: "33243676"
---
# <a name="troubleshoot-error-404-file-not-found"></a><span data-ttu-id="fb1c1-102">Riešenie problémov s chyba 404 súbor nebol nájdený</span><span class="sxs-lookup"><span data-stu-id="fb1c1-102">Troubleshoot Error 404, File not found</span></span>

<span data-ttu-id="fb1c1-103">404 chyba je prijaté pri užívateľov sa pokúšate prístup k lokalite alebo súbor SharePoint alebo OneDrive.</span><span class="sxs-lookup"><span data-stu-id="fb1c1-103">An Error 404 is received when users are attempting to access a site or file in SharePoint or OneDrive.</span></span> <span data-ttu-id="fb1c1-104">To je často spôsobené lokality alebo súbor alebo skupina dostať premenovaný, premiestnený alebo odstránený.</span><span class="sxs-lookup"><span data-stu-id="fb1c1-104">This is often caused by a site or file or group getting renamed, moved or deleted.</span></span> <span data-ttu-id="fb1c1-105">Napríklad: užívatelia budú mať chybu 404 pokúša získať prístup k koreňové kolekcie lokalít a bola odstránená.</span><span class="sxs-lookup"><span data-stu-id="fb1c1-105">For example: Users will experience a 404 Error attempting to access the Root Site Collection and it has been deleted.</span></span>

<span data-ttu-id="fb1c1-106">Riešenie chyba 404 pre web, ktorý bol premenovaný, premiestnený alebo odstránený:</span><span class="sxs-lookup"><span data-stu-id="fb1c1-106">To resolve Error 404 for a Site that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="fb1c1-107">Klasické weby, ktoré existujú v klasickom Admin Center, nájdete v časti [obnovenie kolekcie lokalít odstránené](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="fb1c1-107">For classic sites that exist in the Classic Admin Center, see [Restore a deleted site collection](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>


<span data-ttu-id="fb1c1-108">Moderných stránok (komunikácia, skupina-pripojený, alebo iné stránky), ktoré existujú nové SharePoint admin Center, nájdete v časti [Zobraziť a obnoviť odstránené lokalít v nových SharePoint admin center](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span><span class="sxs-lookup"><span data-stu-id="fb1c1-108">For modern sites (communication, group-connected, or other sites) that exist in the new SharePoint admin center, see [View and restore deleted sites in the new SharePoint admin center](https://docs.microsoft.com/en-us/sharepoint/restore-deleted-site-collection).</span></span>

<span data-ttu-id="fb1c1-109">Riešenie chyba 404 súbor (alebo iné položky), ktorý bol premenovaný, premiestnený alebo odstránený:</span><span class="sxs-lookup"><span data-stu-id="fb1c1-109">To resolve Error 404 for a File (or other item) that has been renamed, moved or deleted:</span></span>

<span data-ttu-id="fb1c1-110">Prejdite na lokalitu SharePoint alebo OneDrive a zobrazenie koša z lokality obsahu.</span><span class="sxs-lookup"><span data-stu-id="fb1c1-110">Go to the SharePoint or OneDrive site and view the Recycle Bin from the Site contents.</span></span> <span data-ttu-id="fb1c1-111">Pozri [obnovenie položiek v priečinku Kôš lokality SharePoint](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span><span class="sxs-lookup"><span data-stu-id="fb1c1-111">See, [Restore items in the Recycle Bin of a SharePoint site](https://support.office.com/en-us/article/Restore-items-in-the-Recycle-Bin-of-a-SharePoint-site-6df466b6-55f2-4898-8d6e-c0dff851a0be#ID0EAADAAA=Online).</span></span>

<span data-ttu-id="fb1c1-112">Ak stále nemôžete nájsť položku, môžete vyhľadávanie denník auditu, ak zapisovanie do denníka zapnuté Zobraziť, [vyhľadávanie audit prihlásiť do Office 365 zabezpečenia & centrum súladu](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span><span class="sxs-lookup"><span data-stu-id="fb1c1-112">If you are still unable to find the item you can search the audit log if logging is enabled see, [Search the audit log in the Office 365 Security & Compliance Center](https://docs.microsoft.com/en-us/office365/securitycompliance/search-the-audit-log-in-security-and-compliance?redirectSourcePath=%252fclient%252fsearch-the-audit-log-in-the-office-365-security-compliance-center-0d4d0f35-390b-4518-800e-0c7ec95e946c).</span></span>