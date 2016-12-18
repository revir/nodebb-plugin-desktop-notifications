# NodeBB Desktop Notifications

This plugin is forlked from [nodebb-plugin-desktop-notifications](https://github.com/psychobunny/nodebb-plugin-desktop-notifications), I fixed two problems of the original plugin:

1. fix site title expression in alert bar tpl;
2. add zh_CN and en_US language support.

This NodeBB plugin uses the HTML5 Notifications API to display desktop alerts upon new incoming notifications.

If you have a forum logo set it will use that as the notification icon. Clicking on the notification will take you the appropriate thread.


When the user clicks on the notification icon in the menu, a permission dialog is launched to activate desktop notifications.

Also supports push notifications on mobile!

## Screenshot

![desktop-notifications](http://i.imgur.com/UnBFk3z.png)
![notifications_mobile.png](http://i.imgur.com/JbfEBTJ.png)

## Installation

    npm install nodebb-plugin-desktop-notifications-v2mm


## Credit

Psychobunny for [nodebb-plugin-desktop-notifications](https://github.com/psychobunny/nodebb-plugin-desktop-notifications).


## Browser support

* Chrome
* Safari
* Firefox
* Firefox OS (v1.2+)
* Firefox Mobile (Android)
