# NozeDock

NozeDock is a Windows desktop tool for molecular docking and structure visualization, with MCP tools for AI-assisted workflows.

**Program users: download only `NozeDock.exe` from the [latest release](https://github.com/Comatpu/NozeDock/releases/latest).**

## Getting started

1. Save `NozeDock.exe` in a writable local folder.
2. Run it. The application creates `NozeDock_data` beside the EXE and prepares its bundled runtime on first launch.
3. Configure your own AI account and MCP connection in the application settings.

Windows 10/11 x64 is required. No separate WSL, Python, Vina, or Node installation is needed. Personal research data and account credentials are not included in public downloads.

## Automatic updates

Each new desktop launch checks for signed updates. App-only changes use a smaller update; runtime changes use a full update. If the update check fails or you are offline, the installed version remains available. Reload refreshes the interface without checking for updates. User research data and settings are kept separately from application updates.

`NozeDock-app.zip`, `NozeDock-runtime.zip`, and `latest.json` are used by the updater. You do not need to download them manually. GitHub's automatically generated Source code archives are not needed to run NozeDock.

This repository hosts public release files and distribution information.
