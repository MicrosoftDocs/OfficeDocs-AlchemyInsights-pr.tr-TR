---
title: Office Dağıtım Aracının (ODT) nasıl kullanılacağı yla ilgili sorular
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 604fc200517316de6e0194bd64e6eb3039cfa61b
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 10/18/2019
ms.locfileid: "36553560"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Office Dağıtım Aracının (ODT) nasıl kullanılacağı yla ilgili sorular

Office Dağıtım Aracını [Microsoft İndirme Merkezi'nden](http://go.microsoft.com/fwlink/p/?LinkID=626065)indirin.
  
Dosyayı indirdikten sonra, Office Dağıtım Aracı yürütülebilir (setup.exe) ve örnek yapılandırma dosyasını (configuration.xml) içeren kendi kendini ayıklayan yürütülebilir dosyayı çalıştırın.
  
 **Office 365 ProPlus ürünlerini istemci bilgisayarlardan hariç tutmak veya kaldırmak için:**
  
Office 365 ProPlus'ı yüklerken, belirli ürünleri hariç tutabilirsiniz. Bunu yapmak için Office'i ODT ile yükleme adımlarını izleyin, ancak yapılandırma dosyanıza DışUygulama öğesini ekleyin. Örneğin, bu yapılandırma dosyası Publisher dışındaki tüm Office 365 ProPlus ürünlerini yükler:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Office Dağıtım Aracına Genel Bakış](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

