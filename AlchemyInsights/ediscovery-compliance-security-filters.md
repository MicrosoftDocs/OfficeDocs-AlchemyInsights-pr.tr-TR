---
title: Içerik arama/dışarı aktarma sırasında hiçbir sonuç döndürülmedi
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3200003"
- "7463"
ms.openlocfilehash: 8786f11f170edb151879235e19caa38b50f3f06e
ms.sourcegitcommit: 3d662e1a1440ba74b5347896347d03bb8c8f3af5
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 12/22/2020
ms.locfileid: "49727243"
---
# <a name="no-results-returned-during-content-searchexport"></a><span data-ttu-id="f4804-102">Içerik arama/dışarı aktarma sırasında hiçbir sonuç döndürülmedi</span><span class="sxs-lookup"><span data-stu-id="f4804-102">No results returned during Content Search/Export</span></span>

<span data-ttu-id="f4804-103">Aşağıdaki eBulma senaryolarında sorun yaşıyorsanız:</span><span class="sxs-lookup"><span data-stu-id="f4804-103">If you are experiencing issues with the following eDiscovery scenarios:</span></span>

- <span data-ttu-id="f4804-104">İçerik arama/verme işlevi veri veya beklenmeyen veriler döndürmüyor</span><span class="sxs-lookup"><span data-stu-id="f4804-104">Content Search/Export returns no data or unexpected data</span></span>
- <span data-ttu-id="f4804-105">eBulma arama veya dışarı aktarma başarısız</span><span class="sxs-lookup"><span data-stu-id="f4804-105">eDiscovery Search or Export fails</span></span>

<span data-ttu-id="f4804-106">Bu, belirli bir yönetici tarafından ayarlanan ve tüm yöneticilere iletilmedi olan bazı uyumluluk güvenlik filtreleri olabilir.</span><span class="sxs-lookup"><span data-stu-id="f4804-106">This may be due to certain Compliance Security Filters that were setup by a specific Admin and not been communicated to all Admins.</span></span>

<span data-ttu-id="f4804-107">Bunu çözmek için, bu sorunlara neden olabilecek uyumluluk güvenlik filtreleri olup olmadığını denetleyin:</span><span class="sxs-lookup"><span data-stu-id="f4804-107">To resolve this, check if there are any Compliance Security Filters that may be causing these issues:</span></span>

1. <span data-ttu-id="f4804-108">Güvenlik ve Uyumluluk Merkezi PowerShell 'e bağlanma</span><span class="sxs-lookup"><span data-stu-id="f4804-108">Connect to Security and Compliance Center Powershell</span></span>
2. <span data-ttu-id="f4804-109">Aşağıdaki komutu çalıştırarak:</span><span class="sxs-lookup"><span data-stu-id="f4804-109">Run the following commandlets:</span></span>

    `$org = “yourdomain.com”`

    `Get-ComplianceSecurityFilter -Organization $org`

<span data-ttu-id="f4804-110">Uyumluluk güvenliği filtreleri hakkında ek bilgi için bkz: [Içerik araması Için Izinler filtreleme](https://docs.microsoft.com/microsoft-365/compliance/permissions-filtering-for-content-search)</span><span class="sxs-lookup"><span data-stu-id="f4804-110">For additional information on Compliance Security Filters, see [Permissions Filtering for Content Search](https://docs.microsoft.com/microsoft-365/compliance/permissions-filtering-for-content-search)</span></span>