Smart AdServer - Google Ads Mobile SDK Adapter for Android
==============================================

This repository is __deprecated__ and no longer supported. Please consider using [smart-gma-mediation-adapter-android](https://github.com/smartadserver/smart-gma-mediation-adapter-android) instead.

Introduction
------------
The _Smart AdServer Android SDK_ can be used through _Google Ads Mobile SDK (DFP)_ using the adapter provided in this repository for both _SASBannerView_ and _SASInterstitialView_.
We'll be following the instructions provided by DFP [here](https://support.google.com/dfp_premium/answer/6238717?hl=en).

Setup
-----

To start using the _Smart AdServer Android SDK_ through DFP, simply add all the classes included in this repository in your project (**the project needs to include a correctly installed _Smart AdServer Android SDK_**).

You can declare _SDK Mediation Creatives_ in the _DFP_ interface. Refer to the article [Add a new mobile creative](https://support.google.com/dfp_premium/answer/1209767) in Google DFP documentation for detailed instructions *Note: make sure to use "SDK Mediation" as the creative type.

To setup the _Custom Event_ (under _Ad networks_), you need to fill:

* the _Parameter_ field: set your _Smart AdServer_ IDs using slash separator `[siteID]/[pageID]/[formatID]`
* the _Class Name_ field: set `com.smartadserver.android.library.mediation.SASCustomEventBanner` for banners and `com.smartadserver.android.library.mediation.SASCustomEventInterstitial` for interstitials
* 


More infos
----------
You can find more informations about the _Smart AdServer Android SDK_ and the _Google Ads Mobile Mediation Adapters_ in the official documentation:
http://help.smartadserver.com/en/
