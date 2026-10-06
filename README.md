<div align="center">

# 🎓 ClassCore — Next-Gen Tuition & Institute Management

**The complete, high-performance offline-first management suite and mobile companion for modern coaching centers, academies, and private tutors.**

[![Version](https://img.shields.io/badge/Version-3.5.5-2563EB?style=for-the-badge&logo=electron)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20(x64)-0078D6?style=for-the-badge&logo=windows)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.5.exe)
[![Android Companion](https://img.shields.io/badge/Android-Companion%20App-3DDC84?style=for-the-badge&logo=android)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)
[![Cloud Sync](https://img.shields.io/badge/Cloud%20Sync-Firebase%20Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Offline Capable](https://img.shields.io/badge/Architecture-100%25%20Offline%20First-10B981?style=for-the-badge)](https://github.com/prajapatikuldeep455-source/classcore-releases)

---

### 📥 [Download ClassCore Desktop v3.5.5 (Windows x64)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.5.exe) &nbsp;|&nbsp; 📲 [Download Mobile Companion (.apk)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)

</div>

---

## 🌟 Why ClassCore?

Managing an educational institute or tuition center shouldn't require juggling complicated spreadsheets, multiple messaging apps, separate billing tools, and manual handwriting on paper cards.

**ClassCore** unifies every operational aspect into a sleek, lightning-fast desktop command center paired with an instant Android mobile app. Built with an **offline-first philosophy**, ClassCore guarantees that power outages, weak internet, or server downtimes never interrupt your admissions, fee collections, or biometric attendance.

---

## 🚀 Highlights in Latest v3.5.5 Release

### 🖥️ 1. Widescreen Mode & 3-Line Sidebar Toggle (`☰` / `Ctrl+B`)
- **Quick Topbar Hamburger Toggle:** A modern 3-line hamburger icon (`☰`) is now integrated right beside the page title in the topbar.
- **Ergonomic Icon-Only Rail (68px):** Clicking `☰` or pressing `Ctrl + B` collapses the 240px navigation sidebar into a compact 68px rail, expanding the active workspace by over 172px for wide data tables, financial ledgers, and attendance sheets.
- **Instant Recognition:** Desks (Dashboard, Students, Batches, Courses, Exams, Fees, Expenses, Reports, Attendance, Broadcast, Settings) remain centered with high-clarity emoji icons and native hover tooltips.
- **Persistent View State:** Remembers the user's preferred sidebar state across reloads and application restarts via `localStorage`.

### 📈 2. Institute Reports & Financial Solvency Desk Overhaul
- **Full-Width Ledger Expansion:** Resolved a grid-nesting constraint in the Class-wise Collections card, unlocking 100% full-width rendering for the **Executive Statement of Operations**, **Fee Collections Register**, **Operating Expense Ledger**, and **Outstanding Receivables**.
- **Zero Text Squish & Cut-offs:** Financial tables, credit inflow streams, and debit payroll allocations now expand with breathing room on standard and ultrawide screens.
- **5-Sheet Audit Workbook (.xlsx):** Generates complete audit-ready Excel workbooks (`Executive Summary`, `Fee Collections`, `Operating Expenses`, `Fee Defaulters & Dues`, `Staff Payroll`) with auto-calculated formulas.

### 📣 3. Re-Engineered WhatsApp Broadcast Desk
- **Delivery Readiness Card (Sending Status):** Replaced legacy bulky alert blocks with a modern Delivery Readiness card featuring an SVG beacon, verified recipient counter, and live pulsing `Ready` badge.
- **Balanced Full-Width 2-Column Grid:** Structured `Recipient Target` and `Sending Status` across an exact 50%–50% responsive grid with matching `58px` baseline heights and zero text truncation.
- **Solid WhatsApp Action Button:** High-contrast WhatsApp brand green button (`#16A34A`) with native iconography, subtle shadow, and responsive hover feedback.

### 📚 4. Courses Desk Layout Polish
- **Harmonized CSS Grid:** Repaired header flexbox encapsulation, ensuring course cards flow naturally from left to right in a responsive auto-fill grid rather than clinging to right-hand edges.

### 🏛️ 5. Senior Developer Codebase Architecture & QA Gate
- **Automated Syntax Validator (`npm run check`):** Native compiler check across all 34 JavaScript modules to ensure 100% syntax integrity and zero syntax regressions.
- **Root Directory Hygiene:** Cleaned legacy scratch files and logs into structured directories (`scripts/legacy/`, `scratch/`, `docs/`).
- **Comprehensive Blueprint:** Published documentation covering process boundaries, security models, and developer guidelines.

---

## 💎 Signature Modules & Capabilities

### 🖨️ Interactive WYSIWYG Print Preview Engine
- **Universal Print Preview Canvas:** High-definition Print Preview studio for Attendance, Fee Receipts, Question Papers, Solutions, Passbooks, Timetables, P&L Statements, and Student Registers.
- **Paper Engine:** Accurate dimensional scaling for `A4`, `A5`, `A6 (105×148mm)`, `A7 (74×105mm)`, `Thermal 80mm/58mm`, and `Fee Card Passbooks (100×185mm)`.
- **Windows 11 Print Dialog Optimization:** Configured for zero blank preview dialog errors with direct native printer selection (Brother, HP, Canon, Epson).

### 🪪 Physical Fee Passbook Overprinting Engine
- **Direct Card Feed:** Prints directly onto physical student tuition cards and passbooks (`100mm × 185mm`, `95mm × 180mm`, or custom dimensions) via rear tray printers (Epson EcoTank, Canon PIXMA).
- **A4 Carrier Sheet Mode:** Laser printer support (HP LaserJet, Brother) using standard A4 carrier sheets.
- **Micro-Calibration Studio:** Drag-and-drop handles and millimeter adjustment sliders for millimeter-accurate print alignment.

### ⚡ Universal Multi-Size Receipts & Dynamic Offline UPI QR
- Dynamic NPCI UPI QR code generation on fee receipts for instant scan-and-pay via Google Pay, PhonePe, Paytm, and BHIM.
- Multi-format printing: A4, A5, A6, A7, and 58mm / 80mm thermal ESC/POS rolls.

### 📝 Automated Question Paper Generator (AQPG)
- Board/school pattern exam question paper synthesis with sections, marks weightage, chapter blueprints, and automated answer keys.
- Preloaded with GSEB & NCERT curriculum chapter catalogs.

### ⏱️ Biometric Attendance & Realtime Defaulters
- USB and network integration with eSSL, Realtime, ZKTeco, and Mantra biometric machines.
- Pen drive log importer for centers without local networks.
- One-click daily attendance registers and absentee WhatsApp alerts to parents.

### 📱 Mobile Companion (Android App)
- **Continuous Camera Viewfinder:** High-speed in-app QR code attendance scanning using phone camera with targeting reticle, audio chime tones, and haptic vibration.
- **100% Offline Compatible:** Powered by bundled `jsQR` and hardware-accelerated scanning.
- **Full Desktop Interoperability:** Automatically scans Desktop PVC ID cards and Roll numbers with instant Cloud Sync to PC.

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
