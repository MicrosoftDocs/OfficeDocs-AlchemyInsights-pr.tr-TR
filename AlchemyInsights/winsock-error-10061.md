---
title: 1554 Winsock hata 10061
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 12/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1554"
- "9000079"
ms.assetid: caecfa19-86c9-4aa4-9c83-b8a974ce60b9
ms.openlocfilehash: e82e90b670235848105636fb2039ed60d3b93c67
ms.sourcegitcommit: 5fb7a4b28859690020efdea630d03e70cc0e6334
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 06/28/2019
ms.locfileid: "35364933"
---
# <a name="winsock-error-10061"></a><span data-ttu-id="7211c-102">WINSOCK Hatası: 10061</span><span class="sxs-lookup"><span data-stu-id="7211c-102">Winsock error 10061</span></span>

<span data-ttu-id="7211c-103">Bu hata kodunu Office 365 (bağlantı) ile hedef ana bilgisayarı bir TCP Yuvasını kurmak uygulanamadı anlamına gelir.</span><span class="sxs-lookup"><span data-stu-id="7211c-103">This error code means that Office 365 couldn't establish a TCP socket (connection) with the target host.</span></span> <span data-ttu-id="7211c-104">Bu hatanın en olası nedeni, güvenlik duvarı yapılandırması ile ilgili bir sorun var.</span><span class="sxs-lookup"><span data-stu-id="7211c-104">The most likely cause of this error is a problem with your firewall configuration.</span></span> <span data-ttu-id="7211c-105">Sorunu gidermek için bu ayarları denetleyin:</span><span class="sxs-lookup"><span data-stu-id="7211c-105">To fix the problem, check these settings:</span></span>

- <span data-ttu-id="7211c-106">Bilgileri [Office 365 URL'leri ve IP adres aralıkları](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges) ile güvenlik duvarı yapılandırmanızı doğrulayın</span><span class="sxs-lookup"><span data-stu-id="7211c-106">Verify your firewall configuration with the information in [Office 365 URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges)</span></span>

- <span data-ttu-id="7211c-107">Hata Exchange çevrimiçi koruma (EOP) belirli ise, daha önce bir değişiklik [Exchange çevrimiçi koruma IP adresleri](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)için bildirildi.</span><span class="sxs-lookup"><span data-stu-id="7211c-107">If the error is specific to Exchange Online Protection (EOP), you should have been previously notified to a change to the [Exchange Online Protection IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>

- <span data-ttu-id="7211c-108">Internet servis sağlayıcınıza (ISS) bağlantı noktası engellemediğinden emin olun.</span><span class="sxs-lookup"><span data-stu-id="7211c-108">Verify that your Internet Service Provider (ISP) isn't blocking the port.</span></span>

- <span data-ttu-id="7211c-109">Bağlayıcılar, akıllı ana bilgisayar ve hedef sunucu ayarlarını doğrulayın.</span><span class="sxs-lookup"><span data-stu-id="7211c-109">Verify the smart host and target server settings in your connectors.</span></span>

<span data-ttu-id="7211c-110">Not Bu yolla *gelen* bağlantıları Office 365 engellemez.</span><span class="sxs-lookup"><span data-stu-id="7211c-110">Note that Office 365 doesn't block *incoming* connections in this manner.</span></span>
