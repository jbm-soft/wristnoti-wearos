# WristNoti (WearOS & Android Companion)

Smartwatch notification companion application built for **WearOS** and **Android**, enabling customizable vibration patterns, quick replies, and filtered notification forwarding.

> 🌐 **JBM SOFT:** [https://jbmsoft.co.kr](https://jbmsoft.co.kr)  
> 🔒 **Note:** This repository serves as a public architecture & portfolio showcase. Proprietary signing keys, ad IDs, and commercial build configs are excluded.

---

## ✨ Key Capabilities

- **WearOS Data Layer Sync:** Reliable phone-to-watch notification bridging
- **Custom Notification Filtering:** App-level allow/mute rules and keyword filtering
- **Battery-Conscious Background Service:** Lightweight listener with minimal wake-locks
- **Haptic & Alert Profiles:** Distinct vibration cues per priority tier

---

## 🏗 Architecture Overview

```text
Android NotificationListenerService
        │
        ▼ (Rule Engine & Filter)
Wearable DataClient / MessageClient
        │
        ▼
WearOS Companion UI & Haptic Dispatcher
```

---

## 🛠 Tech Stack

- **Mobile / Watch:** Android SDK, WearOS, Kotlin / Flutter
- **Privacy Policy:** [wristnoti-privacy](https://github.com/jbm-soft/wristnoti-privacy)
