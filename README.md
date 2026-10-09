# 📰 NewsFeeds — Kotlin Multiplatform (KMP) Learning Project

A hands-on **Kotlin Multiplatform (KMP)** mobile application built to explore multiplatform architecture, shared networking, state management, and modern native UI frameworks (**Jetpack Compose** on Android and **SwiftUI** on iOS).

## 🚀 Key Features & Learning Highlights

- **Shared Business Logic (`sharedLogic`)**: Core data fetching, repository pattern, use cases, and view models written once in Kotlin Common.
- **Ktor Client Networking**: Asynchronous HTTP network calls with Ktor (using OkHttp on Android and Darwin on iOS) with KotlinX Serialization and `HttpTimeout` handling.
- **Dependency Injection with Koin**: Shared DI modules for services, repositories, use cases, and view models.
- **State Management**: Reactive state handling using `StateFlow` & Coroutines, seamless Swift integration via SKIE (`co.touchlab.skie`).
- **Clean Architecture**: Separation of concerns into Data (`Service`/`Repository`), Domain (`UseCase`), and Presentation (`ViewModel`/`State`).
- **Native UI**:
  - 🤖 **Android (`androidApp`)**: Jetpack Compose, Material 3, Navigation Compose, Coil 3 for image loading.
  - 🍎 **iOS (`iosApp`)**: SwiftUI integrated with shared KMP view models via Swift `@MainActor` and `@Published`.

## 🛠️ Tech Stack & Libraries

- **Language**: Kotlin 2.x & Swift 5
- **Multiplatform Framework**: Kotlin Multiplatform (KMP)
- **Dependency Injection**: Koin
- **Networking**: Ktor Client (`content-negotiation`, `kotlinx-json`, `HttpTimeout`)
- **Coroutines & Reactive State**: `kotlinx.coroutines`, `StateFlow`
- **Swift / Kotlin Bridge**: SKIE (`co.touchlab.skie`)
- **Android UI**: Jetpack Compose + Material 3 + Coil 3
- **iOS UI**: SwiftUI + `NavigationStack`
