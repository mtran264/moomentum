# Moomentum — Productivity Tracker

A lightweight, personal productivity tracker built with vanilla HTML, CSS, and JavaScript. Designed to help users track daily activities, build consistent habits, and reflect on their progress.

## Overview

Moomentum is a client-side productivity tracker focused on making daily activity tracking simple and accessible. It runs directly in the browser without requiring a backend server or user account.

Productivity data is stored locally in the browser. JSON export and import functionality lets users back up their progress or transfer it to another device.

## Features

- Track daily activities and productivity.
- Review completed activities and daily progress.
- Export saved productivity data as a JSON file.
- Import previously exported JSON files to restore or transfer progress.
- Install the app on supported devices as a Progressive Web App (PWA).
- Run without a backend database or user account.

<!-- Update this list so it only describes features implemented in your current version. -->

## Tech Stack

- **HTML5** — Page structure
- **CSS3** — Styling and responsive layouts
- **Vanilla JavaScript** — Application logic and data management
- **localStorage** — Local browser data persistence
- **JSON** — Productivity data export and import

## Data Storage & Portability

Moomentum stores productivity records in the browser's `localStorage`. The app does not require a backend database or account.

### Back Up Your Data

1. Use the app's export feature to download your productivity data as a JSON file.
2. Save the file somewhere secure, such as your computer or a trusted backup location.

### Restore or Transfer Your Data

1. Open Momentum on the destination device.
2. Use the import feature to select a previously exported JSON file.
3. Follow the app's import workflow to restore your saved progress.

### Important Notes

- Data is not automatically synchronized between devices.
- Clearing browser or website data may remove locally stored progress.
- Export backups regularly to help preserve your records.
- Keep exported JSON files secure, especially if they contain personal information.
- Check how importing works in your app before proceeding, since it may replace or merge existing records depending on your implementation.

## Progressive Web App (PWA)

Moomentum can be installed on supported devices through a compatible browser and accessed from the device's Home Screen.

Installing the app does not automatically sync data between your phone and computer. Use JSON export and import to transfer your progress manually.

## Getting Started

### Prerequisites

A modern web browser. No build tools are required unless your project uses additional dependencies.

## Roadmap

- [ ] Additional data visualizations
- [ ] Enhance the responsive mobile experience
- [ ] Themes and Dark Mode

## About

Moomentum is an independent personal project exploring productivity trackers, client-side data management, and UX design.

---

*Built as a personal project.*
