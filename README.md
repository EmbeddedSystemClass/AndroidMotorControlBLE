# Steps

First, I created a new basic android project

Then, I integrated BLE with these steps : 

## Integrating Bluetooth Low Energy (BLE)

I followed the official documentation of Android to do this.(https://developer.android.com/guide/topics/connectivity/bluetooth-le) 

### Adding the right permissions to the app manifest

<uses-permission android:name="android.permission.BLUETOOTH"/>
<uses-permission android:name="android.permission.BLUETOOTH_ADMIN"/>
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />