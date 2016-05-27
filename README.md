# GA-SDK-UNITY
GameAnalytics Unity SDK.

Documentation is in the [wiki](https://github.com/GameAnalytics/GA-SDK-UNITY/wiki).


> :information_source:<br>
> The Unity SDK include support for **iOS**, **tvOS** and **Android** platforms.<br>



Changelog
---------
**3.3.3**
* fixed bug related to network changes for Android API level 23 and above (android)

**3.3.2**
* Added max cap (20) for custom dimensions, resource currencies and resource item types
* tvOS library Unity asset importer bug fix

**3.3.1**
* Google Play Services libraries updated to version 8.4.0 (android)

**3.3.0**
* feature for using a custom user id
* fix testflight issue with user id generation (ios)

**3.2.3**
* fixed disappearing GameAnalytics prefab bug (happening since Unity 5.3.0)

**3.2.2**
* postprocess script fixed when ios library is not installed
* Unity 4.7.x support fix

**3.2.1**
* error events fixed (android)

**3.2.0**
* added support for tvOS (tvos)

**3.1.1**
* fixed inclusion of faulty library in 3.1.0 (ios)

**3.1.0**
* altered jailbreak check causing ios9 warning (ios)
* library / framework now compiled with bitcode (ios)
* alternative non-bitcode library (Xcode6) added (ios)
* restructuring to prepare for tvOS (ios)
* fix issue for offline initialization (android)

**3.0.0b**
* new java-only implementation (android)
* install size reduced (android)

**2.4.3**
* Google Play Services libraries updated to version 8.3.0 (android)

**2.4.2**
* Postprocessor script for XCode fixed for Unity 4.6.x (ios)

**2.4.1**
* android.permission.WRITE_EXTERNAL_STORAGE not needed anymore (android)

**2.4.0**
* fixed tracking bug with ad opt out enabled (android)

**2.3.2**
* no network connection bug fix (android)

**2.3.1**
* fix related to connection changes (android)


**2.3.0**
* 'Receiver not registered' bug fix (android)

**2.2.0**
* improved code structure (android)
* built library with Xcode7 (iOS 9.0)
* fixed missing links in setup guide
* minor tweaks

**2.1.4**
* increased allowed character count to 64 for many parameters (android)

**2.1.3**
* fix for session length (android)

**2.1.2**
* fixed enable/disable submit errors in unity settings
* improved session handling (android)
* minor bug fixes (android)

**2.1.1**
* fixed rare editor bug causing settings object replication
* minor bug fixes (android)

**2.1.0**
* Android support added
* Google Play purchase validation
* support for individual game keys for each supported platform

**2.0.4**
* fixed an issue with going-to-background on iOS 6
* fixed submit of birthyear value

**2.0.3**
* fixed an iOS 6 issue
* added a post process build script for setting up Xcode (Unity 5 only)

**2.0.2**
* fix for PlayMaker events
* fix for Critical FPS events

**2.0.1**
* fix for business event receipt rejection in some cases
* tweaked local db size trimming

**2.0.0**
* redesigned Unity SDK 
* initially with **only iOS** support
* progression event
* business event validation
* resource event
* custom dimensions
