# AndroidGeocoderLocation
Position and print with Geocoder NOTE: you need to be outside or you will think that you are getting a blank value and an error

Module:build.gradle 
implementation 'com.google.android.gms:play-services-location:17.0.0'
 
 
 Manifest.xml 
     <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
    <uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
    <uses-permission android:name="android.permission.ACCESS_BACKGROUND_LOCATION" />
    
if you send data from app to db you add <uses-permission android:name="android.permission.INTERNET"/> on your manifest file

