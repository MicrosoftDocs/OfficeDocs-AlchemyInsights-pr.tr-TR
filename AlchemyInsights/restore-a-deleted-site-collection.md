---
title: Silinmiş bir siteyi geri yükleme
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: 570284765f32212b4ef2062db5b70f427b28c121
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47692063"
---
# <a name="restore-a-deleted-site"></a><span data-ttu-id="44bd2-102">Silinmiş bir siteyi geri yükleme</span><span class="sxs-lookup"><span data-stu-id="44bd2-102">Restore a deleted site</span></span>

<span data-ttu-id="44bd2-103">Yönetici bir SharePoint sitesini sildiğinde, site koleksiyonu geri dönüşüm kutusu 'na yerleştirilir ve bu, kalıcı olarak silinmeden önce 93 gün boyunca tutulur.</span><span class="sxs-lookup"><span data-stu-id="44bd2-103">When an admin deletes a SharePoint site, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted.</span></span> <span data-ttu-id="44bd2-104">Siteyi geri yüklemek için:</span><span class="sxs-lookup"><span data-stu-id="44bd2-104">To restore the site:</span></span>
  
1. <span data-ttu-id="44bd2-105">Yeni SharePoint Yönetim merkezinde Şeritteki **geri dönüşüm** kutusu 'nu tıklatın.</span><span class="sxs-lookup"><span data-stu-id="44bd2-105">In the new SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="44bd2-106">Geri yüklemek istediğiniz site koleksiyonunun yanındaki kutuyu işaretleyin.</span><span class="sxs-lookup"><span data-stu-id="44bd2-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="44bd2-107">**Silinmiş öğeleri geri yükle**'yi tıklatın.</span><span class="sxs-lookup"><span data-stu-id="44bd2-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="44bd2-108">Silinmiş bir iletişim sitesini geri yüklemek için yeni SharePoint Yönetim merkezini kullanabilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="44bd2-108">To restore a deleted communication site, you can use the new SharePoint admin center.</span></span> <span data-ttu-id="44bd2-109">Aksi takdirde Microsoft PowerShell 'i kullanmanız gerekir.</span><span class="sxs-lookup"><span data-stu-id="44bd2-109">Otherwise, you need to use Microsoft PowerShell.</span></span> <span data-ttu-id="44bd2-110">Microsoft 365 grubuna ait bir siteyi geri yüklemek için, Exchange Yönetim merkezinde grubu geri yüklemeniz gerekir.</span><span class="sxs-lookup"><span data-stu-id="44bd2-110">To restore a site that belongs to a Microsoft 365 group, you need to restore the group in the Exchange admin center.</span></span> <span data-ttu-id="44bd2-111">Gruplar silindikten sonra 30 gün geri yüklenebilir.</span><span class="sxs-lookup"><span data-stu-id="44bd2-111">Groups can be restored for 30 days after they're deleted.</span></span>
  

