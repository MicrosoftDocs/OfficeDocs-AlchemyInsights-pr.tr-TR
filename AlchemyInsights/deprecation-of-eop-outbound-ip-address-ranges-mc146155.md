---
title: 1065, deprecation EOP giden IP adresi rangesMC146155
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 9/28/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1065
ms.assetid: bd41784e-8002-428d-bc19-25671cfd34e8
ms.openlocfilehash: 0def0a93c61ea762918f1c9e6edb2e9b04446851
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30777291"
---
# <a name="deprecation-of-eop-outbound-ip-address-ranges"></a><span data-ttu-id="eec66-102">Deprecation, EOP giden IP adresi aralıkları</span><span class="sxs-lookup"><span data-stu-id="eec66-102">Deprecation of EOP outbound IP address ranges</span></span>

<span data-ttu-id="eec66-103">Biz (26 Ekim 2018 tarafından giderilen değil ise) posta akışı için şirket içi veya dış hedeflere kesilebilir, kuruluşunuzla ilgili olası bir sorun algılandı.</span><span class="sxs-lookup"><span data-stu-id="eec66-103">We've detected a potential issue with your organization that (if not corrected by October 26th, 2018) might break mail flow to your on-premises or external destinations.</span></span> <span data-ttu-id="eec66-104">Olarak önceden tanımlanmış, IP adres aralığı yönetimini basitleştirmek için biz Office 365 dışında e-posta alıp göndermek için kullanılan döviz çevrimiçi koruma (EOP) IP adres aralıklarını birleştirmek.</span><span class="sxs-lookup"><span data-stu-id="eec66-104">As previously communicated, to simplify IP address range management, we're consolidating the Exchange Online Protection (EOP) IP address ranges that are used to send and receive email outside of Office 365.</span></span> <span data-ttu-id="eec66-105">Bizim çözümlemesi bir veya daha fazla dış e-posta kaynak ve posta akışı bağlayıcılar yapılandırdıınız hedefleri IP adres aralıklarını gösterilen [Buraya](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)gelen bağlantıları kabul olmayan gösterir.</span><span class="sxs-lookup"><span data-stu-id="eec66-105">Our analysis indicates that one or more of the external email sources or destinations that you've configured in mail flow connectors aren't accepting connections from the IP address ranges shown [here](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="eec66-106">Bu kaynaklar ve hedefler [EOP IP adresleri yayınlanan](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses)tüm gelen ve giden bağlantıları kabul emin olmak için 26 Ekim önce davranır.</span><span class="sxs-lookup"><span data-stu-id="eec66-106">Act before October 26th to ensure these sources and destinations will accept connections to and from all [published EOP IP addresses](https://docs.microsoft.com/office365/SecurityCompliance/eop/exchange-online-protection-ip-addresses).</span></span>
  
<span data-ttu-id="eec66-107">Bu değişiklik hakkında daha fazla bilgi için lütfen ileti Merkezi [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620)veya [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274)nakleder bakın.</span><span class="sxs-lookup"><span data-stu-id="eec66-107">For more information about this change, please see Message Center posts [MC146155](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC146155), [MC148620](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC148620), or [MC149274](https://portal.office.com/AdminPortal/home?switchtomodern=true#/MessageCenter?id=MC149274).</span></span>
  
 <span data-ttu-id="eec66-108">**Not**: HTML, XML ve RSS üzerinden IP veya URL Yayımlama bitiş noktası güncelleştirmeleri daha önce kullandıysanız, siz de bu tür güncelleştirmeler otomatikleştirmek için yeni web hizmetlerine geçirmeniz gerekir.</span><span class="sxs-lookup"><span data-stu-id="eec66-108">**Note**: If you previously used IP or URL publishing via HTML, XML, and RSS for endpoint updates, you also should migrate to the new web services for automating these types of updates.</span></span> <span data-ttu-id="eec66-109">Daha fazla bilgi için bkz: [Office 365 bitiş noktası kategoriler ve Office 365 IP adresi ve web hizmeti URL'si](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span><span class="sxs-lookup"><span data-stu-id="eec66-109">For more information, see [Office 365 endpoint categories and Office 365 IP Address and URL web service](https://techcommunity.microsoft.com/t5/Office-365-Blog/Announcing-Office-365-endpoint-categories-and-Office-365-IP/ba-p/177638).</span></span>
  
