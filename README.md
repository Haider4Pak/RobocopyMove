# Robocopy Move Tool (Batch Script)

A simple Windows batch script to **safely move folders** using Robocopy.  
This script preserves the folder name, shows live progress, and creates logs.
Good script for moving folders and files from a hard disk with bad sectors or freezing issues
---

## ✅ Features
- Moves an entire folder to another location
- Preserves folder name in destination
- Skips bad/unreadable files (does not freeze like Explorer)
- Shows progress and ETA while moving
- Creates a log file (`robocopy_log.txt`) in the destination

---

## 🔧 Usage
1. Download or copy the `RobocopyMove.bat` file.
2. Double-click to run.
3. Enter the **full source folder path** (example: `D:\Software\Fonts`).
4. Enter the **destination folder path** (example: `C:\Users\Haider\Downloads\Work Folder`).
5. The script will:
   - Create `Fonts` inside `Work Folder`
   - Move all files/folders inside `Fonts`
   - Show live progress
   - Save a log file in the destination folder

---

## 📌 Example
Source: D:\Software\Fonts
Destination: C:\Users\Haider\Downloads\Work Folder
Result: C:\Users\Haider\Downloads\Work Folder\Fonts\


---

## ⚠️ Notes
- Files that cannot be read (bad sectors, corruption) will be skipped and logged.
- The script **moves files** (they are deleted from the source after successful copy).
- If you want to **keep originals**, replace `/MOVE` with `/COPYALL`.

---

## 🖊️ Author
Made by HAIDER ART
Free to use and share. Contributions welcome!
