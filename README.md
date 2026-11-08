# Debate Timer · 辩论赛计时器

**Debate Timer v3 — standalone, bilingual debate timing for Chinese/English users.**

A single-file debate timer for competitive debates, with configurable formats, multiple timing modes, responsive layouts, and optional sound reminders. The latest standalone release is **v9.3.11**.

**[Download the latest bilingual HTML / 下载最新版双语单页](https://github.com/MoonTzai/debate-timer/releases/latest)**

## Quick start · 快速使用

1. Download `Debate-Timer-v9.3.11.html` from the [v9.3.11 Release](https://github.com/MoonTzai/debate-timer/releases/tag/v9.3.11) and open it in a modern browser.
2. Choose **New Format / 新建赛制** or import a previously saved format. Set rounds, timing modes, sides/teams, and any time pools as needed.
3. Start the match, change the active side when appropriate, and advance through rounds. The on-screen controls and keyboard shortcuts depend on the timing mode.
4. Use **Layout Settings / 布局设置** for responsive layout, preview, theme/background/material options, and **Sound Settings / 声音设置** for reminders and time-up sounds. Use **Apply Settings / 应用设置** to save changes.
5. Export the format or applied configuration if you need a reusable backup. Browser/device support can affect local save, sharing and playback behavior.

中文：下载单页 HTML 后，在浏览器中打开；新建或导入赛制，配置环节与计时模式，开始比赛并按当前模式切换发言方、推进环节。布局、外观、声音均可在设置页面调整；应用设置后保存，需要备份时再导出赛制或配置。

## Features · 主要功能

- **Timing modes / 计时模式**：单方发言、双方交替、质询盘问，以及时间池／共计时赛制支持。
- **Dual display modes / 双显示模式**：原版结构与自由画布双模式；宽屏、窄竖屏与矮横屏布局设置和预览、深浅色主题、背景与磨砂材质调整。
- **Sound reminders / 声音提醒**：可调节的中途提醒时间、归零铃声、被动方有限时警告（自动/自定义/关闭），以及支持自定义音频的声音设置（具体播放效果受设备与浏览器限制）。
- **Configuration / 设置与备份**：赛制导入／导出、布局及声音配置导入／导出、恢复设置和本地持久化功能。
- **Bilingual interface / 双语界面**：简体中文与 English 可在同一单页中切换。

## Which HTML should I use? · 文件说明

| File · 文件 | Language on first use · 首次默认语言 | Purpose · 用途 |
| --- | --- | --- |
| [`辩论赛计时器-Debate-Timer.html`](./%E8%BE%A9%E8%AE%BA%E8%B5%9B%E8%AE%A1%E6%97%B6%E5%99%A8-Debate-Timer.html) | 中文 | Main bilingual source / 正式双语入口 |
| [`Debate-Timer-EN.html`](./Debate-Timer-EN.html) | English | Same functions, English-first entry / 同功能英文默认入口 |
| [`Debate-Timer-v9.3.11.html`](https://github.com/MoonTzai/debate-timer/releases/download/v9.3.11/Debate-Timer-v9.3.11.html) | 中文 | **Recommended downloadable standalone release / 推荐下载单页** |

Both repository HTML files contain the same Timer v3 R22 features (including the native and free-canvas display modes) and can switch languages. A previously saved language preference may override the first-use default. The Release intentionally provides **one complete bilingual HTML**, not duplicate Chinese and English packages.

仓库两个 HTML 仅默认语言不同，均可随时切换中英文；若已有本地语言偏好，以保存的选择为准。Release 仅提供一份完整双语单页，不重复附带英文副本。

## Platforms and related releases · 平台

The standalone HTML is a browser page. The broader **Debate Coach** product also provides web, Windows and Android builds: [Debate Coach Releases](https://github.com/MoonTzai/debate-coach/releases/latest). Platform-specific file import/export, audio playback and persistence behavior should be verified on the device you use.

独立 Timer HTML 面向浏览器使用。若需要包含计时器的 Coach 整合版、Windows 版或 Android APK，可访问上方 Coach Releases。

## Notes · 注意事项

- Export a backup before using full reset; restoring all native defaults may clear locally saved custom background and sound files.
- Use the latest published Release for a stable download. Old HTML files and older Releases may not include recent features.
- This repository README and the English-first HTML are synchronized to **v9.3.11**; release tags and existing published assets are not rewritten.

完整恢复原生默认值可能清除本机保存的自定义背景和铃声，建议先导出备份。请使用正式 Release 下载稳定版本。
