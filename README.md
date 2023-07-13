# Vanced+ MicroG

[![Github All Releases](https://img.shields.io/github/downloads/cuynu/VancedxMicroG/total.svg)](https://github.com/cuynu/VancedxMicroG/releases/latest/download/microg.apk) [![Github All Releases](https://img.shields.io/github/release/cuynu/VancedxMicroG.svg)](https://github.com/cuynu/VancedxMicroG/releases)

microG GmsCore is a FLOSS (Free/Libre Open Source Software) framework to allow applications designed for Google Play Services to run on systems, where Play Services is not available.

This fork tweaks MicroG to be usable by applications that require Google authentication such as YouTube Vanced.

## Warning!
Vanced+ microG probably not work in ReVanced/RVX in future as recent changes from ReVanced/RVX to use with they specific MicroG called ReVanced MicroG

## Notable changes

- No longer a system app
- Package name changed from `com.google.android.gms` to `com.mgoogle.android.gms` to support installation alongside the official MicroG
- Removed unnecessary features:
  - Ads
  - Analytics
  - Car
  - Droidguard
  - Exposure-Notifications
  - Feedback
  - Firebase
  - Games
  - Maps
  - Recovery
  - Registering app permissions
  - SafetyNet
  - Self-Check
  - Search
  - TapAndPay
  - Wallet
  - Wear-Api
- Removed all permissions, as none are required for Google authentication

## Credits

- Source Code for MicroG 0.2.25.224113 was provided by [@OxrxL](https://github.com/OxrxL)
- [@shadow578](https://github.com/shadow578)'s commit used to apply `SPOOFED_PACKAGE_SIGNATURE`
  
