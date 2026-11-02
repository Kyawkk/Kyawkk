<picture>
  <source media="(prefers-color-scheme: dark)" srcset=".github/assets/banner-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset=".github/assets/banner-light.svg">
  <img alt="Kyaw Zin Linn, Software Engineer. Animated banner cycling through Android Engineer, Kotlin Multiplatform, and NFC, POS and RFID integrations." src=".github/assets/banner-light.svg" width="100%">
</picture>

<div align="center">

**Software Engineer | Android & Kotlin Multiplatform**

I build Kotlin and Compose apps with a careful eye for architecture and UI, including apps that integrate NFC cards, POS terminals and RFID readers.
<br>Software Developer at SCITGoC (Singapore) · working remotely from Da Nang, Vietnam

[![Portfolio](https://img.shields.io/badge/Portfolio-7F52FF?style=for-the-badge&logo=firefox&logoColor=white)](https://kyawzinlinn.vercel.app) [![Email](https://img.shields.io/badge/Email-C5372A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kzin5717@gmail.com?subject=Hello%20from%20GitHub) [![GitHub repositories](https://img.shields.io/badge/GitHub-30363D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kyawkk?tab=repositories)

</div>

## 👋 About

- 🛠️ Building Android apps since 2020, from freelance Play Store apps to enterprise handheld-device software.
- 🧩 Particular interests: modular architecture, offline-first data, and integrating hardware reliably.
- 🔭 Currently building cross-platform apps with Compose Multiplatform and exploring newer Compose APIs, such as [shared element transitions](https://github.com/Kyawkk/Jetpack_Compose_New_APIs).

## 🧭 Engineering focus

- 🏗️ **Native Android architecture.** Modular Compose apps with MVVM, Clean Architecture and Hilt, so features can grow without tangling the codebase.
- 📡 **Hardware integration.** Connecting apps to NFC cards, POS terminals, RFID readers and receipt printers on constrained handheld devices.
- 💳 **Payments and transactions.** Payment-gateway and card-tap flows, from charge to receipt.
- 📶 **Offline-first data.** Local caching with Room and background sync, so apps stay usable on unreliable networks.
- 🌐 **Cross-platform with Compose Multiplatform.** One shared Compose UI across Android and iOS.

## 🚀 Featured projects

### [Handheld POS and NFC bus ticketing](https://kyawzinlinn.vercel.app/work/handheld-pos-nfc-bus-ticketing)

Android point-of-sale app for bus fare collection on handheld terminals.

- **Highlights:** Coordinates NFC card reads, payment confirmation and thermal receipt printing as one sequential flow on Kotlin Coroutines, with an offline-first queue for poor connectivity.
- **Links:** [Case study](https://kyawzinlinn.vercel.app/work/handheld-pos-nfc-bus-ticketing)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Coroutines](https://img.shields.io/badge/Coroutines-6E40C9?style=flat-square&logo=kotlin&logoColor=white) ![NFC DESFire EV3](https://img.shields.io/badge/NFC_DESFire_EV3-1565C0?style=flat-square&logo=nfc&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white) ![ESC/POS](https://img.shields.io/badge/ESC%2FPOS-57606A?style=flat-square) ![Source not public](https://img.shields.io/badge/Source_not_public-57606A?style=flat-square)

### [Enterprise RFID and POS inventory](https://kyawzinlinn.vercel.app/work/enterprise-rfid-inventory)

Android app that connects handheld RFID readers to a cloud backend for asset tracking and point-of-sale.

- **Highlights:** Handles high-frequency tag reads without blocking the UI, using a buffered `SharedFlow` pipeline that sends batched updates to Compose. Includes payment-gateway processing and Supabase sync.
- **Links:** [Case study](https://kyawzinlinn.vercel.app/work/enterprise-rfid-inventory)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![SharedFlow](https://img.shields.io/badge/SharedFlow-6E40C9?style=flat-square&logo=kotlin&logoColor=white) ![Zebra RFID SDK](https://img.shields.io/badge/Zebra_RFID_SDK-57606A?style=flat-square) ![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=flat-square&logo=ktor&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-1F8A5B?style=flat-square&logo=supabase&logoColor=white) ![Source not public](https://img.shields.io/badge/Source_not_public-57606A?style=flat-square)

### [Forge: AI workout logger](https://kyawzinlinn.vercel.app/work/forge)

Workout logging app for Android and iOS that generates routines with AI and adapts them to logged sessions.

- **Highlights:** One shared Compose UI, multi-module Clean Architecture with MVI, AI plans streamed into the UI over Kotlin Flow, and offline-first drafts with background sync.
- **Links:** [Case study](https://kyawzinlinn.vercel.app/work/forge)

![Compose Multiplatform](https://img.shields.io/badge/Compose_Multiplatform-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![MVI](https://img.shields.io/badge/MVI-57606A?style=flat-square) ![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=flat-square&logo=ktor&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-1F8A5B?style=flat-square&logo=supabase&logoColor=white) ![In development](https://img.shields.io/badge/In_development-9A6700?style=flat-square) ![Source not public](https://img.shields.io/badge/Source_not_public-57606A?style=flat-square)

### [Spec-Comparer](https://github.com/Kyawkk/Spec-Comparer)

Android app for comparing smartphones, SoCs, laptops and laptop CPUs side by side.

- **Highlights:** Feature modules (`home`, `search`, `details`, `compare`) built on shared core modules (`data`, `domain`, `model`, `network`, `design-system`, `components`). Specs are parsed with Jsoup; the repository states this is for educational use only.
- **Links:** [Source](https://github.com/Kyawkk/Spec-Comparer) · [Release v1.0.0](https://github.com/Kyawkk/Spec-Comparer/releases/tag/v1.0.0)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Hilt](https://img.shields.io/badge/Hilt-1F883D?style=flat-square&logo=android&logoColor=white) ![Jsoup](https://img.shields.io/badge/Jsoup-57606A?style=flat-square) ![Open source](https://img.shields.io/badge/Open_source-1F883D?style=flat-square)

<p>
  <img src=".github/assets/spec-comparer-home.webp" alt="Spec-Comparer home screen with four categories: smartphones, SoC, laptop CPUs and laptops" width="45%">
  <img src=".github/assets/spec-comparer-compare.webp" alt="Spec-Comparer phone comparison screen" width="45%">
</p>

### [Weather_App](https://github.com/Kyawkk/Weather_App)

Android weather app with hourly, daily and five-day forecasts and an offline cache.

- **Highlights:** Split into `core-*` modules (`data`, `database`, `network`, `navigation`, `design`, `ui`) and `feature-*` modules (`location`, `weather`).
- **Links:** [Source](https://github.com/Kyawkk/Weather_App)

![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Hilt](https://img.shields.io/badge/Hilt-1F883D?style=flat-square&logo=android&logoColor=white) ![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=flat-square) ![Room](https://img.shields.io/badge/Room-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Open source](https://img.shields.io/badge/Open_source-1F883D?style=flat-square)

**More:** [SMS_Sender](https://github.com/Kyawkk/SMS_Sender) (scheduled messages and auto-reply with WorkManager) · [MoviesApp](https://github.com/Kyawkk/MoviesApp) (offline-cached movie browser) · [Beer_App](https://github.com/Kyawkk/Beer_App) (Paging 3, offline-first)

## 🧰 Tech stack

**Languages and UI**<br>
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Kotlin Multiplatform](https://img.shields.io/badge/Kotlin_Multiplatform-7F52FF?style=flat-square&logo=kotlin&logoColor=white) ![Java](https://img.shields.io/badge/Java-C66F00?style=flat-square&logo=openjdk&logoColor=white) ![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white) ![Compose Multiplatform](https://img.shields.io/badge/Compose_Multiplatform-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)

**Architecture**<br>
![MVVM](https://img.shields.io/badge/MVVM-57606A?style=flat-square) ![MVI](https://img.shields.io/badge/MVI-57606A?style=flat-square) ![Clean Architecture](https://img.shields.io/badge/Clean_Architecture-57606A?style=flat-square) ![Multi-module Gradle](https://img.shields.io/badge/Multi--module_Gradle-3A7D8C?style=flat-square&logo=gradle&logoColor=white) ![Hilt](https://img.shields.io/badge/Hilt-1F883D?style=flat-square&logo=android&logoColor=white)

**Data and networking**<br>
![Coroutines and Flow](https://img.shields.io/badge/Coroutines_and_Flow-6E40C9?style=flat-square&logo=kotlin&logoColor=white) ![Room](https://img.shields.io/badge/Room-003B57?style=flat-square&logo=sqlite&logoColor=white) ![Retrofit](https://img.shields.io/badge/Retrofit-48B983?style=flat-square) ![Ktor](https://img.shields.io/badge/Ktor-087CFA?style=flat-square&logo=ktor&logoColor=white) ![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=flat-square&logo=graphql&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-1F8A5B?style=flat-square&logo=supabase&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-D84315?style=flat-square&logo=firebase&logoColor=white) ![WorkManager](https://img.shields.io/badge/WorkManager-57606A?style=flat-square) ![Paging 3](https://img.shields.io/badge/Paging_3-57606A?style=flat-square)

**Devices**<br>
![NFC DESFire EV3](https://img.shields.io/badge/NFC_DESFire_EV3-1565C0?style=flat-square&logo=nfc&logoColor=white) ![POS terminal SDKs](https://img.shields.io/badge/POS_terminal_SDKs-57606A?style=flat-square) ![Zebra RFID SDK](https://img.shields.io/badge/Zebra_RFID_SDK-57606A?style=flat-square) ![ESC/POS printing](https://img.shields.io/badge/ESC%2FPOS_printing-57606A?style=flat-square)

**Tooling**<br>
![Android Studio](https://img.shields.io/badge/Android_Studio-4285F4?style=flat-square&logo=androidstudio&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-30363D?style=flat-square&logo=github&logoColor=white)

## 📊 GitHub activity

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kyawkk&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kyawkk&theme=github">
  <img alt="GitHub profile summary for Kyawkk: public repositories, contributions over the last year and contribution graph" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Kyawkk&theme=github" width="100%">
</picture>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Kyawkk&theme=github_dark">
  <source media="(prefers-color-scheme: light)" srcset="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Kyawkk&theme=github">
  <img alt="Top languages by commit for Kyawkk, led by Kotlin" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Kyawkk&theme=github" width="50%">
</picture>

</div>

## 💼 Career

- **2024 – present** · Software Developer, SCITGoC (Singapore)
- **2023 – 2024** · Android Developer, E-Tag RFID (Singapore)
- **2022 – 2023** · Android Developer, Light Idea Software Company (Myanmar)
- **2020 – 2022** · Freelance Android Developer (remote)

## 📬 Connect

<div align="center">

[![Portfolio](https://img.shields.io/badge/Portfolio-7F52FF?style=for-the-badge&logo=firefox&logoColor=white)](https://kyawzinlinn.vercel.app) [![Email](https://img.shields.io/badge/Email-C5372A?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kzin5717@gmail.com?subject=Hello%20from%20GitHub) [![GitHub repositories](https://img.shields.io/badge/GitHub-30363D?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Kyawkk?tab=repositories)

<picture>
  <img alt="Decorative animated wave" src=".github/assets/footer.svg" width="100%">
</picture>

</div>
