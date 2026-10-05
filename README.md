# A Client/Server Example - Kotlin Android / NestJS (2026)

This repository corresponds to the course **"A Client/Server Example - Kotlin Android / NestJS (2026)"**, published at:

**https://stahe.github.io/en-kotlin-android-nestjs-oct-2026/**

## Overview

This document adapts the educational app **RdvMedecins** (a doctor’s appointment scheduling app), which has already been covered in courses on Angular, React, Vue.js, and Flutter, into a native Android app. It presents an **Android** version here: a client written in **Kotlin** using **Jetpack Compose** (Material 3), which relies on a **NestJS** (TypeScript) server exposing a JSON API protected by JWT authentication (ADMIN / USER roles).

This document provides a step-by-step guide following the progression of the course [An Example Client/Server - Flutter / NestJS (2026)](https://stahe.github.io/en-flutter-nestjs-sept-2026/), from which it borrows the server, the database, and the client architecture: each Jetpack Compose concept is linked to its Flutter equivalent. The basics of the Kotlin language are covered in the [Kotlin course](https://stahe.github.io/kotlin-oct-2026/).

The course covers:

- setting up the development environment (Android Studio, Android SDK, Gradle, creating a Compose project, emulator, and Android phone);
- installing and running the app’s NestJS server (MySQL database, configuration, testing with a browser and with Postman);
- an introduction to Android and Jetpack Compose (activities, `@Composable` functions, state and recomposition, `CompositionLocal`, coroutines, lifecycle, and `ViewModel`);
- a detailed, file-by-file walkthrough of the Kotlin client for the RdvMedecins app (OkHttp, kotlinx.serialization, SharedPreferences, Material 3);
- running the app on an emulator and on a phone, addressing mobile-specific pitfalls (server address, `adb reverse`, unencrypted HTTP traffic, screen rotation, narrow screens), building an APK, and an overview of Kotlin Multiplatform;
- a conclusion on what was built and suggestions for further exploration.

## Authors

- **Lead Author:** IA Claude (Anthropic)
- **Reviewer:** [Serge Tahé](https://stahe.github.io)
