# ENV - Environment Configuration Scripts

## Introduction
This directory contains automated scripts for configuring and managing the development environment.

## Script Description

### install - Installation Script
Used to automatically install and configure various dependencies and tools required for the development environment.

### uninstall - Uninstallation Script
Used to completely uninstall and clean up the environment configuration installed by the install script.

### gh.bin - GitHub One-Click Configuration Script
Used to quickly configure GitHub-related settings, including SSH keys, user information, etc.

## Usage

### Preparation
If the scripts cannot be executed, please set execution permissions first:
```bash
chmod +x ./install
chmod +x ./uninstall
chmod +x ./gh.bin
```

### Execute Scripts

Install environment:
```bash
./install
```

Uninstall environment:
```bash
./uninstall
```

Configure GitHub:
```bash
./gh.bin
```

## Notes
- All scripts require administrator privileges to execute correctly
- Please ensure scripts have executable permissions before first use
- It is recommended to backup important configuration files before execution

## License
Use of scripts in this directory must comply with the project license:
**License: CC BY-NC-SA 4.0**

For detailed license content, please refer to the LICENSE file in the project root directory.

### License Key Points
- ✅ Personal and non-commercial use allowed
- ✅ Modification and distribution allowed
- ❌ Commercial use prohibited
- ❌ Prohibited for use in any form of bootcamp (except those owned by TOPCODER FULLSTACK LTD PTY)
- ⚠️ Must attribute original author
- ⚠️ Derivative works must use the same license