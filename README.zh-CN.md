# AI Formula Output Rules 中文说明

这是一个面向两个环境的公式输出规则仓库：

- `Codex App`
- `Claude Code CLI`

仓库提供一个可安装的 `Codex App` skill，以及一份可直接复制到
`Claude Code CLI` 的规则片段。公开范围保持很窄，只覆盖公式渲染、
prose 与 equation 的边界、公式编号，以及避免溢出的布局规则。

## 仓库交付物

- 可安装 skill：
  [codex-app-formula-output-rules](./codex-app-formula-output-rules)
- 可复制 CLI 文件：
  [claude-code-cli/CLAUDE.formula-rules.md](./claude-code-cli/CLAUDE.formula-rules.md)
- 配套引用文件：
  共享原则、`Codex App` 规则、source trace

## 安装 / 使用

- `Codex App`：从本仓库路径 `codex-app-formula-output-rules` 安装
  skill
- `Claude Code CLI`：把
  `claude-code-cli/CLAUDE.formula-rules.md` 复制或合并到本地
  `CLAUDE.md`

## 覆盖范围

- 公式渲染规则
- prose 和 equation 的边界规则
- 公式编号与布局规则
- `Codex App` 与 `Claude Code CLI` 的环境分流
- 尽量语言无关的数学表达规则；必要时只本地化 prose 里的引用词

## 仓库结构

- `codex-app-formula-output-rules/`：可安装的 `Codex App` skill
- `codex-app-formula-output-rules/references/`：公开引用规则子集
- `claude-code-cli/`：写入本地 `CLAUDE.md` 的最小 CLI 片段

英文：

- [README.md](./README.md)
