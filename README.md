# Aesy

This repository maintains Aesy, Aegyce's general-purpose agent. Aesy executes plans delegated by Requirement when no specialized agent matches.<br>
<sub>本仓库维护 Aegyce 的通用 Agent Aesy。未匹配到领域 Agent 时，Aesy 执行 Requirement 委派的计划。</sub>

Some components of Aesy can also be reused by other AI tools through supported formats and interfaces. These may include skills, MCP integrations, tools, and other capabilities.<br>
<sub>Aesy 中的部分组件也可通过相应格式与接口供其他 AI 工具复用，可包括 Skill、MCP 集成、工具及其他能力。</sub>

The `aesy` plugin currently includes [computer-technical-language](skills/computer-technical-language/SKILL.md), a skill for writing and reviewing precise computer technical language.<br>
<sub>`aesy` 插件当前包含 [computer-technical-language](skills/computer-technical-language/SKILL.md)，用于编写和审查准确、清晰的计算机技术表达。</sub>

```text
plugin.json
skills/
└── computer-technical-language/
    └── SKILL.md
LICENSE
COMMERCIAL-LICENSE.md
```

Reusable components are distributed through [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) and can also be accessed directly from this repository through the receiving tool's supported interfaces.<br>
<sub>可复用组件通过 [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) 分发，也可从本仓库直接获取，通过使用方支持的接口接入。</sub>

Original materials are licensed under [CC BY-NC 4.0](LICENSE). Commercial use requires [separate written permission](COMMERCIAL-LICENSE.md).<br>
<sub>原创内容采用 [CC BY-NC 4.0](LICENSE) 许可，商业用途须取得[单独书面授权](COMMERCIAL-LICENSE.md)。</sub>
