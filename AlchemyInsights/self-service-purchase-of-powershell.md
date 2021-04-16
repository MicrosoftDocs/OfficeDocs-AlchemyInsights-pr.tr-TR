---
title: PowerShell'in self servis satın alımları
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9001212"
- "3516"
ms.openlocfilehash: 48b5b0a1be1bc03d45a531a1093f18a3f750c37d
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/15/2021
ms.locfileid: "51797741"
---
# <a name="self-service-purchase-of-powershell"></a><span data-ttu-id="8b57f-102">PowerShell'in self servis satın alımları</span><span class="sxs-lookup"><span data-stu-id="8b57f-102">Self-service purchase of PowerShell</span></span>

<span data-ttu-id="8b57f-103">MSCommerce PowerShell modülünü kullanmak için, modülü TLS 1.2 (yerel yönetici izinleri gereklidir) olan bir Windows 10 cihazına yüklemeniz gerekir.</span><span class="sxs-lookup"><span data-stu-id="8b57f-103">To use the MSCommerce PowerShell module, you need to install it on a Windows 10 device with TLS 1.2 (local administrator permissions required).</span></span>  <span data-ttu-id="8b57f-104">MSCommerce modülüne içeri aktarın ve bağlanın.</span><span class="sxs-lookup"><span data-stu-id="8b57f-104">Import and connect to the MSCommerce module.</span></span>  <span data-ttu-id="8b57f-105">Oturum açmanız istendiğinde, Genel veya Fatura Yöneticisi rolü kimlik bilgilerini kullansanız gerekir.</span><span class="sxs-lookup"><span data-stu-id="8b57f-105">When prompted to log in, you will need to use Global or Billing Admin role credentials.</span></span>  

<span data-ttu-id="8b57f-106">TLS 1.2'niz yoksa, ilkeyi almaya veya güncelleştirmeye çalışırken aşağıdaki hatayı alabilirsiniz:</span><span class="sxs-lookup"><span data-stu-id="8b57f-106">If you don't have TLS 1.2, you may receive the following error when attempting to get or update the policy:</span></span>

<span data-ttu-id="8b57f-107">*ErrorMessage -Temel bağlantı kapatıldı: Gönderme sırasında beklenmeyen bir hata oluştu.*</span><span class="sxs-lookup"><span data-stu-id="8b57f-107">*ErrorMessage -The underlying connection was closed: An unexpected error occurred on a send*.</span></span>



