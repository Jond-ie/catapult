<div align="center">

<img src="icon.png" width="120">

# Catapult

**The LineageOS launcher as your iPhone's Home Screen.**<br>
Android's Trebuchet home screen, app drawer and folders, running in place of iOS's, with Apple's own app open and close animations.

[![Release](https://img.shields.io/github/v/release/Jond-ie/catapult?include_prereleases&label=release&color=4db6ac)](../../releases)
![iOS 15–18](https://img.shields.io/badge/iOS-15–18-555)
![Jailbreak](https://img.shields.io/badge/rootless-.deb-555)

**[Download](../../releases)** · **[Sileo repo](https://jond-ie.github.io/repo)** · **[Report a bug](../../issues)** · **[X @Jond_ie](https://x.com/Jond_ie)**

<!-- screenshots go here: <img src="screenshots/home.png" width="24%"> … (status bar cropped) -->

</div>

Catapult swaps the iOS Home Screen for **Trebuchet**, the launcher from LineageOS. Everything else on your iPhone stays iOS.

> **Public beta: 0.1.0 Beta 1.**
> This repo holds the releases and the issue tracker; Catapult's own source code isn't published.
> It's built on [MakrSas's Trebuchet port](https://github.com/MakrSas/Trebuchet), credits below.

### Highlights
- **The real Trebuchet layout**: grids, dock, page dots and page transitions, ported from LineageOS's own code
- **App drawer** with search that also does maths, unit conversions and web searches
- **Folders** that open on one page, with Android's folder animations
- **Widgets made for it**: Clock, Weather, Now Playing and Batteries (AirPods too), in several sizes
- **Icon shapes and themes**, optionally across all of iOS
- **Your own font** (.ttf / .otf), optionally across all of iOS, with emoji left alone

---

## Install

Add **`https://jond-ie.github.io/repo`** in Sileo or Zebra and install **Catapult**, or grab the `.deb` from **[Releases](../../releases)**.

- **Rootless jailbreaks** (Dopamine, palera1n…), **iOS 15 to 18**.
- Installing Catapult replaces MakrSas's Trebuchet if you have it.
- Something wrong after installing? Catapult has a **safe mode**: if SpringBoard crashes 5 times in a row right after starting, Catapult turns itself off and you get the stock Home Screen back. Normal resprings don't count.

---

## Features

### Home screen
- Trebuchet's grid sizes, dock and page indicator, with an optional search bar on the dock or at the top.
- Apps open from and close back into their icon with **Apple's own zoom**, from the home screen, the dock, folders and the app drawer.
- Notification dots, long-press shortcuts (the app's own quick actions) and hidden apps.
- Drag icons, folders and widgets around the pages.

### App drawer
- All your apps A to Z with fast scroll.
- **Search** finds apps, answers sums and unit conversions, and searches the web in the browser you pick.

### Widgets
- **Clock**, **Weather**, **Now Playing** and **Batteries** (iPhone, AirPods and other connected devices), in several sizes, styled with Material You colours.

### Themes
- **12 icon shapes** from Android (circle, squircle, cookie, pebble and more).
- **Icon themes**: use theme folders you already have. Turn on **Theme icons across iOS** to theme the app switcher, Spotlight, Settings and notifications too. If you use FrostBoard, SnowBoard or Anemone, Catapult leaves system-wide theming to them.
- **Fonts**: pick a .ttf or .otf for the launcher, and turn on **Use this font across iOS** to make it your system font. Emoji and symbols stay Apple's. If the font's other weights (Bold, Medium…) sit in the same folder, bold text uses them.
- Pairs with **Material You** (MakrSas) for wallpaper-based colours.

---

## Tested on

| iOS | Phones |
|---|---|
| iOS 15.8.6 | iPhone 7 |
| iOS 16.2 / 16.7 | iPhone 11 Pro Max, iPhone 8 Plus |
| iOS 17.5.1 | iPhone SE (2nd generation) |
| iOS 18 | iPhone 11 Pro |

Not tested yet: iPads, landscape, and iOS 15 on iPhone XS and newer. Reports welcome.

## Known issues (Beta 1)
- iOS's own widgets can't be placed on the home screen. Catapult has its own widgets instead.
- Portrait only.

## Bugs and ideas
Open an **[issue](../../issues)** with your iPhone model, iOS version, jailbreak, and what happened.

---

<details>
<summary><b>Credits and licences</b></summary>

- **[MakrSas](https://github.com/MakrSas)**: the original Trebuchet port to iOS that Catapult is built on ([MakrSas/Trebuchet](https://github.com/MakrSas/Trebuchet), Apache 2.0), LineageQS, and Material You.
- **LineageOS and the Android Open Source Project**: Trebuchet and Launcher3 (layouts, grids, folders, app drawer, icon shapes, motion and artwork), Apache 2.0.
- **Roboto Flex** by Google, SIL Open Font License.

Catapult is a modified version of MakrSas's port. The full notices and licences are in [third-party/](third-party/) and are installed with the package.
</details>
