# Apple-SwiftPackage-KochavaNetworking-XCFramework

[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FKochava%2FApple-SwiftPackage-KochavaNetworking-XCFramework%2Fbadge%3Ftype%3Dplatforms)](https://swiftpackageindex.com/Kochava/Apple-SwiftPackage-KochavaNetworking-XCFramework)
[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fswiftpackageindex.com%2Fapi%2Fpackages%2FKochava%2FApple-SwiftPackage-KochavaNetworking-XCFramework%2Fbadge%3Ftype%3Dswift-versions)](https://swiftpackageindex.com/Kochava/Apple-SwiftPackage-KochavaNetworking-XCFramework)
[![CodeFactor](https://www.codefactor.io/repository/github/Kochava/Apple-Swiftpackage-KochavaNetworking/badge)](https://www.codefactor.io/repository/github/Kochava/Apple-SwiftPackage-KochavaNetworking)
[![Releases](https://img.shields.io/github/v/release/kochava/Apple-SwiftPackage-KochavaNetworking-XCFramework?include_prereleases&sort=semver)](https://github.com/Kochava/Apple-SwiftPackage-KochavaNetworking-XCFramework/releases)
[![Documentation](https://img.shields.io/badge/Documentation-Visit-202020?style=flat)](https://kochava.github.io/Apple-SwiftPackage-KochavaNetworking/documentation/kochavanetworking)

## KochavaNetworking

The KochavaNetworking framework is an SDK providing advanced networking with runtime dynamic command and control.  For the Apple platform this includes support for iOS, macCatalyst, macOS, tvOS, visionOS, and watchOS.

<img src="https://storage.googleapis.com/kochava-web/2016/07/Kochava-horizontal-black-800x154.png" width="500" />

## Overview

Born in the highly sensitive area of advertising measurement and tracking, Kochava developed the world's most advanced networking framework:  **KochavaNetworking, with Dynamic Runtime Command and Control**.  

At its foundation this includes the ability to adapt network transactions for user privacy, consent, and tracking transparency.  This starts with the conditional on-device ability to redact transactions or elements within the payloads of transactions.  Transactions are defined declaratively, rather than as logic expressed in code, enabling all of their parameters to be configured at runtime.  This includes the ability to change defaults and to specify overrides.  The contents of a payload can be amended or expanded, the structure of a payload can be refactored, and the URL can be redirected or given new query parameters.  Also behavior such as prerequisites, rate, retry waterfall, and persistence can be adjusted.  New network transactions (along with certain other previously coded tasks) can also be described at the server with parameters and then instructed to be executed on-device.

All of this can all be done at runtime through the use of integrated dynamic runtime configuration, which means that these improvements can be applied to versions of applications after they have been deployed— retroactively.  This enables server APIs to be continuously modernized, and legacy software to be adapted on-device without a software update— in real time.  We believe it is the world's most advanced networking framework.

*Runtime Dynamic Command and Control* is currently an undocumented feature which is integrated and leveraged within various Kochava products.  If you are interested in using this feature for your own projects, please let us know by reaching out to your client success manager.  We are currently collecting feedback.

## Background

In 2019, with version 3.1.0, this framework had been initially closed-source and distributed under the generic name **KochavaCore**, where it served as a foundational module for the Kochava Measurement SDK.

In 2024, with version 8.0.0, this framework's name was clarified **KochavaNetworking** and open-sourced with the intention of positioning it for wider use.  We welcome you to see how you may use it for your own projects!  If you are already using Kochava's Measurement SDK (for the Apple platform) then it is already installed in your application and ready for your personal use.  It is available as Swift Package in two forms— the first with an xcframework pre-compiled for performance, and a second alternatively with source code.

## Built on

* Xcode 15.3

## Platforms

* iOS 13.0
* macCatalyst 13.0
* macOS 10.15
* tvOS 13.0
* visionOS 1.0
* watchOS 7.0

## Dependencies

* None

## Integration

KochavaNetworking is a Swift package.  To install it, simply add this package as a dependency.

In Xcode, see File > Swift Packages > Add Package Dependency ... > and enter the URL for this package repository.

[Kochava Apple SDK Integration](https://support.kochava.com/sdk-integration/ios-sdk-integration/)

## Documentation

KochavaNetworking's Swift-DocC documentation is [available here](https://kochava.github.io/Apple-SwiftPackage-KochavaNetworking/documentation/kochavanetworking).

## Author

Kochava, support@kochava.com

## License

Apple-SwiftPackage-KochavaNetworking-XCFramework is available under the [Kochava Terms of Service](https://www.kochava.com/terms-of-service/).
