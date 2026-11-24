RootChecker

"Platform" (https://img.shields.io/badge/Platform-Android-brightgreen?logo=android)
"Category" (https://img.shields.io/badge/Category-Root%20Detection-red)
"Detection" (https://img.shields.io/badge/Detection-Temporary%20%26%20Persistent-orange)
"GhostLock" (https://img.shields.io/badge/Support-GhostLock-purple)
"ReSukiSu" (https://img.shields.io/badge/Support-ReSukiSu-blue)
"BakaSu" (https://img.shields.io/badge/Support-BakaSu-yellow)
"KernelSU" (https://img.shields.io/badge/Support-KernelSU-informational)
"RootMyAndroid" (https://img.shields.io/badge/Support-RootMyAndroid-green)
"Security" (https://img.shields.io/badge/Security-OTP%20Verification-success)
"Monitoring" (https://img.shields.io/badge/Feature-Device%20Monitoring-lightgrey)

An Android security monitoring application that detects temporary and persistent root environments, monitors device restarts, tracks removed applications, and provides OTP-based application access protection.

📱 Overview

RootChecker is designed to identify root access and monitor changes in the Android device environment.

It supports multiple root management frameworks and provides information about device restarts, previously installed applications, and available application activity timestamps.

The application also includes OTP lock verification to prevent unauthorized access.

✨ Key Features

1. OTP Lock Verification

- Requires OTP verification before accessing the application.
- Prevents unauthorized application access.
- Grants access only after successful verification.

2. Root Detection

Identifies root access and checks for supported root management frameworks:

- GhostLock
- ReSukiSu
- BakaSu
- KernelSU
- Traditional Android Root

3. Temporary Root Detection

- Identifies indicators of temporary root access.
- Checks for traces associated with supported root frameworks.
- Monitors changes in root status.

4. Device Restart Detection

- Detects device reboot events.
- Records restart timestamps.
- Helps track changes before and after device restarts.

5. Deleted Application Monitoring

- Identifies previously installed applications that are no longer available.
- Displays detected application removal information.
- Shows available last-used and deletion-related timestamps.

6. Application Activity Information

Displays available information such as:

- Application name
- Package name
- Last-used timestamp
- Deletion information
- Device restart timestamp

🛠️ Detection Capabilities

Component| Function
OTP Verification| Application access protection
GhostLock| Root framework detection
ReSukiSu| Root framework detection
BakaSu| Root framework detection
KernelSU| Root framework detection
Android Root| General root detection
Device Reboot| Restart monitoring
Deleted Apps| Application removal tracking
Last Used| Application activity information

🔍 How It Works

1. OTP Authentication: Users must complete OTP verification before entering the application.
2. Root Analysis: Checks the Android environment for supported root framework indicators.
3. Root Monitoring: Identifies signs of temporary and persistent root access.
4. Reboot Monitoring: Detects device restarts and records timestamps.
5. Application Monitoring: Compares previously recorded application information with currently available applications.
6. Information Display: Shows root detection results, reboot history, removed applications, and available timestamps.

🎯 Project Objectives

- Detect temporary and persistent root environments.
- Identify popular Android root management frameworks.
- Monitor device restart events.
- Track previously installed applications that have been removed.
- Display available application activity information.
- Provide OTP-based authentication.
- Improve Android device security monitoring.

⚠️ Important Notes

- Root detection cannot guarantee identification of every root implementation.
- Root frameworks may change their methods.
- Deleted application identification depends on previously collected information.
- Android may not provide exact application deletion timestamps.
- Last-used information depends on available permissions and Android features.
- Detection results are security indicators, not absolute proof of compromise.

🔐 Permissions

Depending on the implementation, the application may require:

- Installed application visibility
- Application usage statistics
- Device reboot monitoring
- Background monitoring
- Internet access or other permissions required by the OTP implementation

Permission availability may vary across Android versions and devices.

📌 Use Cases

- Android device security monitoring
- Root framework identification
- Temporary root environment analysis
- Application removal monitoring
- Device reboot tracking
- OTP-based application access control
- Mobile security research

🚧 Future Enhancements

- [ ] Support additional root management frameworks.
- [ ] Improve hidden root detection.
- [ ] Maintain detailed reboot history.
- [ ] Add installation and uninstallation history.
- [ ] Introduce security alerts for suspicious changes.
- [ ] Generate security monitoring reports.
- [ ] Improve Android version compatibility.
- [ ] Add OTP expiration and resend management.

⚖️ Disclaimer

RootChecker is intended for Android security research, device integrity monitoring, and educational purposes.

Detection results may vary depending on Android versions, device configurations, permissions, and root-hiding techniques.

OTP verification provides an additional layer of application security but does not guarantee complete device protection.

---

Built for Android Security Monitoring, Root Detection & Secure Application Access. 🔐
