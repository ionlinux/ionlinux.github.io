---
title: Installation Guide
weight: 2
---

## Installing Ion Linux

This guide walks you through a full installation of Ion Linux.

### Preparing Installation Media

Download the latest ISO and write it to a USB drive:

```bash
sudo dd if=ionlinux-latest.iso of=/dev/sdX bs=4M status=progress
sync
```

### Boot and Install

1. Boot from the USB drive
2. Select **Install Ion Linux** from the boot menu
3. Follow the on-screen prompts to configure:
   - Language and locale
   - Disk partitioning
   - User account
   - Network settings

### Post-Installation

After installation, update your system:

```bash
ion update
ion upgrade
```
