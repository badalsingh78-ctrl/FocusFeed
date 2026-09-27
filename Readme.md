# FocusFeed 🎯

> Turn YouTube into your personal learning assistant. Block distractions. Focus better.

FocusFeed is a Chrome extension that helps learners stay focused on educational content by automatically filtering out non-educational YouTube videos. No more rabbit holes — just pure productivity.
 ![CtrlTube Banner](Extension/icon.jpeg)

---

## 🚀 Features

- ✅ Automatically hides non-educational YouTube content  
- 🎯 Designed to identify distractions like Shorts, music videos, and entertainment  
- 🔍 Uses keyword analysis and heuristics to detect content type  
- 🧠 Perfect for students and lifelong learners  
- 🌐 Lightweight and privacy-respecting Chrome extension  


## 🧩 Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/ajaybaghel05/FocusFeed.git
   ```
2. Open [chrome://extensions](chrome://extensions) in your browser.  
3. Enable **Developer Mode** (top right).  
4. Click **Load unpacked** and select the `FocusFeed` folder.  

---

## 🛠️ Development

This project is built using:

- JavaScript (ES6)
- Chrome Extensions APIs
- Manifest v3

> **Key files:**
- `service_worker.js` – background service worker
- `workit.js` – logic injected into YouTube pages
- `index.html` – minimal UI interface (if needed)

---

## 🔍 How It Works

FocusFeed evaluates YouTube thumbnails, titles, and metadata using predefined rules and keyword filters. Videos deemed distracting are automatically hidden or removed from the page.

> **Planned:** AI-based detection using Gemini API (coming soon).

---

## 📦 Folder Structure

```
FocusFeed/
│
├── extension/           # main folder
├──├── index.html           # Extension popup
├──├── workit.js           # Page logic
├──├── service_worker.js    # Background service worker
├──├── manifest.json        # Extension config
└──├── styles.css           # Optional styling
```
---

## 🤝 Contributing

Pull requests are welcome! To contribute:

1. Fork the repo  
2. Create your feature branch:  
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Commit changes:  
   ```bash
   git commit -m 'Add your feature'
   ```
4. Push to the branch:  
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request  

---

## 🙌 Acknowledgments

Created with passion by [Ajay Baghel](https://github.com/ajaybaghel05).
