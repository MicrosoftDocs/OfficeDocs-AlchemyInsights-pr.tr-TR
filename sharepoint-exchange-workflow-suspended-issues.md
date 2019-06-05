---
title: SharePoint Online uygulamasını kullanmaya başlama
ms.author: kirks
author: Techwriter40
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 7ae05f21-eb16-4d71-9e19-4f097eb100d2
ms.openlocfilehash: 9a8d72a01ed35794fcab370b48bbb189663d3396
ms.sourcegitcommit: 6d341637dbb14e90726a1ce1d68f077ace9bb765
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 06/04/2019
ms.locfileid: "34718766"
---
# <a name="workflows-in-sharepoint"></a><span data-ttu-id="61c5f-102">SharePoint iş akışları</span><span class="sxs-lookup"><span data-stu-id="61c5f-102">Workflows in SharePoint</span></span>

<p><span data-ttu-id="61c5f-103">SharePoint iş akışları e-postalar göndermek değil, kuruluşunuzda Exchange Online gönderen sınırları karşılaşmış olabilir.&nbsp;</span><span class="sxs-lookup"><span data-stu-id="61c5f-103">If SharePoint workflows are not sending emails, your organization may have encountered the Exchange Online sender limits.&nbsp;</span></span></p> <p><span data-ttu-id="61c5f-104">Aşağıdaki öğelerden birini kullanıyorsanız, 'İş akışı askıya' hata iletisi ortaya çıkabilir:</span><span class="sxs-lookup"><span data-stu-id="61c5f-104">'Workflow is Suspended' error message may occur if you have one of the following items:</span></span></p> <ul> <li><span data-ttu-id="61c5f-105">Bir iş akışı SharePoint 2010 SharePoint veya SharePoint 2013 iş akışı platform türü kullanan çevrimiçi olarak vardır.</span><span class="sxs-lookup"><span data-stu-id="61c5f-105">You have a workflow in SharePoint Online that's using the SharePoint 2010 or SharePoint 2013 workflow platform type.</span></span></li> <li><span data-ttu-id="61c5f-106">İş akışı, bir saat, günde 10. 000'den fazla alıcı veya dakika başına 30'dan fazla ileti 200'den fazla kullanıcılara özel e-posta iletisi göndermek için yapılandırılır.</span><span class="sxs-lookup"><span data-stu-id="61c5f-106">The workflow is configured to send a custom email message to more than 200 users at a time, more than 10,000 recipients per day, or more than 30 messages per minute.</span></span></li> <li><span data-ttu-id="61c5f-107">İş akışını çalıştırmak, e-posta iletisi gönderilmez ve hata iletisini görürsünüz, <strong>İç Durumu Beklemede için ayarlamak</strong> veya <strong>bir alıcıya gönderilemiyor</strong> görüntülenir.</span><span class="sxs-lookup"><span data-stu-id="61c5f-107">When you run the workflow, the email message isn't sent, and you notice the error message, <strong>Internal Status is set to Suspended</strong> or <strong>Unable to send to a recipient</strong> is displayed.</span></span></li> </ul> <p><span data-ttu-id="61c5f-108">Daha fazla bilgi için lütfen aşağıdaki <a href="https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US">makaleye</a>bakın.</span><span class="sxs-lookup"><span data-stu-id="61c5f-108">For more information, please refer to the following <a href="https://support.office.com/en-us/article/-daily-email-limit-has-exceeded-and-your-workflow-has-been-suspended-or-unable-to-send-to-a-recipient-error-in-a-sharepoint-online-workflow-89d02169-5fa6-4259-affc-73edb6ca9fb6?ui=en-US&amp;rs=en-US&amp;ad=US">article</a>.</span></span></p>

