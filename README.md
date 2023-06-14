# flutter_onesignal_notification

A new Flutter project.

## Getting Started

##setting project main 

  OneSignal.shared.setLogLevel(OSLogLevel.verbose, OSLogLevel.none);
  OneSignal.shared.setAppId('8e74f112-d6ed-44d3-8b42-036eac4348d8');
  OneSignal.shared.promptUserForPushNotificationPermission().then((accepted){
    print('Accepted permission: $accepted');
  });

This project implementation one signal notification

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
