## iosparanoid

Blocking iOS from connecting to APPLE unnecessarily.

## Installation

* Backup your host file at /etc/hosts
* Replace <Insert-Here> to you location server, you can get those number using Pi-Hole.
* Place hosts file at /etc/hosts

## Services blocked

* Location Service
* iCloud
* Calendar
* Spotlight
* Time sync
* iOS Updates check
* AirPort Utility

## Services Tested Working

* AppStore
* Apple Pay
* APNS (Push notification server)
* iMessage

## Resources

* https://www.richard-purves.com/2016/09/10/apple-services/
* https://github.com/l1k/osxparanoia
