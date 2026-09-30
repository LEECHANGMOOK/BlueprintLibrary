# BlueprintLibrary

**BlueprintLibrary** is a free Windows desktop application for saving, previewing, syncing, and reusing Unreal Engine Blueprint node presets.

Copy Blueprint nodes from Unreal Engine, save them as presets, and copy them back to the clipboard whenever you need them.

---

## Download

### [Download the latest Portable version](https://github.com/LEECHANGMOOK/BlueprintLibrary/releases/latest)

No installation required.

1. Download `BlueprintLibrary_*_Portable.zip`
2. Extract the ZIP file
3. Run `BlueprintLibrary.exe`

> Do not run the application directly from inside the ZIP file.

---

## Features

- Save Unreal Engine Blueprint clipboard data as presets
- Preview Blueprint node graphs
- Copy saved presets back to the Windows clipboard
- Rename and delete presets
- Import / Export `.bpl` preset files
- Google Drive Sync between multiple PCs
- Local preset storage
- Portable Windows application

---

## Basic Workflow

### Save a Blueprint

1. Select nodes in the Unreal Engine Blueprint Editor
2. Press `Ctrl + C`
3. Open BlueprintLibrary
4. Enter a preset name
5. Click **Save Clipboard**

### Reuse a Blueprint

1. Select a saved preset
2. Click **Copy**
3. Return to Unreal Engine
4. Press `Ctrl + V`

---

## Google Drive Sync

BlueprintLibrary can synchronize `.bpl` preset files using your own Google Drive account.

Click:

`Google Drive Sync`

and sign in with your Google account.

BlueprintLibrary uses Google Drive only for BlueprintLibrary preset synchronization.

---

## Data Storage

Local presets are stored in:

```text
%LOCALAPPDATA%\BlueprintLibrary\Presets
