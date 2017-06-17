# Back-to-the-future
apply plugin: 'com.android.application'
android {
compileSdkVersion 25
buildToolsVersion "25.0.3"
}
signingConfigs {
create("release") {
storeFile = file("leetdev_android.keystore")
storePassword = "dsgjhieji;jhb"
KeyAlias = "appsKey"
KeyPassword = "Flag{YouCanChangeTheHistory}"
