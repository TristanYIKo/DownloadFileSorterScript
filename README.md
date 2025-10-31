# 🗂️ AutoSort Downloads (Python Script)

A lightweight **Python automation script** that organizes your **Downloads folder** into neatly structured subfolders — automatically.  
It uses **`os`** and **`shutil`** to detect file types and move them into categorized directories (e.g., PDFs, Images, Videos, ZIPs, etc.).

---

## ✨ Overview

Tired of a messy Downloads folder?  
This script automatically **sorts files based on their extensions** and moves them into categorized folders like `/Documents`, `/Images`, `/Videos`, `/Software`, and more.  

You can easily customize the file categories or directory paths to fit your workflow.

---

## 🔧 Features

- ⚙️ **Auto-sorting by file type** — Detects file extensions and organizes them into predefined folders.  
- 📁 **Dynamic folder creation** — Automatically creates missing category folders on the fly.  
- 🔄 **Reusable & customizable** — Modify file mappings or add new types easily.  
- 🧠 **Lightweight logic** — Runs entirely with built-in Python libraries (`os`, `shutil`).  
- 🖥️ **Cross-platform** — Works on Windows, macOS, and Linux.

---

## 💡 Notes

- The script **moves** files (not copies them).  
- You can run it manually or schedule it via **Task Scheduler** (Windows) or **cron** (Mac/Linux).  
- Add logging if you want to track file moves.  
- Safe to re-run anytime — existing files in the destination won’t be overwritten.

