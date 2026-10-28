# Aesy Agent 维护约定

本仓库维护 Aegyce 通用 Agent Aesy 这个完整 Agent。Aesy 承接 Requirement 在未匹配到领域 Agent 时委派的工作。其中可复用的组件按能力包放入 `plugins/<capability>/`，每个目录以 `plugin.json` 声明独立插件。

- 仓库以完整 Agent 为单位维护，插件按独立安装需求划分。需要单独安装的 Skill 使用独立插件；需要配合使用的多个 Skill、MCP 集成或工具可组成同一插件，不默认打包 Agent 的全部能力。
- 每个插件内的 Skill 放在 `skills/<skill-name>/`，名称在包内唯一；MCP 配置按需放在插件根目录的 `mcp.json`。接入方式以宿主支持的格式和接口为准。
- 技术表达遵循 `plugins/computer-technical-language/skills/computer-technical-language/SKILL.md`。修改 Skill 时保留原有事实、条件与范围；仅审查时不改动目标材料。
- 发布内容须自包含，不依赖父项目、仓库外符号链接或本机绝对路径。目录移动或独立克隆后仍应可用；不得打包用户工作、记忆、运行状态、凭据或临时授权。
- README 中文在上，使用 `<br>` 换行，英文以 `<sub>English text</sub>` 小字置于下方。先介绍 Agent 类型与职责，再按 Skill、MCP、工具等类别设章节；每项列名称、入口和一句话简介，尚未提供的类别注明当前状态，新增类别按实际内容组织。
- 能力说明面向 AI 工具复用；README 不列具体 AI 产品的安装或调用示例，不声称未经验证的兼容性。
- 插件名称使用 `aesy-<capability>`，各自的版本记录在包内 `plugin.json`。同一已发布版本不覆盖内容；市场用 `git-subdir` 指向包目录及明确提交，能力更新不改变 Agent 运行身份或权限。
- 每个可独立分发的插件携带完整 `LICENSE` 和 `COMMERCIAL-LICENSE.md`；与仓库根目录保持一致，包内引用不得依赖包外文件。
- 原创内容统一采用 CC BY-NC 4.0；商业用途须另行取得版权所有者的书面授权。保留完整许可证、商业授权说明与 README 双语声明；第三方内容遵循原许可。
- 发布前检查插件清单、Skill 元数据、引用和许可证，并验证宿主发现、加载及目录迁移。未实现的能力不建立空目录或写入能力清单。
