# Enterprise Invoicing & Accounting Suite

A cross-platform web and mobile software package supporting complete invoice lifecycle management, stock controls, and double-entry accounting integrations.

## Features Implemented
* 🧾 **Invoice Generation & Sequential Numbering**: Automatic generation with unique tracking identifiers (`INV-1001`, `INV-1002`).
* 💳 **Partial-Payment & Credit Balance Tracking**: Records custom partial settlements and updates customer ledger balances.
* 📦 **Inventory Integration**: Live stock tracking and inventory deduction upon invoice generation.
* 📱 **WhatsApp & Export Utilities**: Native share capability via WhatsApp along with client-side PDF document downloads.
* 🖨️ **Print-Friendly Formatters**: Media queries tailored specifically for printing standard receipt paper sizes or documents.
* 💰 **Double-Entry Accounting Foundation**: Automated debit/credit entries posted to Accounts Receivable, Revenue, and Cash Accounts.
* 💻 **Windows Web & Android Compatibility**: Configured for execution across modern desktop web browsers and native Android applications via Capacitor.

## How to Run locally

Simply open `index.html` in any web browser (Chrome, Edge, Firefox).

## Native Build Instructions (Android via Capacitor)

1. Ensure Node.js and Android Studio are installed on your workstation.
2. Initialize and install dependencies:
   ```bash
   npm install
   ```
3. Add the Capacitor Android platform:
   ```bash
   npx cap add android
   ```
4. Sync project web assets:
   ```bash
   npx cap sync
   ```
5. Launch Android Studio to build the native APK/Bundle:
   ```bash
   npx cap open android
   ```
