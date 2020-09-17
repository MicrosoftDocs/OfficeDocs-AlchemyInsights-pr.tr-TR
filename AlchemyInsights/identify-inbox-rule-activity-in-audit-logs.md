---
title: Denetim günlüklerinde gelen kutusu kuralı etkinliğini belirleme
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1368"
- "3100005"
ms.assetid: ''
ms.openlocfilehash: 3de6fcde6dc649cb77077d469cc66d4003e0c890
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 09/15/2020
ms.locfileid: "47779071"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="36b96-102">Denetim günlüklerinde gelen kutusu kuralı etkinliğini belirleme</span><span class="sxs-lookup"><span data-stu-id="36b96-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="36b96-103">Gelen kutusu kuralı olaylarını görüntülemek (gelen kutusu kurallarını değiştirmek ve silmek) için Microsoft 365 güvenlik & Uyumluluk Merkezi 'nde denetim günlüğü aramasını kullanabilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="36b96-103">You can use audit log search in the Microsoft 365 Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="36b96-104">[Microsoft 365 güvenlik & Uyumluluk Merkezi](https://protection.office.com/)'nde oturum açın.</span><span class="sxs-lookup"><span data-stu-id="36b96-104">Log in to the [Microsoft 365 Security & Compliance Center](https://protection.office.com/).</span></span>

2. <span data-ttu-id="36b96-105">**Search**  >  **Denetim günlüğü aramasını** ara sayfasına gidin.</span><span class="sxs-lookup"><span data-stu-id="36b96-105">Go to the **Search** > **Audit log search** page.</span></span>

3. <span data-ttu-id="36b96-106">**Başlangıç tarihi** ve **bitiş tarihi** alanlarında tarih aralığını seçin.</span><span class="sxs-lookup"><span data-stu-id="36b96-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="36b96-107">**Exchange posta kutusu aktiviteleri**altında, **Aktiviteler** alanının **Yeni-inboxrule**ile ayarlandığını doğrulayın</span><span class="sxs-lookup"><span data-stu-id="36b96-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="36b96-108">**Ara**'ya tıklayın.</span><span class="sxs-lookup"><span data-stu-id="36b96-108">Click **Search**.</span></span>

<span data-ttu-id="36b96-109">Sonuçlarda bir denetim kaydı seçin.</span><span class="sxs-lookup"><span data-stu-id="36b96-109">In the results, select an audit record.</span></span> <span data-ttu-id="36b96-110">Ayrıntılar açılır listesinde, **ek bilgi**'yi tıklatın.</span><span class="sxs-lookup"><span data-stu-id="36b96-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="36b96-111">Gelen kutusu kuralı ayarları hakkında bilgi **Parametreler** alanında görüntülenir.</span><span class="sxs-lookup"><span data-stu-id="36b96-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="36b96-112">Daha fazla bilgi için bkz: [kullanıcının gelen kutusu kuralı oluşturup oluşturmayacağınızı belirleme](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="36b96-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>
