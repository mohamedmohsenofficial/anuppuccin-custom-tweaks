# AnuPpuccin Custom Tweaks (Obsidian CSS Snippet) 🎨✨

Welcome! I’ve been using the amazing [AnuPpuccin](https://github.com/AnubisNekhet/AnuPpuccin) theme for Obsidian, but as a heavy user, I found myself constantly tweaking the CSS to make it fit a more highly-focused, premium, and distraction-free workflow. 

After refining this code for a long time, I decided to compile all my modifications into a single, clean CSS snippet. This snippet doesn't replace AnuPpuccin; it sits on top of it, enhancing the UI, typography, and mobile experience without breaking the core theme.

## 🚀 Features (What's Inside?)

I completely organized and rebuilt the custom CSS into 10 distinct architectural modules. Here is exactly what this snippet modifies:

### 1. Light Theme Core ☀️
- Restyled basic typography, headings (H1 to H6), and hyperlinks with specific, high-contrast hex colors (e.g., Deep Navy Blue for H1s, Crimson for H2s).
- Added crisp bottom borders for H1s and refined inline title colors for a cleaner reading experience.

### 2. Pitch Black Dark Theme 🌙
- Completely replaced the standard dark gray backgrounds with **True Pitch Black (`#000000`)** for OLED screens and ultimate contrast.
- Custom neon-accented heading colors (Blues, Reds, Oranges) that pop beautifully against the black workspace.
- Redesigned active tabs, sidebars, and title bars to blend seamlessly into the pitch-black aesthetic.

### 3. Typography & Markdown Upgrades 📝
- Custom blockquotes with left-border accents matching the theme mode.
- Sleek, custom horizontal rules (`hr`) with tailored spacing.
- Redesigned text highlights with a nice yellow background and precise padding for both desktop and mobile.

### 4. Custom Callouts & Tables 📊
- Re-engineered Obsidian Callouts (note, tip, important, caution, warning) with custom RGB variables and refined opacity for borders and backgrounds.
- Stripped bulky table borders and replaced them with elegant, semi-transparent borders for a minimalist data view.

### 5. UI, Menus, & Settings Elegance 🎛️
- **File Explorer:** Removed native bulky borders, added smooth hover effects, and introduced custom left-border highlights for nested folders.
- **Settings UI:** Completely overhauled the settings menu for the Dark theme. Settings are now neat cards with rounded corners, and native inputs/dropdowns are heavily customized.
- **Context Menus:** Added subtle borders and hover states to dropdowns and suggestion containers. Light mode menus get a classy warm tint, while Dark mode menus get a deep shadow effect.

### 6. Properties & Tags (Metadata) 🏷️
- Colored tag pills based on the active theme (Solid Blue for Light, Bright Blue for Dark).
- Simplified "Related" properties to look like clean, underlined hyperlinks instead of bulky pills.
- Removed ugly borders and backgrounds from native metadata input fields for a cleaner frontmatter look.

### 7. Code Blocks & Syntax Highlighting 💻
- **Live Preview Fixes:** Stripped out annoying default borders, margins, and pseudo-elements from Live Preview code blocks.
- **Dark Mode Code:** Gave code blocks a distinct dark background (`#111111`) with rounded corners (`12px`) and subtle borders.
- Custom syntax highlighting colors (Strings, Keywords, Functions, Comments) specifically picked to reduce eye strain.

### 8. Toggles, Buttons & Canvas 🔘
- **iOS-Style Toggles:** Replaced native Obsidian checkboxes in the settings with smooth, capsule-shaped iOS-style toggle switches (with sliding animations!).
- Colored CTA buttons and matched Mermaid diagram paths/strokes to the primary theme colors.
- Custom dot-pattern background and colored edges for Obsidian Canvas.

### 9. Smart Heading Collapse Indicators 🔽
- Built a custom, absolute-positioned floating arrow system for folding headings.
- The arrows perfectly inherit the exact color of their specific heading level (H1-H6).
- Arrows remain completely invisible to reduce clutter, instantly appearing via a smooth opacity transition *only* when you hover over the heading.

### 10. Mobile & Tablet Overhaul 📱
- **Pure Black Drawers:** Mobile sidebars and menus are now pure black in dark mode.
- **Floating Capsule Toolbar:** The mobile formatting toolbar detaches from the keyboard and becomes a floating, glassmorphism-style capsule at the bottom of the screen (similar to iOS UI).
- Removed unnecessary structural borders across the mobile workspace to maximize screen real estate.

## 🛠️ How to Install

1. Make sure you have the [AnuPpuccin theme](https://github.com/AnubisNekhet/AnuPpuccin) installed and activated in Obsidian.
2. Download the `anuppuccin-custom-tweaks.css` file from this repository.
3. Open your Obsidian vault folder.
4. Navigate to `.obsidian/snippets/` (Create the `snippets` folder if it doesn't exist).
5. Paste the downloaded `.css` file inside the `snippets` folder.
6. Open Obsidian **Settings > Appearance**.
7. Scroll down to **CSS Snippets** and toggle on `anuppuccin-custom-tweaks`.
8. Enjoy! ☕

## 🤝 Contributing & Modifying
Feel free to fork this repository, tweak the hex codes to your liking, or open an issue if an Obsidian update breaks a specific class. I organized the CSS into 10 clearly commented sections so you can easily find and change what you need.

---
*Disclaimer: This is a CSS modification snippet and is not affiliated with the official AnuPpuccin theme creators. Full credit goes to [AnubisNekhet](https://github.com/AnubisNekhet) for the amazing foundational theme!*
