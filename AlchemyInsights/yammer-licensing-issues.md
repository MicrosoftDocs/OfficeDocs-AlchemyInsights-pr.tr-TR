---
title: Yammer lisanslama sorunları
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/14/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "5900"
- "9003071"
ms.openlocfilehash: f0a7625c7b77860e5ba0e29f2df47101749aace3
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/14/2020
ms.locfileid: "47657296"
---
# <a name="yammer-licensing-issues"></a><span data-ttu-id="89dad-102">Yammer lisanslama sorunları</span><span class="sxs-lookup"><span data-stu-id="89dad-102">Yammer licensing issues</span></span>

<span data-ttu-id="89dad-103">Tüm kullanıcıların Yammer Enterprise hizmetini kullanmak için lisansı olmalıdır, ancak varsayılan olarak Yammer kullanıcıların hizmete erişmek için bir lisansı olmasını gerektirmez.</span><span class="sxs-lookup"><span data-stu-id="89dad-103">All users must have a license to use the Yammer Enterprise service, but by default Yammer does not require that users have a license to access the service.</span></span> <span data-ttu-id="89dad-104">Yönetici ayarı Yammer lisansı olmayan Microsoft 365 kullanıcılarını engelleyecek şekilde değiştirdiğinde, Yammer Kurumsal lisansı atanmamış kullanıcılar Yammer hizmetine erişemez.</span><span class="sxs-lookup"><span data-stu-id="89dad-104">When an administrator changes the setting to block Microsoft 365 users without Yammer licenses, users not assigned a Yammer Enterprise license can't access the Yammer service.</span></span> <span data-ttu-id="89dad-105">Daha fazla bilgi için [Office 365 'Da Yammer kullanıcı lisanslarını yönetme](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365) konusuna bakın</span><span class="sxs-lookup"><span data-stu-id="89dad-105">For more info, see [Manage Yammer user licenses in Office 365](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365)</span></span> 

<span data-ttu-id="89dad-106">Lisanslar kullanıcılardan kaldırıldığında, Yammer kutucuğu artık görüntülenmez ve diğer hizmetler özellikleri gizlemek için lisans kaldırma özelliğini kullanabilir.</span><span class="sxs-lookup"><span data-stu-id="89dad-106">When licenses are removed from users, the Yammer tile is no longer displayed, and other services can use license removal to hide features.</span></span> <span data-ttu-id="89dad-107">Diğer durumlarda Özellikler görünmeye devam edebilir ancak çalışmaya devam eder.</span><span class="sxs-lookup"><span data-stu-id="89dad-107">In other cases, features can still appear but require licence assignment to operate.</span></span>  

<span data-ttu-id="89dad-108">**Lisans, Kullanıcı için güncelleştirilmez**</span><span class="sxs-lookup"><span data-stu-id="89dad-108">**License is not getting updated for the user**</span></span>  

<span data-ttu-id="89dad-109">Bazen kullanıcıya lisans atanır ancak Yammer 'a erişemez.</span><span class="sxs-lookup"><span data-stu-id="89dad-109">Occasionally, a user is assigned a license but is still unable to access Yammer.</span></span> <span data-ttu-id="89dad-110">Bir toplu lisans ataması yapılırken gecikmelerin oluşma olasılığı daha yüksektir.</span><span class="sxs-lookup"><span data-stu-id="89dad-110">Delays are more likely to occur when a mass license assignment is in progress.</span></span> <span data-ttu-id="89dad-111">Sistem eşzamanlı olarak çalıştığı için, Yammer kullanıcıları Azure AD 'de lisanslar değiştiği sırayla güncelleştirilmeyebilir.</span><span class="sxs-lookup"><span data-stu-id="89dad-111">Yammer users might not be updated in the same order as licenses are changed in Azure AD because the system runs asynchronously.</span></span> <span data-ttu-id="89dad-112">Lisans eşitleme sorunlarını bildirmek için bir destek durumunu açmadan önce 24 saate kadar bekleyin.</span><span class="sxs-lookup"><span data-stu-id="89dad-112">Wait up to 24 hours before opening a support case to report license sync issues.</span></span>  

<span data-ttu-id="89dad-113">**Toplu lisans ataması**</span><span class="sxs-lookup"><span data-stu-id="89dad-113">**Bulk licence assignment**</span></span>  

<span data-ttu-id="89dad-114">Lisanslar Yönetim Merkezi veya PowerShell betiği aracılığıyla atanabilir.</span><span class="sxs-lookup"><span data-stu-id="89dad-114">Licenses can be assigned through the admin center or PowerShell scripting.</span></span> <span data-ttu-id="89dad-115">Daha fazla bilgi için, Office 365 PowerShell ile [kullanıcılara lisans atama](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) ve [Kullanıcı hesaplarına lisans atama](https://docs.microsoft.com/office365/enterprise/powershell/assign-licenses-to-user-accounts-with-office-365-powershell)konusuna bakın.</span><span class="sxs-lookup"><span data-stu-id="89dad-115">For more info, see [Assign licenses to users](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) and [Assign licenses to user accounts with Office 365 PowerShell](https://docs.microsoft.com/office365/enterprise/powershell/assign-licenses-to-user-accounts-with-office-365-powershell).</span></span> 

<span data-ttu-id="89dad-116">Microsoft desteği, kod oluşturmayla ilgili Yardım sağlamaz, ancak Yammer lisans atamasında belgeler kullanılabilir.</span><span class="sxs-lookup"><span data-stu-id="89dad-116">Microsoft Support does not provide assistance with creating scripts, but documentation on Yammer license assignment is available.</span></span> <span data-ttu-id="89dad-117">Daha fazla bilgi için [Windows PowerShell kullanarak Yammer lisanslarını yönetme](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365#manage-yammer-licenses-by-using-windows-powershell)konusuna bakın.</span><span class="sxs-lookup"><span data-stu-id="89dad-117">For more info, see [Manage Yammer licenses by using Windows PowerShell](https://docs.microsoft.com/yammer/manage-yammer-users/manage-yammer-licenses-in-office-365#manage-yammer-licenses-by-using-windows-powershell).</span></span>