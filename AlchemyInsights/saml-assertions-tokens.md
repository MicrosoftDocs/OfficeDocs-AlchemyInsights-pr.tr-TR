---
title: SAML onayları (belirteçler)
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
- "9004341"
- "7753"
ms.openlocfilehash: 557e23da09df3ab066c2ad7c0352f5fd904b5490
ms.sourcegitcommit: a61a29dbd0382370fea0be5fa4a61c9a1a9354c7
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 01/18/2021
ms.locfileid: "49885679"
---
# <a name="saml-assertions-tokens"></a><span data-ttu-id="cee2f-102">SAML onayları (belirteçler)</span><span class="sxs-lookup"><span data-stu-id="cee2f-102">SAML Assertions (Tokens)</span></span>

1. <span data-ttu-id="cee2f-103">Güvenlik onayları Işaretleme dili (SAML) belirteçleri taleplerin XML temsilleri.</span><span class="sxs-lookup"><span data-stu-id="cee2f-103">Security Assertions Markup Language (SAML) tokens are XML representations of claims.</span></span> <span data-ttu-id="cee2f-104">Varsayılan olarak, SAML belirteçlerinde Windows Communication Foundation (WCF) kullanımları, yayımlanan belirteçlerdir.</span><span class="sxs-lookup"><span data-stu-id="cee2f-104">By default, SAML tokens Windows Communication Foundation (WCF) uses in federated security scenarios are issued tokens.</span></span> <span data-ttu-id="cee2f-105">Daha fazla bilgi [için bkz.](https://docs.microsoft.com/dotnet/framework/wcf/feature-details/saml-tokens-and-claims)</span><span class="sxs-lookup"><span data-stu-id="cee2f-105">For more information, see [SAML Tokens and Claims](https://docs.microsoft.com/dotnet/framework/wcf/feature-details/saml-tokens-and-claims).</span></span>
2. <span data-ttu-id="cee2f-106">Microsoft Identity platform, her kimlik doğrulama akışının işlenmesinde birkaç türde güvenlik belirteci gösterir.</span><span class="sxs-lookup"><span data-stu-id="cee2f-106">The Microsoft identity platform emits several types of security tokens in the processing of each authentication flow.</span></span> <span data-ttu-id="cee2f-107">[SAML belirteci talepleri başvurusu](https://docs.microsoft.com/azure/active-directory/develop/reference-saml-tokens) , SAML 2,0 belirteçlerinin biçimini, güvenlik özelliklerini ve içeriğini açıklar.</span><span class="sxs-lookup"><span data-stu-id="cee2f-107">[SAML token claims reference](https://docs.microsoft.com/azure/active-directory/develop/reference-saml-tokens) describes the format, security characteristics, and contents of SAML 2.0 tokens.</span></span>
3. <span data-ttu-id="cee2f-108">Belirteç ömürleri yapılandırmasını anlamak için [Microsoft Identity platformunda yapılandırılabilir belirteç ömürleri](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) bölümündeki yönergeleri izleyin.</span><span class="sxs-lookup"><span data-stu-id="cee2f-108">Follow the guidance in [Configurable token lifetimes in Microsoft identity platform](https://docs.microsoft.com/azure/active-directory/develop/active-directory-configurable-token-lifetimes) to understand how to configure token lifetimes.</span></span>
4. <span data-ttu-id="cee2f-109">Azure AD SAML belirteci şifrelemesini yapılandırmayı öğrenmek için [Bu makalede](https://docs.microsoft.com/azure/active-directory/manage-apps/howto-saml-token-encryption) özetlenen adımları izleyin.</span><span class="sxs-lookup"><span data-stu-id="cee2f-109">Follow the steps outlined in [this article](https://docs.microsoft.com/azure/active-directory/manage-apps/howto-saml-token-encryption) to understand how to configure Azure AD SAML token encryption.</span></span>
5. <span data-ttu-id="cee2f-110">Azure AD 'de, sertifika imzalama seçeneklerini ve sertifika imzalama algoritmasını ayarlayabilirsiniz.</span><span class="sxs-lookup"><span data-stu-id="cee2f-110">In Azure AD, you can set up certificate signing options and the certificate signing algorithm.</span></span> <span data-ttu-id="cee2f-111">Daha fazla bilgi için, [Azure Active Directory 'de Galeri UYGULAMALARıNıN SAML belirtecindeki gelişmiş sertifika imzalama seçeneklerine](https://docs.microsoft.com/azure/active-directory/manage-apps/certificate-signing-options)bakın.</span><span class="sxs-lookup"><span data-stu-id="cee2f-111">For more information, see [Advanced certificate signing options in the SAML token for gallery apps in Azure Active Directory](https://docs.microsoft.com/azure/active-directory/manage-apps/certificate-signing-options).</span></span>
