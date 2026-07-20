# AnuPpuccin Premium Mod: Distraction-Free & AMOLED Dark 🎨✨

![Main Preview](screen/D1.png)

Welcome to the **AnuPpuccin Premium Mod**! 
While the original [AnuPpuccin theme](https://github.com/AnubisNekhet/AnuPpuccin) is an absolute masterpiece, I created this modification snippet to push it toward a more highly-focused, premium, and distraction-free workflow. 

My goal is simple: to create the ultimate reading and studying environment for students, kids, and researchers, helping future generations focus solely on their knowledge without visual clutter.

---

## 📊 Development Status & Focus

**Built for personal use, shared with the world.** 
I initially built this mod purely for my personal workflow. Because of my preferences, the development and continuous improvements are **heavily focused on the Dark Mode**. 

Both modes are highly functional, but here is the exact current completion status:

| Theme Mode | Completion | Status |
| :--- | :--- | :--- |
| ☀️ **Light Mode** | **95%** | Almost perfect, minor UI refinements remaining. |
| 🌙 **Dark Mode** | **85%** | Highly functional, ongoing development to reach perfection. |

*Note: Work is actively ongoing to hit 100% for both modes!*

---

## ⚠️ Compatibility & Testing Warning

This theme has been rigorously tested and optimized on the following operating systems:
*   🐧 **Fedora (Linux)**
*   🪟 **Windows**
*   🤖 **Android**

**Untested Platforms:** macOS and iOS (iPhone/iPad). 
Because Obsidian uses universal CSS rendering, the theme is expected to work **80% to 97% flawlessly** on Apple devices as well, but I haven't personally verified it. 

*Go ahead and try it out—you have absolutely nothing to lose!*

---

## 🎯 Try It Instantly! (The Preview Vault)

Don't want to mess with your own vault's settings just yet? No problem! 
I have included a ready-to-use demo vault in this repository so you can test the theme immediately.

1. Download or clone this repository to your device.
2. Open Obsidian and select **Open folder as vault**.
3. Choose the `preview` folder included in this repo.
4. Enjoy exploring the theme, checking the colors, and testing the layouts right away!

---

## 🌟 What Makes This Mod Different? (Comparison)

If you love AnuPpuccin but want something cleaner, this mod is for you. Here is how it compares to the default theme:

| Feature | Default AnuPpuccin | This Custom Mod |
| :--- | :--- | :--- |
| **Dark Mode** | Dark gray / Soft dark | **True Pitch Black (`#000000`)** for OLED/AMOLED battery saving. |
| **Workspace Borders** | Visible structural lines | **Completely Borderless**. Floating elements and clean spacing. |
| **Mobile Toolbar** | Attached to the keyboard | **Floating Glassmorphism Capsule** (iOS-style) at the bottom. |
| **Settings UI** | Standard Obsidian lists | **Card-based Layout** with smooth iOS-style sliding switches. |
| **Code Blocks** | Boxy with visible lines | **Seamless & Rounded** with custom syntax highlight colors. |
| **Headings** | Standard folding arrows | **Invisible Floating Arrows** that appear instantly on hover. |

---

## 📸 Theme Gallery

Take a look at how the theme completely transforms your Obsidian workspace:

<div align="center">
  <img src="screen/D2.png" width="49%">
  <img src="screen/D3.png" width="49%">
  <img src="screen/D4.png" width="49%">
  <img src="screen/D5.png" width="49%">
  <img src="screen/D6.png" width="49%">
  <img src="screen/D7.png" width="49%">
  <img src="screen/D8.png" width="49%">
  <img src="screen/D9.png" width="49%">
  <img src="screen/D10.png" width="49%">
  <img src="screen/D11.png" width="49%">
  <img src="screen/D12.png" width="49%">
  <img src="screen/D13.png" width="49%">
  <img src="screen/D14.png" width="49%">
</div>

---

## 📦 What's Inside? (File Structure)

I have organized the modifications into modular files so you can easily understand and use what you need:

*   📁 `preview/`: A fully working Obsidian demo vault to test the theme safely.
*   📁 `snippets/`:
    *   `anuppuccin-custom-tweaks.css`: The core engine. Contains the Pitch Black UI, heading colors, border removals, custom callouts, and mobile UI upgrades.
    *   `code-blocks-colors.css`: Dedicated styling for syntax highlighting and seamless code block rendering.
    *   `os-default-fonts.css`: Forces Obsidian to use your device's native system fonts and emojis for maximum performance and native feel.
*   📄 `style-settings-export.json`: My personal configuration file for the Style Settings plugin.
*   📁 `screen/`: Contains all the showcase screenshots.

---

## 🛠️ Requirements (For your own Vault)

Before installing this in your personal vault, make sure you have:
1. The **AnuPpuccin** theme installed and applied in Obsidian.
2. The **Style Settings** plugin installed from the Obsidian Community Plugins.

---

## 🚀 Installation Guide

### Step 1: Import the Configuration (Crucial)
To get the exact colors and layout shown in the screenshots, you need to import my settings:
1. Open Obsidian and ensure the **Style Settings** plugin is enabled.
2. Open the `style-settings-export.json` file from this repository and copy all its contents.
3. Go to **Obsidian Settings > Style Settings**.
4. Click the **Import** button at the top.
5. Paste the copied text and hit **Save**.

### Step 2: Install the CSS Snippets

**💻 On Desktop (Windows/Mac/Linux):**
1. Download the `.css` files from the `snippets/` folder in this repo.
2. Open Obsidian and go to **Settings > Appearance**.
3. Scroll down to **CSS Snippets** and click the folder icon to open `.obsidian/snippets/`.
4. Move the downloaded `.css` files into this folder.
5. Refresh the list in Obsidian and toggle them **ON**.

**📱 On Mobile (Android & iOS):**
1. Download the `.css` files to your device.
2. Navigate to your vault folder: `.obsidian/snippets/`. *(Create the `snippets` folder if it doesn't exist. On iOS, you may need to use the native Files app or a third-party app to view hidden folders).*
3. Paste the `.css` files there.
4. Open the Obsidian app > Settings > Appearance > Toggle the snippets **ON**.

---

## 🐛 Known Bugs

As mentioned, I am building this project in my free time. I don't have the time to reach absolute perfection on my own, but I am getting there. 

**Here are the current known issues:**
- [ ] **Mobile Dark Mode:** The files menu background appears transparent.
- [ ] **Code Editor:** The Live Preview code editor styling in Dark Mode needs refinement across all versions.
- [ ] **Mobile Tables:** The table styling in Dark Mode on mobile doesn't perfectly match the sleek desktop version.

---

## 🤝 Contributing

This is an open-source project powered by the community. Contributions are highly welcome for:

*   New CSS features and UI tweaks
*   Better mobile and tablet workflows
*   Documentation improvements
*   Bug fixes (especially the ones listed above!)
*   Performance and cross-device optimizations

Feel free to open an Issue or submit a Pull Request. Let's collaborate to make this the perfect study environment for everyone!

---

## 📜 License

This project is released under the **MIT License**.

You are free to:
*   Use
*   Modify
*   Distribute
*   Fork

...for both personal and commercial projects. 

*(Disclaimer: This is a CSS modification snippet and is not affiliated with the official AnuPpuccin theme creators. Full credit goes to [AnubisNekhet](https://github.com/AnubisNekhet) for the amazing foundational theme!)*

---

## 💖 Support

If you find this project useful, consider supporting its development. Every contribution helps improve features, maintain the project, and keep it accessible for everyone. 🌍✨

<p align="left">
  <a href="https://www.buymeacoffee.com/mohsenofficial" target="_blank">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me a Coffee" width="200">
  </a>
</p>

---

### Final Thoughts 💭
Built for my own needs, shared for the community. If it happens to help someone else, then it has done more than I originally intended. 

Built with passion, curiosity, countless hours of learning, and a deep love for open-source software. 

Thank you for using this project and being part of its journey. 🤟🏼😘
