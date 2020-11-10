---
title: Gıfın ekip konuşmalarını kullanma
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9003825"
- "6850"
ms.openlocfilehash: 2fc29974bff9484c226c9651b9b000a89cad14dc
ms.sourcegitcommit: 534e9217d99336eb471166ff83231c7e408fb1d9
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 11/09/2020
ms.locfileid: "48982574"
---
# <a name="using-giphys-in-teams-conversations"></a><span data-ttu-id="6e166-102">Gıfın ekip konuşmalarını kullanma</span><span class="sxs-lookup"><span data-stu-id="6e166-102">Using Giphys in Teams Conversations</span></span>

<span data-ttu-id="6e166-103">Ekipler sohbetinde gifiziksel erişim varsayılan olarak etkinleştirilmiştir.</span><span class="sxs-lookup"><span data-stu-id="6e166-103">Giphys access in Teams chat is enabled by default.</span></span> <span data-ttu-id="6e166-104">Yönetici olarak, [bir mesajlaşma ilkesi ayarlayarak](https://docs.microsoft.com/microsoftteams/messaging-policies-in-teams#messaging-policy-settings) ve **gifin konuşmaların** **Açık** olduğundan emin olmak için gıas kullanıcıları tarafından kullanılabilir olup olmadığını denetleyebilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="6e166-104">As an administrator, you can control if Giphys are available to users by [setting a messaging policy](https://docs.microsoft.com/microsoftteams/messaging-policies-in-teams#messaging-policy-settings) and ensuring that **Use Giphys in conversations** is **On**.</span></span>

<span data-ttu-id="6e166-105">Gelen GIF 'Ler ekip konuşmalarında beklendiği gibi çalışmıyorsa aşağıdakileri doğrulayın:</span><span class="sxs-lookup"><span data-stu-id="6e166-105">If GIFs are not working as expected in Teams conversations, verify:</span></span>

<span data-ttu-id="6e166-106">[Mesajlaşma ilkesi](https://docs.microsoft.com/microsoftteams/messaging-policies-in-teams) , gifiziksel.</span><span class="sxs-lookup"><span data-stu-id="6e166-106">The [messaging policy](https://docs.microsoft.com/microsoftteams/messaging-policies-in-teams) needs to allow Giphys.</span></span> <span data-ttu-id="6e166-107">PowerShell cmdlet 'lerini kullanarak doğrulamak için:</span><span class="sxs-lookup"><span data-stu-id="6e166-107">To verify by using PowerShell cmdlets:</span></span>

- <span data-ttu-id="6e166-108">[PowerShell Ile takımları yönetebildiğinizi](https://docs.microsoft.com/microsoftteams/teams-powershell-overview?view=o365-worldwide#manage-teams-with-powershell)doğrulayın.</span><span class="sxs-lookup"><span data-stu-id="6e166-108">Verify that you can [Manage Teams with PowerShell](https://docs.microsoft.com/microsoftteams/teams-powershell-overview?view=o365-worldwide#manage-teams-with-powershell).</span></span>
- <span data-ttu-id="6e166-109">[Get-CsTeamsMessagingPolicy-Identity genel](https://docs.microsoft.com/powershell/module/skype/get-csteamsmessagingpolicy?view=skype-ps) PowerShell komutunu çalıştırarak, **Allowgiphy** 'ın **true** olarak ayarlandığını doğrulayın.</span><span class="sxs-lookup"><span data-stu-id="6e166-109">Run the PowerShell command [Get-CsTeamsMessagingPolicy -Identity Global](https://docs.microsoft.com/powershell/module/skype/get-csteamsmessagingpolicy?view=skype-ps) and verify that **AllowGiphy** is set to **TRUE**.</span></span>
- <span data-ttu-id="6e166-110">**Allowgiphy** **yanlış** olarak ayarlanmışsa, aşağıdaki PowerShell komut [kümesi-CsTeamsMessagingPolicy-Identity Global-allowgıphy $true](https://docs.microsoft.com/powershell/module/skype/set-csteamsmessagingpolicy?view=skype-ps).</span><span class="sxs-lookup"><span data-stu-id="6e166-110">If **AllowGiphy** is set to **FALSE** , run the following PowerShell command [Set-CsTeamsMessagingPolicy -Identity Global -AllowGiphy $True](https://docs.microsoft.com/powershell/module/skype/set-csteamsmessagingpolicy?view=skype-ps).</span></span>

<span data-ttu-id="6e166-111">Giphy URL 'ye erişime izin vermek için [Isteğe bağlı bağlantılı deneyimlerin](https://docs.microsoft.com/deployoffice/privacy/optional-connected-experiences) etkinleştirilmesi gerekir.</span><span class="sxs-lookup"><span data-stu-id="6e166-111">[Optional Connected Experiences](https://docs.microsoft.com/deployoffice/privacy/optional-connected-experiences) need to be enabled to allow access to the Giphy URL.</span></span>

> [!NOTE]
> <span data-ttu-id="6e166-112">Kiracınız için yapılandırılmış birden fazla ekip mesajlaşma ilkeniz varsa, etkilenen kullanıcıya atanan ilkenin kimliğini [Get-CsOnlineUser-Identity](https://docs.microsoft.com/powershell/module/skype/get-csonlineuser?view=skype-ps) | PowerShell komutuyla belirleyebilirsiniz. <user@domain.com> TeamsMessagingPolicy öğesini seçin.</span><span class="sxs-lookup"><span data-stu-id="6e166-112">If you have multiple Teams Messaging policies configured for your tenant, you can determine the identity of the policy assigned to the impacted user with the PowerShell command [Get-CsOnlineUser -Identity](https://docs.microsoft.com/powershell/module/skype/get-csonlineuser?view=skype-ps) <user@domain.com> | Select TeamsMessagingPolicy.</span></span>
