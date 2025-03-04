# AEP SDK Sample App for Android

## About this Project

This repository contains the Android sample app for the AEP SDK. 

## Prerequisites

- Android Studio 3.+ with an Android emulator running 7.0+
- JDK 8.+
- Gradle 4.4+

## Installation

1. Open Android Studio and select `Open an existing project`  from the main screen or click `File -> Open...` .
2. Import the Sample-App/settings.gradle file into Android Studio.
3. Set your `ENVIRONMENT_FILE_ID` in MainApp.java.
4. Run Android `app` on the emulator or on real device.

## Documentation
### Edge Extensions Prerequisites
The app needs to be configured with the following Edge extensions in the Data Collection UI before it can be used: 
- [Edge](https://aep-sdks.gitbook.io/docs/foundation-extensions/experience-platform-extension)
- [Edge Identity](https://aep-sdks.gitbook.io/docs/foundation-extensions/identity-for-edge-network)
- [Consent](https://aep-sdks.gitbook.io/docs/foundation-extensions/consent-for-edge-network)
- [Messaging](https://aep-sdks.gitbook.io/docs/beta/adobe-journey-optimizer#configure-extension-in-launch)

### Lifecycle for Edge Network 
Follow the [documentation](https://aep-sdks.gitbook.io/docs/foundation-extensions/lifecycle-for-edge-network) to forward Lifecycle extension metrics to the Adobe Experience Platform.

### Messaging
Follow the [documentation](Documentation/README.md) for using the messaging features.

### Advertising Identifier
Follow the [documentation](Documentation/README.md#advertising-identifier) for enabling advertising identifier features.

## Contributing

Contributions are welcomed! Read the [Contributing Guide](./.github/CONTRIBUTING.md) for more information.

## Licensing

This project is licensed under the MIT License. See [LICENSE](LICENSE) for more information.

