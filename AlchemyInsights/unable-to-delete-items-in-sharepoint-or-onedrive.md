---
title: SharePoint veya OneDrive'daki öğeleri sileme
ms.author: pebaum
author: Techwriter40
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1851"
- "2377"
- "9000255"
ms.assetid: ''
ms.openlocfilehash: 3cc168846999c6880b95edfaedb2df8cf6e843a6
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 10/18/2019
ms.locfileid: "36748596"
---
# <a name="unable-to-delete-items"></a><span data-ttu-id="52bfe-102">Öğeleri sileme</span><span class="sxs-lookup"><span data-stu-id="52bfe-102">Unable to delete items</span></span>

<span data-ttu-id="52bfe-103">SharePoint öğelerini silme sorunları mı yaşıyormusunuz?</span><span class="sxs-lookup"><span data-stu-id="52bfe-103">Having issues deleting SharePoint items?</span></span>

- <span data-ttu-id="52bfe-104">Öğeyi silmek için her zaman [uygun izinlere](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) sahip olduğundan emin olun veya site [koleksiyonu yöneticisinin](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) öğeyi kaldırmagirişiminde bulunmasını istediğinizden emin olun.</span><span class="sxs-lookup"><span data-stu-id="52bfe-104">Always make sure you have the [appropriate permissions](https://docs.microsoft.com/sharepoint/default-sharepoint-groups) to delete the item or have a [site collection administrator](https://docs.microsoft.com/sharepoint/customize-sharepoint-site-permissions#add-change-or-remove-a-site-collection-administrator) attempt remove the item.</span></span>

- <span data-ttu-id="52bfe-105">Öğeüzerinde [bekletme ilkesi](https://docs.microsoft.com/office365/securitycompliance/retention-policies) kurulumu olmadığından emin olun.</span><span class="sxs-lookup"><span data-stu-id="52bfe-105">Ensure that there is not a [retention policy](https://docs.microsoft.com/office365/securitycompliance/retention-policies) setup on the item.</span></span>

- <span data-ttu-id="52bfe-106">Öğenin başka bir kullanıcıya [kullanıma alınmadığından](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) emin olun.</span><span class="sxs-lookup"><span data-stu-id="52bfe-106">Ensure the item is not [checked out](https://support.office.com/article/check-out-check-in-or-discard-changes-to-files-in-a-library-7e2c12a9-a874-4393-9511-1378a700f6de) to another user.</span></span>

- <span data-ttu-id="52bfe-107">Son olarak, yöneticiler, inatçı öğeleri zorla silme gibi karmaşık yönetim eylemleri gerçekleştirmenize olanak tanıyan PowerShell komutlarının kitaplığını içeren [SharePoint Desenleri ve Uygulamaları](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) 'nı (PnP) kullanabilir.</span><span class="sxs-lookup"><span data-stu-id="52bfe-107">Finally, administrators can use [SharePoint Patterns and Practices](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps#installation) (PnP) which contains a library of PowerShell commands that allow you to perform complex management actions such as force deleting stubborn items.</span></span>
- [<span data-ttu-id="52bfe-108">PNP dosyayı kaldırma</span><span class="sxs-lookup"><span data-stu-id="52bfe-108">Remove PNP File</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfile?view=sharepoint-ps)
- [<span data-ttu-id="52bfe-109">PNP Klasörünü Kaldırma</span><span class="sxs-lookup"><span data-stu-id="52bfe-109">Remove PNP Folder</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfolder?view=sharepoint-ps)
- [<span data-ttu-id="52bfe-110">PNP Liste Öğeyi Kaldırma</span><span class="sxs-lookup"><span data-stu-id="52bfe-110">Remove PNP List Item</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplistitem?view=sharepoint-ps)
- [<span data-ttu-id="52bfe-111">PNP Listesini Kaldır</span><span class="sxs-lookup"><span data-stu-id="52bfe-111">Remove PNP List</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnplist?view=sharepoint-ps)
- [<span data-ttu-id="52bfe-112">PNP Alanını Kaldırma (Sütun)</span><span class="sxs-lookup"><span data-stu-id="52bfe-112">Remove PNP Field (Column)</span></span>](https://docs.microsoft.com/powershell/module/sharepoint-pnp/remove-pnpfield?view=sharepoint-ps)