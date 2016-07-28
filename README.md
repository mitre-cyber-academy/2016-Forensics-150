# README #

The Generated APK is all you need to give them.

##Methods of Hacking##
* Figure out Hashes of username/password and put in Username: iamahacker Password: iamnotascriptkiddy
* Send Intent of specific string to cause Broadcast receiver to print flag
* Figure out how the app is taking the decimal ASCII converting it to HEX and then to string and formulate the flag

##Installation/start-up##
1. APK emulator (Android Studio works)
2. Download sdk with API v15
3. Download apktools

     brew install apktool

4. download jd gui installer 

##Solving##
 1. Once everything is loaded you should be able to unzip the Authenticator.apk file. (Recommended: copy Authenticator.apk to a temp file)

     unzip Authenticator.apk


##Another way to solve:
Go into Authenticator/res/values and find string.
   * The strings are encrypted but can be decrypted and then used when the app is launched.


###KEY
* The Key is “e1192d27265d0754f9482fbbe0b8bb165c4f2144”.