<div align="center">

# 👋 Psiu!

**Find the right moment to meet — without the noise of a social network.**

![Status](https://img.shields.io/badge/status-in%20development-F28C28?style=for-the-badge)
![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

---

## 🌿 About

**Psiu!** is an Android app for coordinating availability inside **small, closed circles of close friends**. It is a logistics utility, not a social network: no public feed, no user discovery and no in-app chat.

Organizing a get-together usually means a long group chat full of "when are you free?". Psiu! replaces that back-and-forth with a calm, privacy-first way to see when people are available, and a single minimal signal to get someone's attention when it really matters.

> Built as a final-year capstone project (TCC) for the Internet Systems program.

## ✨ Core features

| | Feature | What it does |
|---|---|---|
| 🔒 | **Closed circles** | Private groups with no public search. Joining is invite-only. |
| 🗓️ | **Availability blocks** | Define time slots and activity types, with granular control over who in the circle can see each block. |
| 🔗 | **Google Calendar integration** | Reads *free/busy* only. The content of your events is never exposed. |
| 🤝 | **Compatibility windows** | Automatically finds the time slots where circle members are available together. |
| 📍 | **Reversible location sharing** | Location sharing that expires on its own and can be revoked at any moment. |
| 🔔 | **Psiu!** | A text-free, priority attention signal with cooldown rules, so it never becomes a source of interruptions. It nudges the recipient out of the app (call or SMS) instead of opening an in-app chat. |

## 🧭 Design principles

- **No feed, no discovery, no chat.** The app does one thing: help people coordinate.
- **Privacy by design.** Minimal OAuth scopes, expiring location data and per-block visibility.
- **Calm by default.** Interruption is rare and deliberate. The *sage* green palette represents calm availability, and the *ember* orange is reserved for the Psiu! signal only.

## 🛠️ Tech stack

**Android app**
- Kotlin · Jetpack Compose · MVVM
- Coroutines & Flow · Hilt · Navigation Compose
- Retrofit · Room · WorkManager · Firebase Cloud Messaging

**Backend**
- Java 21 · Spring Boot 3
- Spring Security (JWT) · Spring Data JPA · Flyway
- PostgreSQL · springdoc-openapi

**Quality & infrastructure**
- JUnit 5 · Mockito · Testcontainers
- Docker · GitHub Actions

## 🗺️ Roadmap

- [x] Wireframes and navigation flow
- [ ] Project foundation (CI, theme, navigation)
- [ ] Authentication and closed circles
- [ ] Availability editor
- [ ] Compatibility window algorithm
- [ ] Google Calendar (free/busy) integration
- [ ] Expiring location sharing
- [ ] Psiu! signal with cooldown and push notifications
- [ ] Testing, documentation and demo

## 📚 Academic background

The project is grounded in research on microcoordination, ambient awareness, location-sharing privacy and notification receptivity, and it positions itself against tools such as Google Calendar, Doodle, Howbout, Life360 and Yo.

## 📄 License

License to be defined.

---

<div align="center">

Made with care for people who just want to hang out. 🌱

</div>
