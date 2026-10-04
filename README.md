# Awesome-Android-Launcher

# Awesome-Android-Launcher

**Curated List of Commercial Launchers & Open-Source GitHub Projects**
*Focused on Minimalism, Search-First Navigation & Digital Wellbeing*
**Last updated: October 2026**

This repository tracks notable **commercial launchers** and **open-source projects** for Android home screen replacement. These tools help users replace their stock launcher with minimal, search-first, or highly customizable alternatives that improve focus and reduce screen time.

**Examples** include Nova Launcher, Niagara Launcher, Smart Launcher, Action Launcher, Lawnchair, AIO Launcher, POCO Launcher, Apex Launcher, Hyperion Launcher, and Microsoft Launcher (the category leaders).

**Open-source emphasis**: The Android launcher ecosystem has a **vibrant open-source community**, though the most polished options often balance open and closed development. **Lawnchair** (Apache-2.0) leads the open-source field as a Pixel Launcher replacement with **13,383 stars**, offering Material You support, At a Glance widget, and Nova Launcher backup import . **Victoria Launcher** (GPL-3.0) provides an open-source alternative to Niagara Launcher with list-based navigation and customizable fonts . **Slate** (FOSS) takes minimalism to its logical extreme—a blank canvas where you place every icon yourself . **KISS Launcher**, **Olauncher**, and **Escape Launcher** prioritize search-first navigation and digital wellbeing over visual customization . This section documents these production-grade solutions.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [Commercial Launchers](#commercial-launchers)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Commercial Launchers

- **[Nova Launcher](https://novalauncher.com/)**  
  **The long-time standard for Android customization, now free but ad-supported.** Provides extensive gesture controls, icon pack support, customizable grids, and scroll effects. **2026 note**: Nova Launcher was sold a second time; the future is "secure" but the launcher now includes advertising .

- **[Niagara Launcher](https://niagaralauncher.app/)**  
  **The leading list-based launcher for one-handed use and minimalism.** Replaces app icons with an alphabetized list and favorites. **Niagara Pro** adds more themes, pop-up folders, custom clock/fonts, usage breakers, and widget stacking . Free version is ad-free.

- **[Smart Launcher](https://smartlauncher.net/)**  
  **Auto-categorized app drawer with a distinctive flower-style home screen.** Groups apps by category automatically for faster discovery .

- **[Action Launcher](https://actionlauncher.com/)**  
  **Quick Covers and Shutters for efficient access to apps and widgets.** Provides "Quick Covers" that turn icons into folders, and "Shutters" that reveal widgets without leaving the home screen .

- **[Hyperion Launcher](https://hyperionlauncher.dev/)**  
  **Modern launcher with a focus on customization and performance.** Community-recommended alternative as Nova Launcher's future became uncertain .

- **[POCO Launcher](https://www.mi.com/global/poco-launcher/)**  
  Xiaomi's launcher for POCO devices, known for speed, clean layout, and app drawer categorization.

- **[Apex Launcher](https://apexlauncher.com/)**  
  Classic third-party launcher with extensive customization options and icon pack support.

- **[Microsoft Launcher (Android)](https://www.microsoft.com/en-us/launcher)**  
  **Windows-integrated Android launcher with productivity focus.** Provides customizable feeds, family safety features, and cross-device integration with Windows .

- **[AIO Launcher](https://aiolauncher.com/)**  
  **Information-dense launcher with widgets and news feeds.** Popular for users who want their home screen to surface useful information at a glance.

## Open-Source GitHub Projects

### Pixel-Style & Customizable Launchers

- **[Lawnchair](https://github.com/LawnchairLauncher/lawnchair)**  
  **The leading open-source Pixel Launcher replacement.** **Apache-2.0 licensed**, **13,383 GitHub stars** . Built on Launcher3 from the Android Open Source Project, it ports Pixel Launcher features while adding extensive customization. **Key features**: **Material You theming** that follows wallpaper and system colors ; **At a Glance widget** with Smartspacer integration ; **App Drawer Folders** (manual or auto-categorized via Caddy) ; **Nova Launcher backup import** (home screen/dock grid, widgets, folders, icon pack) ; rich grid and icon customization; global search for apps, contacts, and web ; QuickSwitch support for Android Recents (root required) . **Available on Play Store and GitHub** . **Tradeoffs**: Still in beta; foldable support is a work in progress; some features may lag behind closed-source competitors . **Best for**: Users wanting the Pixel look with deeper customization and open-source transparency.

- **[Victoria Launcher](https://github.com/adelmonte/victoria-launcher)**  
  **Open-source alternative to Niagara Launcher with list-based navigation.** **GPL-3.0-or-later licensed** . **Key features**: **Minimal list-based home screen** with favorites under a clock and weather widget; **A-Z scrubber** on screen edges for jumping to letters; **Custom fonts** (pick any .ttf or .otf file); **Themed icons** for apps that ship monochrome icons (Android 13+); **Icon shapes** (circle, rounded, square); **Work profile and private space support**; **No ads, no tracking, no network access** . **Requirements**: Android 8.0+ . **Best for**: Users wanting Niagara Launcher's list-based approach without proprietary software.

### Minimalist & Digital Wellbeing Launchers

- **[Slate](https://github.com/braniik/slate)**  
  **FOSS minimal launcher focused on simplicity and tailored experience.** **Key philosophy**: "Most launchers are too bloated. Slate does the opposite—you start with nothing and add what you want, where you want it. You just launch apps." . **Key features**: **Freescreen mode** (place icons anywhere at any coordinate with optional guide lines); **List mode** (vertical or horizontal scrolling list); **Per-app customization** (icon size, label visibility, text size, icon shape, rotation, wallpaper); **Icon shapes** (round, square, squircle, hexagon, octagon); **Icon rotation** (-360° to 360°); **Icon pack support** (ADW, Nova, Apex, GO, Tesla); **Work profile support** (Shelter, Island) . **Installation**: F-Droid or GitHub releases . **Best for**: Users wanting a blank-canvas launcher where every icon placement is intentional.

- **[Escape Launcher](https://github.com/)**  
  **Open-source minimalist launcher focused on reducing screen time.** **Key features**: **Text-based home screen** showing time, date, battery percentage, and a short list of apps (no icons); **Usage statistics screen** (swipe left) showing daily screen time, comparison to recommended threshold, and per-app breakdown; **Five-second countdown** for problematic apps—the delay often breaks the impulse to open . **Available on F-Droid** . **Best for**: Users wanting intentional friction to reduce compulsive phone use.

- **[KISS Launcher](https://github.com/Neamar/KISS)**  
  **Search-first minimalist launcher with almost no battery usage.** **Key features**: **Search bar home screen**—type two letters and matching apps, contacts, web searches, or unit conversions appear; **Learns most-used apps** and floats them up in suggestions; **Open source, available on F-Droid, no in-app purchases** . **Tradeoffs**: Blank-screen aesthetic is jarring at first; customization is intentionally minimal . **Best for**: Users who want to search for apps rather than browse icons.

- **[Olauncher](https://github.com/tanujnotes/Olauncher)**  
  **Lightweight, open-source minimalist launcher.** **Key features**: **Text-only home screen** showing time, date, battery, and a short list of apps (no icons); **Swipe up** for full app list navigable by typing app names; **Hide problematic apps**; **Disable status bar** to avoid notification dots . **Best for**: Users wanting the simplest possible launcher.

- **[Discreet Launcher](https://github.com/Vincent-Falzon/DiscreetLauncher)**  
  **Open-source launcher focused on a distraction-free home screen.** **Key features**: **Clean home screen** to enjoy wallpaper; **Swipe down** for favorite apps, **swipe up** for full app list; **Long-press for system settings and store page**; **Directories, search, rename, hide apps**; **Notification for favorites access**; **Horizontal swipe or double-tap to open apps**; **Web shortcut support**; **Theme and color customization**; **Icon pack support** . **Requires Android 5.0+** . **Available on F-Droid** . **Best for**: Users wanting a simple, offline, ad-free launcher with essential features.

### Additional Strong Open-Source Options

- **Pixel-Style**: **Lawnchair** (Apache-2.0, 13k+ stars, Nova import), **Neo Launcher** (FOSS, highly customizable) .
- **List-Based**: **Victoria Launcher** (GPL-3.0, Niagara alternative), **KISS Launcher** (search-first) .
- **Minimalist**: **Slate** (blank canvas), **Escape Launcher** (digital wellbeing), **Olauncher** (text-only), **Discreet Launcher** (distraction-free) .
- **Note**: **OpenLauncher** (2k stars) appears unmaintained as of 2026 (no commits in 90+ days) .

**Frameworks for building custom systems**: Combine **Lawnchair** for a Pixel-style foundation with deep customization and Nova backup import, **Victoria Launcher** for list-based one-handed navigation, **Slate** for a blank-canvas minimalist approach, and **Escape Launcher** or **Olauncher** for digital wellbeing features. Add **F-Droid** for privacy-respecting distribution and **Obtainium** for automatic updates from GitHub releases.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's commercial or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Launchers replace your Android home screen and may require accessibility permissions for certain features; review privacy policies and permission requests before installing.
- **Open-source reality**: The Android launcher ecosystem has **mature open-source alternatives** at both the **Pixel-style** (**Lawnchair**, 13k+ stars, Apache-2.0) and **list-based** (**Victoria Launcher**, GPL-3.0) layers. **Slate**, **Escape Launcher**, **Olauncher**, and **Discreet Launcher** serve minimalist and digital wellbeing use cases . **Nova Launcher**, once the customization king, is now ad-supported after two acquisitions—making open-source alternatives more attractive than ever . **OpenLauncher** appears unmaintained as of 2026 . The open-source path is **genuinely viable** for users wanting privacy-respecting, ad-free launchers with full control over their home screen experience.

---

**Made for Android users, digital minimalists, and open-source enthusiasts.**
Let's make Android home screens more open, intentional, and distraction-free.
