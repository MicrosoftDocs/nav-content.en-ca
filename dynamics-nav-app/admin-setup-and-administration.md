---
title: Administrative tasks in Dynamics NAV
description: Some tasks in [!INCLUDE[d365fin](includes/d365fin_md.md)] requires central administration and setup. See what they are and learn what to do.
author: edupont04
ms.prod: dynamics-nav-2017
ms.topic: article
ms.devlang: na
ms.tgt_pltfrm: na
ms.workload: na
ms.search.keywords: 
ms.date: 09/01/2017
ms.author: edupont
ms.translationtype: HT
ms.sourcegitcommit: 4fefaef7380ac10836fcac404eea006f55d8556f
ms.openlocfilehash: 873c8e6f9887ef49d8639851bb64013d985e640e
ms.contentlocale: en-ca
ms.lasthandoff: 10/16/2017

---
# <a name="setup-and-administration-in-dynamics-nav"></a><span data-ttu-id="2319c-104">Setup and Administration in Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="2319c-104">Setup and Administration in Dynamics NAV</span></span>
<span data-ttu-id="2319c-105">Central administration tasks are usually performed by one role in the company.</span><span class="sxs-lookup"><span data-stu-id="2319c-105">Central administration tasks are usually performed by one role in the company.</span></span> <span data-ttu-id="2319c-106">The scope of these tasks can depend on the company's size and the administrator's job responsibilities.</span><span class="sxs-lookup"><span data-stu-id="2319c-106">The scope of these tasks can depend on the company's size and the administrator's job responsibilities.</span></span> <span data-ttu-id="2319c-107">These tasks can include managing database synchronization of job and email queues, setting up users, customizing the user interface, and managing encryption keys.</span><span class="sxs-lookup"><span data-stu-id="2319c-107">These tasks can include managing database synchronization of job and email queues, setting up users, customizing the user interface, and managing encryption keys.</span></span>  

<span data-ttu-id="2319c-108">Entering the correct setup values from the start is important to the success of any new business software.</span><span class="sxs-lookup"><span data-stu-id="2319c-108">Entering the correct setup values from the start is important to the success of any new business software.</span></span> [!INCLUDE[d365fin](includes/d365fin_md.md)]<span data-ttu-id="2319c-109"> includes a number of setup guides that help you set up core data.</span><span class="sxs-lookup"><span data-stu-id="2319c-109"> includes a number of setup guides that help you set up core data.</span></span> <span data-ttu-id="2319c-110">For more information, see [Setting Up Dynamics NAV](setup.md).</span><span class="sxs-lookup"><span data-stu-id="2319c-110">For more information, see [Setting Up Dynamics NAV](setup.md).</span></span>

<!--Whether you use [!INCLUDE[rim](../../includes/rim_md.md)] to implement setup values or you manually enter them in the new company, you can support your setup decisions with some general recommendations for selected setup fields that are known to potentially cause the solution to be inefficient if defined incorrectly.-->  

<span data-ttu-id="2319c-111">A super user or an administrator can set up the Data Exchange Framework to enable users to export and import data in bank and payroll files, for example for various cash management processes.</span><span class="sxs-lookup"><span data-stu-id="2319c-111">A super user or an administrator can set up the Data Exchange Framework to enable users to export and import data in bank and payroll files, for example for various cash management processes.</span></span>  

<span data-ttu-id="2319c-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span><span class="sxs-lookup"><span data-stu-id="2319c-112">The following table describes a sequence of tasks, with links to the topics that describe them.</span></span>   

