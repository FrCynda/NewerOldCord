# NewerOldCord

**A personal project to bring back the previous Discord UI.**
_NewerOldCord is a fork of [OldCord](https://github.com/milbits/oldcord), revamped to look more like the Discord interface that was just replaced — keeping the classic layout, but updating the visuals to feel more in line with recent design._

## Preview

![Preview](https://github.com/FrCynda/NewerOldCord/blob/main/compare.png)

## What this theme does

- Keeps the **classic Discord layout** based on OldCord.
- Updates visual styling to match the **previous (2024) Discord UI**.

Note: **Light Mode is not supported.**
This theme was built for dark mode only — it hasn't been tested or styled for light mode.

Disclaimer: this is a personal project built through trial and error. The theme can break with Discord updates, and fixes depend on available time and motivation.

## Structure

- `src/main.css` - importer only (header + 3 upstream OldCord imports + local modules)
- `src/theme-vars.css`, `src/fonts.css`, `src/chat.css`, `src/sidebar.css`, `src/popouts.css`, `src/tweaks.css` - the theme split from QuickCSS v1.1
- `NewerOldCord.css` - legacy wrapper importing `src/main.css` via raw (kept for existing users)
- `NewerOldCord.theme.css` - recommended wrapper importing `src/main.css` via GitHub Pages (correct `text/css` MIME for BetterDiscord)

## Upstream imports

Only 3 upstream OldCord files are used (deliberately excludes `color.css`, `imgs.css`, `profile.css`):

```css
@import url("https://milbits.github.io/oldcord/src/components/other.css");
@import url("https://milbits.github.io/oldcord/src/components/redesign.css");
@import url("https://milbits.github.io/oldcord/src/components/vars.css");
```

Track upstream manually (this repo is a fork, but local clones can compare like this):

```
git remote add upstream https://github.com/milbits/oldcord.git
git fetch upstream
```

## Installation

You can use this theme with **BetterDiscord**, **Vencord**, or any modded client that supports custom CSS.

### BetterDiscord (recommended)

1. [Download `NewerOldCord.theme.css`](https://frcynda.github.io/NewerOldCord/NewerOldCord.theme.css)
   (Right-click > "Save As") – uses GitHub Pages (`text/css`) so remote `@import` loads correctly.
   Legacy alt: [Download `NewerOldCord.css`](https://raw.githubusercontent.com/FrCynda/NewerOldCord/refs/heads/main/NewerOldCord.css)
2. Move it to your themes folder:
   - **Windows**: `%appdata%/BetterDiscord/themes`
   - **Linux**: `~/.config/BetterDiscord/themes`
3. Enable the theme in your BetterDiscord settings.

### Vencord

Local installation:

1. [Download `NewerOldCord.theme.css`](https://frcynda.github.io/NewerOldCord/NewerOldCord.theme.css)
2. In Discord: `Settings > Vencord > Themes > Open Theme Folder`
3. Place the file in that folder and enable it.

Online method (recommended):

1. Go to `Settings > Vencord > Themes`
2. Click "Add Theme" and paste this URL:

```
https://frcynda.github.io/NewerOldCord/src/main.css
```

Legacy alt (kept working):

```
https://raw.githubusercontent.com/FrCynda/NewerOldCord/refs/heads/main/src/main.css
```

### Manual import via CSS

Recommended (GitHub Pages, works in BetterDiscord + Vencord):

```css
@import url("https://frcynda.github.io/NewerOldCord/src/main.css");
```

Legacy alt (kept working, Vencord / direct download):

```css
@import url("https://raw.githubusercontent.com/FrCynda/NewerOldCord/refs/heads/main/src/main.css");
```

## Need old UI screenshots

I'm missing a lot of visual references from the old Discord UI for this theme. Stuff like:

    Pinned messages
    Inbox / Mentions
    Server settings
    Notification dropdowns
    User popouts / profiles
    Member list or role popups

I don't have many screenshots of those. If you have anything, screenshots or clips, post them on this [server](https://discord.gg/aAHWPZHfs2). Even rough ones help.
