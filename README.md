# SideCalendar

[中文](https://github.com/sha2kyou/SideCalendar/blob/main/README_ZH.md) | [English](https://github.com/sha2kyou/SideCalendar/blob/main/README.md)

**SideCalendar** is a macOS menu bar app that unifies events and information from various sources (Calendar, Reminders, RSS, GitHub, etc.) into a dynamic screen edge information stream.

> [!WARNING]  
> This。application is closed-source. The repository is solely for release distribution and issue tracking.  
> This。application is still under development and may have some issues affecting usage. Contributions via Issues are welcome!

## Minimum Requirements
macOS 14.0 (Sonoma) or later.

## Installation

### Option 1 (Recommended)

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

The events you have subscribed to will be presented as colored bars along the edge of the screen.

<img width="3842" height="2162" alt="1Capture_2025-08-22_20 48 14" src="https://github.com/user-attachments/assets/e2a66ac0-0586-481e-baad-b9add99795a1" />

If you have many events, the colored bars may even merge into a rainbow!

<img width="3842" height="2162" alt="1Capture_2025-08-22_20 52 51" src="https://github.com/user-attachments/assets/41288a69-5724-42b7-bb2f-cd0ef5c857fd" />

There is also a **Simplie Bubble** mode, suitable for users who only want to view updates without delving into details.

<img width="3842" height="2162" alt="1Capture_2025-08-23_13 14 06" src="https://github.com/user-attachments/assets/f00c6c45-a4a7-4847-b02c-f771f2622b91" />

## To-Do List

- [x] Improve the plugin framework  
- [x] Optimize multi-plugin loading performance  
- [ ] Integrate the plugin marketplace and set default plugins  
- [x] Implement asynchronous multi-plugin loading  
- [ ] Add support for custom plugins  
- [ ] Integrate CalDav plugin  
- [x] Integrate Github Star plugin 
- [x] Integrate Github PR plugin   
- [x] Implement readability adjustment settings  
