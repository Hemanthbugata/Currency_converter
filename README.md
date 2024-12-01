# Currency Converter

A sleek Android app for converting between currencies and Bitcoin. Fetches live exchange rates from two APIs for accurate conversions.

## Features

- Convert between global currencies.
- Fetch live Bitcoin exchange rates.
- Data fetched using reliable APIs.
- User-friendly and responsive interface.

## Tech Stack

- **Language**: Java
- **Build Tool**: Gradle
- **API Integration**: Two APIs for currency and Bitcoin data

## Prerequisites

- **Android Studio** (latest version recommended)
- Minimum SDK: 21 (Android 5.0 Lollipop)
- An active internet connection for API data

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Hemanthbugata/Currency_converter.git
   cd Currency_converter
2. Open the Project in Android Studio
Launch Android Studio.
Go to File > Open... and navigate to the cloned project directory.
Click OK to open the project.

3. Sync Gradle Files
Android Studio should prompt you to Sync Gradle Files. If not:
Go to File > Sync Project with Gradle Files.
Ensure you are connected to the internet for Gradle to download dependencies.

4. Configure API Keys
Open the file res/values/strings.xml.
Add your API keys for currency and Bitcoin data:
xml
```
<string name="currency_api_key">your_currency_api_key</string>
<string name="bitcoin_api_key">your_bitcoin_api_key</string>
```
Replace your_currency_api_key and your_bitcoin_api_key with the actual API keys.


5. Build the Project
Go to Build > Rebuild Project in Android Studio.
Wait for the build process to complete.
Fix any errors if they occur (e.g., missing dependencies or Gradle version issues).


6. Run the App
Connect a physical device with USB Debugging enabled, or start an emulator:
To enable USB Debugging:
Go to Settings > Developer Options > Enable USB Debugging on your device.
Click the green Run button in Android Studio or press Shift + F10.
Select the target device and wait for the app to launch.


Troubleshooting
Gradle Issues
Check the gradle-wrapper.properties file for the correct Gradle version.
Update Gradle via File > Project Structure > Project if needed.

API Key Errors

Ensure the API keys are correct and valid.
Test the API endpoints using a tool like Postman to verify connectivity.

Emulator Issues
Use a compatible device image for the app's minimum SDK version.

Allocate more RAM to the emulator for better performance:

Go to AVD Manager > Edit Virtual Device > Show Advanced Settings > Memory and Storage.

final output files :

  
![image](https://github.com/user-attachments/assets/e34a34aa-1ff4-49d2-a141-5de4cf0b9420)

![image](https://github.com/user-attachments/assets/61dd6881-3d54-462b-a594-474f14f12eae)

![image](https://github.com/user-attachments/assets/9522a1be-294d-40a8-8ede-5088f0283aae)



Additional Notes

The app uses two APIs for:
Currency Conversion: Real-time exchange rates.
Bitcoin Conversion: Latest Bitcoin rates.
Ensure API services are accessible and active during testing.
