# Smonitor

VB6 Security Event Monitor (`SMonitor.exe`, Daedalus): polls the Security event log for selected IDs (logon/logoff/lockout/audit clear/etc.) on an interval and can alert, email, or page; main form redacted to `.example`. Open `Smonitor.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `SMonitor` (`Smonitor.vbp`) | VB6 | WinForms exe | Poll Security log and notify on watched events |
