# WhiteDragon Marketplace

精选的 Claude Code 插件，涵盖技能、工作流程和生产力工具。

## 安装

将此市场添加到 Claude Code：

**方法1**

在 `claud code` 命令行里:
```
/plugin
```

- 选择 `3. Add marketplace`
- 输入 `white-dragon-core/claude-code-marketspace` 或 `https://github.com/white-dragon-core/claude-code-marketspace` 或 `git@github.com:white-dragon-core/claude-code-marketspace.git`
    - 将会 clone 仓库到 `~/.claude` 目录
    - 都试试, 有概率失败.
    - 确认代理开启
- 安装完毕后, 进入插件选择界面
- 按下 `空格` 选中待安装插件
- 全部选中
- 按下 `i` 等待安装完毕.

**方法2**
在 `claud code` 命令行里:
```
/plugin marketplace add white-dragon-core/claude-code-marketspace
```

然后在下面的可用插件里, 获取指令, 手工安装.

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


## 验证

安装成功后, 启动 `claude code`.
- 询问 `密码是什么`
- 回答 `天王盖地虎,武松三十五`

**注意**
`/plugin` 后, 有个选项 `2. Manage and uninstall plugins`, 可以开启或关闭插件, 需要关注插件状态.