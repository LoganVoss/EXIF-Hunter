# EXIF Hunter

SwiftUI macOS project by Logan Voss.

## Project status

The checked-in app currently opens a starter view with a globe icon and “Hello, world!” text. EXIF inspection features are not implemented in the current source.

## Open the project

1. Clone this repository.
2. Open [`ExifHunter.xcodeproj`](ExifHunter.xcodeproj) in Xcode.
3. Select the `ExifHunter` target and a Mac run destination.
4. Build and run with **⌘R**. If Xcode requests signing setup, select your own development team in **Signing & Capabilities**.

The project was created with Xcode 16.4 and is configured for macOS 15.5 with Swift 5 language mode. These settings are recorded in [`project.pbxproj`](ExifHunter.xcodeproj/project.pbxproj).

## Repository guide

- [`ExifHunter/ExifHunterApp.swift`](ExifHunter/ExifHunterApp.swift): app entry point and window setup.
- [`ExifHunter/ContentView.swift`](ExifHunter/ContentView.swift): current main view and SwiftUI preview.
- [`ExifHunter/Assets.xcassets`](ExifHunter/Assets.xcassets): asset catalog.
- [`ExifHunter/ExifHunter.entitlements`](ExifHunter/ExifHunter.entitlements): app entitlements.
