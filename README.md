# Android12BluetoothDemo

Based on this project: https://github.com/melvyniandrag/Android-Simple-Bluetooth-Example

But had to update a some code and configurations to make it work for Android 12.

Tested and running fine on 
* Galaxy SM-T380 running Android 9. Correctly requests LOCATION permissions for bluetooth.
* Pixel 4a running Android 12. Correctly uses new BLUETOOTH permissions for bluetooth, and not the old LOCATION permissions.

Note: As of this first commit I am not requesting the bluetooth permissions. You need to go into app settings and grant them manually. TODO.
