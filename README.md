# MiniOS Live Testing Builds

Welcome to the test build repository for MiniOS Live! Here you'll find recent builds of MiniOS Live, intended for testing and to provide access to the latest MiniOS features and improvements.

## About Test Builds

These builds create ISO images of MiniOS, incorporating recent code changes. While these builds provide access to cutting-edge advancements, they may occasionally be less stable than official releases and might include experimental features. These are for testing purposes and to allow users early access to upcoming changes.

### Test Build Advantages:
- **Recent Updates**: Includes recent improvements and code changes.
- **Early Access**: Download and test the latest build before wider release.

## Available Images

| Image Name | Description | Build Status |
|---|---|---|
| `bookworm-xfce-standard-amd64` | Debian 12 (bookworm), XFCE desktop, Standard package variant, 64-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-standard-amd64.yml?style=flat-square) |
| `bookworm-xfce-standard-i386` | Debian 12 (bookworm), XFCE desktop, Standard package variant, 32-bit MiniOS kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-standard-i386.yml?style=flat-square) |
| `bookworm-xfce-toolbox-amd64` | Debian 12 (bookworm), XFCE desktop, Toolbox package variant, 64-bit Standard Debian kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-toolbox-amd64.yml?style=flat-square) |
| `bookworm-xfce-ultra-amd64` | Debian 12 (bookworm), XFCE desktop, Ultra package variant, 64-bit Standard Debian kernel image | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/minios-linux/minios-nightly/bookworm-xfce-ultra-amd64.yml?style=flat-square) |


## MiniOS Kernel Details

The `Standard` MiniOS images include the MiniOS kernel. This kernel is similar to the standard Debian kernel but with key differences: it does *not* include Secure Boot support, and it *does* include built-in support for AUFS. Drivers for some Realtek and Broadcom wireless adapters are included in all 64-bit builds. **AUFS is a union filesystem that excels in live environments by enabling system modifications and persistence on read-only media. A key feature of AUFS is its support for hotplugging squashfs images, allowing for dynamic loading and unloading of entire compressed filesystems without requiring a reboot.**

The `Toolbox` and `Ultra` variants use the standard Debian kernel: it *does* include Secure Boot support, and it does *not* include built-in support for AUFS.

## Download the Latest Test Build

The most recent ISO can be downloaded directly from the repository or build pipeline. Check the [Releases](https://github.com/minios-linux/minios-nightly/releases) for the latest version.

## Disclaimer

These test builds are intended for **testing purposes only**. They may contain bugs or experimental features and should not be used in production environments. For stable and production-ready versions, refer to the official MiniOS releases.

## Feedback and Issues

Found a bug or have suggestions? Open an issue in the repository to let us know. Your feedback helps improve MiniOS Live!

---

Happy testing!