---
title: Kiracı ilkesi düzeltme (eylem geçersiz kılma)
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: bc7ad8acd86c9d5b2f99ffdc6fe8a8b53e1fcb8b
ms.sourcegitcommit: 60c504f3ac187eaf1141b3ba701d9e0633bdd968
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 03/08/2021
ms.locfileid: "50695690"
---
# <a name="fix-tenant-policy-action-override"></a><span data-ttu-id="a65dd-102">Kiracı ilkesi düzeltme (eylem geçersiz kılma)</span><span class="sxs-lookup"><span data-stu-id="a65dd-102">Fix Tenant policy (action override)</span></span>

<span data-ttu-id="a65dd-103">Kiracınıza gelen istenmeyen posta önleme ilkesi bu iletiyi etkiledi.</span><span class="sxs-lookup"><span data-stu-id="a65dd-103">An anti-spam policy in your tenant affected this message.</span></span> <span data-ttu-id="a65dd-104">İlkeyi gözden geçirmek için şunları yapın:</span><span class="sxs-lookup"><span data-stu-id="a65dd-104">To review the policy, do the following:</span></span>

1. <span data-ttu-id="a65dd-105">[Office 365 Güvenlik ve Uyumluluk &'ne](https://go.microsoft.com/fwlink/p/?linkid=2077143)gidin ve ardından Tehdit yönetimi İlkesi İstenmeyen Postayla   >    >  [Mücadele'ye gidin.](https://go.microsoft.com/fwlink/?linkid=2101518)</span><span class="sxs-lookup"><span data-stu-id="a65dd-105">Go to the [Office 365 Security & Compliance Center](https://go.microsoft.com/fwlink/p/?linkid=2077143), and then go to **Threat management** > **Policy** > [Anti-spam](https://go.microsoft.com/fwlink/?linkid=2101518).</span></span>
2. <span data-ttu-id="a65dd-106">İlke kaynağının **şunları gösterir** olup olmadığını kontrol edin:  **Add-Xheader/ModifySubject/Redirect/Delete/No action/ BCC iletisi**</span><span class="sxs-lookup"><span data-stu-id="a65dd-106">Check to see if **Policy source** indicates the following:  **Add-Xheader/ModifySubject/Redirect/Delete/No action/ BCC message**</span></span>

    <span data-ttu-id="a65dd-107">Öyleyse, Özel **sekmesinde** iletiyi etkilenen ilkenin ayarlarını kontrol edin.</span><span class="sxs-lookup"><span data-stu-id="a65dd-107">If so, on the **Custom** tab, check the settings of the policy that affected the message.</span></span> <span data-ttu-id="a65dd-108">Tüm Exchange Online Protection **müşterilerine uygulanan** Standart ayarlar iletiyi etkilemektedir.</span><span class="sxs-lookup"><span data-stu-id="a65dd-108">It's possible that the **Standard settings** applied to all Exchange Online Protection customers affected the message.</span></span>

<span data-ttu-id="a65dd-109">İstenmeyen posta filtresi ilkelerini yapılandırma hakkında daha fazla bilgi için bkz. [İstenmeyen posta filtresi ilkelerinizi yapılandırma.](https://go.microsoft.com/fwlink/?linkid=2101431)</span><span class="sxs-lookup"><span data-stu-id="a65dd-109">For more information on configuring spam filter policies, see [Configure your spam filter policies](https://go.microsoft.com/fwlink/?linkid=2101431).</span></span>
