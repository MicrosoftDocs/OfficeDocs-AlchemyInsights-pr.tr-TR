---
title: Linux makinesi üzerinde MDATP için dışlamaları yapılandırma ve doğrulama
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
ms.openlocfilehash: 4fad0a513f7c6d2f0337019488a4055c25e1650d
ms.sourcegitcommit: 6312ee31561db36104f32282d019d069ede69174
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 03/11/2021
ms.locfileid: "50749245"
---
# <a name="configure-and-validate-exclusions-for-mdatp-on-a-linux-machine"></a><span data-ttu-id="ce581-102">Linux makinesinde MDATP için dışlamaları yapılandırma ve doğrulama</span><span class="sxs-lookup"><span data-stu-id="ce581-102">Configure and validate exclusions for MDATP on a Linux machine</span></span>

<span data-ttu-id="ce581-103">Belirli dosyaları, klasörleri, süreçleri ve süreç açılan dosyaları MDATP taramalarından çıkarabilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="ce581-103">You can exclude certain files, folders, processes, and process-opened files from MDATP scans.</span></span> <span data-ttu-id="ce581-104">Dışlamalar, benzersiz veya özel amaçlı yazılım ve dosyaların yanlış algılanmasına yardımcı olur.</span><span class="sxs-lookup"><span data-stu-id="ce581-104">Exclusions help prevent incorrect detection of software and files unique or customized to your organization.</span></span> <span data-ttu-id="ce581-105">Dışlamalar, MDATP'nin neden olduğu performans sorunlarını da azaltmak için yardımcı olur.</span><span class="sxs-lookup"><span data-stu-id="ce581-105">Exclusions also help mitigate performance problems caused by MDATP.</span></span>

<span data-ttu-id="ce581-106">Daha fazla bilgi edinmek için Bkz. [Linux için MDATP'de dışlamaları yapılandırma ve doğrulama.](https://go.microsoft.com/fwlink/?linkid=2144517)</span><span class="sxs-lookup"><span data-stu-id="ce581-106">To learn more, see [Configure and validate exclusions for MDATP for Linux](https://go.microsoft.com/fwlink/?linkid=2144517).</span></span>

> [!IMPORTANT]
> <span data-ttu-id="ce581-107">Bu makalede açıklanan dışlamalar Linux için MDATP'nin uç nokta algılama ve yanıt (EDR) dahil diğer özellikleri için geçerli değildir.</span><span class="sxs-lookup"><span data-stu-id="ce581-107">The exclusions described in this article don't apply to other capabilities of MDATP for Linux, including endpoint detection and response (EDR).</span></span> <span data-ttu-id="ce581-108">Bu makalede açıklanan yöntemleri kullanarak dışlama dosyalarınız, EDR uyarılarını ve diğer algılama özelliklerini tetikler.</span><span class="sxs-lookup"><span data-stu-id="ce581-108">Files that you exclude by using the methods described in this article can still trigger EDR alerts and other detection capabilities.</span></span>
