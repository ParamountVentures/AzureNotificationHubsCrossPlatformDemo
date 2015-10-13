# Azure Notifications Hubs Cross Platform Cordova Sample

This uses an Azure Notification Plugin at https://github.com/ParamountVentures/ventures-paramount-phonegap-plugin-notificationhubs which is based on a combination of https://github.com/sgrebnov/cordova-plugin-azure-notificationhub and https://github.com/phonegap/phonegap-plugin-push

The reason is that the MS notification hubs sample didn't do the toasts on Android and iOS which the official PushPlugin does (this however needed integtration with the Azure Notification Hubs), but the Windows version does do toasts, so that was left as it (for now).

#Windows
Follow the steps in https://github.com/ParamountVentures/AzureNotificationHubsDemo

*Important. Ensure that you replace the Identity element in the .appmanifest with your app identity and publisher id - this needs to be done manually for now in Cordova.

#iOS and Android
Follow the steps in https://github.com/phonegap/phonegap-plugin-push

##iOS Key Points##
- Follow the steps to set up iOS provisioning

    https://azure.microsoft.com/en-us/documentation/articles/notification-hubs-ios-get-started/
    
- Don’t try debugging push in simulator - device only for push notifications

- The latest version of the messaging SDK for iOS can be found at:

    https://github.com/Azure/azure-mobile-services/blob/master/CHANGELOG.ios.md#sdk-downloads