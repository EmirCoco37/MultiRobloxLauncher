# Multi Roblox Launcher

**Closed Source • Windows 10/11 x64**

Multi Roblox Launcher is a portable Windows launcher for managing multiple Roblox accounts and keeping multiple Roblox clients open at the same time.

## Features

- Add and save multiple Roblox accounts
- Keep multiple Roblox clients open at once
- Join games directly with a Place ID
- Join Roblox private servers using a private server link
- Follow / join another Roblox player
- Built-in Anti-AFK with automatic 10-minute cycles
- Working FPS limiter
- Low Resource Mode for reduced CPU and RAM usage
- Close all running Roblox Player clients with one button
- Built-in Auto Updater
- Portable — no installer required

## Anti-AFK

Anti-AFK is disabled by default.

When enabled, the launcher immediately runs one Anti-AFK cycle and briefly focuses each open Roblox client.

After that, a **10-minute timer** starts. You can minimize your Roblox windows normally.

When the timer reaches 0, the launcher restores and focuses each Roblox client, performs the Anti-AFK input, and minimizes the window again.

If a minimized Roblox window does not respond immediately, the launcher automatically retries it before continuing with the next client.

The next 10-minute timer then starts automatically.

## Low Resource Mode

Low Resource Mode reduces CPU and RAM usage while multiple Roblox clients are running.

It is designed for running several Roblox clients in the background for longer periods of time.

If you experience lag spikes after running Roblox for a few hours, try launching the clients at **60 FPS instead of 30 FPS**. This will not affect Low Resource Mode.

## Preview

![Multi Roblox Launcher](MultiRobloxLauncher-v1.1.1.png)

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

### Updating to v1.1.1 from an older version

If you already have accounts saved in an older version, copy the entire **`Data`** folder from your old launcher folder into the new v1.1.1 folder.

You only need to do this **once** when moving to v1.1.1.

Your saved accounts will then continue to work without having to log into them again.

### Future Updates

Starting with v1.1.1, Multi Roblox Launcher includes a built-in **Auto Updater**.

When a new version is available, the launcher can automatically download and install it for you.

During an update:

- The launcher will close automatically
- The update will be installed
- Your `Data` and `Logs` folders will be kept
- Multi Roblox Launcher will start again automatically when the update is complete

You will **not need to manually copy your `Data` folder again** for future updates installed through the Auto Updater.

## Usage

1. Download the latest Windows x64 ZIP from Releases.
2. Extract the ZIP.
3. Close all running Roblox clients and fully exit Roblox from the **Windows system tray** before starting Multi Roblox Launcher.
4. Run `Multi Roblox Launcher.exe`.
5. Click **Add Account** and sign in on the official Roblox website.
6. Select an account.
7. Enter a Place ID and click **Join Server**, or paste a Roblox private server link.
8. To join another player, enter their Roblox username and click **Follow**.
9. Optionally enable **Anti-AFK** or **Low Resource Mode**.
10. Use **Close All Roblox** to close all running Roblox Player clients at once.

> **Note:** Close All Roblox only closes Roblox Player clients. Roblox Studio is not affected.

## Auto Updater

Multi Roblox Launcher automatically checks for new versions.

When an update is available, you can install it directly through the launcher without manually downloading and replacing files.

The launcher will close during the update and automatically reopen when the installation is complete.

## VirusTotal

You are also free to upload the downloaded ZIP or EXE to VirusTotal yourself before running it.

## Closed Source

Multi Roblox Launcher is proprietary software.

The source code is **not public** and is not included in this repository.

See [LICENSE](LICENSE) for usage and redistribution terms.

## Disclaimer

Multi Roblox Launcher is an independent project and is not affiliated with, endorsed by, or sponsored by Roblox Corporation.

## Publisher

**amvu**

GitHub: **@EmirCoco37**
