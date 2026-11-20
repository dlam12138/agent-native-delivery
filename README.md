# Agent-Native Delivery

一个用于仓库文档审计和 Agent 指令维护的 Skill。它帮助你从源码、配置和现有记录核对项目事实，再维护分层 `AGENTS.md`、架构与接口文档，并交付可复核的验证结果。

## 安装

在 Codex 中使用以下提示安装。安装完成后调用 `$agent-native-delivery`。

```text
使用 $skill-installer 安装 https://github.com/dlam12138/agent-native-delivery/tree/main/skills/agent-native-delivery
```

## 使用

```text
用 $agent-native-delivery 审计当前仓库的 AGENTS.md 和架构文档，找出和实现冲突的地方。先给我审计结果。
```

也可用于维护一个模块的指令、核查 Agent 的规则加载方式，或整理文档更新的验证与交接。[查看 SKILL.md](skills/agent-native-delivery/SKILL.md)

## 来源与许可

工作流提炼自 UPC Pocket 的 Agent 手册、兼容记录和文档建设审计，沿用原项目的 MIT 许可及版权声明。[原始文档](https://github.com/dlam12138/UPCPocket/tree/f690c69777b1546c98cda4203e6c499f6250e803/docs/agent-native) · [MIT License](LICENSE)
