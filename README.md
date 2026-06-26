# 🗂️ file_rename

**Stop renaming files one by one. Let Python do it in one shot.**

A lightweight Python script that automatically detects every file of a given extension in a folder and renames them all sequentially — `photo-1.jpg`, `photo-2.jpg`, `photo-3.jpg`... — in one clean sweep.

---

## ⚡ Why This Exists

Anyone who's ever downloaded a folder full of `IMG_2847.jpg`, `Screenshot (12).jpg`, `WhatsApp Image 2026.jpg` knows the pain of manually renaming files one at a time. This script automates that entire mess into a single function call — no GUI, no third-party tools, just pure Python doing what it does best.

---

## 🚀 How It Works

```python


1. **Scans** the current directory for every file
2. **Filters** files matching the target extension (`.jpg` by default)
3. **Renames** each one sequentially using Python's built-in `os.rename()`

That's it — three steps, zero dependencies.

---

## 🛠️ Usage

```bash
git clone https://github.com/deepanshu-bisht-dev/file_rename.git
cd file_rename
python main.py
```

Drop this script into any folder full of images, run it, and watch the chaos turn into `photo-1.jpg`, `photo-2.jpg`, `photo-3.jpg`...

> 💡 Want a different extension or prefix? Just tweak the `arrange_files()` call at the bottom — change `.jpg` to `.png`, `.txt`, or anything else.

---

## 📦 Tech Stack

- **Language:** Python 3
- **Modules:** `os` (built-in — no external dependencies)

---

## 🔮 Future Improvements

- [ ] Accept extension and prefix as command-line arguments
- [ ] Support renaming files across multiple extensions in one run
- [ ] Add a dry-run mode to preview renames before applying them
- [ ] Recursive renaming for nested folders

---

## 🤝 Connect

Found this useful or have ideas to improve it? Feel free to fork, star ⭐, or connect with me on [LinkedIn](#).

---

*Small script. Real problem. Zero manual labor.* 🐍
