# 🎯 HelpmeFocus

> A browser extension that blocks distracting websites to help you stay focused.

---

## 🦊 Temporary Installation for Firefox (Local Testing)

1. **Download or clone** this GitHub repository.
2. In Firefox, navigate to `about:debugging#/runtime/this-firefox` in your address bar.
3. Click **Load Temporary Add-on…**.
4. Select `firefox-extension/manifest.json`.
5. Firefox will install **Focus Browser Guard**.

### 🔍 Finding the Focus Popup

> **Note:** The Focus popup is **not** inside the general Firefox Extensions menu!

1. Click Firefox's **puzzle-piece Extensions button** near the address bar.
2. Find **Focus Browser Guard** (ignore other extensions like *YouTube Repeat*).
3. **Pin** Focus Browser Guard to your toolbar.
4. Click the **Focus Browser Guard toolbar icon** directly.
5. Click **Start focus session** or **Open local dashboard**.

> 💡 **Troubleshooting:** If the popup is empty or shows only a thin white line, remove the temporary add-on from `about:debugging`, reload `firefox-extension/manifest.json`, and ensure you click the **Focus Browser Guard toolbar icon** rather than opening it from the puzzle-piece dropdown menu.

---

## 🌐 Installation for Google Chrome

1. **Download or clone** this repository.
2. Open Chrome and navigate to:
   ```text
   chrome://extensions
