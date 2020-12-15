---
title: Yönetim önerileri nasıl eklenir ve yönetilir-önerilen adımlar
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/07/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004114"
- "7194"
ms.openlocfilehash: 142bf1474ac0e0eac5cecb9dddd35e28b6b6631e
ms.sourcegitcommit: 94036315916fbc79dca2a692c2e9bc1139dd28f6
ms.translationtype: MT
ms.contentlocale: tr-TR
ms.lasthandoff: 12/08/2020
ms.locfileid: "49678868"
---
# <a name="how-to-add-and-manage-adminstrators---recommended-steps"></a><span data-ttu-id="677d2-102">Yönetim önerileri nasıl eklenir ve yönetilir-önerilen adımlar</span><span class="sxs-lookup"><span data-stu-id="677d2-102">How to add and manage adminstrators - recommended steps</span></span>

<span data-ttu-id="677d2-103">**Abonelik yöneticisini veya ortak yöneticiyi düzenleme**</span><span class="sxs-lookup"><span data-stu-id="677d2-103">**Edit the Subscription Administrator or Co-administrator**</span></span>

- <span data-ttu-id="677d2-104">Hesap Yöneticisi her iki rolü de düzenleyebilir, abonelik Yöneticisi yalnızca [Azure portalında](https://ms.portal.azure.com/#home)ortak yöneticileri değiştirebilirler.</span><span class="sxs-lookup"><span data-stu-id="677d2-104">The Account Administrator can edit both roles whereas the Subscription Administrator can only change Co-administrators in the [Azure portal](https://ms.portal.azure.com/#home).</span></span>
- [<span data-ttu-id="677d2-105">Azure aboneliği yöneticilerini ekleme veya değiştirme</span><span class="sxs-lookup"><span data-stu-id="677d2-105">Add or change Azure subscription administrators</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/add-change-subscription-administrator)

<span data-ttu-id="677d2-106">**Abonelik Yöneticisi 'ni veya Iç (GERÇEKLEŞTIRILECEKTIR) abonelikleri için Co-Administrator güncelleştirme**</span><span class="sxs-lookup"><span data-stu-id="677d2-106">**Update the Subscription Administrator or Co-Administrator for Internal (AIRS) Subscriptions**</span></span>

<span data-ttu-id="677d2-107">Hizmet Yöneticisi veya ortak yönetici, aşağıdaki adımları kullanarak bu eyleme Self-sunabilir:</span><span class="sxs-lookup"><span data-stu-id="677d2-107">The Service Administrator or the Co-administrator can self-serve this action by using the following steps:</span></span>

1. <span data-ttu-id="677d2-108">[Azure portalında](https://ms.portal.azure.com/#home) oturum açın ve sol dikey, **maliyet yönetimi + faturalandırma** 'ı tıklatın.</span><span class="sxs-lookup"><span data-stu-id="677d2-108">Log in to the [Azure portal](https://ms.portal.azure.com/#home) and click **Cost Management + Billing** in the left blade.</span></span>
2. <span data-ttu-id="677d2-109">Aboneliğinizle birlikte satır öğesine tıklayın.</span><span class="sxs-lookup"><span data-stu-id="677d2-109">Click on the line item with your subscription.</span></span> <span data-ttu-id="677d2-110">Bu, aboneliğinizin genel görünümünü açar.</span><span class="sxs-lookup"><span data-stu-id="677d2-110">This opens the Overview for your subscription.</span></span>
3. <span data-ttu-id="677d2-111">**Abonelik** dikey penceresinde **Özellikler**'e tıklayın.</span><span class="sxs-lookup"><span data-stu-id="677d2-111">On the **Subscription** blade, click **Properties**.</span></span> 
4. <span data-ttu-id="677d2-112">**Hizmet Yöneticisi** düğmesine tıklayın.</span><span class="sxs-lookup"><span data-stu-id="677d2-112">Click the **Service Admin** button.</span></span>
5. <span data-ttu-id="677d2-113">Hizmet Yöneticisi olarak ayarlamak istediğiniz kullanıcının e-postasını girin ve **Tamam 'a** tıklayın.</span><span class="sxs-lookup"><span data-stu-id="677d2-113">Enter the email of the user whom you want to set as a Service Administrator and click **OK**.</span></span>

<span data-ttu-id="677d2-114">**Yönetici ekleme/değiştirme/kaldırma**</span><span class="sxs-lookup"><span data-stu-id="677d2-114">**Add/Change/Remove Co-administrator**</span></span>

1. <span data-ttu-id="677d2-115">[Azure portalında](https://ms.portal.azure.com/#home) hizmet yöneticisi olarak oturum açın.</span><span class="sxs-lookup"><span data-stu-id="677d2-115">Log in to the [Azure portal](https://ms.portal.azure.com/#home) as a Service Administrator.</span></span>
2. <span data-ttu-id="677d2-116">[Abonelikleri](https://ms.portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) açın ve bir abonelik seçin.</span><span class="sxs-lookup"><span data-stu-id="677d2-116">Open [Subscriptions](https://ms.portal.azure.com/#blade/Microsoft_Azure_Billing/SubscriptionsBlade) and select a subscription.</span></span> <span data-ttu-id="677d2-117">(Birlikte Yönetim Yardımcıları yalnızca abonelik kapsamında atanabilir.)</span><span class="sxs-lookup"><span data-stu-id="677d2-117">(Co-adminstrators can only be assigned at the subscription scope.)</span></span>
3. <span data-ttu-id="677d2-118">**Access Control (IAM)**  >  **Klasik yöneticileri** ekleme ortak  >    >  **yönetici** Ekle bölmesini açmak için yardımcı yönetici Ekle  'yi (ortak yönetici Ekle seçeneği devre dışıysa) açın.</span><span class="sxs-lookup"><span data-stu-id="677d2-118">Navigate to **Access control (IAM)** > **Classic administrators** > **Add** > **Add co-administrator** to open the **Add co-admin** pane (If the Add co-administrator option is disabled, it denotes that you do not have permissions).</span></span>
4. <span data-ttu-id="677d2-119">Eklemek istediğiniz kullanıcıyı seçin ve **Ekle**'ye tıklayın.</span><span class="sxs-lookup"><span data-stu-id="677d2-119">Select the user whom you want to add and click **Add**.</span></span>

<span data-ttu-id="677d2-120">**Daha fazla bilgi edinin:**</span><span class="sxs-lookup"><span data-stu-id="677d2-120">**Learn more:**</span></span>
- [<span data-ttu-id="677d2-121">Yardımcı yönetici ekleme</span><span class="sxs-lookup"><span data-stu-id="677d2-121">Add a Co-Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="677d2-122">Yardımcı yöneticiyi kaldırma</span><span class="sxs-lookup"><span data-stu-id="677d2-122">Remove a co-administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="677d2-123">Hizmet yöneticisini değiştirme</span><span class="sxs-lookup"><span data-stu-id="677d2-123">Change the Service Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="677d2-124">Hesap yöneticisini görüntüleme</span><span class="sxs-lookup"><span data-stu-id="677d2-124">View the Account Administrator</span></span>](https://docs.microsoft.com/azure/role-based-access-control/classic-administrators)
- [<span data-ttu-id="677d2-125">RBAC ve Azure portalını kullanarak erişimi yönetme</span><span class="sxs-lookup"><span data-stu-id="677d2-125">Manage access using RBAC and Azure portal</span></span>](https://docs.microsoft.com/azure/role-based-access-control/role-assignments-portal)

<span data-ttu-id="677d2-126">**Azure Active Directory (AD) kullanarak kullanıcıları ekleme/silme**</span><span class="sxs-lookup"><span data-stu-id="677d2-126">**Add/delete users using Azure Active Directory (AD)**</span></span>

<span data-ttu-id="677d2-127">Azure Active Directory (Azure AD) kuruluşunuzdan yeni kullanıcılar ekleyebilir veya varolan kullanıcıları silebilirsiniz:</span><span class="sxs-lookup"><span data-stu-id="677d2-127">You can add new users or delete existing users from your Azure Active Directory (Azure AD) organization:</span></span>

1. <span data-ttu-id="677d2-128">Yeni bir kullanıcı eklemek için, kuruluş için Kullanıcı Yöneticisi olarak [Azure portalında](https://ms.portal.azure.com/#home) oturum açın.</span><span class="sxs-lookup"><span data-stu-id="677d2-128">To add a new user, log in to the [Azure portal](https://ms.portal.azure.com/#home) as a User-administrator for the organization.</span></span>
2. <span data-ttu-id="677d2-129">**Azure Active Directory**'yi seçin, **Kullanıcılar** 'ı seçin ve ardından **Yeni Kullanıcı**'ya tıklayın.</span><span class="sxs-lookup"><span data-stu-id="677d2-129">Select **Azure Active Directory**, select **Users** and then click **New user**.</span></span>
3. <span data-ttu-id="677d2-130">**Kullanıcı** sayfasında, gerekli bilgileri doldurun.</span><span class="sxs-lookup"><span data-stu-id="677d2-130">On the **User** page, fill out the required information.</span></span> <span data-ttu-id="677d2-131">**Oluştur**'a tıklayın.</span><span class="sxs-lookup"><span data-stu-id="677d2-131">Click **Create**.</span></span> <span data-ttu-id="677d2-132">Kullanıcı oluşturulur ve Azure AD kiracınıza eklenir.</span><span class="sxs-lookup"><span data-stu-id="677d2-132">The user is created and added to your Azure AD tenant.</span></span>

<span data-ttu-id="677d2-133">**Daha fazla bilgi**:</span><span class="sxs-lookup"><span data-stu-id="677d2-133">**Learn more**:</span></span>

- [<span data-ttu-id="677d2-134">Yeni Kullanıcı ekleme</span><span class="sxs-lookup"><span data-stu-id="677d2-134">Add a new user</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory)
- [<span data-ttu-id="677d2-135">Kullanıcı silme</span><span class="sxs-lookup"><span data-stu-id="677d2-135">Delete a user</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/add-users-azure-active-directory)
- [<span data-ttu-id="677d2-136">Azure Active Directory kullanarak kullanıcının profil bilgilerini ekleme veya güncelleştirme</span><span class="sxs-lookup"><span data-stu-id="677d2-136">Add or update a user's profile information using Azure Active Directory</span></span>](https://docs.microsoft.com/azure/active-directory/fundamentals/active-directory-users-profile-azure-portal)

<span data-ttu-id="677d2-137">**Önerilen belgeler**</span><span class="sxs-lookup"><span data-stu-id="677d2-137">**Recommended documents**</span></span>

- [<span data-ttu-id="677d2-138">Rol tabanlı erişim denetimi (RBAC) nedir?</span><span class="sxs-lookup"><span data-stu-id="677d2-138">What is role-based access control (RBAC)?</span></span>](https://docs.microsoft.com/azure/role-based-access-control/overview)
- [<span data-ttu-id="677d2-139">Azure 'da farklı rolleri anlama</span><span class="sxs-lookup"><span data-stu-id="677d2-139">Understand the different roles in Azure</span></span>](https://docs.microsoft.com/azure/role-based-access-control/rbac-and-directory-admin-roles)
- [<span data-ttu-id="677d2-140">Azure Active Directory 'de yönetici rolü izinleri</span><span class="sxs-lookup"><span data-stu-id="677d2-140">Administrator role permissions in Azure Active Directory</span></span>](https://docs.microsoft.com/azure/active-directory/roles/permissions-reference)
- [<span data-ttu-id="677d2-141">Öğretici: RBAC ve Azure portalını kullanarak bir kullanıcıya erişim Izni verme</span><span class="sxs-lookup"><span data-stu-id="677d2-141">Tutorial: Grant access for a user using RBAC and the Azure portal</span></span>](https://docs.microsoft.com/azure/role-based-access-control/quickstart-assign-role-user-portal)
- [<span data-ttu-id="677d2-142">Azure 'da RBAC sorunlarını giderme</span><span class="sxs-lookup"><span data-stu-id="677d2-142">Troubleshoot RBAC in Azure</span></span>](https://docs.microsoft.com/azure/role-based-access-control/troubleshooting)
- [<span data-ttu-id="677d2-143">Azure Yönetim gruplarıyla kaynaklarınızı düzenleme</span><span class="sxs-lookup"><span data-stu-id="677d2-143">Organize your resources with Azure management groups</span></span>](https://docs.microsoft.com/azure/governance/management-groups/overview)
- [<span data-ttu-id="677d2-144">Azure faturasının kopyasını e-posta yoluyla isteme</span><span class="sxs-lookup"><span data-stu-id="677d2-144">How to request copy of Azure invoice via email</span></span>](https://azure.microsoft.com/en-us/blog/azure-email-invoices/)
- [<span data-ttu-id="677d2-145">Azure 'dan kredi veya banka kartı ekleme, güncelleştirme veya kaldırma</span><span class="sxs-lookup"><span data-stu-id="677d2-145">How to add, update or remove a credit or debit card from Azure</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/change-credit-card)
- [<span data-ttu-id="677d2-146">Aboneliği yönetme (yeniden etkinleştirme/Iptal etme/değiştirme)</span><span class="sxs-lookup"><span data-stu-id="677d2-146">Manage (Reactivate/Cancel/Switch) subscription</span></span>](https://docs.microsoft.com/azure/cost-management-billing/manage/subscription-disabled)



