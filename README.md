# HostBar releases

Update feed and builds of [HostBar](https://github.com/tiagoperesduarte/hostbar), a macOS menu bar app that watches, powers and prices my hosts.

Installed copies read `appcast.xml` through Sparkle and download the zip it points to in `releases/`. Everything here is written by the release pipeline; nothing is edited by hand.

To install by hand, download the latest zip in `releases/`, unzip it into `~/Applications` and, on the first launch, allow it in System Settings > Privacy & Security ("Open Anyway"): builds are signed ad-hoc, without an Apple Developer ID.
