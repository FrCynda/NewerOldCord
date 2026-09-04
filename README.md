# NewerOldCord

**A personal project to bring back the previous Discord UI.**  
_NewerOldCord is a fork of [OldCord](https://github.com/milbits/oldcord), revamped to look more like the Discord interface that was just replaced — keeping the classic layout, but updating the visuals to feel more in line with recent design._

---

# Comparison

![Preview](https://github.com/FrCynda/NewerOldCord/blob/main/compare.png)

---

# Need Old UI Screenshots

I'm missing a lot of visual references from the old Discord UI for my theme. Stuff like:

    Pinned messages
    Inbox / Mentions
    Server settings
    Notification dropdowns
    User popouts / profiles
    Member list or role popups

I don’t have many screenshots of those, and memory does NOT serve me well. If you have anything, screenshots, clips, whatever—post them on this [server](https://discord.gg/aAHWPZHfs2). Even rough ones help a lot.


## ❗ Disclaimer

**NewerOldCord** is a fork of the original **OldCord** theme. With Discord rolling out a brand new UI, the old OldCord layout started to feel a bit outdated — so I decided to give it a refresh.

The goal of this project is to **update OldCord to better resemble the Discord UI that was just retired**, keeping the structure of the older layout while modernizing it to look more like the recent version that many users were familiar with.

I'm very much an **amateur** — not a CSS expert — and this is all built through trial, error, and lots of tweaking. This is not going to be a long term project, I'm only doing this for myself for now and sharing it. The theme will break with subsequent discord updates, I do not know if I'll have the motivation or will to fix issues that will arise in the future.

---

## 🔦 What This Theme Does

- Keeps the **classic Discord layout** based on OldCord.
- Updates visual styling to match the **previous (2024) Discord UI**

> ⚠️ **Light Mode is not supported.**  
> This theme was built for dark mode only — it hasn’t been tested or styled for light mode.

---

## 🛠 Installation

You can use this theme with **BetterDiscord**, **Vencord**, or any modded client that supports custom CSS.

---

### ✅ BetterDiscord (recommended)

1. [Download `NewerOldCord.theme.css`](https://frcynda.github.io/NewerOldCord/NewerOldCord.theme.css)
   (Right-click > "Save As") – uses GitHub Pages (`text/css`) so remote `@import` loads correctly.
   Legacy alt: [Download `NewerOldCord.css`](https://raw.githubusercontent.com/FrCynda/NewerOldCord/refs/heads/main/NewerOldCord.css)
2. Move it to your themes folder:  
   - **Windows**: `%appdata%/BetterDiscord/themes`  
   - **Linux**: `~/.config/BetterDiscord/themes`
3. Enable the theme in your BetterDiscord settings.

---

### ✅ Vencord

#### Local Installation:
1. [Download `NewerOldCord.theme.css`](https://frcynda.github.io/NewerOldCord/NewerOldCord.theme.css)
2. In Discord: `Settings > Vencord > Themes > Open Theme Folder`
3. Place the file in that folder and enable it.

#### Online Method (recommended):
1. Go to `Settings > Vencord > Themes`
2. Click “Add Theme” and paste this URL:

```
https://frcynda.github.io/NewerOldCord/src/main.css
```

Legacy alt (kept working):
```
https://raw.githubusercontent.com/FrCynda/NewerOldCord/refs/heads/main/src/main.css
```

---

### 🎛 Manual Import via CSS

Recommended (GitHub Pages, works in BetterDiscord + Vencord):

```css
@import url("https://frcynda.github.io/NewerOldCord/src/main.css");
```

Legacy alt (kept working, Vencord / direct download):

```css
@import url("https://raw.githubusercontent.com/FrCynda/NewerOldCord/refs/heads/main/src/main.css");
```
