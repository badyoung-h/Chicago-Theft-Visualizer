# 贡献指南 | Contributing Guide

感谢你对 **Chicago Theft Visualizer** 项目感兴趣！我们欢迎任何形式的贡献，无论是修复 Bug、改进文档，还是增加新功能。

为了保持项目代码库的整洁和可维护性，请遵循以下指南。

## 🛠️ 贡献流程 | Contribution Process

### 1. Fork 并克隆项目

点击 GitHub 页面右上角的 **Fork** 按钮，将项目复制到你的账号下，然后克隆到本地：

```bash
git clone https://github.com/你的用户名/Chicago-Theft-Visualizer.git
```

### 2. 创建特性分支

在开始编写代码前，请创建一个专门的分支：

```bash
git checkout -b feature/your-feature-name
```

### 3. 本地开发与测试

- 确保你已经按照 [README.md](README.md) 中的说明配置好了本地开发环境。
- 在提交代码前，请确保项目能够正常运行，没有明显的错误。

### 4. 提交更改

```bash
git add .
git commit -m "feat: 增加 XXX 功能"
```

### 5. 推送并创建 Pull Request (PR)

将分支推送到你的仓库并点击 **New Pull Request**。

***

## 💡 PR 最佳实践建议 | PR Best Practices

为了提高代码审查效率，我们强烈建议遵循以下原则：

### **🚀 每次 PR 仅增加一个功能 (One Feature per PR)**

- **保持原子化**：请确保每一个 Pull Request 只包含一个独立的功能或修复。
- **如果你有多个功能要增加**：请分多次创建不同的分支，并分别发起多个 PR。

### **📝 提交信息规范**

推荐使用简单的前缀来标识你的提交类型：

- `feat:` 新功能 (New feature)
- `fix:` 修复 Bug (Bug fix)
- `docs:` 仅文档修改 (Documentation only)
- `style:` 格式化、缺失分号等（不影响代码运行的修改）
- `refactor:` 代码重构（既不是修复 Bug 也不是新增功能）

***

## 📜 行为准则

- 请保持礼貌与尊重。
- 在提交涉及界面改动的 PR 时，建议在说明中附上截图。

感谢你的贡献！🙌
