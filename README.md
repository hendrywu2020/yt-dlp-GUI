# 🚀 YouTube 音视频及字幕下载中心

![License](https://img.shields.io/badge/license-MIT-blue.svg)

一款简洁、强大、专为桌面用户设计的 YouTube 媒体下载工具。基于 Python、yt-dlp 核心和 CustomTkinter 现代图形库构建。

![应用截图](https://user-images.githubusercontent.com/YOUR_USERNAME/YOUR_REPO/path/to/your/screenshot.png)
*(请将上方截图替换为您自己程序的截图)*

---

## ✨ 主要功能 (Features)

*   **全能下载**：支持 **MP3** (纯音频)、**MP4** (音视频) 以及 **SRT/VTT** (独立字幕) 三种核心格式。
*   **高清支持**：视频模式下可自由选择 **Best (最佳)**, **720p**, **1080p**, **1440p (2K)**, **2160p (4K)** 等多种分辨率，程序会自动向下兼容。
*   **智能字幕**：可选择将**中英文字幕**自动**嵌入**到下载的 MP4 文件中，方便在播放器中随时开关。
*   **实时反馈**：现代化的图形界面，配备**全程可视的智能进度条**。无论是分析、下载还是合并文件，都能让您对当前状态一目了然。
*   **自动核心更新**：每次启动时，程序都会在后台**自动静默更新 `yt-dlp` 核心**，确保对 YouTube 最新变化的最大兼容性。
*   **批量处理**：支持在输入框中粘贴**多个链接**（每行一个），程序会自动依次处理。

## 🚀 快速开始 (普通用户)

1.  前往本项目的 **[Releases 页面](https://github.com/YOUR_USERNAME/YOUR_REPO/releases)**。
2.  下载最新版本的 `.zip` 压缩包（例如 `Downloader_v3.4.zip`）。
3.  解压后，直接双击运行里面的 `.exe` 程序即可。

*(提示: 您需要先完成 `.exe` 的打包，并创建一个 Release 才能让此链接生效)*

## 🔧 从源码运行 (开发者)

1.  **克隆本仓库**
    ```bash
    git clone https://github.com/YOUR_USERNAME/YOUR_REPO.git
    cd YOUR_REPO
    ```

2.  **安装依赖**
    ```bash
    pip install -r requirements.txt
    ```
    *(您需要手动创建一个 `requirements.txt` 文件，内容如下:)*
    ```
    yt-dlp
    customtkinter
    ```
<img width="1196" height="940" alt="PixPin_2025-09-27_15-29-48" src="https://github.com/user-attachments/assets/9c2ca24a-ce59-448e-bb86-88c8b02dc66a" />

3.  **运行主程序**
    ```bash
    python gui_downloader.py
    ```

## ⚠️ 免责声明 (Disclaimer)

本工具仅供下载**公开、无版权**或您**拥有合法权利**的在线内容。

用户应自行承担因使用本工具下载受版权保护内容而可能引发的一切法律责任。开发者对任何形式的滥用不承担任何责任。

## 📜 许可证 (License)

本项目采用 **MIT 许可证**。详情请见 `LICENSE` 文件。

## 🤝 贡献与反馈 (Contributing & Feedback)

欢迎通过本仓库的 **[Issues](https://github.com/YOUR_USERNAME/YOUR_REPO/issues)** 页面报告 Bug 或提出宝贵的功能建议！
