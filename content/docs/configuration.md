---
title: Configuration
weight: 3
---

## Configuring Ion Linux

Ion Linux is highly configurable. This guide covers common configuration tasks.

### Package Management

Ion Linux uses the `ion` package manager:

```bash
# Search for packages
ion search <package>

# Install a package
ion install <package>

# Remove a package
ion remove <package>

# Update package database and upgrade
ion update && ion upgrade
```

### Display Server

Ion Linux ships with Wayland by default. To configure your display settings:

```bash
ion config display
```

### Kernel Parameters

Custom kernel parameters can be set in `/etc/ion/kernel.conf`:

```bash
sudo ion config kernel
```
