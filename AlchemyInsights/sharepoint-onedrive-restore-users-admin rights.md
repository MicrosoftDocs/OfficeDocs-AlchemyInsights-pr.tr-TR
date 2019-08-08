---
title: İletiler için OneDrive iş siteleri için reddedildi erişim sorunlarını giderme
ms.author: efrene
author: efrene
manager: pamgreen
ms.date: 11/14/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.assetid: cebb7a4a-33e1-474e-a5d0-dbd02a80b1e9
ms.openlocfilehash: d47ce80bdd07a25d9724057edf0289808a00a3db
ms.sourcegitcommit: 8a83b508785c96c19648ed574f442bbef2c2dff9
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 08/07/2019
ms.locfileid: "36232565"
---
# <a name="troubleshooting-access-denied-messages-to-onedrive-for-business-sites"></a><span data-ttu-id="72435-102">İletiler için OneDrive iş siteleri için reddedildi erişim sorunlarını giderme</span><span class="sxs-lookup"><span data-stu-id="72435-102">Troubleshooting Access denied messages to OneDrive for Business sites</span></span>

<span data-ttu-id="72435-103">Bu sorun, kullanıcı olduğunda ve aynı kullanıcı asıl adı ile (UPN) yeniden oluşturulması en sık oluşur.</span><span class="sxs-lookup"><span data-stu-id="72435-103">This issue most frequently occurs when a user is deleted and re-created with the same user principal name (UPN).</span></span> <span data-ttu-id="72435-104">Yeni hesabı farklı bir PUID (Passport benzersiz kimliği) değeri kullanılarak oluşturulur.</span><span class="sxs-lookup"><span data-stu-id="72435-104">The new account is created by using a different PUID (Passport Unique ID) value.</span></span> <span data-ttu-id="72435-105">Kullanıcı bir site koleksiyonu veya kendi OneDrive erişmeye çalıştığında, kullanıcı yanlış bir PUID sahiptir.</span><span class="sxs-lookup"><span data-stu-id="72435-105">When the user tries to access a site collection or their OneDrive, the user has an incorrect PUID.</span></span> <span data-ttu-id="72435-106">İkinci senaryo directory eşitlemesi, Active Directory kuruluş birimi (OU) ile ilgilidir.</span><span class="sxs-lookup"><span data-stu-id="72435-106">A second scenario involves directory synchronization with an Active Directory organizational unit (OU).</span></span> <span data-ttu-id="72435-107">Bunlar, kullanıcıların zaten SharePoint için oturumu ve ardından farklı bir kuruluş birimine taşınan ve SharePoint ile resynced, bu sorunla karşılaşabilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="72435-107">If users have already signed in to SharePoint, and then are moved to a different OU and resynced with SharePoint, they may experience this problem.</span></span>

1. <span data-ttu-id="72435-108">Bu sorunu gidermek için makaledeki adımları,[bir kullanıcının Office 365'te geri](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide)ile özgün UPN kurtarmalısınız.</span><span class="sxs-lookup"><span data-stu-id="72435-108">To resolve this issue you should restore the original UPN with the steps in the article,[Restore a user in Office 365](https://docs.microsoft.com/office365/admin/add-users/restore-user?view=o365-worldwide).</span></span>
2. <span data-ttu-id="72435-109">Özgün kullanıcı geri yükleyemezseniz, aşağıdaki adımları, [kullanıcı bilgileri listesinde bir kullanıcıyı kaldırmak]()kullanarak OneDrive sitesinden eski kullanıcı kaldırmanız gerekir.</span><span class="sxs-lookup"><span data-stu-id="72435-109">If you cannot restore the original user you should remove the old user from the OneDrive site using these steps, [Remove a user from the user info list]().</span></span> 
3. <span data-ttu-id="72435-110">Bu yapıldıktan sonra kullanıcının yönetici hakları OneDrive sitesine [Ekle admin kullanıcı OneDrive için kullanıcının](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive) aşağıdaki adımları izleyerek sahip doğrulayabilirsiniz</span><span class="sxs-lookup"><span data-stu-id="72435-110">After this is done, you can verify the user has admin rights to the OneDrive site by following the steps to [Add admin's for a user's OneDrive](https://docs.microsoft.com/sharepoint/manage-user-profiles?redirectSourcePath=%252fen-us%252farticle%252fmanage-user-profiles-in-the-sharepoint-admin-center-494bec9c-6654-41f0-920f-f7f937ea9723#add-and-remove-admins-for-a-users-onedrive)</span></span>

<span data-ttu-id="72435-111">İzin düzeyleri hakkında daha fazla bilgi için [SharePoint izin düzeylerini anlama](https://docs.microsoft.com/sharepoint/understanding-permission-levels)makalesine bakın.</span><span class="sxs-lookup"><span data-stu-id="72435-111">For more information on permission levels, see the article, [Understanding permission levels in SharePoint](https://docs.microsoft.com/sharepoint/understanding-permission-levels).</span></span>
