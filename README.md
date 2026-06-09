<!-- 言語 / Language -->
[日本語](README.ja.md) · **English** · [中文](README.zh.md)

# TBH MarketLens

**Point at an item in _TBH: Task Bar Hero_, press a key, and its Steam Market price pops up instantly — no typing, no Alt-Tab.**

by **Ghost Shark Robotics** · UI in 日本語 / English / 中文

---

## ⬇ Download & run (Windows)

1. Open the **[📥 Releases](https://github.com/GhostSharkRobotics/tbh-marketlens/releases)** page.
2. Under the newest version's **“Assets”**, click the **`.zip`** file (it starts with `TBH-MarketLens`).
3. **Right-click the .zip → Extract All.** Keep the files together in one folder.
4. Run **`TBH MarketLens.exe`** → it sits in your **system tray** (near the clock). A short how-to shows on first run.

> 💡 If Windows shows **“Windows protected your PC,”** click **More info → Run anyway** — the app is unsigned, this is normal. Some antivirus may false-positive on hotkey apps built with PyInstaller; allow it if you trust the source.

---

## What it does

- **Hover an item → press your hotkey → a card shows its Steam Market price** (lowest listing + median), fetched when you ask.
- Reads the item **right under your cursor** via on-screen OCR and matches the game's item database — equipment, gems, engravings, materials and more — with names, rarity and type in **日本語 / English / 中文**.
- **Price history** (tray): sort by added/lowest/median, favourite, rename / fix mis-reads, change rarity, delete, and **update all prices** at once. Saved between sessions.
- **Sell timer** (tray): tracks the listing hold on your Steam inventory and notifies you when items become sellable.
- Rebind the trigger to **any key or combo** (default: mouse **back / side** button). Optional **start with Windows**.

## Is it safe? (anti-cheat)

Yes. MarketLens is a **completely separate program**. It only ① screenshots its own/the desktop screen and reads text, ② listens for your chosen hotkey, and ③ asks **Steam's public price API**. It **never reads or writes the game's memory, injects nothing, and never touches the game process** — no speed/time manipulation — so it does not trigger the game's cheat detection.

## Privacy

Anonymous usage stats only (launches, looked-up item names, errors) tied to a random ID — **never your IP, Steam inventory, or any personal data**. Turn it off anytime in **Settings**.

## Updates

MarketLens checks on startup. When a new version exists, a **⬆ Update** entry appears in the tray/Settings — **one click downloads it, swaps the files, and restarts.** No manual re-download.

---

*Optional tip: ☕ [Ko-fi](https://ko-fi.com/ghostsharkrobotics). Unofficial fan-made tool, provided “as is.”*
