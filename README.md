# HelpmeFocus

Extension that blocks websites to help you focus.

## Temporary installation for testing FIREFOX extension locally

1. Download or clone the GitHub repository.
2. In Firefox, open `about:debugging#/runtime/this-firefox`.
3. Click **Load Temporary Add-on…**.
4. Select `firefox-extension/manifest.json`.
5. Firefox adds Focus Browser Guard.

### Finding the Focus popup

The Focus popup is not the general Firefox Extensions menu:

* Click Firefox's puzzle-piece **Extensions** button near the address bar.
* Find **Focus Browser Guard**. Ignore other extensions such as YouTube Repeat.
* Pin **Focus Browser Guard** to the toolbar.
* Click the **Focus Browser Guard** toolbar icon itself.
* Click **Start focus session** or **Open local dashboard**.

If the popup is empty or shows only a thin white line, remove the temporary add-on from `about:debugging`, load `firefox-extension/manifest.json` again, and click the Focus Browser Guard icon—not the puzzle-piece menu.

## Install in Chrome (Warning: I have not tested this. let me know if it doesn't work...)

1. Download or clone this repository.
2. Open: `chrome://extensions`
3. Turn on **Developer mode**.
4. Click **Load unpacked**.
5. Select the `chrome-extension/` folder.
6. Pin **Focus Browser Guard** from Chrome's Extensions menu.
7. Click the **Focus Browser Guard** toolbar icon.
8. Click **Open local dashboard**.

## Use the extension

The local dashboard lets you:

* Start normal sessions that can end early.
* Start hard-block sessions that stay locked until the timer expires.
* Choose 20, 25, 45, or 60-minute sessions.
* Quickly add common distracting sites.
* Choose Full site or Feed only.
* Switch an existing site between Full site and Feed only without removing it.
* Enable, disable, and remove sites.
