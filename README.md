# AgentTeam

连接本机 Claude Code 的 Windows 桌面客户端，帮助产品经理通过私聊和场景群聊完成产品工作。

**[查看完整产品介绍](http://122.51.35.154/agentteam/)** · [GitHub 图文说明](docs/PRODUCT-INTRODUCTION.md) · [下载 EXE 安装版](https://github.com/Piratelhx/AgentTeam-Downloads/releases/latest)

![群聊与文档交付](docs/images/01_group_overview.png)

## 三个产品场景

| 场景 | 协作方式 | 交付 |
| --- | --- | --- |
| 需求分析与 PRD 编写 | 业务分析 → 交互设计 → 技术评估 → 产品经理整合 | PRD 文档、验收标准及待确认项 |
| 产品方案模拟评审 | 主持 → 专家独立审查 → 最多两轮交叉回应 → 收敛 | 评审结论、修改建议与保留分歧 |
| 产品机会调研 | 市场研究 → 用户研究 → 证据核验 → 机会整合 | 机会报告、MVP 与验证计划 |

所有成员逐位接力；每个群的成员和分工来自场景，建群后保持固定。可自定义 Agent、System Prompt、场景与本地 Skill。


## 聊天与文件

- 支持私聊、群聊、@ 指定成员和完成后的手动接力。
- 消息可复制、记录时间；编辑用户消息后重新生成后续对话与关联文件记录。
- 支持上传文档，禁止上传图片；交付文档进入群文件，可预览和在本机文件夹中显示。
- 任务进行时锁定输入，支持停止；修改文件和执行命令按当前权限处理。

![群文件](docs/images/02_group_files.png)

## 挂载本地 Skill

搜索、查看和勾选本机 Skill，支持全选、清空与独立内容阅读。不同 Agent 可以挂载不同的方法与规范。


## 安装

仅提供 **Windows x64 EXE 安装版**。支持选择安装目录、覆盖旧版并保留聊天与配置，安装完成后可打开客户端。

使用前，请在自己的电脑安装并登录 Claude Code，然后在 AgentTeam 设置中点击 **测试 Claude Code**。模型请求复用本机账号与配置，安装包不包含制作者的账号或聊天。

## 产品介绍资料

- [在线 HTML 功能介绍](http://122.51.35.154/agentteam/)：20 个功能章节，支持目录跳转与截图放大。
- [GitHub 图文说明](docs/PRODUCT-INTRODUCTION.md)。
- [完整 HTML 文件](docs/AgentTeam-Product-Guide.html)：可下载到本机后用浏览器打开。
- 每个正式版本的 Release 也附带 HTML 产品介绍及安装包校验文件。

截图来自独立示例资料，用于展示交互和文件交付形式，不代表真实业务调研结果。

本仓库用于公开安装包和产品资料；应用源码由原私有仓库维护。
