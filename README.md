# Aesy

本仓库维护 Aegyce 的通用 Agent Aesy。当 Requirement 未找到适合处理当前任务的领域 Agent 时，由 Aesy 执行其委派的计划。<br><sub>This repository maintains Aesy, Aegyce's general-purpose agent. When Requirement cannot find a specialized agent suited to the current task, it delegates the plan to Aesy for execution.</sub>

## 当前支持的能力<br><sub>Available capabilities</sub>

### 技能<br><sub>Skills</sub>

- [computer-technical-language](plugins/computer-technical-language/skills/computer-technical-language/SKILL.md)：用于编写、润色和审查计算机技术文档、代码注释与技术答复，统一术语，改进措辞，并保留已有事实、条件和不确定性。<br><sub>Draft, revise, and review computing documentation, code comments, and technical responses, using consistent terminology and clear wording while preserving facts, conditions, and uncertainty.</sub>

- [studio-portrait](plugins/studio-portrait/skills/studio-portrait/SKILL.md)：基于用户原始照片制作或修正高质感影棚商务肖像，保持五官特征与自然表情，统一高级西服、影棚布光与背景纵深。<br><sub>Create and refine high-end studio business portraits from original photos while preserving facial features and expressions, standardizing formal suits, studio lighting, and background depth.</sub>

### MCP 集成<br><sub>MCP integrations</sub>

暂未提供 MCP 集成。<br><sub>No MCP integrations are currently provided.</sub>

### 工具<br><sub>Tools</sub>

暂未提供独立工具。<br><sub>No standalone tools are currently provided.</sub>

## 组件复用<br><sub>Component reuse</sub>

Aesy 的部分组件可供其他 AI 工具使用，可包括 Skill、MCP 集成、工具等。具体使用方式取决于该工具支持的格式和接口。<br><sub>Other AI tools can use some of Aesy’s components, which may include skills, MCP integrations, tools, and other capabilities. How they are used depends on the formats and interfaces the tool supports.</sub>

这些组件以可独立安装的能力包形式存放在 [plugins/](plugins/)，通过 [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace) 分发，也可从本仓库直接获取。<br><sub>Reusable components are stored as independently installable capability packages under [plugins/](plugins/), distributed through [Aegyce Marketplace](https://github.com/Aegyce/aegyce-marketplace), and also available directly from this repository.</sub>

## 许可<br><sub>License</sub>

原创内容采用 [CC BY-NC 4.0](LICENSE) 许可，商业用途须取得[单独书面授权](COMMERCIAL-LICENSE.md)。<br><sub>Original materials are licensed under [CC BY-NC 4.0](LICENSE). Commercial use requires [separate written permission](COMMERCIAL-LICENSE.md).</sub>
