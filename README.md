# SideCalendar

[中文](https://github.com/sha2kyou/SideCalendar/blob/main/README_ZH.md) | [English](https://github.com/sha2kyou/SideCalendar/blob/main/README.md)

**SideCalendar** is a macOS menu bar app that unifies events and information from various sources (Calendar, Reminders, RSS, GitHub, etc.) into a dynamic screen edge information stream.

> [!WARNING]  
> This software is closed-source. The repository is solely for release distribution and issue tracking.

## Minimum Requirements
macOS 14.0 (Sonoma) or later.

## Installation

### Option 1

You can install **SideCalendar** via Homebrew. If you do not have Homebrew installed, please visit its official website for installation instructions.

Steps:

1. **Add the Homebrew Tap:**
    ```bash
    brew tap sha2kyou/casks
    ```

2. **Install SideCalendar:**
    ```bash
    brew install --cask side-calendar
    ```

### Option 2

Download the latest version manually from the [Release Page](https://github.com/sha2kyou/SideCalendar/releases/latest) and drag the application into the **Applications** folder.

## Installation Notes

If you see the warning *“Apple cannot verify that SideCalendar is free from malware”* on first launch, go to  
`System Settings → Privacy & Security` and select **Open Anyway**.

## Screenshots

<img width="537" height="983" alt="image" src="https://github.com/user-attachments/assets/52fecad7-2b97-4f01-b319-96ac6dd9af41" />

## To-Do List

- [x] Improve the plugin framework  
- [x] Optimize multi-plugin loading performance  
- [ ] Integrate the plugin marketplace and set default plugins  
- [ ] Implement asynchronous multi-plugin loading  
- [ ] Add support for custom plugins  
- [ ] Integrate CalDav plugin  
- [x] Implement readability adjustment settings  
