# Apple-SwiftPackage-KochavaNetworking-XCFramework

[![Releases](https://img.shields.io/github/v/release/kochava/Apple-SwiftPackage-KochavaNetworking-XCFramework?include_prereleases&sort=semver)](https://github.com/Kochava/Apple-SwiftPackage-KochavaNetworking-XCFramework/releases)

## KochavaNetworking

The KochavaNetworking framework is an SDK providing advanced networking with runtime dynamic command and control.  For the Apple platform this includes support for iOS, macCatalyst, macOS, tvOS, visionOS, and watchOS.

<img src="https://storage.googleapis.com/kochava-web/2016/07/Kochava-horizontal-black-800x154.png" width="500" />

## Overview

Born in the highly sensitive area of advertising measurement and tracking, Kochava developed the world's most advanced networking framework:  **KochavaNetworking, with Dynamic Runtime Command and Control**.  

At its foundation this includes the ability to adapt network transactions for user privacy, consent, and tracking transparency.  This starts with the ability to redact transactions or elements within the payloads of transactions.  Moving forward transactions are defined declaratively rather than as logic expressed in code, enabling all of their parameters to be configured at runtime.  This includes the ability to change defaults and to specify overrides.  The contents of a payload can be altered or amended, the structure of a payload can be changed, and the URL can be redirected or given new query parameters.  Also behavior such as prerequisites, rate, retry waterfall, and persistence can be altered.  New network transactions (as well as certain other previously coded tasks) can also be described at the server and then instructed to be executed on-device.

This can all be done at runtime through the use of integrated dynamic runtime configuration, which means that this support can be applied to versions of applications after they have been deployed.  This enables server APIs to be modernized— and legacy software to be adapted on-device without a software update— in real time.  We believe it is the world's most advanced networking framework.

In 2019, with version 3.1.0, this framework had been initially closed-source and distributed under the generic name **KochavaCore**, where it served as a foundational module for the Kochava Measurement SDK.

In 2024, with version 8.0.0, this framework's name was clarified **KochavaNetworking** and open-sourced with the intention of positioning it for wider use.  We welcome you to see how you may use it for your own projects!  If you are already using Kochava's Measurement SDK (for the Apple platform) then it is already installed in your application and ready for your personal use.  It is available as Swift Package in two forms— the first with an xcframework pre-compiled for performance, and a second alternatively with source code.

*Runtime Dynamic Command and Control* is currently an undocumented feature which is integrated and used within various Kochava products.  If you are interested in using this feature for your own projects, please let us know by reaching out to your client success manager.  We are currently collecting feedback.

## Built on

* Xcode 15.2

## Platforms

* iOS 13.0
* macCatalyst 13.0
* macOS 10.15
* tvOS 13.0
* visionOS 1.0
* watchOS 6.0

## Dependencies

* None

## Integration

KochavaNetworking is a Swift package.  To install it, simply add this package as a dependency.

In Xcode, see File > Swift Packages > Add Package Dependency ... > and enter the URL for this package repository.

[Kochava Apple SDK Integration](https://support.kochava.com/sdk-integration/ios-sdk-integration/)

## Author

Kochava, support@kochava.com

## License

Apple-SwiftPackage-KochavaNetworking-XCFramework is available under the [Kochava Terms of Service](https://www.kochava.com/terms-of-service/).
