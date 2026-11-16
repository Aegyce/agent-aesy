# Aesy

[![English (current)](https://img.shields.io/badge/English-8C2F39?style=flat-square)](README.md)

This repository maintains Aesy, Aegyce's general-purpose agent. When Requirement cannot find a specialized agent suited to the current task, it delegates the plan to Aesy for execution.

## Available capabilities

### Skills

- [computer-technical-language](plugins/computer-technical-language/skills/computer-technical-language/SKILL.md): Draft, revise, and review computing documentation, code comments, and technical responses, using consistent terminology and clear wording while preserving facts, conditions, and uncertainty.

- [studio-portrait](plugins/studio-portrait/skills/studio-portrait/SKILL.md): Create and refine high-end studio business portraits from original photos while preserving facial features and expressions, standardizing formal suits, studio lighting, and background depth.

### MCP integrations

No MCP integrations are currently provided.

### Tools

No standalone tools are currently provided.

## Component reuse

Other AI tools can use some of Aesy’s components, which may include skills, MCP integrations, tools, and other capabilities. How they are used depends on the formats and interfaces the tool supports.

Reusable components are stored as independently installable capability packages under [plugins/](plugins/), distributed through [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace), and also available directly from this repository.

## License

Original materials are licensed under [CC BY-NC 4.0](LICENSE). Commercial use requires [separate written permission](COMMERCIAL-LICENSE.md).
