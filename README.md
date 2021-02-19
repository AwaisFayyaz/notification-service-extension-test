# A demo project to diagnose an issue with notification service extension in iOS

This is a demo project to test the notification service extension in iOS. 

Sometimes, notification extension is not triggered when a push notification is received. 

I am trying to modify the title of a push notification before presenting it to the user. I have followed the official guidelines mentioned at 
https://developer.apple.com/documentation/usernotifications/modifying_content_in_newly_delivered_notifications

I have followed the recommended guidelines while implementing this service extension such as setting mutable-content:1 in payload of a push notification.
But due to some unknown reason, iOS does not fire notification service extension sometimes and my notifications title is not updated before being presented to the user.

This is occuring on iOS 14.4. on iOS 12, it is working fine

I have double checked that My Configuration for the service extension is correct. I am discussing this issue at apple dev forums There
https://developer.apple.com/forums/thread/67202?page=1#662863022

I also asked a question at stack overflow but could not find an answer
https://stackoverflow.com/questions/66259849/why-notification-service-extension-is-not-firing-on-ios-14

Hoping to find an answer to this question soon!
