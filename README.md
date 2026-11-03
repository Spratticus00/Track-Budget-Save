# Track-Budget-Save

<img width="1024" height="1024" alt="Image" src="https://github.com/user-attachments/assets/845a186d-c497-4ba5-826b-3c7bcb90375c" />

Track Budget Save is a native SwiftUI budgeting app for iPhone (iOS 17+). Everything stays on your device: there are no accounts, no bank logins and no analytics, and CSV files are read on the phone and never uploaded.  Check out the User Guide PDF under the new release for a full breakfown of the app!

## Features

### Summary
- Month navigator with net, income and spending
- Six-month chart as bars, pie or line
- Spending by category against monthly budgets
- Goals and rearrangeable widgets
- A hide-amounts button for private viewing
- Current and saved monthly PDF statements

### Activity
- Searchable, filterable transaction list grouped by day with running balances
- Transaction editor with split transactions, photos, comments and notes
- Swipe actions, bulk edit and saved filters

### Accounts
- Checking, savings, cards, loans, cash and brokerage
- Six-month Net Worth trend
- Bank CSV import with duplicate detection and your own merchant rules (your categories always win over the bank's)

### Alerts
- Bill reminders and budget warnings
- Unusual-charge alerts
- A review queue for transactions that need a category

### Partner sharing
- Sync over Tailscale to a self-hosted server
- Air sync between two nearby phones, with no internet needed
- Share and import a data file
- View your own, your partner's, or combined data
- Private items never leave your phone

### Settings
- Recurring transactions, quick add, smarter imports, insights and budget pacing
- Appearance options including background, widget color and an optional bunny companion

### Security and reliability
- PIN and Face ID lock, with a Forgot PIN reset that erases data after two confirmations
- Encrypted backups, restore and hourly safety copies
- Amounts stored as whole cents so totals always add up

## Tech

SwiftUI, Keychain, Multipeer Connectivity and URLSession. An optional Python sync server (easyledger_sync.py) binds to a Tailscale address and uses hashed paths and token authentication.

## Privacy

Your data lives only on your device unless you choose to sync, share or back it up.
