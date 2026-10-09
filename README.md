# Cyre Screenplay

**Cyre Screenplay** is a screenplay editor built for writers and storytellers — a focused place to draft in **Fountain**, see your story take shape, and move from first idea to a script you can share.

## Download

Click your platform to download the **latest** desktop build:

| Platform | Download |
| -------- | -------- |
| **macOS (Apple Silicon)** | [Download `.dmg`](https://github.com/neuralline/cyre-screenplay-releases/releases/latest/download/Cyre-Screenplay-mac-arm64.dmg) |
| **macOS (Intel)** | [Download `.dmg`](https://github.com/neuralline/cyre-screenplay-releases/releases/latest/download/Cyre-Screenplay-mac-x64.dmg) |
| **Windows** | [Download installer](https://github.com/neuralline/cyre-screenplay-releases/releases/latest/download/Cyre-Screenplay-Setup.exe) |
| **Linux (AppImage)** | [Download AppImage](https://github.com/neuralline/cyre-screenplay-releases/releases/latest/download/Cyre-Screenplay-linux-x64.AppImage) |
| **Linux (Debian/Ubuntu)** | [Download `.deb`](https://github.com/neuralline/cyre-screenplay-releases/releases/latest/download/Cyre-Screenplay-linux-x64.deb) |

Older builds and release notes: **[All releases](https://github.com/neuralline/cyre-screenplay-releases/releases)**.

The installed app checks for updates in the background. On Windows and Linux it downloads them and installs when you restart. On macOS it tells you when a new version is out, and you can also choose **Cyre Screenplay → Check for Updates…** at any time.

### macOS: “damaged”, “cannot verify”, or “Apple could not verify…”

Test builds are **not yet signed with an Apple Developer ID or notarized**, so macOS blocks them when they are downloaded through a browser. The app is not damaged; this is how macOS treats any unsigned download.

**Easiest: install from Terminal.** Files downloaded with `curl` are not flagged by macOS, so the app opens normally. For Apple Silicon (M1 and later):

```bash
curl -fL -o /tmp/cyre.zip https://github.com/neuralline/cyre-screenplay-releases/releases/latest/download/Cyre-Screenplay-mac-arm64.zip \
  && ditto -x -k /tmp/cyre.zip /Applications && rm /tmp/cyre.zip
```

For Intel Macs, replace `mac-arm64` with `mac-x64`. Run the same command again to update.

**Already downloaded the `.dmg`?** Drag the app to Applications, then run:

```bash
xattr -dr com.apple.quarantine "/Applications/Cyre Screenplay.app"
```

**Without Terminal:** open the app once. When macOS blocks it, go to **System Settings → Privacy & Security**, scroll down to the message about **Cyre Screenplay**, click **Open Anyway**, and confirm. (On macOS 15 Sequoia and later, right-click → Open no longer skips this step.)

### Windows: “Windows protected your PC”

Until the installer is code-signed, SmartScreen may show this warning. Click **More info → Run anyway**.

## What you can do

- **Write in Fountain** — industry-friendly plain text with smart formatting as you type  
- **Stay in flow** — minimal, modern workspace built for long writing sessions  
- **Explore the script** — scene and story tools to navigate structure, characters, and locations  
- **Understand your draft** — insights on pacing, shape, and craft (without leaving the page)  
- **Storyboard view** — see the script as scenes and beats, not only as a scroll of pages  
- **Title page & production details** — keep metadata with the project  
- **Work your way** — open local `.fountain` files and project files; cloud projects on supported plans  
- **Desktop & web** — install the app here; the browser version is hosted separately by the Cyre team  

## Formats & projects

Start a new screenplay, open an existing Fountain file, or work inside a **Cyre project** so notes, story bible material, and your script stay together.

## Support

This repository is for **installers and updates** only. The application source is not published here.

For questions or feedback, contact **Neural Line** through your usual project or account channel.

---

*Cyre Screenplay — write the story; we’ll help you see it clearly.*
