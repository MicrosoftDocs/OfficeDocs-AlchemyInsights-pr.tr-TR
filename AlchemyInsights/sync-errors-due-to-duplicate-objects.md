---
title: 902 (Eşitleme hataları nedeniyle yinelenen nesneleri)
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 5/30/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 902
ms.assetid: 9d9277a5-c825-4512-8d54-7138b2ee0c40
ms.openlocfilehash: eac74a6d4de58c9cdbdc8e8df8f705293bb12e87
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 03/22/2019
ms.locfileid: "30781281"
---
# <a name="sync-errors-due-to-duplicate-objects"></a><span data-ttu-id="816e6-102">Eşitleme hataları nedeniyle nesneleri çoğaltma</span><span class="sxs-lookup"><span data-stu-id="816e6-102">Sync errors due to duplicate objects</span></span>

<span data-ttu-id="816e6-103">Dizin eşitleme tamamlandığında, aşağıdaki hata iletilerinden birini alabilirsiniz:</span><span class="sxs-lookup"><span data-stu-id="816e6-103">You might receive one of the following error messages when directory synchronization finishes:</span></span>
  
- <span data-ttu-id="816e6-104">Bu Microsoft Çevrimiçi Hizmetler nesnesinde zaten yerel dizin başka bir nesneyle ilişkilendirilmiş olan değerlerini Bu nesneyle ilişkili aşağıdaki özniteliklere sahip olduğundan güncelleştirilemedi.</span><span class="sxs-lookup"><span data-stu-id="816e6-104">Unable to update this object in Microsoft Online Services because the following attributes associated with this object have values that may already be associated with another object in your local directory.</span></span>
    
- <span data-ttu-id="816e6-105">Microsoft Çevrimiçi Hizmetler dizininizde proxy adresi ile eşitlenmiş bir nesne zaten var.</span><span class="sxs-lookup"><span data-stu-id="816e6-105">A synchronized object with the same proxy address already exists in your Microsoft Online Services directory.</span></span>
    
- <span data-ttu-id="816e6-106">Bu nesne zaten, yerel dizin hizmetlerinde başka bir nesne ile ilişkili olabilir değerleri Bu nesneyle ilişkili aşağıdaki özniteliklere sahip olduğundan güncelleştirilemedi: UserPrincipalName.</span><span class="sxs-lookup"><span data-stu-id="816e6-106">Unable to update this object because the following attributes associated with this object have values that may already be associated with another object in your local directory services: UserPrincipalName.</span></span>
    
<span data-ttu-id="816e6-107">Sorunu tanımlamak ve gidermek için karşıdan yükleme ve [IdFix DirSync hata düzeltme aracı](https://www.microsoft.com/download/details.aspx?id=36832)' nı çalıştırın.</span><span class="sxs-lookup"><span data-stu-id="816e6-107">To identify and fix the issue, download and run the [IdFix DirSync Error Remediation Tool](https://www.microsoft.com/download/details.aspx?id=36832).</span></span>
  
<span data-ttu-id="816e6-108">Daha fazla bilgi için bkz: [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span><span class="sxs-lookup"><span data-stu-id="816e6-108">For more information, see [KB2647098](https://support.microsoft.com/help/2647098/duplicate-or-invalid-attributes-prevent-directory-synchronization-in-o).</span></span>
  
