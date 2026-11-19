<div align="center">

# 🎬 Clippr

**Your game clips, sorted, trimmed and shared — without a cloud account.**

Clippr records your games in the background with OBS. Press a key and the last 30 seconds (or 2 minutes) are saved as a clip, filed under the right game, with your kills already marked on the timeline.

### [⬇ Download ClipprSetup.exe](https://github.com/MyPantsRGone/Clippr/releases/latest)

Windows 10 / 11 · free · everything stays on your PC

![The Clippr library](docs/library.png)

</div>

---

## ✨ What it does

| | |
|---|---|
| 🎮 **Clip any game with one key** | Clippr keeps a replay buffer running in OBS (installed and set up for you). Press your clip key and the last moments are saved. Several keys can save different lengths, and whole game sessions can be recorded too. |
| 🗂 **Sorted automatically** | Every clip lands under the game you were playing, with the game's cover art. New clips wait in **New clips** until you've had a look. |
| 🎯 **Kills on the timeline** | Counter-Strike 2, Dota 2 and League report your kills, headshots and deaths officially. In Deadlock and Valorant, Clippr reads them from the clip itself. Every clip shows its best **action moments**. |
| ✂️ **Trim in a second** | Drag the handles and save — instantly and with no quality loss, or frame-exact. The old version goes to *Recently deleted*, so you can always get it back. |
| 🫥 **Privacy blur** | Paint over names, chat or anything private, and choose how long the blur lasts. It's baked into anything you share. |
| 💬 **Copy for Discord** | One click makes a copy that fits Discord's upload limit and puts it on your clipboard. Just press Ctrl+V in Discord. |
| 🏘 **Clippr Town** | Your clips live in a little pixel-art town as villagers, and the town grows as your library does. |
| 🎨 **Make it yours** | 16 themes, Liquid Glass, Frutiger Aero, animated backgrounds, or your own picture or video. |
| 🔄 **Updates itself** | Clippr checks this page for new versions and installs them when you say so. |

---

## 🎥 The clip editor

Watch, trim and file your clips. Kills and action moments are marked on the filmstrip, and the arrows at the sides of the window (or **Shift + ← / →**) take you to the previous or next clip.

**Hold right-click on the video to draw**, for example to circle the enemy. The line fades away on its own after a few seconds.

![Drawing on a clip: circling the enemy with right-click](docs/drawing.gif)

## 🫥 Blur names and chat

Press **Blur** (or **B**) and paint over anything you don't want to share: your name in the kill feed, chat, a friend's gamertag. Scroll the mouse wheel to change the brush size. A grey bar under the timeline shows how long the blur lasts, so drag its ends to match. If the thing moves, end the bar there and paint a new blur at the new spot. Blurs are baked into **Copy for Discord** and precise trims; your original clip stays untouched.

![Blurring your own name in the kill feed](docs/blur.gif)

## 🕹 Game versions, together

Versions of the same game share one entry, with tabs at the top: **CS2, CS:GO and Source** under Counter-Strike, **Vanilla and Modded** under Minecraft, every GTA game (plus FiveM) under Grand Theft Auto, and so on. Covers download automatically, even for games you've uninstalled. If no cover can be found, the game's own icon is used.

![Counter-Strike with tabs for CS2, CS:GO and Source](docs/families.png)

## 📁 Folders, your way

Games and folders share one list in the sidebar, in whatever order you drag them. Drop a game or folder onto another folder and it becomes a tab there. You can keep it in the sidebar too, and your clips are never duplicated. A folder holding several games shows their icons, which spread out when you point at it. There's also a folder for every year, made automatically.

![A folder with folders inside it as tabs](docs/folders.png)

## 🏘 Clippr Town

Every clip is a villager. Clips with the most kills get the best houses, and each game gets its own building. Watch the town grow with **Town history**, or switch on **Adventure** for a walled city that defends itself from raiders.

![Clippr Town](docs/town.png)

![Adventure mode: a walled city](docs/adventure.png)

## 🎨 Themes

![The Frutiger Aero theme](docs/aero.png)

---

## ⚡ Light on your PC

- **Nothing heavy while you play.** Clippr pauses its own work while a game is running.
- **Clip scanning only when you're away.** Reading kills from clips only runs while your PC is idle (no mouse or keyboard for 2 minutes). It stops the moment you're back, and you can pause or cancel it in **Settings → Clipping**.
- **Big libraries are fine.** Tested with 9,000 clips: the library loads as you scroll, and the town keeps 600 villagers out and about.

## 🔒 Private by design

- Clips, your library and your settings never leave your PC. There's no account and no upload.
- The only things Clippr downloads are OBS / FFmpeg (when installing), game covers (it sends only the game's name), and updates from this page.

## 📦 Install

1. Download **ClipprSetup.exe** from the [latest release](https://github.com/MyPantsRGone/Clippr/releases/latest).
2. Run it. It installs Clippr and anything that's missing (OBS, FFmpeg and Python).
3. A short setup asks for your clip key and where to keep clips. Then just play.

> Windows may warn about an unknown publisher the first time, because the installer isn't code-signed. Click **More info → Run anyway**.
