# xCodeOutput
Running pod install...                                              9,9s
Running Xcode build...                                                  
Xcode build done.                                           187,0s
Failed to build iOS app
Error output from Xcode build:
↳
    ** BUILD FAILED **


Xcode's output:
↳
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/store_redirect-1.0.2/ios/Classes/StoreRedirectPlugin.m:27:48: warning: 'openURL:' is deprecated: first deprecated in iOS 10.0 [-Wdeprecated-declarations]
                [[UIApplication sharedApplication] openURL:[NSURL URLWithString:iTunesLink]];
                                                   ^~~~~~~
                                                   openURL:options:completionHandler:
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/store_redirect/store_redirect-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:123:1: note: 'openURL:' has been explicitly marked
    deprecated here
    - (BOOL)openURL:(NSURL*)url API_DEPRECATED_WITH_REPLACEMENT("openURL:options:completionHandler:", ios(2.0, 10.0)) NS_EXTENSION_UNAVAILABLE_IOS("");
    ^
    1 warning generated.
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/PhotoPermissionStrategy.m:39:13: warning: enumeration value 'PHAuthorizationStatusLimited' not handled
    in switch [-Wswitch]
        switch (authorizationStatus) {
                ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/PhotoPermissionStrategy.m:39:13: note: add missing switch cases
        switch (authorizationStatus) {
                ^
    1 warning generated.
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/PhonePermissionStrategy.m:41:35: warning: 'subscriberCellularProvider' is deprecated: first deprecated
    in iOS 12.0 [-Wdeprecated-declarations]
        CTCarrier *carrier = [netInfo subscriberCellularProvider];
                                      ^~~~~~~~~~~~~~~~~~~~~~~~~~
                                      serviceSubscriberCellularProviders
    In module 'CoreTelephony' imported from /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/PhonePermissionStrategy.m:8:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/CoreTelephony.framework/Headers/CTTelephonyNetworkInfo.h:110:50: note: property
    'subscriberCellularProvider' is declared deprecated here
    @property(readonly, retain, nullable) CTCarrier *subscriberCellularProvider API_DEPRECATED_WITH_REPLACEMENT("serviceSubscriberCellularProviders", ios(4.0, 12.0)) API_UNAVAILABLE(macos);
                                                     ^
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/CoreTelephony.framework/Headers/CTTelephonyNetworkInfo.h:110:50: note:
    'subscriberCellularProvider' has been explicitly marked deprecated here
    1 warning generated.
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/PermissionManager.m:69:59: warning: 'openURL:' is deprecated: first deprecated in iOS 10.0
    [-Wdeprecated-declarations]
            BOOL success = [[UIApplication sharedApplication] openURL:[NSURL URLWithString:UIApplicationOpenSettingsURLString]];
                                                              ^~~~~~~
                                                              openURL:options:completionHandler:
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:123:1: note: 'openURL:' has been explicitly marked
    deprecated here
    - (BOOL)openURL:(NSURL*)url API_DEPRECATED_WITH_REPLACEMENT("openURL:options:completionHandler:", ios(2.0, 10.0)) NS_EXTENSION_UNAVAILABLE_IOS("");
    ^
    1 warning generated.
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:42:7: warning: 'UIUserNotificationType' is deprecated: first deprecated
    in iOS 10.0 - Use UserNotifications Framework's UNAuthorizationOptions [-Wdeprecated-declarations]
          UIUserNotificationType notificationTypes = 0;
          ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:17:32: note: 'UIUserNotificationType' has
    been explicitly marked deprecated here
    typedef NS_OPTIONS(NSUInteger, UIUserNotificationType) {
                                   ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:43:28: warning: 'UIUserNotificationTypeSound' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNAuthorizationOptions [-Wdeprecated-declarations]
          notificationTypes |= UIUserNotificationTypeSound;
                               ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:17:32: note: 'UIUserNotificationType' has
    been explicitly marked deprecated here
    typedef NS_OPTIONS(NSUInteger, UIUserNotificationType) {
                                   ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:44:28: warning: 'UIUserNotificationTypeAlert' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNAuthorizationOptions [-Wdeprecated-declarations]
          notificationTypes |= UIUserNotificationTypeAlert;
                               ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:17:32: note: 'UIUserNotificationType' has
    been explicitly marked deprecated here
    typedef NS_OPTIONS(NSUInteger, UIUserNotificationType) {
                                   ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:45:28: warning: 'UIUserNotificationTypeBadge' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNAuthorizationOptions [-Wdeprecated-declarations]
          notificationTypes |= UIUserNotificationTypeBadge;
                               ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:17:32: note: 'UIUserNotificationType' has
    been explicitly marked deprecated here
    typedef NS_OPTIONS(NSUInteger, UIUserNotificationType) {
                                   ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:46:7: warning: 'UIUserNotificationSettings' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNNotificationSettings [-Wdeprecated-declarations]
          UIUserNotificationSettings *settings = [UIUserNotificationSettings settingsForTypes:notificationTypes categories:nil];
          ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:44:12: note: 'UIUserNotificationSettings' has
    been explicitly marked deprecated here
    @interface UIUserNotificationSettings : NSObject
               ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:46:74: warning: 'UIUserNotificationSettings' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNNotificationSettings [-Wdeprecated-declarations]
          UIUserNotificationSettings *settings = [UIUserNotificationSettings settingsForTypes:notificationTypes categories:nil];
                                                                             ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:44:12: note: 'UIUserNotificationSettings' has
    been explicitly marked deprecated here
    @interface UIUserNotificationSettings : NSObject
               ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:47:42: warning: 'registerUserNotificationSettings:' is deprecated:
    first deprecated in iOS 10.0 - Use UserNotifications Framework's -[UNUserNotificationCenter requestAuthorizationWithOptions:completionHandler:] and -[UNUserNotificationCenter setNotificationCategories:]
    [-Wdeprecated-declarations]
          [[UIApplication sharedApplication] registerUserNotificationSettings:settings];
                                             ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:250:1: note: 'registerUserNotificationSettings:' has been
    explicitly marked deprecated here
    - (void)registerUserNotificationSettings:(UIUserNotificationSettings *)notificationSettings API_DEPRECATED("Use UserNotifications Framework's -[UNUserNotificationCenter requestAuthorizationWithOptions:completionHandler:] and
    -[UNUserNotificationCenter setNotificationCategories:]", ios(8.0, 10.0)) API_UNAVAILABLE(tvos);
    ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:68:5: warning: 'UIUserNotificationSettings' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNNotificationSettings [-Wdeprecated-declarations]
        UIUserNotificationSettings * setting = [[UIApplication sharedApplication] currentUserNotificationSettings];
        ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:44:12: note: 'UIUserNotificationSettings' has
    been explicitly marked deprecated here
    @interface UIUserNotificationSettings : NSObject
               ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:68:79: warning: 'currentUserNotificationSettings' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's -[UNUserNotificationCenter getNotificationSettingsWithCompletionHandler:] and -[UNUserNotificationCenter getNotificationCategoriesWithCompletionHandler:]
    [-Wdeprecated-declarations]
        UIUserNotificationSettings * setting = [[UIApplication sharedApplication] currentUserNotificationSettings];
                                                                                  ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:253:70: note: property 'currentUserNotificationSettings'
    is declared deprecated here
    @property(nonatomic, readonly, nullable) UIUserNotificationSettings *currentUserNotificationSettings API_DEPRECATED("Use UserNotifications Framework's -[UNUserNotificationCenter getNotificationSettingsWithCompletionHandler:]
    and -[UNUserNotificationCenter getNotificationCategoriesWithCompletionHandler:]", ios(8.0, 10.0)) API_UNAVAILABLE(tvos);
                                                                         ^
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:253:70: note: 'currentUserNotificationSettings' has been
    explicitly marked deprecated here
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:69:26: warning: 'UIUserNotificationTypeNone' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNAuthorizationOptions [-Wdeprecated-declarations]
        if (setting.types == UIUserNotificationTypeNone) permissionStatus = PermissionStatusDenied;
                             ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:17:32: note: 'UIUserNotificationType' has
    been explicitly marked deprecated here
    typedef NS_OPTIONS(NSUInteger, UIUserNotificationType) {
                                   ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:71:5: warning: 'UIRemoteNotificationType' is deprecated: first
    deprecated in iOS 8.0 - Use UserNotifications Framework's UNAuthorizationOptions for user notifications and registerForRemoteNotifications for receiving remote notifications instead. [-Wdeprecated-declarations]
        UIRemoteNotificationType type = [[UIApplication sharedApplication] enabledRemoteNotificationTypes];
        ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:69:32: note: 'UIRemoteNotificationType' has been
    explicitly marked deprecated here
    typedef NS_OPTIONS(NSUInteger, UIRemoteNotificationType) {
                                   ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:71:72: warning: 'enabledRemoteNotificationTypes' is deprecated: first
    deprecated in iOS 8.0 - Use -[UIApplication isRegisteredForRemoteNotifications] and UserNotifications Framework's -[UNUserNotificationCenter getNotificationSettingsWithCompletionHandler:] to retrieve user-enabled remote
    notification and user notification settings [-Wdeprecated-declarations]
        UIRemoteNotificationType type = [[UIApplication sharedApplication] enabledRemoteNotificationTypes];
                                                                           ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIApplication.h:229:1: note: 'enabledRemoteNotificationTypes' has been
    explicitly marked deprecated here
    - (UIRemoteNotificationType)enabledRemoteNotificationTypes API_DEPRECATED("Use -[UIApplication isRegisteredForRemoteNotifications] and UserNotifications Framework's -[UNUserNotificationCenter
    getNotificationSettingsWithCompletionHandler:] to retrieve user-enabled remote notification and user notification settings", ios(3.0, 8.0)) API_UNAVAILABLE(tvos);
    ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/NotificationPermissionStrategy.m:72:17: warning: 'UIUserNotificationTypeNone' is deprecated: first
    deprecated in iOS 10.0 - Use UserNotifications Framework's UNAuthorizationOptions [-Wdeprecated-declarations]
        if (type == UIUserNotificationTypeNone) permissionStatus = PermissionStatusDenied;
                    ^
    In module 'UIKit' imported from /Users/apple/Desktop/Metro-Flutter/ios/Pods/Target Support Files/permission_handler/permission_handler-prefix.pch:2:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/UIKit.framework/Headers/UIUserNotificationSettings.h:17:32: note: 'UIUserNotificationType' has
    been explicitly marked deprecated here
    typedef NS_OPTIONS(NSUInteger, UIUserNotificationType) {
                                   ^
    13 warnings generated.
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.m:50:9: warning: 'ABAuthorizationStatus' is deprecated: first deprecated in
    iOS 9.0 - use CNAuthorizationStatus [-Wdeprecated-declarations]
            ABAuthorizationStatus status = ABAddressBookGetAuthorizationStatus();
            ^
    In module 'AddressBook' imported from /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.h:11:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/AddressBook.framework/Headers/ABAddressBook.h:44:26: note: 'ABAuthorizationStatus' has been
    explicitly marked deprecated here
    typedef CF_ENUM(CFIndex, ABAuthorizationStatus) {
                             ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.m:50:40: warning: 'ABAddressBookGetAuthorizationStatus' is deprecated: first
    deprecated in iOS 9.0 - use [CNContactStore authorizationStatusForEntityType:] [-Wdeprecated-declarations]
            ABAuthorizationStatus status = ABAddressBookGetAuthorizationStatus();
                                           ^
    In module 'AddressBook' imported from /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.h:11:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/AddressBook.framework/Headers/ABAddressBook.h:50:33: note: 'ABAddressBookGetAuthorizationStatus'
    has been explicitly marked deprecated here
    AB_EXTERN ABAuthorizationStatus ABAddressBookGetAuthorizationStatus(void) AB_DEPRECATED("use [CNContactStore authorizationStatusForEntityType:]");
                                    ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.m:53:18: warning: 'kABAuthorizationStatusNotDetermined' is deprecated: first
    deprecated in iOS 9.0 - use CNAuthorizationStatus [-Wdeprecated-declarations]
                case kABAuthorizationStatusNotDetermined:
                     ^
    In module 'AddressBook' imported from /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.h:11:
    /Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/Developer/SDKs/iPhoneOS14.0.sdk/System/Library/Frameworks/AddressBook.framework/Headers/ABAddressBook.h:44:26: note: 'ABAuthorizationStatus' has been
    explicitly marked deprecated here
    typedef CF_ENUM(CFIndex, ABAuthorizationStatus) {
                             ^
    /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.m:55:18: warning: 'kABAuthorizationStatusRestricted' is deprecated: first
    deprecated in iOS 9.0 - use CNAuthorizationStatus [-Wdeprecated-declarations]
                case kABAuthorizationStatusRestricted:
                     ^
    In module 'AddressBook' imported from /Users/apple/developer/flutter/.pub-cache/hosted/pub.dartlang.org/permission_handler-4.4.0+hotfix.4/ios/Classes/strategies/ContactPermissionStrategy.h:11:
