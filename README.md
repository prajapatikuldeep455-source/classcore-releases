<div align="center">

# 🎓 ClassCore — Next-Gen Tuition & Institute Management

**The complete, high-performance offline-first management suite and mobile companion for modern coaching centers, academies, and private tutors.**

[![Version](https://img.shields.io/badge/Version-3.5.6-2563EB?style=for-the-badge&logo=electron)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20(x64)-0078D6?style=for-the-badge&logo=windows)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.6.exe)
[![Android Companion](https://img.shields.io/badge/Android-Companion%20App-3DDC84?style=for-the-badge&logo=android)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)
[![Cloud Sync](https://img.shields.io/badge/Cloud%20Sync-Firebase%20Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Offline Capable](https://img.shields.io/badge/Architecture-100%25%20Offline%20First-10B981?style=for-the-badge)](https://github.com/prajapatikuldeep455-source/classcore-releases)

---

### 📥 [Download ClassCore Desktop v3.5.6 (Windows x64)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.6.exe) &nbsp;|&nbsp; 📲 [Download Mobile Companion (.apk)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)

</div>

---

## 🌟 Why ClassCore?

Managing an educational institute or coaching center shouldn't require juggling complicated spreadsheets, multiple messaging apps, separate billing tools, and manual handwriting on paper registers.

**ClassCore** unifies every operational aspect into a sleek, lightning-fast desktop command center paired with an instant Android mobile app. Built with an **offline-first philosophy**, ClassCore guarantees that power outages, weak internet, or server downtimes never interrupt your admissions, fee collections, student examinations, or biometric attendance.

---

## 🚀 Highlights in Latest v3.5.6 Release

### 🛡️ 1. Fortified Backend Engine & Forensic Hardening
* **AES-256-GCM Vault Auto-Decryption:** Upgraded backup restoration in `main.js`. Automatically detects and decrypts encrypted `CC_VAULT_V1` backup archives while preserving seamless compatibility with plain JSON databases.
* **Windows File Lock Defender:** Implemented exponential backoff retry logic (`0ms`, `60ms`, `180ms`, `350ms`) with copy-on-write fallback in `_safeWriteData`. Completely eliminates `EBUSY` / `EPERM` write crashes on Windows and purges orphan `.tmp.*` files.
* **Database Anti-Truncation Shield:** Integrated a strict Schema Merge Guard in `main.js` preventing partial payloads or defused settings calls from ever truncating or wiping core student arrays.
* **Zero-Leak Chromium Engine:** Bounded timeout race (15s) with deterministic window destruction in `_generatePDF` and `print-content` prevents background worker hangs and eliminates RAM consumption leaks.
* **WhatsApp AI Auto-Reply Guard:** Added 30-second socket timeouts across Anthropic, Gemini, and OpenAI handlers in `wa-hub-ai.js` to ensure the messaging engine never freezes on network disconnects.
* **Atomic Local KV Storage:** Replaced raw synchronous writes in `wa-hub-store.js` with atomic file swapping (`_safeWriteJsonFile`).

### 📱 2. ClassCore Mobile Companion (Android App)
* **Real-Time Bi-Directional Cloud Sync:** Instant sync with ClassCore PC desktop via Google Firebase Firestore with an offline-resilient local change buffer.
* **🔒 Biometric App Lock:** Safeguard institute data with physical fingerprint sensor and face authentication.
* **📷 High-Speed QR Attendance Scanner:** Full-frame camera viewfinder with emerald target lock, laser scanning animation, and audio chime feedback.
* **👥 Role-Based Staff Dashboards:** Dedicated views for Teachers (attendance, homework, tests) while securely hiding institute expenses and owner net profit.
* **💰 Mobile Fee Ledger & Instant Receipts:** View collection trends, record payments, and share WhatsApp receipts directly from your phone.

### 🖥️ 3. Widescreen Mode & 3-Line Sidebar Toggle (`☰` / `Ctrl+B`)
* **Quick Topbar Hamburger Toggle:** A modern 3-line hamburger icon (`☰`) is integrated right beside the page title in the topbar.
* **Ergonomic Icon-Only Rail (68px):** Clicking `☰` or pressing `Ctrl + B` collapses the 240px navigation sidebar into a compact 68px rail, expanding the active workspace by over 172px for wide data tables, financial ledgers, and attendance sheets.
* **Persistent View State:** Remembers the user's preferred sidebar state across reloads and application restarts.

### 📈 4. Financial Solvency & Reports Overhaul
* **Full-Width Ledger Expansion:** Unlocks 100% full-width rendering for Executive Statement of Operations, Fee Collections Register, Operating Expense Ledger, and Outstanding Receivables.
* **5-Sheet Audit Workbook (.xlsx):** Generates complete audit-ready Excel workbooks with automated balance sheet formulas.

### 📣 5. Re-Engineered WhatsApp Broadcast Desk
* **Balanced Full-Width 2-Column Grid:** Structured `Recipient Target` and `Sending Status` across an exact 50%–50% responsive grid with matching `58px` baseline heights and zero text truncation.
* **Beacon Ready Status:** Modern Delivery Readiness card with live pulsing status indicator and zero UI squish.

---

## 💎 Signature Modules & Capabilities

### 🖨️ Universal WYSIWYG Print Preview Engine
* **Universal Canvas:** High-definition Print Preview studio for Attendance, Fee Receipts, Question Papers, Solutions, Passbooks, Timetables, P&L Statements, and Student Registers.
* **Accurate Paper Scaling:** Pixel-perfect calibration for `A4`, `A5`, `A6`, `A7`, `Thermal 80mm/58mm`, and `Passbooks (100×185mm)`.

### 🪪 Physical Fee Passbook Overprinting Engine
* **Direct Card Feed:** Prints directly onto physical student tuition cards and passbooks via rear tray printers (Epson EcoTank, Canon PIXMA).
* **Laser Printer Carrier Sheet Mode:** Support for HP LaserJet and Brother printers using standard A4 carrier sheets.
* **Micro-Calibration Studio:** Millimeter adjustment handles for precision print alignment.

### ⚡ Universal Multi-Size Receipts & Dynamic Offline UPI QR
* Dynamic NPCI UPI QR code generation on fee receipts for instant scan-and-pay via Google Pay, PhonePe, Paytm, and BHIM.
* Multi-format printing: A4, A5, A6, A7, and 58mm / 80mm thermal ESC/POS rolls.

### 📝 Automated Question Paper Generator (AQPG)
* Board/school pattern exam question paper synthesis with sections, marks weightage, chapter blueprints, and automated answer keys.
* Preloaded with GSEB & NCERT curriculum chapter catalogs.

### ⏱️ Biometric Attendance & Realtime Defaulters
* USB and network integration with eSSL, Realtime, ZKTeco, and Mantra biometric machines.
* Pen drive log importer for centers without local networks.
* One-click daily attendance registers and absentee WhatsApp alerts to parents.

---

## 💻 System Requirements

| Specification | Minimum | Recommended |
|:---|:---|:---|
| **OS** | Windows 10 (64-bit) | Windows 11 (64-bit) |
| **Processor** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 or higher |
| **RAM** | 4 GB | 8 GB or higher |
| **Storage** | 500 MB free disk space | SSD storage with 2 GB+ free space |
| **Mobile App OS** | Android 8.0 (Oreo) or higher | Android 12, 13, 14+ |
| **Printers** | Any standard A4/A5 Laser or InkJet Printer, Thermal (58mm/80mm), or Passbook Printer | Brother DCP series, HP LaserJet, Epson EcoTank, TVS Thermal |

---

## 📞 Support & Community

Managing an educational institute shouldn't require complex IT setups. If you have questions or need assistance:

- **Creator & Lead Developer:** Kuldeep Prajapati
- **Support & Inquiries:** [coreclass.2025@gmail.com](mailto:coreclass.2025@gmail.com)

<div align="center">
  <sub>Copyright © 2025–2026 ClassCore. All rights reserved.</sub>
</div>
