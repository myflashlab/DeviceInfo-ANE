# DeviceInfo ANE for Android+iOS
This ANE gives you many useful information about the current device OS the app is running in.

[find the latest **asdoc** for this ANE here.](http://myflashlab.github.io/asdoc/com/myflashlab/air/extensions/deviceInfo/package-detail.html)

# AIR Usage
For the complete AS3 code usage, see the [demo project here](https://github.com/myflashlab/DeviceInfo-ANE/blob/master/AIR/src/Main.as).

```actionscript
import com.myflashlab.air.extensions.deviceInfo.*;

// this ANE does not need initialization. 
// simply call it and receive the device information

var androidObj:Object = DeviceInfo.androidInfo();
trace(JSON.stringify(androidObj);

var iOSObj:Object = DeviceInfo.iosInfo();
trace(JSON.stringify(iOSObj);
```

# Air .xml manifest
```xml
<!--
Embedding the ANE:
-->
  <extensions>
	<extensionID>com.myflashlab.air.extensions.deviceInfo</extensionID>
	
	<!-- dependency ANEs https://github.com/myflashlab/common-dependencies-ANE -->
	<extensionID>com.myflashlab.air.extensions.dependency.overrideAir</extensionID>
  </extensions>
-->
```

# Requirements
* Android API 19+
* iOS SDK 8.0+
* AIR SDK 31.0+

# Commercial Version
https://www.myflashlabs.com/product/device-info-ane-adobe-air-native-extension/

[![DeviceInfo ANE](https://www.myflashlabs.com/wp-content/uploads/2019/04/product_adobe-air-ane-device-info.jpg)](https://www.myflashlabs.com/product/device-info-ane-adobe-air-native-extension/)

# Tutorials
[How to embed ANEs into **FlashBuilder**, **FlashCC** and **FlashDevelop**](https://www.youtube.com/watch?v=Oubsb_3F3ec&list=PL_mmSjScdnxnSDTMYb1iDX4LemhIJrt1O)  

# Premium Support #
[![Premium Support package](https://www.myflashlabs.com/wp-content/uploads/2016/06/professional-support.jpg)](https://www.myflashlabs.com/product/myflashlabs-support/)
If you are an [active MyFlashLabs club member](https://www.myflashlabs.com/product/myflashlabs-club-membership/), you will have access to our private and secure support ticket system for all our ANEs. Even if you are not a member, you can still receive premium help if you purchase the [premium support package](https://www.myflashlabs.com/product/myflashlabs-support/).