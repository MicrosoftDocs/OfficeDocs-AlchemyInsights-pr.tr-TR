---
title: MFA etkinleştirildiğinde Exchange Online PowerShell'e Bağlanma
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "761"
- "3500011"
ms.assetid: 9b0b89e3-d1d7-4e4d-93de-bb4cd00904d8
ms.openlocfilehash: 81d9e74652b20d2bbae6cae581cc31fdc33e82da
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 04/22/2020
ms.locfileid: "43705825"
---
# <a name="connect-to-exchange-online-powershell-when-mfa-is-enabled"></a><span data-ttu-id="d8445-102">MFA etkinleştirildiğinde Exchange Online PowerShell'e bağlanın</span><span class="sxs-lookup"><span data-stu-id="d8445-102">Connect to Exchange Online PowerShell when MFA is enabled</span></span>

<span data-ttu-id="d8445-103">Hesabınızda çok faktörlü kimlik doğrulama (MFA) etkinse, Exchange Online PowerShell'e bağlanmak için bu yönergeleri izlemeniz gerekir: [Çok faktörlü kimlik doğrulaması kullanarak Exchange Online PowerShell'e bağlanın.](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell)</span><span class="sxs-lookup"><span data-stu-id="d8445-103">If your account has multi-factor authentication (MFA) enabled, you need to follow these instructions to connect to Exchange Online PowerShell: [Connect to Exchange Online PowerShell using multi-factor authentication](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/mfa-connect-to-exchange-online-powershell).</span></span>

<span data-ttu-id="d8445-104">**Not**: Geçmişte Exchange Online PowerShell'e düzenli [bağlantı yönergelerini](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell)kullanarak bağlanmış olsanız bile, Hesabınız için MFA etkinleştirildikten sonra MFA bağlantı yönergelerini kullanmanız gerekir.</span><span class="sxs-lookup"><span data-stu-id="d8445-104">**Note**: Even if you've connected to Exchange Online PowerShell in the past using [the regular connection instructions](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell), you need to use the MFA connection instructions after MFA has been enabled for your account.</span></span>
