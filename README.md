# Vaani Download

This repository is the public distribution home for Vaani.

It is intentionally separate from the private source repository. Public downloads, release notes, and user-facing docs live here. The full Vaani source code stays private.

## What This Repository Contains

- Windows installer release links
- public documentation
- release notes and changelog
- website-linked download references

## Latest Public Release

Use the Releases page for the latest stable Windows installer:

- [Vaani Releases](https://github.com/SkyBotsDeveloper/Vaani-Download/releases)

Current installer naming can stay consistent with the app build, for example:

- `vaani-ai-1.2.3-setup.exe`
- installer checksum in [`SHA256SUMS.txt`](./SHA256SUMS.txt)

## Recommended Public Repo Scope

Keep this repository limited to:

- docs
- changelog
- release notes
- GitHub Releases assets

Do not keep these here:

- application source code
- secrets
- API keys
- private build scripts
- development-only config

## Docs

- [Installation Guide](./docs/installation.md)
- [Downloads Policy](./docs/downloads.md)
- [Website Sync Notes](./docs/website.md)

## Private Source Repo

The main Vaani app source should be stored in a separate private repository. This public repo exists only for release distribution and docs.
