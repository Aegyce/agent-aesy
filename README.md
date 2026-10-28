# Aesy

The capability package for Aesy, Aegyce's general-purpose agent. Aesy executes plans delegated by Requirement when no specialized agent matches.<br>
<sub>Aegyce 通用 Agent Aesy 的能力包。未匹配到领域 Agent 时，Aesy 执行 Requirement 委派的计划。</sub>

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

Install Aesy through [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace). In Codex, select its skill or invoke `$aesy:computer-technical-language`.<br>
<sub>通过 [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) 安装 Aesy。在 Codex 中选择对应 Skill，或使用 `$aesy:computer-technical-language` 调用。</sub>

Original materials are licensed under [CC BY-NC 4.0](LICENSE). Commercial use requires [separate written permission](COMMERCIAL-LICENSE.md).<br>
<sub>原创内容采用 [CC BY-NC 4.0](LICENSE) 许可，商业用途须取得[单独书面授权](COMMERCIAL-LICENSE.md)。</sub>
