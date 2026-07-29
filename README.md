# Staffy Public Releases

This repository publishes **downloadable Staffy desktop apps only**.

Source code stays private in:
`https://github.com/kashifg4171/Squarenex_Staff_Tracking_Desktop`

## What you get here

Each GitHub Release attaches **only**:

| File | Platform |
|------|----------|
| `Staffy-Windows-Setup-vX.Y.Z+N.exe` | Windows installer |
| `Staffy-macOS-vX.Y.Z+N.dmg` | macOS disk image |

No source code, no `.zip` of Dart/Flutter project, no secrets.

## How releases are created

1. Push (or manual workflow) on the **private** desktop repo.
2. CI builds `.exe` + `.dmg`.
3. CI creates a Release **in this public repo** and uploads only those two files.

## Download

Open **Releases** on this repo and grab the latest `.exe` or `.dmg`.

### macOS Gatekeeper
Unsigned builds: right-click Staffy → **Open** the first time.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md).
