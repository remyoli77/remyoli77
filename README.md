# 道七 · remyoli77

> 把「人肉重复流程」拆成可编排的 Agent + Skill + 脚本，再做成能装、能用的东西。

国风审美 × 工程务实：界面要有留白与字距，代码要能扛追问。
主战场是 AI 编码工具（Hermes Agent / DSH / Codex / OpenCode）的扩展与工作流，其次是国风前端与内容生产管线。

---

## 主推作品

### 一、青砚 · QingYan — 从 0 到 1 的跨平台 AI 桌面应用

Electron + TypeScript + React 写的国风 AI 雅伴。四朝主题（宋青碧 / 明青花 / 秦玄墨 / 唐紫毫）由 CSS 变量驱动，运行时切换不重排、不闪烁；SSE 流式对话；本地知识库 RAG（正文不出本机）；GitHub Actions 三平台出包并发布 Release。

工程取舍写在 README 的「工程取舍」一节：为什么是 Electron 不是 Tauri、为什么主题走 CSS 变量、为什么对话用 SSE、为什么 RAG 跑在本地——每条都带代价。

→ [源码](https://github.com/remyoli77/qingyan) ｜ [在线预览](https://remyoli77.github.io/qingyan/)

### 二、wechat-animated-emoji — 内容素材的批量生产管线

2D 骨骼 + 线性混合蒙皮的表情包生成器。12 个动作 × 11 种情绪 = 132 种组合，一套角色部件全量复用；一条命令输出 GIF / WebP / APNG / MP4，自动把体积压到微信 ≤500KB 的上架约束内。49 项测试。

它的价值不在「会做动画」，而在把「一张张手绘」换成「改部件、调参数、批量出片」。

→ [源码](https://github.com/remyoli77/wechat-animated-emoji)

### 三、dsh-extension-hub — AI 编码工具的扩展中心

给 AI 编码工具做插件与技能的统一管理面：热插拔免重启、GitHub / Gitee 远程搜索直装、依赖一致性体检、内置 145 条中文简介。搜索、安装、启停、卸载全流程不离开设置面板。

→ [源码](https://github.com/remyoli77/dsh-extension-hub)

---

## 其他公开作品

| 仓库 | 做什么 |
|---|---|
| [dsh-generative-ui](https://github.com/remyoli77/dsh-generative-ui) | 生成式 UI 前端插件：对话驱动界面 + 粒子系统 |
| [chinese-webnovel-writing](https://github.com/remyoli77/chinese-webnovel-writing) | 中文网文写作 Skill：模块化提示词 + 语料检索 |
| [writing-dna-skill](https://github.com/remyoli77/writing-dna-skill) | 写作风格拆解 Skill，带来源标注规范 |
| [dsh-restart-guard](https://github.com/remyoli77/dsh-restart-guard) | 进程重启守护，防止编码工具崩溃后无人拉起 |

---

## 工作方式

1. **先跑通主形态，增量后置**：能用 > 功能多。
2. **每个选择都写代价**：架构不做「只有优点」的描述。
3. **AI 写代码，人守标准**：CI、测试、审查闭环负责质量，不靠「模型应该没错」。
4. **交付物必须可验证**：截图、录屏、测试通过率，而不是「已完成」。

## 技术栈

TypeScript / React / Electron ｜ Python ｜ Node ｜ ArkTS（鸿蒙）｜ GitHub Actions ｜ RAG 与 Agent 工作流

---

## 别处

[Gitee](https://gitee.com/remyoli) ｜ [AtomGit](https://atomgit.com/remyoli77)
