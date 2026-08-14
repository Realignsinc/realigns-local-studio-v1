# Installation Guide

## Realigns Local Studio v1

Licensed by Realigns Inc.

## Before Installation

You need:

- A supported Mac or Windows computer
- A valid Realigns license or trial access
- A GGUF model file selected by your organization or downloaded from an approved model source
- Enough system memory for the selected model

No GGUF model is included inside the installer.

---

## Mac Installation

Supported Mac:

- Apple Silicon Mac only
- M1, M2, M3, M4 or newer

Installer file:

`Realigns Local Studio v1-1.0.0-mac-arm64.dmg`

Steps:

1. Download the Mac DMG installer.
2. Open the DMG file.
3. Drag **Realigns Local Studio v1** into the **Applications** folder.
4. Open the app from Applications.
5. Activate your license or trial access.
6. Go to **Model Manager**.
7. Upload your GGUF model.
8. Select the model.
9. Start the local runtime.
10. Begin using the AI workspaces.

### Mac Security Notice

The current commercial testing build may require Apple Developer ID signing and notarization for smooth public opening on all Mac systems.

If macOS blocks the app during approved testing, contact Realigns support.

---

## Windows Installation

Supported Windows:

- Windows x64

Installer file:

`Realigns Local Studio v1-1.0.0-win-x64.exe`

Steps:

1. Download the Windows setup file.
2. Run the installer.
3. Open **Realigns Local Studio v1**.
4. Activate your license or trial access.
5. Go to **Model Manager**.
6. Upload your GGUF model.
7. Select the model.
8. Start the local runtime.
9. Begin using the AI workspaces.

### Windows Security Notice

Until Windows code signing is completed, Microsoft SmartScreen or browser security may show a warning for first-time downloads. This is common for new unsigned desktop software.

Only download Realigns Local Studio v1 from official Realigns channels.

---

## Model Setup

Realigns Local Studio v1 supports GGUF model files.

Recommended model choice depends on:

- Available RAM
- CPU/GPU capability
- Required language support
- Required speed
- Business use case

Small models are suitable for light chat and basic assistance. Medium models are suitable for better reasoning and document work. Larger models require stronger hardware.

---

## Uninstalling on Mac

Normal uninstall:

1. Quit Realigns Local Studio v1.
2. Open Applications.
3. Drag **Realigns Local Studio v1** to Trash.
4. Empty Trash.

Full clean removal also requires deleting local app data:

`~/Library/Application Support/realigns-ai-studio-beta-v1`

This removes uploaded models, settings, license cache, and local history.

---

## Uninstalling on Windows

Use Windows Settings:

1. Open **Settings**.
2. Go to **Apps**.
3. Find **Realigns Local Studio v1**.
4. Click **Uninstall**.

The Windows installer is configured to remove application data during uninstall.
