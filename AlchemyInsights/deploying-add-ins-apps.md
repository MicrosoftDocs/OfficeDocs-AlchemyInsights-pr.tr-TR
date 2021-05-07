---
title: Eklentiler için eklentileri Microsoft 365 Uygulamaları
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/30/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "11107"
- "9005477"
ms.openlocfilehash: a878a35ba9b530ce22ca7c263d20bd942d6896a8
ms.sourcegitcommit: 6c6b0c3885f33b08db929fe0b6496508d31fa2d6
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 05/06/2021
ms.locfileid: "52233554"
---
# <a name="deploying-add-ins-for-microsoft-365-apps"></a><span data-ttu-id="74a52-102">Eklentiler için eklentileri Microsoft 365 Uygulamaları</span><span class="sxs-lookup"><span data-stu-id="74a52-102">Deploying add-ins for Microsoft 365 Apps</span></span>

<span data-ttu-id="74a52-103">Merkezi Dağıtım, eklentilerin, kuruluş içindeki kullanıcılara Office dağıtımı için önerilen yoldur.</span><span class="sxs-lookup"><span data-stu-id="74a52-103">Centralized Deployment is the recommended way for deploying Office add-ins to users and groups within your organization.</span></span> <span data-ttu-id="74a52-104">Eklentileri dağıtmak için aşağıdaki adımları izleyin:</span><span class="sxs-lookup"><span data-stu-id="74a52-104">To deploy add-ins, follow the steps below:</span></span>

