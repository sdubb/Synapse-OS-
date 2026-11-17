# Synapse OS downloads

This repository contains Synapse OS installer files only. The source code and development documentation are in the [main Synapse repository](https://github.com/sdubb/syn).

## Windows

Download [`Synapse-0.0.49-Windows-Setup.exe`](./Synapse-0.0.49-Windows-Setup.exe), run the installer and launch Synapse. Configure a model provider on first use.

## macOS

Run the **Build Synapse macOS installer** workflow in the [source repository](https://github.com/sdubb/syn/actions/workflows/synapse-macos-build.yml). It produces a universal `.dmg` artifact for Apple Silicon and Intel. The current build is unsigned; sign and notarize it with Apple Developer credentials before public distribution.

## Linux

A packaged Linux installer is not published yet. Use the source repository and run the CLI or build the desktop app for your distribution.

## MSI

No MSI package is included in this release because a verified MSI build was not available. It will be added as a separate installer when produced.
