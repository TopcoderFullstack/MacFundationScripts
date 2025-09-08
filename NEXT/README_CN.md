# NEXT - Next.js项目生成器

## 简介
本目录包含用于快速生成现代化Next.js全栈项目的自动化脚本。

## 项目技术栈
生成的项目将包含以下技术栈：

- **Next.js** - React框架
- **Shadcn/UI** - UI组件库
- **Supabase** - 后端即服务
- **Drizzle** - TypeScript ORM工具
- **Husky** - Git钩子管理
- **lint-staged** - 暂存文件检查
- **ESLint** - 代码质量检查
- **Prettier** - 代码格式化

## 脚本说明

### run - 项目生成脚本
自动创建并配置一个完整的Next.js + Shadcn/UI + Supabase + Drizzle项目，包含代码质量管理工具。

## 使用方法

### 执行前准备
如果脚本无法执行，请先设置执行权限：
```bash
chmod +x ./run
```

### 执行脚本
生成项目：
```bash
./run
```

## 项目特性
- ✅ 预配置的Next.js项目结构
- ✅ Shadcn/UI组件集成
- ✅ Supabase数据库和认证
- ✅ Drizzle ORM配置
- ✅ Git提交前自动代码检查
- ✅ ESLint代码质量保证
- ✅ Prettier自动格式化
- ✅ Husky + lint-staged集成

## 注意事项
- 脚本需要管理员权限才能正确执行
- 首次使用前请确保脚本具有可执行权限
- 确保已安装Node.js和npm/yarn
- 需要稳定的网络连接以下载依赖

## 许可协议
使用本目录下的脚本需要遵守项目许可协议：
**License: CC BY-NC-SA 4.0**

详细协议内容请参见项目根目录下的LICENSE文件。

### 协议要点
- ✅ 允许个人和非商业使用
- ✅ 允许修改和分发
- ❌ 禁止商业用途
- ❌ 禁止任何形式的训练营使用（仅授权TOPCODER FULLSTACK LTD PTY所属的训练机构）
- ⚠️ 必须注明原作者
- ⚠️ 衍生作品必须使用相同协议