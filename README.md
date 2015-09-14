# Azure Notifications Hubs Cross Platform Cordova Sample

This is based on a combination of https://github.com/sgrebnov/cordova-plugin-azure-notificationhub and https://github.com/phonegap/phonegap-plugin-push

The reason is that the MS notification hubs sample didn't do the toasts on Android and iOS which the official PushPlugin does (this however needed integtration with the Azure Notification Hubs), but the Windows version does do toasts, so that was left as it (for now).

#Windows
Follow the steps in https://github.com/ParamountVentures/AzureNotificationHubsDemo

*Important. Ensure that you replace the Identity element in the .appmanifest with your app identity and publisher id - this needs to be done manually for now in Cordova.

#iOS and Android
Follow the steps in https://github.com/phonegap/phonegap-plugin-push
