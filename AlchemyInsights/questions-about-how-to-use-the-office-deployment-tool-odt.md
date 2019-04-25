---
title: Office Dağıtım Aracı'nın (ODT) kullanma hakkında sorular
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: e91d40f872dd401ee210ac05eb39d64b6fb88027
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/23/2019
ms.locfileid: "32371788"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Office Dağıtım Aracı'nın (ODT) kullanma hakkında sorular

Office dağıtım aracı [Microsoft Yükleme Merkezi'nden](http://go.microsoft.com/fwlink/p/?LinkID=626065)yükleyin.
  
Dosyayı karşıdan yükledikten sonra Office dağıtım aracı yürütülebilir (setup.exe) içeren kendi kendine ayıklanan yürütülebilir dosya ve örnek bir yapılandırma dosyası (configuration.xml) çalıştırın.
  
 **Dışarıda veya Office 365 ProPlus ürün istemci bilgisayarlardan kaldırmak için:**
  
Office 365 ProPlus yüklerken, belirli ürünleri dışlayabilirsiniz. Bunu yapmak için ODT ile Office yüklemek için adımları izleyin, ancak ExcludeApp öğesi yapılandırma dosyanıza ekleyin. Örneğin, Publisher dışındaki tüm Office 365 ProPlus ürünleri bu yapılandırma dosyası yükler:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Office dağıtım aracı genel bakış](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

