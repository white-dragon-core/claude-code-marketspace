# WhiteDragon Marketplace

精选的 Claude Code 插件，涵盖技能、工作流程和生产力工具。

## 安装

将此市场添加到 Claude Code：

```bash
/plugin marketplace add white-dragon-core/claude-code-marketspace
```

## 可用插件

### Superpowers (核心)

**描述：** 核心技能库，包含 TDD、调试、协作模式和经过验证的技术

**类别：** 测试、调试、协作、元

**安装：**
```bash
/plugin install superpowers@white-dragon-marketplace
```

**您将获得：**
- 20+ 经过实战测试的技能
- `/brainstorm`、`/write-plan`、`/execute-plan` 命令
- 用于发现的技能搜索工具
- SessionStart 上下文注入

**仓库：** https://github.com/obra/superpowers

---

### Elements of Style

**描述：** 基于威廉·斯特伦克（William Strunk Jr.）的《风格的要素》（1918）的写作指南

**类别：** 写作、文档、参考

**安装：**
```bash
/plugin install elements-of-style@white-dragon-marketplace
```

**您将获得：**
- `writing-clearly-and-concisely` 技能
- 完整的 1918 参考文本（~12k tokens）
- 清晰、简洁写作的全部 18 条规则
- 语法、标点和写作指导

**仓库：** https://github.com/obra/the-elements-of-style

---

### Superpowers Developing for Claude Code

**描述：** 用于开发 Claude Code 插件、技能、MCP 服务器和扩展的技能和资源。包含全面的官方文档和自动更新机制。

**类别：** 开发、文档、工具

**安装：**
```bash
/plugin install superpowers-developing-for-claude-code@white-dragon-marketplace
```

**您将获得：**
- 开发 Claude Code 插件的技能和资源
- 开发技能、MCP 服务器和扩展的工具
- 全面的官方文档
- 自动更新机制

**仓库：** https://github.com/obra/superpowers-developing-for-claude-code

---

### Bevy Framework for Claude Code

**描述：** 用于开发 Bevy Framework 插件、技能、MCP 服务器和扩展的工具。包含全面的官方文档和自动更新机制。

**类别：** 开发、框架、游戏引擎

**安装：**
```bash
/plugin install bevy-framework-for-claude-code@white-dragon-marketplace
```

**您将获得：**
- 开发 Bevy Framework 插件的工具
- 开发技能、MCP 服务器和扩展的资源
- 全面的官方文档
- 自动更新机制

**仓库：** https://github.com/white-dragon-bevy/claude-bevy

---

### Test Cloud Testez

**描述：** 用于测试和调试代码的工具。包含全面的官方文档和自动更新机制。

**类别：** 测试、调试、工具

**安装：**
```bash
/plugin install test-cloud-testez@white-dragon-marketplace
```

**您将获得：**
- 测试和调试代码的工具
- 全面的官方文档
- 自动更新机制

**仓库：** https://github.com/white-dragon-core/test-cloud-testez

---

## 市场结构

```
superpowers-marketplace/
├── .claude-plugin/
│   └── marketplace.json       # 插件目录
└── README.md                  # 本文件
```

## 支持

- **问题反馈**: https://github.com/white-dragon-core/claude-code-marketspace/issues
- **核心插件**: https://github.com/obra/superpowers

## 许可证

市场元数据：MIT 许可证

各个插件：请参阅各自插件的许可证
