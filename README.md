# LeagueSkinChanger

LeagueSkinChanger is a Windows desktop application for managing League of Legends skins.

The main goal of the project is to provide a simple way to browse skins, select the ones you want to use, and manage custom skins from one place.

> This repository contains documentation, screenshots and official releases only. The source code is not included.

<p align="center">
  <img src="assets/showcase.png" alt="LeagueSkinChanger">
</p>

https://github.com/kaplumbaga01x/LeagueSkin/releases

## Features

### Skin Browser

Browse champions and their available skins from a single interface.

### Skin Selection

Select the skin you want to use and manage your current selection without dealing with a complicated interface.

### Favorites

Save your favorite skins so you can easily find them again later.

### Custom Skins

LeagueSkinChanger supports custom `.fantome` skin packages.

You can add and manage your own custom skins through the application.

### Party Mode

Party Mode allows LeagueSkinChanger to be used together with other players in the same party.

### Automation

LeagueSkinChanger includes optional automation features for the League Client:

- Auto Accept
- Auto Pick
- Auto Ban

These features can be enabled or disabled individually.

### League Client Detection

LeagueSkinChanger can automatically detect the League Client when it is running.

### Updates

LeagueSkinChanger checks GitHub Releases for new versions.

When a new version is available, the application can download and install the update automatically.

---

## Screenshots

### Dashboard

![Dashboard](screenshots/dashboard.png)

### Champion & Skin Browser

![Champion Browser](screenshots/champions.png)

### Party Mode

![Party Mode](screenshots/party-mode.png)

### Automation

![Automation](screenshots/automation.png)

---

## Download

The latest version of LeagueSkinChanger is available on the GitHub Releases page.

**[Download LeagueSkinChanger](../../releases/latest)**

The releases contain the official compiled Windows builds and release notes.

The source code is not included in this repository.

---

## Requirements

- Windows 10 or later
- League of Legends installed
- League Client for client-related features

### External Components

Some functionality of LeagueSkinChanger requires the following external components:

- `ltk_patcher_dll.dll`
- `ltk_patcher_host.exe`

These files are **not included in this repository or in the official LeagueSkinChanger releases**.

LeagueSkinChanger does not provide, host, mirror, or redistribute these files.

Users who require these components must obtain them independently from their legitimate source and place them in the appropriate application directory.

> Do not download these files from unofficial or modified sources.

---

## Updating

LeagueSkinChanger uses GitHub Releases as its update channel.

The application periodically checks the latest GitHub Release.

If a newer version is available:

1. LeagueSkinChanger detects the new version.
2. The update is downloaded automatically.
3. The application asks to restart when the update is ready.
4. The new version is installed.
5. LeagueSkinChanger starts again.

Updates are distributed through GitHub Releases.

---

## Repository Structure

```text
LeagueSkinChanger/
├── README.md
├── assets/
│   └── showcase.png
├── screenshots/
│   ├── dashboard.png
│   ├── champions.png
│   ├── party-mode.png
│   └── automation.png
└── .github/
    └── workflows/
