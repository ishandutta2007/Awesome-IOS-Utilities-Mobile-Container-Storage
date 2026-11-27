# Awesome-IOS-Utilities-Mobile-Container-Storage

# Awesome-IOS-Utilities-Mobile-Container-Storage



Top IOS Utilities Mobile Container Storage (Opensource) 🌟 Star if you like it! 🌟



A curated list of top iOS utilities, mobile container storage solutions, IPA sideloading tools, device inspection protocols, OTA app distribution servers, and iOS CI/CD infrastructure—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.



---



## Table of Contents



- [SaaS/Hosted Platforms](#saashosted-platforms)

- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)

  - [Mobile Container Storage & Local iOS Utilities](#mobile-container-storage--local-ios-utilities)

  - [Open-Source IPA Sideloading & App Signing Tools](#open-source-ipa-sideloading--app-signing-tools)

  - [iOS Device Management, Protocols & Debugging CLI](#ios-device-management-protocols--debugging-cli)

  - [Self-Hosted OTA App Distribution & Beta Testing Platforms](#self-hosted-ota-app-distribution--beta-testing-platforms)

  - [Self-Hosted Mobile CI/CD, Virtualization & Build Infrastructure](#self-hosted-mobile-cicd-virtualization--build-infrastructure)

- [Contributing](#contributing)



---



## SaaS/Hosted Platforms



Commercial, cloud-hosted iOS build pipelines, proprietary sideloading services, managed beta distribution platforms, and hosted Apple silicon CI/CD.



* **[Xcode Cloud](https://apple.com)** - Apple's official continuous integration and delivery service built directly into Xcode for building, testing, and distributing iOS apps.

* **[TestFlight](https://apple.com)** - Apple's hosted beta testing platform enabling developers to distribute pre-release iOS builds and collect tester feedback.

* **[Sideloadly](https://sideloadly.io)** - Proprietary desktop utility for Windows and macOS allowing users to sign and install IPA files onto iOS devices via Apple IDs.

* **[Firebase App Distribution](https://google.com)** - Google's hosted pre-release app distribution service for rapidly deploying iOS and Android builds to trusted testers.

* **[Diawi](https://diawi.com)** - Cloud-based web service for developers to upload IPA/APK files and generate instant over-the-air (OTA) installation links.

* **[DeployGate](https://deploygate.com)** - Managed cloud platform for continuous mobile app distribution, live device log streaming, and team beta testing.

* **[Bitrise](https://bitrise.io)** - Mobile-first cloud CI/CD platform featuring hosted macOS M-series build machines and automated App Store/TestFlight workflows.

* **[Visual Studio App Center (Legacy / Hosted)](https://appcenter.ms)** - Microsoft's cloud lifecycle management suite for mobile build automation, analytics, and beta distribution.

* **[AltStore / AltServer (Hosted Ecosystem & PAL)](https://altstore.io)** - Commercial/open-core alternative app store and sideloading ecosystem offering AltStore PAL in the EU and desktop companion syncing.

* **[Cydia Impactor / Hosted Signing Services](http://cydiaimpactor.com)** - Classic proprietary GUI tool and third-party cloud signing services for installing unsigned IPA packages on iOS.



---



## Open-Source Equivalents & Tools



Free and open-source software (FOSS) iOS container utilities, open-source IPA signers, libimobiledevice protocols, self-hosted OTA servers, and macOS/iOS CI runners.



### Mobile Container Storage & Local iOS Utilities



* **[Crate iOS (oneamendez)](https://github.com)** - Open-source iOS utility and mobile container storage application designed for organized local file and asset management on iOS.

* **[AltStore (Open-Source Core)](https://github.com)** - Open-source alternative app store for non-jailbroken iOS devices utilizing standard Apple developer certificates and on-device re-signing.

* **[SideStore](https://github.com)** - Community-driven, untethered open-source fork of AltStore enabling on-device IPA signing and refreshing using only a local VPN tunnel.

* **[TrollStore](https://github.com)** - Open-source jailed perma-signed IPA installer exploiting CoreTrust bugs on compatible iOS versions for permanent system-level app installation.

* **[LiveContainer](https://github.com)** - Open-source app launcher and container runtime allowing users to run unsigned iOS apps inside a single signed container without exceeding the 3-app sideload limit.

* **[UTM (iOS Virtualization)](https://github.com)** - Full-featured open-source system emulator and virtual machine host for iOS and macOS powered by QEMU.



### Open-Source IPA Sideloading & App Signing Tools



* **[Sideloader (Dadoum)](https://github.com)** - Cross-platform open-source IPA sideloading tool written in Nim/C++ supporting Windows, Linux, and macOS without iTunes dependencies.

* **[Impactor (PlumeImpactor / Open Sideloaders)](https://github.com)** - Modern, cross-platform open-source iOS IPA signing and sideloading utility built in Rust for Linux, macOS, and Windows.

* **[zsign](https://github.com)** - Fast, cross-platform open-source code-signing utility for iOS `.ipa` files written in C++ for Linux, macOS, and Windows.

* **[Feather](https://github.com)** - Free, open-source on-device iOS IPA installer and manager supporting custom certificate signing and alt-store repositories.

* **[ESign / Scarlet Open-Source Alternatives (AppInstaller iOS)](https://github.com)** - Open-source on-device app signers eliminating closed-source telemetry found in proprietary third-party IPA installers.



### iOS Device Management, Protocols & Debugging CLI



* **[libimobiledevice](https://github.com)** - Cross-platform open-source C library and CLI suite (`ideviceinstaller`, `idevicesyslog`, `idevicebackup2`) to communicate natively with iOS devices.

* **[pymobiledevice3](https://github.com)** - Pure-Python3 open-source implementation for working with all iOS device protocols, developer disk images, tunnels, and container inspection.

* **[go-ios](https://github.com)** - Standalone open-source tool written in Go enabling automated iOS device control, app installation, and XCUITest execution on Linux and Windows.

* **[ifuse](https://github.com)** - Open-source FUSE filesystem driver allowing users to mount iOS app document containers and media directories directly on Linux and macOS.

* **[Appium (XCUITest Driver)](https://github.com)** - Open-source UI automation driver for testing iOS apps and managing simulator/device containers programmatically.



### Self-Hosted OTA App Distribution & Beta Testing Platforms



* **[ipapk-server](https://github.com)** - Lightweight, self-hosted open-source OTA server for uploading and distributing iOS `.ipa` and Android `.apk` builds over HTTPS.

* **[AppHost](https://github.com)** - Open-source, self-hosted internal app store and beta distribution platform serving as a private alternative to Diawi and TestFlight.

* **[Firim / Zealot](https://github.com)** - Self-hosted open-source over-the-air mobile app distribution platform with CI/CD webhooks, UDID collection, and version history.

* **[InstallOnAir Open Alternatives (OpenOTA)](https://github.com)** - Self-hosted open-source web signing and OTA installation server allowing teams to distribute signed IPAs from their own domain.



### Self-Hosted Mobile CI/CD, Virtualization & Build Infrastructure



* **[Fastlane](https://github.com)** - The industry-standard open-source automation toolset for iOS code signing (`match`), screenshot generation, building, and TestFlight/App Store deployment.

* **[Tart (Cirrus Labs)](https://github.com)** - Open-source macOS and Linux virtual machine toolset built on Apple's Virtualization.Framework for ephemeral Apple Silicon iOS CI/CD runners.

* **[XcodeGen](https://github.com)** - Open-source command-line tool written in Swift that generates clean Xcode projects from YAML specs and folder structures.

* **[Tuist](https://github.com)** - Open-source toolchain for scaling Xcode projects with modularization, binary caching, and streamlined local/CI workflows.

* **[xtool](https://github.com)** - Cross-platform open-source Xcode replacement enabling SwiftPM-based iOS app compilation, signing, and deployment directly from Linux and Windows.



---



## Contributing



Contributions are welcome! Feel free to open a Pull Request to add more open-source iOS utilities, mobile container storage tools, IPA sideloaders, or iOS DevOps infrastructure.



1. Fork the repository.

2. Add your project under the appropriate category with a concise description.

3. Submit a Pull Request.
