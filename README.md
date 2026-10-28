# Aesy

本仓库维护 Aegyce 的通用 Agent Aesy。当 Requirement 未找到适合处理当前任务的领域 Agent 时，由 Aesy 执行其委派的计划。<br>
This repository maintains Aesy, Aegyce's general-purpose agent. When Requirement cannot find a specialized agent suited to the current task, it delegates the plan to Aesy for execution.

## 当前支持的能力<br>Available capabilities

### 技能<br>Skills

- [computer-technical-language](plugins/computer-technical-language/skills/computer-technical-language/SKILL.md)：用于编写、润色和审查计算机技术文档、代码注释与技术答复，统一术语，改进措辞，并保留已有事实、条件和不确定性。<br>
  Draft, revise, and review computing documentation, code comments, and technical responses, using consistent terminology and clear wording while preserving facts, conditions, and uncertainty.

### MCP 集成<br>MCP integrations

暂未提供 MCP 集成。<br>
No MCP integrations are currently provided.

### 工具<br>Tools

暂未提供独立工具。<br>
No standalone tools are currently provided.

## 组件复用<br>Component reuse

Aesy 的部分组件可供其他 AI 工具使用，可包括 Skill、MCP 集成、工具等。具体使用方式取决于该工具支持的格式和接口。<br>
Other AI tools can use some of Aesy’s components, which may include skills, MCP integrations, tools, and other capabilities. How they are used depends on the formats and interfaces the tool supports.

这些组件以可独立安装的能力包形式，通过 [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) 分发，也可从本仓库直接获取。<br>
Reusable components are distributed as independently installable capability packages through [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) and are also available directly from this repository.

- [Aesy:computer-technical-language](plugins/computer-technical-language)：提供计算机技术用语 Skill，可单独安装。<br>
  Provides the computing terminology and technical writing skill as an independently installable plugin.

## 许可<br>License

原创内容采用 [CC BY-NC 4.0](LICENSE) 许可，商业用途须取得[单独书面授权](COMMERCIAL-LICENSE.md)。<br>
Original materials are licensed under [CC BY-NC 4.0](LICENSE). Commercial use requires [separate written permission](COMMERCIAL-LICENSE.md).
