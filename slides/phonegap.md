##PhoneGap vs Cordova

PhoneGap runs on top of Cordova and provides extra features. Both are free and for now both have similar compatibilities (webKit).

Here is an example Android Application using PhoneGap.

    package com.hybridframework.phonegapPlayer;

    import android.os.Bundle;
    import org.apache.cordova.CordovaActivity;

    public class CordovaApp extends CordovaActivity
    {
        @Override
        public void onCreate(Bundle savedInstanceState)
        {
            super.onCreate(savedInstanceState);
            super.init();
            // Set by <content src="index.html" /> in config.xml
            loadUrl(launchUrl);
        }
    }
