
# Helios Privacy Policy

**Effective Date: May 4, 2026**

This Privacy Policy describes the information we collect when you use Helios mobile applications, websites, and products. It also explains how we store, use, transfer, and delete your information. Our goal is not only to comply with privacy laws and regulations, but also to earn and maintain your trust.

## Information We Collect & How We Use It

Helios does not display advertisements in our mobile app or on our devices. Any data collected is used solely for the operation of Helios and for troubleshooting purposes. Data required for Helios to function remains encrypted and stored locally on your device. When you delete the app, your data is deleted as well. Below is a summary of the data we collect and how it is used. These descriptions are also available in-app, where you can configure and modify your preferences at any time.

### Device Model & Operating System (OS) Version

*If you opt out, Crashlytics will be disabled.*

Device information is used to identify crash patterns that may be specific to certain devices or operating systems.


### Device Time

*If you opt out, you will need to manually set the lamp time. Bluetooth scan functionality requires device time under legitimate interest and will be maintained.*

We use your device's time to control lamp schedules. Bluetooth uses the time to limit scans to no more than five every 30 seconds. If Crashlytics is enabled, the device time is also used to report when a crash occurs.

### MAC Address (Lamp Identifier)

*If you opt out, the app will not send the MAC address to Crashlytics. Otherwise, the use and storage of the MAC address is considered a legitimate interest, as it is necessary to connect to and control your lamp.*

The MAC address is a unique Bluetooth identifier assigned to each device. On Android, this address is static; on iOS, it changes every 15–20 minutes. Helios uses this address to track your lamp(s) within internal processes. This information is encrypted and stored locally on your device, and is only included in Crashlytics reports if enabled.

### RSSI (Bluetooth Signal Strength)

*If you opt out, you will need to manually connect to lamps as needed.*

RSSI is a Bluetooth measure of signal strength. Helios uses it to connect your phone to the nearest Helios lamps. We do not store or share RSSI data. It is only collected via Crashlytics in the event of a crash. This data is considered sensitive because it could potentially be used to estimate location.

## Third-Party Services

Helios uses Crashlytics to collect information about your Helios system in the event of an error or crash. This is the only circumstance in which data is sent to Helios developers. Crashlytics is an optional feature; you can choose to allow or deny it when you first use the app. Crashlytics has its own privacy policy, but at Helios, we prioritize your privacy and have disabled as much of Crashlytics' data collection as possible, including Google Analytics.

When sending data to Crashlytics, we include only the minimum details necessary to resolve issues. Any additional data collection would only occur if you contact us directly.

Crashlytics will only be enabled if you have opted in to both Crashlytics and Device Model & OS collection. If either is disabled, Crashlytics will not be enabled, as Device Model & OS information is required for crash reports.

When the app is running, the lamp state data is constantly changing and logs as we do operations. The data is only used for crash reporting and is only collected at the time of a crash.

#### Crash Report Data Details

The following data may be collected at the time of a crash:

- **Device Model & OS Version**: Used to identify crash patterns specific to certain devices or operating systems.
- **App Version**: Helps us track issues related to specific releases. If you report a bug on an older version, we may advise you to update the app if the issue has been fixed.
- **Lamp Version(s)**: The firmware version of connected lamps, collected only if iLumens lamps are connected at the time of the crash. This helps identify compatibility issues.
- **Scanned iLumens Bluetooth Devices**: During a Bluetooth scan, we log the name, ID, and RSSI (signal strength) of detected iLumens devices. The app connects to a maximum of three iLumens devices at a time. This information is only collected at the time of a crash and helps diagnose connection issues.
- **Lamp Identifiers**: The MAC address and user-assigned name of your lamp, collected only at the time of a crash, to help track your lamp during troubleshooting.
- **Schedule Data**: If your lamp has active schedules, we log them to replicate issues in-house. We do not track inactive schedules or your usage of them. This is only collected at the time of a crash.
- **LED Data**: The current LED settings (brightness and color) at the time of the crash. We do not track your history of LED usage.
- **Lamp State Data**: Whether your lamp is on or off, if a schedule is active, and if the lamp believes it is day or night based on the schedule. We also log whether the current LED settings are set manually or by a schedule, and if the night light or motion sensor is active. This data is only collected at the time of a crash.
- **Time of Crash**: The exact time of the crash and the time your phone sends the report, which is important for diagnosing scheduling issues.
- **Stack Traces**: Detailed information about the app's state at the time of the crash, including the sequence of function calls. Stack traces do not contain any identifiable data beyond what is listed above.

## Data Retention

In-app data is retained only while the app is installed on your device. If you delete the app, all associated data is deleted as well. Unless information is sent through a Crashlytics report, Helios developers never see, collect, or store your data.

Crashlytics automatically deletes all crash report data every 6–8 months.

## Requesting & Deleting Your Data

### In-App Data

For security reasons, the raw data stored on your device cannot be directly viewed by users. This protects our encryption methods in case your device is compromised. However, nearly all data stored on your device is displayed within the app, including lamp names, schedules, and your privacy settings. Some meta-data is stored for functional purposes only and is not user-facing.

### Crashlytics Data

#### Deleting Crashlytics Data

You can delete your Crashlytics data in-app with a single click. Additionally, whenever you disable Crashlytics, we automatically send a deletion request on your behalf. Crashlytics processes these requests within 24 hours and provides an estimated deletion date. All Crashlytics data is deleted after 6–8 months, regardless of requests.

#### Requesting Your Crashlytics Data

Due to the anonymization of data sent to Crashlytics, we may require additional information from you to process your request. For best results, do not disable Crashlytics before submitting your request. To request your data, go to Helios settings (cog icon at the top right of the home page), navigate to Feedback, and send us a message. We are committed to supporting your autonomy over your data and will assist you throughout the process.
