# RootChecker
Android security monitoring tool that detects temporary and persistent root environments (GhostLock, ReSukiSu, BakaSu, KernelSU), monitors device reboots, and identifies previously installed applications that have been removed.
android, root-detection, temporary-root, root-checker, kernelsu, ghostlock, bakasu, resukisu, android-security, root-management, root-framework, mobile-security, device-integrity, android-development, security-monitoring
# 📱 Android Root & Temporary Root Detection System

A security-focused Android application designed to detect root access, identify temporary root environments, monitor device reboot events, and track applications that have been removed from the device.

## 🚀 Overview

This project provides an Android security monitoring solution that detects various root management frameworks and monitors changes in the device's application environment.

Unlike basic root detection systems, this application focuses on identifying both persistent and temporary root access mechanisms. It also monitors device restart events and maintains information about applications that were deleted after being previously installed.

The application displays useful details such as the detection timestamp, last-used time, and deletion information to help users understand changes in their device environment.

## ✨ Key Features

### 1. Root Detection
Detects root access and identifies the presence of multiple root management frameworks, including:

- **GhostLock**
- **ReSukiSu**
- **BakaSu**
- **KernelSU**
- **Traditional Android Root**

### 2. Temporary Root Detection
- Identifies temporary root access mechanisms.
- Checks for traces and indicators associated with supported root frameworks.
- Helps identify root environments that may not remain active permanently.
- Provides additional visibility into changes in the device's root status.

### 3. Device Restart Detection
- Detects when the Android device has been restarted.
- Tracks reboot events and their timestamps.
- Helps correlate device restarts with changes in root status and installed applications.

### 4. Deleted Application Monitoring
- Identifies applications that were previously installed but are no longer present.
- Displays information about detected deleted applications.
- Records the available deletion-related timestamps.
- Displays the last-used time when available.

### 5. Application Activity Information

Provides application-related information, including:

- Application name
- Package name
- Last-used timestamp (when available)
- Detected deletion information
- Device restart timestamp

## 🛠️ Detection Capabilities

| Component | Detection |
|---|---|
| GhostLock | Root framework detection |
| ReSukiSu | Root framework detection |
| BakaSu | Root framework detection |
| KernelSU | Root framework detection |
| Android Root | General root detection |
| Device Reboot | Restart event detection |
| Deleted Apps | Previously installed application monitoring |
| Last Used | Application usage information, when available |

## 🔍 How It Works

The application follows a monitoring-based approach:

1. **Root Analysis:** Checks the Android environment for indicators associated with supported root management frameworks.
2. **Root Status Monitoring:** Evaluates the device for signs of temporary or persistent root access.
3. **Reboot Monitoring:** Detects device restart events and records the corresponding timestamps.
4. **Application Monitoring:** Tracks application installation information and identifies previously installed applications that are no longer available.
5. **Information Display:** Presents detected root frameworks, reboot information, deleted applications, and available application usage timestamps.

## 🎯 Project Objectives

- Improve visibility into Android root environments.
- Detect temporary as well as persistent root indicators.
- Identify the presence of popular Android root management frameworks.
- Monitor device restart events.
- Identify applications removed from the device.
- Provide useful application activity and timestamp information.
- Support Android security analysis and device integrity monitoring.

## ⚠️ Important Notes

- Root detection is based on identifiable indicators and is not guaranteed to detect every root implementation.
- Root management frameworks may change their implementation to evade detection.
- Deleted application identification depends on previously collected application information.
- Android does not always expose the exact application deletion timestamp.
- Last-used information may depend on available Android usage statistics and granted permissions.
- Detection results should be treated as security indicators rather than absolute proof of compromise.

## 🔐 Permissions

Depending on the implementation, the application may require Android permissions or special access for:

- Installed application visibility
- Application usage statistics
- Device reboot event monitoring
- Background monitoring

Some capabilities may vary depending on the Android version and device manufacturer.

## 📌 Use Cases

- Android device security monitoring
- Root framework identification
- Temporary root environment analysis
- Android application removal monitoring
- Device reboot tracking
- Mobile security research
- Android device integrity analysis

## 🚧 Future Enhancements

- [ ] Add support for more root management frameworks.
- [ ] Improve detection of hidden root environments.
- [ ] Maintain a detailed device reboot history.
- [ ] Add application installation and uninstallation history.
- [ ] Introduce security alerts for suspicious device changes.
- [ ] Generate detailed security monitoring reports.
- [ ] Improve compatibility across Android versions.

## 🤝 Contributions

Contributions, suggestions, and bug reports are welcome!

If you would like to improve root detection techniques or add support for additional Android root frameworks, feel free to contribute.

## ⚖️ Disclaimer

This project is intended for Android security research, device integrity monitoring, and educational purposes.

The detection mechanisms are designed to identify potential root-related indicators and application environment changes. Results may vary depending on Android versions, device configurations, permissions, and root-hiding techniques.

---

**Built for Android Security Monitoring & Root Environment Analysis.** 🔐
