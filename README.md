# UnityPinCodeInputUI

A clean and customizable 6-digit PIN code input UI system for Unity using TextMeshPro.  
Perfect for OTP screens, PIN logins, numeric codes, and more.

![preview](https://your-preview-image-url-if-any)

## ✨ Features

- 🔢 6-digit PIN layout using `TMP_InputField`s
- 🎯 Auto focus to next field on input
- ⬅️ Backspace deletes and moves to previous field (hold support)
- 🖼️ Highlight active field using custom sprites
- 🚫 No blinking caret for cleaner UI
- 📱 Mobile friendly

---

## 📦 Installation

### Option 1: Unity Package

Download or clone the repo and drag the `PINInputUI` folder into your Unity `Assets/` folder.

### Option 2: Git URL (UPM)
Coming soon...

---

## 🧰 Usage

1. Add the `PINInputFields.cs` script to a GameObject.
2. Create 6 `TMP_InputField` objects (1 character each).
3. Assign them in the `inputFields[]` array.
4. Add 6 `Image` objects as borders and assign to `boxBorders[]`.
5. Assign your `selected` and `unselected` sprites.

---

## 🔧 Customization

- Change the number of digits (default = 6).
- Update styles via Unity Inspector.
- Modify `UpdateSprites()` to change highlight behavior.

---

## 📜 License

MIT – Free to use in personal and commercial projects.

---

## 📸 Screenshot

Coming soon...
