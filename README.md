<p align="center"><img src="icon.png" width="128" alt="Zone4build" /></p>

<h1 align="center">Zone4build for desktop</h1>

<p align="center">
Zone4build in a window, plus a runner that lets your projects run on <b>your own computer's Docker</b>.<br/>
Your account, projects and the AI agent stay on <a href="https://zone4build.com">zone4build.com</a>.
</p>

## Download

| | |
|---|---|
| **macOS — Apple Silicon** (M1–M4) | [Zone4build-mac-arm64.dmg](https://github.com/zone4build/zone4build-desktop/releases/latest/download/Zone4build-mac-arm64.dmg) |
| **macOS — Intel** | [Zone4build-mac-x64.dmg](https://github.com/zone4build/zone4build-desktop/releases/latest/download/Zone4build-mac-x64.dmg) |
| **Windows 10/11** (most PCs) | [Zone4build-windows-x64.exe](https://github.com/zone4build/zone4build-desktop/releases/latest/download/Zone4build-windows-x64.exe) |
| **Windows on ARM** | [Zone4build-windows-arm64.exe](https://github.com/zone4build/zone4build-desktop/releases/latest/download/Zone4build-windows-arm64.exe) |

All versions: [Releases](https://github.com/zone4build/zone4build-desktop/releases). Checksums: `SHA256SUMS.txt` in each release.

## Install

1. Install **[Docker Desktop](https://www.docker.com/products/docker-desktop/)** and start it (needed to run projects on your computer).
2. Install Zone4build:
   - **Mac:** open the `.dmg` and drag Zone4build to Applications. The app isn't signed yet: the first time, **right-click → Open**.
   - **Windows:** run the installer. If SmartScreen warns, **More info → Run anyway**.
3. Open Zone4build and **sign in**. Your computer is paired with your account automatically.
4. In a project, use the status bar's **Run on** switch and pick your computer.

## Safe by design

The app keeps **one outgoing connection** to Zone4build; nothing listens on your network. It only runs Zone4build containers, only mounts folders inside `~/Zone4build`, only opens ports on `127.0.0.1`, and never runs anything privileged.

## Also

- Command line: `npm install -g zone4code-cmd` — [guide](https://zone4build.com/cli)
- Desktop guide: [zone4build.com/desktop](https://zone4build.com/desktop)
- Support: support@zone4build.com
