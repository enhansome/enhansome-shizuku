# awesome-shizuku with stars

### Languages

English | [简体中文](/README_cn.md) | [繁體中文](/README_tw.md)

[![Awesome](https://cdn.jsdelivr.net/gh/sindresorhus/awesome@d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 501,015 | 🐛 105 | 📅 2026-08-21

Shizuku allows normal apps to use system APIs directly with elevated privileges using ADB on non-rooted devices. This list compiles a few apps that are known to make use of Shizuku's capabilities.

More details: <https://shizuku.rikka.app/>

Pull requests are welcome. See [Contributing](CONTRIBUTING.md) for hints. Closed-source apps are listed in a separate file. See [below](#closed-source-apps) for details.

> \[!NOTE]
> To stay up-to-date with this list, [you can check the daily changelogs](https://github.com/timschneeb/changelog-awesome-shizuku) ⭐ 91 | 🐛 0 | 📅 2026-08-25.

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

* [Operit AI](https://github.com/AAswordman/Operit) ⭐ 7,362 | 🐛 91 | 🌐 Kotlin | 📅 2026-08-28 - The most powerful AI agent and AI chat software on Android. Can run commands using Shizuku `LGPL-3.0`
* [OpenMinis](https://github.com/OpenMinis/OpenMinis) ⭐ 4,032 | 🐛 136 | 🌐 Swift | 📅 2026-08-18 - AI-powered agent with Linux shell, browser automation, and system control via Shizuku `GPL-3.0`
* [OmniBot](https://github.com/omnimind-ai/OmniBot) ⭐ 1,934 | 🐛 23 | 🌐 Dart | 📅 2026-08-29 - On-device AI agent with terminal, web browsing, device control, and system integration `GPL-3.0`
* [Ruto-GLM](https://github.com/iamr0s/Ruto-GLM/blob/main/README_en.md) ⭐ 705 | 🐛 11 | 🌐 Kotlin | 📅 2026-01-11 - Automation and Multitasking Framework using AutoGLM. Can create virtual screens that agents can run apps on and use multi-window `Apache 2.0`
* [Open-AutoGLM-Android](https://github.com/xinzezhu/Open-AutoGLM-Android/blob/main/README_EN.md) ⭐ 363 | 🐛 15 | 🌐 Kotlin | 📅 2026-07-21 - Automates actions on your device using the AutoGLM vision language model `GPL-3.0`
* [Mythara](https://github.com/ankurCES/project_mythara) ⭐ 70 | 🐛 2 | 🌐 Kotlin | 📅 2026-05-28 - Open-source local-first agentic AI OS layer for Android. Runs 65+ on-device tools (calls, SMS, calendar, Termux, face recognition); uses Shizuku for cosmetic system tweaks (font scale, dark mode, accent) without root `MIT`
* [rish-mcp](https://github.com/turin-dev/rish-mcp) ⭐ 12 | 🐛 9 | 🌐 Go | 📅 2026-08-26 - Exposes an Android device's Shizuku shell to AIs as an MCP `run_shell` tool over an outbound WebSocket relay — run shell commands from Claude or any MCP client with no VPN, ADB, or sshd `MIT`

### Android TV

* [flicky](https://apt.izzysoft.de/fdroid/index/apk/app.flicky) - An F-Droid client designed for Android TVs `GPL-3.0` [(Source code)](https://github.com/mlm-games/flicky) ⭐ 419 | 🐛 18 | 🌐 Kotlin | 📅 2026-08-24
* [fluffy](https://apt.izzysoft.de/fdroid/index/apk/app.fluffy) - An file manager and archive viewer designed for Android TVs `GPL-3.0` [(Source code)](https://github.com/mlm-games/fluffy) ⭐ 184 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-29
* [RecentAppsTV](https://github.com/Qutaiba-Khader/RecentAppsTV) ⭐ 27 | 🐛 2 | 🌐 Kotlin | 📅 2026-05-31 - Recent Apps overlay for Android TV `Propietary`

### Audio

* [RootlessJamesDSP](https://play.google.com/store/apps/details?id=me.timschneeberger.rootlessjamesdsp) - An implementation of the system-wide JamesDSP audio processing engine for non-rooted Android devices `GPL-3.0` [(Source code)](https://github.com/timschneeb/RootlessJamesDSP) ⭐ 1,647 | 🐛 139 | 🌐 C | 📅 2026-08-23
* [VolumeManager](https://github.com/yume-chan/VolumeManager) ⭐ 544 | 🐛 20 | 🌐 Kotlin | 📅 2026-05-19 - Control each app's volume independently `GPL-2.0`
* [MicUp](https://github.com/papergray/MicUp) ⭐ 143 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-11 ✨ - Real-time microphone audio processing for Android `MIT`
* [wecho](https://github.com/qumolangmo/wecho) ⭐ 89 | 🐛 1 | 🌐 Dart | 📅 2026-08-28 - An Android application for global audio effects processing `MIT`
* [Volume++](https://github.com/noel-digital-fan/volume_plus_plus) ⭐ 82 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-29 - Custom volume panel with per-app audio mixing via Shizuku or root `MIT`

### Automation

* [AutoJs6](https://github.com/SuperMonster003/AutoJs6) ⭐ 6,288 | 🐛 340 | 🌐 Java | 📅 2026-03-16 - JavaScript-based automation tool `MPL-2.0`
* [Geto](https://github.com/JackEblan/Geto) ⭐ 1,163 | 🐛 25 | 🌐 Kotlin | 📅 2026-07-29 - Automatically change device settings when a specific app is launched. `GPL-3.0`
* [PhoneProfilesPlus](https://github.com/henrichg/PhoneProfilesPlus) ⭐ 654 | 🐛 18 | 🌐 Java | 📅 2025-09-29 - Allows automatic or one-click configuration of your device for specific life situations `Apache-2.0`
* [Tasker Settings](https://github.com/joaomgcd/TaskerSettings) ⭐ 595 | 🐛 14 | 🌐 Kotlin | 📅 2025-11-25 - Helper app for Tasker `Propietary`

### Communication

* [TxtNet-Browser](https://github.com/lukeaschenbrenner/TxtNet-Browser) ⭐ 1,519 | 🐛 12 | 🌐 Java | 📅 2026-04-08 - An app that lets you browse the web over SMS `GPL-3.0`
* [ShizuCallRecorder](https://github.com/kitsumed/ShizuCallRecorder) ⭐ 1,356 | 🐛 15 | 🌐 Kotlin | 📅 2026-08-29 ✨ - ShizuCallRecorder empowers ADB through Shizuku to record phone calls on non-rooted device! `GPL-3.0`
* [CatShare](https://f-droid.org/packages/moe.reimu.catshare/) - Send and receive files over Bluetooth `MIT` [(Source code)](https://github.com/kmod-midori/CatShare) ⭐ 742 | 🐛 15 | 🌐 Kotlin | 📅 2026-02-25
* [revenge-manager](https://github.com/revenge-mod/revenge-manager) ⭐ 700 | 🐛 17 | 🌐 Kotlin | 📅 2026-01-12 - Discord modding tool. Another continuation of the abandoned Bunny-Manager project `OSL-3.0`
* [Aliucord-Manager](https://github.com/Aliucord/Manager) ⭐ 670 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-15 - Discord modding tool `OSL-3.0`
* [Kettu](https://github.com/C0C0B01/Kettu) ⭐ 602 | 🐛 1 | 🌐 TypeScript | 📅 2026-08-27 - Discord modding tool. Continuation of the abandoned Bunny-Manager project `BSD-3-Clause`
* [Lemmy Redirect](https://apt.izzysoft.de/fdroid/index/apk/dev.zwander.lemmyredirect) - A simple app for automatically launching Lemmy links in your preferred Lemmy client. `MIT` [(Source code)](https://github.com/zacharee/MastodonRedirect) ⭐ 198 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-10
* [Mastodon Redirect](https://apt.izzysoft.de/fdroid/index/apk/dev.zwander.mastodonredirect) - A simple app for automatically launching fediverse links in your preferred Mastodon client. `MIT` [(Source code)](https://github.com/zacharee/MastodonRedirect) ⭐ 198 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-10
* [Bluesky Redirect](https://apt.izzysoft.de/fdroid/index/apk/io.github.turtlepaw.blueskyredirect) - A simple app for automatically launching Bluesky links in your preferred Bluesky client `MIT` [(Source code)](https://github.com/Turtlepaw/BlueskyRedirect) ⭐ 12 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-31

### Customization

* [TapTap](https://github.com/KieronQuinn/TapTap) ⭐ 4,024 | 🐛 16 | 🌐 Kotlin | 📅 2024-10-26 ✨ - Port of the double tap on the back of the device feature from Android 12 to any Android 7.0+ device `GPL-3.0`
* [essentials](https://github.com/sameerasw/essentials) ⭐ 2,792 | 🐛 96 | 🌐 Kotlin | 📅 2026-08-28 ✨ - Essential tools, mods and workarounds for Pixels. Also compatible with other devices `MIT`
* [AmbientMusicMod](https://github.com/KieronQuinn/AmbientMusicMod) ⭐ 2,497 | 🐛 10 | 🌐 Kotlin | 📅 2024-09-07 - Port of Now Playing from Pixels to other Android devices `GPL-3.0`
* [ShizuTools](https://github.com/legendsayantan/ShizuTools) ⭐ 2,474 | 🐛 30 | 🌐 Kotlin | 📅 2026-07-28 - Contains some easy-to-use tools to go beyond the level of control allowed by Android System `GPL-3.0`
* [ColorBlendr](https://github.com/Mahmud0808/ColorBlendr) ⭐ 2,418 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-23 - An application to modify Material You colors of your device `GPL-3.0`
* [LinkSheet](https://github.com/LinkSheet/LinkSheet) ⭐ 2,083 | 🐛 83 | 🌐 Kotlin | 📅 2026-08-07 - Restore the Android <12 Url-App-Link-Chooser with Material3 `Modified MPL-2.0`
* [System UI Tuner](https://github.com/zacharee/Tweaker) ⭐ 1,720 | 🐛 67 | 🌐 Kotlin | 📅 2026-08-27 - View and modify hidden settings on Android devices `MIT`
* [Smart Dock](https://f-droid.org/packages/cu.axel.smartdock/) - Transform your phone into a desktop environment with taskbar, recent apps, and start menu `GPL-3.0` [(Source code)](https://github.com/axel358/smartdock) ⭐ 1,407 | 🐛 42 | 🌐 Kotlin | 📅 2026-05-21
* [Taskbar](https://f-droid.org/packages/com.farmerbb.taskbar/) - Use a start menu to access apps. Shizuku can unlock additional features `Apache-2.0` [(Source code)](https://github.com/farmerbb/Taskbar) ⭐ 1,246 | 🐛 209 | 🌐 Java | 📅 2024-11-21
* [Tarnhelm](https://f-droid.org/packages/cn.ac.lz233.tarnhelm/) - Clean up tracking from sharing links. Supports custom URL rewrite rules `GPL-3.0` [(Source code)](https://github.com/lz233/Tarnhelm) ⭐ 787 | 🐛 9 | 🌐 Kotlin | 📅 2026-08-13
* [Language-Selector](https://github.com/VegaBobo/Language-Selector) ⭐ 764 | 🐛 8 | 🌐 Kotlin | 📅 2024-12-29 - Allows users to select individual app languages (Android 13+) `Apache-2.0`
* [CarrierVanityName](https://github.com/nullbytepl/CarrierVanityName) ⭐ 686 | 🐛 28 | 🌐 Kotlin | 📅 2024-02-10 - Carrier Vanity Name is a very simple app to change the carrier names on unrooted Android devices `GPL-3.0`
* [Extendroid](https://github.com/legendsayantan/Extendroid) ⭐ 675 | 🐛 7 | 🌐 Kotlin | 📅 2026-07-28 ✨ - Adds desktop-like multi-window support on Android for smartphones. `GPL-3.0`
* [YoukiDEX](https://github.com/mrYouki/YoukiDex-Android-Desktop) ⭐ 551 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-21 - A full desktop experience layer for Android `GPL-3.0`
* [Lockscreen Widgets](https://play.google.com/store/apps/details?id=tk.zwander.lockscreenwidgets) `IAP` 💰 - Display widgets on the lockscreen. Shizuku is only required on Android 13 and later `MIT` [(Source code)](https://github.com/zacharee/LockscreenWidgets/) ⭐ 511 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-29
* [DroidOS](https://github.com/Katsuyamaki/DroidOS) ⭐ 392 | 🐛 10 | 🌐 Kotlin | 📅 2026-05-04 ✨ - Tiling window manager, Samsung DEX replacement, popup app launcher `Proprietary`
* [gama](https://github.com/palincat/gama) ⭐ 380 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-23 - Can switch between OpenGL and Vulkan renderers by setting the `debug.hwui.renderer` system property `MIT`
* [Smart Edge](https://f-droid.org/en/packages/com.imi.smartedge.sidebar.panel/) - A highly customizable Android side panel inspired by OriginOS `MIT` [(Source code)](https://github.com/Imtiaz-Official/Smart-Edge) ⭐ 319 | 🐛 40 | 🌐 Kotlin | 📅 2026-06-13
* [Dragon-Launcher](https://f-droid.org/packages/org.elnix.dragonlauncher/) ✨ - Highly customizable, gestures based Android launcher focused on speed and efficiency `GPL-3.0` [(Source code)](https://github.com/Elnix90/Dragon-Launcher) ⭐ 285 | 🐛 27 | 🌐 Kotlin | 📅 2026-08-29
* [Adaptive-Theme](https://play.google.com/store/apps/details?id=dev.lexip.hecate) - Smart dark mode based on ambient light `GPL-3.0` [(Source code)](https://github.com/xLexip/Adaptive-Theme) ⭐ 211 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-27
* [SmartspacerPlugins](https://github.com/KieronQuinn/SmartspacerPlugins) ⭐ 201 | 🐛 42 | 🌐 Kotlin | 📅 2026-06-13 - Plugins for Smartspacer `GPL-3.0`
* [WidgetsPro](https://github.com/preethamkmr3/WidgetsPro) ⭐ 167 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-20 - CPU and battery widgets `Proprietary`
* [Smart Island](https://github.com/agupta07505/SmartIsland) ⭐ 118 | 🐛 5 | 🌐 Kotlin | 📅 2026-08-29 - A lightweight Android overlay that turns notifications, calls, and media playback into a floating glanceable island `GPL-3.0`
* [CustomAnimator](https://play.google.com/store/apps/details?id=com.arslan.customanimator) - Customize animation speeds on a more fine-grained level `GPL-3.0` [(Source code)](https://github.com/AhmetCanArslan/CustomAnimator) ⭐ 117 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-27
* [AutoDND](https://f-droid.org/packages/moe.dic1911.autodnd/) - A simple tool to toggle DND automatically when using specified apps `AGPL-3.0` [(Source code)](https://github.com/im030/android_AutoDND) ⭐ 104 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-18
* [Jarngreipr](https://github.com/BrianJr03/Jarngreipr) ⭐ 98 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-14 - Launcher for dual-screen gaming devices. Uses Shizuku to map on of the touch screens to controller inputs `MIT`
* [DarQ-Reborn](https://github.com/Arora-Sir/DarQ-Reborn) ⭐ 82 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-12 - Per-app selectable force dark option for Android 10 and above `Apache-2.0`
* [MultiLocale](https://github.com/Nightdavisao/MultiLocale) ⭐ 70 | 🐛 2 | 🌐 Kotlin | 📅 2025-11-11 - A simple app that enables you to add additional (or "unsupported") languages to your device's locale settings, if the OEM (Xiaomi) doesn't let you `MIT`
* [ShizukuShortcuts](https://github.com/yshalsager/ShizukuShortcuts) ⭐ 60 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-29 - Create launcher shortcuts for shell commands `GPL-3.0`
* [OmniPrompt](https://github.com/mrndstvndv/OmniPrompt) ⭐ 54 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-18 - A keyboard-first Android command palette that unifies app/device search, and system utilities into an overlay `GPL-3.0`
* [Dawn-Desktop-Addons](https://github.com/Dawncraft/Dawn-Desktop-Addons) ⭐ 45 | 🐛 3 | 🌐 Java | 📅 2023-10-11 - Some Android app widgets and live wallpapers `GPL-3.0`
* [AutoRotate](https://github.com/eiyooooo/AutoRotate) ⭐ 44 | 🐛 2 | 🌐 Kotlin | 📅 2025-06-10 - Manage automatic rotation of different screens on Android phones `GPL-3.0`

### Development utilities

* [LibChecker](https://github.com/LibChecker/LibChecker) ⭐ 7,121 | 🐛 17 | 🌐 Kotlin | 📅 2026-08-28 - An app to view libraries used in apps on your device. Uses Shizuku to determine the installation source of other apps. `Apache-2.0`
* [DSU-Sideloader](https://github.com/VegaBobo/DSU-Sideloader) ⭐ 2,272 | 🐛 128 | 🌐 Kotlin | 📅 2024-03-13 - A simple app made to help users easily install GSIs via DSU's Android feature. `Apache-2.0`
* [KeyAttestation](https://github.com/vvb2060/KeyAttestation) ⭐ 2,093 | 🐛 18 | 🌐 Java | 📅 2025-09-30 - Supports generating, saving, loading, parsing and verifying Android key and ID attestation data. `Proprietary`
* [ActivityManager](https://github.com/sdex/ActivityManager) ⭐ 1,294 | 🐛 14 | 🌐 Kotlin | 📅 2026-07-25 - Launch hidden and unexported activities directly without root `Apache-2.0`
* [LogFox](https://github.com/F0x1d/LogFox) ⭐ 1,287 | 🐛 19 | 🌐 Kotlin | 📅 2026-08-27 ✨ - Yet another logcat reader for Android `GPL-3.0`
* [Cosmic-IDE](https://github.com/aload0/Cosmic-IDE) ⭐ 719 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-21 - IDE for JVM development. Uses Shizuku for an embedded shell `GPL-3.0`
* [wireless-adb-switch](https://github.com/Smooth-E/wireless-adb-switch) ⭐ 678 | 🐛 11 | 🌐 Kotlin | 📅 2026-05-26 - Widgets & quick settings tile to toggle wireless debugging (with KDE Connect integration) `GPL-3.0`
* [AndroidLowLevelDetector](https://play.google.com/store/apps/details?id=net.imknown.android.forefrontinfo) - Detect Treble, GSI, Mainline, APEX, system-as-root(SAR), A/B, etc. `Apache-2.0` [(Source code)](https://github.com/imknown/AndroidLowLevelDetector) ⭐ 463 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-28
* [AndroidAccounts](https://github.com/iamr0s/AndroidAccounts) ⭐ 322 | 🐛 5 | 🌐 Kotlin | 📅 2023-07-19 - Dump package names of apps that have registered an account for a user. `Proprietary`
* [RootActivityLauncher](https://play.google.com/store/apps/details?id=tk.zwander.rootactivitylauncher) `Paid` 💰 - Launch/interact with (un)exported activities, services, and receivers. Supports Shizuku alongside root. `GPL-3.0` [(Source code)](https://github.com/zacharee/RootActivityLauncher) ⭐ 286 | 🐛 6 | 🌐 Kotlin | 📅 2025-09-29
* [CurrentActivity](https://github.com/Omico/CurrentActivity) ⭐ 281 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-27 - A current activity monitor `GPL-3.0`
* [FrameX-Android](https://github.com/MaheshSharan/FrameX-Android) ⭐ 130 | 🐛 12 | 🌐 Kotlin | 📅 2026-08-02 - Real-time performance overlay for Android `MIT`
* [dualapp-mediastore-compatibility](https://github.com/kaedea/dualapp-mediastore-compatibility) ⭐ 57 | 🐛 0 | 🌐 Java | 📅 2025-07-15 - Fixes MediaStore & File IO compatibility issues between HostProfile App and WorkProfile/DualApp/MultiApp. `Proprietary`
* [FPSViewer](https://github.com/binhmod/FPSViewer) ⭐ 54 | 🐛 3 | 🌐 Java | 📅 2026-05-21 - FPS viewer overlay with graph `Proprietary`
* [ManageSensors](https://github.com/Carry-rrk/ManageSensors) ⭐ 44 | 🐛 2 | 🌐 Kotlin | 📅 2025-01-18 - Utilizes Shizuku to call AppOps APIs for fine-grained app permission control `MIT`
* [get\_event](https://github.com/lalakii/get_event) ⭐ 39 | 🐛 0 | 🌐 Java | 📅 2026-08-10 - Read /dev/input/event\* `Proprietary`
* [debuggable-app-data-backup](https://github.com/timschneeb/debuggable-app-data-backup) ⭐ 36 | 🐛 1 | 🌐 Kotlin | 📅 2026-02-04 - Backup/restore private app data of debuggable apps using Shizuku `GPL-3.0`

### Device owner (DPM)

* [Dhizuku](https://github.com/iamr0s/Dhizuku) ⭐ 3,753 | 🐛 19 | 🌐 Kotlin | 📅 2026-08-27 - Shizuku-inspired app that allows sharing DeviceOwner permissions to third-party apps `GPL-3.0`
* [OwnDroid](https://github.com/BinTianqi/OwnDroid) ⭐ 1,348 | 🐛 9 | 🌐 Kotlin | 📅 2026-08-26 - Manage your device with Device owner privileges `GPL-3.0`
  * [MDPC](https://github.com/MrRare2/MDPC) ⭐ 115 | 🐛 0 | 🌐 Kotlin | 📅 2026-03-13 - Fork of OwnDroid with added features `GPL-3.0`
* [harbor](https://f-droid.org/packages/com.monstera.harbor/) - Work-profile manager with optional Shizuku tools for automation `Apache-2.0` [(Source code)](https://github.com/Stem0794/harbor) ⭐ 23 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-26

### Display management

* [SecondScreen](https://play.google.com/store/apps/details?id=com.farmerbb.secondscreen.free) - Better screen mirroring for Android devices `Apache-2.0` [(Source code)](https://github.com/farmerbb/SecondScreen) ⭐ 514 | 🐛 59 | 🌐 Java | 📅 2024-09-14
* [Dextop](https://github.com/NarYuki/Dextop) ⭐ 182 | 🐛 2 | 🌐 Dart | 📅 2026-08-26 - Desktop environment using Samsung DeX or Shizuku with multitasking and custom resolution `GPL-3.0`
* [Grayscaler](https://github.com/C10udburst/Grayscaler) ⭐ 162 | 🐛 6 | 🌐 Kotlin | 📅 2025-02-18 - Keep your phone mostly monochrome, but allow apps like camera to be in color `GPL-3.0`
* [android-display-mirror](https://github.com/jqssun/android-display-mirror) ⭐ 157 | 🐛 11 | 🌐 C++ | 📅 2026-08-24 ✨ - Screen mirroring hub with support for sharing screen content over AirPlay, Moonlight/Sunshine, and DisplayLink `GPL-3.0`
* [android-display-extend](https://github.com/jqssun/android-display-extend) ⭐ 147 | 🐛 6 | 🌐 Java | 📅 2026-07-22 ✨ - Display manager for physical and virtual displays with a built-in virtual touchscreen. Great for use with `scrcpy --new-display` on a PC `GPL-3.0`
* [Fold\_Switcher](https://github.com/eiyooooo/Fold_Switcher) ⭐ 95 | 🐛 5 | 🌐 Kotlin | 📅 2025-06-10 - Switch between various display folding states on foldable devices `Apache-2.0`
* [Adaptive-Hz](https://github.com/mahmutaunal/Adaptive-Hz) ⭐ 73 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-20 - Automatically switches display refresh rate between 60Hz and 120Hz based on user interaction. Designed for Samsung devices without true adaptive refresh `MIT`
* [deskcontrol](https://github.com/exiarepairii/deskcontrol) ⭐ 60 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-08 - Turns your phone into a touchpad and keyboard for a single app running on a wired external display `GPL-3.0`
* [ConnectScreen](https://connect-screen.com/) - Launch single apps to display in fullscreen on external displays. Can use the primary screen of the mobile as a virtual touchpad to control external display. Can rotate the screen for applications like TikTok `GPL-3.0` [(Source code)](https://gitee.com/connect-screen/connect-screen)

### Entertainment

* [Mihon](https://github.com/mihonapp/mihon) ⭐ 23,210 | 🐛 722 | 🌐 Kotlin | 📅 2026-08-28 - Manga reader using Shizuku plugin management. Independent successor of Tachiyomi. `Apache-2.0`
  * Mihon/Tachiyomi has several other active forks, including [TachiyomiSY](https://github.com/jobobby04/TachiyomiSY) ⭐ 4,121 | 🐛 313 | 🌐 Kotlin | 📅 2026-08-27 and [TachiyomiAZ](https://github.com/az4521/TachiyomiAZ) ⭐ 728 | 🐛 22 | 🌐 Kotlin | 📅 2026-08-28
* [Aniyomi](https://github.com/aniyomiorg/aniyomi) ⭐ 7,634 | 🐛 375 | 🌐 Kotlin | 📅 2026-08-26 - Tachiyomi fork with anime support and plugin management using Shizuku. `Apache-2.0`
* [BiliDownOut](https://f-droid.org/packages/cn.a10miaomiao.bilidown/) - Export videos downloaded from the Android version of Bilibili `GPL-3.0` [(Source code)](https://github.com/10miaomiao/bili-down-out) ⭐ 376 | 🐛 15 | 🌐 Kotlin | 📅 2026-07-19
* [hlbmerge\_flutter](https://github.com/molihuan/hlbmerge_flutter) ⭐ 351 | 🐛 4 | 🌐 Dart | 📅 2026-07-27 - Merge and export BiliBili cache files into MP4, supports mobile and computer client `Apache-2.0`

### File management

* [SDMaid-SE](https://play.google.com/store/apps/details?id=eu.darken.sdmse) `IAP` 💰 - SD Maid 2/SE is Android's most thorough cleaning tool `GPL-3.0` [(Source code)](https://github.com/d4rken-org/sdmaid-se) ⭐ 7,398 | 🐛 15 | 🌐 Kotlin | 📅 2026-08-27
* [NFile](https://github.com/Senzme/NFile) ⭐ 383 | 🐛 61 | 🌐 Dart | 📅 2026-08-11 - File manager with Android folder access using Shizuku `GPL-3.0`
* [fluffy](https://apt.izzysoft.de/fdroid/index/apk/app.fluffy) - An file manager and archive viewer with Android TV support. Supports full file access using Shizuku, if enabled in settings `GPL-3.0` [(Source code)](https://github.com/mlm-games/fluffy) ⭐ 184 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-29
* [ZenFile](https://github.com/l930203811/ZenFile) ⭐ 123 | 🐛 5 | 🌐 Dart | 📅 2026-08-29 - NFile fork with built-in remote file server support `GPL-3.0`
* [XFiles](https://github.com/Local1stDotApp/XFiles) ⭐ 29 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-15 - Offline file manager with root and Shizuku support for full filesystem access `GPL-3.0`
* [XArchiver](https://github.com/Xtra-Manager-Software/XArchiver) ⭐ 2 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-22 - File manager with built-in archive support `MIT`

> \[!NOTE]
> [See here more file managers (closed-source)](pages/CLOSED_SOURCE.md#file-management)

### Games

* [translatefgo](https://github.com/rayshift/translatefgo) ⭐ 337 | 🐛 13 | 🌐 C# | 📅 2026-04-25 - Fate/Grand Order game translation project `MIT`
* [Ascent](https://github.com/4o3F/Ascent) ⭐ 217 | 🐛 1 | 🌐 Dart | 📅 2026-04-22 - A tool for retrieving gacha history links from Mihoyo games  `AGPL-3.0`
* [blocktopograph](https://github.com/Blocktopograph/Blocktopograph) ⭐ 180 | 🐛 5 | 📅 2026-01-11 - Blocktopograph is an app server for MCBE, it includes a world, NBT editor for local worlds `Apache-2.0`
* [LOModInstaller](https://github.com/anyabot/LOModInstaller) ⭐ 83 | 🐛 1 | 🌐 Kotlin | 📅 2026-06-23 - Mod manager for the game 'Last Origin' `Proprietary`
* [BDroid\_X](https://github.com/Ark-Repoleved/BDroid_X) ⭐ 81 | 🐛 9 | 🌐 JavaScript | 📅 2026-04-27 - Browndust II Mod manager `Proprietary`
* [pogoplusle](https://github.com/Mygod/pogoplusle) ⭐ 67 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-26 - Skip the pairing dialog when connecting a Pokémon GO Plus `Apache-2.0`
* [umamusume-localify-android](https://github.com/Kimjio/umamusume-localify-android) ⭐ 58 | 🐛 6 | 🌐 C++ | 📅 2026-08-21 - Localization module for Umamusume via Zygisk with Shizuku integration `MIT`
* [stalker](https://github.com/onerdna/stalker) ⭐ 51 | 🐛 63 | 🌐 Dart | 📅 2026-08-09 - Save data viewer & editor for Shadow Fight 2 `GPL-3.0`
* [HandheldExp](https://github.com/Teppichseite/HandheldExp) ⭐ 49 | 🐛 2 | 🌐 Kotlin | 📅 2024-09-22 - In-game menu for EmulationStation (ES-DE) on Android  `MIT`
* [CloudSync-Mobile](https://github.com/StardewValleyMods/CloudSync-Mobile) ⭐ 30 | 🐛 0 | 🌐 TypeScript | 📅 2026-05-25 - An app that allows you to sync your Stardew Valley saves across multiple devices `GPL-3.0`
* [lac-tool](https://github.com/aliernfrog/lac-tool) ⭐ 21 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-29 - Manage maps, wallpapers, and screenshots for the game 'Los Angeles Crimes' `GPL-3.0`
* [pf-tool](https://github.com/aliernfrog/pf-tool) ⭐ 19 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-24 - Easily import and share Polyfield maps `GPL-3.0`
* [Okkei Patcher](https://github.com/solrudev/OkkeiPatcher) ⭐ 10 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-31 - Companion app for localizing the Android version of CHAOS;CHILD visual novel `GPL-3.0`
* [ShinGen](https://github.com/Shio2077/ShinGen#genshin-impact-auto-conversation-clicker-on-android) ⭐ 8 | 🐛 0 | 🌐 Java | 📅 2025-11-27 - Genshin Impact Auto-Conversation Clicker `MIT`

### Input methods

* [KeyMapper](https://play.google.com/store/apps/details?id=io.github.sds100.keymapper) ✨ - An Android app that changes what the buttons do on your devices! `GPL-3.0` [(Source code)](https://github.com/keymapperorg/KeyMapper) ⭐ 2,620 | 🐛 203 | 🌐 Kotlin | 📅 2026-08-11
* [XtMapper](https://github.com/Xtr126/XtMapper) ⭐ 433 | 🐛 35 | 🌐 Java | 📅 2026-07-18 - Keymapper for Android x86 `GPL-3.0`
* [pastiera](https://github.com/palsoftware/pastiera) ⭐ 191 | 🐛 60 | 🌐 Kotlin | 📅 2026-08-20 - Android keyboard specialized for Physical Keyboard Devices. Uses Shizuku for trackpad gestures `GPL-3.0`
* [keysync](https://github.com/aka-munan/keysync) ⭐ 144 | 🐛 11 | 🌐 Kotlin | 📅 2026-02-26 - Play games using mouse and keyboard on Android device; keymapper for games `Apache-2.0`
* [C9](https://github.com/austinauyeung/C9) ⭐ 92 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-12 - Efficient grid-based cursor provided alongside a traditional cursor. Shizuku is only required on Android 11. `Apache-2.0`
* [Android-Show-Taps](https://github.com/k3x1n/Android-Show-Taps) ⭐ 47 | 🐛 8 | 🌐 Kotlin | 📅 2024-06-23 - Show customized taps upon touches `GPL-3.0`
* [TitanPad](https://github.com/sztupy/TitanPad) ⭐ 28 | 🐛 8 | 🌐 Kotlin | 📅 2026-05-06 - Converts the Titan2's Physical Keyboard's capacitive input into mouse and scroll gestures. Uses Shizuku for reading the trackpad input and setting up virtual HID devices `Apache-2.0`
* [andRemote2](https://github.com/c0dev0id/andRemote2) ⭐ 1 | 🐛 0 | 🌐 Kotlin | 📅 2026-04-21 - Emulates the DMD Remote 2 for map apps `Proprietary`

### Installer & app stores

* [Obtainium](https://github.com/ImranR98/Obtainium) ⭐ 19,326 | 🐛 386 | 🌐 Dart | 📅 2026-08-29 - Get Android App Updates Directly From the Source `GPL-3.0`
  * [ObtainX](https://f-droid.org/packages/dev.bikram.obtainx/) - Obtainium fork with Material 3 UI redesign `GPL-3.0` [(Source code)](https://github.com/bikram-agarwal/ObtainX) ⭐ 1,068 | 🐛 7 | 🌐 Dart | 📅 2026-08-29
* [GitHub-Store](https://f-droid.org/packages/zed.rainxch.githubstore/) - App store for GitHub releases with discovery function `Apache-2.0` [(Source code)](https://github.com/kurikomi-labs/komi-store) ⭐ 18,051 | 🐛 113 | 🌐 Kotlin | 📅 2026-07-29
* [Droid-ify](https://f-droid.org/packages/com.looker.droidify/) - Material F-Droid client `GPL-3.0` [(Source code)](https://github.com/Droid-ify/client) ⭐ 7,335 | 🐛 195 | 🌐 Kotlin | 📅 2026-08-28
* [InstallerX-Revived](https://github.com/wxxsfxyzm/InstallerX-Revived) ⭐ 6,369 | 🐛 17 | 🌐 Kotlin | 📅 2026-08-28 ✨ - Modern and functional Android app installer replacement `GPL-3.0`
* [Neo-Store](https://f-droid.org/packages/com.machiav3lli.fdroid/) - An F-Droid client with modern UI and an arsenal of extra features `GPL-3.0` [(Source code)](https://github.com/NeoApplications/Neo-Store) ⭐ 4,950 | 🐛 126 | 🌐 Kotlin | 📅 2026-08-26
* [SAI](https://f-droid.org/packages/com.aefyr.sai.fdroid/) - Android split APKs installer `GPL-3.0` [(Source code)](https://github.com/Aefyr/SAI) ⭐ 3,807 | 🐛 0 | 🌐 Java | 📅 2024-06-03
* [InstallWithOptions](https://github.com/zacharee/InstallWithOptions) ⭐ 3,181 | 🐛 14 | 🌐 Kotlin | 📅 2026-08-27 - Simple-ish app using Shizuku to install APKs on-device with advanced options `MIT`
* [Orion Store](https://github.com/RookieEnough/Orion-Store) ⭐ 3,177 | 🐛 71 | 🌐 TypeScript | 📅 2026-08-17 - App store for modded apps `GPL-3.0`
* [universal-installer](https://github.com/pass-with-high-score/universal-installer) ⭐ 1,329 | 🐛 21 | 🌐 Kotlin | 📅 2026-08-29 - Install and manage APK packages with split APK support, silent install via Shizuku, and VirusTotal malware scanning `GPL-3.0`
* [instafel](https://github.com/mamiiblt/instafel) ⭐ 1,254 | 🐛 15 | 🌐 Java | 📅 2026-08-21 - Updater app for Instafel, an Instagram mod `MIT`
* [ffupdater](https://f-droid.org/packages/de.marmaro.krt.ffupdater/) - FFUpdater: Updater for privacy-friendly browser `GPL-3.0` [(Source code)](https://github.com/Tobi823/ffupdater) ⭐ 1,084 | 🐛 88 | 🌐 Kotlin | 📅 2026-06-27
* [Shizuku Package Installer](https://github.com/vvb2060/PackageInstaller) ⭐ 699 | 🐛 8 | 🌐 Kotlin | 📅 2025-08-12 - A lightweight app installer replacement with split APK support `Apache-2.0`
* [PI](https://github.com/SanmerApps/PI) ⭐ 698 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-28 - Package installer that allows overwriting the package requester and executor `MIT`
* [florid](https://github.com/Nandanrmenon/florid) ⭐ 499 | 🐛 46 | 🌐 Dart | 📅 2026-06-16 - Material3 F‑Droid Client `GPL-3.0`
* [BHub](https://github.com/B1ays/BHub) ⭐ 357 | 🐛 4 | 🌐 Kotlin | 📅 2025-10-01 - Download, install and share mods easily `Proprietary`
* [ShizuCoreFetch](https://github.com/elhizazi1/ShizuCoreFetch) ⭐ 328 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-27 - Shizuku-powered app manager with silent installs, updates, and batch operations `GPL-3.0`
* [AuroraStore](https://f-droid.org/packages/com.aurora.store/) - An open-source alternative to Google Play Store with privacy and modern design `GPL-3.0` [(Source code)](https://gitlab.com/AuroraOSS/AuroraStore)
* [IzzyOnDroid](https://gitlab.com/sunilpaulmathew/izzyondroid) - An unofficial client for IzzyOnDroid F-Droid Repository `GPL-3.0`

### Miscellaneous

* [SimpleWear](https://play.google.com/store/apps/details?id=com.thewizrd.simplewear) - A simple app for controlling your Android devices from your WearOS watch `Apache-2.0` [(Source code)](https://github.com/SimpleAppProjects/SimpleWear) ⭐ 184 | 🐛 6 | 🌐 Kotlin | 📅 2025-11-11
* [krude](https://github.com/KusStar/krude) ⭐ 163 | 🐛 1 | 🌐 Kotlin | 📅 2025-08-13 - All-in-one app and workflow launcher. Uses Shizuku for process killing and file management `MIT`
* [AppBooster](https://github.com/androidexpert35/AppBooster) ⭐ 93 | 🐛 8 | 🌐 Kotlin | 📅 2026-07-20 - GUI for Android's builtin `dex2oat` utility, allowing DEX code of installed apps to be re-optimized `Apache-2.0`
* [NotiFixer](https://github.com/dkajan19/NotiFixer) ⭐ 83 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-06 - Android utility to make notifications persistent/undismissable using Shizuku `MIT`
* [PoC-Deployer-System](https://github.com/wqry085/PoC-Deployer-System) ⭐ 77 | 🐛 0 | 🌐 Java | 📅 2026-02-16 - Exploits CVE-2024-31317 for Zygote injection, integrating remote terminal and file transfer capabilities `MIT`
* [telegram-rc](https://github.com/telegram-sms/telegram-rc) ⭐ 65 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-26 - Remote control your device via Telegram messages `BSD 3-Clause`
* [OnStop2FinishAndRemoveTask](https://github.com/takusan23/OnStop2FinishAndRemoveTask) ⭐ 33 | 🐛 1 | 🌐 Kotlin | 📅 2026-08-12 - Automatically close selected apps when you exit them to save power and memory `Apache-2.0`
* [HiddenAlarmRevealer](https://github.com/AhmetCanArslan/HiddenAlarmRevealer) ⭐ 19 | 🐛 0 | 🌐 Java | 📅 2026-04-04 - Find the reason why the alarm icon is active in the status bar `Proprietary`

### Network

* [sing-box](https://f-droid.org/packages/io.nekohasekai.sfa/) - Universal proxy platform. Uses Shizuku for per-app proxying `GPL-3.0` [(Source code)](https://github.com/SagerNet/sing-box) ⭐ 37,361 | 🐛 289 | 🌐 Go | 📅 2026-08-29
* [WG Tunnel](https://github.com/wgtunnel/android) ⭐ 3,095 | 🐛 107 | 🌐 Kotlin | 📅 2026-08-28 - A FOSS Android client for WireGuard and AmneziaWG with auto-tunneling. `MIT`
* [ShizuWall](https://github.com/AhmetCanArslan/ShizuWall) ⭐ 2,182 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-28 ✨ - Open-source app firewall that doesn't depend on VPNs or root `GPL-3.0`
* [Traffic Light](https://play.google.com/store/apps/details?id=com.leekleak.trafficlight) - A persistent network speed tracker in your status bar `GPL-3.0` [(Source code)](https://github.com/leekleak/traffic-light) ⭐ 828 | 🐛 21 | 🌐 Kotlin | 📅 2026-08-13
* [ADNS](https://github.com/eyalm2000/adns) ⭐ 576 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-26 - DNS-based ad blocker for Android `MIT`
* [delta](https://github.com/supershadoe/delta) ⭐ 556 | 🐛 17 | 🌐 Kotlin | 📅 2026-05-02 - Hotspot manager using Shizuku `BSD-3-Clause`
* [NetworkSwitch](https://github.com/aunchagaonkar/NetworkSwitch) ⭐ 451 | 🐛 20 | 🌐 Kotlin | 📅 2026-08-20 - Android app for 4G/5G network mode switching `GPL-3.0`
* [de1984](https://github.com/dorumrr/de1984) ⭐ 389 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-29 - App firewall without using an VPN; can also manage packages `MIT`
* [wifi-password-manager](https://github.com/Khh-vu/wifi-password-manager) ⭐ 289 | 🐛 6 | 🌐 Kotlin | 📅 2026-08-25 - Simple app using Shizuku to manage & view saved Wi-Fi passwords `MIT`
* [WiFiList](https://play.google.com/store/apps/details?id=tk.zwander.wifilist) `Paid` 💰 - View your saved WiFi passwords on Android 11 and later without root `Proprietary` [(Source code)](https://github.com/zacharee/WiFiList) ⭐ 267 | 🐛 9 | 🌐 Kotlin | 📅 2025-01-18
* [FireWall Blocks](https://github.com/shynoiddev/FireWall-Blocks) ⭐ 216 | 🐛 9 | 🌐 Kotlin | 📅 2026-07-09 - Dual-mode firewall: blocks internet access using Shizuku or a standard local VPN interface or both. `MIT`
* [CellReader](https://play.google.com/store/apps/details?id=dev.zwander.cellreader) `Paid` 💰 - Can read cell tower info on Android `MIT` [(Source code)](https://github.com/zacharee/CellReader) ⭐ 90 | 🐛 0 | 🌐 Kotlin | 📅 2025-09-20
* [Dolphy-App](https://github.com/unvoiddd/Dolphy-App) ⭐ 71 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-26 - NFC, BLE, and IR multi-tool for wireless protocol research `GPL-3.0`
* [Hostman](https://github.com/LinZong/Hostman) ⭐ 54 | 🐛 0 | 🌐 Kotlin | 📅 2025-12-31 `Root` - Preview & edit the /etc/hosts file `MIT`
* [EasySpot](https://github.com/EasySpotApp/EasySpot) ⭐ 49 | 🐛 1 | 🌐 Kotlin | 📅 2025-10-26 - An app that allows you to turn on your hotspot remotely via Bluetooth - think Apple Continuity, but for everyone `GPL-3.0`
* [NaiveproxyForAndroid](https://github.com/Dobiec/NaiveproxyForAndroid) ⭐ 47 | 🐛 2 | 🌐 Java | 📅 2024-10-30 - A simple application to run Naiveproxy on Android `MIT`
* [Shizzi](https://github.com/carlelieser/shizzi) ⭐ 41 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-22 - Rootless Wi-Fi tethering bypass via Shizuku `Proprietary`
* [NetToggle](https://github.com/Dhangofa/NetToggle) ⭐ 27 | 🐛 0 | 🌐 Java | 📅 2026-08-27 - A lightweight Android Quick Settings tile to force 5G Only, 4G Only and preferred network modes using Root or Shizuku `GPL-3.0`
* [FindMyDevice](https://gitlab.com/fmd-foss/fmd-android) - Secure & open-source alternative to Google's FindMyDevice service. `GPL-3.0`

### Patching

* [Morphe](https://morphe.software/) - User-friendly YouTube patcher based on Universal-ReVanced-Manager `GPL-3.0` [(Source code)](https://github.com/MorpheApp/morphe-manager) ⭐ 7,555 | 🐛 26 | 🌐 Kotlin | 📅 2026-08-29
* [LSPatch](https://github.com/JingMatrix/LSPatch) ⭐ 3,774 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-23 - A non-root Xposed framework extending from LSPosed `GPL-3.0`
* [Universal-ReVanced-Manager](https://github.com/Jman-Github/Universal-ReVanced-Manager) ⭐ 1,285 | 🐛 55 | 🌐 Kotlin | 📅 2026-08-29 - ReVanced patcher that has extra features the official manager doesn't have `GPL-3.0`

### Power management

* [EnforceDoze](https://f-droid.org/packages/com.akylas.enforcedoze/) - Enable Doze mode immediately after screen off and turn off motion sensing to get best battery life `GPL-3.0` [(Source code)](https://github.com/Akylas/EnforceDoze) ⭐ 356 | 🐛 21 | 🌐 Java | 📅 2026-07-26
* [NoMoreBackground](https://f-droid.org/packages/com.adilhanney.no_more_background/) - A fire-and-forget program to stop Android apps from running in the background `GPL-3.0` [(Source code)](https://github.com/adil192/no_more_background) ⭐ 309 | 🐛 9 | 🌐 Dart | 📅 2026-08-06
* [ScreenOff](https://github.com/WuDi-ZhanShen/ScreenOff) ⭐ 262 | 🐛 14 | 🌐 Java | 📅 2025-01-14 - Turn off your Android's screen without entering standby/sleep mode `Proprietary`
* [RebootNya](https://github.com/daisukiKaffuChino/RebootNya) ⭐ 254 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-20 - Advanced reboot menu with Shizuku support `Apache-2.0`
* [BatStats](https://github.com/mlm-games/BatStats) ⭐ 175 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-24 - Battery monitor with stats via Shizuku `GPL-3.0`
* [Battery-Monitor](https://github.com/tswistak/Battery-Monitor) ⭐ 69 | 🐛 41 | 🌐 Kotlin | 📅 2026-08-25 - Track and log battery capacity and parameters over time using Shizuku `GPL-3.0`
* [sleep-timer](https://github.com/Xitee1/sleep-timer) ⭐ 49 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-25 - Sleep timer that can pause media, and turn off WIFI/Bluetooth/Display `GPL-3.0`
* [zukulock](https://github.com/tiendnm/zukulock) ⭐ 46 | 🐛 0 | 🌐 Kotlin | 📅 2025-08-19 - Very lightweight app that locks the screen when launched. Helps reduce wear on the power button `MIT`
* [Amply](https://github.com/d4rken-org/amply) ⭐ 29 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-27 - Easy control of charging limits. Temporarily allows one full charge, then automatically restores your protective charge limit `GPL-3.0`
* [battery-stats-changer](https://github.com/superisuer/battery-stats-changer) ⭐ 23 | 🐛 0 | 🌐 Java | 📅 2025-12-28 - Open source app to visually change battery data via Shizuku `GPL-3.0`
* [Batt](https://gitlab.com/narektor/batt) - A simple app that shows battery status information on Android 14 and later. `GPL-3.0`

### Privacy

* [Amarok-Hider](https://apt.izzysoft.de/fdroid/index/apk/deltazero.amarok.foss) - Hide your private files and Android apps with just one click `Apache-2.0` [(Source code)](https://github.com/deltazefiro/Amarok-Hider) ⭐ 3,219 | 🐛 61 | 🌐 Java | 📅 2026-08-11
* [AppLock](https://github.com/aload0/AppLock) ⭐ 848 | 🐛 106 | 🌐 Kotlin | 📅 2026-07-21 ✨ - Lock sensitive apps with a PIN and optionally biometrics `MIT`
* [PrivacyFlip](https://f-droid.org/packages/io.github.dorumrr.privacyflip/) - Manage your device privacy based on lock/unlock state `MIT` [(Source code)](https://github.com/dorumrr/privacyflip) ⭐ 277 | 🐛 13 | 🌐 Kotlin | 📅 2026-01-22
* [AntiForensic-Tools](https://github.com/bakad3v/Android-AntiForensic-Tools) ⭐ 190 | 🐛 2 | 🌐 Kotlin | 📅 2026-08-27 - An application designed to silently protect user data from powerful adversaries `GPL-3.0`

### Productivity

* [Curbox](https://f-droid.org/packages/neth.iecal.curbox/) ✨ - Tool to reduce screen addiction and view usage analytics `GPL-3.0` [(Source code)](https://github.com/curbox-app/curbox-android) ⭐ 1,263 | 🐛 33 | 🌐 Kotlin | 📅 2026-08-28
* [DetoxDroid](https://github.com/flxapps/DetoxDroid) ⭐ 510 | 🐛 53 | 🌐 Kotlin | 📅 2026-07-27 - Digital Detoxing: Use your phone rather than letting your phone use you `GPL-3.0`
* [Blink](https://github.com/character-flat/Blink) ⭐ 18 | 🐛 0 | 🌐 Kotlin | 📅 2026-05-17 - A persistent, highly customizable 20-20-20 rule eye-care timer that uses Shizuku to whitelist itself from Android's battery optimizations `GPL-3.0`

### Quick settings

* [PrivateDNSAndroid](https://github.com/karasevm/PrivateDNSAndroid) ⭐ 1,029 | 🐛 13 | 🌐 Kotlin | 📅 2026-07-29 - Quick settings tile to switch active private DNS server `MIT`
* [Quick-Tile Settings](https://f-droid.org/packages/com.rbn.qtsettings/) - QS tiles for toggling USB debugging and switching private DNS hosts `GPL-3.0` [(Source code)](https://github.com/RBN-Apps/Quick-Tile-Settings) ⭐ 367 | 🐛 13 | 🌐 Kotlin | 📅 2026-08-27
* [Better Internet Tiles](https://play.google.com/store/apps/details?id=be.casperverswijvelt.unifiedinternetqs) - Bring back Wi-Fi and mobile data tiles on Android 12 or higher + a better-unified internet tile `GPL-3.0` [(Source code)](https://github.com/CasperVerswijvelt/Better-Internet-Tiles) ⭐ 258 | 🐛 32 | 🌐 Kotlin | 📅 2025-05-12
* [Private DNS Quick Setting](https://apt.izzysoft.de/fdroid/index/apk/com.flashsphere.privatednsqs) - QS tile for toggling the private DNS setting on or off `GPL-3.0` [(Source code)](https://github.com/flashsphere/private-dns-qs) ⭐ 125 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-28
* [SensorsOff](https://github.com/LinerSRT/SensorsOff) ⭐ 102 | 🐛 2 | 🌐 Java | 📅 2023-09-17 - Enable/Disable device sensors via quick settings `Apache-2.0`
* [DNS Toggle](https://f-droid.org/packages/com.ericlowry.dnstoggle/) - Quick Settings tile for Private DNS toggling and configuration, with optional advanced automation. `MIT` [(Source code)](https://github.com/ELowry/DNSToggle) ⭐ 101 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-23
* [AlwaysOnDisplayToggle](https://f-droid.org/packages/org.alberto97.aodtoggle/) - An Android quick setting to toggle Always on Display `MIT` [(Source code)](https://github.com/Alberto97/AlwaysOnDisplayToggle) ⭐ 86 | 🐛 0 | 🌐 Kotlin | 📅 2025-05-16
* [DataSimTile](https://github.com/Mygod/DataSimTile) ⭐ 50 | 🐛 0 | 🌐 Java | 📅 2026-08-08 - Tile to switch the default mobile data SIM `Apache-2.0`
* [DisplayToggle](https://f-droid.org/packages/io.github.ulysseszh.displaytoggle/) - Provides quick settings tile and shortcuts to turn off the display without locking the screen or stopping foreground running apps `MIT` [(Source code)](https://github.com/UlyssesZh/DisplayToggle) ⭐ 21 | 🐛 2 | 🌐 Kotlin | 📅 2025-09-20

### Software management

* [Hail](https://f-droid.org/packages/com.aistra.hail/) ✨ - Freeze, hide, or disable any app. Create and organize app groups that can be frozen with one click. `GPL-3.0` [(Source code)](https://github.com/aistra0528/Hail) ⭐ 6,568 | 🐛 167 | 🌐 Kotlin | 📅 2026-08-28
* [Canta](https://play.google.com/store/apps/details?id=io.github.samolego.canta) - Uninstall any app without root `LGPL-3.0` [(Source code)](https://github.com/samolego/Canta) ⭐ 5,672 | 🐛 30 | 🌐 Kotlin | 📅 2026-08-24
* [Island](https://play.google.com/store/apps/details?id=com.oasisfeng.island) - Isolate and clone apps for privacy protection and parallel running `Apache-2.0` [(Source code)](https://github.com/oasisfeng/island) ⭐ 3,888 | 🐛 670 | 🌐 Java | 📅 2025-04-24
* [Blocker](https://github.com/lihenggui/blocker) ⭐ 2,379 | 🐛 44 | 🌐 Kotlin | 📅 2026-08-27 - Enable/disable Android components such as activities, services, receivers, and providers `Apache-2.0`
* [MMRL](https://github.com/MMRLApp/MMRL) ⭐ 2,144 | 🐛 7 | 🌐 Kotlin | 📅 2026-08-18 `Root` - Manage your Magisk module repository `GPL-3.0`
* [Inure App Manager](https://play.google.com/store/apps/details?id=app.simple.inure.play) `15-day trial` `IAP` 💰 - Android app manager for both rooted and non-rooted devices `GPL-3.0` [(Source code)](https://github.com/Hamza417/Inure) ⭐ 1,899 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-28
* [UpgradeAll](https://f-droid.org/packages/net.xzos.upgradeall/) - Check updates for Android apps, Magisk modules and more! `GPL-3.0` [(Source code)](https://github.com/DUpdateSystem/UpgradeAll) ⭐ 1,334 | 🐛 40 | 🌐 Kotlin | 📅 2026-08-28
* [Package Manager](https://play.google.com/store/apps/details?id=com.smartpack.packagemanager) - A powerful app to manage both system and user apps `GPL-3.0` [(Source code)](https://github.com/SmartPack/PackageManager) ⭐ 814 | 🐛 71 | 🌐 Java | 📅 2026-08-25
* [Thor](https://play.google.com/store/apps/details?id=com.valhalla.thor) - App manager with freeze and install capabilities. `GPL-3.0` [(Source code)](https://github.com/trinadhthatakula/Thor) ⭐ 534 | 🐛 12 | 🌐 Kotlin | 📅 2026-08-29
* [FreezeYou](https://f-droid.org/packages/cf.playhi.freezeyou/) - Improve your device's speed and battery life by freezing crappy software manually or semi-automatically `Apache-2.0` [(Source code)](https://github.com/FreezeYou/FreezeYou) ⭐ 270 | 🐛 34 | 🌐 Kotlin | 📅 2026-08-09
* [Buge App Manager](https://github.com/BugeStudioTeam/Buge-App-Manager) ⭐ 184 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-29 - An app manager focusing on permission management `GPL-3.0`
* [krude](https://github.com/KusStar/krude) ⭐ 163 | 🐛 1 | 🌐 Kotlin | 📅 2025-08-13 - All-in-one app and workflow launcher `MIT`
* [AppControlX](https://github.com/risunCode/AppControl-X) ⭐ 159 | 🐛 5 | 🌐 Kotlin | 📅 2026-03-10 - Freeze, force stop, uninstall apps, change background optimization and more `GPL-3.0`
* [DisabledLauncher](https://github.com/voruti/DisabledLauncher) ⭐ 137 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-26 - Android app that disables unused apps while still allowing convenient access to them `MIT`
* [Insular](https://f-droid.org/packages/com.oasisfeng.island.fdroid/) - Complete FLOSS fork of Island `Apache-2.0` [(Source code)](https://gitlab.com/secure-system/Insular)

### Task manager

* [TaskManager](https://github.com/RohitKushvaha01/TaskManager) ⭐ 616 | 🐛 4 | 🌐 C++ | 📅 2026-08-18 - A Task Manager for Android. Killing processes requires root access. `Apache-2.0`
* [shappky](https://github.com/YasserNull/shappky) ⭐ 547 | 🐛 20 | 🌐 Kotlin | 📅 2026-08-25 ✨ - A simple app to boost performance by stopping background apps. `GPL-3.0`
* [Running Services Monitor](https://play.google.com/store/apps/details?id=me.biplobsd.rsm) - Monitor running services on your Android device `MIT` [(Source code)](https://github.com/biplobsd/running_services_monitor) ⭐ 412 | 🐛 5 | 🌐 Dart | 📅 2026-07-12
* [Pensum](https://github.com/troikoss/Pensum) ⭐ 170 | 🐛 1 | 🌐 Kotlin | 📅 2026-03-30 ✨ - Windows-style Task Manager for Android `GPL-3.0`
* [ReAppzuku](https://github.com/gree1d/ReAppzuku) ⭐ 168 | 🐛 0 | 🌐 Java | 📅 2026-08-04 - Control and manage background applications. Fork of shappky `GPL-3.0`
* [KillMyApps](https://github.com/dedeadend/KillMyApps) ⭐ 72 | 🐛 0 | 🌐 Java | 📅 2026-08-22 - Background process killer to improve battery life and performance via Shizuku or root `GPL-3.0`
* [memhogs](https://github.com/cicerothoma/memhogs-android) ⭐ 47 | 🐛 2 | 🌐 Kotlin | 📅 2026-07-04 - Which apps are eating your phone's memory. Per-app breakdown via Shizuku, helpers grouped under the app that owns them `MIT`

### Terminals

* [Haven](https://f-droid.org/packages/sh.haven.app/) - Terminal, SSH, VNC, RDP, SFTP & cloud storage client for Android `AGPL-3.0` [(Source code)](https://github.com/GlassHaven/Haven) ⭐ 1,129 | 🐛 52 | 🌐 Kotlin | 📅 2026-08-29
* [ReTerminal](https://github.com/RohitKushvaha01/ReTerminal) ⭐ 632 | 🐛 9 | 🌐 C | 📅 2026-08-22 ✨ - Sleek, Material 3-inspired terminal emulator based on Termux's robust TerminalView `MIT`
* [aShell](https://gitlab.com/sunilpaulmathew/ashell) - A local ADB shell for Shizuku-powered Android devices `GPL-3.0`
  * [aShell You](https://github.com/DP-Hridayan/aShellYou) ⭐ 2,246 | 🐛 36 | 🌐 Kotlin | 📅 2026-08-29 - Material You Redesign of aShell app. `GPL-3.0`

> \[!NOTE]
> Using [rish](pages/RISH.md), you can create a local ADB shell with any terminal emulator, such as Termux.

### Vendor-specific

#### Google Pixel

* [Smartspacer](https://github.com/KieronQuinn/Smartspacer) ⭐ 3,489 | 🐛 4 | 🌐 Kotlin | 📅 2026-08-08 - Customizable widget, can upgrade the built-in 'At a glance' widget on Pixel devices using Shizuku `GPL-3.0`
* [pixel-volte-patch](https://github.com/kyujin-cho/pixel-volte-patch/blob/main/README.en.md) ⭐ 2,993 | 🐛 95 | 🌐 Kotlin | 📅 2026-02-07 - Enable VoLTE on Pixel 6 & 7 with LG U+ `GPL-3.0`
* [TurboIMS](https://github.com/Turbo1123/TurboIMS) ⭐ 364 | 🐛 5 | 🌐 Java | 📅 2025-10-17 - Enhanced IMS Configuration Tool for Google Pixel devices `Apache-2.0`
* [hilight-studio](https://github.com/DhananjayBhosale/hilight-studio) ⭐ 258 | 🐛 27 | 🌐 Kotlin | 📅 2026-08-29 - Pixel 11 HiLight LED controller for custom notification and status light effects `MIT`
* [Root-My-Pixel](https://github.com/alex193a/Root-My-Pixel) ⭐ 233 | 🐛 21 | 🌐 Kotlin | 📅 2026-08-29 - Root automation for Pixel devices via CVE-2026-43499 exploit `Proprietary`
* [PixelCarrierSettings](https://github.com/iKirby/PixelCarrierSettings) ⭐ 209 | 🐛 1 | 🌐 Kotlin | 📅 2026-01-02 - Enable VoLTE for carriers in unsupported regions on Pixel devices `GPL-3.0`
* [Always On Display](https://f-droid.org/packages/org.alberto97.aodtoggle/) - Toggle Always on Display from the quick settings panel `MIT` [(Source code)](https://github.com/Alberto97/AlwaysOnDisplayToggle) ⭐ 86 | 🐛 0 | 🌐 Kotlin | 📅 2025-05-16
* [Pixel-IMS-5G](https://github.com/barrylk/Pixel-IMS-5G) ⭐ 30 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-04 - Enable 5G standalone (5G SA) and VoNR on Google Pixel devices `GPL-3.0`

#### Samsung OneUI

* [Root-My-Galaxy](https://github.com/BuSung-dev/Root-My-Galaxy) ⭐ 947 | 🐛 406 | 🌐 Kotlin | 📅 2026-08-24 - KSU installer for supported Samsung Galaxy firmware with CVE-2026-43499 `Apache-2.0`
* [SMTShell](https://github.com/BLuFeNiX/SMTShell) ⭐ 245 | 🐛 5 | 🌐 Java | 📅 2023-06-15 - Privilege escalation exploit [(CVE-2019-16253)](https://nvd.nist.gov/vuln/detail/CVE-2019-16253) to system user access (UID 1000) on non-rooted devices running up to OneUI 5. Uses Shizuku for automation `LGPL-2.1`
* [SBatteryTweaks](https://github.com/pascua28/SBatteryTweaks) ⭐ 149 | 🐛 1 | 🌐 Java | 📅 2026-04-18 - Enable or disable fast charging mode on Samsung devices when the battery temperature reaches a certain point  `Proprietary`
* [ScamsungFonts](https://github.com/KhunHtetzNaing/ScamsungFonts) ⭐ 27 | 🐛 0 | 🌐 Kotlin | 📅 2026-08-03 - Font manager for Samsung Galaxy (OneUI) via System shell or Root `No license`
* [ShutterMute](https://github.com/ajebulon/ShutterMute) ⭐ 20 | 🐛 1 | 🌐 Kotlin | 📅 2026-03-05 - Disable the forced camera shutter sounds on Samsung devices that have their CSC set to certain countries with this restriction `Proprietary`
* [Fonts](https://apt.izzysoft.de/fdroid/index/apk/com.je.fontsmanager.samsung) - One UI 8 rootless font installer `GPL-3.0` [(Source code)](https://codeberg.org/dryerlint/fontsmanager)

#### MIUI

* [Mi-FreeForm](https://github.com/sunshine0523/Mi-FreeForm) ⭐ 783 | 🐛 39 | 🌐 Kotlin | 📅 2024-03-25 - Display most apps in the form of freeform on MIUI `GPL-3.0`
* [FxxkMIUIAd](https://github.com/qhy040404/FxxkMIUIAd) ⭐ 188 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-24 - Turn off MIUI ads with minimal cost `Apache-2.0`
* [FiveGSwitcher](https://play.google.com/store/apps/details?id=com.ysy.switcherfiveg) - 5G shortcut switch for HyperOS/MIUI `GPL-3.0` [(Source code)](https://github.com/ysy950803/FiveGSwitcher) ⭐ 148 | 🐛 4 | 🌐 Kotlin | 📅 2026-07-24
* [MixFlipTool](https://github.com/parallelcc/MixFlipTool) ⭐ 69 | 🐛 3 | 🌐 Kotlin | 📅 2024-10-24 - One-click configuration for Mix Flip's outer screen: Use any apps and restore system apps to default style `GPL-3.0`
* [mtbtool-android-app](https://github.com/h3nnes/mtbtool-android-app) ⭐ 18 | 🐛 1 | 🌐 Kotlin | 📅 2026-07-04 - Perform bandlock and edit EFS NV items on qualcomm-based Xiaomi devices without root  `MIT`
* [NavigationSwitcher](https://github.com/chiyuki0325/NavigationSwitcher) ⭐ 7 | 🐛 0 | 🌐 Kotlin | 📅 2024-08-10 - Enable 3-button navigation in rhythm games for MIUI / HyperOS  `Proprietary`

#### Other

* [ClusterTune](https://github.com/AurelioB/ClusterTune) ⭐ 288 | 🐛 11 | 🌐 Kotlin | 📅 2026-08-23 - Tune CPU cluster frequencies to balance performance and power on AYN handheld devices `GPL-2.0`
* [ThorVolumeLink](https://github.com/pth2000/ThorVolumeLink) ⭐ 24 | 🐛 1 | 🌐 Java | 📅 2026-08-16 - Synchronized volume control for the dual displays of the AYN Thor `MIT`
* [RedTrigger](https://github.com/zampierilucas/RedTrigger) ⭐ 13 | 🐛 0 | 🌐 Kotlin | 📅 2026-06-21 - System-wide shoulder triggers for Nubia Red Magic phones `MIT`
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
> I'm also using an automated crawler that searches for new projects, making use of Shizuku across GitHub and several F-Droid repos. You can view the [current auto-generated crawl report here](https://github.com/timschneeb/app-crawler/blob/master/SUMMARY.md) ⭐ 81 | 🐛 6 | 🌐 Python | 📅 2026-08-29.

***

## Development libraries

### Core

* [Shizuku-API](https://github.com/RikkaApps/Shizuku-API) ⭐ 2,493 | 🐛 315 | 🌐 Java | 📅 2025-05-29 - Developer documentation for Shizuku and Sui, including examples `Apache-2.0`
* [Shizuku-Plugin (Flutter)](https://github.com/santhosh-D-subramani/Shizuku-Plugin) ⭐ 39 | 🐛 2 | 🌐 HTML | 📅 2026-08-17 - Shizuku API bindings for Flutter apps `GPL-3.0`

### Filesystem

* [Ackpine](https://github.com/solrudev/Ackpine) ⭐ 175 | 🐛 3 | 🌐 Kotlin | 📅 2026-08-07 - Android Coroutines-friendly Kotlin-first Package Installer extensions with Shizuku support `Apache-2.0`
* [nextgenfs](https://github.com/rayshift/nextgenfs) ⭐ 37 | 🐛 1 | 🌐 Java | 📅 2024-02-19 - Shizuku compatible android/data access from Xamarin - AIDL library `MIT`
* [LintFile](https://github.com/lumkit/LintFile) ⭐ 31 | 🐛 1 | 🌐 Kotlin | 📅 2024-07-23 - A file operation library with Shizuku, root, and regular filesystem backends `LGPL-2.1`

### System

***

## Miscellaneous content

### Command-line utilities

* [AndroSH](https://github.com/ahmed-alnassif/AndroSH) ⭐ 238 | 🐛 0 | 🌐 Python | 📅 2026-08-27 - No-Root Multi-Distro Linux on Android via Shizuku/ADB - Run Arch, Fedora, Alpine, Debian, Ubuntu, Kali, Void, Manjaro, OpenSUSE & Chimera with full system integration, proot isolation & Termux:X11 GUI `GPL-3.0`

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

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-29._
