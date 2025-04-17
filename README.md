
---

## 🧹 Anurag's Cleaner – Auto Clear Your Browser Data

A simple, no-nonsense Chrome extension that **automatically clears all your browsing data every 15 seconds**. Whether you're a developer testing in incognito mode, or someone who just values a clean browser, this tool has your back.

---

### ⚙️ Features

- Clears **all browsing data** every 15 seconds (history, cookies, cache, passwords, etc.)
- Toggle the auto-clear feature ON/OFF anytime
- Minimal and clean popup interface
- Lightweight – runs quietly in the background

---

### 🧪 How It Works

The extension sets a repeating alarm every 15 seconds. When the alarm goes off, it checks if "Auto Clear" is enabled, and if so, it nukes all stored browsing data.

You can turn the cleaner ON or OFF from the extension popup.

---

### 📦 Installation

#### Option 1: Load Unpacked (for testing)
1. [Download this repo as ZIP](./anurag_cleaner_extension.zip) and extract it.
2. Open Chrome and go to `chrome://extensions/`
3. Enable **Developer mode** (top right)
4. Click **Load unpacked** and select the extracted folder

#### Option 2: Pack and Publish
Want to share this with the world? Zip it up and [submit it to the Chrome Web Store](https://chrome.google.com/webstore/developer/dashboard).

---

### 📁 Files Overview

```
📁 anurag-cleaner/
├── background.js   # Clears data every 15s using Chrome alarms
├── manifest.json   # Extension config
├── popup.html      # UI for enabling/disabling cleaner
├── popup.js        # Logic for toggle button
└── icon.png        # Extension icon
```

---

### 🚀 Future Ideas

- Custom clear interval
- Select specific types of data to clear
- Notifications/logs of last clean
- Dark mode popup UI

---

### 🙌 Author

**Anurag Srivastav** – [GitHub](https://github.com/DeveloperAnuragsrivastav)  
Built with ❤️ to keep browsers fresh.

---
