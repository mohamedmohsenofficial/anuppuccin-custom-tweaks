# AnuPpuccin Premium Mod 🎨✨

![Main Preview](Screen/D1.png)
![Main Preview](Screen/D2.png)

Welcome to **AnuPpuccin Premium Mod**! 

The original [AnuPpuccin theme](https://github.com/AnubisNekhet/AnuPpuccin) is amazing, but I wanted something more focused and clean. So I built this modification to create a premium, distraction-free workspace.

**My goal?** Build the perfect reading and studying environment for students, researchers, and anyone who wants to focus on what matters—without visual clutter.

---

## Current Status

**Built for myself, shared with everyone.** 

I made this for my own workflow, and I use **Dark Mode** exclusively. That's why Dark Mode gets most of my attention. Both modes work great, but here's where they stand:

| Theme Mode | Completion | Status |
| :--- | :--- | :--- |
|  **Light Mode** | **95%** | Nearly perfect, just tiny tweaks left |
|  **Dark Mode** | **85%** | Works great, actively improving it |

*Still working toward 100% on both!*

---

## What's Tested (And What's Not)

**Tested & Working:**
*   **Fedora (Linux)**
*   **Windows**
*   **Android**

**Not Tested Yet:** macOS and iOS (iPhone/iPad)

Since Obsidian uses standard CSS, it should work **80-97% perfectly** on Apple devices too—I just haven't tested it myself. 

*Worth trying! You've got nothing to lose.*

---

## Quick Test (No Setup Required)

Don't want to touch your current vault settings? No problem!

I included a ready-to-use demo vault so you can see the theme in action immediately:

1. Download or clone this repo
2. Open Obsidian → **Open folder as vault**
3. Select the `preview.zip` zip file amd extract it
4. Start exploring—colors, layouts, everything!

---

## How This Differs From Default AnuPpuccin

Love AnuPpuccin but want it cleaner? This is for you.

| Feature | Default AnuPpuccin | This Mod |
| :--- | :--- | :--- |
| **Dark Mode** | Dark gray / Soft dark | **True Black (`#000000`)** — saves battery on OLED screens |
| **Borders** | Visible lines everywhere | **Borderless** — clean, floating elements |
| **Mobile Toolbar** | Stuck to keyboard | **Floating glass capsule** (iOS-style) |
| **Settings** | Plain lists | **Card layout** with smooth iOS toggles |
| **Code Blocks** | Boxy with borders | **Seamless & rounded** with custom colors |
| **Headings** | Always-visible arrows | **Hidden arrows** that show on hover only |

---

## Screenshots

See how this transforms your workspace:

<div align="center">
  <img src="Screen/D3.png" width="49%">
  <img src="Screen/D4.png" width="49%">
  <img src="Screen/D5.png" width="49%">
  <img src="Screen/D6.png" width="49%">
  <img src="Screen/D7.png" width="49%">
  <img src="Screen/D8.png" width="49%">
  <img src="Screen/D9.png" width="49%">
  <img src="Screen/D10.png" width="49%">
  <img src="Screen/D11.png" width="49%">
  <img src="Screen/D12.png" width="49%">
  <img src="Screen/D13.png" width="49%">
  <img src="Screen/D14.png" width="49%">
</div>

---

## What's Inside

Everything is organized in separate files so you can pick what you need:

*   📁 **`preview/`** — Complete demo vault to test safely
*   📁 **`Screen/`** — All screenshots
*    **`snippets/`** — The actual CSS modifications:
    *   `anuppuccin-custom-tweaks.css` — Core stuff: black UI, colors, border removal, mobile improvements
    *   `code-blocks-colors.css` — Syntax highlighting & code block styling
    *   `os-default-fonts.css` — Uses your system fonts for better performance
*   📄 **`style-settings-export.json`** — My exact Style Settings config

---

## Before You Install

Make sure you have:

1. **AnuPpuccin theme** installed and active in Obsidian
2. **Style Settings plugin** installed (from Community Plugins)

---

## Installation

### Step 1: Import My Settings (Important!)

To get the exact look from the screenshots:

1. Open Obsidian → Enable **Style Settings** plugin
2. Open `style-settings-export.json` from this repo → Copy everything
3. Go to **Settings → Style Settings**
4. Click **Import** (top of page)
5. Paste → Click **Save**

### Step 2: Add CSS Snippets

**Desktop (Windows/Mac/Linux):**

1. Download `.css` files from `snippets/` folder
2. Obsidian → **Settings → Appearance**
3. Scroll to **CSS Snippets** → Click folder icon 📁
4. Drop the `.css` files into that folder
5. Go back to Obsidian → Click refresh → Toggle all snippets **ON**

** Mobile (Android & iOS):**

1. Download `.css` files to your phone
2. Go to your vault → `.obsidian/snippets/` - hidden folders
   *   *Create `snippets` folder if missing*
   *   *iOS: Use Files app or a file manager to see hidden folders*
3. Paste `.css` files there
4. Obsidian app → **Settings → Appearance** → Turn snippets **ON**

---

## Known Issues

Building this in my free time, so perfection takes time. Here's what still needs work:

- [ ] **Mobile Dark Mode:** Files menu background is transparent
- [ ] **Code Editor:** Live Preview styling in Dark Mode needs polish
- [ ] **Mobile Tables:** Don't look as clean as desktop version yet

---

## 🤝 Want to Help?

This is community-powered. All contributions welcome:

*   New CSS features or UI improvements
*   Better mobile/tablet support
*   Documentation fixes
*   Bug fixes (especially the ones above!)
*   Performance tweaks

Open an issue or submit a PR. Let's build the perfect study tool together!

---

## License

**MIT License** — do whatever you want with it.

Use it, modify it, share it, fork it — personal or commercial, no restrictions.

*(Note: This is a CSS mod, not official AnuPpuccin. Huge thanks to [AnubisNekhet](https://github.com/AnubisNekhet) for the base theme!)*

---

## 💖 Support the Project

If this helps you, consider supporting development. Every bit helps keep this free and improving. 🌍✨

<p align="left">
  <a href="https://www.buymeacoffee.com/mohsenofficial" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" width="200">
  </a>
</p>

---

### Final Words 💭

I built this for myself. If it helps you too, that's even better.

Made with curiosity, late-night coding sessions, and love for open-source.

Thanks for using it and being part of this journey. 🤟😘
