# Aesy

Aesy is Aegyce's general-purpose agent, executing plans delegated by Requirement when no specialized agent matches. This repository maintains its reusable capabilities for AI tools.<br>
<sub>Aesy 是 Aegyce 的通用 Agent，在未匹配到领域 Agent 时执行 Requirement 委派的计划。本仓库维护其可供不同 AI 工具复用的能力。</sub>

The `aesy` plugin currently includes [computer-technical-language](skills/computer-technical-language/SKILL.md), a skill for writing and reviewing precise computer technical language.<br>
<sub>`aesy` 插件当前包含 [computer-technical-language](skills/computer-technical-language/SKILL.md)，用于编写和审查准确、清晰的计算机技术表达。</sub>

```text
plugin.json
skills/
└── computer-technical-language/
    ├── SKILL.md
    └── agents/openai.yaml
LICENSE
COMMERCIAL-LICENSE.md
```

Access the package through [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace), or load individual skills through your AI tool's skill interface. Skill instructions can also be supplied as task context.<br>
<sub>通过 [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) 获取能力包，或通过所用 AI 工具的 Skill 接口加载单项技能；也可将技能指令作为任务上下文使用。</sub>

Original materials are licensed under [CC BY-NC 4.0](LICENSE). Commercial use requires [separate written permission](COMMERCIAL-LICENSE.md).<br>
<sub>原创内容采用 [CC BY-NC 4.0](LICENSE) 许可，商业用途须取得[单独书面授权](COMMERCIAL-LICENSE.md)。</sub>
