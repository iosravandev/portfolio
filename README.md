<div align="center">

<img src="assets/banner.svg" alt="Ravan Mehdiyev — iOS Developer Portfolio" width="100%">

<br>

![Swift](https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white)
![SwiftUI](https://img.shields.io/badge/SwiftUI-0D96F6?style=for-the-badge&logo=swift&logoColor=white)
![iOS](https://img.shields.io/badge/iOS-000000?style=for-the-badge&logo=apple&logoColor=white)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?style=for-the-badge&logo=xcode&logoColor=white)

Native iOS apps I design and build, from product idea to App Store–ready release.

[**Scrollary**](#-scrollary) &nbsp;•&nbsp; [**MedCall**](#-medcall) &nbsp;•&nbsp; [**Tech Stack**](#-tech-stack) &nbsp;•&nbsp; [**Certificates**](https://github.com/iosravandev/certificates) &nbsp;•&nbsp; [**Website**](https://iosravandev.github.io/portfolio/)

</div>

---

## 📚 Scrollary

> **Earn your screen time by learning vocabulary.**

Scrollary blocks the apps you choose, such as Instagram or TikTok, using Apple's Screen Time. To unlock them, you scroll a TikTok-style feed of vocabulary cards. Each correct answer earns minutes of screen time. Words you miss go into **My Words**, where a Recovery Quiz pays double.

<table>
  <tr>
    <td align="center" width="20%"><img src="assets/scrollary/feed.jpg" alt="Word feed"><br><sub><b>Word feed</b></sub></td>
    <td align="center" width="20%"><img src="assets/scrollary/how-it-works.jpg" alt="How it works"><br><sub><b>How it works</b></sub></td>
    <td align="center" width="20%"><img src="assets/scrollary/stats.jpg" alt="Stats"><br><sub><b>Stats</b></sub></td>
    <td align="center" width="20%"><img src="assets/scrollary/my-words.jpg" alt="My Words"><br><sub><b>My Words</b></sub></td>
    <td align="center" width="20%"><img src="assets/scrollary/plans.jpg" alt="Subscription plans"><br><sub><b>Plans</b></sub></td>
  </tr>
</table>

**Highlights**

- 🛡 **Screen Time integration**: blocks the chosen apps with the Family Controls, ManagedSettings and DeviceActivity frameworks, plus custom Shield UI and Shield Action extensions.
- 🃏 **Endless learning feed**: vertical, swipeable word cards with meaning-match and fill-in-the-blank quizzes, audio and example sentences.
- ⏱ **Time economy**: correct answers bank minutes of screen time. Boost quizzes and Recovery Quizzes (2× rewards) make reviewing worthwhile.
- 📊 **Progress & stats**: words learned, points, daily goals and milestones.
- 🔄 **Offline-first sync**: the full word catalogue is cached locally with SwiftData and kept up to date by delta sync against a NestJS REST API.
- 💳 **Subscriptions**: monthly and yearly plans with a free trial through RevenueCat. No account or login needed.

![SwiftUI](https://img.shields.io/badge/SwiftUI-111827?style=flat-square)
![SwiftData](https://img.shields.io/badge/SwiftData-111827?style=flat-square)
![Observation](https://img.shields.io/badge/Observation-111827?style=flat-square)
![FamilyControls](https://img.shields.io/badge/Family_Controls-111827?style=flat-square)
![ManagedSettings](https://img.shields.io/badge/ManagedSettings-111827?style=flat-square)
![DeviceActivity](https://img.shields.io/badge/DeviceActivity-111827?style=flat-square)
![RevenueCat](https://img.shields.io/badge/RevenueCat-F25A5A?style=flat-square)
![REST API](https://img.shields.io/badge/REST_API-111827?style=flat-square)

🌐 [scrollary.cloud](https://scrollary.cloud)

---

## 💊 MedCall

> **Your medication calls you, so you never miss a dose.**

Most pill reminders are notifications that get swiped away. MedCall rings like an **incoming phone call**: a full-screen alarm that sounds even in Silent mode, where you swipe to confirm you took the dose. Live Activities and widgets show your next dose at a glance.

<table>
  <tr>
    <td align="center" width="20%"><img src="assets/medcall/onboarding.jpg" alt="Onboarding"><br><sub><b>Onboarding</b></sub></td>
    <td align="center" width="20%"><img src="assets/medcall/home.jpg" alt="Today"><br><sub><b>Today</b></sub></td>
    <td align="center" width="20%"><img src="assets/medcall/incoming-call.jpg" alt="Incoming call alarm"><br><sub><b>Incoming call</b></sub></td>
    <td align="center" width="20%"><img src="assets/medcall/medicines.jpg" alt="Medicine list"><br><sub><b>Medicines</b></sub></td>
    <td align="center" width="20%"><img src="assets/medcall/details.jpg" alt="Medicine details"><br><sub><b>Details</b></sub></td>
  </tr>
</table>

**Highlights**

- 📞 **Call-style alarms**: full-screen, ringing reminders built on AlarmKit, with Take, Reject and Snooze actions.
- 🏝 **Live Activities & Dynamic Island**: a live countdown to the next dose on the Lock Screen and in the Dynamic Island.
- 🧩 **Home Screen widgets & controls**: next-dose and daily-progress widgets, with interactive actions through App Intents.
- 🗓 **Flexible schedules**: several doses per day, chosen weekdays, dosage amounts, notes, and pausing/resuming medicines.
- 🔥 **History & streaks**: a per-medicine log of taken and missed doses, with streak tracking.
- 🏗 **Clean architecture**: MVVM with use cases, repositories and a dependency container on top of Core Data.

![SwiftUI](https://img.shields.io/badge/SwiftUI-0e7490?style=flat-square)
![AlarmKit](https://img.shields.io/badge/AlarmKit-0e7490?style=flat-square)
![ActivityKit](https://img.shields.io/badge/ActivityKit-0e7490?style=flat-square)
![WidgetKit](https://img.shields.io/badge/WidgetKit-0e7490?style=flat-square)
![App Intents](https://img.shields.io/badge/App_Intents-0e7490?style=flat-square)
![Core Data](https://img.shields.io/badge/Core_Data-0e7490?style=flat-square)
![StoreKit](https://img.shields.io/badge/StoreKit-0e7490?style=flat-square)
![Combine](https://img.shields.io/badge/Combine-0e7490?style=flat-square)

---

## 🛠 Tech Stack

| Area | Technologies |
|:--|:--|
| **Language & UI** | Swift, SwiftUI, UIKit, Observation, Combine |
| **Persistence** | SwiftData, Core Data, Keychain, App Groups |
| **System integration** | Screen Time (FamilyControls, ManagedSettings, DeviceActivity), AlarmKit, ActivityKit, WidgetKit, App Intents, UserNotifications |
| **Monetization** | StoreKit, RevenueCat |
| **Architecture** | MVVM, Clean Architecture, dependency injection, offline-first sync |
| **Tooling** | Xcode, Git, XCTest / XCUITest, Claude Code |

## 📫 More

- 🎓 **Certificates:** [github.com/iosravandev/certificates](https://github.com/iosravandev/certificates)
- 💻 **GitHub:** [@iosravandev](https://github.com/iosravandev)

<div align="center">

<sub>The source code for these apps is private. This repository shows the products, their features and the technology behind them.</sub>

</div>
