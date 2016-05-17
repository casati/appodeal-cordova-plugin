#Appodeal Cordova Plugin

Appodeal's supply-side platform is designed and built by veteran publishers, for publishers. Appodeal is not an ad network, it is a new approach to monetizing for publishers. 

The platform is a large auction house, accompanied by a mediation layer, that exposes a publisher's inventory to all available buyers on the market via relationships with every major ad network, RTB exchange, and DSP. Appodeal showcases publisher inventory to the advertiser, and offers the highest rate in real time. 

[Android integration guide](http://www.appodeal.com/sdk/documentation?framework=9&full=1&platform=1) </br>
[iOS integration guide](http://www.appodeal.com/sdk/documentation?framework=9&full=1&platform=2)


#Why this fork?

I've created this fork to make the Appodeal plugin capable to work with [AdMob Pro](https://github.com/floatinghotpot/cordova-admob-pro) or any other plugin that uses the Google Play Ads Services (com.google.android.gms:play-services-ads).
Basically the *android-support-v4.jar* has been removed and replaced with a reference to the *com.google.android.gms:play-services-ads:+* framework (see config.xml)