|<span data-ttu-id="2319c-113">**To**</span><span class="sxs-lookup"><span data-stu-id="2319c-113">**To**</span></span>|<span data-ttu-id="2319c-114">**See**</span><span class="sxs-lookup"><span data-stu-id="2319c-114">**See**</span></span>|  
|------------|-------------|  
|<span data-ttu-id="2319c-115">Add users, manage permissions and access to data, assign roles.</span><span class="sxs-lookup"><span data-stu-id="2319c-115">Add users, manage permissions and access to data, assign roles.</span></span>|[<span data-ttu-id="2319c-116">Users, Profiles, and Role Centres in Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="2319c-116">Users, Profiles, and Role Centers in Dynamics NAV</span></span>](admin-users-profiles-roles.md)|  
|<span data-ttu-id="2319c-117">Track all direct modifications that users make to data in the database to identify the origin of errors and data changes.</span><span class="sxs-lookup"><span data-stu-id="2319c-117">Track all direct modifications that users make to data in the database to identify the origin of errors and data changes.</span></span>|[<span data-ttu-id="2319c-118">Logging Changes in Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="2319c-118">Logging Changes in Dynamics NAV</span></span>](across-log-changes.md)|  
|<span data-ttu-id="2319c-119">Support your setup decisions with recommendations for selected fields that are known to potentially cause the solution to be inefficient if set up incorrectly</span><span class="sxs-lookup"><span data-stu-id="2319c-119">Support your setup decisions with recommendations for selected fields that are known to potentially cause the solution to be inefficient if set up incorrectly</span></span>|[<span data-ttu-id="2319c-120">Set Up Complex Application Areas Using Best Practices</span><span class="sxs-lookup"><span data-stu-id="2319c-120">Set Up Complex Application Areas Using Best Practices</span></span>](set-up-complex-application-areas-using-best-practices.md)|  
|<span data-ttu-id="2319c-121">Expose pages, codeunits, and queries as web services.</span><span class="sxs-lookup"><span data-stu-id="2319c-121">Expose pages, codeunits, and queries as web services.</span></span>|[<span data-ttu-id="2319c-122">How to: Publish a Web Service</span><span class="sxs-lookup"><span data-stu-id="2319c-122">How to: Publish a Web Service</span></span>](across-how-publish-web-service.md)|  
|<span data-ttu-id="2319c-123">Set up an SMTP server to enable e-mail communication in and out of Dynamics NAV</span><span class="sxs-lookup"><span data-stu-id="2319c-123">Set up an SMTP server to enable e-mail communication in and out of Dynamics NAV</span></span>| [<span data-ttu-id="2319c-124">How to: Set Up Email Manually or Using the Assisted Setup</span><span class="sxs-lookup"><span data-stu-id="2319c-124">How to: Set Up Email Manually or Using the Assisted Setup</span></span>](madeira-how-setup-email.md)|  
|<span data-ttu-id="2319c-125">Enter single or recurring requests to run reports or codeunits.</span><span class="sxs-lookup"><span data-stu-id="2319c-125">Enter single or recurring requests to run reports or codeunits.</span></span>|[<span data-ttu-id="2319c-126">Use Job Queues to Schedule Tasks</span><span class="sxs-lookup"><span data-stu-id="2319c-126">Use Job Queues to Schedule Tasks</span></span>](admin-job-queues-schedule-tasks.md)|  
|<span data-ttu-id="2319c-127">Manage, delete, or compress documents</span><span class="sxs-lookup"><span data-stu-id="2319c-127">Manage, delete, or compress documents</span></span>|[<span data-ttu-id="2319c-128">Manage Documents</span><span class="sxs-lookup"><span data-stu-id="2319c-128">Manage Documents</span></span>](admin-manage-documents.md)|  

## <a name="see-also"></a><span data-ttu-id="2319c-129">See Also</span><span class="sxs-lookup"><span data-stu-id="2319c-129">See Also</span></span>
[<span data-ttu-id="2319c-130">Overview of Business Functionality</span><span class="sxs-lookup"><span data-stu-id="2319c-130">Overview of Business Functionality</span></span>](madeira-business-functionality.md)  
[<span data-ttu-id="2319c-131">General Business Functionality</span><span class="sxs-lookup"><span data-stu-id="2319c-131">General Business Functionality</span></span>](ui-across-business-areas.md)  
<span data-ttu-id="2319c-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span><span class="sxs-lookup"><span data-stu-id="2319c-132">[Working with [!INCLUDE[d365fin](includes/d365fin_md.md)]](ui-work-product.md)</span></span>  
<span data-ttu-id="2319c-133">[Welcome to [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span><span class="sxs-lookup"><span data-stu-id="2319c-133">[Welcome to [!INCLUDE[d365fin](includes/d365fin_md.md)]](index.md)</span></span>  

