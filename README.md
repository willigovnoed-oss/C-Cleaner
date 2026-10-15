SUPPORTED BY OPENAI COMPANY #C-Cleaner

**A lightweight Windows junk file cleaner with a simple graphical interface.**

C-Cleaner helps you reclaim disk space on your C: drive by clearing out unnecessary junk files. It is a single portable `.exe` - no installer, no setup, no bloat.

## Features

- Simple point-and-click GUI
- Portable single executable - nothing to install
- Free and open source (MIT)

## Download

Grab the latest `C-Cleaner.exe` from the [Releases page](https://github.com/willigovnoed-oss/C-Cleaner/releases/latest).

## Usage

1. Download `C-Cleaner.exe`.
2. Double-click to run it.
3. Review what will be cleaned, then confirm.

## Requirements

- Windows 10 / 11 (64-bit)

## Verify your download

SHA-256 of `C-Cleaner.exe` (v1.0.0):

```
af9e3e84d3bf5461ff219389810c5c2a844764d4415f0e2c2553ffd9866b7915
```

Check it in PowerShell:

```powershell
Get-FileHash .\C-Cleaner.exe -Algorithm SHA256
```

## Notes

- The executable is built with Python and PyInstaller. Because it is not code-signed, Windows SmartScreen or some antivirus tools may show a warning (a common false positive for PyInstaller apps). Click **More info -> Run anyway** if you trust the source and the hash matches.
- Deleted files may not be recoverable. Always review what is selected before cleaning and keep backups of anything important.

## Disclaimer

Provided "as is", without warranty of any kind. Use at your own risk. This project is not affiliated with or endorsed by Piriform, Avast or CCleaner.

## License

[MIT](LICENSE)
