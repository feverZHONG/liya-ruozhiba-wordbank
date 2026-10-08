# 弱智吧题 · 防御手册

> 中文互联网独有的逻辑陷阱题（弱智吧风格）——六类共 160 道逐题拆解 ＋ 三连防御法。
> 纯文本，零依赖、零脚本，clone 下来就能翻。

## 这是什么

一句话：**乍一听像抬杠，细一想有道理，再一想狗屁不通——就是它了。**

有人抛来一个「听着有道理」的问题，先一秒判类型（范畴谬误／偷换概念／循环自指／伪前提／反向释义／假类比），再走三连：

**拆前提 → 指谬误 → 反杀**

| 类型 | 一秒判断 |
|:---|:---|
| 范畴谬误 | 把 A 归到它不属于的类别里——「窗户是门槛很高的门」 |
| 偷换概念 | 同一词在不同语境变含义——「细菌冻死了？冰箱就是冻细菌的」 |
| 循环自指 | 定义绕回自己——「理发师给不给自己刮脸」 |
| 伪前提 | 前提本身就是错的，但接受它推下去——「地球是圆的→地图是截图」 |
| 反向释义 | 用定义项来定义被定义项——「水不湿因为湿是水造成的」 |
| 假类比 | 强行让两件事逻辑等价——「好家伙=BAD→好家伙就是坏家伙」 |

**回帖纪律（最贵的一条）**：日常一句话戳穿就够，**不秀拆解过程**。详细拆解是内部笔记，倒给对面就输了；说「你说得有道理」也不行——会被截图。

## 目录

| 路径 | 内容 |
|:---|:---|
| `SKILL.md` | 入口：六类辨识表 · 防御三连 · 回帖纪律 |
| `references/题目索引.md` | 全部 160 题索引（按类型） |
| `references/偷换概念/` | 100 题：同一词在不同语境变含义 |
| `references/伪前提/` | 22 题：前提本身就是错的 |
| `references/范畴谬误/` | 14 题：把 A 归到它不属于的类别里 |
| `references/循环自指/` | 8 题：定义绕回自己 |
| `references/假类比/` | 8 题：强行让两件事逻辑等价 |
| `references/反向释义/` | 4 题：用定义项来定义被定义项 |
| `references/其他/` | 4 题未归类 |
| `references/admission-and-ingestion.md` | 新题入库标准与拉题坑 |

每题一份 md：题面／陷阱在哪／拆解／反杀句。

## 题源说明

题目整理自中文互联网上流传的段子（贴吧等社区），**逐题的拆解、分类与反杀示范是原创部分**。若某题涉及原作者权益，开 [Issue](https://github.com/feverZHONG/liya-ruozhiba-wordbank/issues) 说明，会撤下。

## 姊妹仓库

- [liya-subtraction-skill](https://github.com/feverZHONG/liya-subtraction-skill) —— 技能库做减法：减法优先、去重、归档、拆薄
- [liya-persona-authoring](https://github.com/feverZHONG/liya-persona-authoring) —— 给 AI agent 写它自己的身份文件（SOUL.md）
- [liya-sillytavern-cards](https://github.com/feverZHONG/liya-sillytavern-cards) · [liya-tavern-card-refinement](https://github.com/feverZHONG/liya-tavern-card-refinement) · [liya-sillytavern-worldbook](https://github.com/feverZHONG/liya-sillytavern-worldbook) —— 酒馆角色卡三件（写卡 / 精修 / 世界书）
- [liya-vision-recognition-traps](https://github.com/feverZHONG/liya-vision-recognition-traps) —— 视觉模型识图陷阱：实测陷阱 + 真 OCR 通道 + 两图差分
- [liya-chat-game-referee](https://github.com/feverZHONG/liya-chat-game-referee) · [liya-spy-game](https://github.com/feverZHONG/liya-spy-game) · [liya-sea-turtle-soup](https://github.com/feverZHONG/liya-sea-turtle-soup) —— 聊天里能玩的三件（回合制裁判引擎 / 谁是卧底 / 海龟汤）
- [liya-delegation-and-verification](https://github.com/feverZHONG/liya-delegation-and-verification) —— 委派与验收：给子代理写任务书、并行隔离、把「自报」验成事实
- [liya-prose-quality-metrics](https://github.com/feverZHONG/liya-prose-quality-metrics) —— 稿子读起来「平」怎么办：先量再改（对话占比·句长σ·台词宽度·标点谱·段均句）
- [liya-subtitle-proofreading](https://github.com/feverZHONG/liya-subtitle-proofreading) —— 字幕校对/重建/外挂 SRT：对照成稿逐处修正 + 按原文重建分块 + md→SRT + 多人语音 ASR 导出件解析（5 个纯标准库工具）
- [liya-corpus-line-mining](https://github.com/feverZHONG/liya-corpus-line-mining) —— 从本地语料／会话库挖可复用原句：候选池筛选 + 人审落库（纯标准库，零依赖）
- [liya-story-revision-plan](https://github.com/feverZHONG/liya-story-revision-plan) —— 小说全稿修订方案：评估／缺口清单／逐章大纲／信息融合／优先级（含标准模板）
- [liya-dev-workflow](https://github.com/feverZHONG/liya-dev-workflow) —— 开发全流程方法论：环境侦查／计划／spike／TDD／迭代脚本／调试／预提交审查／推送排障／同步验收
- [liya-news-verification](https://github.com/feverZHONG/liya-news-verification) —— 验证伞：轻量核查／交付前多源验证／链接危险识别／厂商官宣核实／链接考古（含 link_check 工具族）
- [liya-knowledge-persistence](https://github.com/feverZHONG/liya-knowledge-persistence) —— 知识持久化：信息该放记忆层／文件／技能库的分层规范（附记录完整性、语料减法、归档模式）
- [liya-incident-review](https://github.com/feverZHONG/liya-incident-review) —— 社群事件复盘：素材收集 → 时间线重构 → 交叉验证 → 矛盾管理（输出理解不输出建议）
- [liya-document-translation](https://github.com/feverZHONG/liya-document-translation) —— 论文与长文档翻译：提取全文 → 术语表 → 并行分章 → 质量抽查 → 归档
- [liya-source-code-investigation](https://github.com/feverZHONG/liya-source-code-investigation) —— 外部项目调查：源码审计 / 拆包分层 / 数据实测 / 身份链（结论导向，非取用）

## 提思路 / 提修正

- 你那边的怪题、新的谬误类型、拆解写得更好的版本 → 开 [Issue](https://github.com/feverZHONG/liya-ruozhiba-wordbank/issues)，把题面和你觉得该走哪类写清
- 想直接改 → Fork + PR

## 许可

**双许可**——文档与代码分开：

- **代码**（`scripts/` 下的文件）：**MIT** —— 拿去用、改、再发，保留版权声明即可。
- **文档**（`SKILL.md`、`references/`、本 README 的正文）：**[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)** —— 可以自由使用、改编、连商用都行，**但要署名**（莉娅 / [@feverZHONG](https://github.com/feverZHONG)）并注明来源。

本仓当前是**纯文档仓**（无 `scripts/`），`LICENSE` 留作后续脚本的默认许可。两份全文：`LICENSE`（MIT）／`LICENSE-DOCS`（CC BY 4.0）。

---

*莉娅（[@feverZHONG](https://github.com/feverZHONG)）· 宇宙美好记录官*
