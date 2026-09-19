# 🛡️ PrivaBoost

### Privacy-Focused Chrome Extension for Blocking Unwanted Tracking

PrivaBoost is a Chrome extension designed to improve browsing privacy by identifying and blocking unwanted tracking requests.

It provides a simple browser interface that allows users to manage privacy settings while using Chrome Storage API to persist their preferences.

---

## 🚀 Features

* 🛡️ Detects unwanted tracking requests
* 🚫 Blocks identified tracking requests
* 📊 Blocks an average of **50+ tracking requests per browsing session**
* ⚙️ Provides a user-friendly popup interface
* 💾 Persists user settings using Chrome Storage API
* 🌐 Works directly inside the Chrome browser

---

## 🧠 How It Works

```text
User Opens Website
        ↓
Browser Request
        ↓
PrivaBoost Detection
        ↓
Check Tracking Request
        ↓
   ┌───────────────┐
   │ Tracking?     │
   └───────┬───────┘
           │
      ┌────┴────┐
      ↓         ↓
     YES        NO
      ↓         ↓
   BLOCK       ALLOW
      ↓
Privacy Protected
```

---

## 🛠️ Tech Stack

| Technology            | Purpose                               |
| --------------------- | ------------------------------------- |
| JavaScript            | Extension logic and tracker detection |
| HTML5                 | Popup interface structure             |
| CSS3                  | Popup interface styling               |
| Chrome Storage API    | Persisting user settings              |
| Chrome Extension APIs | Browser integration                   |

---

## 📂 Project Structure

```text
PrivaBoost/
│
├── manifest.json
├── popup/
│   ├── popup.html
│   ├── popup.css
│   └── popup.js
│
├── scripts/
│   └── ...
│
├── assets/
│   └── ...
│
└── README.md
```

> Update the folder structure above if your actual repository uses different filenames or folders.

---

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/KolipakaRishik/PrivaBoost.git
```

### 2. Open Chrome Extensions

Open:

```text
chrome://extensions/
```

### 3. Enable Developer Mode

Turn on **Developer mode** from the top-right corner.

### 4. Load PrivaBoost

Click:

**Load unpacked**

Then select the cloned PrivaBoost project folder.

### 5. Start Using PrivaBoost

Once installed, open the extension from the Chrome toolbar and configure your privacy settings.

---

## 📊 Project Highlights

* Designed and developed as a browser-based privacy solution
* Implemented tracker detection and blocking functionality
* Built a user-friendly popup interface
* Used Chrome Storage API for persistent settings
* Achieved an average of **50+ blocked tracking requests per browsing session**

---

## 🔮 Future Improvements

Potential improvements include:

* Advanced tracker classification
* Detailed blocking statistics
* Custom block/allow lists
* Domain-level privacy controls
* Improved filtering rules
* Privacy analytics dashboard

---

## 👨‍💻 Author

**Rishik Kolipaka**

Computer Science Graduate | Software Engineer

* 💼 LinkedIn: https://www.linkedin.com/in/kolipaka-rishik
* 🐙 GitHub: https://github.com/KolipakaRishik

---

⭐ If you find this project interesting, consider giving the repository a star.
