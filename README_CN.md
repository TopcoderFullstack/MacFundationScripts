# MacFundationScripts

macOS开发环境配置和Next.js项目生成自动化脚本集合。

## 概述

本仓库为macOS开发者提供必要的自动化脚本，包括环境配置工具和现代Web开发项目生成器。

## 目录结构

### 📁 ENV - 环境配置
包含用于设置和管理macOS开发环境的脚本。

- **install** - 安装和配置开发环境
- **uninstall** - 移除已安装的环境配置
- **gh.bin** - 一键配置GitHub（SSH密钥、用户设置）

[查看详情](./ENV/README_CN.md) | [English](./ENV/README.md)

### 📁 NEXT - Next.js项目生成器
包含用于生成现代全栈Next.js应用的脚本。

- **run** - 创建完整的Next.js项目，包含：
  - Shadcn/UI组件
  - Supabase集成
  - Drizzle ORM
  - ESLint + Prettier
  - Husky + lint-staged

[查看详情](./NEXT/README_CN.md) | [English](./NEXT/README.md)

## 快速开始

### 前置要求
- macOS操作系统
- 管理员权限
- 已安装Node.js和npm/yarn（用于NEXT脚本）
- 稳定的网络连接

### 安装

1. 克隆此仓库：
```bash
git clone [repository-url]
cd MacFundationScripts
```

2. 设置执行权限：
```bash
chmod +x ENV/install ENV/uninstall ENV/gh.bin
chmod +x NEXT/run
```

3. 运行所需脚本：
```bash
# 配置开发环境
./ENV/install

# 生成Next.js项目
./NEXT/run
```

## 特性

✅ **自动化环境设置** - 快速配置开发工具  
✅ **GitHub集成** - 一键SSH和用户配置  
✅ **现代技术栈** - 使用最新工具和最佳实践的Next.js  
✅ **代码质量** - 预配置的代码检查和格式化  
✅ **类型安全** - TypeScript和Drizzle ORM集成  

## 系统要求

- macOS 10.15或更高版本
- 脚本执行需要管理员权限
- Node.js 18+（用于Next.js项目）
- 已安装Git

## 支持

如有问题、疑问或想要贡献，请在仓库中提交issue。

## 许可证

**CC BY-NC-SA 4.0**

本项目采用知识共享署名-非商业性使用-相同方式共享4.0国际许可证。

### 要点：
- ✅ 允许个人和非商业使用
- ✅ 允许修改和分发
- ❌ 禁止商业用途
- ❌ 禁止任何形式的训练营使用（仅授权TOPCODER FULLSTACK LTD PTY所属的训练机构）
- ⚠️ 必须注明原作者
- ⚠️ 衍生作品必须使用相同许可证

详见 [LICENSE](./LICENSE) 文件。

## 作者

MacFundationScripts贡献者

---

版权所有 © 2025 MacFundationScripts。保留所有权利。