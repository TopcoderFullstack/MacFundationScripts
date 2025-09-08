# MacFundationScripts

A collection of automated scripts for macOS development environment setup and Next.js project generation.

## Overview

This repository provides essential automation scripts for developers working on macOS, including environment configuration tools and modern web development project generators.

## Directory Structure

### 📁 ENV - Environment Configuration
Contains scripts for setting up and managing development environments on macOS.

- **install** - Installs and configures development environment
- **uninstall** - Removes installed environment configurations
- **gh.bin** - One-click GitHub configuration (SSH keys, user settings)

[More details](./ENV/README.md) | [中文文档](./ENV/README_CN.md)

### 📁 NEXT - Next.js Project Generator
Contains scripts for generating modern full-stack Next.js applications.

- **run** - Creates a complete Next.js project with:
  - Shadcn/UI components
  - Supabase integration
  - Drizzle ORM
  - ESLint + Prettier
  - Husky + lint-staged

[More details](./NEXT/README.md) | [中文文档](./NEXT/README_CN.md)

## Quick Start

### Prerequisites
- macOS operating system
- Administrator privileges
- Node.js and npm/yarn installed (for NEXT scripts)
- Stable internet connection

### Installation

1. Clone this repository:
```bash
git clone [repository-url]
cd MacFundationScripts
```

2. Set execution permissions:
```bash
chmod +x ENV/install ENV/uninstall ENV/gh.bin
chmod +x NEXT/run
```

3. Run desired scripts:
```bash
# Configure development environment
./ENV/install

# Generate Next.js project
./NEXT/run
```

## Features

✅ **Automated Environment Setup** - Quick configuration of development tools  
✅ **GitHub Integration** - One-click SSH and user configuration  
✅ **Modern Stack** - Next.js with latest tools and best practices  
✅ **Code Quality** - Pre-configured linting and formatting  
✅ **Type Safety** - TypeScript and Drizzle ORM integration  

## Requirements

- macOS 10.15 or later
- Administrator privileges for script execution
- Node.js 18+ (for Next.js projects)
- Git installed

## Support

For issues, questions, or contributions, please open an issue in the repository.

## License

**CC BY-NC-SA 4.0**

This project is licensed under Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

### Key Points:
- ✅ Personal and non-commercial use allowed
- ✅ Modification and distribution allowed
- ❌ Commercial use prohibited
- ❌ Prohibited for use in any form of bootcamp (except those owned by TOPCODER FULLSTACK LTD PTY)
- ⚠️ Must attribute original author
- ⚠️ Derivative works must use same license

See [LICENSE](./LICENSE) for full details.

## Author

MacFundationScripts Contributors

---

Copyright © 2025 MacFundationScripts. All rights reserved.