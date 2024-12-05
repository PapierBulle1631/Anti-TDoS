# Anti-TDoS Android App

## Overview

The **Anti-TDoS** app is designed to protect Android users from potential Telephony Denial of Service (TDoS) attacks by automatically blocking excessive incoming calls. The app monitors incoming calls, and if more than 3 calls are detected in one minute, it will notify the user and provide an option to block future calls. 

This can help prevent unwanted disruptions due to aggressive spam or attack attempts via telephony services.

## Features

- **Call Monitoring**: Detects incoming calls and tracks their frequency.
- **Automatic Call Blocking**: After detecting more than 3 incoming calls in one minute, the app can automatically block calls.
- **Notifications**: Sends notifications to the user when a potential TDoS attack is detected.
- **Permissions**: Requests necessary permissions to read call state and end calls (if required).

## Installation

1. **Clone this repository** or **Download the APK file**:
   - To clone:
     ```bash
     git clone https://github.com/PapierBulle1631/Anti-TDoS.git
     ```
   - Or download the APK directly from the releases section.

2. **Install the APK** on your Android device:
   - Go to **Settings > Security** and enable **Install from Unknown Sources**.
   - Open the downloaded APK file on your device to begin the installation.

## Permissions Required

- **READ_PHONE_STATE**: Required to monitor incoming calls.
- **ANSWER_PHONE_CALLS**: Required to end calls if a TDoS is detected.
- Do not forget to giev every needed permissions from **settings**

## Usage

1. Once installed, the app will automatically start monitoring incoming calls.
2. If it detects more than 3 calls in a minute, it will notify the user.
3. The user can choose to disable call blocking by interacting with the notification.
4. The app works silently in the background, only notifying the user when necessary.

## License

This project is licensed under the Apache 2.0 - see the [LICENSE](LICENSE) file for details.

## Contributing

This is a finished version and no modification are to come. Feel free to send feedback but it is not probable that the apk changes.

## Contact

For any inquiries or issues, feel free to open an issue in this repository, or contact me at:
- Email: bubblewrap1631@gmail.com
