---
title: SharePoint uyarı bildirimleri teslim edilmiyor
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 9225ec0f-771f-4d7a-8157-e188953107aa
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "1655"
ms.openlocfilehash: f4002dc865fb7a03b07a9256709b947d6d774cb0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47751263"
---
# <a name="sharepoint-alert-notifications-not-delivered"></a><span data-ttu-id="1cbe0-102">SharePoint uyarı bildirimleri teslim edilmiyor</span><span class="sxs-lookup"><span data-stu-id="1cbe0-102">SharePoint alert notifications not delivered</span></span>

<span data-ttu-id="1cbe0-103">E-postanızın gereksız klasörüne göz atın, bazen uyarılar orada görünebilir.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-103">Please check the JUNK folder in your email, as sometimes alerts might go there.</span></span>

<span data-ttu-id="1cbe0-104">**Tüm uyarıların teslim edilip edilmediğini** veya belirli bir dosya veya kitaplıktan gelen bir **uyarının** teslim edilmediğini saptayın.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-104">Determine if **all alerts are not delivered** or if **an individual alert** from a specific file or library is not delivered.</span></span>

- <span data-ttu-id="1cbe0-105">**Tek tek uyarılar teslim edilmiyor**: belirli bir dosya veya kitaplıktan gelen bir uyarı teslim edilemediğinde, bunu silip yeniden oluşturmayı deneyebilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-105">**Individual alerts are not delivered**: If an individual alert from a specific file or library is not delivered, you can attempt to delete and recreate it.</span></span> <span data-ttu-id="1cbe0-106">Uyarıyı yeniden oluşturmak için [SharePoint uyarılarını yönetme, görüntüleme veya silme](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) konusuna bakın.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-106">See [Manage, view, or delete SharePoint alerts](https://support.office.com/article/manage-view-or-delete-sharepoint-alerts-99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) to recreate the alert.</span></span>
- <span data-ttu-id="1cbe0-107">**Tüm uyarılar teslim edilmiyor**: birden çok dosya veya kitaplıklardaki tüm uyarılar teslim edilemezse, SharePoint veya Exchange ile ilgili tüm Danışma belgelerini/olaylarını denetlemek Için [hizmet durumu panosunu](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) ziyaret edin.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-107">**All alerts are not delivered**: If all alerts from multiple files or libraries are not delivered, visit the [Service Health dashboard](https://admin.microsoft.com/AdminPortal/Home#/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="1cbe0-108">Sorun SharePoint uyarısı yeteneği veya Exchange aracılığıyla e-postalarda gecikmelere neden olabilir.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-108">The issue could be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="1cbe0-109">Ayrıca, başka bir e-postanın teslim edilip edilmediğini de dikkate almak da gerekirse, sorun büyük olasılıkla Exchange gecikmelerinden kaynaklanıyor olabilir.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-109">It will also be important to note whether other email is being delivered, and if not, the issue is likely with Exchange delays.</span></span>

<span data-ttu-id="1cbe0-110">Uyarılarla ilgili SSS:</span><span class="sxs-lookup"><span data-stu-id="1cbe0-110">FAQ on alerts:</span></span>

- <span data-ttu-id="1cbe0-111">Uyarılar dağıtım grubuna gönderilemiyor, yalnızca güvenlik ve O365 grupları destekleniyor olabilir.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-111">It is not possible to send alerts to Distribution Group, only Security and O365 groups are supported.</span></span>
- <span data-ttu-id="1cbe0-112">Uyarı e-posta şablonlarını özelleştiremezsiniz; bunları sağlamak için Microsoft FLOW veya SharePoint Designer Iş akışını kullanmanız gerekir.</span><span class="sxs-lookup"><span data-stu-id="1cbe0-112">You cannot customize alert email templates; you need to use Microsoft FLOW or SharePoint Designer Workflow to achieve those.</span></span>

## <a name="related-topics"></a><span data-ttu-id="1cbe0-113">İlgili konular</span><span class="sxs-lookup"><span data-stu-id="1cbe0-113">Related Topics</span></span>

<span data-ttu-id="1cbe0-114">SharePoint Online 'da Microsoft akışını denemek mi istiyorsunuz?</span><span class="sxs-lookup"><span data-stu-id="1cbe0-114">Want to try Microsoft Flow in SharePoint Online?</span></span>

- [<span data-ttu-id="1cbe0-115">Akış oluştur</span><span class="sxs-lookup"><span data-stu-id="1cbe0-115">Create Flow</span></span>](https://support.office.com/article/a9c3e03b-0654-46af-a254-20252e580d01)

- [<span data-ttu-id="1cbe0-116">SharePoint ve akış</span><span class="sxs-lookup"><span data-stu-id="1cbe0-116">SharePoint and Flow</span></span>](https://flow.microsoft.com//blog/sharepoint-and-flow/)
