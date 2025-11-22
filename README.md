# Final Year Project (CMP-X301-0)  
## A Personalised Islamic Mobile Application with Real-Time Prayer Scheduling, Qibla Orientation, and Intelligent Mosque Finder

This repository contains all project artefacts, source code, documentation, and progress updates for my Final Year Project at the University of Roehampton.

---

## Project Overview

Millions of Muslims travel, relocate, and work around the world and rely on mobile applications for accurate prayer times, Qibla direction, and access to nearby mosques. Existing applications, such as MuslimPro and Athan, often experience issues with accuracy, adaptability, and personalisation, particularly when users move between cities or across international borders.

This project aims to develop a cross-platform Islamic companion application that adapts intelligently to the user’s real-time location to deliver accurate prayer schedules, reliable Qibla orientation and dynamic mosque discovery worldwide. The system is designed to support Muslims living abroad, international students, travellers and anyone who requires trustworthy religious guidance in unfamiliar environments.

---

## Problem Statement

Muslims frequently rely on mobile applications for accurate prayer times, Qibla direction and mosque discovery. However, existing solutions often struggle with inconsistent accuracy, poor adaptability during travel, and limited personalisation. When users cross borders, enter new cities or move between different time zones, prayer times may shift, Qibla calculations may become unreliable and mosque-finder data may be outdated or unavailable.

These limitations create challenges for Muslims who depend on consistent guidance throughout their day. To address these issues, this project proposes the development of a context-aware Islamic mobile application capable of recalculating prayer times accurately, updating Qibla orientation reliably and offering real-time mosque discovery. The system will dynamically adapt to user movement and preferences to provide an improved and dependable user experience.

---

## Aims and Objectives

### Aims (What)

- Develop a personalised Islamic mobile application that provides real-time, location-based prayer times and Qibla direction.
- Integrate a global mosque-finder system to help users identify nearby mosques with distance, details and navigation support.
- Implement a smart travel mode that automatically recalibrates prayer times and mosque suggestions as users move.
- Ensure cross-platform compatibility for both Android and iOS using a unified development framework.

### Objectives (How)

- Build the mobile application using Flutter for efficient cross-platform development.
- Implement accurate prayer time algorithms using globally accepted Islamic calculation methods.
- Use device GPS, compass sensors and geolocation mathematics to produce accurate Qibla bearings.
- Integrate mapping APIs (Google Maps or OpenStreetMap) for mosque detection and navigation.
- Add personalisation settings such as madhab selection, notification preferences and interface themes.
- Conduct usability testing, performance evaluation and accuracy validation.
- Produce a complete working prototype with documentation and a roadmap for future enhancements.

---

## Core Features

### Minimum Viable Product (MVP)

- Location-based prayer time calculations.
- Accurate Qibla direction using compass and geolocation.
- Mosque finder with distance and navigation features.
- User profile and personalisation settings.
- Prayer reminder notifications.

### Planned Enhancements

- Intelligent travel mode with automatic recalibration.
- Improved mosque data caching for offline use.
- Ramadan-specific features and reminders.
- Optional cloud synchronisation for user preferences.

---

## Technology Stack

- Framework: Flutter (Dart)
- Platforms: Android and iOS
- Mapping Services: Google Maps API or OpenStreetMap
- State Management: To be decided
- Backend (if implemented): REST API, Firebase or Supabase
- Development Tools: Visual Studio Code, Git, GitHub, Android Studio/Xcode

---

## High-Level Architecture

- Presentation Layer: Flutter UI components for prayer times, Qibla screen, mosque map and settings.
- Domain Layer: Core application logic including prayer time calculations and Qibla mathematics.
- Data Layer: Services for API calls, geolocation functions, sensor data and persistent storage.
- Infrastructure Layer: API clients, permission handlers and notification schedulers.

Architecture diagrams and technical documentation will be added as development progresses.

---

## Getting Started (In Progress)

1. Clone the repository:

   ```bash
   git clone https://github.com/rohanxco/FYP.git
   cd FYP
