# Veil

A real-time AI copilot for Windows calls and presentations. It sits on top of your screen, listens to the call, can see your screen, knows your background from files you upload, and suggests what to say. A switch on the overlay decides whether people in your screen share can see it.

This page only holds the installers. To download, open **[Releases](../../releases/latest)** and download `Veil-Setup-<version>.exe`.

## Install

1. Open the downloaded file. Veil installs for your Windows account with no admin prompt, and adds a **Veil** icon to your Desktop and Start menu.
2. Windows may show **"Windows protected your PC"** because the installer isn't code-signed. Click **More info**, then **Run anyway**.
3. In Veil, click the settings icon at the right end of the top pill, paste your own [Anthropic API key](https://console.anthropic.com/) and press **Save**. Usage is billed to that key.

Needs Windows 10 version 2004 or later.

## Updates

Veil checks for new versions when it starts and every 4 hours, and downloads them quietly. When one is ready, a blue **Update** button appears on the pill. Press it and Veil reopens on the new version. **Settings** shows your version and has **Check for updates**.

## Shortcuts

| Keys | Action |
|---|---|
| `Ctrl+Enter` | Assist with what's on screen and in the call |
| `Ctrl+\` | Hide or show the overlay |
| `Ctrl+Alt+S` | Hidden from or visible in your screen share |
| `Ctrl+Alt+L` | Start or stop listening |
| `Ctrl+Alt+Q` | Quit |

You can change any of them in Settings.

## Good to know

- Hiding from screen shares works through Windows' capture exclusion. It can't hide from a phone or camera pointed at the screen, and Veil doesn't hide from monitoring software on the PC. Test it with a second device before relying on it.
- Recording or transcribing a call can require everyone's consent where you are, and many exams, assessments and interviews ban undisclosed AI help.
- Uninstall from Windows **Settings > Apps**.
