---
title: SharePoint, OneDrive ve Microsoft ekipleri için ATP
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1037
ms.assetid: ''
ms.openlocfilehash: 3d02ded959114675847831690b4d4a3ebcf0e137
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47715581"
---
# <a name="atp-for-sharepoint-onedrive-and-microsoft-teams"></a><span data-ttu-id="7e51b-102">SharePoint, OneDrive ve Microsoft ekipleri için ATP</span><span class="sxs-lookup"><span data-stu-id="7e51b-102">ATP for SharePoint, OneDrive, and Microsoft Teams</span></span>

<span data-ttu-id="7e51b-103">Gelişmiş tehdit korumasını etkinleştirmek için şu adımları izleyin:</span><span class="sxs-lookup"><span data-stu-id="7e51b-103">Follow these steps to enable Advanced Threat Protection:</span></span>

1. <span data-ttu-id="7e51b-104">[https://protection.office.com](https://protection.office.com)Genel yönetici veya güvenlik yöneticisi hesabıyla gidin ve oturum açın.</span><span class="sxs-lookup"><span data-stu-id="7e51b-104">Go to [https://protection.office.com](https://protection.office.com) and sign in with a global administrator or security administrator account.</span></span>

2. <span data-ttu-id="7e51b-105">Gezinti bölmesinde **tehdit yönetimi**'nin altında, **ilke** \> **güvenli ekleri**'ni seçin.</span><span class="sxs-lookup"><span data-stu-id="7e51b-105">In the left navigation pane under **Threat management**, choose **Policy** \> **Safe Attachments**.</span></span>

3. <span data-ttu-id="7e51b-106">**SharePoint, OneDrive ve Microsoft ekipleri IÇIN ATP 'Yi aç**'ı seçin.</span><span class="sxs-lookup"><span data-stu-id="7e51b-106">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**.</span></span>

4. <span data-ttu-id="7e51b-107">Kötü amaçlı dosyaları algılamadığımdan bildirim almak için [etkinlik uyarısı Ilkesi oluşturun](https://docs.microsoft.com/microsoft-365/compliance/create-activity-alerts) .</span><span class="sxs-lookup"><span data-stu-id="7e51b-107">[Create an activity alert policy](https://docs.microsoft.com/microsoft-365/compliance/create-activity-alerts) to receive notifications when we detect malicious files.</span></span>

<span data-ttu-id="7e51b-108">Eksiksiz yönergeler için bu [konuya](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams)bakın.</span><span class="sxs-lookup"><span data-stu-id="7e51b-108">For complete instructions, see this [topic](https://docs.microsoft.com/microsoft-365/security/office-365-security/turn-on-atp-for-spo-odb-and-teams).</span></span>

<span data-ttu-id="7e51b-109">**Not**: tasarıma göre, ATP, SharePoint Online, OneDrive Iş veya Microsoft ekipte her dosyayı taramaz.</span><span class="sxs-lookup"><span data-stu-id="7e51b-109">**Note**: By design, ATP doesn't scan every single file in SharePoint Online, OneDrive for Business, or Microsoft Teams.</span></span> <span data-ttu-id="7e51b-110">Dosyalar, kötü amaçlı dosyaları belirlemek için paylaşım etkinliğini, Konuk etkinliğini ve tehdit sinyallerini kullanan bir süreç tarafından zaman uyumsuz olarak taranır.</span><span class="sxs-lookup"><span data-stu-id="7e51b-110">Files are scanned asynchronously by a process that uses sharing activity, guest activity, and threat signals to identify malicious files.</span></span> <span data-ttu-id="7e51b-111">Daha fazla bilgi için bu [konuya](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams)bakın.</span><span class="sxs-lookup"><span data-stu-id="7e51b-111">For more information, see this [topic](https://docs.microsoft.com/microsoft-365/security/office-365-security/atp-for-spo-odb-and-teams).</span></span>
