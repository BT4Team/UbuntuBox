<p align="center">
  <img src="website/logo.png" alt="UbuntuBox logo" width="112">
</p>

<h1 align="center">UbuntuBox</h1>

<p align="center"><b>Ubuntu right on your phone.</b></p>

<p align="center">
  A real Ubuntu 24.04 terminal for Android. No root, nothing else to install.<br>
  Git, curl and apt are built in, and AI coding agents are one tap away.
</p>

<p align="center">
  <a href="https://ubox.bt4team.com"><b>🌐 Website</b></a> &nbsp;·&nbsp;
  <a href="https://ubox.bt4team.com/#install"><b>⬇ Download for Android</b></a> &nbsp;·&nbsp;
  <a href="https://ubox.bt4team.com/privacy.html">Privacy</a>
</p>

<p align="center">Android 9 or newer</p>

---

## Features

| | |
|---|---|
| **Real Ubuntu 24.04 LTS** | Install anything with `apt` or `pip`: compilers, Python, Node.js, databases, editors. apt keeps its package lists up to date by itself, and `sudo` just works. |
| **Works out of the box** | On most phones Ubuntu comes built into the app with curl, Git, nano, less, unzip and more, so setup needs no internet at all. |
| **AI agents in one tap** | Install, launch and update Claude Code, Cursor CLI, Antigravity CLI and OpenCode from the Agent Hub. |
| **Sign-ins just work** | When a tool opens a browser to sign in, your phone's browser opens. Tap any link in the terminal to open or copy it. |
| **Your files, everywhere** | The whole Ubuntu system shows up in Android's Files app as “UbuntuBox”. Turn on phone storage to reach it at `/storage/emulated/0`. |
| **Keeps running** | Long builds and agent runs carry on in the background. Several sessions at once, each in its own tab. |
| **Made for touch** | Esc, Tab, Ctrl, Alt, arrows and Paste on one scrollable row; hold an arrow to keep moving. Copy, paste and typing that work on every keyboard. |
| **Your look** | Follows your phone's light or dark mode, or pick one of four themes. JetBrains Mono or Fira Code, and pinch to zoom. |
| **No root** | Everything runs inside the app. Nothing to unlock, no other apps to install. |

## AI agents

The Agent Hub installs each agent with its official installer, keeps it up to date and opens it in a new tab.

| Agent | Command |
|---|---|
| Claude Code | `claude` |
| Cursor CLI | `agent` |
| Antigravity CLI | `agy` |
| OpenCode | `opencode` |

Need another tool? Run its install command in the terminal, just as on any Ubuntu machine. Node.js 24 and Python 3 are one tap away under Toolchains.

## Install

1. **Download.** Open [ubox.bt4team.com](https://ubox.bt4team.com) on your phone and tap **Download**.
2. **Allow the install.** Open the downloaded file. If Android asks, allow your browser or Files app to install apps.
3. **Install Ubuntu.** Open UbuntuBox and tap **Install**. It takes a minute or so.
4. **Start coding.** Your shell opens. Install an agent from the Agent Hub, or just start typing.

Already installed? UbuntuBox checks for new versions by itself and offers them. Installing a new version keeps your Ubuntu files.

## Good to know

- **Which phones?** Android 9 or newer. On 64-bit ARM phones (almost every phone from the last several years) Ubuntu is built into the app. Other phones download it during setup, about 30 MB.
- **Root?** Not needed. Ubuntu runs inside the app, and inside Ubuntu you are its root user.
- **Space?** About 200 MB after setup, plus whatever you install.
- **AI agents' cost?** Each agent works with its maker's account or API key, on that maker's terms. UbuntuBox installs and opens them.
- **Privacy?** No accounts, no ads, no analytics. Your files stay on your phone. Read the [privacy policy](https://ubox.bt4team.com/privacy.html).

## For developers

```sh
./gradlew :app:assembleDebug   # → app/build/outputs/apk/debug/app-debug.apk
```

Building, testing, the bundled Ubuntu image, signing and releases are described in
[docs/DEVELOPMENT.md](docs/DEVELOPMENT.md). The website's source is in [`website/`](website/).

## License

UbuntuBox is proprietary software, © 2026 BT4 Team. All rights reserved.
Third-party components and their licenses are listed in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

UbuntuBox is not affiliated with or endorsed by Canonical. Ubuntu is a trademark of Canonical Ltd.
