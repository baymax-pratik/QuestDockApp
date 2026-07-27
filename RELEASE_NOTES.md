## QuestDock v1.0.0

**Quest device traces, docked.**

QuestDock is a Windows desktop utility for Unreal Engine teams on **Meta Quest**. Manage headsets over ADB, push Unreal Insights `UECommandLine` configs, launch your package, and pull traces back to your PC — with progress, status, and a clear activity log.

### Download

**Use this file only:** [`QuestDock-win-x64.zip`](https://github.com/baymax-pratik/QuestDockApp/releases/download/v1.0.0/QuestDock-win-x64.zip)

1. Unzip  
2. Run **`QuestDock.exe`**  
3. Open **Settings** → set ADB path, package name, and trace folder  

Self-contained build — **no separate .NET install** required.

> Ignore GitHub’s automatic “Source code” links — they only contain the README, not the app.

### Screenshots

#### Main window (light)
![QuestDock light theme](https://raw.githubusercontent.com/baymax-pratik/QuestDockApp/main/media/questdock-main-light-v2.png)

#### Main window (dark)
![QuestDock dark theme](https://raw.githubusercontent.com/baymax-pratik/QuestDockApp/main/media/questdock-main-dark-v2.png)

#### Settings
![QuestDock settings](https://raw.githubusercontent.com/baymax-pratik/QuestDockApp/main/media/questdock-settings-v2.png)

### What’s included

- Refresh connected Quest / Android devices  
- Push / delete `UECommandLine` for Unreal Insights  
- Launch your configured package  
- Pull traces with live log output  
- Open local trace folder  
- Trace presets (GPU, CPU, Performance, Memory, Networking, Full Trace, Custom)  
- Light / Dark theme toggle  

### Quick workflow

```text
Refresh Devices → Push UECommandLine → Launch → Pull Trace → Open Trace Folder → Unreal Insights
```

### Requirements

- Windows 10/11 (x64)  
- Meta Quest with Developer Mode + USB debugging  
- ADB (Android Platform Tools)  

Full documentation: https://github.com/baymax-pratik/QuestDockApp
