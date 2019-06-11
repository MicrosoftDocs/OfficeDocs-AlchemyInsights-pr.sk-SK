---
title: Začíname s SharePoint Online
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: afb1ef115d364ee3e2cf09ea850adb57ad1d44e6
ms.sourcegitcommit: 136b8209c52c2a05d0f2fdaab93b2cd92253fa2c
ms.translationtype: MT
ms.contentlocale: sk-SK
ms.lasthandoff: 06/07/2019
ms.locfileid: "34770577"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="060a1-102">Toky činností na lokalite SharePoint</span><span class="sxs-lookup"><span data-stu-id="060a1-102">Workflows in SharePoint</span></span>

<span data-ttu-id="060a1-103">Ak pracovné postupy služby SharePoint nie odosielanie e-mailov, organizácii narazili Exchange Online obmedzenia odosielateľa.</span><span class="sxs-lookup"><span data-stu-id="060a1-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.</span></span>

<span data-ttu-id="060a1-104">"Je prerušený pracovného postupu" chybové hlásenie sa môže vyskytnúť, ak máte jednu z nasledujúcich položiek:</span><span class="sxs-lookup"><span data-stu-id="060a1-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span>

- <span data-ttu-id="060a1-105">Máte pracovného postupu SharePoint Online, používajúce SharePoint 2010 alebo SharePoint 2013 pracovného postupu typ platformy.</span><span class="sxs-lookup"><span data-stu-id="060a1-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span>

- <span data-ttu-id="060a1-106">Pracovný postup je nakonfigurovaný na odosielanie vlastné e-mailové správy vyše 200 používateľov, viac ako 10 000 príjemcov za deň, alebo viac ako 30 správ za minútu.</span><span class="sxs-lookup"><span data-stu-id="060a1-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span>

<span data-ttu-id="060a1-107">Pri spustení pracovného postupu, emailovú správu nie je odoslaná a spozorujete chybové hlásenie, vnútorný stav je nastavený na zavesené alebo nie je možné Odoslať príjemcovi je zobrazená.</span><span class="sxs-lookup"><span data-stu-id="060a1-107">When you run the workflow, the email message isn't sent, and you notice the error message, Internal Status is set to Suspended or Unable to send to a recipient is displayed.</span></span>

<span data-ttu-id="060a1-108">Ďalšie informácie nájdete v nasledujúcom [článku](https://support.office.com/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span><span class="sxs-lookup"><span data-stu-id="060a1-108">For more information, please refer to the following [article](https://support.office.com/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US).</span></span>
