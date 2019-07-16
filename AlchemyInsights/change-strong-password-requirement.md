---
title: Güçlü parola gereksinim Değiştir
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: ''
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000105"
- "1600"
ms.openlocfilehash: 53affd2a347c004e7b21b353c2b3df98bc30a585
ms.sourcegitcommit: a7e5ca472000dfec471950bafd12eee8d7144f74
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 07/16/2019
ms.locfileid: "35701603"
---
# <a name="change-strong-password-requirement"></a><span data-ttu-id="0eaa4-102">Güçlü parola gereksinim Değiştir</span><span class="sxs-lookup"><span data-stu-id="0eaa4-102">Change strong password requirement</span></span>

<span data-ttu-id="0eaa4-103">Güçlü parolalar, varsayılan olarak gereklidir.</span><span class="sxs-lookup"><span data-stu-id="0eaa4-103">Strong passwords are required by default.</span></span> 

<span data-ttu-id="0eaa4-104">PowerShell kullanarak güçlü parolalar bu komutla belirli kullanıcılar için devre dışı bırakabilirsiniz:</span><span class="sxs-lookup"><span data-stu-id="0eaa4-104">Using PowerShell you can disable strong passwords for specific users with this command:</span></span><br>
<span data-ttu-id="0eaa4-105">*Set-MsolUser – UserPrincipalName <UserPrincipalName> – StrongPasswordRequired $false*</span><span class="sxs-lookup"><span data-stu-id="0eaa4-105">*Set-MsolUser –UserPrincipalName <UserPrincipalName> –StrongPasswordRequired  $false*</span></span>

- [<span data-ttu-id="0eaa4-106">Parola İlkesi hakkında daha fazla bilgi</span><span class="sxs-lookup"><span data-stu-id="0eaa4-106">More information on password policy</span></span>](https://docs.microsoft.com/azure/active-directory/authentication/concept-sspr-policy#password-policies-that-only-apply-to-cloud-user-accounts)
- [<span data-ttu-id="0eaa4-107">O365 PowerShell ile bağlanma</span><span class="sxs-lookup"><span data-stu-id="0eaa4-107">How to connect to O365 with PowerShell</span></span>](https://docs.microsoft.com/office365/enterprise/powershell/connect-to-office-365-powershell#connect-with-the-microsoft-azure-active-directory-module-for-windows-powershell)
- [<span data-ttu-id="0eaa4-108">PowerShell MsolUser komutları hakkında daha fazla bilgi</span><span class="sxs-lookup"><span data-stu-id="0eaa4-108">More information on PowerShell MsolUser commands</span></span>](https://docs.microsoft.com/powershell/module/msonline/set-msoluser?view=azureadps-1.0)