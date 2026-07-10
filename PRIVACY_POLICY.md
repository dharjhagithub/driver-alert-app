# Privacy Policy — Driver Alert Monitor

**Effective date:** July 10, 2026
**Last updated:** July 10, 2026
**Developer:** Dharmendra Jha
**Contact:** dhaajh@gmail.com
**App repository:** https://github.com/dharjhagithub/driver-alert-app

---

## 1. Overview

Driver Alert Monitor ("the App") is a free, open-source drowsiness detection application released under the MIT License. This Privacy Policy explains what data the App accesses, how it is used, and your rights as a user.

**Summary for users who prefer plain language:**
- The App uses your device camera to detect drowsiness in real time.
- All camera processing happens entirely on your device.
- No video, images, or biometric data are ever recorded, stored, or transmitted.
- The App has no account system, no analytics, no advertising, and no backend server.
- We collect nothing. We store nothing. We share nothing.

---

## 2. Information We Do Not Collect

The App does **not** collect, store, transmit, or share any of the following:

- Video footage or still images from your camera
- Biometric data of any kind (facial geometry, eye patterns, or movement data)
- Location data (GPS or network-based)
- Device identifiers (IMEI, advertising ID, or similar)
- Usage statistics or analytics
- Crash reports or diagnostic data
- Any personally identifiable information

---

## 3. Camera Access

The App requests access to your device's front-facing camera solely to perform real-time drowsiness detection. Specifically:

- **Purpose:** The camera feed is analysed frame-by-frame on your device to detect signs of drowsiness such as eye closure, head drooping, or face turning away.
- **Processing:** All analysis is performed locally on your device using TensorFlow.js. The camera feed is never encoded, saved, uploaded, or transmitted in any form.
- **Retention:** No frame, image, or video clip is ever written to your device storage or sent off your device.
- **Scope:** Camera access is only active while you have explicitly started a monitoring session by tapping "Start Monitoring." It stops immediately when you tap "Stop Monitoring" or close the App.

You may revoke camera permission at any time via your device settings. The App will not function without camera access as it is the sole mechanism of drowsiness detection.

---

## 4. AI Model and Internet Access

The App uses the MediaPipe FaceMesh model via TensorFlow.js for face and eye detection.

- On first launch, the App downloads the AI model files from trusted content delivery networks (jsDelivr CDN and/or TensorFlow Hub) over a standard HTTPS connection.
- These model files contain no personal data. They are generic mathematical weights used for face detection and are not personalised to you in any way.
- After the first download, the model is cached on your device and the App operates fully offline. No subsequent network requests are made during normal use.
- The App does not communicate with any server operated by the developer during or after use.

---

## 5. Data Stored on Your Device

The App stores only the following on your device, solely to enable offline operation:

- **AI model cache:** The downloaded TensorFlow.js model weights, stored in your browser's Cache Storage. This contains no personal data.
- **EULA acceptance state:** A flag indicating whether you have accepted the End User License Agreement during the current session. This is not persisted between sessions.

No personal information, camera data, or usage history is ever written to your device storage.

---

## 6. Third-Party Services

The App does not integrate with any third-party analytics, advertising, social media, or tracking services.

The only third-party network requests the App makes are:

| Service | Purpose | Privacy Policy |
|---|---|---|
| jsDelivr CDN | Download AI model on first launch | https://www.jsdelivr.com/privacy-policy-jsdelivr-net |
| TensorFlow Hub | Alternative AI model source | https://policies.google.com/privacy |

Neither service receives any camera data or personal information from you. They serve static files only.

---

## 7. Children's Privacy

The App is intended for use by licensed motor vehicle drivers and is therefore directed at users aged 18 and older. The App does not knowingly collect any information from children under the age of 13. If you believe a child under 13 has used the App, please note that no data has been collected and no action is required.

---

## 8. Important Safety and Liability Disclaimer

Driver Alert Monitor is a **supplemental driving aid only**. It is not a substitute for attentive, responsible driving.

**You must understand and acknowledge the following before using the App:**

- The App **may fail** to detect drowsiness under certain conditions including poor lighting, unusual camera angles, obstructions, or hardware limitations.
- The App **may generate false alerts** that could momentarily distract you.
- The App **does not control your vehicle** in any way.
- **You are solely and fully responsible** for the safe operation of your vehicle at all times, regardless of whether the App is running, alerting, or functioning correctly.
- The App **must not** be used as justification for driving while impaired, fatigued, or medically unfit to drive.
- The developer, contributors, and distributors of this App **accept no liability** for any accident, injury, loss, or damage arising from the use or misuse of this App, or from the failure of the App to detect drowsiness or generate a timely alert.

If you feel drowsy while driving, **do not rely on any app**. Pull over safely and rest.

---

## 9. Open Source Transparency

Driver Alert Monitor is fully open source under the MIT License. The complete source code is publicly available at:

**https://github.com/dharjhagithub/driver-alert-app**

You are encouraged to inspect, audit, and verify the code yourself. The source code confirms that no data collection, transmission, or storage of personal information takes place.

---

## 10. Changes to This Policy

If the App is updated in a way that materially changes how data is handled, this Privacy Policy will be updated and the "Last updated" date at the top of this document will be revised. Continued use of the App after any such change constitutes acceptance of the updated policy.

Given the App's current design (no data collection of any kind), material changes are unlikely. Any future version that introduces data collection would require explicit user consent before such collection begins.

---

## 11. Your Rights

Because the App collects no personal data, there is no personal data to access, correct, export, or delete. No action is required or possible on either side.

If you have questions about this policy or the App's data practices, you may contact the developer at:

**Email:** dhaajh@gmail
**GitHub:** https://github.com/dharjhagithub/driver-alert-app/issues

---

## 12. Governing Law

This Privacy Policy is governed by the laws of India. Any disputes arising from this policy shall be subject to the jurisdiction of the courts of India.

---

*Driver Alert Monitor is released under the MIT License and provided free of charge. The developer makes no warranties of any kind regarding the App's fitness for any particular purpose, including road safety.*