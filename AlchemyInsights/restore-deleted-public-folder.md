---
title: Silinen ortak klasörü geri yükleme
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3500007"
- "3488"
ms.openlocfilehash: cd85dd3c0eb14f6e02ac4f912e733468403387aa
ms.sourcegitcommit: 2a9d059262c07c33f9a740b3da4e6e3366b2f925
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 02/20/2020
ms.locfileid: "42158547"
---
# <a name="restore-a-deleted-public-folder"></a>Silinen ortak klasörü geri yükleme

**Ortak klasörden silinen öğeleri geri yüklemek için:**

- Bkz. [Outlook 2016'da silinen öğeleri posta olmayan bir ortak klasörden kurtaramazsınız.](https://aka.ms/pfrec)
 
**Silinen ortak klasörü (herhangi bir türde) geri yüklemek için:** 

- Lütfen aşağıdaki EXO PowerShell komutunu kullanın:

    Sözdizimi:

     `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse  | ?{$_.Name -eq "\<name_of_deleted_public_Folder"};Set-PublicFolder $pf.identity -Path \<path where the folder will be restored>`

    Örnek: Aşağıdaki komut Alt Klasör1'i geri yükleyecek ve \Parent1 altına yerleştirilecektir:

    `$pf=Get-PublicFolder \NON_IPM_SUBTREE\DUMPSTER_ROOT -Recurse | ?{$_.Name -eq "Subfolder1"};Set-PublicFolder $pf.identity -Path \Parent1`

Bkz. Daha fazla ayrıntı için [silinen ortak klasörü geri yükleyin.](https://docs.microsoft.com/exchange/collaboration-exo/public-folders/restore-deleted-public-folder)
