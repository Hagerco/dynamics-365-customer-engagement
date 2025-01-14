---
title: New UX for the mobile app (preview)
description: Learn about the redesigned user experience of the Dynamics 365 Field Service mobile app for managing bookings and work orders.
ms.date: 07/30/2023
ms.topic: overview
ms.subservice: field-service-mobile
author: andrea-orimoto
ms.author: andreo
---

# New UX for the mobile app (preview)

[!INCLUDE [public-preview-banner](../includes/public-preview-banner.md)]

[!INCLUDE [public-preview-note](../includes/public-preview-note.md)]

## Preview availability

This article contains information about the new user experience features in the Dynamics 365 Field Service mobile app. The improved UX aims to help service technicians swiftly access all the information they need on the go. This modern user experience supports familiar mobile navigation, gestures, and controls to manage work orders, tasks, services, and products.

Technicians save valuable time for daily work by quickly updating the status of a booking or accessing driving directions to a customer site. They can easily select, change, or complete work order details and also add notes with multiple images.

Detailed information for the immediate task is now readily available with embedded Dynamics 365 Guides. [Embedded guides in the Field Service mobile app](/dynamics365/mixed-reality/guides/admin-connect-field-service-mobile) provide technicians with step-by-step guided instructions, pictures, and videos that provide more details.

> [!VIDEO https://www.microsoft.com/en-us/videoplayer/embed/RW18Uzz]

## Preview content in the documentation

Once [an administrator enables](#enable-the-preview-features) the preview features, they're available directly in the existing Field Service mobile app. Technicians don't need to download a new app and organizations don't need to perform any migration. However, make sure that the mobile app and the Field Service solution are updated to the latest version.

> [!NOTE]
> For the preview of the new UX on mobile, the minimum Field Service version required is [8.8.95.25](version-history.md#889525).
> The minimum app version required is 13.23072.18 on iOS and 3.23072.18 on Android.

To learn more about these new features, review documentation articles and find content for preview features alongside the current content in dedicated tabs.

Here's a list of documents that contain specific preview content:

- [Download the mobile app and get started](download-get-started-mobile-app.md)
- [Complete work orders on the mobile app](get-work-done-mobile-app.md)
- [Access related apps form the Field Service mobile app](access-related-apps-mobile-app.md)
- [Embedded Guides in Field Service (preview)](access-related-apps-mobile-app.md)

## Enable the preview features

To enable the preview features for your organization, sign in as a **Field Service Administrator** to Dynamics 365 in a web browser. Select the **Field Service Mobile** app module from the list of all installed apps in your organizations.

In the mobile app, open the **Settings** area. Set the toggle to enable or disable the preview features for all users within the organization.

## Limitations of preview features

The preview features currently have the following limitations:

- Offline mode isn't supported. Users enabled for offline don't see the new features and see the existing Unified Interface experiences. To properly experience the new preview features, disable the offline profile.
- In preview, the new UX is currently not customizable. [Field Service Mobile app module customizations](field-service-customizations.md) aren't supported and don't work in the new UX. However, the customized model-driven app experiences (such as custom forms and business logic) continue to be accessible through an icon on the top right of the new UX, allowing users to switch back and forth.
- The new preview features respect the mobile device language settings, while the current app respects the language settings in the user profile. You might see a mixed language experience if the two settings are out of sync.

## Preview Support

During the preview period, there's limited support for this feature and we don't recommend it for production usage. If you run into issues with this preview, select **Send feedback** in the left navigation menu of the mobile app to send an email to our team with logs attached to it.

## Next steps

- [Install and set up the mobile app](mobile-power-app-get-started.md)

[!INCLUDE[footer-include](../includes/footer-banner.md)]
