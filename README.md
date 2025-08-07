# 🎯 YouTube Link Extractor

A lightweight and easy-to-use web tool that allows you to extract direct YouTube video links from embedded iframe sources — especially useful when videos are embedded using `youtube-nocookie.com`, like in course websites. This helps uncover the original unlisted YouTube video URL for personal or debugging purposes.

![Preview](https://i.postimg.cc/SKTT7xN4/Screenshot-2025-08-07-144548.png)

---

## 🚀 Features

- ✅ Extract original YouTube video URL from iframe embed code
- ✅ Works with `youtube-nocookie.com` and other embed variations
- ✅ Clean, responsive HTML/CSS design
- ✅ Copy to clipboard button
- ✅ Built-in usage tutorial
- ✅ No installation required – 100% client-side

---

## 🧠 How It Works

This tool reads the **YouTube Embed URL** found in browser dev tools and parses the video ID from it. It then converts it into a standard `https://www.youtube.com/watch?v=VIDEO_ID` link.

---

## 🔎 Use Case

Many course platforms embed **unlisted** YouTube videos using iframe players. You can use this tool to extract those links for:

- Bookmarking lectures
- Watching on the official YouTube player
- Debugging embedded video issues
- Educational purposes

> ❗ **Note:** This tool does **not** bypass YouTube restrictions or provide unauthorized downloads. Use responsibly.

---

## 🧰 How to Use

1. Open the browser video player on a course website.
2. Right-click the page and choose **Inspect** or press `Ctrl+Shift+I`.
3. Go to the **Network** tab and filter by **JS**.
4. Look for a file like `www-embed-player.js` and click it.
5. In the **Headers** tab, scroll to find the **Referer** URL.
6. Copy that full URL and paste it into this tool’s textarea.
7. Click **"Extract Link"** – and done!

---

## 🖼️ UI Overview

- 🔵 Blue-themed modern interface  
- 📋 Text area for pasting the URL  
- 🎯 Output section shows the YouTube link  
- 📘 Integrated step-by-step tutorial  

---

## 📂 Folder Structure

```
📁 yt-unlisted-link-generator/
├── index.html       # Main project file
├── LICENSE          # MIT License
└── README.md        # You're reading this
```

---

## 📄 License

This project is licensed under the **MIT License** – feel free to use, modify, and share it for personal or commercial use with proper credit.

```
MIT License © 2025 MD AL AMIN
```

---

## 👤 Author

Developed with ❤️ by **MD AL AMIN | CMAA**  
📫 Connect: [Coming soon]

---

## 🏁 Final Note

This is a utility tool intended for **educational** or **developer debugging** purposes. Always respect content creators’ rights and YouTube’s terms of service.

---
