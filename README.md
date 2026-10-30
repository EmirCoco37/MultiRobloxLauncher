# Multi Roblox Launcher

**Closed Source | Windows 10/11 x64**

A portable Windows launcher for managing multiple Roblox accounts and running multiple Roblox clients at the same time.

## Features

- **Account Management** - Save multiple Roblox accounts with avatars, custom nicknames, favorites, drag-and-drop sorting, search and last-used information.
- **Multi-Instance & Multi-Launch** - Run multiple Roblox clients and launch selected accounts sequentially with a configurable 1-10 second delay.
- **Launch Options** - Join games by Place ID, follow other players or join private servers using a link.
- **Saved Games & Private Servers** - Save, edit and organize presets with automatic Roblox game name detection.
- **Performance Controls** - Custom FPS limits (1-999 or Unlimited) and Low Resource Mode for background clients.
- **Anti-AFK** - Runs immediately when enabled and repeats at a configurable 1-15 minute interval, including support for minimized windows.
- **Quality of Life** - Roblox client counter, recent history, optional system tray mode and Roblox window size restoration.
- **Utilities** - Settings import/export, detailed diagnostics, Close All Roblox and a built-in auto-updater.

## Preview

![Multi Roblox Launcher - Home](screenshots/home.png)

<details>
<summary><strong>View more screenshots (Settings & Support)</strong></summary>

### Settings - Performance & Anti-AFK

![Multi Roblox Launcher - Settings, upper section](screenshots/settings-top.png)

### Settings - Launcher & Tools

![Multi Roblox Launcher - Settings, lower section](screenshots/settings-bottom.png)

### Support

![Multi Roblox Launcher - Support](screenshots/support.png)

</details>

## Download

**[Download the latest release](https://github.com/EmirCoco37/MultiRobloxLauncher/releases/latest)**

No installer required. Download and extract the Windows x64 ZIP.

## Updating

The built-in updater checks for new releases when you open the launcher. If no update prompt appears, go to **Settings > Check for Updates**.

Your existing accounts, settings, `Data` and `Logs` are preserved during an automatic update.

**Updating manually?** Extract the new release and copy your existing `Data` folder into the new launcher folder to keep your saved accounts and settings.

## Usage

1. [Download and extract the latest Windows x64 ZIP](https://github.com/EmirCoco37/MultiRobloxLauncher/releases/latest).
2. Close any running Roblox clients before starting the launcher.
3. Run `Multi Roblox Launcher.exe`.
4. Click **Add Account** and sign in through the official Roblox website.
5. Select one or more accounts and choose **Join Game**, **Follow Player** or **Private Server**.
6. Optionally customize your FPS limit, Anti-AFK interval and Low Resource Mode under **Settings**.

> **Tip:** If you notice lag spikes after running Roblox for several hours, try a 60 FPS limit instead of 30 FPS.

## Security

- Roblox passwords are **never stored** by the launcher.
- Saved account sessions are stored locally and encrypted for your Windows user account.
- Sign-in is performed through the **official Roblox website**.
- Settings exports do not include account sessions.
- The launcher does not use DLL injection, exploits or modified Roblox files.

> **Never share your `Data` folder.** It contains your locally saved account sessions.

## Requirements

- Windows 10 or Windows 11 (64-bit)
- Roblox desktop player installed
- Internet connection for login, updates and Roblox services

## Closed Source

Multi Roblox Launcher is proprietary software. Its source code is not public and is not included in this repository. See [LICENSE](LICENSE) for usage and redistribution terms.

## Disclaimer

Multi Roblox Launcher is an independent project and is not affiliated with, endorsed by or sponsored by Roblox Corporation.

## Publisher

Discord: **@amvu**  
GitHub: **@EmirCoco37**
