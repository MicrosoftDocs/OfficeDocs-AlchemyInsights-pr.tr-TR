---
title: Modern Azure e-posta Faturalaması
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "9003801"
- "6866"
ms.openlocfilehash: 65df6091a97d4937379ded384a78b5d07aa76e42
ms.sourcegitcommit: a5ba4dc8c349ed79147f67b62bde544281f7c106
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 11/03/2020
ms.locfileid: "48922147"
---
# <a name="email-invoicing-in-azure"></a><span data-ttu-id="439e1-102">Azure 'da e-posta faturalamayı</span><span class="sxs-lookup"><span data-stu-id="439e1-102">Email invoicing in Azure</span></span>

<span data-ttu-id="439e1-103">E-posta faturası tercihini güncelleştirmek için fatura profilinde bir sahibin veya katılımcı rolüne sahip olmanız gerekir.</span><span class="sxs-lookup"><span data-stu-id="439e1-103">You must have an owner or a contributor role on the billing profile or its billing account to update its email invoice preference.</span></span> <span data-ttu-id="439e1-104">Bir kez seçtiğinizde, bir faturalandırma profilinde sahibi, katılımcısı, okuyucular ve fatura yöneticisi rollerine sahip tüm kullanıcılar bu faturanın faturasını alır.</span><span class="sxs-lookup"><span data-stu-id="439e1-104">Once you have opted-in, all users with an owner, contributor, readers, and invoice manager roles on a billing profile will get its invoice in email.</span></span>

1. <span data-ttu-id="439e1-105">[Azure portalında](https://portal.azure.com/)oturum açın.</span><span class="sxs-lookup"><span data-stu-id="439e1-105">Sign in to the [Azure portal](https://portal.azure.com/).</span></span>
2. <span data-ttu-id="439e1-106">**Maliyet yönetimi ve faturalamayı** arayın.</span><span class="sxs-lookup"><span data-stu-id="439e1-106">Search for **Cost Management + Billing**.</span></span>
3. <span data-ttu-id="439e1-107">Sol taraftaki **faturaları** seçin ve ardından sayfanın başından **e-posta faturası** 'nı seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-107">Select **Invoices** from the left-hand side and then select **Email Invoice** from the top of the page.</span></span>
4. <span data-ttu-id="439e1-108">Birden fazla faturalandırma profiliniz varsa, bir faturalandırma profili seçin ve **kabul** et 'i seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-108">If you have multiple billing profiles, select a billing profile and then select **Opt in**.</span></span>

5. <span data-ttu-id="439e1-109">**Güncelleştir** 'i seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-109">Select **Update**.</span></span>
6. <span data-ttu-id="439e1-110">Birden fazla faturalandırma profiliniz varsa, bir faturalandırma profili seçin ve **kabul** et 'i seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-110">If you have multiple billing profiles, select a billing profile and then select **Opt in**.</span></span>

<span data-ttu-id="439e1-111">Başkalarına, bir MCA veya MPA fatura profili için Fatura Yöneticisi rolü atayarak görüntüleyebilir, indirin ve ödeyin.</span><span class="sxs-lookup"><span data-stu-id="439e1-111">You give others access to view, download, and pay invoices by assigning them the invoice manager role for an MCA or MPA billing profile.</span></span> <span data-ttu-id="439e1-112">Faturanızı e-posta ile almak istiyorsanız, kullanıcılar da faturaları e-posta ile alırlar.</span><span class="sxs-lookup"><span data-stu-id="439e1-112">If you've opted in to get your invoice in email, users also get the invoices in email.</span></span>

1. <span data-ttu-id="439e1-113">[Azure portalında](https://portal.azure.com/)oturum açın.</span><span class="sxs-lookup"><span data-stu-id="439e1-113">Sign in to the [Azure portal](https://portal.azure.com/).</span></span>
2. <span data-ttu-id="439e1-114">**Maliyet yönetimi ve faturalamayı** arayın.</span><span class="sxs-lookup"><span data-stu-id="439e1-114">Search for **Cost Management + Billing**.</span></span>
3. <span data-ttu-id="439e1-115">Sol taraftaki **faturalandırma profilleri** 'ni seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-115">Select **Billing profiles** from the left-hand side.</span></span> <span data-ttu-id="439e1-116">Faturalandırma profilleri listesinde, Fatura Yöneticisi rolünü atamak istediğiniz bir faturalandırma profili seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-116">From the billing profiles list, select a billing profile for which you want to assign an invoice manager role.</span></span>
4. <span data-ttu-id="439e1-117">Sol taraftaki **erişim denetimi 'ni (IAM)** seçin ve ardından sayfanın başından **Ekle** 'yi seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-117">Select **Access Control (IAM)** from the left-hand side and then select **Add** from the top of the page.</span></span>

<span data-ttu-id="439e1-118">Rol açılan listesinde, **Fatura Yöneticisi 'ni** seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-118">In the Role drop-down list, select **Invoice Manager**.</span></span> <span data-ttu-id="439e1-119">Erişim verecek kullanıcının e-posta adresini girin.</span><span class="sxs-lookup"><span data-stu-id="439e1-119">Enter the email address of the user to give access.</span></span> <span data-ttu-id="439e1-120">Rolü atamak için **Kaydet** 'i seçin.</span><span class="sxs-lookup"><span data-stu-id="439e1-120">Select **Save** to assign the role.</span></span>
