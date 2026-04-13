# 🧹 Windows Temporary Files Cleaner

A simple and advanced batch script collection to clean unnecessary files on Windows systems and improve performance.

---

## 📌 Overview

This project provides two versions of a Windows cleanup script:

- **Version 1 (Basic)** → Lightweight and simple
- **Version 2 (Advanced)** → Full system cleanup with additional features

These scripts help to:
- Remove temporary files
- Clear system cache
- Delete logs and leftover update files
- Free up disk space

---

## ⚙️ Features

### 🔹 Version 1 (Basic Cleaner)
- Deletes user temporary files
- Deletes Windows temporary files
- Clears Prefetch cache
- Simple and fast execution

### 🔹 Version 2 (Advanced Cleaner)
- ✔ Administrator privilege check
- ✔ Full folder reset (delete & recreate)
- ✔ Windows Update cache cleaning
- ✔ System logs cleanup
- ✔ DISM component cleanup
- ✔ Recycle Bin cleaning
- ✔ Icon cache reset

---

## 🚀 How to Use

1. Download or clone this repository
2. Choose a script version:
   - `Clean Temporary Files V.1.bat`
   - `Clean Temporary Files V.2.bat`
3. Right-click the file
4. Select **"Run as Administrator"**

---

## ⚠️ Important Notes

- Always run as **Administrator**
- Do not run too frequently (recommended: once every 1–2 weeks)
- Some cache will be removed (apps may load slower on first launch)
- Old Windows updates may not be recoverable after cleanup

---

## 📊 Comparison

| Feature | Version 1 | Version 2 |
|--------|----------|----------|
| Temp File Cleaning | ✅ | ✅ |
| Admin Check | ❌ | ✅ |
| Deep Cleaning | ❌ | ✅ |
| Windows Update Cleanup | ❌ | ✅ |
| DISM Optimization | ❌ | ✅ |
| Recycle Bin Cleaning | ❌ | ✅ |

---

## 📁 Project Structure

```
.
├── Clean Temporary Files V.1.bat
├── Clean Temporary Files V.2.bat
├── index.html
└── README.md
```

---

## 🧠 Technical Details

The scripts use Windows Command Prompt commands such as:

- `del` → Delete files
- `rd` → Remove directories
- `mkdir` → Recreate folders
- `DISM` → System component cleanup
- `PowerShell` → Recycle Bin cleanup

---

## ⚠️ Disclaimer

Use this script at your own risk. While generally safe, improper usage may remove useful cached data or system restore points.

---

## 💡 Contribution

Feel free to fork this repository and improve the script.

---

## ⭐ Support

If you find this project useful, consider giving it a **star ⭐ on GitHub**.

