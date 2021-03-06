---
title: Generate an app in PowerApps for the Common Data Service for Apps (quickstart)| Microsoft Docs
description: Automatically generate an app in PowerApps to manage data in the Common Data Service for Apps
services: powerapps
documentationcenter: na
author: AFTOwen
manager: kfile

ms.service: powerapps
ms.devlang: na
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 03/10/2018
ms.author: anneta

---
# Quickstart for generating an app in PowerApps for the Common Data Service for Apps

In this quickstart, you'll use PowerApps to automatically generate your first app based on a list of sample accounts in the [Common Data Service for Apps](../common-data-service/data-platform-intro.md). In this app, you can browse all accounts, show details of a single account, and create, update, or delete an account.

To follow this quickstart, you must switch to an [environment](working-with-environments.md) in which a database in the Common Data Service has been created and contains data. If no such environment exists and you have administrative privileges, you can [create an environment](../../administrator/environments-administration.md#create-an-environment) that meets this requirement.

If you don't have a license for PowerApps, you can [sign up for free](../signup-for-powerapps.md).

## Generate an app
1. Sign in to [PowerApps](https://web.powerapps.com).

	![PowerApps home page](./media/data-platform-create-app/sign-in.png)

1. Under **Make apps like these**, hover over **Start from data**, and then select **Make this app**.

	![Option to create an app](./media/data-platform-create-app/make-this-app.png)

1. Under **Start with your data**, select the arrow that points to the right.

	![Arrow icon](./media/data-platform-create-app/right-arrow.png)

1. Under **Connections**, select your connection to the Common Data Service.

1. Type **Accounts** in the search box (near the right edge), select **Accounts** under **Choose a table**, and then select **Connect**.

	![Select an entity](./media/data-platform-create-app/select-entity.png)

After a few minutes, your app opens to the browse screen, which shows a list of accounts. Near the top of the screen, a title bar shows icons for refreshing the list, sorting the list, and creating an account. Under the title bar, a search box provides the option to filter the list based on text that you type or paste. 

By default, the list shows an image, an email address, a city, and an ID for that account. But you can customize the list, which is called a gallery, to show other types of data.

![Browse screen](./media/data-platform-create-app/browse-screen.png)

## Save the app
You'll probably want to make more changes before you use this app or share it with others. As a best practice, save your work so far before you proceed.

1. Near the upper-left corner, click or tap the **File** tab.

1. In the **App settings** page, set the app name to **AppGen**, change the background color to deep red, and change the icon to a checkmark.

	![App settings page](./media/data-platform-create-app/app-settings.png)

1. Near the left edge, click or tap **Save**.

## Next steps
In this quickstart, you created an app to manage sample data about accounts in the Common Data Service for Apps. As a next step, customize the default browse screen to better suit your needs.

> [!div class="nextstepaction"]
> [Customize a default browse screen](customize-layout-sharepoint.md).
