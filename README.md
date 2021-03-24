# aframe WebVR - android by Eclipse


Tested a-frame v 0.7.x to 0.9.x on android App 



[![Watch the video](https://img.youtube.com/vi/vez5Xxkyga4/0.jpg)](https://youtu.be/vez5Xxkyga4)


##Webview android (Eclipse)

https://download.01.org/crosswalk/releases/crosswalk/android/beta/23.53.589.4/arm/


## aframevr
https://github.com/aframevr/aframe


## MainActivity.xml

    <?xml version="1.0" encoding="utf-8"?>
    <LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical" >
    
    <org.xwalk.core.XWalkView
         android:id="@+id/xwalkWebViewvr"
         android:orientation="vertical"
         android:layout_width="fill_parent"
         android:layout_height="fill_parent"
         android:background="#000000"
         />
    </LinearLayout>


## MainActivity.xml

	   XWalkView xWalkWebView=(XWalkView)findViewById(R.id.xwalkWebViewvr);
	 	xWalkWebView.clearCache(true);
		xWalkWebView.load("file:///android_asset/index.html", null);
		// turn on debugging
		XWalkPreferences.setValue(XWalkPreferences.REMOTE_DEBUGGING, true);


## Can be start web Augmented reality
Https://Webxr.edafait.com

## Good Company hosting and low price VPN 
https://shorturl.edafait.com/?fZVHLor 

## YouTube Channel Wonder developer To Subscriber 
https://shorturl.edafait.com/?zuS4kvW
