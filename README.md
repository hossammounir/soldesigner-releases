# Sōldesigner releases

Sōldesigner is Sōlrein's hourly PV system simulator for research and teaching, for Windows 10 and 11 (64-bit).

**Download it from [solrein.co/soldesigner](https://solrein.co/soldesigner).** That page always offers the latest version.

This repository holds only the published installers. Installed copies of Sōldesigner check it for new versions and offer to update themselves.

Each release has two files:

| File | What it is |
|---|---|
| `Soldesigner-Setup.exe` | The installer. It installs for the current user and needs no administrator rights. |
| `Soldesigner-Setup.exe.sha256` | The installer's SHA-256 checksum. |

To check a download in PowerShell, run:

```
(Get-FileHash .\Soldesigner-Setup.exe -Algorithm SHA256).Hash
```

The result should match the checksum file.
