# 🦊 The Fox Firefox Theme 

The whole idea in the beginning was to make a toolbar with an image that I liked,  
and that would go well with the homepage of the browser.  
Now it's a whole theme on it! 🎨

![Preview](Screenshots/screenshot1.jpg)

---

## 📑
- [🔧 Installation Instructions](#-installation-instructions)
  - [1. Enable UserChrome and UserContent support](#1-enable-userchrome-and-usercontent-support)
  - [2. Locate your Firefox profile folder](#2-locate-your-firefox-profile-folder)
  - [3. Create a chrome folder (if it doesn’t exist)](#3-create-a-chrome-folder-if-it-doesnt-exist)
  - [4. Restart Firefox](#4-restart-firefox)
- [📸 Screenshots](#-screenshots)
- [💡 Notes](#-notes)

---


## 🔧 Installation

This theme uses **Firefox's `userChrome.css` and `userContent.css`** customization system.  
Follow the steps below to apply it:

### 1. Enable UserChrome and UserContent
1. Open Firefox and type: `about:config` on the address bar.
2. Accept the warning if prompted.
3. Search for:
   - `toolkit.legacyUserProfileCustomizations.stylesheets`
4. Set it to **`true`**.

### 2. Locate your Firefox profile folder
1. In Firefox, go to: `about:profiles`
2. Look for the desired user section **Root Dictory**.
3. Click **Open Folder**.

### 3. Create a `chrome` folder (if it doesn’t exist)
Inside your profile folder:
- Create a new folder named `chrome`
- [Download the theme as a ZIP](https://github.com/Shr11mp/The-Fox-Firefox-theme/archive/refs/heads/main.zip)  
- Extract the ZIP and place **all its contents** inside the `chrome` folder, including **`userChrome.css`** and **`userContent.css`**.


Your structure should look like this:

```
/your-firefox-profile/
└── chrome/
  ├── userChrome.css
  ├── userContent.css
  ├── theme-images/
  └── other-theme-files...
```

### 4. Restart Firefox
Close and reopen Firefox.
Your custom theme should now be applied! 🚀

---

## 📸 Screenshots
Here are some Screenshots from the **Screenshots/** folder.
![Firefox theme](Screenshots/screenshot1.jpg)
![Articfox theme](Screenshots/screenshot2.jpg)

---

## 💡 Notes
- If the theme doesn’t load, double-check that the preference  
  `toolkit.legacyUserProfileCustomizations.stylesheets` is still set to `true`.
- Changes to CSS files require restarting Firefox to take effect.
- Make sure you’re using a **compatible Firefox version** (some UI elements may differ between releases).
- Check your **operating system** (Windows, macOS, Linux), since some styles may behave slightly differently.

---
✨ Enjoy your customized browsing experience!