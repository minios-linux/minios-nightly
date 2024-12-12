# MiniOS Live Nightly Builds

Welcome to the nightly build repository for MiniOS Live!  Here you'll find the most recent automated builds of MiniOS Live, generated daily at **00:00 UTC**.  These builds give you immediate access to the latest MiniOS features and improvements.

## About Nightly Builds

Nightly builds are automatically created ISO images of MiniOS, incorporating the very latest code changes.  While these builds provide access to cutting-edge advancements, they may occasionally be less stable than official releases and might include experimental features.

### Nightly Build Advantages:
- **Daily Generation**: Built automatically every day at **00:00 UTC**.
- **Up-to-the-Minute Updates**: Includes the newest improvements and code changes.
- **Instant Availability**: Download and test the latest build immediately.

## Available Images

| Image Name | Description | Build Status |
|---|---|---|
| `bookworm-xfce-standard-amd64` | Debian 12 (bookworm), XFCE desktop, Standard package variant, 64-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-standard-amd64.yml?style=flat-square) |
| `bookworm-xfce-standard-i386` | Debian 12 (bookworm), XFCE desktop, Standard package variant, 32-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-standard-i386.yml?style=flat-square) |
| `bookworm-xfce-toolbox-amd64` | Debian 12 (bookworm), XFCE desktop, Toolbox package variant, 64-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-toolbox-amd64.yml?style=flat-square) |
| `bookworm-flux-minimum-amd64` | Debian 12 (bookworm), Fluxbox desktop, Minimum package variant, 64-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-flux-minimum-amd64.yml?style=flat-square) |
| `bookworm-flux-minimum-i386` | Debian 12 (bookworm), Fluxbox desktop, Minimum package variant, 32-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-flux-minimum-i386.yml?style=flat-square) |
| `buster-xfce-standard-amd64` | Debian 10 (buster), XFCE desktop, Standard package variant, 64-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/buster-xfce-standard-amd64.yml?style=flat-square) |
| `buster-xfce-standard-i386` | Debian 10 (buster), XFCE desktop, Standard package variant, 32-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/buster-xfce-standard-i386.yml?style=flat-square) |
| `bookworm-xfce-puzzle-amd64` | Debian 12 (bookworm), XFCE desktop, Puzzle package variant, 64-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-puzzle-amd64.yml?style=flat-square) |
| `bookworm-xfce-ultra-amd64` | Debian 12 (bookworm), XFCE desktop, Ultra package variant, 64-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-ultra-amd64.yml?style=flat-square) |
| `sid-xfce-standard-amd64` | Debian Sid (unstable), XFCE desktop, Standard package variant, 64-bit **Debian kernel** image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/sid-xfce-standard-amd64.yml?style=flat-square) |
| `sid-xfce-standard-i386` | Debian Sid (unstable), XFCE desktop, Standard package variant, 32-bit **Debian kernel** image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/sid-xfce-standard-i386.yml?style=flat-square) |


## MiniOS Kernel Details

The MiniOS kernel is similar to the standard Debian kernel but with key differences:  it does *not* include Secure Boot support, and it *does* include built-in support for AUFS and NTFS3.  The Debian Sid images use the standard Debian kernel.

## Download the Latest Nightly Build

The most recent ISO can be downloaded directly from the repository or build pipeline. Check the [Releases](https://github.com/minios-linux/minios-nightly/releases) for the latest version.


## Disclaimer
Nightly builds are intended for testing and early access to new features. These builds may contain bugs or experimental features. For stable and production-ready versions, refer to the official MiniOS releases.


## Feedback and Issues

Found a bug or have suggestions? Open an issue in the repository to let us know. Your feedback helps improve MiniOS Live!

---

Happy testing!