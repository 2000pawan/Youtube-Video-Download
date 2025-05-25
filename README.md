# 🎥 YouTube Video Downloader

A simple and user-friendly desktop GUI application built with Python Tkinter and yt-dlp to download high-quality video and audio from YouTube links.

---

## 🚀 Features

- 🎯 Download best-quality video and audio from any valid YouTube video URL.
- 📁 Browse and select your desired download directory.
- ✅ Easy-to-use interface with helpful message alerts.
- 🔁 Option to clear/reset input fields.
- ❌ Close/Exit the app with a click.
- 🖼️ Clean and modern GUI using Tkinter.

---

## 📂 Options to Use

### ✅ Option 1: Use the Standalone Executable (`Video_Download.exe`)
- No Python installation needed! Just download and run the executable file.
- Double-click to launch the YouTube Video Downloader.
- Paste the YouTube link, choose a folder, and click **Download**.
- ⚠️ Make sure FFmpeg is present in your system or bundled with the EXE.  
  If needed, extract FFmpeg and update the `ffmpeg_path` in the script before compiling.

---

### 🐍 Option 2: Run the Script Locally (For Developers)

#### Requirements:
- Python 3.x
- yt-dlp
- ffmpeg

#### 🔧 Installation:

1. Clone the repository:
    ```bash
    git clone https://github.com/2000pawan/Youtube-Video-Downloader.git
    cd Youtube-Video-Downloader
    ```
2. Install dependencies:
    ```bash
    pip install yt-dlp
    ```
3. Download FFmpeg:  
   Download the latest FFmpeg static build from:  
   👉 https://www.gyan.dev/ffmpeg/builds/  
   Extract and copy the path to the `ffmpeg/bin` folder (e.g., `D:/Software/ffmpeg/bin`), then update it in the script under `ffmpeg_path`.

---

## 🧠 Usage

Run the script:

```bash
python youtube_video_downloader.py
