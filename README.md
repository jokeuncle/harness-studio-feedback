# Harness Studio

### 让积累的技能，跟上你切换的 AI 工具。

在一处整理 Skill 与 MCP，比较、修改并复制到常用客户端。每次改动先看差异，保留备份，让熟悉的方法继续用。

**[访问官网](https://harnessloom.com/) · [下载与安装](https://harnessloom.com/#download) · [体验交互演示](https://harnessloom.com/#demo) · [提交反馈](https://github.com/jokeuncle/harness-studio-feedback/issues/new/choose)**

[![Harness Studio 配置工作台：查看来源、浏览 Skill 正文并整理客户端配置](https://harnessloom.com/software-routing-dark.webp)](https://harnessloom.com/#workflow)

*来自官网的真实软件界面，使用示例配置。*

## 换个工具，熟悉的方法接着用

你可能在 Codex 里打磨过一套代码评审方法，在 Claude Code 里整理过发布检查，又在另一个客户端配置了常用资料源。换工具时，这些积累值得一起带过去。

Harness Studio 是一款本地配置工作台，帮你看清配置在哪里、有哪些差异、准备改动什么，再由你确认保存。

| 你正在做的事 | 工作台如何帮忙 |
| --- | --- |
| 新项目开工 | 查看项目级与用户级配置，调整已支持的 Skill、MCP 开关，再到客户端确认加载情况。 |
| 换个 AI 工具 | Skill 正文、脚本与参考资料一起复制；MCP 按项检查目标格式，预览后再保存。 |
| 接手旧仓库 | 分清同名配置的来源、作用范围与内容，先看差异，再决定改哪一份。 |
| 迭代已有方法 | 比较改进后的 Skill 与已有副本，确认更新，并保留备份和变更记录。 |

## 改配置之前，先把改动看清楚

1. **看清来源**：在一处查看已识别的本地配置，分清客户端、项目级与用户级范围。
2. **确认差异**：编辑、复制或更新前先预览；遇到冲突或无法安全转换的内容，会提示你核对。
3. **保留退路**：写入前备份，改动后留记录。还原前检查当前文件和备份，避免覆盖后来产生的新改动。

[![复制 Skill 前的变更预览，核对来源、目标与内容后再确认写入](https://harnessloom.com/software-preview-dark.webp)](https://harnessloom.com/#workflow)

Skill 的随附文件也属于方法的一部分。复制时一起处理正文、脚本、参考资料与文件权限；遇到不安全的链接或超限资源，会停止并提示。

## 常用的 AI 工具，放在一处管理

**Codex · Claude Code · Cursor · VS Code · Gemini CLI · OpenCode**

适配上述客户端的已知配置格式，可用范围因客户端而异：

- Skill 开关目前适配 Codex、Claude Code。
- MCP 开关目前适配 Codex、Claude Code、Gemini CLI、OpenCode。
- 仅适配已知的标准配置位置；自定义配置目录尚未覆盖。OpenCode 当前适配 v1 配置，不支持 v2 的 `mcp.servers` 结构。

配置复制到目标后形成独立副本。保存成功后，仍可能需要重新加载、重启客户端或确认信任。发现文件、语法检查通过与 MCP 实际连通是不同结果；查看配置不会启动 MCP。

## 工作台，也可以是你喜欢的样子

六张原创内置背景，也可以选择自己的图片或 GIF 动图。支持深浅主题，背景强度与虚化可调，随时恢复默认。

[![Harness Studio 湖山晨光背景：给工作台留一片开阔，截图使用示例配置](https://harnessloom.com/software-wallpaper-alpine-lake-dark.webp)](https://harnessloom.com/#appearance)

自选原图保存在本机，不上传、不降低分辨率。Skill、MCP 配置与其中的凭据在本机读取和处理；商业授权服务处理账号、订单与设备授权信息。详见[隐私说明](https://harnessloom.com/privacy.html)。

## 先试一试，再决定

未购买时，仍可查看本地配置、查看历史和还原备份，也可在明确标注的示例项目里体验操作。编辑真实配置或复制到其他客户端，需要购买并激活个人版。

个人版采用买断方式，不自动续费。当前价格、设备数量、版本更新权益、离线使用条件与购买条款，以[官网说明](https://harnessloom.com/#pricing)及软件内展示为准。

- [查看各平台下载状态](https://harnessloom.com/#download)：按操作系统与芯片选择；未开放的条目以官网显示为准。
- 安装与更新指南：[macOS](https://harnessloom.com/install-macos.html) · [Windows](https://harnessloom.com/install-windows.html) · [Linux](https://harnessloom.com/install-linux.html)。
- [研究与实践](https://harnessloom.com/#research)：了解技能复用、上下文与工具配置背后的思考。相关研究不代表作者为产品背书，也不代表本产品已复现论文效果。

## 反馈与建议

这里用于提交 Harness Studio 的使用问题、界面问题和功能建议。**本仓库是公开反馈入口，不包含产品源码、安装包或发布制品。下载请前往官网。**

## 提交之前

1. 先在 [已有反馈](https://github.com/jokeuncle/harness-studio-feedback/issues) 中搜索关键词，看看是否已有相同问题。可以在已有 Issue 中补充复现条件，避免重复提交。
2. 登录 GitHub。没有账号的话，需要先注册；不方便使用 GitHub，可联系支持邮箱：827919619@qq.com。
3. 点击 [新建反馈](https://github.com/jokeuncle/harness-studio-feedback/issues/new/choose)，选择「问题反馈」或「功能建议」。

## 怎样描述问题

- 标题：说明在哪个页面、做了什么、遇到了什么。例如「新建 Skill：保存后仍显示处理中」。
- 环境：应用版本、操作系统版本、涉及的 AI 客户端。
- 复现步骤：按操作顺序列出，说明是否每次都能出现。
- 预期与实际结果：分别描述希望发生什么、实际发生什么；错误提示请保留准确文字。
- 截图：只附与问题有关的区域，先遮盖个人信息和敏感内容。

提交后，可在 Issue 页面查看讨论、补充信息和关注处理进展。Issue 的状态用于跟踪反馈，不代表承诺的交付时间。

## 请保护隐私

**Issue、评论和附件均为公开内容。** 请不要上传密码、API Key、Token、MCP 密钥、完整配置文件、账号恢复码、付款凭证或含个人信息的日志。文件路径、用户名和截图也应先脱敏。

账号、付款、设备授权和其他涉及个人信息的问题，请通过支持邮箱处理，不要公开提交。

## 功能建议

请描述你正在完成什么任务、目前卡在哪里、希望如何改进，以及现有操作方式。具体场景比单独列出功能名称更便于讨论。
