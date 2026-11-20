# theBox

A personal assistant that works on your computer and asks before it acts. You describe a job in plain language; theBox plans the steps, does the work (reading files, running code, writing reports) and asks you before anything sensitive. You choose the model: one on your own computer, or one in your own AWS Bedrock account.

**Website:** https://opaq-ai.github.io/getTheBox/
**Downloads:** [Releases](https://github.com/opaq-ai/getTheBox/releases/latest). Version **0.3.0**: Linux (`.deb`, AppImage) is the tested build; **Mac (Apple Silicon and Intel zips) and Windows (portable zip) are untested builds for testers.** The earlier [0.2.1](https://github.com/opaq-ai/getTheBox/releases/tag/v0.2.1) (offline document analysis) is still available.

This repository holds the public downloads and the website. Anyone can download the releases without an account.

## Install

- **Linux:** `sudo apt install ./theBox-<version>-linux-amd64.deb`, or make the AppImage executable and run it. 0.3.0 upgrades an installed 0.2.x and keeps your settings.
- **macOS (testers):** unzip, drag to Applications, then run `xattr -cr /Applications/theBox.app` once (the app is not signed).
- **Windows (testers):** unzip and run `theBox.exe`; choose More info, then Run anyway. Not safe for sensitive work yet: permission tests fail on Windows (see the release notes).

Verify a download against `SHA256SUMS.txt` in the release.

## Status

0.3.0 is the first release of the new assistant. Not yet there: the recipe store (the ratings, review and reviewer pages show sample data) and models on your computer inside the new assistant. The Mac and Windows builds have never been run on a real machine. "Redacted cloud" masks identifiers it can recognise, not people's or companies' names. The installers are not code-signed. Please [open an issue](https://github.com/opaq-ai/getTheBox/issues) and say which system you use, but do not attach sensitive documents.
