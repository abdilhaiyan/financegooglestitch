# Project Summary: FamFinance

**FamFinance** is a professional, secure, and family-oriented financial management suite. It bridges high-fidelity UI design with a lightweight Google Sheets backend, allowing families to track spending, manage collective bills, and generate professional PDF reports in real-time.

---

## 🏗️ Architecture Overview
- **Frontend**: Responsive HTML5/CSS3 (Tailwind CSS) with vanilla JavaScript.
- **Backend**: Google Apps Script (acting as a REST API).
- **Database**: Google Sheets (structured into Transactions, RecurringPayments, and FamilyGoals).
- **Hosting**: Designed for GitHub Pages, Netlify, or Vercel.

---

## 📱 Screen Catalog & Purpose

### Desktop Suite (Primary Management)
1. **Family Contribution Hub (Live Sync)**: High-level overview of savings, goals, and recent activity.
2. **Transaction Manager (Live Sync)**: The main ledger for viewing, searching, and exporting family expenses.
3. **Payment & Transfers (Live Sync)**: Interface for managing recurring bills and manual family transfers.
4. **Analytics & Reports Dashboard (Deep Dive)**: Detailed spending breakdowns, budget vs. actuals, and comparative charts.
5. **Report Center (Pro Archiving)**: Configuration for automated reporting and PDF archiving to Google Drive.
6. **Settings & Customization (Enhanced)**: Profile management, family sharing roles, and cloud connection status.

### Mobile Suite (On-the-Go Access)
1. **Family Hub (Mobile)**: Glanceable goal progress and quick-action bill payments.
2. **Transaction Manager (Mobile)**: Mobile-optimized feed for checking transactions anywhere.
3. **Payments & Transfers (Mobile)**: Simplified transfer form and bill scheduling.
4. **Report Center (Mobile)**: Mobile configuration for generating spending insights.
5. **Family Members Management**: Administrative interface for managing family roles and privacy.

---

## 🔐 Design System: Kinship Ledger
- **Typography**: Inter (Clean, modern, professional).
- **Color Palette**: Deep slate (`#0f172a`) with high-contrast functional colors (Success Green, Error Red, Info Blue).
- **Visual Style**: Flat, high-glanceability cards with consistent 4px rounding and generous whitespace.

---

## 🛠️ Implementation Priority
1. **Backend First**: Deploy the `code.gs` Apps Script to establish the API.
2. **Database Schema**: Setup the Google Sheet tabs to ensure data integrity.
3. **Core UI**: Deploy the **Transaction Manager** and **Family Contribution Hub** as your primary entry points.
4. **Extended Features**: Add Analytics and Settings screens to complete the suite.
