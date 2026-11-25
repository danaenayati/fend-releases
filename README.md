# Fend releases

Ready-to-install builds of Fend, an ad blocker and VPN client for Mac and Android. The source code is kept elsewhere; this repository only holds the release files that the apps check for updates.

Download the newest release from [Releases](../../releases/latest):

- **Mac:** `Fend-<version>.dmg`, or `Fend-OpenVPN-<version>.dmg` with OpenVPN support.
- **Android phone:** `Fend-<version>-arm64-v8a.apk` (most phones) or `Fend-<version>-universal.apk`.
- **Android TV:** `Fend-TV-<version>.apk`.

Once installed, Fend checks here for new versions by itself. Every Mac update is signed, and Fend refuses one whose signature doesn't match; Android only installs an update signed with the same key as the app already on the phone.
