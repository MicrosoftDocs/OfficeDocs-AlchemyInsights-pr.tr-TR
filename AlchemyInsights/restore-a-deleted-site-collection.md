---
title: Silinmiş bir site koleksiyonunu geri yükleme
ms.author: kaarins
author: kaarins
manager: scotv
ms.date: 5/1/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: cf7521c3-97b4-465a-97eb-6c0a41338a30
ms.openlocfilehash: b3c72033dfcc093dd0c2837d2866c6a78d64449c
ms.sourcegitcommit: d6ea5e9458a2b8ceaab3ac4bd483e1130b9a398a
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 01/15/2019
ms.locfileid: "28317860"
---
# <a name="restore-a-deleted-site-collection"></a><span data-ttu-id="410de-102">Silinmiş bir site koleksiyonunu geri yükleme</span><span class="sxs-lookup"><span data-stu-id="410de-102">Restore a deleted site collection</span></span>

<span data-ttu-id="410de-p101">Bir yönetici Klasik site koleksiyonu silmesinden burada kalıcı olarak silinmeden önce 93 gün tutulan Dönüşüm, site koleksiyonundaki yerleştirilir. Site koleksiyonu geri yüklemek için:</span><span class="sxs-lookup"><span data-stu-id="410de-p101">When an admin deletes a classic site collection, it's placed in the site collection Recycle Bin, where it's kept for 93 days before it's permanently deleted. To restore the site collection:</span></span>
  
1. <span data-ttu-id="410de-105">Klasik SharePoint Yönetim Merkezi'nde Şerit üzerinde **Geri Dönüşüm Kutusu'nu** tıklatın.</span><span class="sxs-lookup"><span data-stu-id="410de-105">In the classic SharePoint admin center, click **Recycle Bin** on the ribbon.</span></span> 
    
2. <span data-ttu-id="410de-106">Geri yüklemek istediğiniz site koleksiyonunu yanındaki onay kutusunu seçin.</span><span class="sxs-lookup"><span data-stu-id="410de-106">Select the check box next to the site collection you want to restore.</span></span>
    
3. <span data-ttu-id="410de-107">**Silinen öğeleri geri yükle**' yi tıklatın.</span><span class="sxs-lookup"><span data-stu-id="410de-107">Click **Restore Deleted Items**.</span></span>
    
<span data-ttu-id="410de-p102">Silinen iletişim site geri yüklemek için yeni SharePoint Yönetim Merkezi önizleme özelliğini kullanabilirsiniz. Aksi takdirde, PowerShell kullanmanız gerekir. Bir Office 365 grubuna ait bir siteyi geri yüklemek için Exchange Yönetim Merkezi grubunda geri gerekir. Bunlar silinmiş sonraki 30 gün için grupları geri yüklenebilir.</span><span class="sxs-lookup"><span data-stu-id="410de-p102">To restore a deleted communication site, you can use the new SharePoint admin center preview. Otherwise, you need to use PowerShell. To restore a site that belongs to an Office 365 group, you need to restore the group in the Exchange admin center. Groups can be restored for 30 days after they're deleted.</span></span>
  

