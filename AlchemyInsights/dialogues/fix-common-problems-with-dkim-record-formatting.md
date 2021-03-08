---
title: DKIM kaydı biçimlendirmesi ile ilgili sık karşılaşılan sorunları düzeltme
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 02/23/2021
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9002531"
- "7375"
ms.openlocfilehash: 0a59ca1c93121cb4681c0d44b85a9b756c07895b
ms.sourcegitcommit: 78fe9f33438cb0c19f0dab31253b5853b73f4f47
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 03/05/2021
ms.locfileid: "50527333"
---
# <a name="fix-common-problems-with-dkim-record-formatting"></a><span data-ttu-id="da9fe-102">DKIM kaydı biçimlendirmesi ile ilgili sık karşılaşılan sorunları düzeltme</span><span class="sxs-lookup"><span data-stu-id="da9fe-102">Fix common problems with DKIM record formatting</span></span>

<span data-ttu-id="da9fe-103">DKIM ayarlama sorunlarının çoğu hatalı DNS kayıtlarıyla ilgilidir.</span><span class="sxs-lookup"><span data-stu-id="da9fe-103">Most DKIM set-up issues are related to incorrect DNS records.</span></span>

<span data-ttu-id="da9fe-104">DKIM ayarlama sorunlarını düzeltmek için DKIM CNAME kaydının **(TXT** kaydı değil) doğru biçimlendirilmiş olduğunu doğrulayın.</span><span class="sxs-lookup"><span data-stu-id="da9fe-104">To fix the DKIM set-up issues, verify that the DKIM CNAME record (**not** a TXT record) is formatted correctly.</span></span> <span data-ttu-id="da9fe-105">Daha fazla bilgi için [Bkz. Office 365'te DKIM'i](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email)el ile ayarlamak için ne yapmak gerekir?</span><span class="sxs-lookup"><span data-stu-id="da9fe-105">For more information, see [What you need to do to manually set up DKIM in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/use-dkim-to-validate-outbound-email).</span></span>

<span data-ttu-id="da9fe-106">Genel olarak DNS kayıtlarıyla ilgili yardıma ihtiyacınız varsa, [Office 365 için](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider)herhangi bir DNS barındırma sağlayıcısında DNS kayıtları oluşturma bkz.</span><span class="sxs-lookup"><span data-stu-id="da9fe-106">If you need help with DNS records in general, see [Create DNS records at any DNS hosting provider for Office 365](https://docs.microsoft.com/microsoft-365/admin/get-help-with-domains/create-dns-records-at-any-dns-hosting-provider).</span></span>

> [!NOTE]
> <span data-ttu-id="da9fe-107">Etki alanınız için DNS barındırma hizmette DKIM DNS kayıtlarınızı oluşturduktan veya güncelleştirdikten sonra, DNS kayıtlarının yayılmasını beklemeniz gerekir.</span><span class="sxs-lookup"><span data-stu-id="da9fe-107">After you create or update your DKIM DNS records at the DNS hosting service for your domain, you'll need to wait for the DNS records to propagate.</span></span>
