# 🐕 DogSC·Pro v44.7.0

> 录屏与轻量编辑工具 · Screen Recording & Lightweight Editor
>
> 基于开源项目的 Windows 二创版 · Windows derivative based on open-source projects

---

## 📌 关于本项目 / About This Project

**DogSC·Pro** 是基于开源录屏工具 DogSC 的 Windows 二创版本，在原版基础上进行了适配与打包，让 Windows 用户也能体验这款简洁高效的录屏编辑器。

**DogSC·Pro** is a Windows derivative of the open-source screen recording tool DogSC, adapted and packaged to bring this elegant screen editor to Windows users.

### 溯源 / Attribution

| 项目 Project | 作者 Author | 仓库 Repository |
|-------------|------------|----------------|
| 原创 DogSC | 神烦老狗 [@laogou717](https://github.com/laogou717) | [github.com/laogou717/dogsc](https://github.com/laogou717/dogsc) (macOS) |
| Windows 适配 | [xiaoying8666](https://github.com/xiaoying8666) | [github.com/xiaoying8666/dogscwindows](https://github.com/xiaoying8666/dogscwindows) |
| **DogSC·Pro**（本版） | — | — |

> ⚠️ 本版本不是原作者的官方发布。遇到问题请提交到本仓库，不要提到上游仓库。
>
> This release is not an official build by the original author. Please file issues in this repo, not upstream.

---

## 📦 下载 / Downloads

| 文件 File | 说明 Description | 大小 Size | SHA256 |
|-----------|------------------|-----------|--------|
| `DogSC-Pro-win32-x64-44.7.0.zip` | 便携版（免安装）Portable | 174.41 MB | `6599584920bb3ef4dc752d7557423a5cf3cd1638d2efd3409a79b110c6297843` |

> 完整校验和见 [`sha256sums.txt`](./sha256sums.txt) · Full checksums in [`sha256sums.txt`](./sha256sums.txt)

---

## 🖥️ 系统要求 / System Requirements

- **操作系统 / OS:** Windows 10 (2004+) / Windows 11（64-bit）
- **架构 / Architecture:** x64 (Intel / AMD)
- **磁盘空间 / Disk Space:** ~300 MB
- **运行环境 / Runtime:** 无需额外安装 · No additional installation required

---

## 🚀 使用方法 / How to Use

### 便携版（免安装） / Portable

1. 下载并解压 `DogSC-Pro-win32-x64-44.7.0.zip`
2. 进入解压后的文件夹
3. 双击 `DogSC.exe` 直接运行

```powershell
# PowerShell 快速启动
Expand-Archive DogSC-Pro-win32-x64-44.7.0.zip -DestinationPath DogSC-Pro
.\DogSC-Pro\DogSC.exe
```

---

## ✅ 校验完整性 / Verify Checksum

### PowerShell（推荐）

```powershell
Get-FileHash DogSC-Pro-win32-x64-44.7.0.zip -Algorithm SHA256
```

### Git Bash / WSL

```bash
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

- 🎉 DogSC·Pro 首次发布 / Initial release of DogSC·Pro
- 基于 DogSC v44.7.0 Windows 适配版打包 / Packaged from DogSC v44.7.0 Windows port

---

## 📄 许可 / License

本软件基于 MIT License 开源项目打包。

- 原版 DogSC：Copyright (c) 2026 神烦老狗，[MIT License](https://github.com/laogou717/dogsc/blob/main/LICENSE)
- Windows 适配：[MIT License](https://github.com/xiaoying8666/dogscwindows/blob/main/LICENSE)
- 随附字体采用其自身许可 · Bundled fonts have their own licenses

---

## 🙏 致谢 / Credits

- [神烦老狗 @laogou717](https://github.com/laogou717) — 原创作者 Original Author
- [xiaoying8666/dogscwindows](https://github.com/xiaoying8666/dogscwindows) — Windows 适配 Windows Port
- 所有开源贡献者 All open-source contributors
