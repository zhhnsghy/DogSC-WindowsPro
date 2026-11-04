# DogSC-WindowsPro
DogSC 是神烦老狗原创的录屏与编辑工具，以 MIT License 开源
[RELEASE.md](https://github.com/user-attachments/files/34359558/RELEASE.md)
# DogSC v44.7.0

> 🐕 **录屏与轻量编辑工具 · Screen Recording & Lightweight Editor**
>
> 基于 [laogou717/dogsc](https://github.com/laogou717/dogsc)（神烦老狗）的 Windows 适配版 · Windows port of the original macOS app by 神烦老狗

---

## 📌 关于本项目 / About This Project

**原创作者 / Original Author:** 神烦老狗 ([@laogou717](https://github.com/laogou717))  
**原版仓库 / Upstream:** [github.com/laogou717/dogsc](https://github.com/laogou717/dogsc)（macOS）  
**Windows 适配 / Windows Port:** [xiaoying8666/dogscwindows](https://github.com/xiaoying8666/dogscwindows)

DogSC 是神烦老狗原创的录屏与编辑工具，以 MIT License 开源。本版本基于 Windows 适配仓库打包，将其编译为可直接安装的 `.exe` 和便携版 `.zip`。

DogSC is a screen recording and editing tool created by 神烦老狗, released under the MIT License. This release packages the Windows port into an installable `.exe` and a portable `.zip`.

---

## 📦 下载 / Downloads

| 文件 File | 说明 Description | 大小 Size | SHA256 |
|-----------|------------------|-----------|--------|
| `DogSC-Setup-44.7.0.exe` | Windows 安装程序（推荐）Installer (Recommended) | 126.72 MB | `73c4fafa2294fadb458023b28f1735d2bd77c4a20a9d5969a5731a2d7facc53c` |
| `DogSC-win32-x64-44.7.0.zip` | 便携版（免安装）Portable (No install) | 175.83 MB | `ed1636aee6aa8cdd23760b5929a9d11bca1e9e9cda4dd155844934d38f6f3f4a` |

> 完整校验和见 `sha256sums.txt` · Full checksums in `sha256sums.txt`

---

## 🖥️ 系统要求 / System Requirements

- **操作系统 / OS:** Windows 10 2004+ / Windows 11（64-bit）
- **架构 / Architecture:** x64 (Intel / AMD)
- **磁盘空间 / Disk Space:** ~300 MB

---

## 🚀 安装 / Installation

### 方式一：安装程序（推荐） / Installer (Recommended)

双击 `DogSC-Setup-44.7.0.exe`，按向导完成安装。
Double-click `DogSC-Setup-44.7.0.exe` and follow the wizard.

### 方式二：便携版 / Portable

解压 `DogSC-win32-x64-44.7.0.zip`，双击 `DogSC.exe` 直接运行。
Extract `DogSC-win32-x64-44.7.0.zip`, then double-click `DogSC.exe` to run.

---

## ✅ 校验完整性 / Verify Checksum

```powershell
# PowerShell
Get-FileHash DogSC-Setup-44.7.0.exe -Algorithm SHA256
Get-FileHash DogSC-win32-x64-44.7.0.zip -Algorithm SHA256
```

```bash
# Git Bash / WSL
sha256sum -c sha256sums.txt
```

---

## ✨ 功能特性 / Features

| 功能 Feature | 描述 Description |
|-------------|-----------------|
| 🎥 **录制 Recording** | 整块屏幕、单个窗口、自选区域；摄像头、麦克风、系统声音各自成轨 · Full screen, window, custom region; camera, mic, system audio on separate tracks |
| 🎬 **运镜 Camera Movement** | 按点击自动缩放、镜头跟随指针；手动添加缩放，可调倍率、焦点、缓动 · Auto-zoom on click, follow pointer; manual zoom with rate, focus, easing |
| ✂️ **剪辑 Editing** | 时间线分割、拖边裁短、变速，缩略图预览，支持撤销/重做 · Split, trim, speed change on timeline; undo/redo with thumbnails |
| 🖱️ **光标与摄像头 Cursor & Camera** | 光标重新合成（大小、平滑、静止隐藏、点击反馈）；摄像头形状/大小/位置/镜像 · Re-synthesized cursor (size, smooth, hide-when-idle, click feedback); camera shape/size/position/flip |
| 🎨 **画面设计 Canvas Design** | 比例、留白、圆角、描边、阴影；背景支持图案、壁纸、自选图、纯色 · Aspect ratio, padding, corner radius, stroke, shadow; patterned/wallpaper/custom/solid background |
| 📤 **导出 Export** | MP4 + M4A，原始分辨率/1080p/1440p/4K，30/60 FPS，进度可取消 · MP4 + M4A, original/1080p/1440p/4K, 30/60 FPS, cancellable progress |

---

## 📝 更新日志 / Changelog

### v44.7.0

- 🎉 首次打包发布 Windows 安装版与便携版
- 🎉 Initial packaged release with Windows installer & portable zip

---

## 📄 许可 / License

- 原版 DogSC：Copyright (c) 2026 神烦老狗，[MIT License](https://github.com/laogou717/dogsc/blob/main/LICENSE)
- Windows 适配：[MIT License](https://github.com/xiaoying8666/dogscwindows/blob/main/LICENSE)
- 随附字体采用其自身许可 · Bundled fonts have their own licenses

---

## 🙏 致谢 / Credits

- [神烦老狗 @laogou717](https://github.com/laogou717) — 原创作者 Original Author
- [xiaoying8666/dogscwindows](https://github.com/xiaoying8666/dogscwindows) — Windows 适配 Windows Port
- 所有开源贡献者 All open-source contributors

---

> ⚠️ **注意 / Note:** 本 Windows 适配版不是原作者的官方发布，使用遇到的问题请提交到 [xiaoying8666/dogscwindows](https://github.com/xiaoying8666/dogscwindows) 的 Issues，不要提到原仓库。
>
> This Windows port is not an official release by the original author. Please file issues in the Windows port repo, not the upstream.
