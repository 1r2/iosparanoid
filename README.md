# iosparanoid

Hosts file for blocking iOS unnecessarily connections to Apple.

## Installation

* Backup your host file at `/etc/hosts`.
* Replace `<Insert-Here>` to you location server, you can get those values using Pi-Hole or similar.
* Place hosts file at `/etc/hosts`.

## Services Blocked

* Location Service
* iCloud
* Calendar
* Spotlight
* Time Sync
* iOS Updates check
* AirPort Utility

## Services Tested Working

* AppStore
* Apple Pay
* APNS (Apple Push Notification server)
* Mail/Notes App
* iMessage
* Facetime Audio
* Sideloading Apps with Cydia Impactor

## Additionally Blocking some Ads/Tracking servers

* Google Ads
* Amazon Ads
* Crashlytics
* Appsflyer
* Flurry
* Combined with UHB 1.3.0 by Thireus

## References & Credits

* https://www.richard-purves.com/2016/09/10/apple-services/
* https://github.com/l1k/osxparanoia
