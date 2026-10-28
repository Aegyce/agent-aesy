# Aesy

本仓库维护 Aegyce 的通用 Agent Aesy。未匹配到领域 Agent 时，Aesy 执行 Requirement 委派的计划。<br>
<sub>This repository maintains Aesy, Aegyce's general-purpose agent. Aesy executes plans delegated by Requirement when no specialized agent matches.</sub>

## 当前支持的能力<br><sub>Available capabilities</sub>

### 技能<br><sub>Skills</sub>

- [computer-technical-language](plugins/computer-technical-language/skills/computer-technical-language/SKILL.md)：用于编写、润色和审查计算机技术表达，规范术语与措辞并保留原有事实、条件和不确定性。<br>
  <sub>Write, revise, and review computer technical language with precise terminology while preserving facts, conditions, and uncertainty.</sub>

### MCP 集成<br><sub>MCP integrations</sub>

暂未提供 MCP 集成。<br>
<sub>No MCP integrations are currently provided.</sub>

### 工具<br><sub>Tools</sub>

暂未提供独立工具。<br>
<sub>No standalone tools are currently provided.</sub>

## 组件复用<br><sub>Component reuse</sub>

Aesy 中的部分组件可通过相应格式与接口供其他 AI 工具复用，可包括 Skill、MCP 集成、工具及其他能力。<br>
<sub>Some components of Aesy can be reused by other AI tools through supported formats and interfaces. These may include skills, MCP integrations, tools, and other capabilities.</sub>

可复用组件按可独立安装的能力包，通过 [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) 分发，也可从本仓库直接获取。<br>
<sub>Reusable components are distributed as independently installable capability packages through [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) and are also available directly from this repository.</sub>

- [Aesy:computer-technical-language](plugins/computer-technical-language)：提供计算机技术用语 Skill，可单独安装。<br>
  <sub>Provides the computer technical language skill as an independently installable plugin.</sub>

## 许可<br><sub>License</sub>

原创内容采用 [CC BY-NC 4.0](LICENSE) 许可，商业用途须取得[单独书面授权](COMMERCIAL-LICENSE.md)。<br>
<sub>Original materials are licensed under [CC BY-NC 4.0](LICENSE). Commercial use requires [separate written permission](COMMERCIAL-LICENSE.md).</sub>