<span data-ttu-id="74a52-105">**Not:** Kullanıcılara eklentileri yüklemek Office için bkz. Office programlarında [eklentileri görüntüleme, yönetme Office yükleme.](https://support.microsoft.com/topic/view-manage-and-install-add-ins-in-office-programs-16278816-1948-4028-91e5-76dca5380f8d)</span><span class="sxs-lookup"><span data-stu-id="74a52-105">**Note:** To install add-ins for Office as an individual user, see [View, manage, and install add-ins in Office programs](https://support.microsoft.com/topic/view-manage-and-install-add-ins-in-office-programs-16278816-1948-4028-91e5-76dca5380f8d).</span></span> <span data-ttu-id="74a52-106">Ayrıca, Mağaza eklentilerinin ayrı Office satın alımının etkinleştirildiğinden emin olun.</span><span class="sxs-lookup"><span data-stu-id="74a52-106">Also, make sure that individual acquisition of Office Store add-ins is enabled.</span></span> <span data-ttu-id="74a52-107">Ayrıntılar için [bkz. tüm istemcilerde Office Store'Office indirmelerini](https://docs.microsoft.com/microsoft-365/admin/manage/manage-addins-in-the-admin-center?view=o365-worldwide#prevent-add-in-downloads-by-turning-off-the-office-store-across-all-clients-except-outlook)engelleme (Outlook).</span><span class="sxs-lookup"><span data-stu-id="74a52-107">For details, see [Prevent add-in downloads by turning off the Office Store across all clients (Except Outlook)](https://docs.microsoft.com/microsoft-365/admin/manage/manage-addins-in-the-admin-center?view=o365-worldwide#prevent-add-in-downloads-by-turning-off-the-office-store-across-all-clients-except-outlook).</span></span>

1. <span data-ttu-id="74a52-108">Merkezi Dağıtım kullanarak ortamının eklentilerin dağıtımıyla ilgili gereksinimleri karşı olduğundan emin olun.</span><span class="sxs-lookup"><span data-stu-id="74a52-108">Ensure that your environment meets the requirements for deployment of add-ins using Centralized Deployment.</span></span> <span data-ttu-id="74a52-109">Ayrıntılar için bkz. [Gereksinimler](https://docs.microsoft.com/microsoft-365/admin/manage/centralized-deployment-of-add-ins?#requirements).</span><span class="sxs-lookup"><span data-stu-id="74a52-109">For details, see [Requirements](https://docs.microsoft.com/microsoft-365/admin/manage/centralized-deployment-of-add-ins?#requirements).</span></span>
2. <span data-ttu-id="74a52-110">Tümleştirilmiş **Ayarlar**  >  **Eklentilerin** dağıtımı  >  **için** Microsoft 365 Yönetim Merkezinde Uygulamaları edinin'e gidin.</span><span class="sxs-lookup"><span data-stu-id="74a52-110">Go to **Settings** > **Integrated Apps** > **Get apps** in the Microsoft 365 admin center to deploy add-ins.</span></span> 

<span data-ttu-id="74a52-111">Notlar:</span><span class="sxs-lookup"><span data-stu-id="74a52-111">Notes:</span></span> 

- <span data-ttu-id="74a52-112">Tümleşik Uygulamalar için yöneticinin Genel Yönetici veya Yönetici Exchange olması gerekir.</span><span class="sxs-lookup"><span data-stu-id="74a52-112">Integrated Apps requires that the admin has Global Admin or Exchange Admin permissions.</span></span>

- <span data-ttu-id="74a52-113">Eklentileri birden çok kullanıcıya dağıtırken, tek tek kullanıcılar yerine grupları kullanarak atamalar yapmalarını öneririz.</span><span class="sxs-lookup"><span data-stu-id="74a52-113">When deploying add-ins to multiple users, we recommend making assignments by using groups instead of individual users.</span></span> <span data-ttu-id="74a52-114">Ayrıntılar için [bkz. Kullanıcılara ve gruplara eklenti atarken dikkate alınacak noktalar](https://docs.microsoft.com/microsoft-365/admin/manage/manage-deployment-of-add-ins?view=o365-worldwide#considerations-when-assigning-an-add-in-to-users-and-groups).</span><span class="sxs-lookup"><span data-stu-id="74a52-114">For details, see [Considerations when assigning an add-in to users and groups](https://docs.microsoft.com/microsoft-365/admin/manage/manage-deployment-of-add-ins?view=o365-worldwide#considerations-when-assigning-an-add-in-to-users-and-groups).</span></span>

- <span data-ttu-id="74a52-115">Merkezi Dağıtım, iç içe gruplarda veya üst grupları olan gruplarda bulunan kullanıcıları desteklemez.</span><span class="sxs-lookup"><span data-stu-id="74a52-115">Centralized Deployment doesn't support users in nested groups or groups that have parent groups.</span></span> <span data-ttu-id="74a52-116">Ayrıntılar için [bkz. Kullanıcı ve grup atamaları](https://docs.microsoft.com/microsoft-365/admin/manage/centralized-deployment-of-add-ins?view=o365-worldwide#user-and-group-assignments).</span><span class="sxs-lookup"><span data-stu-id="74a52-116">For details, see [User and group assignments](https://docs.microsoft.com/microsoft-365/admin/manage/centralized-deployment-of-add-ins?view=o365-worldwide#user-and-group-assignments).</span></span>

- <span data-ttu-id="74a52-117">Kullanıcıların oturum açması için Microsoft 365 Uygulama Yönetim Hizmeti'nin (GUID: '0517ffae-825d-4aff-999e-3f2336b8a20a') etkinleştirildiğinden emin olun.</span><span class="sxs-lookup"><span data-stu-id="74a52-117">Ensure that the Microsoft 365 App Management Service (GUID: '0517ffae-825d-4aff-999e-3f2336b8a20a') is enabled for users to sign in.</span></span> <span data-ttu-id="74a52-118">Ayrıntılar için [bkz. Uygulama özelliklerini yapılandırma.](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure#configure-app-properties)</span><span class="sxs-lookup"><span data-stu-id="74a52-118">For details, see [Configure app properties](https://docs.microsoft.com/azure/active-directory/manage-apps/add-application-portal-configure#configure-app-properties).</span></span>

- <span data-ttu-id="74a52-119">Tümleşik Uygulamaları kullanarak eklentilerin dağıtımında sorun yaşanıyorsa, Eklentileri kullanarak [dağıtmayı deneyin.](https://admin.microsoft.com/AdminPortal/Home?#/Settings/AddIns)</span><span class="sxs-lookup"><span data-stu-id="74a52-119">If you experience issues deploying add-ins by using Integrated Apps, try deploying by using [Add-Ins](https://admin.microsoft.com/AdminPortal/Home?#/Settings/AddIns).</span></span>

<span data-ttu-id="74a52-120">Daha fazla bilgi için bkz.:</span><span class="sxs-lookup"><span data-stu-id="74a52-120">For more information, see:</span></span>

<span data-ttu-id="74a52-121">[Yönetim merkezinde eklentileri dağıtma](https://docs.microsoft.com/microsoft-365/admin/manage/manage-deployment-of-add-ins) 
 [Yönetim merkezinde eklentileri yönetme](https://docs.microsoft.com/microsoft-365/admin/manage/manage-addins-in-the-admin-center) 
 [Eklentileri yönetmek için Merkezi Dağıtım PowerShell cmdlet'lerini kullanma](https://docs.microsoft.com/microsoft-365/enterprise/use-the-centralized-deployment-powershell-cmdlets-to-manage-add-ins) 
 [Yönetim Office Merkezi Dağıtım kullanarak Eklentileri Yayımlama Microsoft 365 yayımlama](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment#publish-an-office-add-in-via-centralized-deployment) 
 [Sorun giderme: Kullanıcı eklentileri görmüyor](https://docs.microsoft.com/office365/troubleshoot/access-management/user-not-seeing-add-ins) 
 [Eklentilerle kullanıcı Office sorunlarını giderme](https://docs.microsoft.com/office/dev/add-ins/testing/testing-and-troubleshooting)</span><span class="sxs-lookup"><span data-stu-id="74a52-121">[Deploy add-ins in the admin center](https://docs.microsoft.com/microsoft-365/admin/manage/manage-deployment-of-add-ins)
[Manage add-ins in the admin center](https://docs.microsoft.com/microsoft-365/admin/manage/manage-addins-in-the-admin-center)
[Use the Centralized Deployment PowerShell cmdlets to manage add-ins](https://docs.microsoft.com/microsoft-365/enterprise/use-the-centralized-deployment-powershell-cmdlets-to-manage-add-ins)
[Publish Office Add-ins using Centralized Deployment via the Microsoft 365 admin center](https://docs.microsoft.com/office/dev/add-ins/publish/centralized-deployment#publish-an-office-add-in-via-centralized-deployment)
[Troubleshoot: User not seeing add-ins](https://docs.microsoft.com/office365/troubleshoot/access-management/user-not-seeing-add-ins)
[Troubleshoot user errors with Office Add-ins](https://docs.microsoft.com/office/dev/add-ins/testing/testing-and-troubleshooting)</span></span>