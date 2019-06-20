---
title: "Change the external sharing setting for a site"
ms.reviewer: 
ms.author: mikeplum
author: MikePlumleyMSFT
manager: pamgreen
audience: Admin
ms.topic: article
ms.service: sharepoint-online
localization_priority: Priority
ms.collection:  
- Strat_OD_share
- M365-collaboration
search.appverid:
- SPO160
- MET150
ms.assetid: 6288296a-b6b7-4ea4-b4ed-c297bf833e30
description: "Learn how to change the external sharing setting for a site."
---

# Turn external sharing on or off for a site

You must be a global or SharePoint admin in Office 365 to change the external sharing setting for a site (previously called a "site collection"). Site owners are not allowed to change this setting.
  
Note that this procedure applies to classic sites, communication sites, and new team sites. To learn how to change the external sharing setting for a user's OneDrive, see [Change the external sharing setting for a user's OneDrive](/onedrive/user-external-sharing-settings). For info about changing your organization-level settings, see [Turn external sharing on or off for SharePoint Online](turn-external-sharing-on-or-off.md).
  
1. Sign in to https://admin.microsoft.com as a global or SharePoint admin. (If you see a message that you don't have permission to access the page, you don't have Office 365 administrator permissions in your organization.)
    
    > [!NOTE]
    > If you have Office 365 Germany, sign in at https://portal.office.de. If you have Office 365 operated by 21Vianet (China), sign in at https://login.partner.microsoftonline.cn/. Then select the Admin tile to open the admin center.  
    
2. In the left pane, under **Admin centers**, select **SharePoint**. (You might need to select **Show all** to see the list of admin centers.) 

3. If the classic SharePoint admin center appears, select **Try it now** to open the new SharePoint admin center. 
    
4. In the left pane of the new SharePoint admin center, under **Sites** select **Active sites**.
    
5. Select the site, and then select **Sharing**.

    ![Changing the external sharing setting for a site](media/external-sharing-site.png)
     
6. Select an external sharing option (see the following table), and select **Save**.
    
### Which option to select...

|**Select this option:**|**If you want to:**|
|:-----|:-----|
|Anyone  <br/> | Allow site owners and others with full control permission to share the site with people who authenticate. Allow site users to decide when sharing files and folders to require authentication or allow people to access the item anonymously. Anyone links to files and folders can be freely forwarded. <br/> |
|New and existing guests  <br/> | Allow site owners and others with full control permission to share the site with people outside the organization. These people will need to sign in and will be added to the directory. Allow site users to share files and folders with people who aren't in the organization's directory. <br/> |
|Existing guests  <br/> |Allow sharing with only people already in your directory. These users may exist in your directory because they previously accepted sharing invitations or because they were [manually added](/azure/active-directory/b2b/b2b-quickstart-add-guest-users-portal). (You can tell an external user because they have **#EXT#** in their user name.)  <br/> |
|Only people in your organization  <br/> |Prevent all site users from sharing any site content externally. (This is the default setting for new classic sites.)  <br/> |


The settings available are dependent on your organization-level setting. If you enable external sharing for a site and it is later turned off for your organization, external sharing will become unavailable at the site level and any shared links will stop working. If it is turned back on for the organization, the site sharing setting will return to what it was before and the shared links will resume working.


> [!NOTE]
> You might have site content shared with an Office 365 group that has guest members, and the group settings prevent guest members from accessing group resources. In this case, even if you turn on external sharing for the site, guests of the group may not be able to access site content. To enable or disable Office 365 Group guest member access, see [Manage guest access in Office 365 Groups](/office365/admin/create-groups/manage-guest-access-in-groups).
  
## See also

[Stop sharing files or folders or change permissions](https://support.office.com/article/0a36470f-d7fe-40a0-bd74-0ac6c1e13323)