<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
  <img alt="KZL monogram followed by a line connecting three layer nodes" src="assets/header-light.svg" width="100%">
</picture>

# Kyaw Zin Linn

**Android Engineer** · Kotlin · Jetpack Compose · NFC, POS and RFID hardware

Software Developer at SCITGoC · working remotely from Da Nang, Vietnam

[Portfolio](https://kyawzinlinn.vercel.app) · [Email](mailto:kzin5717@gmail.com?subject=Hello%20from%20GitHub)
<!-- LinkedIn: add `· [LinkedIn](https://www.linkedin.com/in/<handle>)` once the exact URL is confirmed. -->

</div>

## About

- Building Android apps since 2020, in Kotlin and Jetpack Compose, structured with MVVM and Clean Architecture.
- Professional work centres on hardware-connected apps: NFC transit cards, POS terminals and RFID readers, plus payment-gateway integration.
- Currently exploring Compose Multiplatform and newer Compose APIs, such as [shared element transitions](https://github.com/Kyawkk/Jetpack_Compose_New_APIs).

## Hands-on work

Apps built around real hardware. Source is not public for these; case studies are on my [portfolio](https://kyawzinlinn.vercel.app).

- **Handheld POS and NFC bus ticketing.** Android app for fare collection on a constrained POS terminal: NFC (DESFire EV3) card taps, payment, thermal receipt printing, and trip management over GraphQL.
- **Enterprise RFID and POS inventory.** Android app that connects handheld Zebra RFID readers to a cloud backend for asset tracking and point-of-sale, with real-time tag scanning and payment-gateway processing.
- **Forge, an AI workout logger** *(in development)*. Compose Multiplatform app for Android and iOS that generates and adapts training routines.

## Technical focus

| Area | Tools and practices |
| :--- | :--- |
| **UI** | Jetpack Compose, Material Design, Kotlin, Java |
| **Architecture** | MVVM, Clean Architecture, multi-module Gradle projects, Hilt (Dagger), manual dependency injection |
| **Data and background work** | Coroutines and Flow, Room, Retrofit, WorkManager, Paging 3, GraphQL, Firebase, Ktor, Supabase |
| **Devices and payments** | NFC smart cards, POS terminal SDKs, Zebra RFID SDK, ESC/POS receipt printing, payment gateways |
| **Tooling** | Android Studio, Git, GitHub |

## Open-source projects

### [Spec-Comparer](https://github.com/Kyawkk/Spec-Comparer)

Compare smartphones, SoCs, laptops and laptop CPUs side by side, using specifications scraped from the web.

- Feature modules (`home`, `search`, `details`, `compare`) sit on shared core modules (`data`, `domain`, `model`, `network`, `design-system`, `components`).
- Built with Compose, Hilt, MVVM and Clean Architecture. Spec data is parsed with Jsoup; the repository states this is for educational use only.
- **Stack:** `Kotlin` · `Jetpack Compose` · `Hilt` · `Jsoup`
- **Links:** [Source](https://github.com/Kyawkk/Spec-Comparer) · [Release v1.0.0](https://github.com/Kyawkk/Spec-Comparer/releases/tag/v1.0.0)

<table>
  <tr>
    <td><img src="https://raw.githubusercontent.com/Kyawkk/Spec-Comparer/master/screenshots/one.png" alt="Spec-Comparer home screen with four categories: smartphones, SoC, laptop CPUs and laptops" width="200"></td>
    <td><img src="https://raw.githubusercontent.com/Kyawkk/Spec-Comparer/master/screenshots/four.png" alt="Spec-Comparer phone comparison screen" width="200"></td>
  </tr>
</table>

### [Weather_App](https://github.com/Kyawkk/Weather_App)

Weather forecasts for a chosen location, with hourly, daily and five-day views and an offline cache.

- Split into `core-*` modules (`data`, `database`, `network`, `navigation`, `design`, `ui`) and `feature-*` modules (`location`, `weather`).
- **Stack:** `Kotlin` · `Jetpack Compose` · `Hilt` · `Retrofit` · `Room` · `Coroutines`
- **Links:** [Source](https://github.com/Kyawkk/Weather_App)

### [SMS_Sender](https://github.com/Kyawkk/SMS_Sender)

Schedule text messages and set up automatic replies to incoming SMS.

- Clean Architecture with presentation, domain and data layers. Scheduled sends run on WorkManager and a BroadcastReceiver handles incoming messages.
- Dependencies are wired by hand, without a DI framework.
- **Stack:** `Kotlin` · `Jetpack Compose` · `Room` · `WorkManager`
- **Links:** [Source](https://github.com/Kyawkk/SMS_Sender)

**More:** [MoviesApp](https://github.com/Kyawkk/MoviesApp) (offline-cached movie browser) · [Beer_App](https://github.com/Kyawkk/Beer_App) (Paging 3, offline-first) · [Jetpack_Compose_New_APIs](https://github.com/Kyawkk/Jetpack_Compose_New_APIs) (experiments with new Compose APIs)

## Experience

- **2024 – present** · Software Developer, SCITGoC (Singapore)
- **2023 – 2024** · Android Developer, E-Tag RFID (Singapore)
- **2022 – 2023** · Android Developer, Light Idea (Myanmar)
- **2020 – 2022** · Freelance Android Developer (remote)

## Contact

Email [kzin5717@gmail.com](mailto:kzin5717@gmail.com?subject=Hello%20from%20GitHub) or see my [portfolio](https://kyawzinlinn.vercel.app).
