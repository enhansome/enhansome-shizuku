# awesome-shizuku with stars

### Languages

English | [简体中文](/README_cn.md) | [繁體中文](/README_tw.md)

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 496,259 | 🐛 100 | 📅 2026-06-30

Shizuku allows normal apps to use system APIs directly with elevated privileges using ADB on non-rooted devices. This list compiles a few apps that are known to make use of Shizuku's capabilities.

More details: <https://shizuku.rikka.app/>

Pull requests are welcome. See [Contributing](CONTRIBUTING.md) for hints. Closed-source apps are listed in a separate file. See [below](#closed-source-apps) for details.

> \[!NOTE]
> To stay up-to-date with this list, [you can check the daily changelogs](https://github.com/timschneeb/changelog-awesome-shizuku) ⭐ 89 | 🐛 0 | 📅 2026-08-07.

***

## Table of contents

* [Apps](#apps)
  * [AI agents](#ai-agents)
  * [Android TV](#android-tv)
  * [Audio](#audio)
  * [Automation](#automation)
  * [Communication](#communication)
  * [Customization](#customization)
  * [Development utilities](#development-utilities)
  * [Device Owner (DPM)](#device-owner-dpm)
  * [Display management](#display-management)
  * [Entertainment](#entertainment)
  * [File management](#file-management)
  * [Games](#games)
  * [Input methods](#input-methods)
  * [Installer & app stores](#installer--app-stores)
  * [Miscellaneous](#miscellaneous)
  * [Network](#network)
  * [Patching](#patching)
  * [Power management](#power-management)
  * [Privacy](#privacy)
  * [Productivity](#productivity)
  * [Quick settings](#quick-settings)
  * [Software management](#software-management)
  * [Task manager](#task-manager)
  * [Terminals](#terminals)
  * [Vendor-specific](#vendor-specific)
    * [Google Pixel](#google-pixel)
    * [Samsung OneUI](#samsung-oneui)
    * [MIUI](#miui)
    * [Other](#other)
  * [Closed-source apps](#closed-source-apps)
  * [Unlisted apps](#unlisted-apps)
* [Development libraries](#development-libraries)
  * [Core](#core)
  * [Filesystem](#filesystem)
  * [System](#system)
  * [Power](#power)
* [Miscellaneous content](#miscellaneous-content)
* [Rish shell](#rish-shell)
* [Annotations](#annotations)
* [License](#license)

***

## Apps

### AI agents

* [Operit AI](https://github.com/AAswordman/Operit) ⭐ 6,945 | 🐛 68 | 🌐 Kotlin | 📅 2026-08-16 - The most powerful AI agent and AI chat software on Android. Can run commands using Shizuku `LGPL-3.0`
* [Ruto-GLM](https://github.com/iamr0s/Ruto-GLM/blob/main/README_en.md) ⭐ 703 | 🐛 11 | 🌐 Kotlin | 📅 2026-01-11 - Automation and Multitasking Framework using AutoGLM. Can create virtual screens that agents can run apps on and use multi-window `Apache 2.0`
* [Open-AutoGLM-Android](https://github.com/xinzezhu/Open-AutoGLM-Android/blob/main/README_EN.md) ⭐ 359 | 🐛 15 | 🌐 Kotlin | 📅 2026-07-21 - Automates actions on your device using the AutoGLM vision language model `GPL-3.0`
* [Mythara](https://github.com/ankurCES/project_mythara) ⭐ 57 | 🐛 1 | 🌐 Kotlin | 📅 2026-05-28 - Open-source local-first agentic AI OS layer for Android. Runs 65+ on-device tools (calls, SMS, calendar, Termux, face recognition); uses Shizuku for cosmetic system tweaks (font scale, dark mode, accent) without root `MIT`
* [rish-mcp](https://github.com/turin-dev/rish-mcp) ⭐ 9 | 🐛 0 | 🌐 Go | 📅 2026-08-16 - Exposes an Android device's Shizuku shell to AIs as an MCP `run_shell` tool over an outbound WebSocket relay — run shell commands from Claude or any MCP client with no VPN, ADB, or sshd `MIT`

### Android TV

* [flicky](https://apt.izzysoft.de/fdroid/index/apk/app.flicky) - An F-Droid client designed for Android TVs `GPL-3.0` [(Source code)](https://github.com/mlm-games/flicky) ⭐ 404 | 🐛 17 | 🌐 Kotlin | 📅 2026-08-10
* [fluffy](https://apt.izzysoft.de/fdroid/index/apk/app.fluffy) - An file manager and archive viewer designed for Android TVs `GPL-3.0` [(Source code)](https://github.com/mlm-games/fluffy) ⭐ 180 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-16
* [RecentAppsTV](https://github.com/Qutaiba-Khader/RecentAppsTV) ⭐ 25 | 🐛 2 | 🌐 Kotlin | 📅 2026-05-31 - Recent Apps overlay for Android TV `Propietary`

### Audio

* [RootlessJamesDSP](https://play.google.com/store/apps/details?id=me.timschneeberger.rootlessjamesdsp) - An implementation of the system-wide JamesDSP audio processing engine for non-rooted Android devices `GPL-3.0` [(Source code)](https://github.com/timschneeb/RootlessJamesDSP) ⭐ 1,632 | 🐛 135 | 🌐 C | 📅 2026-07-24
* [VolumeManager](https://github.com/yume-chan/VolumeManager) ⭐ 524 | 🐛 16 | 🌐 Kotlin | 📅 2026-05-19 - Control each app's volume independently `GPL-2.0`
* [MicUp](https://github.com/papergray/MicUp) ⭐ 126 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-11 ✨ - Real-time microphone audio processing for Android `MIT`
* [wecho](https://github.com/qumolangmo/wecho) ⭐ 78 | 🐛 0 | 🌐 C++ | 📅 2026-07-19 - An Android application for global audio effects processing `MIT`

### Automation

* [AutoJs6](https://github.com/SuperMonster003/AutoJs6) ⭐ 6,234 | 🐛 336 | 🌐 Java | 📅 2026-03-16 - JavaScript-based automation tool `MPL-2.0`
* [Geto](https://github.com/JackEblan/Geto) ⭐ 1,112 | 🐛 20 | 🌐 Kotlin | 📅 2026-07-29 - Automatically change device settings when a specific app is launched. `GPL-3.0`
* [PhoneProfilesPlus](https://github.com/henrichg/PhoneProfilesPlus) ⭐ 650 | 🐛 17 | 🌐 Java | 📅 2025-09-29 - Allows automatic or one-click configuration of your device for specific life situations `Apache-2.0`
* [Tasker Settings](https://github.com/joaomgcd/TaskerSettings) ⭐ 594 | 🐛 14 | 🌐 Kotlin | 📅 2025-11-25 - Helper app for Tasker `Propietary`

### Communication

* [TxtNet-Browser](https://github.com/lukeaschenbrenner/TxtNet-Browser) ⭐ 1,516 | 🐛 12 | 🌐 Java | 📅 2026-04-08 - An app that lets you browse the web over SMS `GPL-3.0`
* [ShizuCallRecorder](https://github.com/kitsumed/ShizuCallRecorder) ⭐ 1,244 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-14 ✨ - ShizuCallRecorder empowers ADB through Shizuku to record phone calls on non-rooted device! `GPL-3.0`
* [CatShare](https://f-droid.org/packages/moe.reimu.catshare/) - Send and receive files over Bluetooth `MIT` [(Source code)](https://github.com/kmod-midori/CatShare) ⭐ 736 | 🐛 14 | 🌐 Kotlin | 📅 2026-02-25
* [revenge-manager](https://github.com/revenge-mod/revenge-manager) ⭐ 689 | 🐛 18 | 🌐 Kotlin | 📅 2026-01-12 - Discord modding tool. Another continuation of the abandoned Bunny-Manager project `OSL-3.0`
* [Aliucord-Manager](https://github.com/Aliucord/Manager) ⭐ 661 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-15 - Discord modding tool `OSL-3.0`
* [Kettu](https://github.com/C0C0B01/Kettu) ⭐ 586 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-27 - Discord modding tool. Continuation of the abandoned Bunny-Manager project `BSD-3-Clause`
* [Lemmy Redirect](https://apt.izzysoft.de/fdroid/index/apk/dev.zwander.lemmyredirect) - A simple app for automatically launching Lemmy links in your preferred Lemmy client. `MIT` [(Source code)](https://github.com/zacharee/MastodonRedirect) ⭐ 198 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-10
* [Mastodon Redirect](https://apt.izzysoft.de/fdroid/index/apk/dev.zwander.mastodonredirect) - A simple app for automatically launching fediverse links in your preferred Mastodon client. `MIT` [(Source code)](https://github.com/zacharee/MastodonRedirect) ⭐ 198 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-10
* [Bluesky Redirect](https://apt.izzysoft.de/fdroid/index/apk/io.github.turtlepaw.blueskyredirect) - A simple app for automatically launching Bluesky links in your preferred Bluesky client `MIT` [(Source code)](https://github.com/Turtlepaw/BlueskyRedirect) ⭐ 12 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-31

### Customization

* [TapTap](https://github.com/KieronQuinn/TapTap) ⭐ 4,019 | 🐛 16 | 🌐 Kotlin | 📅 2024-10-26 ✨ - Port of the double tap on the back of the device feature from Android 12 to any Android 7.0+ device `GPL-3.0`
* [essentials](https://github.com/sameerasw/essentials) ⭐ 2,624 | 🐛 101 | 🌐 Kotlin | 📅 2026-08-15 ✨ - Essential tools, mods and workarounds for Pixels. Also compatible with other devices `MIT`
* [AmbientMusicMod](https://github.com/KieronQuinn/AmbientMusicMod) ⭐ 2,484 | 🐛 10 | 🌐 Kotlin | 📅 2024-09-07 - Port of Now Playing from Pixels to other Android devices `GPL-3.0`
* [ShizuTools](https://github.com/legendsayantan/ShizuTools) ⭐ 2,443 | 🐛 26 | 🌐 Kotlin | 📅 2026-07-28 - Contains some easy-to-use tools to go beyond the level of control allowed by Android System `GPL-3.0`
* [ColorBlendr](https://github.com/Mahmud0808/ColorBlendr) ⭐ 2,374 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-15 - An application to modify Material You colors of your device `GPL-3.0`
* [LinkSheet](https://github.com/LinkSheet/LinkSheet) ⭐ 2,057 | 🐛 82 | 🌐 Kotlin | 📅 2026-08-07 - Restore the Android <12 Url-App-Link-Chooser with Material3 `Modified MPL-2.0`
* [System UI Tuner](https://github.com/zacharee/Tweaker) ⭐ 1,718 | 🐛 67 | 🌐 Kotlin | 📅 2026-08-11 - View and modify hidden settings on Android devices `MIT`
* [DarQ](https://github.com/KieronQuinn/DarQ) ⚠️ Archived ✨ - DarQ provides a per-app selectable force dark option for Android 10 and above `Apache-2.0`
* [Smart Dock](https://f-droid.org/packages/com.axel358.smartdock/) - Transform your phone into a desktop environment with taskbar, recent apps, and start menu `GPL-3.0` [(Source code)](https://github.com/axel358/smartdock) ⭐ 1,394 | 🐛 42 | 🌐 Kotlin | 📅 2026-05-21
* [Taskbar](https://f-droid.org/packages/com.farmerbb.taskbar/) - Use a start menu to access apps. Shizuku can unlock additional features `Apache-2.0` [(Source code)](https://github.com/farmerbb/Taskbar) ⭐ 1,235 | 🐛 207 | 🌐 Java | 📅 2024-11-21
* [Tarnhelm](https://f-droid.org/packages/cn.ac.lz233.tarnhelm/) - Clean up tracking from sharing links. Supports custom URL rewrite rules `GPL-3.0` [(Source code)](https://github.com/lz233/Tarnhelm) ⭐ 778 | 🐛 9 | 🌐 Kotlin | 📅 2026-08-13
* [Language-Selector](https://github.com/VegaBobo/Language-Selector) ⭐ 754 | 🐛 8 | 🌐 Kotlin | 📅 2024-12-29 - Allows users to select individual app languages (Android 13+) `Apache-2.0`
* [CarrierVanityName](https://github.com/nullbytepl/CarrierVanityName) ⭐ 680 | 🐛 28 | 🌐 Kotlin | 📅 2024-02-10 - Carrier Vanity Name is a very simple app to change the carrier names on unrooted Android devices `GPL-3.0`
* [Extendroid](https://github.com/legendsayantan/Extendroid) ⭐ 666 | 🐛 7 | 🌐 Kotlin | 📅 2026-07-28 ✨ - Adds desktop-like multi-window support on Android for smartphones. `GPL-3.0`
* [Lockscreen Widgets](https://play.google.com/store/apps/details?id=tk.zwander.lockscreenwidgets) `IAP` 💰 - Display widgets on the lockscreen. Shizuku is only required on Android 13 and later `MIT` [(Source code)](https://github.com/zacharee/LockscreenWidgets/) ⭐ 502 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-15
* [YoukiDEX](https://github.com/mrYouki/YoukiDex-Android-Desktop) ⭐ 452 | 🐛 3 | 🌐 Kotlin | 📅 2026-04-05 - A full desktop experience layer for Android `GPL-3.0`
* [DroidOS](https://github.com/Katsuyamaki/DroidOS) ⭐ 387 | 🐛 10 | 🌐 Kotlin | 📅 2026-05-04 ✨ - Tiling window manager, Samsung DEX replacement, popup app launcher `Proprietary`
* [gama](https://github.com/palincat/gama) ⭐ 369 | 🐛 4 | 🌐 Kotlin | 📅 2026-07-26 - Can switch between OpenGL and Vulkan renderers by setting the `debug.hwui.renderer` system property `MIT`
* [Smart Edge](https://f-droid.org/en/packages/com.imi.smartedge.sidebar.panel/) - A highly customizable Android side panel inspired by OriginOS `MIT` [(Source code)](https://github.com/Imtiaz-Official/Smart-Edge) ⭐ 313 | 🐛 38 | 🌐 Kotlin | 📅 2026-06-13
* [Dragon-Launcher](https://f-droid.org/packages/org.elnix.dragonlauncher/) ✨ - Highly customizable, gestures based Android launcher focused on speed and efficiency `GPL-3.0` [(Source code)](https://github.com/Elnix90/Dragon-Launcher) ⭐ 277 | 🐛 24 | 🌐 Kotlin | 📅 2026-08-14
* [SmartspacerPlugins](https://github.com/KieronQuinn/SmartspacerPlugins) ⭐ 200 | 🐛 43 | 🌐 Kotlin | 📅 2026-06-13 - Plugins for Smartspacer `GPL-3.0`
* [Adaptive-Theme](https://play.google.com/store/apps/details?id=dev.lexip.hecate) - Smart dark mode based on ambient light `GPL-3.0` [(Source code)](https://github.com/xLexip/Adaptive-Theme) ⭐ 189 | 🐛 10 | 🌐 Kotlin | 📅 2026-08-15
* [WidgetsPro](https://github.com/preethamkmr3/WidgetsPro) ⭐ 166 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-20 - CPU and battery widgets `Proprietary`
* [CustomAnimator](https://play.google.com/store/apps/details?id=com.arslan.customanimator) - Customize animation speeds on a more fine-grained level `GPL-3.0` [(Source code)](https://github.com/AhmetCanArslan/CustomAnimator) ⭐ 112 | 🐛 1 | 🌐 Kotlin | 📅 2026-07-28
* [AutoDND](https://f-droid.org/packages/moe.dic1911.autodnd/) - A simple tool to toggle DND automatically when using specified apps `AGPL-3.0` [(Source code)](https://github.com/dic1911/android_AutoDND) ⭐ 104 | 🐛 1 | 🌐 Kotlin | 📅 2025-12-22
* [Jarngreipr](https://github.com/BrianJr03/Jarngreipr) ⭐ 97 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-14 - Launcher for dual-screen gaming devices. Uses Shizuku to map on of the touch screens to controller inputs `MIT`
* [AutoDark](https://f-droid.org/packages/me.ranko.autodark/) - A small Android app to let you schedule dark mode On/Off `MIT` [(Source code)](https://github.com/0ranko0P/AutoDark) ⚠️ Archived
* [Smart Island](https://github.com/agupta07505/SmartIsland) ⭐ 79 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-15 - A lightweight Android overlay that turns notifications, calls, and media playback into a floating glanceable island `GPL-3.0`
* [MultiLocale](https://github.com/Nightdavisao/MultiLocale) ⭐ 70 | 🐛 2 | 🌐 Kotlin | 📅 2025-11-11 - A simple app that enables you to add additional (or "unsupported") languages to your device's locale settings, if the OEM (Xiaomi) doesn't let you `MIT`
* [ShizukuShortcuts](https://github.com/yshalsager/ShizukuShortcuts) ⭐ 60 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-12 - Create launcher shortcuts for shell commands `GPL-3.0`
* [OmniPrompt](https://github.com/mrndstvndv/OmniPrompt) ⭐ 50 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-14 - A keyboard-first Android command palette that unifies app/device search, and system utilities into an overlay `GPL-3.0`
* [AutoRotate](https://github.com/eiyooooo/AutoRotate) ⭐ 43 | 🐛 2 | 🌐 Kotlin | 📅 2025-06-10 - Manage automatic rotation of different screens on Android phones `GPL-3.0`
* [Dawn-Desktop-Addons](https://github.com/Dawncraft/Dawn-Desktop-Addons) ⭐ 43 | 🐛 3 | 🌐 Java | 📅 2023-10-11 - Some Android app widgets and live wallpapers `GPL-3.0`

### Development utilities

* [LibChecker](https://github.com/LibChecker/LibChecker) ⭐ 7,099 | 🐛 20 | 🌐 Kotlin | 📅 2026-08-13 - An app to view libraries used in apps on your device. Uses Shizuku to determine the installation source of other apps. `Apache-2.0`
* [DSU-Sideloader](https://github.com/VegaBobo/DSU-Sideloader) ⭐ 2,250 | 🐛 128 | 🌐 Kotlin | 📅 2024-03-13 - A simple app made to help users easily install GSIs via DSU's Android feature. `Apache-2.0`
* [KeyAttestation](https://github.com/vvb2060/KeyAttestation) ⭐ 2,069 | 🐛 18 | 🌐 Java | 📅 2025-09-30 - Supports generating, saving, loading, parsing and verifying Android key and ID attestation data. `Proprietary`
* [ActivityManager](https://github.com/sdex/ActivityManager) ⭐ 1,276 | 🐛 13 | 🌐 Kotlin | 📅 2026-07-25 - Launch hidden and unexported activities directly without root `Apache-2.0`
* [LogFox](https://github.com/F0x1d/LogFox) ⭐ 1,265 | 🐛 19 | 🌐 Kotlin | 📅 2026-06-25 ✨ - Yet another logcat reader for Android `GPL-3.0`
* [Cosmic-IDE](https://github.com/Cosmic-Ide/Cosmic-IDE) ⭐ 704 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-14 - IDE for JVM development. Uses Shizuku for an embedded shell `GPL-3.0`
* [wireless-adb-switch](https://github.com/Smooth-E/wireless-adb-switch) ⭐ 676 | 🐛 10 | 🌐 Kotlin | 📅 2026-05-26 - Widgets & quick settings tile to toggle wireless debugging (with KDE Connect integration) `GPL-3.0`
* [AndroidLowLevelDetector](https://play.google.com/store/apps/details?id=net.imknown.android.forefrontinfo) - Detect Treble, GSI, Mainline, APEX, system-as-root(SAR), A/B, etc. `Apache-2.0` [(Source code)](https://github.com/imknown/AndroidLowLevelDetector) ⭐ 463 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-16
* [AndroidAccounts](https://github.com/iamr0s/AndroidAccounts) ⭐ 319 | 🐛 5 | 🌐 Kotlin | 📅 2023-07-19 - Dump package names of apps that have registered an account for a user. `Proprietary`
* [RootActivityLauncher](https://play.google.com/store/apps/details?id=tk.zwander.rootactivitylauncher) `Paid` 💰 - Launch/interact with (un)exported activities, services, and receivers. Supports Shizuku alongside root. `GPL-3.0` [(Source code)](https://github.com/zacharee/RootActivityLauncher) ⭐ 287 | 🐛 6 | 🌐 Kotlin | 📅 2025-09-29
* [CurrentActivity](https://github.com/Omico/CurrentActivity) ⭐ 279 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-04 - A current activity monitor `GPL-3.0`
* [FrameX-Android](https://github.com/MaheshSharan/FrameX-Android) ⭐ 122 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-02 - Real-time performance overlay for Android `MIT`
* [dualapp-mediastore-compatibility](https://github.com/kaedea/dualapp-mediastore-compatibility) ⭐ 57 | 🐛 0 | 🌐 Java | 📅 2025-07-15 - Fixes MediaStore & File IO compatibility issues between HostProfile App and WorkProfile/DualApp/MultiApp. `Proprietary`
* [FPSViewer](https://github.com/binhmod/FPSViewer) ⭐ 53 | 🐛 3 | 🌐 Java | 📅 2026-05-21 - FPS viewer overlay with graph `Proprietary`
* [ManageSensors](https://github.com/Carry-rrk/ManageSensors) ⭐ 42 | 🐛 2 | 🌐 Kotlin | 📅 2025-01-18 - Utilizes Shizuku to call AppOps APIs for fine-grained app permission control `MIT`
* [get\_event](https://github.com/lalakii/get_event) ⭐ 39 | 🐛 0 | 🌐 Java | 📅 2026-08-10 - Read /dev/input/event\* `Proprietary`
* [debuggable-app-data-backup](https://github.com/timschneeb/debuggable-app-data-backup) ⭐ 34 | 🐛 1 | 🌐 Kotlin | 📅 2026-02-04 - Backup/restore private app data of debuggable apps using Shizuku `GPL-3.0`

### Device owner (DPM)

* [Dhizuku](https://github.com/iamr0s/Dhizuku) ⭐ 3,684 | 🐛 17 | 🌐 Kotlin | 📅 2026-08-13 - Shizuku-inspired app that allows sharing DeviceOwner permissions to third-party apps `GPL-3.0`
* [OwnDroid](https://github.com/BinTianqi/OwnDroid) ⭐ 1,328 | 🐛 8 | 🌐 Kotlin | 📅 2026-08-16 - Manage your device with Device owner privileges `GPL-3.0`
  * [MDPC](https://github.com/MrRare2/MDPC) ⭐ 109 | 🐛 0 | 🌐 Kotlin | 📅 2026-03-13 - Fork of OwnDroid with added features `GPL-3.0`

### Display management

* [SecondScreen](https://play.google.com/store/apps/details?id=com.farmerbb.secondscreen.free) - Better screen mirroring for Android devices `Apache-2.0` [(Source code)](https://github.com/farmerbb/SecondScreen) ⭐ 509 | 🐛 54 | 🌐 Java | 📅 2024-09-14
* [Grayscaler](https://github.com/C10udburst/Grayscaler) ⭐ 159 | 🐛 6 | 🌐 Kotlin | 📅 2025-02-18 - Keep your phone mostly monochrome, but allow apps like camera to be in color `GPL-3.0`
* [android-display-extend](https://github.com/jqssun/android-display-extend) ⭐ 137 | 🐛 6 | 🌐 Java | 📅 2026-07-22 ✨ - Display manager for physical and virtual displays with a built-in virtual touchscreen. Great for use with `scrcpy --new-display` on a PC `GPL-3.0`
* [android-display-mirror](https://github.com/jqssun/android-display-mirror) ⭐ 135 | 🐛 11 | 🌐 C++ | 📅 2026-08-08 ✨ - Screen mirroring hub with support for sharing screen content over AirPlay, Moonlight/Sunshine, and DisplayLink `GPL-3.0`
* [Fold\_Switcher](https://github.com/eiyooooo/Fold_Switcher) ⭐ 88 | 🐛 5 | 🌐 Kotlin | 📅 2025-06-10 - Switch between various display folding states on foldable devices `Apache-2.0`
* [Adaptive-Hz](https://github.com/mahmutaunal/Adaptive-Hz) ⭐ 64 | 🐛 6 | 🌐 Kotlin | 📅 2026-07-24 - Automatically switches display refresh rate between 60Hz and 120Hz based on user interaction. Designed for Samsung devices without true adaptive refresh `MIT`
* [deskcontrol](https://github.com/exiarepairii/deskcontrol) ⭐ 59 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-08 - Turns your phone into a touchpad and keyboard for a single app running on a wired external display `GPL-3.0`
* [ConnectScreen](https://connect-screen.com/) - Launch single apps to display in fullscreen on external displays. Can use the primary screen of the mobile as a virtual touchpad to control external display. Can rotate the screen for applications like TikTok `GPL-3.0` [(Source code)](https://gitee.com/connect-screen/connect-screen)

### Entertainment

* [Mihon](https://github.com/mihonapp/mihon) ⭐ 22,884 | 🐛 713 | 🌐 Kotlin | 📅 2026-08-15 - Manga reader using Shizuku plugin management. Independent successor of Tachiyomi. `Apache-2.0`
  * Mihon/Tachiyomi has several other active forks, including [TachiyomiSY](https://github.com/jobobby04/TachiyomiSY) ⭐ 4,100 | 🐛 310 | 🌐 Kotlin | 📅 2026-08-12 and [TachiyomiAZ](https://github.com/az4521/TachiyomiAZ) ⭐ 722 | 🐛 22 | 🌐 Kotlin | 📅 2026-08-16
* [Aniyomi](https://github.com/aniyomiorg/aniyomi) ⭐ 7,599 | 🐛 373 | 🌐 Kotlin | 📅 2026-08-13 - Tachiyomi fork with anime support and plugin management using Shizuku. `Apache-2.0`
* [BiliDownOut](https://f-droid.org/packages/cn.a10miaomiao.bilidown/) - Export videos downloaded from the Android version of Bilibili `GPL-3.0` [(Source code)](https://github.com/10miaomiao/bili-down-out) ⭐ 372 | 🐛 15 | 🌐 Kotlin | 📅 2026-07-19
* [hlbmerge\_flutter](https://github.com/molihuan/hlbmerge_flutter) ⭐ 330 | 🐛 5 | 🌐 Dart | 📅 2026-07-27 - Merge and export BiliBili cache files into MP4, supports mobile and computer client `Apache-2.0`

### File management

* [SDMaid-SE](https://play.google.com/store/apps/details?id=eu.darken.sdmse) `IAP` 💰 - SD Maid 2/SE is Android's most thorough cleaning tool `GPL-3.0` [(Source code)](https://github.com/d4rken-org/sdmaid-se) ⭐ 7,290 | 🐛 27 | 🌐 Kotlin | 📅 2026-08-16
* [NFile](https://github.com/Senzme/NFile) ⭐ 364 | 🐛 59 | 🌐 Dart | 📅 2026-08-11 - File manager with Android folder access using Shizuku `GPL-3.0`
* [fluffy](https://apt.izzysoft.de/fdroid/index/apk/app.fluffy) - An file manager and archive viewer with Android TV support. Supports full file access using Shizuku, if enabled in settings `GPL-3.0` [(Source code)](https://github.com/mlm-games/fluffy) ⭐ 180 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-16
* [ZenFile](https://github.com/l930203811/ZenFile) ⭐ 103 | 🐛 2 | 🌐 Dart | 📅 2026-08-14 - NFile fork with built-in remote file server support `GPL-3.0`

> \[!NOTE]
> [See here more file managers (closed-source)](pages/CLOSED_SOURCE.md#file-management)

### Games

* [translatefgo](https://github.com/rayshift/translatefgo) ⭐ 337 | 🐛 13 | 🌐 C# | 📅 2026-04-25 - Fate/Grand Order game translation project `MIT`
* [Ascent](https://github.com/4o3F/Ascent) ⭐ 216 | 🐛 0 | 🌐 Dart | 📅 2026-04-22 - A tool for retrieving gacha history links from Mihoyo games  `AGPL-3.0`
* [blocktopograph](https://github.com/Blocktopograph/Blocktopograph) ⭐ 179 | 🐛 5 | 📅 2026-01-11 - Blocktopograph is an app server for MCBE, it includes a world, NBT editor for local worlds `Apache-2.0`
* [LOModInstaller](https://github.com/anyabot/LOModInstaller) ⭐ 81 | 🐛 1 | 🌐 Kotlin | 📅 2026-06-23 - Mod manager for the game 'Last Origin' `Proprietary`
* [BDroid\_X](https://github.com/Ark-Repoleved/BDroid_X) ⭐ 79 | 🐛 9 | 🌐 JavaScript | 📅 2026-04-27 - Browndust II Mod manager `Proprietary`
* [pogoplusle](https://github.com/Mygod/pogoplusle) ⭐ 65 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-12 - Skip the pairing dialog when connecting a Pokémon GO Plus `Apache-2.0`
* [stalker](https://github.com/onerdna/stalker) ⭐ 51 | 🐛 52 | 🌐 Dart | 📅 2026-08-09 - Save data viewer & editor for Shadow Fight 2 `GPL-3.0`
* [HandheldExp](https://github.com/Teppichseite/HandheldExp) ⭐ 48 | 🐛 2 | 🌐 Kotlin | 📅 2024-09-22 - In-game menu for EmulationStation (ES-DE) on Android  `MIT`
* [CloudSync-Mobile](https://github.com/FawazTakahji/CloudSync-Mobile) ⭐ 29 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-25 - An app that allows you to sync your Stardew Valley saves across multiple devices `GPL-3.0`
* [lac-tool](https://github.com/aliernfrog/lac-tool) ⭐ 21 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-14 - Manage maps, wallpapers, and screenshots for the game 'Los Angeles Crimes' `GPL-3.0`
* [pf-tool](https://github.com/aliernfrog/pf-tool) ⭐ 19 | 🐛 4 | 🌐 Kotlin | 📅 2026-07-12 - Easily import and share Polyfield maps `GPL-3.0`
* [Okkei Patcher](https://github.com/solrudev/OkkeiPatcher) ⭐ 10 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-31 - Companion app for localizing the Android version of CHAOS;CHILD visual novel `GPL-3.0`
* [ShinGen](https://github.com/Shio2077/ShinGen#genshin-impact-auto-conversation-clicker-on-android) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2025-11-27 - Genshin Impact Auto-Conversation Clicker `MIT`

### Input methods

* [KeyMapper](https://play.google.com/store/apps/details?id=io.github.sds100.keymapper) ✨ - An Android app that changes what the buttons do on your devices! `GPL-3.0` [(Source code)](https://github.com/keymapperorg/KeyMapper) ⭐ 2,578 | 🐛 203 | 🌐 Kotlin | 📅 2026-08-11
* [XtMapper](https://github.com/Xtr126/XtMapper) ⭐ 429 | 🐛 35 | 🌐 Java | 📅 2026-07-18 - Keymapper for Android x86 `GPL-3.0`
* [pastiera](https://github.com/palsoftware/pastiera) ⭐ 180 | 🐛 48 | 🌐 Kotlin | 📅 2026-08-13 - Android keyboard specialized for Physical Keyboard Devices. Uses Shizuku for trackpad gestures `GPL-3.0`
* [keysync](https://github.com/aka-munan/keysync) ⭐ 140 | 🐛 11 | 🌐 Kotlin | 📅 2026-02-26 - Play games using mouse and keyboard on Android device; keymapper for games `Apache-2.0`
* [C9](https://github.com/austinauyeung/C9) ⭐ 90 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-12 - Efficient grid-based cursor provided alongside a traditional cursor. Shizuku is only required on Android 11. `Apache-2.0`
* [Android-Show-Taps](https://github.com/k3x1n/Android-Show-Taps) ⭐ 47 | 🐛 8 | 🌐 Kotlin | 📅 2024-06-23 - Show customized taps upon touches `GPL-3.0`
* [TitanPad](https://github.com/sztupy/TitanPad) ⭐ 27 | 🐛 8 | 🌐 Kotlin | 📅 2026-05-06 - Converts the Titan2's Physical Keyboard's capacitive input into mouse and scroll gestures. Uses Shizuku for reading the trackpad input and setting up virtual HID devices `Apache-2.0`
* [andRemote2](https://github.com/c0dev0id/andRemote2) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-04-21 - Emulates the DMD Remote 2 for map apps `Proprietary`

### Installer & app stores

* [Obtainium](https://github.com/ImranR98/Obtainium) ⭐ 18,986 | 🐛 395 | 🌐 Dart | 📅 2026-08-10 - Get Android App Updates Directly From the Source `GPL-3.0`
* [GitHub-Store](https://f-droid.org/packages/zed.rainxch.githubstore/) - App store for GitHub releases with discovery function `Apache-2.0` [(Source code)](https://github.com/OpenHub-Store/GitHub-Store) ⭐ 17,636 | 🐛 102 | 🌐 Kotlin | 📅 2026-07-29
* [Droid-ify](https://f-droid.org/packages/com.looker.droidify/) - Material F-Droid client `GPL-3.0` [(Source code)](https://github.com/Droid-ify/client) ⭐ 7,263 | 🐛 196 | 🌐 Kotlin | 📅 2026-08-16
* [InstallerX-Revived](https://github.com/wxxsfxyzm/InstallerX-Revived) ⭐ 6,170 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-15 ✨ - Modern and functional Android app installer replacement `GPL-3.0`
* [Neo-Store](https://f-droid.org/packages/com.machiav3lli.fdroid/) - An F-Droid client with modern UI and an arsenal of extra features `GPL-3.0` [(Source code)](https://github.com/NeoApplications/Neo-Store) ⭐ 4,906 | 🐛 129 | 🌐 Kotlin | 📅 2026-04-25
* [SAI](https://f-droid.org/packages/com.aefyr.sai.fdroid/) - Android split APKs installer `GPL-3.0` [(Source code)](https://github.com/Aefyr/SAI) ⭐ 3,780 | 🐛 0 | 🌐 Java | 📅 2024-06-03
* [InstallWithOptions](https://github.com/zacharee/InstallWithOptions) ⭐ 3,158 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-11 - Simple-ish app using Shizuku to install APKs on-device with advanced options `MIT`
* [Orion Store](https://github.com/RookieEnough/Orion-Store) ⭐ 3,094 | 🐛 68 | 🌐 TypeScript | 📅 2026-07-25 - App store for modded apps `GPL-3.0`
* [universal-installer](https://github.com/pass-with-high-score/universal-installer) ⭐ 1,256 | 🐛 17 | 🌐 Kotlin | 📅 2026-08-09 - Install and manage APK packages with split APK support, silent install via Shizuku, and VirusTotal malware scanning `GPL-3.0`
* [instafel](https://github.com/mamiiblt/instafel) ⭐ 1,234 | 🐛 12 | 🌐 Java | 📅 2026-08-16 - Updater app for Instafel, an Instagram mod `MIT`
* [ffupdater](https://f-droid.org/packages/de.marmaro.krt.ffupdater/) - FFUpdater: Updater for privacy-friendly browser `GPL-3.0` [(Source code)](https://github.com/Tobi823/ffupdater) ⭐ 1,078 | 🐛 88 | 🌐 Kotlin | 📅 2026-06-27
* [PI](https://github.com/SanmerApps/PI) ⭐ 692 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-14 - Package installer that allows overwriting the package requester and executor `MIT`
* [Shizuku Package Installer](https://github.com/vvb2060/PackageInstaller) ⭐ 687 | 🐛 8 | 🌐 Kotlin | 📅 2025-08-12 - A lightweight app installer replacement with split APK support `Apache-2.0`
* [florid](https://github.com/Nandanrmenon/florid) ⭐ 497 | 🐛 44 | 🌐 Dart | 📅 2026-06-16 - Material3 F‑Droid Client `GPL-3.0`
* [BHub](https://github.com/B1ays/BHub) ⭐ 353 | 🐛 4 | 🌐 Kotlin | 📅 2025-10-01 - Download, install and share mods easily `Proprietary`
* [AuroraStore](https://f-droid.org/packages/com.aurora.store/) - An open-source alternative to Google Play Store with privacy and modern design `GPL-3.0` [(Source code)](https://gitlab.com/AuroraOSS/AuroraStore)
* [IzzyOnDroid](https://gitlab.com/sunilpaulmathew/izzyondroid) - An unofficial client for IzzyOnDroid F-Droid Repository `GPL-3.0`

### Miscellaneous

* [SimpleWear](https://play.google.com/store/apps/details?id=com.thewizrd.simplewear) - A simple app for controlling your Android devices from your WearOS watch `Apache-2.0` [(Source code)](https://github.com/SimpleAppProjects/SimpleWear) ⭐ 181 | 🐛 4 | 🌐 Kotlin | 📅 2025-11-11
* [krude](https://github.com/KusStar/krude) ⭐ 157 | 🐛 1 | 🌐 Kotlin | 📅 2025-08-13 - All-in-one app and workflow launcher. Uses Shizuku for process killing and file management `MIT`
* [AppBooster](https://github.com/androidexpert35/AppBooster) ⭐ 82 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-20 - GUI for Android's builtin `dex2oat` utility, allowing DEX code of installed apps to be re-optimized `Apache-2.0`
* [NotiFixer](https://github.com/dkajan19/NotiFixer) ⭐ 76 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-06 - Android utility to make notifications persistent/undismissable using Shizuku `MIT`
* [PoC-Deployer-System](https://github.com/wqry085/PoC-Deployer-System) ⭐ 75 | 🐛 0 | 🌐 Java | 📅 2026-02-16 - Exploits CVE-2024-31317 for Zygote injection, integrating remote terminal and file transfer capabilities `MIT`
* [telegram-rc](https://github.com/telegram-sms/telegram-rc) ⭐ 65 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-26 - Remote control your device via Telegram messages `BSD 3-Clause`
* [OnStop2FinishAndRemoveTask](https://github.com/takusan23/OnStop2FinishAndRemoveTask) ⭐ 30 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-12 - Automatically close selected apps when you exit them to save power and memory `Apache-2.0`
* [HiddenAlarmRevealer](https://github.com/AhmetCanArslan/HiddenAlarmRevealer) ⭐ 19 | 🐛 0 | 🌐 Java | 📅 2026-04-04 - Find the reason why the alarm icon is active in the status bar `Proprietary`

### Network

* [sing-box](https://f-droid.org/packages/io.nekohasekai.sfa/) - Universal proxy platform. Uses Shizuku for per-app proxying `GPL-3.0` [(Source code)](https://github.com/SagerNet/sing-box) ⭐ 37,024 | 🐛 303 | 🌐 Go | 📅 2026-08-15
* [WG Tunnel](https://github.com/wgtunnel/android) ⭐ 3,023 | 🐛 108 | 🌐 Kotlin | 📅 2026-08-16 - A FOSS Android client for WireGuard and AmneziaWG with auto-tunneling. `MIT`
* [ShizuWall](https://github.com/AhmetCanArslan/ShizuWall) ⭐ 2,100 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-13 ✨ - Open-source app firewall that doesn't depend on VPNs or root `GPL-3.0`
* [Traffic Light](https://play.google.com/store/apps/details?id=com.leekleak.trafficlight) - A persistent network speed tracker in your status bar `GPL-3.0` [(Source code)](https://github.com/leekleak/traffic-light) ⭐ 780 | 🐛 19 | 🌐 Kotlin | 📅 2026-08-13
* [delta](https://github.com/supershadoe/delta) ⭐ 551 | 🐛 17 | 🌐 Kotlin | 📅 2026-05-02 - Hotspot manager using Shizuku `BSD-3-Clause`
* [ADNS](https://github.com/eyalm2000/adns) ⭐ 520 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-14 - DNS-based ad blocker for Android `MIT`
* [NetworkSwitch](https://github.com/aunchagaonkar/NetworkSwitch) ⭐ 422 | 🐛 22 | 🌐 Kotlin | 📅 2026-07-08 - Android app for 4G/5G network mode switching `GPL-3.0`
* [de1984](https://github.com/dorumrr/de1984) ⭐ 365 | 🐛 28 | 🌐 Kotlin | 📅 2025-12-15 - App firewall without using an VPN; can also manage packages `MIT`
* [wifi-password-manager](https://github.com/Khh-vu/wifi-password-manager) ⭐ 279 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-08 - Simple app using Shizuku to manage & view saved Wi-Fi passwords `MIT`
* [WiFiList](https://play.google.com/store/apps/details?id=tk.zwander.wifilist) `Paid` 💰 - View your saved WiFi passwords on Android 11 and later without root `Proprietary` [(Source code)](https://github.com/zacharee/WiFiList) ⭐ 262 | 🐛 9 | 🌐 Kotlin | 📅 2025-01-18
* [FireWall Blocks](https://github.com/shynoiddev/FireWall-Blocks) ⭐ 210 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-09 - Dual-mode firewall: blocks internet access using Shizuku or a standard local VPN interface or both. `MIT`
* [CellReader](https://play.google.com/store/apps/details?id=dev.zwander.cellreader) `Paid` 💰 - Can read cell tower info on Android `MIT` [(Source code)](https://github.com/zacharee/CellReader) ⭐ 89 | 🐛 0 | 🌐 Kotlin | 📅 2025-09-20
* [Hostman](https://github.com/LinZong/Hostman) ⭐ 54 | 🐛 0 | 🌐 Kotlin | 📅 2025-12-31 `Root` - Preview & edit the /etc/hosts file `MIT`
* [Dolphy-App](https://github.com/unvoiddd/Dolphy-App) ⭐ 52 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-08 - NFC, BLE, and IR multi-tool for wireless protocol research `GPL-3.0`
* [EasySpot](https://github.com/EasySpotApp/EasySpot) ⭐ 46 | 🐛 1 | 🌐 Kotlin | 📅 2025-10-26 - An app that allows you to turn on your hotspot remotely via Bluetooth - think Apple Continuity, but for everyone `GPL-3.0`
* [NaiveproxyForAndroid](https://github.com/Dobiec/NaiveproxyForAndroid) ⭐ 45 | 🐛 2 | 🌐 Java | 📅 2024-10-30 - A simple application to run Naiveproxy on Android `MIT`
* [NetToggle](https://github.com/Dhangofa/NetToggle) ⭐ 20 | 🐛 1 | 🌐 Java | 📅 2026-08-16 - A lightweight Android Quick Settings tile to force 5G Only, 4G Only and preferred network modes using Root or Shizuku `GPL-3.0`
* [FindMyDevice](https://gitlab.com/fmd-foss/fmd-android) - Secure & open-source alternative to Google's FindMyDevice service. `GPL-3.0`

### Patching

* [Morphe](https://morphe.software/) - User-friendly YouTube patcher based on Universal-ReVanced-Manager `GPL-3.0` [(Source code)](https://github.com/MorpheApp/morphe-manager) ⭐ 7,155 | 🐛 36 | 🌐 Kotlin | 📅 2026-08-16
* [LSPatch](https://github.com/JingMatrix/LSPatch) ⭐ 3,638 | 🐛 28 | 🌐 Java | 📅 2026-04-19 - A non-root Xposed framework extending from LSPosed `GPL-3.0`
* [Universal-ReVanced-Manager](https://github.com/Jman-Github/Universal-ReVanced-Manager) ⭐ 1,253 | 🐛 52 | 🌐 Kotlin | 📅 2026-08-14 - ReVanced patcher that has extra features the official manager doesn't have `GPL-3.0`

### Power management

* [EnforceDoze](https://f-droid.org/packages/com.akylas.enforcedoze/) - Enable Doze mode immediately after screen off and turn off motion sensing to get best battery life `GPL-3.0` [(Source code)](https://github.com/farfromrefug/EnforceDoze) ⭐ 351 | 🐛 21 | 🌐 Java | 📅 2026-07-26
* [NoMoreBackground](https://f-droid.org/packages/com.adilhanney.no_more_background/) - A fire-and-forget program to stop Android apps from running in the background `GPL-3.0` [(Source code)](https://github.com/adil192/no_more_background) ⭐ 297 | 🐛 8 | 🌐 Dart | 📅 2026-08-06
* [ScreenOff](https://github.com/WuDi-ZhanShen/ScreenOff) ⭐ 261 | 🐛 14 | 🌐 Java | 📅 2025-01-14 - Turn off your Android's screen without entering standby/sleep mode `Proprietary`
* [RebootNya](https://github.com/daisukiKaffuChino/RebootNya) ⭐ 236 | 🐛 2 | 🌐 Kotlin | 📅 2026-04-29 - Advanced reboot menu with Shizuku support `Apache-2.0`
* [BatStats](https://github.com/mlm-games/BatStats) ⭐ 172 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-10 - Battery monitor with stats via Shizuku `GPL-3.0`
* [Battery-Monitor](https://github.com/tswistak/Battery-Monitor) ⭐ 54 | 🐛 41 | 🌐 Kotlin | 📅 2026-08-15 - Track and log battery capacity and parameters over time using Shizuku `GPL-3.0`
* [sleep-timer](https://github.com/Xitee1/sleep-timer) ⭐ 48 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-10 - Sleep timer that can pause media, and turn off WIFI/Bluetooth/Display `GPL-3.0`
* [zukulock](https://github.com/tiendnm/zukulock) ⭐ 45 | 🐛 0 | 🌐 Kotlin | 📅 2025-08-19 - Very lightweight app that locks the screen when launched. Helps reduce wear on the power button `MIT`
* [battery-stats-changer](https://github.com/superisuer/battery-stats-changer) ⭐ 22 | 🐛 0 | 🌐 Java | 📅 2025-12-28 - Open source app to visually change battery data via Shizuku `GPL-3.0`
* [Amply](https://github.com/d4rken-org/amply) ⭐ 16 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-15 - Easy control of charging limits. Temporarily allows one full charge, then automatically restores your protective charge limit `GPL-3.0`
* [Batt](https://gitlab.com/narektor/batt) - A simple app that shows battery status information on Android 14 and later. `GPL-3.0`

### Privacy

* [Amarok-Hider](https://apt.izzysoft.de/fdroid/index/apk/deltazero.amarok.foss) - Hide your private files and Android apps with just one click `Apache-2.0` [(Source code)](https://github.com/deltazefiro/Amarok-Hider) ⭐ 3,191 | 🐛 61 | 🌐 Java | 📅 2026-08-11
* [AppLock](https://github.com/aload0/AppLock) ⭐ 829 | 🐛 105 | 🌐 Kotlin | 📅 2026-07-21 ✨ - Lock sensitive apps with a PIN and optionally biometrics `MIT`
* [PrivacyFlip](https://f-droid.org/packages/io.github.dorumrr.privacyflip/) - Manage your device privacy based on lock/unlock state `MIT` [(Source code)](https://github.com/dorumrr/privacyflip) ⭐ 267 | 🐛 13 | 🌐 Kotlin | 📅 2026-01-22
* [AntiForensic-Tools](https://github.com/bakad3v/Android-AntiForensic-Tools) ⭐ 185 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-15 - An application designed to silently protect user data from powerful adversaries `GPL-3.0`

### Productivity

* [Curbox](https://f-droid.org/packages/neth.iecal.curbox/) ✨ - Tool to reduce screen addiction and view usage analytics `GPL-3.0` [(Source code)](https://github.com/nethical6/curbox) ⭐ 1,180 | 🐛 27 | 🌐 Kotlin | 📅 2026-08-07
* [DetoxDroid](https://github.com/flxapps/DetoxDroid) ⭐ 501 | 🐛 50 | 🌐 Kotlin | 📅 2026-07-27 - Digital Detoxing: Use your phone rather than letting your phone use you `GPL-3.0`
* [Blink](https://github.com/character-flat/Blink) ⭐ 15 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-17 - A persistent, highly customizable 20-20-20 rule eye-care timer that uses Shizuku to whitelist itself from Android's battery optimizations `GPL-3.0`

### Quick settings

* [PrivateDNSAndroid](https://github.com/karasevm/PrivateDNSAndroid) ⭐ 1,020 | 🐛 11 | 🌐 Kotlin | 📅 2026-07-29 - Quick settings tile to switch active private DNS server `MIT`
* [Quick-Tile Settings](https://f-droid.org/packages/com.rbn.qtsettings/) - QS tiles for toggling USB debugging and switching private DNS hosts `GPL-3.0` [(Source code)](https://github.com/RBN-Apps/Quick-Tile-Settings) ⭐ 335 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-10
* [Better Internet Tiles](https://play.google.com/store/apps/details?id=be.casperverswijvelt.unifiedinternetqs) - Bring back Wi-Fi and mobile data tiles on Android 12 or higher + a better-unified internet tile `GPL-3.0` [(Source code)](https://github.com/CasperVerswijvelt/Better-Internet-Tiles) ⭐ 257 | 🐛 32 | 🌐 Kotlin | 📅 2025-05-12
* [Private DNS Quick Setting](https://apt.izzysoft.de/fdroid/index/apk/com.flashsphere.privatednsqs) - QS tile for toggling the private DNS setting on or off `GPL-3.0` [(Source code)](https://github.com/flashsphere/private-dns-qs) ⭐ 122 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-14
* [SensorsOff](https://github.com/LinerSRT/SensorsOff) ⭐ 101 | 🐛 2 | 🌐 Java | 📅 2023-09-17 - Enable/Disable device sensors via quick settings `Apache-2.0`
* [DNS Toggle](https://f-droid.org/packages/com.ericlowry.dnstoggle/) - Quick Settings tile for Private DNS toggling and configuration, with optional advanced automation. `MIT` [(Source code)](https://github.com/ELowry/DNSToggle) ⭐ 91 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-09
* [AlwaysOnDisplayToggle](https://f-droid.org/packages/org.alberto97.aodtoggle/) - An Android quick setting to toggle Always on Display `MIT` [(Source code)](https://github.com/Alberto97/AlwaysOnDisplayToggle) ⭐ 86 | 🐛 0 | 🌐 Kotlin | 📅 2025-05-16
* [DataSimTile](https://github.com/Mygod/DataSimTile) ⭐ 48 | 🐛 0 | 🌐 Java | 📅 2026-08-08 - Tile to switch the default mobile data SIM `Apache-2.0`
* [DisplayToggle](https://f-droid.org/packages/io.github.ulysseszh.displaytoggle/) - Provides quick settings tile and shortcuts to turn off the display without locking the screen or stopping foreground running apps `MIT` [(Source code)](https://github.com/UlyssesZh/DisplayToggle) ⭐ 21 | 🐛 2 | 🌐 Kotlin | 📅 2025-09-20

### Software management

* [Hail](https://f-droid.org/packages/com.aistra.hail/) ✨ - Freeze, hide, or disable any app. Create and organize app groups that can be frozen with one click. `GPL-3.0` [(Source code)](https://github.com/aistra0528/Hail) ⭐ 6,452 | 🐛 168 | 🌐 Kotlin | 📅 2026-08-12
* [Canta](https://play.google.com/store/apps/details?id=io.github.samolego.canta) - Uninstall any app without root `LGPL-3.0` [(Source code)](https://github.com/samolego/Canta) ⭐ 5,561 | 🐛 29 | 🌐 Kotlin | 📅 2026-08-16
* [Island](https://play.google.com/store/apps/details?id=com.oasisfeng.island) - Isolate and clone apps for privacy protection and parallel running `Apache-2.0` [(Source code)](https://github.com/oasisfeng/island) ⭐ 3,874 | 🐛 664 | 🌐 Java | 📅 2025-04-24
* [Blocker](https://github.com/lihenggui/blocker) ⭐ 2,357 | 🐛 51 | 🌐 Kotlin | 📅 2026-08-03 - Enable/disable Android components such as activities, services, receivers, and providers `Apache-2.0`
* [MMRL](https://github.com/MMRLApp/MMRL) ⭐ 2,127 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-10 `Root` - Manage your Magisk module repository `GPL-3.0`
* [Inure App Manager](https://play.google.com/store/apps/details?id=app.simple.inure.play) `15-day trial` `IAP` 💰 - Android app manager for both rooted and non-rooted devices `GPL-3.0` [(Source code)](https://github.com/Hamza417/Inure) ⭐ 1,875 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-16
* [UpgradeAll](https://f-droid.org/packages/net.xzos.upgradeall/) - Check updates for Android apps, Magisk modules and more! `GPL-3.0` [(Source code)](https://github.com/DUpdateSystem/UpgradeAll) ⭐ 1,328 | 🐛 41 | 🌐 Kotlin | 📅 2026-08-16
* [Package Manager](https://play.google.com/store/apps/details?id=com.smartpack.packagemanager) - A powerful app to manage both system and user apps `GPL-3.0` [(Source code)](https://github.com/SmartPack/PackageManager) ⭐ 809 | 🐛 89 | 🌐 Java | 📅 2026-06-17
* [Thor](https://play.google.com/store/apps/details?id=com.valhalla.thor) - App manager with freeze and install capabilities. `GPL-3.0` [(Source code)](https://github.com/trinadhthatakula/Thor) ⭐ 514 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-16
* [FreezeYou](https://f-droid.org/packages/cf.playhi.freezeyou/) - Improve your device's speed and battery life by freezing crappy software manually or semi-automatically `Apache-2.0` [(Source code)](https://github.com/FreezeYou/FreezeYou) ⭐ 270 | 🐛 34 | 🌐 Kotlin | 📅 2026-08-09
* [krude](https://github.com/KusStar/krude) ⭐ 157 | 🐛 1 | 🌐 Kotlin | 📅 2025-08-13 - All-in-one app and workflow launcher `MIT`
* [AppControlX](https://github.com/risunCode/AppControl-X) ⭐ 154 | 🐛 5 | 🌐 Kotlin | 📅 2026-03-10 - Freeze, force stop, uninstall apps, change background optimization and more `GPL-3.0`
* [Buge App Manager](https://github.com/BugeStudioTeam/Buge-App-Manager) ⭐ 152 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-15 - An app manager focusing on permission management `GPL-3.0`
* [DisabledLauncher](https://github.com/voruti/DisabledLauncher) ⭐ 136 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-12 - Android app that disables unused apps while still allowing convenient access to them `MIT`
* [Insular](https://f-droid.org/packages/com.oasisfeng.island.fdroid/) - Complete FLOSS fork of Island `Apache-2.0` [(Source code)](https://gitlab.com/secure-system/Insular)

### Task manager

* [TaskManager](https://github.com/RohitKushvaha01/TaskManager) ⭐ 605 | 🐛 4 | 🌐 C++ | 📅 2026-08-07 - A Task Manager for Android. Killing processes requires root access. `Apache-2.0`
* [shappky](https://github.com/YasserNull/shappky) ⭐ 533 | 🐛 19 | 🌐 Kotlin | 📅 2026-08-16 ✨ - A simple app to boost performance by stopping background apps. `GPL-3.0`
* [Running Services Monitor](https://play.google.com/store/apps/details?id=me.biplobsd.rsm) - Monitor running services on your Android device `MIT` [(Source code)](https://github.com/biplobsd/running_services_monitor) ⭐ 404 | 🐛 5 | 🌐 Dart | 📅 2026-07-12
* [Pensum](https://github.com/troikoss/Pensum) ⭐ 165 | 🐛 1 | 🌐 Kotlin | 📅 2026-03-30 ✨ - Windows-style Task Manager for Android `GPL-3.0`
* [ReAppzuku](https://github.com/gree1d/ReAppzuku) ⭐ 159 | 🐛 1 | 🌐 Java | 📅 2026-08-04 - Control and manage background applications. Fork of shappky `GPL-3.0`
* [memhogs](https://github.com/cicerothoma/memhogs-android) ⭐ 20 | 🐛 1 | 🌐 Kotlin | 📅 2026-07-04 - Which apps are eating your phone's memory. Per-app breakdown via Shizuku, helpers grouped under the app that owns them `MIT`

### Terminals

* [Haven](https://f-droid.org/packages/sh.haven.app/) - Terminal, SSH, VNC, RDP, SFTP & cloud storage client for Android `AGPL-3.0` [(Source code)](https://github.com/GlassOnTin/Haven) ⭐ 1,053 | 🐛 49 | 🌐 Kotlin | 📅 2026-08-15
* [ReTerminal](https://github.com/RohitKushvaha01/ReTerminal) ⭐ 624 | 🐛 15 | 🌐 C | 📅 2026-08-16 ✨ - Sleek, Material 3-inspired terminal emulator based on Termux's robust TerminalView `MIT`
* [aShell](https://gitlab.com/sunilpaulmathew/ashell) - A local ADB shell for Shizuku-powered Android devices `GPL-3.0`
  * [aShell You](https://github.com/DP-Hridayan/aShellYou) ⭐ 2,188 | 🐛 36 | 🌐 Kotlin | 📅 2026-08-16 - Material You Redesign of aShell app. `GPL-3.0`

> \[!NOTE]
> Using [rish](pages/RISH.md), you can create a local ADB shell with any terminal emulator, such as Termux.

### Vendor-specific

#### Google Pixel

* [Smartspacer](https://github.com/KieronQuinn/Smartspacer) ⭐ 3,473 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-08 - Customizable widget, can upgrade the built-in 'At a glance' widget on Pixel devices using Shizuku `GPL-3.0`
* [pixel-volte-patch](https://github.com/kyujin-cho/pixel-volte-patch/blob/main/README.en.md) ⭐ 2,968 | 🐛 95 | 🌐 Kotlin | 📅 2026-02-07 - Enable VoLTE on Pixel 6 & 7 with LG U+ `GPL-3.0`
* [TurboIMS](https://github.com/Turbo1123/TurboIMS) ⭐ 359 | 🐛 5 | 🌐 Java | 📅 2025-10-17 - Enhanced IMS Configuration Tool for Google Pixel devices `Apache-2.0`
* [PixelCarrierSettings](https://github.com/iKirby/PixelCarrierSettings) ⭐ 205 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-02 - Enable VoLTE for carriers in unsupported regions on Pixel devices `GPL-3.0`
* [Always On Display](https://f-droid.org/packages/org.alberto97.aodtoggle/) - Toggle Always on Display from the quick settings panel `MIT` [(Source code)](https://github.com/Alberto97/AlwaysOnDisplayToggle) ⭐ 86 | 🐛 0 | 🌐 Kotlin | 📅 2025-05-16
* [Pixel-IMS-5G](https://github.com/barrylk/Pixel-IMS-5G) ⭐ 17 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-04 - Enable 5G standalone (5G SA) and VoNR on Google Pixel devices `GPL-3.0`

#### Samsung OneUI

* [Root-My-Galaxy](https://github.com/BuSung-dev/Root-My-Galaxy) ⭐ 825 | 🐛 365 | 🌐 Kotlin | 📅 2026-08-09 - KSU installer for supported Samsung Galaxy firmware with CVE-2026-43499 `Apache-2.0`
* [SMTShell](https://github.com/BLuFeNiX/SMTShell) ⭐ 244 | 🐛 5 | 🌐 Java | 📅 2023-06-15 - Privilege escalation exploit [(CVE-2019-16253)](https://nvd.nist.gov/vuln/detail/CVE-2019-16253) to system user access (UID 1000) on non-rooted devices running up to OneUI 5. Uses Shizuku for automation `LGPL-2.1`
* [SBatteryTweaks](https://github.com/pascua28/SBatteryTweaks) ⭐ 148 | 🐛 1 | 🌐 Java | 📅 2026-04-18 - Enable or disable fast charging mode on Samsung devices when the battery temperature reaches a certain point  `Proprietary`
* [ScamsungFonts](https://github.com/KhunHtetzNaing/ScamsungFonts) ⭐ 21 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-03 - Font manager for Samsung Galaxy (OneUI) via System shell or Root `No license`
* [ShutterMute](https://github.com/ajebulon/ShutterMute) ⭐ 19 | 🐛 1 | 🌐 Kotlin | 📅 2026-03-05 - Disable the forced camera shutter sounds on Samsung devices that have their CSC set to certain countries with this restriction `Proprietary`
* [Fonts](https://apt.izzysoft.de/fdroid/index/apk/com.je.fontsmanager.samsung) - One UI 8 rootless font installer `GPL-3.0` [(Source code)](https://codeberg.org/dryerlint/fontsmanager)

#### MIUI

* [Mi-FreeForm](https://github.com/sunshine0523/Mi-FreeForm) ⭐ 783 | 🐛 38 | 🌐 Kotlin | 📅 2024-03-25 - Display most apps in the form of freeform on MIUI `GPL-3.0`
* [FxxkMIUIAd](https://github.com/qhy040404/FxxkMIUIAd) ⭐ 187 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-12 - Turn off MIUI ads with minimal cost `Apache-2.0`
* [FiveGSwitcher](https://play.google.com/store/apps/details?id=com.ysy.switcherfiveg) - 5G shortcut switch for HyperOS/MIUI `GPL-3.0` [(Source code)](https://github.com/ysy950803/FiveGSwitcher) ⭐ 145 | 🐛 4 | 🌐 Kotlin | 📅 2026-07-24
* [MixFlipTool](https://github.com/parallelcc/MixFlipTool) ⭐ 68 | 🐛 3 | 🌐 Kotlin | 📅 2024-10-24 - One-click configuration for Mix Flip's outer screen: Use any apps and restore system apps to default style `GPL-3.0`
* [mtbtool-android-app](https://github.com/h3nnes/mtbtool-android-app) ⭐ 16 | 🐛 0 | 🌐 Kotlin | 📅 2026-07-04 - Perform bandlock and edit EFS NV items on qualcomm-based Xiaomi devices without root  `MIT`
* [NavigationSwitcher](https://github.com/chiyuki0325/NavigationSwitcher) ⭐ 7 | 🐛 0 | 🌐 Kotlin | 📅 2024-08-10 - Enable 3-button navigation in rhythm games for MIUI / HyperOS  `Proprietary`

#### Other

* [ClusterTune](https://github.com/AurelioB/ClusterTune) ⭐ 270 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-11 - Tune CPU cluster frequencies to balance performance and power on AYN handheld devices `GPL-2.0`
* [ThorVolumeLink](https://github.com/pth2000/ThorVolumeLink) ⭐ 21 | 🐛 2 | 🌐 Java | 📅 2026-07-18 - Synchronized volume control for the dual displays of the AYN Thor `MIT`
* [RedTrigger](https://github.com/zampierilucas/RedTrigger) ⭐ 12 | 🐛 0 | 🌐 Kotlin | 📅 2026-06-21 - System-wide shoulder triggers for Nubia Red Magic phones `MIT`
* [Recording-Light-Control](https://github.com/Farpathan/Recording-Light-Control) ⭐ 3 | 🐛 2 | 🌐 Kotlin | 📅 2026-01-10 - Recording Light Control gives precise control over the Nothing Phone (3)'s recording light `Proprietary`

### Closed-source apps

Closed-source apps have been moved into a separate sublist. [You can view them here.](pages/CLOSED_SOURCE.md)

> \[!NOTE]
> **Why are closed-source apps in a separate list?**
> Shizuku gives apps high-level ADB access. For security reasons, this main directory only includes open-source and source-available apps, as anyone can check their code to make sure they aren't doing anything shady and compile them on their own machine.
>
> Fully closed-source apps require blind trust, so they are kept in a separate list.
> Almost all closed-source apps have already open-source counterparts that implement the same (if not even more) features anyways.

### Unlisted apps

To keep the main list clean, all apps that have been deprecated or abandoned are stored on a separate page: [ARCHIVED.md](pages/ARCHIVED.md)

> \[!NOTE]
> I'm also using an automated crawler that searches for new projects, making use of Shizuku across GitHub and several F-Droid repos. You can view the [current auto-generated crawl report here](https://github.com/timschneeb/app-crawler/blob/master/SUMMARY.md) ⭐ 78 | 🐛 5 | 🌐 Python | 📅 2026-08-15.

***

## Development libraries

### Core

* [Shizuku-API](https://github.com/RikkaApps/Shizuku-API) ⭐ 2,449 | 🐛 301 | 🌐 Java | 📅 2025-05-29 - Developer documentation for Shizuku and Sui, including examples `Apache-2.0`
* [Shizuku-Plugin (Flutter)](https://github.com/santhosh-D-subramani/Shizuku-Plugin) ⭐ 39 | 🐛 2 | 🌐 Dart | 📅 2025-10-30 - Shizuku API bindings for Flutter apps `GPL-3.0`

### Filesystem

* [Ackpine](https://github.com/solrudev/Ackpine) ⭐ 175 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-07 - Android Coroutines-friendly Kotlin-first Package Installer extensions with Shizuku support `Apache-2.0`
* [shizuku\_apk\_installer](https://github.com/re7gog/shizuku_apk_installer) ⚠️ Archived - Flutter plugin for installing Android APKs using Shizuku API `MIT`
* [nextgenfs](https://github.com/rayshift/nextgenfs) ⭐ 37 | 🐛 1 | 🌐 Java | 📅 2024-02-19 - Shizuku compatible android/data access from Xamarin - AIDL library `MIT`
* [LintFile](https://github.com/lumkit/LintFile) ⭐ 30 | 🐛 1 | 🌐 Kotlin | 📅 2024-07-23 - A file operation library with Shizuku, root, and regular filesystem backends `LGPL-2.1`

### System

* [ServiceManagerCompat](https://github.com/SanmerApps/ServiceManagerCompat) ⚠️ Archived - ServiceManager bindings `MIT`

***

## Miscellaneous content

### Command-line utilities

* [AndroSH](https://github.com/ahmed-alnassif/AndroSH) ⭐ 235 | 🐛 1 | 🌐 Python | 📅 2026-07-14 - Professional Multi-Distribution Linux Environments for Android. Run Archlinux, Fedora, Alpine, Debian, Ubuntu, Kali, Void, Manjaro & Chimera with full Android system integration `GPL-3.0`

### Flows for [Automate](https://llamalab.com/automate/)

* [Better Shizuku Starter](https://llamalab.com/automate/community/flows/50863) - Check and automatically start Shizuku **13.6** on key events via wireless debugging with the *free* version of Automate. `MIT`
* [Shizuku Keeper](https://llamalab.com/automate/community/flows/51118) - Continuously run Shizuku **13.6** or **ADB** uninterrupted without root, Wi-Fi, or cables via USB debugging with Automate *Premium.* `MIT`
  * [Shizuku Keeper Lite](https://llamalab.com/automate/community/flows/51012) - Check Shizuku **13.6** at regular intervals and automatically restart it via wireless debugging with the *free* version of Automate. `MIT`

***

## Annotations

* ✨ - My personal recommendation: makes extensive use of Shizuku or is a unique/hidden gem
* `Paid` 💰 - Paid application
* `IAP` 💰 - Contains in-app purchases
* `Ads` - Contains ads
* `Proprietary` - Not licensed under a FOSS license. Applies to closed-source software or source-available projects.
* `n-day trial` - Payment required after `n` days
* `Root` - Requires Shizuku to run in Root mode

***

## License

This list is licensed under the [Creative Commons Attribution-ShareAlike 3.0 Unported](https://creativecommons.org/licenses/by-sa/3.0/deed.en) License.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-16._
