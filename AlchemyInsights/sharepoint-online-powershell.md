---
title: Sharepoint Online PowerShell
ms.author: v-todmc
author: todmccoy
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: 8c270748fc75f929371fbb2856daad3ae61a1540
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764283"
---
# <a name="sharepoint-online-powershell"></a><span data-ttu-id="a5e92-102">Sharepoint Online PowerShell</span><span class="sxs-lookup"><span data-stu-id="a5e92-102">Sharepoint Online PowerShell</span></span>

<span data-ttu-id="a5e92-103">Sharepoint Online içinde PowerShell veya Scripts ile mi çalışıyormusunuz?</span><span class="sxs-lookup"><span data-stu-id="a5e92-103">Working with PowerShell or Scripts within Sharepoint Online?</span></span> <span data-ttu-id="a5e92-104">Daha fazla bilgi için aşağıdaki bağlantıları ziyaret edin.</span><span class="sxs-lookup"><span data-stu-id="a5e92-104">Visit the links below for more information.</span></span>
- [<span data-ttu-id="a5e92-105">SharePoint Online Management Shell ile başlarken</span><span class="sxs-lookup"><span data-stu-id="a5e92-105">Getting started with SharePoint Online Management Shell</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [<span data-ttu-id="a5e92-106">Çok faktörlü kimlik doğrulama (MFA) ile SPO PowerShell'e bağlanın</span><span class="sxs-lookup"><span data-stu-id="a5e92-106">Connect to SPO PowerShell with multifactor authentication (MFA)</span></span>](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- <span data-ttu-id="a5e92-107">[SharePoint Desenleri ve Uygulamaları (PnP),](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) SPO'ya yönelik karmaşık yönetim eylemleri gerçekleştirmenize olanak tanıyan powershell komutları kitaplığı içerir.</span><span class="sxs-lookup"><span data-stu-id="a5e92-107">[SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contains a library of PowerShell commands that allows you to perform complex management actions towards SPO.</span></span>

> [!NOTE]
> - <span data-ttu-id="a5e92-108">SPO yönetim kabuğuyla bağlantı kurmada sorun yaşıyorsanız, en son sürüme güncelleştirdiğinizden emin olun ve *modülü "Microsoft.Online.SharePoint.PowerShell İçe Aktar"* kullanarak [yeniden içe aktarmayı](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) deneyin.</span><span class="sxs-lookup"><span data-stu-id="a5e92-108">If you are having issues connecting with the SPO management shell, make sure that you have updated to the latest version and try to [re-import the module](https://docs.microsoft.com/powershell/developer/module/importing-a-powershell-module) using *“Import-Module Microsoft.Online.SharePoint.PowerShell”.*</span></span>
> - <span data-ttu-id="a5e92-109">İstemci tarafı nesne modeli komut dosyalarını çalıştırmaya çalışıyorsanız, Yerel makinenizde [Sharepoint Online İstemci Bileşenleri SDK](https://www.microsoft.com/download/details.aspx?id=42038) yüklü olması gerekir.</span><span class="sxs-lookup"><span data-stu-id="a5e92-109">If you are attempting to run client-side object model scripts, you will need to have the [Sharepoint Online Client Components SDK](https://www.microsoft.com/download/details.aspx?id=42038) installed on your local machine.</span></span>
> - <span data-ttu-id="a5e92-110">PowerShell'den komut dosyaları çalıştırırken sorun yaşıyorsanız, PowerShell'i Yönetici olarak çalıştırmayı ve [Yürütme İlkesi'ni](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6)değiştirmeyi düşünebilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="a5e92-110">If you are having issues running scripts from PowerShell, you may want to consider running PowerShell as an Administrator and changing the [Execution Policy](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).</span></span>