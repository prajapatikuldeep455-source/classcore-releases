<div align="center">

# 🎓 ClassCore — Next-Gen Tuition & Institute Management

**The complete, high-performance offline-first management suite and mobile companion for modern coaching centers, academies, and private tutors.**

[![Version](https://img.shields.io/badge/Version-3.5.2-2563EB?style=for-the-badge&logo=electron)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest)
[![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011%20(x64)-0078D6?style=for-the-badge&logo=windows)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.2.exe)
[![Android Companion](https://img.shields.io/badge/Android-Companion%20App-3DDC84?style=for-the-badge&logo=android)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)
[![Cloud Sync](https://img.shields.io/badge/Cloud%20Sync-Firebase%20Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)](https://firebase.google.com)
[![Offline Capable](https://img.shields.io/badge/Architecture-100%25%20Offline%20First-10B981?style=for-the-badge)](https://github.com/prajapatikuldeep455-source/classcore-releases)

---

### 📥 [Download ClassCore Desktop v3.5.2 (Windows x64)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.2.exe) &nbsp;|&nbsp; 📲 [Download Mobile Companion (.apk)](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk)

</div>

---

## 🌟 Why ClassCore?

Managing an educational institute or tuition center shouldn't require juggling complicated spreadsheets, multiple messaging apps, separate billing tools, and manual handwriting on paper cards.

**ClassCore** unifies every operational aspect into a sleek, lightning-fast desktop command center paired with an instant Android mobile app. Built with an **offline-first philosophy**, ClassCore guarantees that power outages, weak internet, or server downtimes never interrupt your admissions, fee collections, or biometric attendance.

---

## 🚀 Highlights in Latest v3.5.2 Release

### 📊 1. Executive Profit & Loss (P&L) Statement Engine
- **Holistic Operational Accounting:** Automatically computes **Operating Revenue** (Total fees collected across Cash, UPI, and Bank transfer channels), **Operating Expenditures** (Classroom & center expense vouchers), and **Faculty Payroll** (Disbursed teacher salaries).
- **Executive Metric Cards:** Instant computation of Gross Revenue, Total Operating Outflow, Net Operating Surplus/Deficit, and Operating Profit Margin %.
- **Comparative Multi-Channel Schedule:** Side-by-side analytical breakdown of revenue streams vs categorized expense heads.
- **Auditable Voucher Audit Trail:** Complete transaction-level table with Voucher No, Date, Category, Description, Paid To, Payment Mode, and Amount.
- **Period Filter Presets:** Instant 1-click recalculation across `This Month`, `Last Month`, `This Financial Year`, and `All-Time`.
- **1-Click Certified Exports:** Native Electron A4 Print layout (`window.classcore.printContent`), official signed PDF document export (`window.classcore.savePDF`), and spreadsheet-ready CSV downloads.

### ⚡ 2. Real-Time Auto-Balancing Milestones Engine
- **Zero-Friction Balance Allocation:** Adding a milestone (`➕ Add Milestone`) automatically checks for any unallocated remainder (`Target - Scheduled Sum`) and assigns the exact unallocated balance.
- **Smart 1-Click Split & Equalize:** Adding a milestone to an already balanced schedule automatically re-splits the fee evenly without manual mental math.
- **Live Reactive Feedback:** Typing in any milestone amount dynamically updates the scheduled sum, allocation status pill, and percentage share badge `(40%)`, `(30%)` in real time.
- **Actionable Correction Quick-Fixes:** Contextual `[⚡ Allocate]` and `[⚡ Balance]` buttons appear immediately if an overage or remainder is detected.
- **Admission Form Sync:** Typing a new course fee in student admission auto-scales all milestone installments proportionally.

### ☁️ 3. Dynamic Cloud Plan Synchronization
- **Bidirectional Plan Sync:** Dynamic synchronization between local software licenses and Cloud Firestore (`accounts/{username}` and `institutes/{username}`).
- **Eliminates Overwrite Bug:** Fixes an issue where cloud documents were overwritten with `'trial'`. Active paid plans (`monthly`, `yearly`, `lifetime`) now persist securely and sync to companion devices.
- **Auto Cloud-to-Desktop Upgrade:** Plans upgraded via the web console or mobile companion automatically unlock the desktop client without requiring manual license key re-entry.
- **Real-Time Purchase Trigger:** Razorpay payments and offline key activations trigger instantaneous Firestore cloud sync.

### 📲 4. Direct Mobile APK Download QR Code
- **1-Scan Frictionless Download:** Scanning the pairing QR code with any Android phone now links directly to the production APK download, eliminating intermediate GitHub sign-in walls.
- **Browser & WhatsApp Sharing:** Integrated "Download in Browser", "Copy Link", and "Share to WhatsApp" actions for simple staff onboarding.

### 👁️ 5. Teacher Security & Password Reveal System
- **Reversible Credential Cipher:** Implemented an obfuscated credential cipher (`_encryptPassToken` / `_decryptPassToken`) allowing administrators to view their actual plain password on-demand using the "👁️ Show" toggle.

### 🛡️ 6. Historical Point-in-Time Database Snapshots
- **Intelligent Snapshot Auditing:** Snapshots are cataloged with human-friendly badges (`Safety Guard`, `Daily Snapshot`, `System Baseline`) instead of cryptic filenames.
- **1-Click Restore & Pen Drive Export:** Restore any historical database point in 1 click with automatic pre-restore safety snapshots and direct external USB drive backups.

---

## ✨ Features in v3.5.0 Release

### 🪪 1. Physical Fee Card Passbook Overprinting Engine
- **Direct-on-Card Printing:** Print directly onto any existing physical tuition fee card or monthly passbook without needing specialized stationery.
- **Pre-Calibrated Universal Presets:** Sub-millimeter pre-configured alignment for standard **11-Month** (*June to April*) and **12-Month** (*May to April*) tuition cycles.
- **Dual Universal Feeding Modes:**
  - **Direct Card Feed Mode:** Tailored for Epson EcoTank, Canon PIXMA, and HP InkTank printers with custom card rear feeder slots (`100mm × 185mm`).
  - **A4 Carrier Sheet Mode:** Universal support for laser printers (HP LaserJet, Brother, Canon) by placing cards onto a standard A4 carrier sheet.
- **Interactive Drag Designer & Calibration Sliders:** Visual canvas with drag-and-drop handles (`↕`) and fine micro-calibration sliders (`±15mm`) with persistent memory.
- **Selective Digital Signing:** Optional cursive digital signature printing. Unchecking leaves cells 100% blank for real physical pen signing; unpaid months remain blank for future print passes.

### 📸 2. Smart Computer Vision Auto-Detection
- **Instant Photo Analysis:** Upload a photo of any coaching class's physical fee card. The built-in HTML5 Canvas computer vision engine scans luminance gradients and horizontal lines in < 20ms.
- **Automatic Grid Snapping:** Automatically detects student header label lines (Name, Class, Roll No, Fees) and aligns month table rows with zero manual math.

### ⚡ 3. Dynamic Offline UPI QR Receipts
- **Instant Scan-to-Pay:** Every fee receipt automatically encodes the payable amount, tuition VPA, and student ID into a standard NPCI UPI QR code. Parents scan and pay instantly via Google Pay, PhonePe, Paytm, or BHIM.
- **Multi-Size Invoices:** Print in A4 full-page, A5 half-page, A6 voucher, A7 slip, or 58mm / 80mm ESC/POS thermal printer format.

### 📝 4. Intelligent Exam Question Paper Generator
- **School & Board Pattern Papers:** Generate professional exam papers with custom sections, marks allocation, answer keys, and watermarks.
- **1-Click PDF Export:** Clean print-ready formatting with institute branding and custom instructions.

### ⏱️ 5. Universal Biometric Hub
- **Direct LAN & USB Sync:** Native integration with leading biometric machines (**eSSL**, **Realtime**, **ZKTeco**, **Mantra**, **BioMax**).
- **Pen Drive Log Importer:** Import punch logs offline from USB flash drives (`.dat`, `.csv`, `.txt`).
- **Live Background Scanner:** Real-time push notifications and automated WhatsApp parent alerts on student punch-in/punch-out.

---

## 🚀 Key Modules & 360° Capabilities

```
                      ┌─────────────────────────────────────────┐
                      │          ClassCore Command Center       │
                      └────────────────────┬────────────────────┘
                                           │
         ┌──────────────────┬──────────────┴──────────────┬──────────────────┐
         │                  │                             │                  │
┌────────▼────────┐┌────────▼────────┐           ┌────────▼────────┐┌────────▼────────┐
│  Admissions 360 ││  Attendance 360 │           │    Fees 360°    ││    Exams 360°   │
│  PVC ID Cards   ││  Biometric Hub  │           │  Fee Card Engine││  Paper Generator│
│  Student Dossier││  QR Punch Desk  │           │  Dynamic UPI QR ││  A4 Report Cards│
└─────────────────┘└─────────────────┘           └─────────────────┘└─────────────────┘
         │                  │                             │                  │
         └──────────────────┼─────────────────────────────┼──────────────────┘
                            │                             │
                   ┌────────▼────────┐           ┌────────▼────────┐
                   │  Timetable 360° │           │  WhatsApp Hub   │
                   │ Clash Detection │           │ AI Auto-Replies │
                   │ Operating Ledger│           │ Auto-Broadcasts │
                   └─────────────────┘           └─────────────────┘
```

---

### 1. 🎓 Students Directory & Admissions 360°
- **Comprehensive Student Dossier:** Maintain complete profiles including academic history, date of birth, blood group, school, guardian details, and active enrolled batches.
- **CR80 Smart PVC ID Card Generator:** Instant generation of professional student ID cards complete with institute branding, student photo, student barcode, and QR code for rapid attendance.
- **Auto Roll Numbers & Admission Numbers:** Automated configurable roll number indexing and admission code numbering.
- **High-Speed CSV Importer & Exporter:** Bulk import hundreds of existing student records in seconds with automatic column mapping and validation.

---

### 2. ⚡ Attendance & Biometric Management 360°
- **Universal Biometric Attendance Hub:** Plug-and-play compatibility with eSSL, Realtime, ZKTeco, Mantra, and BioMax scanners via USB and LAN.
- **Pen Drive Log Importer:** Effortlessly import attendance logs via USB flash drive without running network cables to the machine.
- **Instant QR & Barcode Attendance Punch Desk:** High-speed barcode/QR attendance punch modal with real-time audio chimes and visual verification.
- **Visual Monthly Attendance Heatmap:** Interactive calendar grid visualizing daily attendance patterns (Present `P`, Absent `A`, Late `L`, Formal Leave `LV`).
- **Critical Defaulters Radar:** Automatically isolates students falling below required attendance thresholds (e.g. `< 75%`) for proactive academic intervention.
- **Daily WhatsApp Attendance Bulletin:** 1-click attendance summary reports dispatched directly to parents informing them of their ward's presence or absence.

---

### 3. 💰 Fees, Installments & Physical Fee Card Engine 360°
- **Physical Fee Card Overprinting:** Direct printing onto existing coaching fee cards and passbooks with sub-millimeter precision.
- **Multi-Part Installment Schedules:** Divide course fees into flexible milestone installments with individual due dates and custom amounts.
- **Thermal POS & Multi-Size Invoices:** Support for 80mm and 58mm POS thermal receipt printers, A7 mini vouchers, A6 slips, A5 sheets, and formal full-page A4 PDF fee receipts.
- **Dynamic "Scan-to-Pay" UPI QR:** Embedded dynamic UPI payment QR codes featuring custom payment amounts and transaction references, allowing parents to pay instantly from GPay, PhonePe, or Paytm.
- **Fee Defaulter Aging Analysis:** Granular tracking of overdue dues broken down into aging buckets (0–30 days, 31–60 days, 61–90 days, 90+ days).
- **3-Tone WhatsApp Fee Reminders:** Polite reminder, due date alert, and urgent notice templates with personalized payment details.

---

### 4. 📅 Multi-Batch Timetable & Clash Prevention
- **7-Day Interactive Weekly Matrix:** Visual weekday schedule (Monday to Sunday) displaying all running batches, classrooms, and teachers.
- **Automated Clash Detection:** Real-time clash radar prevents scheduling overlapping batches for the same teacher or classroom.
- **1-Click Quick Scheduler:** Fast preset scheduler allowing instant assignment of day presets (`Mon–Sat`, `Mon–Fri`, `MWF`, `TTS`).

---

### 5. 👨‍🏫 Teacher Payroll & Salary Vouchers
- **Monthly Payout Desk:** Seamless calculation of net teacher compensation based on base monthly pay, bonuses, and deductions.
- **Thermal POS & A4 Salary Slips:** Instant generation and printing of formal salary vouchers.
- **Direct WhatsApp Payslips:** Send salary slips and payment confirmations directly to faculty members via WhatsApp in 1 click.

---

### 6. 💸 Operating Expense Ledger & P&L Analytics
- **Categorized Expense Tracker:** Monitor recurring and ad-hoc overhead expenses (Rent, Electricity, Supplies, Teacher Salaries, Marketing).
- **Live Profit & Margin Indicators:** Real-time calculation of Gross Tuition Collections, Operating Expenses, and Net Operating Margin.
- **Printable Debit Vouchers & CSV Export:** Maintain audit-ready financial ledgers with customizable date filters.

---

### 7. 📊 Multi-Subject Exam Series & Question Paper Generator 360°
- **Intelligent Exam Paper Generator:** Auto-format question papers with sections, marks distribution, blueprints, and answer keys.
- **Spreadsheet-Style Batch Marksheet Matrix:** Enter marks rapidly with keyboard navigation (`Tab`, `Shift+Tab`, `Enter`, arrow keys) and an instant Absent (`AB`) toggle.
- **🏆 Top 3 Toppers Podium:** Automatic calculation of Top 3 Toppers (Gold 🥇, Silver 🥈, Bronze 🥉), aggregate percentages, and batch ranks.
- **Weakest Subject Radar & Remedial Watchlist:** Automatically isolates subjects with lowest class averages and flags struggling students for targeted remedial guidance.
- **1-Click Continuous A4 Batch Report Cards:** Bulk print elegant student report cards with CBSE/GSEB grading scales, subject breakdowns, and signature lines.

---

### 8. 💬 Integrated WhatsApp Hub (Zero-Cost Messaging)
- **Direct WhatsApp Connection:** Powered by a built-in WhatsApp Web engine (`Baileys`) — send broadcasts, receipts, and scorecards directly without opening external browser tabs.
- **Anti-Ban Protection:** Intelligent pacing, randomized delays, and human-like typing intervals protect your account from spam filters.
- **Multi-Provider AI Auto-Reply Engine:** Built-in AI auto-responder compatible with **Google Gemini**, **Anthropic Claude**, and **OpenAI GPT** to answer prospective parent queries outside operating hours.

---

### 9. ☁️ Unified Cloud Sync & Android Mobile Companion
- **Real-Time Bi-Directional Synchronization:** Sync students, batches, attendance, fee collections, expenses, and exams between Desktop and Android Mobile using Google Firebase Firestore.
- **Unified Cloud Authentication:** Secure login using `@username` and salted cryptographic password hashing (`SHA-256 + 16-byte salt`).
- **Remember Me Functionality:** 1-tap seamless synchronization without re-typing credentials daily.
- **True Offline First:** Continue operating smoothly when internet is down; changes automatically flush to the cloud when connection resumes.

---

## 💻 System Requirements

| Platform | Minimum Requirements | Recommended |
| :--- | :--- | :--- |
| **Windows Desktop** | Windows 10 (64-bit), 4 GB RAM, 500 MB Storage | Windows 11 (64-bit), 8 GB RAM, SSD Storage |
| **Android Mobile** | Android 8.0 (Oreo) or newer, 2 GB RAM | Android 11+ or newer, 4 GB RAM |

---

## 📥 Installation & Setup Guide

### 1. Windows Desktop Installation
1. Download the latest installer: [`ClassCore-Setup-3.5.2.exe`](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Setup-3.5.2.exe).
2. Run the installer and follow the setup wizard.
3. Launch **ClassCore** from your Desktop or Start Menu.
4. On first launch, create your Admin account with your desired `@username` and password.

### 2. Android Mobile Companion Setup
1. Download the latest APK: [`ClassCore-Mobile.apk`](https://github.com/prajapatikuldeep455-source/classcore-releases/releases/latest/download/ClassCore-Mobile.apk).
2. Open the APK on your Android device and tap **Install** *(Enable "Install from Unknown Sources" if prompted)*.
3. Open the ClassCore App and log in using your **Desktop `@username` and Password**.
4. Check **Remember Me** to stay logged in and enjoy real-time background synchronization.

---

## 🔒 Security & Privacy First

- **Zero Third-Party Data Selling:** Your student directories, financial records, and marks are stored locally on your device and inside your own private Firebase cloud project.
- **Cryptographic Password Protection:** Passwords are never sent or stored as plaintext; protected with salted SHA-256 encryption.
- **Layer 3 Tamper Hardening:** Code obfuscation and ASAR archive encryption safeguard licensing and proprietary logic.
- **Private Source Code:** The core application engine is developed in a closed-source private repository; only verified production binaries are distributed via this repository.

---

## 📞 Support & Community

- **Creator & Lead Developer:** Kuldeep Prajapati
- **Support & Inquiries:** [coreclass.2025@gmail.com](mailto:coreclass.2025@gmail.com)

<div align="center">
  <sub>Copyright © 2025–2026 ClassCore. All rights reserved.</sub>
</div>
