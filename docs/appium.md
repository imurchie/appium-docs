---
id: index
title: Appium
redirect_from: "/index.html"
---

![Introducing Appium]({{ "/img/introducing-appium.gif" | prepend: site.baseurl }})

Appium is an open-source tool for automating native, mobile web, and hybrid applications on iOS mobile, Android mobile, and Windows desktop platforms.  **Native apps** are those written using the iOS, Android, or Windows SDKs.  **Mobile web apps** are web apps accessed using a mobile browser (Appium supports Safari on iOS and Chrome or the built-in 'Browser' app on Android).  **Hybrid apps** have a wrapper around a "webview" -- a native control that enables interaction with web content. Projects like [Phonegap](http://phonegap.com/), make it easy to build apps using web technologies that are then bundled into a native wrapper, creating a hybrid app.

Importantly, Appium is "cross-platform": it allows you to write tests against
multiple platforms (iOS, Android, Windows), using the same API. This enables code reuse between iOS, Android, and Windows test suites.

For specific information about what it means for Appium to "support" its
platforms, and automation modalities, please see the [platform support doc](docs/en/appium-setup/platform-support.md).
