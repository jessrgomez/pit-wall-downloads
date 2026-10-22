# Pit Wall: RB Buddy

A Formula 1 desktop companion. An F1 car drives along your screen and acts as your race engineer: it keeps your tasks, radios you with "Box, box!" when something is due, and calls out your tickets and meetings.

This repository holds the installers. The source code is private.

## Download

| System | Installer | Size |
| --- | --- | --- |
| Windows 10 or 11 | [PitWall-RB-Buddy-Setup-1.2.0.exe](https://github.com/jessrgomez/pit-wall-downloads/releases/download/v1.2.0/PitWall-RB-Buddy-Setup-1.2.0.exe) | 2.4 MB |
| Ubuntu (64-bit) | [PitWall-RB-Buddy-1.1.1-amd64.deb](https://github.com/jessrgomez/pit-wall-downloads/releases/download/ubuntu-v1.1.1/PitWall-RB-Buddy-1.1.1-amd64.deb) | 72 MB |

Every version is on the [Releases](https://github.com/jessrgomez/pit-wall-downloads/releases) page.

## Install on Windows

1. Download the `.exe` and run it. It installs just for you, so no admin rights are needed.
2. The installer isn't code-signed, so Windows SmartScreen may say the app is unrecognised. Click **More info**, then **Run anyway**.
3. The car starts on your desktop. Right-click it, open **Pit Wall**, then **Settings** to set your name.

PowerShell 5.1 and the Edge WebView2 Runtime come with Windows 10 and 11, so there is nothing else to install. To uninstall, go to **Settings > Apps > Pit Wall RB Buddy**.

## Install on Ubuntu

1. Download the `.deb`.
2. Double-click it and choose **Install**, or run:
   ```
   sudo apt install ./PitWall-RB-Buddy-1.1.1-amd64.deb
   ```
3. Open **Pit Wall RB Buddy** from your apps. The car appears at the bottom of the screen.

To uninstall, run `sudo apt remove pitwall-rb-buddy`.

## Using it

- **Click the car** to box (stop) or send it out, and **drag it** to move it.
- **Right-click the car** for the menu: Pit Wall, tasks, tickets, Max's moods, Race mode, pit stops and the driver getting out.
- **Add tasks** in Pit Wall. Times written in plain English ("call the bank at 3pm") become reminders, and the car calls "Box, box!" when they're due.
- **Connect accounts** in Settings (Jira, Gmail, Yahoo Mail, Slack, Lark, Trello) to have their due items added to your tasks and called out on the radio. Everything is optional; the task tracker works without any account.

Your settings and tasks stay on your computer.

Made by [Jessica Gomez](https://jessicargomez-portfolio.vercel.app).
