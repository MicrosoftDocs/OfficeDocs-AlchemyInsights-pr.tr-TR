---
title: 618 Takvim Paylaşım Politikası
ms.author: chrisda
author: chrisda
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "618"
- "899"
- "3800014"
ms.assetid: bc3db17b-87f8-4e50-b3ee-8b105b70d67a
ms.openlocfilehash: cc5827975eff10a119281541622224d0e37f08a7
ms.sourcegitcommit: 2afad0b107d03cd8c4de0b85b5bee38a13a7960d
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 05/26/2020
ms.locfileid: "44373019"
---
# <a name="policy-error-when-sharing-a-calendar"></a><span data-ttu-id="f9b90-102">Takvim paylaşırken ilke hatası</span><span class="sxs-lookup"><span data-stu-id="f9b90-102">Policy error when sharing a calendar</span></span>

1. <span data-ttu-id="f9b90-103">Durumunuza uygun olarak aşağıdakilerden birini yapın:</span><span class="sxs-lookup"><span data-stu-id="f9b90-103">Do one of the following, as appropriate for your situation:</span></span>
    - <span data-ttu-id="f9b90-104">Remote PowerShell'i kullanarak Exchange Online'a bağlanın.</span><span class="sxs-lookup"><span data-stu-id="f9b90-104">Connect to Exchange Online by using Remote PowerShell.</span></span> <span data-ttu-id="f9b90-105">Daha fazla bilgi için Remote [PowerShell kullanarak Exchange Online'a Bağlan'a](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx)bakın.</span><span class="sxs-lookup"><span data-stu-id="f9b90-105">For more information, see [Connect to Exchange Online using Remote PowerShell](https://technet.microsoft.com/library/jj984289%28v=exchg.160%29.aspx).</span></span>
    - <span data-ttu-id="f9b90-106">Şirket içi sunucuda Exchange Management Shell'i açın.</span><span class="sxs-lookup"><span data-stu-id="f9b90-106">On the on-premises server, open the Exchange Management Shell.</span></span>
2. <span data-ttu-id="f9b90-107">Kullanıcıya atanan paylaşım ilkesini belirleyin.</span><span class="sxs-lookup"><span data-stu-id="f9b90-107">Determine the sharing policy that's assigned to the user.</span></span> <span data-ttu-id="f9b90-108">Bunu yapmak için aşağıdaki komutu çalıştırın ve döndürülen ilkeyi not edin:</span><span class="sxs-lookup"><span data-stu-id="f9b90-108">To do this, run the following command and note the policy returned:</span></span>

    `
    Get-Mailbox User1 | fl *sharing*
    `

3. <span data-ttu-id="f9b90-109">Kullanıcı için paylaşım ilkesini güncelleştirin.</span><span class="sxs-lookup"><span data-stu-id="f9b90-109">Update the sharing policy for the user.</span></span> <span data-ttu-id="f9b90-110">Bunu yapmak için aşağıdaki adımları izleyin:</span><span class="sxs-lookup"><span data-stu-id="f9b90-110">To do this, follow these steps:</span></span>
    - <span data-ttu-id="f9b90-111">Exchange yönetici merkezini açın.</span><span class="sxs-lookup"><span data-stu-id="f9b90-111">Open the Exchange admin center.</span></span>
    - <span data-ttu-id="f9b90-112">**Kuruluş'u**tıklatın ve ardından **Bireysel Paylaşım**altında kullanıcıya atanan ilkeyi çift tıklatın.</span><span class="sxs-lookup"><span data-stu-id="f9b90-112">Click **Organization**, and then double-click the policy that's assigned to the user under **Individual Sharing**.</span></span> <span data-ttu-id="f9b90-113">Bu, adım 2'de döndürülen ilkedir.</span><span class="sxs-lookup"><span data-stu-id="f9b90-113">This is the policy that was returned in step 2.</span></span>
    - <span data-ttu-id="f9b90-114">Paylaşım Kuralı sayfasında, hangi **bilgileri paylaşmak istediğinizi belirt' in**altında izin vermek istediğiniz takvim paylaşım düzeyini seçin; **kaydet'i**tıklatın.</span><span class="sxs-lookup"><span data-stu-id="f9b90-114">On the Sharing Rule page, select the calendar sharing level that you want to allow under **Specify what information you want to share**; click **Save**.</span></span>

<span data-ttu-id="f9b90-115">Daha fazla bilgi için bkz: ["İlke, kullanıcı takvimi paylaşmaya çalıştığında bu düzeyde bir veya daha fazla alıcıya izin verilmesine izin vermez.](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue)</span><span class="sxs-lookup"><span data-stu-id="f9b90-115">For more information see: ["Policy does not allow granting permissions at this level to one or more of the recipient(s)" error when user tries to share calendar](https://docs.microsoft.com/exchange/troubleshoot/calendar-sharing/policy-permissions-issue).</span></span>
