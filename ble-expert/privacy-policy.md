---
layout: default
title: BLE Expert - Privacy Policy
---

# Privacy Policy for BLE Expert

**Effective Date:** October 2026

Thank you for choosing **BLE Expert**. Your privacy is critically important to us. This Privacy Policy explains how the application handles information when you use it. We are committed to complying with Google Play's User Data policy.

## 1. Information Collection and Use

**BLE Expert is a local engineering tool. It runs on your device.** We do not collect, transmit, store, share, or sell personal data, location, scan results, GATT payloads, or mesh keys to any server we operate.

The app uses Android Bluetooth permissions only to do the work you start:

*   **Bluetooth scan (`BLUETOOTH_SCAN`):** On Android 12 and later this permission is declared with `neverForLocation`. Scan results, RSSI, and advertisement payloads stay in the app.
*   **Location (`ACCESS_FINE_LOCATION`, `ACCESS_COARSE_LOCATION`):** Android 11 and earlier require a location permission before an app can scan for Bluetooth LE devices. We use it only for that scan. We do not read GPS fixes, and we do not upload a location.
*   **Bluetooth connect (`BLUETOOTH_CONNECT`):** Used when you connect, read, write, subscribe, or bond with a device you choose.
*   **Bluetooth advertise (`BLUETOOTH_ADVERTISE`):** Used only when you start advertising or a connectable GATT server on this phone.

**No telemetry:** The app does not send crash reports, analytics, or advertisement identifiers. It does not read the Google Advertising ID, SIM serial, or a device identifier for tracking.

## 2. Bluetooth and Mesh Traffic

Connections, advertisements, and Bluetooth Mesh messages go directly between this phone and nearby devices. That traffic does not pass through our servers. Mesh network keys, application keys, and provisioned node records are stored in the app's local storage on the device.

## 3. Google Play Billing

Toolbox access can be unlocked with a free trial stored on the device, or with the Google Play subscription `ble_expert_premium`. Purchases are processed by Google Play. We do not receive your payment card number. The app asks Play whether the subscription is active so it can unlock the toolbox. The app does not create an account, and it does not ask for an email or password.

## 4. Data Retention

Scan lists, GATT logs, settings, mesh keys, and the trial clock stay in the application sandbox on your device. We do not keep a copy on an external database.

**Retention period:** This local data remains until you clear it, clear the app's storage, or uninstall the app.

## 5. Data Deletion

Because we do not hold your data on a server, there is no deletion request to send us. You can remove local data in either of these ways:

1. **In the app:** Settings → Data & permissions → Clear cache removes the scan list and cached GATT logs.
2. **System settings:** Settings → Apps → BLE Expert → Storage → Clear data.
3. **Uninstall:** Removing the app deletes its local data.

Mesh network backups that you copied to the clipboard or saved elsewhere are outside the app. Delete those copies yourself.

## 6. Changes to This Privacy Policy

We may update this policy from time to time. The new text will be posted on this page with a revised effective date.

## 7. Contact Us

Questions about this policy can be sent to the developer email shown on the BLE Expert listing in Google Play.
