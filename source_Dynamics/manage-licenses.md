---
title: "Manage licenses for Market Insights | Microsoft Docs"
description: "Learn how to manage user licenses for users of Market Insights."
keywords: "licenses, Market Insights, Office 365, user license, assign, remove"
ms.date: 10/31/2018
ms.service: dynamics-365-ai
ms.topic: article
ms.assetid: 48d75683-0297-46dc-bcb1-a8301525db02
author: m-hartmann
ms.author: mhart
manager: shellyha
ms.custom: dyn365-ai-marketinsights
search.audienceType: 
  - admin
  - customizer
  - enduser
search.app: 
  - D365CE
  - D365SE
---

# Manage licenses for [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)]

(This topic is pre-release documentation and is subject to change.)

Using the [!INCLUDE[pn_MS_Office_365](../includes/pn-ms-office-365.md)] admin center, you can manage [!INCLUDE[Dynamics 365 Market Insights](../includes/pn-market-insights-long.md)] user licenses and other services. This topic provides information about the steps to give users access to [!INCLUDE[Dynamics 365 Market Insights](../includes/pn-market-insights-long.md)].  
You must be your organization's [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] administrator to perform the following tasks.

## Prepare your organization

For step-by-step instructions on adding a service to an existing [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] subscription, see [Office help: Manage a subscription](https://go.microsoft.com/fwlink/p/?LinkId=392376).

As a [!INCLUDE[pn_microsoftcrm](../includes/pn-microsoftcrm.md)] customer, review [Microsoft Dynamics 365 pricing and licensing](https://go.microsoft.com/fwlink/p/?LinkID=401462) if the organization is eligible for [!INCLUDE[Dynamics 365 Market Insights](../includes/pn-market-insights-long.md)] user licenses.

If your school or work organization doesn't have an [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] subscription yet, you need to create an [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] tenant for your organization.

### Sign up for a new organization on Office 365

1. Sign up on [Office 365](https://admin.microsoft.com/).

2. Follow the wizard to create your organization and your administrator account.

3. Optionally, select the number of users that you plan to provide access for.

4. Optionally, select add-ins to enhance your post quota.

5. Complete the purchase process to start provisioning [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)].

It takes a few minutes to complete the provisioning process before you can start using [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)]. You'll receive an email with the details to access your [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)] instance when it's set up. You are now ready to [sign in](sign-in.md) and [set up](settings-administration.md) [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)].

## Assign a license to a user

Enable users to work with [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)] by assigning [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)] licenses to them. As an administrator you can always [modify the user's permissions](assign-user-roles.md) to use certain features.  

1. In the [Microsoft 365 admin center](https://admin.microsoft.com/), select **Users** > **Active Users**, and then select the user.

2. In the **Product licenses** tab, select **Edit**.

3. Set the toggle for **Dynamics 365 Customer Engagement Plan** or **[!INCLUDE[Dynamics 365 Market Insights](../includes/pn-market-insights-long.md)]** to **On**.

4. Select **Save** to confirm your change and update the user's product licenses.  

## Remove a license from a user

When you [create an Office 365 user account](https://go.microsoft.com/fwlink/p/?LinkId=526143), you normally [assign a license](https://go.microsoft.com/fwlink/p/?LinkId=390651) to users so that they can use certain features. 

When you [remove the assigned license](https://go.microsoft.com/fwlink/p/?LinkId=526144) from a user in your subscription, the license assigned to that user automatically becomes available for assignment to a different user. If you want the user to still have access to other applications that you manage through [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)], for example [!INCLUDE[pn_Microsoft_Exchange_Online](../includes/pn-microsoft-exchange-online.md)] or [!INCLUDE[pn_ms_SharePoint_long](../includes/pn-ms-sharepoint-long.md)], don't delete the user. Instead, remove the [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)] license you've assigned to the user.  
Removing a user's license  from [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)] deletes all related custom settings, alerts, and any owned or shared streams. Deleted custom settings can't be restored. Search topics owned by a removed user will remain. It takes up to 30 days to reflect the removal of a license in the list of users in [!INCLUDE[Market Insights](../includes/pn-market-insights-short.md)].

1. In the [Microsoft 365 admin center](https://admin.microsoft.com/), select **Users** > **Active Users**, and then select the user.

2. In the **Product licenses** tab, select **Edit**.

3. Set the toggle for **Dynamics 365 Customer Engagement Plan** or **[!INCLUDE[Dynamics 365 Market Insights](../includes/pn-market-insights-long.md)]** to **Off**.

4. Select **Save** to confirm your change and update the user's product licenses.

## Purchase licenses or add other Office 365 plans

You can purchase and add licenses and other plans to your subscription any time. You must be a global or billing administrator for your company's account to purchase licenses or add other [!INCLUDE[pn_Office_365](../includes/pn-office-365.md)] plans to your subscription.  
[!INCLUDE[proc_more_information](../includes/proc-more-information.md)] [Microsoft Dynamics 365 pricing and licensing](https://go.microsoft.com/fwlink/p/?LinkID=401462)

### Purchase additional licenses

1. In the [!INCLUDE[pn_office_365_admin_center](../includes/pn-office-365-admin-center.md)], select **Billing** > **Purchase Services**.

2. Select the [!INCLUDE[Dynamics 365 Market Insights](../includes/pn-market-insights-long.md)] add-in or user licenses you want to purchase, and then select **Change license quantity**. Customize your order by choosing the number of licenses you'd like to order.

3. Follow the checkout procedure to confirm your purchase.

### Privacy notices

[!INCLUDE[cc_privacy_msl_cookies](../includes/cc-privacy-market-insights-cookies.md)]  

[!INCLUDE[cc_privacy_msl_partners](../includes/cc-privacy-market-insights-partners.md)]  

[!INCLUDE[cc_privacy_mse_azure_event_hubs](../includes/cc-privacy-market-insights-azure-event-hubs.md)]  

### See Also

[Get started with Market Insights](get-started.md)   
[Assign permissions and user roles](assign-user-roles.md)   
[Integrate Market Insights with Dynamics 365](integrate-widgets-dynamics-365.md)   
[Connect Market Insights to other domains](connect-other-domains.md)
 