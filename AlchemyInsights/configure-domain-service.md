---
title: Etki alanı hizmetini yapılandırma
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 01/15/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "7931"
- "9004400"
ms.openlocfilehash: 51e0bd78240627876721cbce654188afac1ee365
ms.sourcegitcommit: a61a29dbd0382370fea0be5fa4a61c9a1a9354c7
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 01/18/2021
ms.locfileid: "49885684"
---
# <a name="unable-to-enable-aad-ds-or-deployment-is-failing"></a><span data-ttu-id="338ea-102">AAD etkinleştirilemiyor-DS veya dağıtım başarısız oluyor</span><span class="sxs-lookup"><span data-stu-id="338ea-102">Unable to enable AAD-DS or deployment is failing</span></span>

<span data-ttu-id="338ea-103">Azure AD etki alanı hizmeti 'nin (AAD-DS) etkinleştirilmemiş veya dağıtılmadığı sorunu çözmek için aşağıdaki adımları uygulayın:</span><span class="sxs-lookup"><span data-stu-id="338ea-103">To solve the issue of Azure AD domain service (AAD-DS) not being enabled or failing to be deployed, perform the following steps:</span></span>

1. <span data-ttu-id="338ea-104">Var olan bir sanal ağı kullanıyorsanız, portalda AAD-DS 'de eşitleme yapmak için gereken bağlantı noktalarını engelleyen kurallar için NSG 'inizi denetleyin https://aka.ms/aadds-networking .</span><span class="sxs-lookup"><span data-stu-id="338ea-104">If you are using an already existing virtual network, check your NSG for rules that block ports needed to synchronize in AAD-DS in the portal https://aka.ms/aadds-networking.</span></span>
2. <span data-ttu-id="338ea-105">Bu sorun giderme kılavuzunda, hata iletinizin yanıtlanmadığını denetleyin  https://aka.ms/aadds-troubleshoot-enable .</span><span class="sxs-lookup"><span data-stu-id="338ea-105">Check to see if your error message is answered in this troubleshooting guide that is available in  https://aka.ms/aadds-troubleshoot-enable.</span></span>
3. <span data-ttu-id="338ea-106">Azure AD etki alanı Hizmetleri 'ni yeni bir sanal ağda dağıtmayı deneyin.</span><span class="sxs-lookup"><span data-stu-id="338ea-106">Try deploying Azure AD Domain Services in a new virtual network.</span></span>
4. <span data-ttu-id="338ea-107">AAD 'yi dağıtma-DS: [AAD etki alanı Hizmetleri oluşturma ve yapılandırma](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-create-instance)</span><span class="sxs-lookup"><span data-stu-id="338ea-107">Follow the Getting Started guide on how to deploy AAD-DS: [Create and Configure AAD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/tutorial-create-instance).</span></span>
5. <span data-ttu-id="338ea-108">Azure AD etki alanı Hizmetleri 'ni dağıtma konusunda sorun yaşıyorsanız, bir kez daha çalışmanızı öğrenmenize yardımcı olacak genel hataları çözmek için [Azure AD etki alanı Hizmetleri sorunlarını giderme](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot) konusuna bakın.</span><span class="sxs-lookup"><span data-stu-id="338ea-108">If you are having issues with Deploying Azure AD Domain Services, see [Troubleshoot Azure AD Domain Services](https://docs.microsoft.com/azure/active-directory-domain-services/troubleshoot) to resolve common errors to help you get things working again.</span></span> 

<span data-ttu-id="338ea-109">**AAD devre dışı bırakılamıyor-DS**</span><span class="sxs-lookup"><span data-stu-id="338ea-109">**Unable to disable AAD-DS**</span></span>

<span data-ttu-id="338ea-110">AAD-DS duraklatılamıyor.</span><span class="sxs-lookup"><span data-stu-id="338ea-110">AAD-DS is unable to be paused.</span></span> <span data-ttu-id="338ea-111">Yönetilen etki alanınızı kullanmayı durdurmak istiyorsanız, silinmesi gerekir.</span><span class="sxs-lookup"><span data-stu-id="338ea-111">If you wish to stop using your managed domain, it must be deleted.</span></span>
<span data-ttu-id="338ea-112">Yönetilen etki alanınızı silmek için, [AAD etki alanı hizmetini silme](https://docs.microsoft.com/azure/active-directory-domain-services/delete-aadds)konusuna bakın.</span><span class="sxs-lookup"><span data-stu-id="338ea-112">To delete your Managed domain, see [Delete AAD Domain Service](https://docs.microsoft.com/azure/active-directory-domain-services/delete-aadds).</span></span>



