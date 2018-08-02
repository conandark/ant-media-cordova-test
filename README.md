# ant-media-cordova-test

make sure to install android studio, then in the project directory:
1. npm install -g cordova
2. cordova platform add android
3. edit www/index.html and replace ANTSERVER string with the ant-media server host name.
4. connect your phone with developer mode on and usb debegging turned on.
5. run "cordova run android --list"
6. start app: "cordova run android --debug --target=YOUR_DEVICE_ID" (replace YOUR_DEVICE_ID with the device id from the step #4)
