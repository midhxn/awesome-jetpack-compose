# 🚀 Awesome Jetpack Compose

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d73059c/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![Jetpack Compose](https://img.shields.io/badge/Compose-1.10%2B-4285F4?style=flat&logo=android&logoColor=white)](https://developer.android.com/jetpack/compose)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.0%2B-7F52FF?style=flat&logo=kotlin&logoColor=white)](https://kotlinlang.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated list of resources, libraries, and tools for **Jetpack Compose**, the modern Android (and Multiplatform) UI toolkit. Updated for the **2026 ecosystem** (Material 3, Navigation Type Safety, CMP Stable).

## Table of Contents

- [Getting Started](#-getting-started)
- [Compose Multiplatform (CMP)](#-compose-multiplatform-cmp)
- [UI Components & Libraries](#-ui-components--libraries)
  - [Images & Media](#images--media)
  - [Charts & Visualization](#charts--visualization)
  - [Rich Text & Markdown](#rich-text--markdown)
  - [Calendar & Date](#calendar--date)
  - [Maps & Location](#maps--location)
  - [Widgets (Glance)](#widgets-glance)
- [Architecture & State](#-architecture--state)
  - [Navigation](#navigation)
  - [Dependency Injection](#dependency-injection)
  - [State Management](#state-management)
- [System Integrations](#-system-integrations)
  - [Permissions](#permissions)
  - [Camera & Video](#camera--video)
- [Theming & Design](#-theming--design)
- [Animations](#-animations)
- [Data & Networking](#-data--networking)
- [Wear OS & TV](#-wear-os--tv)
- [Testing](#-testing)
- [Tools & Utilities](#-tools--utilities)
- [Sample Projects](#-sample-projects)
- [Community](#-community)

---

## 🏁 Getting Started

*Essential resources to begin your journey.*

- [Official Jetpack Compose Documentation](https://developer.android.com/jetpack/compose) - The authoritative source.
- [Compose Guided Pathway](https://developer.android.com/courses/pathways/compose) - Google's official step-by-step course with badges.
- [Thinking in Compose](https://developer.android.com/jetpack/compose/mental-model) - Critical reading to understand the declarative mental model.
- [Jetpack Compose Roadmap](https://developer.android.com/jetpack/androidx/compose-roadmap) - Official roadmap of Stable, Beta, and Alpha APIs.
- [Material 3 Design Spec](https://m3.material.io/) - The design system used by default in modern Compose.

[↑ Back to Top](#table-of-contents)

## 🌍 Compose Multiplatform (CMP)

*Share UI across Android, iOS, Desktop, and Web. This is the future of Compose.*

- [Compose Multiplatform](https://github.com/JetBrains/compose-multiplatform) - The official repository by JetBrains.
- [KMP Awesome](https://github.com/terrakok/kmp-awesome) - A dedicated list for Kotlin Multiplatform libraries.
- [Voyager](https://github.com/adrielcafe/voyager) - A multiplatform navigation library.
- [ImageLoader](https://github.com/qdsfdhvh/compose-imageloader) - A Compose Multiplatform image loading library.
- [Moko Resources](https://github.com/icerockdev/moko-resources) - Share strings, images, colors, and fonts across platforms.

[↑ Back to Top](#table-of-contents)

## 🎨 UI Components & Libraries

### Core UI
- [Material 3 Compose](https://developer.android.com/jetpack/compose/designsystems/material3) - The standard UI library.
- [Accompanist](https://github.com/google/accompanist) - Experimental features (Pager, Permissions, WebViews). *Note: Many parts are now in official AndroidX.*
- [Compose Icons](https://github.com/DevSrSouza/compose-icons) - FontAwesome, Feather, Tabler, and Eva icons for Compose.
- [Telephoto](https://github.com/saket/telephoto) - Zoomable images and media viewers.

### Images & Media
- [Coil](https://coil-kt.github.io/coil/compose/) - **The Standard.** Kotlin-first, lightweight image loading.
- [Landscapist](https://github.com/skydoves/landscapist) - Highly optimized image loading (supports Glide, Coil, Fresco).
- [Sketch](https://github.com/panpf/sketch) - A powerful and comprehensive image loader for Compose.

### Charts & Visualization
- [Vico](https://github.com/patrykandpatrick/vico) - A lightweight, extensible chart library for Compose and Views.
- [YCharts](https://github.com/code-with-the-keen/YCharts) - Easy-to-use graphs (Line, Bar, Pie, Donut).
- [Compose Charts](https://github.com/tehras/charts) - Simple charts for basic needs.

### Rich Text & Markdown
- [Compose Richtext](https://github.com/halilibo/compose-richtext) - Advanced rich text formatting and Markdown rendering.
- [Jeziellago Markdown](https://github.com/jeziellago/compose-markdown) - A simple Markdown renderer.

### Calendar & Date
- [Compose Calendar](https://github.com/boguszpawlowski/ComposeCalendar) - A customizable calendar composable.
- [Kalendar](https://github.com/himanshoe/Kalendar) - A distinct and easy-to-use calendar library.

### Maps & Location
- [Maps Compose](https://github.com/googlemaps/android-maps-compose) - Official Jetpack Compose components for the Google Maps SDK.
- [OsmDroid Compose](https://github.com/tech-kittens/osmdroid-compose) - OpenStreetMap implementation for Compose.

### Widgets (Glance)
- [Jetpack Glance](https://developer.android.com/jetpack/compose/glance) - Build App Widgets using Compose-style APIs.
- [Glance Experimental Tools](https://google.github.io/accompanist/glance/) - Tools to simplify Glance development.

[↑ Back to Top](#table-of-contents)

## 🏗 Architecture & State

### Navigation
- [Navigation Compose](https://developer.android.com/jetpack/compose/navigation) - Official Google library. *Updated for Type Safety in 2025.*
- [Decompose](https://github.com/arkivanov/Decompose) - Advanced lifecycle and navigation management, ideal for KMP.
- [Compose Destinations](https://github.com/raamcosta/compose-destinations) - Annotation processing wrapper for type-safe navigation.
- [Appyx](https://github.com/bumble-tech/appyx) - Model-driven navigation with gesture control (Bumble).

### Dependency Injection
- [Hilt](https://developer.android.com/training/dependency-injection/hilt-jetpack) - **The Standard for Android.** Built on Dagger, fully integrated with Compose/ViewModel.
- [Koin](https://insert-koin.io/docs/reference/koin-compose/compose) - **The Standard for KMP.** A pragmatic, lightweight DSL dependency injection framework.
- [Anvil](https://github.com/square/anvil) - A compiler plugin for Dagger 2 to make dependency injection easier (Square).

### State Management
- [Circuit](https://github.com/slackhq/circuit) - A unidirectional data flow architecture (by Slack) separating UI from State.
- [Molecule](https://github.com/cashapp/molecule) - Build your state using Compose logic itself.
- [Mavericks](https://github.com/airbnb/mavericks) - Airbnb’s MVI framework.
- [Orbit MVI](https://github.com/orbit-mvi/orbit-mvi) - A simple MVI framework with Coroutines.

[↑ Back to Top](#table-of-contents)

## 🔗 System Integrations

### Permissions
- [Accompanist Permissions](https://google.github.io/accompanist/permissions/) - (Or its successor) The easiest way to handle runtime permissions in Compose.
- [KPermissions](https://github.com/NicoNicola/KPermissions) - A lightweight Kotlin library for permissions.

### Camera & Video
- [CameraX Compose](https://developer.android.com/jetpack/androidx/releases/camera) - Check the `androidx.camera:camera-viewfinder-compose` artifact.
- [ExoPlayer (Media3)](https://developer.android.com/media/media3) - The standard for playing video; easily wrapped in `AndroidView`.

[↑ Back to Top](#table-of-contents)

## 🖌 Theming & Design

- [Material Theme Builder](https://material-foundation.github.io/material-theme-builder/) - Generate `Theme.kt` from a seed color.
- [Showkase](https://github.com/airbnb/Showkase) - A "Storybook" for Android; view all your `@Preview` composables in one app.
- [Compose Shadow](https://github.com/adamglin0/compose-shadow) - Advanced custom shadows.

[↑ Back to Top](#table-of-contents)

## ✨ Animations

- [Lottie Compose](https://github.com/airbnb/lottie/blob/master/android-compose.md) - Render After Effects animations.
- [Seekable Animation](https://github.com/UseAnimation/SeekableAnimation) - Seek through standard Compose animations.
- [Compose Motion](https://github.com/fornewid/compose-motion) - Material transitions (Container transform, etc.).

[↑ Back to Top](#table-of-contents)

## 💾 Data & Networking

- [Retrofit](https://github.com/square/retrofit) - Type-safe HTTP client.
- [Ktor Client](https://ktor.io/) - Multiplatform networking client.
- [Room](https://developer.android.com/training/data-storage/room) - Local database with Flow support.
- [DataStore](https://developer.android.com/topic/libraries/architecture/datastore) - Replacement for SharedPreferences.
- [SQLDelight](https://github.com/cashapp/sqldelight) - Generate Kotlin from SQL; excellent for KMP.

[↑ Back to Top](#table-of-contents)

## ⌚ Wear OS & TV

- [Compose for Wear OS](https://developer.android.com/training/wearables/compose) - Build UI for smartwatches.
- [Horologist](https://github.com/google/horologist) - Extensions for Wear OS (Media, Volume control, etc.).
- [Compose for TV](https://developer.android.com/training/tv/playback/compose) - Build UI for Android TV.

[↑ Back to Top](#table-of-contents)

## 🧪 Testing

- [Compose UI Test](https://developer.android.com/jetpack/compose/testing) - Official testing artifact.
- [Maestro](https://maestro.mobile.dev/) - **Recommended.** The simplest UI testing framework (YAML based).
- [Paparazzi](https://github.com/cashapp/paparazzi) - Render screens without an emulator for screenshot testing.
- [Roborazzi](https://github.com/takahirom/roborazzi) - Robust screenshot testing with Robolectric.
- [Turbine](https://github.com/cashapp/turbine) - Testing library for Kotlin Flows.

[↑ Back to Top](#table-of-contents)

## 🛠 Tools & Utilities

- [Relay for Figma](https://relay.material.io/) - Design-to-code handoff.
- [Detekt Compose Rules](https://github.com/mrmans0n/compose-rules) - Static analysis to catch Compose errors (e.g. passing ViewModels down).
- [KSP](https://github.com/google/ksp) - Faster annotation processing.
- [Layout Inspector](https://developer.android.com/studio/debug/layout-inspector) - Built into Android Studio to debug UI hierarchies.

[↑ Back to Top](#table-of-contents)

## 📱 Sample Projects

- [Now In Android (NiA)](https://github.com/android/nowinandroid) - Google's gold-standard sample app.
- [Pokedex](https://github.com/skydoves/Pokedex) - Showcases Hilt, Flow, Room, and custom motion.
- [CatchUp](https://github.com/ZacSweers/CatchUp) - Real-world app by Zac Sweers (Circuit, Anvil).
- [Tivi](https://github.com/chrisbanes/tivi) - TV show tracking app by Chris Banes.
- [Compose Spotify](https://github.com/Gurupreet/ComposeSpotify) - A clone of the Spotify UI.

[↑ Back to Top](#table-of-contents)

## 👥 Community

- [Kotlin Slack](https://kotlinlang.slack.com/) - Channel `#compose`.
- [Android Worldwide](https://discord.gg/android-worldwide) - Discord server.
- [r/JetpackCompose](https://www.reddit.com/r/JetpackCompose/) - Reddit community.

---

## 🤝 Contributing

Contributions are welcome

## ⚖️ License

Distributed under the MIT License. See `LICENSE` for more information.
