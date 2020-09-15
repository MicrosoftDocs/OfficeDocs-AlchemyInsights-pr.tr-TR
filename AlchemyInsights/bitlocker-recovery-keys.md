---
title: BitLocker kurtarma anahtarları
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "1922"
- "9000220"
ms.openlocfilehash: 7c56e68cf303939d8e7d4ee0a7301e367ecfe9f9
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47685906"
---
# <a name="accessing-bitlocker-recovery-keys"></a><span data-ttu-id="7f375-102">BitLocker Kurtarma anahtarlarına erişme</span><span class="sxs-lookup"><span data-stu-id="7f375-102">Accessing Bitlocker recovery keys</span></span>

<span data-ttu-id="7f375-103">BitLocker ayarları Intune Endpoint Protection Ilkesini yapılandırırken, BitLocker kurtarma bilgilerinin Azure Active Directory 'de depolanması gerekip gerekmediği tanımlanır.</span><span class="sxs-lookup"><span data-stu-id="7f375-103">When configuring Bitlocker settings Intune Endpoint Protection Policy, it is possible to define whether Bitlocker recovery information should be stored in Azure Active Directory.</span></span>

<span data-ttu-id="7f375-104">Bu ayar yapılandırılırsa, cihaz için depolanan kurtarma verileri Intune cihazlarındaki verilerin iki yolu nedeniyle bir Intune yöneticisine görünür olmalıdır:</span><span class="sxs-lookup"><span data-stu-id="7f375-104">If that setting is configured, the stored recovery data should be visible to an Intune admin as part of the device record data in Intune Devices blade in two ways:</span></span>

<span data-ttu-id="7f375-105">Cihazlar-Azure AD cihazları-> "aygıt" veya cihazlar-> tüm cihazlar-> "cihaz"-> kurtarma anahtarları</span><span class="sxs-lookup"><span data-stu-id="7f375-105">Devices - Azure AD devices -> "Device"  OR Devices -> All Devices -> "Device" -> Recovery keys</span></span>

<span data-ttu-id="7f375-106">Alternatif olarak, cihaza yönetimsel erişim varsa, kurtarma anahtarı (parola) yükseltilmiş bir komut isteminden aşağıdaki komut çalıştırılarak görülebilir:</span><span class="sxs-lookup"><span data-stu-id="7f375-106">Alternatively, if there is administrative access to the device itself, the recovery key (Password) can be seen by running the following command from an elevated command prompt:</span></span>

```
manage-bde -protectors c: -get
Example
Volume C: []
All Key Protectors
    TPM:
      ID: {8A5D13D6-7ED9-46C8-A74F-AC3ADF016EC8}
      PCR Validation Profile:
        0, 2, 4, 8, 9, 10, 11
    Numerical Password:
      ID: {DFA26333-XXXX-402C-YYYY-A8C40AF3ZZZZ}
      Password:
        393943-22222-281721-555554-577984-77777-194700-99999
```
<span data-ttu-id="7f375-107">Cihaz Intune 'da kaydolma öncesinde şifrelendiyse, kurtarma anahtarı, OOBE işlemi sırasında cihazda oturum açmak için kullanılan "Microsoft hesabı" (MSA) ile ilişkilendirilmiş olabilir.</span><span class="sxs-lookup"><span data-stu-id="7f375-107">If the device was encrypted prior to enrolment in Intune, the recovery key may have been associated with the "Microsoft Account" (MSA) used to sign in to the device during the OOBE process.</span></span> <span data-ttu-id="7f375-108">Öyleyse,  https://onedrive.live.com/recoverykey Bu MSA ile erişilmesi ve oturum açmak, kurtarma anahtarlarının depolandığı cihazları göstermelidir.</span><span class="sxs-lookup"><span data-stu-id="7f375-108">If that was the case, accessing  https://onedrive.live.com/recoverykey and signing in with that MSA should show the devices for which recovery keys were stored.</span></span>
 
<span data-ttu-id="7f375-109">Cihaz, etki alanı tabanlı Grup İlkesi aracılığıyla yapılandırma sonucunda şifrelenmişse, kurtarma bilgileri şirket içi Active Directory 'de depolanabilir.</span><span class="sxs-lookup"><span data-stu-id="7f375-109">If the device was encrypted as a result of configuration through domain-based group policy, the recovery information may be stored in the on-premise Active Directory.</span></span>
 

