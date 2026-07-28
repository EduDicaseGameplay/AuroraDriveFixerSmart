# 🚀 Aurora Drive Fixer Smart

A smart utility designed to repair Aurora Scan Paths and Title Updates after replacing, cloning, or migrating storage devices.

---

## 📌 About

**Aurora Drive Fixer Smart** was developed to automatically repair common Aurora issues caused by replacing, cloning, or migrating hard drives and USB storage devices.

The script safely updates Aurora's database by correcting internal Scan Path and Title Update references using the selected device's serial number.

Before applying any changes, the script displays a preview of the detected repairs, allowing you to review the modifications in advance. It also detects true duplicate Title Updates already associated with the selected device and safely removes only redundant database entries.

The entire repair process is interactive, protected against unexpected errors, and finishes with a detailed summary of all operations performed.

---

## 🖼️ Preview

### Broken Scan Paths

<p align="center">
  <img src="assets/screenshot1.png" width="800"/>
</p>

### Script Selection

<p align="center">
  <img src="assets/screenshot2.png" width="800"/>
</p>

### Backup Warning

<p align="center">
  <img src="assets/screenshot3.png" width="800"/>
</p>

### Drive Selection (Correct Serial Number)

<p align="center">
  <img src="assets/screenshot4.png" width="800"/>
</p>

### Selected Drive Confirmation

<p align="center">
  <img src="assets/screenshot5.png" width="800"/>
</p>

### Choose to Repair Scan Paths and/or Title Updates

<p align="center">
  <img src="assets/screenshot6.png" width="800"/>
</p>

### Scan Paths Found

<p align="center">
  <img src="assets/screenshot7.png" width="800"/>
</p>

### Title Updates Found

<p align="center">
  <img src="assets/screenshot8.png" width="800"/>
</p>

### Final Results (Summary of Changes)

<p align="center">
  <img src="assets/screenshot9.png" width="800"/>
</p>

### Scan Paths Successfully Repaired

<p align="center">
  <img src="assets/screenshot10.png" width="800"/>
</p>

---

## 🧠 Key Features

* 🛠️ Automatically repairs invalid Aurora database references after replacing, cloning, or migrating storage devices.
* 🔧 Automatic **Scan Path** repair.
* 🔄 Automatic **Title Update (TU)** repair.
* 🧬 Detects and safely removes **true duplicate** Title Updates.
* 🔍 Identifies storage devices by **serial number**.
* 👁️ Preview Scan Path changes before applying them.
* 👁️ Preview Title Update changes before applying them.
* ⚙️ Option to repair **Title Updates only**.
* 📊 Displays a final report including:
  * Successfully repaired Scan Paths.
  * Successfully repaired Title Updates.
  * Removed duplicate Title Updates.
  * Errors (if any).
* 🔁 Optionally restart Aurora after the repair.
* 🛡️ Protected database operations using `pcall`.

---

## 🛡️ Safety

* ✔️ No changes are made without user confirmation.
* ✔️ Confirms the selected storage device before making changes.
* ✔️ Displays detected Scan Paths before repairing them.
* ✔️ Displays detected Title Updates before repairing them.
* ✔️ Uses protected error handling (`pcall`) to prevent unexpected failures.
* ✔️ Verifies data before applying modifications.
* ⚠️ Clearly recommends creating a backup before running the script.

> ⚠️ **Important:**
>
> This script **does not create backups automatically**.
> It is strongly recommended to manually back up Aurora's database before using it.

---

## 📦 When to Use

Use this tool in the following situations:

* 🔁 After **cloning a hard drive or USB storage device**.
* 💾 After **replacing a storage device**.
* 🔄 After **migrating Aurora to another drive**.
* 🎮 When **games no longer appear in Aurora**.
* 🩶 When **game covers appear grayed out**.
* ⚙️ When **Title Updates are no longer applied**.
* 📂 When **Scan Paths still reference the old storage device**.

---

## 📂 Backup (Recommended)

Before running the script, back up one of the following database files:

```text
Data\Databases\content.db
```

or

```text
User\Data\Databases\content.db
```

---

## ⚙️ How It Works

1. Select the correct storage device (identified by its serial number).
2. Choose whether to repair **Scan Paths** together with **Title Updates**, or repair **Title Updates only**.
3. The script scans Aurora's database looking for entries that need to be updated.
4. A preview of the detected changes is displayed before any modification is made.
5. Scan Paths and/or Title Updates are safely repaired.
6. True duplicate Title Updates are automatically detected and safely removed.
7. A detailed summary of all operations is displayed.
8. Optionally restart Aurora to immediately apply the changes.

---

## 🔄 Recommendation

After the script completes, **restart Aurora** to ensure all changes are properly applied.

The script also provides the option to restart Aurora automatically after the repair process finishes.

---

## 🙏 Credits

This project was inspired by **Aurora Cloned Drive Fixer**, created by **EmiMods**.

Aurora Drive Fixer Smart builds upon the same idea while focusing on providing a safer and more user-friendly repair experience for Aurora users.

🔗 Original project:
https://github.com/EmiMods/FixClonedDrive

👤 Original author:
EmiMods

---

## ⚠️ Disclaimer

Use this tool only when necessary.

Although every repair is performed using protected database operations, modifying Aurora's database incorrectly or using the script outside its intended purpose may still lead to unexpected database inconsistencies.

For this reason, creating a backup before running the script is strongly recommended.

---

## 📌 Status

🟢 Stable — Ready for use.

---

## 💬 Contributing

Suggestions, improvements, bug reports, and feedback are always welcome!

If you encounter an issue or have ideas to improve Aurora Drive Fixer Smart, feel free to open an Issue or submit a Pull Request.

Community contributions help make this project better for everyone.