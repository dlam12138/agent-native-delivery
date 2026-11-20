<h1 align="center">Agent-Native Delivery</h1>

<p align="center">
  核对仓库文档与实际实现，厘清 Agent 指令的作用域，交付可复核的证据。
</p>

<p align="center">
  <a href="#快速开始"><strong>快速开始</strong></a>
  · <a href="#使用场景">使用场景</a>
  · <a href="skills/agent-native-delivery/SKILL.md">查看 Skill</a>
</p>

## 快速开始

### 安装

在 Codex 中发送这条安装提示。

```text
使用 $skill-installer 安装 https://github.com/dlam12138/agent-native-delivery/tree/main/skills/agent-native-delivery
```

### 试用

打开目标仓库，在 Codex 中发送这条审计提示。

```text
用 $agent-native-delivery 只读审计当前仓库的 AGENTS.md 和架构文档。
列出与实际实现冲突的地方，并附上证据位置。
```

> [!NOTE]
> 只读审计报告发现和证据。修订文档须在本次任务的授权范围内进行。

## 使用场景

| 任务 | 交付结果 |
| --- | --- |
| 整理根与局部 `AGENTS.md` | 核对指令的作用域、冲突及应保留的规则 |
| 同步架构与接口文档 | 对照源码、配置和调用方，定位需要更新的表述 |
| 核查 Agent 的规则加载 | 记录会话中有证据支持的规则来源，必要时给出显式读取路径 |
| 交接文档变更 | 列出实读依据、实际验证的范围和待核查事项 |

详细流程见两份参考文档。[仓库审计与文档结构](skills/agent-native-delivery/references/repository-audit.md) · [验证与交接](skills/agent-native-delivery/references/verification-and-handoff.md)

## 来源与许可

工作流提炼自 UPC Pocket 的 Agent 手册、兼容记录和文档建设审计，沿用原项目的 MIT 许可及版权声明。[原始文档](https://github.com/dlam12138/UPCPocket/tree/f690c69777b1546c98cda4203e6c499f6250e803/docs/agent-native) · [MIT License](LICENSE)
