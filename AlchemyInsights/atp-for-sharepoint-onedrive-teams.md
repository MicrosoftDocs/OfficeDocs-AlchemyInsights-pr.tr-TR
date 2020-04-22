---
title: SharePoint, OneDrive ve Microsoft Ekipleri için ATP
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1037
ms.assetid: ''
ms.openlocfilehash: 28046c61e1aedbb2c07cca3fc01b118d0dc3c143
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43712478"
---
# <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="ad421-102">SharePoint, OneDrive ve Microsoft Ekipleri için ATP</span><span class="sxs-lookup"><span data-stu-id="ad421-102">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="ad421-103">Gelişmiş Tehdit Koruması sağlamak için aşağıdaki adımları izleyin:</span><span class="sxs-lookup"><span data-stu-id="ad421-103">Follow these steps to enable Advanced Threat Protection:</span></span>

1. <span data-ttu-id="ad421-104">Genel [https://protection.office.com](https://protection.office.com) bir yönetici veya güvenlik yöneticisi hesabıyla oturum açın ve oturum açın.</span><span class="sxs-lookup"><span data-stu-id="ad421-104">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

2. <span data-ttu-id="ad421-105">**Tehdit yönetimi**altında sol gezinti bölmesinde, **İlke** \> **Güvenli Ekler**seçin.</span><span class="sxs-lookup"><span data-stu-id="ad421-105">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Attachments**.</span></span>

3. <span data-ttu-id="ad421-106">**SharePoint, OneDrive ve Microsoft Teams için ATP'yi aç'ı**seçin.</span><span class="sxs-lookup"><span data-stu-id="ad421-106">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**.</span></span>

4. <span data-ttu-id="ad421-107">Kötü amaçlı dosyaları algıladığımızda bildirim almak için [bir etkinlik uyarı ilkesi oluşturun.](https://docs.microsoft.com/office365/securitycompliance/create-activity-alerts)</span><span class="sxs-lookup"><span data-stu-id="ad421-107">[Create an activity alert policy](https://docs.microsoft.com/office365/securitycompliance/create-activity-alerts) to receive notifications when we detect malicious files.</span></span>

<span data-ttu-id="ad421-108">Tam yönergeler için bu [konuya](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams)bakın.</span><span class="sxs-lookup"><span data-stu-id="ad421-108">For complete instructions, see this [topic](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams).</span></span>

<span data-ttu-id="ad421-109">**Not**: ATP, tasarım gereği SharePoint Online, OneDrive for Business veya Microsoft Teams'deki her bir dosyayı taramaz.</span><span class="sxs-lookup"><span data-stu-id="ad421-109">**Note**: By design, ATP doesn't scan every single file in SharePoint Online, OneDrive for Business, or Microsoft Teams.</span></span> <span data-ttu-id="ad421-110">Dosyalar, kötü amaçlı dosyaları tanımlamak için paylaşım etkinliği, konuk etkinliği ve tehdit sinyallerini kullanan bir işlem tarafından eşzamanlı olarak taranır.</span><span class="sxs-lookup"><span data-stu-id="ad421-110">Files are scanned asynchronously by a process that uses sharing activity, guest activity, and threat signals to identify malicious files.</span></span> <span data-ttu-id="ad421-111">Daha fazla bilgi için bu [konuya](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams)bakın.</span><span class="sxs-lookup"><span data-stu-id="ad421-111">For more information, see this [topic](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>
