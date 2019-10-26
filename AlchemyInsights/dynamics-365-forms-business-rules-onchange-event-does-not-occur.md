---
title: Dynamics 365 Formlar İş Kuralları - İş Kuralı Bir Form için Ateş Değil
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: cbdedd2c5fcf5517243e60e36d86479d6c3f7814
ms.sourcegitcommit: 0b06093dabd685f76cc39b1d7c0f8b03883b6e79
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 10/25/2019
ms.locfileid: "36529039"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a><span data-ttu-id="eb96c-102">Alan programlı olarak değiştirilirse OnChange olayı oluşmaz</span><span class="sxs-lookup"><span data-stu-id="eb96c-102">OnChange event does not occur if the field is changed programmatically</span></span>

<span data-ttu-id="eb96c-103">Alan *öznitelik* kullanılarak programlı olarak değiştirilirse *OnChange* olayı oluşmaz. [setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) yöntemi.</span><span class="sxs-lookup"><span data-stu-id="eb96c-103">The *OnChange* event does not occur if the field is changed programmatically using the *attribute.*[setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) method.</span></span> <span data-ttu-id="eb96c-104">*OnChange* olayının olay işleyicilerinin değeri ayarladıktan sonra çalışmasını istiyorsanız *formContext.data.entity özniteliğini* kullanmanız gerekir. [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) yöntemi kodunuzda.</span><span class="sxs-lookup"><span data-stu-id="eb96c-104">If you want event handlers for the *OnChange* event to run after you set the value you must use the *formContext.data.entity attribute.*[fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) method in your code.</span></span>

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
