# CtrlTube 🎯

> Turn YouTube into your personal learning assistant. Block distractions. Focus better.

CtrlTube is a Chrome extension that helps learners stay focused on educational content by automatically filtering out non-educational YouTube videos. No more rabbit holes — just pure productivity.

![CtrlTube Banner](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/003/465/627/datas/gallery.jpg) <!-- Add your image path -->

---

## 🚀 Features

- ✅ Automatically hides non-educational YouTube content  
- 🎯 Designed to identify distractions like Shorts, music videos, and entertainment  
- 🔍 Uses keyword analysis and heuristics to detect content type  
- 🧠 Perfect for students and lifelong learners  
- 🌐 Lightweight and privacy-respecting Chrome extension  

---

## 📸 Preview

> _Screenshots of the extension in action_

| Before | After | UI |
|--------|-------|-------|
| ![Before](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/003/466/015/datas/gallery.jpg) | ![After](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/003/466/016/datas/gallery.jpg) | ![UI](https://d112y698adiu2z.cloudfront.net/photos/production/software_photos/003/466/013/datas/gallery.jpg) |

---

## 🧩 Installation

1. Clone or download this repository:
   ```bash
   git clone https://github.com/MrVoracious/CtrlTube.git
   ```
2. Open [chrome://extensions](chrome://extensions) in your browser.  
3. Enable **Developer Mode** (top right).  
4. Click **Load unpacked** and select the `CtrlTube` folder.  

---

## 🛠️ Development

This project is built using:

- JavaScript (ES6)
- Chrome Extensions APIs
- Manifest v3

> **Key files:**
- `service_worker.js` – background service worker
- `content.js` – logic injected into YouTube pages
- `popup.html` – minimal UI interface (if needed)

---

## 🔍 How It Works

CtrlTube evaluates YouTube thumbnails, titles, and metadata using predefined rules and keyword filters. Videos deemed distracting are automatically hidden or removed from the page.

> **Planned:** AI-based detection using Gemini API (coming soon).

---

## 📦 Folder Structure

```
CtrlTube/
│
├── extension/           # main folder
├──├── popup.html           # Extension popup
├──├── content.js           # Page logic
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

## License

This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license.

You are free to:

- Share — copy and redistribute the material in any medium or format  
- Adapt — remix, transform, and build upon the material  

**Under the following terms:**

- **Attribution** — You must give appropriate credit.
- **NonCommercial** — You may not use the material for commercial purposes.
- **No additional restrictions** — You may not apply legal terms or technological measures that legally restrict others from doing anything the license permits.

🔗 [Read the full license](https://creativecommons.org/licenses/by-nc/4.0/)

---

## 🙌 Acknowledgments

Created with passion at **KT HACK 2025** by  
[MrVoracious](https://github.com/MrVoracious), [fuel000cynical](https://github.com/fuel000cynical), and [insomniac-robot](https://github.com/Insomniac-Robot).
