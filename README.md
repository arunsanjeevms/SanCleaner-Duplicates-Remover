# 🧹 SanCleaner - Duplicate File Finder & Cleaner

**A powerful, modern Windows application to find and clean duplicate files—built by Arun Sanjeev.**

![Version](https://img.shields.io/badge/Version-1.0.0-green)
![Platform](https://img.shields.io/badge/Platform-Windows-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)

---

## ✨ Features

### 🔍 Smart File Detection
- **Hash-Based Scanning** (CRC32 + MD5)
- Supports **images, videos, documents**, and more
- **File size filtering** (set min/max size)
- Fast, multi-threaded scanning

### 🎨 Clean & Modern UI
- Built using **Tkinter**
- Live **progress updates** and status tracking
- Integrated **log viewer**
- **Responsive layout** (resizes well on different screens)

### 🛡️ Safe File Handling
- Preview before deleting
- Choose to **move or delete** duplicates
- Backup support (move to separate folder)
- Graceful handling of inaccessible/missing files

### ⚙️ Customization Options
- Select file types to include/exclude
- Set scanning behavior and performance options
- Light/Dark theme support

---

## 🚀 Getting Started

### ✅ Download & Run
1. **Download** `SanCleaner.exe` from the [Releases](https://github.com/arunsanjeevms/SanCleaner-Duplicates-Remover/releases)
2. **No installation needed** – just double-click and run
3. **Select** a folder to scan
4. **Review** results and clean duplicates

### 🖥️ System Requirements
- **OS**: Windows 10/11 (64-bit)
- **RAM**: 4GB minimum
- **Python not required** – runs as standalone `.exe`

---

## 📖 How It Works

### 1. Select Folder
- Browse to choose a folder (scans subfolders too)
- System folders are skipped for safety

### 2. Configure Filters
- Select file types (images, videos, docs, etc.)
- Set file size limits

### 3. Start Scan
- Real-time scanning with progress updates

### 4. Review Results
- Duplicates grouped for review
- Total space that can be saved

### 5. Clean Files
- **Move** duplicates to another folder
- Or **Delete** them permanently

---

## 🎯 Use Cases

- 🖼️ Remove duplicate images from photo collections  
- 📁 Clean up document clutter  
- 🎬 Organize your movie or video folders  
- 💾 Free up disk space and reduce storage bloat  

---

## 🛠️ Built With

- **Python 3.13**
- **Tkinter** (GUI)
- **PyInstaller** (EXE packaging)
- **CRC32 & MD5** (file hashing)
- **Multithreading** for smooth UI

---

## 🧪 Development Setup

```bash
# Clone this repository
git clone https://github.com/arunsanjeevms/SanCleaner-Duplicates-Remover.git
cd SanCleaner-Duplicates-Remover

# Install dependencies
pip install -r requirements.txt

# Run it
python main.py
