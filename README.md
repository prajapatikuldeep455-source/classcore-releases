<div align="center">

# 🎓 ClassCore — Next-Gen Tuition & Institute Management

**The complete, high-performance offline-first management suite and mobile companion for modern coaching centers, academies, and private tutors.**

[![Version](https://img.shields.io/badge/Version-3.5.4-2563EB?style=for-the-badge&logo=electron)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20(x64)-0078D6?style=for-the-badge&logo=windows)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.4.exe)
[![Android Companion](https://img.shields.io/badge/Android-Companion%20App-3DDC84?style=for-the-badge&logo=android)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)
[![Cloud Sync](https://img.shields.io/badge/Cloud%20Sync-Firebase%20Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Offline Capable](https://img.shields.io/badge/Architecture-100%25%20Offline%20First-10B981?style=for-the-badge)](https://github.com/prajapatikuldeep455-source/classcore-releases)

---

### 📥 [Download ClassCore Desktop v3.5.4 (Windows x64)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.4.exe) &nbsp;|&nbsp; 📲 [Download Mobile Companion (.apk)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)

</div>

---

## 🌟 Why ClassCore?

Managing an educational institute or tuition center shouldn't require juggling complicated spreadsheets, multiple messaging apps, separate billing tools, and manual handwriting on paper cards.

**ClassCore** unifies every operational aspect into a sleek, lightning-fast desktop command center paired with an instant Android mobile app. Built with an **offline-first philosophy**, ClassCore guarantees that power outages, weak internet, or server downtimes never interrupt your admissions, fee collections, or biometric attendance.

---

## 🚀 Highlights in Latest v3.5.4 Release

### 🖨️ 1. Interactive WYSIWYG Print Preview Engine
- **Universal Print Preview Canvas:** Clicking print anywhere in the software (Monthly Attendance, Fee Receipts, Question Papers, Solutions, Passbooks, Timetables, P&L Statements, Vouchers, and Student Registers) immediately launches a dedicated, high-definition Print Preview window.
- **Top Control Suite:**
  - 🖨️ **Print (प्रिंट करें) [Ctrl+P]:** Send cleanly to the printer with one click.
  - 🌐 **Open in Chrome / Browser:** Instant one-click launch in your default web browser (Chrome, Edge) with full native browser print preview, two-sided printing, margins, and paper trays.
  - 💾 **Save PDF:** Export the rendered document into a certified PDF instantly.
  - 🔍 **Zoom In (+) / Zoom Out (−) / Fit 100%:** Inspect minute details, student roll numbers, fee totals, and barcodes before printing.
  - 📄 **Dynamic Paper Badge:** Auto-detects and formats for `A4 Portrait`, `A4 Landscape`, `A5`, `Thermal 80mm`, and `Thermal 58mm`.
  - ✕ **Close [Esc]:** Quick dismissal.
- **Neutral Paper Studio Canvas:** Displays true-to-life white document pages on a comfortable reader neutral workspace (`#525659`), eliminating dark mode interference on printed materials.
- **Windows 11 Print Dialog Optimization:** Automatically configures `PreferLegacyPrintDialog = 1` on startup, completely resolving the Windows 11 *"This app doesn't support print preview"* blank box and providing fast, direct native printer selection (Brother, HP, Canon, Epson).

### 📱 2. Mobile Companion Fee Reconciliation & Alphanumeric Receipts
- **Conflict-Free History Merging:** Merges payments collected via the Android companion app with local desktop accounts without clobbering existing histories or duplicate timestamps.
- **Alphanumeric Receipt Parsing:** Safely parses alphanumeric receipt tokens (`REC-17482`), eliminating inline JavaScript `ReferenceError` crashes and ensuring instant receipt preview and re-prints.
- **Live Modal Refresh:** Incoming mobile fee transactions immediately appear in open payment history modals on desktop without restarting.

### 📚 3. Courses & Exams Persistence & Firestore Schema Compliance
- **Firestore Security Rules Alignment:** Automatically computes and attaches `count: list.length` to all synchronized collections (`batches`, `exams`, `attendance`, `expenses`), preventing silent `PERMISSION_DENIED` rejection.
- **Permanent Creation Action:** Added a permanent `＋ Create Exam` primary button in the exams dashboard header.
- **State ID Clean Reset:** Auto-resets `editCourseId = null` and `_editExamId = null` on modal dismissal, preventing accidental overwrites.

### 🛡️ 4. Snapshot Disaster Recovery Engine
- **Atomic Pre-Restore Safety Net:** Automatically creates an emergency snapshot (`classcore_pre_restore_*.json`) immediately before restoring any historical backup.
- **Zero-Downtime State Refresh:** Decrypts encrypted database vaults atomically and broadcasts instant reload events to all active windows.

### 🪪 5. Physical Fee Card Passbook Overprinting Engine
- **Direct Card Feed Mode:** Print directly onto custom tuition passbooks and cards (`100mm × 185mm`) via Epson EcoTank and Canon rear trays.
- **A4 Carrier Sheet Mode:** Universal support for laser printers (HP LaserJet, Brother, Canon) using A4 carrier sheets.
- **Micro-Calibration:** Visual canvas with drag-and-drop handles and millimeter adjustment sliders.

### ⚡ 6. Executive Profit & Loss (P&L) Statement Engine
- **Operating Revenue & Expenses:** Real-time financial calculations across fee collections, expense vouchers, and faculty payroll.
- **Certified Exports:** Native Electron print layouts, official PDF exports, and spreadsheet-ready CSV downloads.

---

## 💻 System Requirements

| Specification | Minimum | Recommended |
|:---|:---|:---|
| **OS** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 or higher |
| **RAM** | 4 GB | 8 GB or higher |
| **Storage** | 500 MB free disk space | SSD storage with 2 GB+ free space |
| **Printers** | Any standard A4 / A5 Laser or InkJet Printer, Thermal (58mm/80mm), or Passbook Printer | Brother DCP series, HP LaserJet, Epson EcoTank, TVS Thermal |

---

## 📞 Support & Community

Managing an educational institute shouldn't require complex IT setups. If you have questions or need assistance:

- **Creator & Lead Developer:** Kuldeep Prajapati
- **Support & Inquiries:** [coreclass.2025@gmail.com](mailto:coreclass.2025@gmail.com)

<div align="center">
  <sub>Copyright © 2025–2026 ClassCore. All rights reserved.</sub>
</div>
