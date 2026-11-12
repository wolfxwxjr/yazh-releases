# Yazh — Veena Classes · downloads

A calm, offline desktop app for a veena teacher: students, lessons, attendance,
class balances and payments.

**Download the latest version:**
https://github.com/wolfxwxjr/yazh-releases/releases/latest

Pick `Yazh-1.0.0-portable.exe`. There is nothing to install — double-click and
the studio opens.

## First run

Sign in with the demo studio:

- **Email:** `teacher@yazh.app`
- **Password:** `Veena@2026`

Eight fictional students are included so every screen can be tried. All data is
stored on your own computer, in `%APPDATA%\Yazh\data`; nothing is uploaded.

## Windows warning

The app is not code-signed. Windows SmartScreen may say **“Windows protected
your PC”** the first time. Click **More info → Run anyway**. Code-signing
certificates are a paid service; the warning does not mean the file is unsafe.

## Requirements

- Windows 10 or 11, 64-bit
- No internet connection required
- About 120 MB of disk space

## What works in 1.0.0

- Sign-in and private local storage
- Dashboard calculated from your own records
- Students, photos, search and filters
- Classes remaining this month per student
- Month / week / day schedule, recurring lessons, double-booking prevention
- Student-local time while scheduling international lessons
- Attendance: present, absent, cancelled, rescheduled, completed
- Payments in 13 currencies, outstanding balances, PDF receipts
- Carnatic curriculum and progress notes per student
- In-app notifications

Coming next: editable progress, materials library, reports and exports,
settings and backups.

## Verify the download

`SHA256SUMS.txt` in each release lists the checksum. On Windows:

```powershell
Get-FileHash .\Yazh-1.0.0-portable.exe -Algorithm SHA256
```

## Screenshots

![Dashboard](dashboard.png)

More in the main project's `docs/screenshots` history.
