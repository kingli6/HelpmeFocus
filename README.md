# HelpmeFocus

Extension that blocks websites to help you focus.

## Temporary installation for testing FIREFOX extension locally

1. Download or clone the GitHub repository.
2. In Firefox, open `about:debugging#/runtime/this-firefox`.
3. Click **Load Temporary Add-on…**.
4. Select `firefox-extension/manifest.json`.
5. Firefox adds Focus Browser Guard.

### Finding the Focus popup

The Focus popup is not the general Firefox Extensions menu:

* Click Firefox's puzzle-piece **Extensions** button near the address bar.
* Find **Focus Browser Guard**. Ignore other extensions such as YouTube Repeat.
* Pin **Focus Browser Guard** to the toolbar.
* Click the **Focus Browser Guard** toolbar icon itself.
* Click **Start focus session** or **Open local dashboard**.

If the popup is empty or shows only a thin white line, remove the temporary add-on from `about:debugging`, load `firefox-extension/manifest.json` again, and click the Focus Browser Guard icon—not the puzzle-piece menu.

## Install in Chrome (Warning: I have not tested this. let me know if it doesn't work...)

1. Download or clone this repository.
2. Open: `chrome://extensions`
3. Turn on **Developer mode**.
4. Click **Load unpacked**.
5. Select the `chrome-extension/` folder.
6. Pin **Focus Browser Guard** from Chrome's Extensions menu.
7. Click the **Focus Browser Guard** toolbar icon.
8. Click **Open local dashboard**.

## Use the extension

The local dashboard lets you:

* Start normal sessions that can end early.
* Start hard-block sessions that stay locked until the timer expires.
* Choose 20, 25, 45, or 60-minute sessions.
* Quickly add common distracting sites.
* Choose Full site or Feed only.
* Switch an existing site between Full site and Feed only without removing it.
* Enable, disable, and remove sites.

# Focus Desktop Guard for Windows

**Focus Desktop Guard** is a lightweight, local Windows companion for the Focus browser extensions. It monitors and blocks distracting Windows applications—such as Steam, Discord, Spotify, Epic Games Launcher, and Battle.net—during timed focus sessions. If a blocked program is reopened while a session is active, Focus Desktop Guard automatically closes it again.

> [!IMPORTANT]
> This application must remain open during a focus session. Closing the Focus Desktop Guard window will stop monitoring. It is designed for personal productivity and is not tamper-proof.

---

## ✨ Features

* 🖥️ **Simple Graphical Interface:** Easy-to-use GUI for quick session configuration.
* ⏱️ **Flexible Timers:** Choose custom session lengths ranging from 1 to 240 minutes.
* 🎯 **App Selection:** Easily select one or multiple applications to block.
* 🔒 **Session Modes:**
  * **Normal Sessions:** Can be manually ended early if needed.
  * **Hard-Block Sessions:** Remain locked until the timer fully expires.
* 📂 **Custom App Support:** Add any Windows executable via an `.exe` file picker.
* 🗑️ **Management:** Easily remove custom applications directly from the interface.
* 🛡️ **Private & Local:** Runs entirely offline with no accounts, servers, or internet connection required.
* 💻 **CLI Support:** Optional command-line controls for advanced users and automation.

---

## 📋 Requirements

* **OS:** Windows 10 or Windows 11
* **Shell:** Windows PowerShell 5.1 *(pre-installed on Windows)*
* **Permissions:** Administrator privileges may be required to close applications running with elevated permissions.

---

## 🚀 Quick Start

### 1. Download the Program
Download the latest release package from the project's **Releases** page:
* `focus-windows-desktop-guard-v0.3.1.zip`

*(Alternatively, clone this repository and navigate to the `windows-desktop-guard` folder).*

### 2. Unblock the Downloaded Archive
Before extracting the ZIP file, remove the Windows security block:
1. Right-click the downloaded `.zip` file and select **Properties**.
2. Under the **General** tab, check the **Unblock** box near the bottom.
3. Click **Apply**, then **OK**.
4. Extract the contents of the ZIP file.

> *Note: Unblocking prevents Windows from applying downloaded-file security restrictions to the extracted PowerShell scripts.*

### 3. Launch the Interface
1. Open the extracted `windows-desktop-guard` folder.
2. Right-click `Start-FocusDesktopGuard.cmd`.
3. Select **Run as administrator**.

The Focus Desktop Guard window will open automatically. You do not need to open PowerShell manually or interact with the command menu.
