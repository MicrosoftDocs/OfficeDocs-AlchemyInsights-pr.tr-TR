---
title: DLP beklendiği gibi çalışmıyor
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 1/9/2019
ms.audience: ITPro
ms.topic: article
ms.prod: office-online-server
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1241"
- "3200001"
ms.assetid: f6fcf5ad-55a1-4f25-af27-1f7c1ce06409
ms.openlocfilehash: 102c8025571f840cf64091d75295acec50661df2
ms.sourcegitcommit: 1d98db8acb9959aba3b5e308a567ade6b62da56c
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 08/22/2019
ms.locfileid: "36530319"
---
# <a name="dlp-not-working-as-expected"></a><span data-ttu-id="2716b-102">DLP beklendiği gibi çalışmıyor</span><span class="sxs-lookup"><span data-stu-id="2716b-102">DLP not working as expected</span></span>

<span data-ttu-id="2716b-103">Office 365'de beklendiği gibi çalışmıyor **Veri kaybını önleme (DLP)** ile ilgili sorunlar yaşıyorsunuz?</span><span class="sxs-lookup"><span data-stu-id="2716b-103">Are you having problems with **Data Loss Prevention (DLP)** in Office 365 not working as expected?</span></span> <span data-ttu-id="2716b-104">Bu durumda, **DLP İlkesi** doğru ayarlandığından ve onu değerlendirildiğinde verilerinizi **DLP İlkesi** içeren aradığı emin olun.</span><span class="sxs-lookup"><span data-stu-id="2716b-104">If so, make sure that your **DLP policy** is set up correctly, and that your data contains what the **DLP policy** is looking for when it is being evaluated.</span></span>
  
 <span data-ttu-id="2716b-105">**DLP kurma**</span><span class="sxs-lookup"><span data-stu-id="2716b-105">**Setting up DLP**</span></span>
  
<span data-ttu-id="2716b-106">DLP ilkeleri belirlemenize ve kuruluşunuz içindeki hassas bilgileri korumak sağlar.</span><span class="sxs-lookup"><span data-stu-id="2716b-106">DLP policies allows you to identify and protect sensitive information in your organization.</span></span> <span data-ttu-id="2716b-107">DLP ilkeleri Kurulum, bilgileri kullanmak için [burada](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span><span class="sxs-lookup"><span data-stu-id="2716b-107">To setup DLP policies, use the information [here](https://docs.microsoft.com/office365/securitycompliance/prevent-data-loss#set-up-dlp).</span></span>
  
 <span data-ttu-id="2716b-108">**DLP ilkeleri arayın**</span><span class="sxs-lookup"><span data-stu-id="2716b-108">**What DLP policies look for**</span></span>
  
<span data-ttu-id="2716b-109">**Yerleşik hassas bilgi türleri** Office 365 güvenlik ve uyumluluk Merkezi'nde kullanırken, DLP ilkeleri belirli desenleri ve öğeleri bu hassas türler algılama zaman arayın.</span><span class="sxs-lookup"><span data-stu-id="2716b-109">When using the **built-in sensitive information types** in Office 365 Security and Compliance center, DLP policies look for specific patterns and elements when detecting these sensitive types.</span></span>
  
- <span data-ttu-id="2716b-110">**Yerleşik hassas bilgi türleri**</span><span class="sxs-lookup"><span data-stu-id="2716b-110">**Built-in Sensitive Information Types**</span></span>

    <span data-ttu-id="2716b-111">Yerleşik hassas türler ve DLP İlkesi zaman duyarlı türünü algılama göründüğünü hakkında daha fazla bilgi için bkz: [önemli bilgi türlerini arayın](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span><span class="sxs-lookup"><span data-stu-id="2716b-111">For information on the built-in Sensitive types and what a DLP policy looks for when detecting the Sensitive type, see: [What the sensitive information types look for](https://docs.microsoft.com/office365/securitycompliance/what-the-sensitive-information-types-look-for).</span></span>

- <span data-ttu-id="2716b-112">**Özel hassas bilgi türleri**</span><span class="sxs-lookup"><span data-stu-id="2716b-112">**Custom Sensitive Information Types**</span></span>

    <span data-ttu-id="2716b-113">Özel hassas bilgi türlerini oluşturmaya çalışıyorsanız, özel bir hassas tür oluşturma hakkında bilgi için aşağıdaki makaleyi kullanın: [özel önemli bilgiler türü yaratma](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span><span class="sxs-lookup"><span data-stu-id="2716b-113">If you are trying to create custom sensitive information types, use the following article for information on how to create a custom sensitive type: [Create a custom sensitive information type](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type).</span></span>

<span data-ttu-id="2716b-114">**DLP ilkeyi sınayın**</span><span class="sxs-lookup"><span data-stu-id="2716b-114">**Test a DLP policy**</span></span>

<span data-ttu-id="2716b-115">Veri türü olan bir yerleşik veya özel önemli bilgiler test etmek için **sınıflandırmaları**altında **Test tipi** seçeneğini kullanın > **hassas bilgi türleri**.</span><span class="sxs-lookup"><span data-stu-id="2716b-115">To test your data with a built-in or custom sensitive information type, use the **Test type** option under **Classifications** > **Sensitive info types**.</span></span> <span data-ttu-id="2716b-116">Daha fazla bilgi için bkz: [Test özel hassas bilgi türleri](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span><span class="sxs-lookup"><span data-stu-id="2716b-116">For more information, see [Test custom sensitive information types](https://docs.microsoft.com/office365/securitycompliance/create-a-custom-sensitive-information-type#test-custom-sensitive-information-types-in-the-security--compliance-center).</span></span>

 <span data-ttu-id="2716b-117">**Raporlar**</span><span class="sxs-lookup"><span data-stu-id="2716b-117">**Reports**</span></span>
  
- <span data-ttu-id="2716b-118">Hassas veriler görüşleri ile elde [DLP raporları.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span><span class="sxs-lookup"><span data-stu-id="2716b-118">Get sensitive data insights with [DLP Reports.](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#dlp-reports)</span></span>

- <span data-ttu-id="2716b-119">Belirli bir [Olayı rapor](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports)olayın ayrıntılarını görmek.</span><span class="sxs-lookup"><span data-stu-id="2716b-119">See specific details of the event with an [Incident Report](https://docs.microsoft.com/office365/securitycompliance/data-loss-prevention-policies#incident-reports).</span></span>
