---
title: How to delete a group using the Azure AD portal | Microsoft Docs
description: Learn how to delete a group using the Azure Active Directory portal.
services: active-directory
author: eross-msft
manager: mtillman

ms.service: active-directory
ms.workload: identity
ms.component: fundamentals
ms.topic: conceptual
ms.date: 08/29/2018
ms.author: lizross
ms.reviewer: krbain
ms.custom: it-pro                         
---

# How to: Delete a group using the Azure Active Directory portal
You can delete a group for any number of reasons, but typically it will be because you:

- Incorrectly set the **Group type** to the wrong option

- Created the wrong or a duplicate group by mistake 

- No longer need the group

## To delete a group
1. Sign in to the [Azure AD portal](https://portal.azure.com) using a Global administrator account for the directory.

2. Select **Azure Active Directory**, and then select **Groups**.

3. From the **Groups - All groups** blade, search for and select the group you want to delete. For these steps, we'll use **MDM policy - East**.

    ![Groups-All groups blade, group name highlighted](media/active-directory-groups-delete-group/group-all-groups-screen.png)

4. On the **MDM policy - East Overview** blade, and then select **Delete**.

    The group is deleted from your Azure Active Directory tenant.

    ![MDM policy - East Overview blade, delete option highlighted](media/active-directory-groups-delete-group/group-overview-blade.png)

## Next steps

- If you delete a group by mistake, you can create it again. For more information, see [How to create a basic group and add members](active-directory-groups-create-azure-portal.md).
- If you delete an Office 365 group by mistake, you might be able to restore it. For more information, see [Restore a deleted Office 365 group](../users-groups-roles/groups-restore-deleted.md).
