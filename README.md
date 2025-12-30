# EroGrabber 📥

EroGrabber is a lightweight Ruby tool designed to make downloading video content from EroThots simple and fast. Unlike traditional methods that require digging through browser developer tools, this script automatically "scrapes" the page to find the high-quality video source for you.

---

### 📝 Author's Note
> **Apologies to the community—this is my first time using GitHub!** I created this downloader because I wanted a simpler way to save videos without dealing with the Network tab every time, and I wanted to share it with everyone. I hope you find it useful!

---

## ✨ Features
- **No Developer Tools Required**: You don't need to open the "Network" tab or search for `.mp4` links manually.
- **One-Click Logic**: Just copy the URL from your browser address bar and run the script.
- **High Quality**: Downloads the original stream directly from the CDN using `ffmpeg`.
- **Clipboard Support**: Automatically detects if you have a link copied to your clipboard.

## 🛠 Prerequisites
To use this script, you need to have **Ruby** and **FFmpeg** installed on your system.

### For Linux (Arch/Artix):
```bash
sudo pacman -S ruby ffmpeg xclip
