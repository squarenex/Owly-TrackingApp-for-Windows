# Staffy Public Releases

This repository holds **downloadable** Staffy desktop builds only.

Source code stays private:
`https://github.com/kashifg4171/Squarenex_Staff_Tracking_Desktop`

## Downloads (after push)

| File | Platform |
|------|----------|
| [`releases/Staffy-Windows-Setup-latest.exe`](./releases/Staffy-Windows-Setup-latest.exe) | Windows |
| [`releases/Staffy-macOS-latest.dmg`](./releases/Staffy-macOS-latest.dmg) | macOS |

Versioned filenames are also kept under [`releases/`](./releases/).

## How builds get here (no tokens)

1. Build in the private repo with `scripts\build-and-copy-to-public.ps1`
2. Files are copied into this repo’s `releases/` folder
3. **You** `git add` / `commit` / `push` this public repo

See [RELEASE_SETUP.md](./RELEASE_SETUP.md).

### macOS Gatekeeper
Unsigned builds: right-click Staffy → **Open** the first time.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md).
