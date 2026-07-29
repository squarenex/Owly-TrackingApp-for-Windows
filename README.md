# Staffy Public Releases

This repository is the public distribution channel for Staffy desktop builds.

## Purpose

- Publish release notes and downloadable binaries.
- Keep source code private in the private repository.

## Private Source Repository

- Source code is maintained in:
  `https://github.com/kashifg4171/Squarenex_Staff_Tracking_Desktop` (private)

## What is stored here

- Release notes (`CHANGELOG.md`)
- Download artifacts (`releases/`), such as:
  - `.exe`
  - `.msi`
  - `.zip`
  - checksums (`.sha256`, `.txt`)

## What is not stored here

- Application source code
- Internal scripts, keys, or secrets
- Environment files (`.env`)

## Release process

1. Build in the private source repository.
2. Export release binaries.
3. Add binaries under `releases/<version>/`.
4. Update `CHANGELOG.md`.
5. Create a GitHub Release in this public repository and attach binaries.

