# theBox

Analyse sensitive documents with an AI that never leaves your computer. theBox (the app is named **DocAnalyze**) reads your PDFs, Word and Excel files, does the calculations with real code and writes the report, using a language model that runs entirely on your own machine.

**Website:** https://opaq-ai.github.io/getTheBox/
**Downloads:** [Releases](https://github.com/opaq-ai/getTheBox/releases/latest) (Linux `.deb` and AppImage, macOS Apple Silicon and Intel)

This repository holds the public downloads and the website. Anyone can download the releases without an account.

## Install

- **Linux:** `sudo apt install ./DocAnalyze-<version>-linux-amd64.deb`, or make the AppImage executable and run it.
- **macOS:** unzip, drag to Applications, then run `xattr -cr /Applications/DocAnalyze.app` once (the app is not signed yet).

Verify a download against `SHA256SUMS.txt` in the release.

## Status

Early release. The Linux build has been run end to end; the macOS builds have not yet been run on a real Mac. Neither is code-signed. Please [open an issue](https://github.com/opaq-ai/getTheBox/issues) and say which system you use, but do not attach sensitive documents.
