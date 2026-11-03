<div align="center">

# Psiu!

Availability coordination for small, closed groups of friends.

![Status](https://img.shields.io/badge/status-in%20development-F28C28?style=for-the-badge)
![Kotlin](https://img.shields.io/badge/Kotlin-Jetpack%20Compose-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Java](https://img.shields.io/badge/Java-Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

---

## About

Psiu! is an Android app that helps close friends figure out when they can meet. It is a logistics tool, not a social network: there is no public feed, no user discovery and no in-app chat.

Most plans start with a group chat full of "when are you free?" messages. Psiu! replaces that with a shared view of everyone's availability and one minimal signal for the rare moments when you need someone's attention.

It is the capstone project (TCC) of my Internet Systems degree.

## Features

- **Closed circles.** Groups have no public search and can only be joined by invitation.
- **Availability blocks.** You define time slots and activity types, and choose which circle members can see each one.
- **Google Calendar integration.** The app reads free/busy status only. Event details are never accessed.
- **Compatibility windows.** It finds the time slots where members of a circle are available at the same time.
- **Location sharing.** Sharing expires automatically and can be revoked at any time.
- **Psiu!** A text-free priority signal with cooldown rules, so it does not turn into a constant source of interruptions. The recipient is sent to a call or SMS outside the app instead of an internal chat.

## Design principles

- No feed, no discovery and no chat. The app only helps people coordinate.
- Privacy first: minimal OAuth scopes, expiring location data and per-block visibility.
- Interruption should be rare and deliberate. Green tones are used for availability, and orange is reserved for the Psiu! signal.

## Tech stack

**Android app:** Kotlin, Jetpack Compose, MVVM, Coroutines and Flow, Hilt, Navigation Compose, Retrofit, Room, WorkManager, Firebase Cloud Messaging

**Backend:** Java 21, Spring Boot 3, Spring Security (JWT), Spring Data JPA, Flyway, PostgreSQL, springdoc-openapi

**Quality and infrastructure:** JUnit 5, Mockito, Testcontainers, Docker, GitHub Actions

## Roadmap

- [x] Wireframes and navigation flow
- [ ] Project foundation (CI, theme, navigation)
- [ ] Authentication and closed circles
- [ ] Availability editor
- [ ] Compatibility window algorithm
- [ ] Google Calendar (free/busy) integration
- [ ] Expiring location sharing
- [ ] Psiu! signal with cooldown and push notifications
- [ ] Testing, documentation and demo

## Background

The project draws on research about microcoordination, ambient awareness, location-sharing privacy and notification receptivity. It is positioned against Google Calendar, Doodle, Howbout, Life360 and Yo.

## License

Not defined yet.
