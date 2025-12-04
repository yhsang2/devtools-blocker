# 🔒 Developer Tools Blocker (F12 & DevTools Protection Script)

This JavaScript snippet prevents users from opening browser developer tools  
such as **F12**, **Ctrl + Shift + I**, **Ctrl + U**, and various platform-specific shortcuts.  
It also includes a detection mechanism that alerts the user if DevTools is triggered.

> ⚠️ **Important Note:**  
> This script does *not* guarantee perfect protection against advanced users or developers.  
> It is only effective for deterring general users and preventing accidental DevTools access.

---

## 🚀 Features

### ⛔ Blocks Common DevTools Shortcuts
The script prevents multiple keyboard combinations used to open DevTools:

- **F12**
- **Ctrl + Shift + I / J / C**
- **Ctrl + U**
- **Cmd + Alt + I / J / C / U**
- **Cmd + Shift + C**
- Works on **Chrome, Firefox, Edge, Safari**

### 🔍 Detects DevTools Execution
If DevTools is opened through any non-keyboard method  
(right-click → Inspect, menu button, etc.), a warning alert appears:

## 📝 Usage

Include the script directly in your webpage:

```html
<script src="devtools-blocker.js"></script>

