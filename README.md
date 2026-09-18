# Multi Roblox Launcher

**Closed Source • Windows 10/11 x64**

Multi Roblox Launcher is a portable Windows launcher for managing multiple Roblox accounts and keeping multiple Roblox clients open at the same time.

## Features

- Add and save multiple Roblox accounts
- Keep multiple Roblox clients open at once
- Join games directly with a Place ID
- Follow / join another Roblox player
- Built-in Anti-AFK with automatic 10-minute cycles
- Working FPS limiter
- Low Resource Mode for reduced CPU and RAM usage
- Portable — no installer required

## Anti-AFK

Anti-AFK is disabled by default.

When enabled, the launcher immediately runs one Anti-AFK cycle and briefly focuses each open Roblox client.

After that, a **10-minute timer** starts. You can minimize your Roblox windows normally.

When the timer reaches 0, the launcher briefly restores and focuses each Roblox client, performs the Anti-AFK input, and minimizes the window again.

The next 10-minute timer then starts automatically.

## Preview

![Multi Roblox Launcher](MultiRobloxLauncher.png)

## Requirements

- Windows 10 or Windows 11 x64
- **The normal Roblox desktop player must already be installed**

> ⚠️ **Important:** Before starting Multi Roblox Launcher, close all running Roblox clients and fully exit Roblox from the **Windows system tray**. Roblox running in the background can prevent multi-instance from working correctly.

## Security

Roblox passwords are **never stored**.

Saved Roblox account sessions are stored locally and encrypted for the current Windows user.

Account login is performed through the **official Roblox website** using the launcher's dedicated login browser.

**IMPORTANT: Never share your `Data` folder with anyone. It contains your locally saved account sessions.**

The launcher uses the normal Roblox desktop client and does **not** use DLL injection, exploits, or modified Roblox files.

## Download

➡️ **[Download the latest release](https://github.com/EmirCoco37/MultiRobloxLauncher/releases/latest)**

## Updating

If you already have accounts saved in an older version, you do **not** need to log into them again.

Simply copy the entire **`Data`** folder from your old launcher folder into the new build.

## VirusTotal

You are also free to upload the downloaded ZIP or EXE to VirusTotal yourself before running it.

## Usage

1. Download the latest Windows x64 ZIP from Releases.
2. Extract the ZIP.
3. Close all running Roblox clients and fully exit Roblox from the **Windows system tray** before starting Multi Roblox Launcher.
4. Run `Multi Roblox Launcher.exe`.
5. Click **Add Account** and sign in on the official Roblox website.
6. Select an account, enter a Place ID, then click **Join Server**.
7. To join another player, enter their Roblox username and click **Follow**.
8. Optionally enable **Anti-AFK** or **Low Resource Mode**.

## Closed Source

Multi Roblox Launcher is proprietary software.

The source code is **not public** and is not included in this repository.

See [LICENSE](LICENSE) for usage and redistribution terms.

## Disclaimer

Multi Roblox Launcher is an independent project and is not affiliated with, endorsed by, or sponsored by Roblox Corporation.

## Publisher

**amvu**

GitHub: **@EmirCoco37**
