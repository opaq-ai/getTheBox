# theBox

A personal assistant that works on your computer and asks before it acts. You describe a job in plain language; theBox plans the steps, does the work (reading files, running code, writing reports) and asks you before anything sensitive. You choose the model: one on your own computer, or one in your own AWS Bedrock account.

**Website:** https://opaq-ai.github.io/getTheBox/
**Downloads:** [Releases](https://github.com/opaq-ai/getTheBox/releases/latest). Version **0.3.0** is Linux only (`.deb` and AppImage). Mac users should use [0.2.1](https://github.com/opaq-ai/getTheBox/releases/tag/v0.2.1) (offline document analysis, Apple Silicon and Intel) for now.

This repository holds the public downloads and the website. Anyone can download the releases without an account.

## Install

- **Linux:** `sudo apt install ./theBox-<version>-linux-amd64.deb`, or make the AppImage executable and run it. 0.3.0 upgrades an installed 0.2.x and keeps your settings.
- **macOS (0.2.1 only):** unzip, drag to Applications, then run `xattr -cr /Applications/theBox.app` once (the app is not signed yet).

Verify a download against `SHA256SUMS.txt` in the release.

## Status

0.3.0 is the first release of the new assistant. Not yet there: the recipe store (the ratings, review and reviewer pages show sample data), models on your computer inside the new assistant, and Mac and Windows builds. "Redacted cloud" masks identifiers it can recognise, not people's or companies' names. The installers are not code-signed. Please [open an issue](https://github.com/opaq-ai/getTheBox/issues) and say which system you use, but do not attach sensitive documents.
