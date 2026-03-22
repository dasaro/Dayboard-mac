# Dayboard for macOS

Private distribution repository for packaged Dayboard builds.

This repository contains downloadable macOS app builds, release notes, and installation guidance. It does not contain the Dayboard source code.

## What Dayboard Is

Dayboard is a calm, low-friction task board designed for a low-energy, inattentive ADHD workflow.

Core principles:

- fast capture
- low visual noise
- progressive disclosure
- no shame-heavy productivity framing

## Download

Use the private [Releases](https://github.com/dasaro/Dayboard-mac/releases) page to download the latest packaged app.

Current packaged build:

- release: `v2026.03.22-e8756a9`
- asset: `Dayboard-macOS-v2026.03.22-e8756a9.zip`
- source commit: `e8756a9`

## Install

1. Download the latest zip from Releases.
2. Unzip `Dayboard.app`.
3. Move `Dayboard.app` into `/Applications`.
4. Open the app.

If macOS warns that the app is from an unidentified developer, use Finder to right-click the app and choose `Open`.

## Privacy

The packaged app does not ship with local Dayboard data.

Specifically, the release bundle is checked to exclude user data such as:

- task databases
- habit logs
- activity tracking logs

Your Dayboard data remains local on each Mac that runs the app.

## Requirements

- macOS 14 or newer
- Apple Silicon or Intel Mac

## Repository Scope

This repository is for packaged builds only:

- release assets
- install notes
- changelog

The source code stays in a separate private repository; this public repository intentionally exposes only packaged app releases and release notes.
