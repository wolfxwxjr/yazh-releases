# Yazh — Studio Assistant

**A calm, offline studio for private music teachers.** Students, lessons,
attendance, fees, progress and practice tools in one quiet Windows app. No
account, no subscription, no telemetry.

[**⬇ Download the latest Windows build**](https://github.com/nk12Kumar/yazh-releases/releases/latest)

![Yazh dashboard](screenshots/dashboard.png)

`Portable .exe` · `Offline` · `No demo data` · `No sign-in`

---

## Download

| File | Use it for |
|---|---|
| **`Yazh-1.18.0-portable.exe`** | Windows — available now |
| **macOS DMG** | Delayed — hosted Mac runner unavailable |
| **`SHA256SUMS.txt`** | Checksums |

Double-click the `.exe`. There is no installer. A short welcome asks for your
name, studio name, region, time zone and currency, then opens your empty studio.
There are no demo students.

> **Windows warning:** the app is not code-signed. SmartScreen may say
> **“Windows protected your PC”** — click **More info → Run anyway**.
>
> **Mac:** right-click **Yazh** → **Open** the first time.

## Start here

1. Open the app.
2. Enter your studio details.
3. Add your first student.
4. Schedule a lesson or record a payment.

![Students](screenshots/students.png)

## What is inside

- **Students** — profiles, instrument, level, fees, classes left, search and archive.
- **Schedule** — month/week/day, weekly or fortnightly lessons, rescheduling,
  meeting links and time-zone aware lesson times.
- **Attendance** — present, absent, cancelled, rescheduled or completed; make-up credits.
- **Payments** — tuition, individual lessons, packages, part-payments, balances,
  PDF receipts and monthly fees due.
- **Progress** — editable 11-stage Carnatic path, custom stages, revision flags,
  dated notes and printable student reports.
- **Reports** — revenue, attendance, growth, outstanding fees, lessons and
  countries, with PDF and CSV export.
- **Compositions** — Pallavi–Swarakalpana sections, lyrics, notation grid,
  printable PDF, audio/PDF attachments and student assignment.
- **Recordings** — record or upload takes, add feedback, compare takes and download.
- **Practice tools** — tuner, metronome, tala simulator, shruti box, practice
  timer, scale library, dictionary and quick recorder.
- **Raga explorer** — 72 Melakarta ragas, janya ragas, prayogas and gamaka notes.
- **Teaching assistant** — offline by default; optional Ollama or Gemini.
- **Settings** — themes, text size, volume, language, backups, restore and update check.

![Practice tools](screenshots/tools.png)

> **Materials were removed in 1.18.0.** The section did not work reliably enough
> to keep; the studio stays focused on lessons, fees and progress.

**Full walkthrough: [Yazh User Guide](GUIDE.md).**

## Your data

| Platform | Folder |
|---|---|
| Windows | `%APPDATA%\Yazh\data` |
| macOS | `~/Library/Application Support/Yazh/data` |

Everything stays on your computer. The local API is bound to `127.0.0.1`; there
is no cloud account, no telemetry and no third-party runtime request. Yazh keeps
an automatic daily backup of the last 14 copies. Backup, restore and full export
are in **Settings → Data**.

Replacing the `.exe` keeps your data folder. Upgrades migrate in place and save a
dated database snapshot before changing the schema.

## Version 1.18.0

- **All demo students and placeholder data removed.** The app starts clean.
- **Materials section removed completely** — navigation, page, shortcuts and API.
- **First-run setup** asks for the teacher and studio details before the dashboard.
- **Left navigation scrolls**, so every section is reachable on a short screen.
- **Fixed** mobile overflow on the student and progress screens.
- **Fixed** local composition audio/PDF links in the desktop shell.
- **Fixed** packaged update-check version reporting.
- **Faster dashboard** — heavy pages load on demand.

The Windows app is available now. The macOS build is delayed by GitHub's hosted
runner and will be added when it runs.

## Verify a download

```powershell
Get-FileHash .\Yazh-1.18.0-portable.exe -Algorithm SHA256
```

Compare with `SHA256SUMS.txt`.

## A note on source

This repository contains **downloads and user documentation only**. The source
repository is private, maintained by the author. Yazh is MIT-licensed.

---

Yazh · Studio Assistant · 1.18.0
