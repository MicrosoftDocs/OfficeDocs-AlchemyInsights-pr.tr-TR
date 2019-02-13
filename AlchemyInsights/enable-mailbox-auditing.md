---
title: Posta kutusu denetimi etkinleştirme
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/5/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: Adm_O365
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 3a7ffccadf6b415f7dd0d0871d368402332a0cd7
ms.sourcegitcommit: dd43cc0a9470f98b8ef2a3787c823801d674c666
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 02/12/2019
ms.locfileid: "29916760"
---
# <a name="enable-mailbox-auditing"></a>Posta kutusu denetimi etkinleştirme

Tek bir kullanıcı veya tüm kuruluş için posta kutusu denetimini etkinleştirmek için aşağıdaki cmdlet'leri uzak güç kabuğundan çalıştırmanız gerekir:
  
 **Tek kullanıcı**
  
Set-posta kutusu - kimlik "Jane Dow" - AuditEnabled $true
  
 **Kuruluş**
  
Get-posta kutusu - ResultSize sınırsız - filtre {RecipientTypeDetails - eq "UserMailbox"} | Set-posta kutusu - AuditEnabled $true
  
[Daha fazla bilgi edinin](https://support.office.com/article/aaca8987-5b62-458b-9882-c28476a66918)
  

