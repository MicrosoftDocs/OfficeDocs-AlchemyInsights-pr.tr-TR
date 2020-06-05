---
title: SharePoint ve OneDrive uyarılarının alınmasında gecikmeler
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000118"
- "2642"
ms.openlocfilehash: 7f1033cec3abec782d1eee3b32128c4c60778913
ms.sourcegitcommit: 8e093114cd31141664e267a7c7b779398d5fdfa8
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 06/04/2020
ms.locfileid: "44563530"
---
# <a name="delays-in-receiving-sharepoint-and-onedrive-alerts"></a><span data-ttu-id="c0cdf-102">SharePoint ve OneDrive uyarılarının alınmasında gecikmeler</span><span class="sxs-lookup"><span data-stu-id="c0cdf-102">Delays in receiving SharePoint and OneDrive alerts</span></span>

- <span data-ttu-id="c0cdf-103">Önce e-postanızdaki Önemsiz veya Spam klasörünü kontrol edin.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-103">First check the Junk or Spam folder in your email.</span></span>
- <span data-ttu-id="c0cdf-104">**Birden çok dosya veya kitaplıktan gelen tüm uyarılar gecikirse,** SharePoint veya Exchange ile oluşabilecek danışma/olayları kontrol etmek için Hizmet Durumu [panosunu](https://portal.office.com/adminportal/home?ref=/servicehealth) ziyaret edin.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-104">If **all alerts from multiple files or libraries are delayed**, visit the [Service Health dashboard](https://portal.office.com/adminportal/home?ref=/servicehealth) to check for any advisories/incidents that may be occurring with SharePoint or Exchange.</span></span> <span data-ttu-id="c0cdf-105">Sorun, SharePoint uyarı yeteneği veya Exchange aracılığıyla e-postalardaki gecikmelerle ilgili olabilir.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-105">The issue might be with the SharePoint alert capability or delays in emails through Exchange.</span></span> <span data-ttu-id="c0cdf-106">Ayrıca, diğer e-postaların teslim edilip edilmediğine de dikkat edin, sorun büyük olasılıkla Exchange gecikmeleriyle birlikte dir.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-106">Also note whether other email is being delivered—if not, the issue is likely with Exchange delays.</span></span>
- <span data-ttu-id="c0cdf-107">**Belirli bir dosyadan veya kitaplıktan tek bir uyarı teslim edilmezse,** bu uyarıyı silmeye ve yeniden oluşturmaya çalışır.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-107">If **an individual alert from a specific file or library is not delivered**, attempt to delete and recreate it.</span></span> <span data-ttu-id="c0cdf-108">Uyarıyı yeniden oluşturmak için [SharePoint uyarılarını yönet, görüntüleyin veya silin.](https://support.microsoft.com/office/99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2)</span><span class="sxs-lookup"><span data-stu-id="c0cdf-108">See [Manage, view, or delete SharePoint alerts](https://support.microsoft.com/office/99dfb19c-9a90-4a8c-aba1-aa8c8afb0de2) to recreate the alert.</span></span>

> [!NOTE]
> - <span data-ttu-id="c0cdf-109">Uyarılar bir Dağıtım Grubuna gönderilemez.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-109">Alerts cannot be sent to a Distribution Group.</span></span> <span data-ttu-id="c0cdf-110">Yalnızca Güvenlik ve O365 grupları desteklenir.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-110">Only Security and O365 groups are supported.</span></span>
> - <span data-ttu-id="c0cdf-111">Uyarı e-posta şablonlarını özelleştiremezsiniz.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-111">You cannot customize alert email templates.</span></span> <span data-ttu-id="c0cdf-112">Bunları başarmak için Microsoft Akışını veya SharePoint Designer İş Akışını kullanmanız gerekir.</span><span class="sxs-lookup"><span data-stu-id="c0cdf-112">You must use Microsoft Flow or SharePoint Designer Workflow to achieve those.</span></span>
