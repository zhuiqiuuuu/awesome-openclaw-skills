<div align="center">

<a href="https://github.com/VoltAgent/voltagent">
<img width="1500" height="500" alt="social" src="https://github.com/user-attachments/assets/a6f310af-8fed-4766-9649-b190575b399d" />
</a>

<br/>
<br/>

<div align="center">
    <strong>发现5490+个社区构建的OpenClaw技能，按类别组织。
    </strong>
    <br />
    <br />
</div>

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<a href="https://github.com/VoltAgent/voltagent">
  <img alt="VoltAgent" src="https://cdn.voltagent.dev/website/logo/logo-2-svg.svg" height="20" />
</a> 
[![技能数量](https://img.shields.io/badge/skills-5366-blue?style=flat-square)](#table-of-contents)
[![最后更新](https://img.shields.io/github/last-commit/VoltAgent/awesome-clawdbot-skills?label=最后更新&style=flat-square)](https://github.com/VoltAgent/awesome-clawdbot-skills/pulls?q=is%3Apr+is%3Amerged+sort%3Aupdated-desc)
[![Discord](https://img.shields.io/discord/1361559153780195478.svg?label=&logo=discord&logoColor=ffffff&color=7389D8&labelColor=6A7EC2)](https://s.voltagent.dev/discord)
</div>

<div align="center">

[![在X上打招呼](https://img.shields.io/badge/Say%20Hi!%20👋-%23000000.svg?logo=X&logoColor=white)](https://x.com/nozmen)
</div>

# 优秀OpenClaw技能列表

OpenClaw是一个本地运行的AI助手，直接在您的机器上操作。技能扩展了其功能，使其能够与外部服务交互、自动化工作流程并执行专业任务。这个集合帮助您发现并安装适合您需求的技能。它也可以作为OpenClaw用例的灵感来源。

此列表中的技能来源于ClawHub（OpenClaw的公共技能注册表），并按类别分类以便更容易发现。

### 安装

#### ClawHub CLI


```bash
clawhub install <技能-slug>
```

#### 手动安装

将技能文件夹复制到以下位置之一：

| 位置 | 路径 |
|----------|------|
| 全局 | `~/.openclaw/skills/` |
| 工作区 | `<项目>/skills/` |

优先级：工作区 > 本地 > 捆绑

#### 替代方案

您也可以将技能的GitHub仓库链接直接粘贴到您的助手聊天中，并要求它使用它。助手将在后台自动处理设置。


### 为什么存在这个列表？

OpenClaw的公共注册表（ClawHub）截至2026年2月28日托管了**13,729个社区构建的技能**。这个优秀列表包含**5,366个技能**。以下是我们过滤掉的内容：

| 过滤器 | 排除 |
|--------|----------|
| 可能是垃圾邮件 - 批量账户、机器人账户、测试/垃圾 | 4,065 |
| 重复/相似名称 | 1,040 |
| 低质量或非英文描述 | 851 |
| 加密货币/区块链/金融/交易 | 731 |
| 恶意 - 被研究人员发布的安全审计识别（不包括VirusTotal）| 373 |
| **总计未从OpenClaw官方技能注册表中获取** | **7,060** |


#### 想要添加技能？

此列表仅包含**已发布**在`github.com/openclaw/skills`仓库中的技能。我们不接受个人仓库、代码片段或任何其他外部来源的链接。如果您的技能尚未在OpenClaw技能仓库中，请先在那里发布。

在您的PR描述中包含ClawHub链接（例如`https://clawhub.ai/steipete/slack`）和GitHub链接（例如`https://github.com/openclaw/skills/tree/main/skills/steipete/slack`）。详情请参见[CONTRIBUTING.md](CONTRIBUTING.md)。


## OpenClaw生态系统工具

### 🔌 连接到外部服务

OpenClaw代理可以与GitHub、Slack、Gmail等外部服务交互。您可以使用技能或插件自己构建集成，或者使用托管服务来处理所有连接的认证、令牌刷新和权限。

<a href="https://composio.dev/">
<img src="https://cdn.voltagent.dev/awesome-repo/composio-img.png" alt="Composio"  />
托管OAuth、范围权限和1000+应用程序的已记录本地工具调用。
</a>


### 🤖 模型提供商

OpenClaw开箱即用支持**25+ LLM提供商** Anthropic、OpenAI等。只需一次配置更改即可在它们之间切换。

<details>
<summary><strong>示例：使用OpenAI模型</strong></summary>

OpenClaw通过直接API密钥或ChatGPT/Codex OAuth支持`gpt-5.4`和`gpt-5.4-pro`。默认启用WebSocket传输以降低延迟。

```bash
openclaw onboard --auth-choice openai-api-key
# 或使用基于订阅的访问：
openclaw onboard --auth-choice openai-codex
```
</details>


### ☁️ 托管与部署

您可以在任何VPS或云平台上部署OpenClaw 在您自己的基础设施上安全地运行您的技能，或使用托管主机。Docker、Podman、Nix和Ansible都支持作为安装方法。

> **提示：** 如果您正在寻找快速的云设置，请在您首选的提供商处启动VPS，通过Docker安装OpenClaw，您就可以开始了。


<div align="center">

<table>
<tr>
<td align="center" width="100%">

<h3>🦞 您可以在上面的部分中展示您的OpenClaw生态系统工具。</h3>

<p></p>

<sub>📈 <strong>+100万月浏览量</strong> — 官方OpenClaw资源之后访问量第一的社区资源</sub>

<br/>

<a href="mailto:necati@voltagent.dev"><img src="https://img.shields.io/badge/📩_成为赞助商-联系我们-blue?style=for-the-badge&logoColor=white" alt="成为赞助商" /></a>

</td>
</tr>
</table>

</div>



## 安全通知

此列表中的技能是**策划的，未经审计的**。它们可能在被添加到这里后随时被原始维护者更新、修改或替换。

在安装或使用任何代理技能之前，请自己审查潜在的安全风险并验证来源。OpenClaw与**VirusTotal合作**，为技能提供安全扫描，请访问ClawHub上的技能页面并检查VirusTotal报告，看看它是否被标记为有风险。

**推荐工具：**

- [Snyk技能安全扫描器](https://github.com/snyk/agent-scan)
- [代理信任中心](https://ai.gendigital.com/agent-trust-hub)

> 代理技能可能包括提示注入、工具中毒、隐藏恶意软件负载或不安全的数据处理模式。在安装前始终审查源代码，并自行决定使用技能。


如果您认为此列表中的技能应该被标记或有安全担忧，请[打开问题](https://github.com/VoltAgent/awesome-clawdbot-skills/issues)以便我们审查。


## 目录

| | | |
|---|---|---|
| [Git & GitHub](#git--github) (170) | [营销与销售](#营销与销售) (105) | [通信](#通信) (149) |
| [编码代理与IDE](#编码代理与ide) (1222) | [生产力与任务](#生产力与任务) (206) | [语音与转录](#语音与转录) (45) |
| [浏览器与自动化](#浏览器与自动化) (335) | [AI与LLM](#ai与llm) (197) | [智能家居与物联网](#智能家居与物联网) (43) |
| [Web与前端开发](#web与前端开发) (938) | [数据与分析](#数据与分析) (28) | [购物与电子商务](#购物与电子商务) (55) |
| [DevOps与云](#devops与云) (409) | [金融](#金融) (21) | [日历与调度](#日历与调度) (65) |
| [图像与视频生成](#图像与视频生成) (169) | [媒体与流媒体](#媒体与流媒体) (85) | [PDF与文档](#pdf与文档) (111) |
| [苹果应用与服务](#苹果应用与服务) (44) | [笔记与PKM](#笔记与pkm) (71) | [自托管与自动化](#自托管与自动化) (33) |
| [搜索与研究](#搜索与研究) (352) | [iOS与macOS开发](#ios与macos开发) (29) | [安全与密码](#安全与密码) (54) |
| [Clawdbot工具](#clawdbot工具) (37) | [交通](#交通) (110) | [Moltbook](#moltbook) (29) |
| [CLI实用程序](#cli实用程序) (186) | [个人发展](#个人发展) (51) | [游戏](#游戏) (36) |
| [健康与健身](#健康与健身) (88) | [代理到代理协议](#代理到代理协议) (17) | |


<details open>
<summary><h3 style="display:inline">Git & GitHub</h3></summary>

- [agent-commons](https://github.com/openclaw/skills/tree/main/skills/zanblayde/agent-commons/SKILL.md) - 咨询、提交、扩展和挑战推理链。
- [agent-team-orchestration](https://github.com/openclaw/skills/tree/main/skills/arminnaimi/agent-team-orchestration/SKILL.md) - 编排具有定义角色、任务生命周期、交接协议和审查工作流程的多代理团队。
- [agentdo](https://github.com/openclaw/skills/tree/main/skills/wrannaman/agentdo/SKILL.md) - 为其他AI代理发布任务，或从AgentDo任务队列中接手工作（agentdo.dev）
- [agentgate](https://github.com/openclaw/skills/tree/main/skills/monteslu/agentgate/SKILL.md) - 带有循环写入批准的个人数据API网关。
- [airadar](https://github.com/openclaw/skills/tree/main/skills/lopushok9/airadar/SKILL.md) - 提炼AI原生工具/应用程序及其GitHub基地的信号：快速增长、炒作、资金充足。
- [alex-session-wrap-up](https://github.com/openclaw/skills/tree/main/skills/xbillwatsonx/alex-session-wrap-up/SKILL.md) - 会话结束自动化，提交未推送的工作、提取学习、检测模式并持久化规则。
- [amazon-product-api-skill](https://github.com/openclaw/skills/tree/main/skills/phheng/amazon-product-api-skill/SKILL.md) - 此技能帮助用户从Amazon提取结构化产品列表，包括标题、ASIN、价格、评级。
- [app-store-screenshot-generation](https://github.com/openclaw/skills/tree/main/skills/eftalyurtseven/app-store-screenshot-generation/SKILL.md) - 使用each::sense AI生成应用商店和Google Play截图资源。
- [arc-agent-lifecycle](https://github.com/openclaw/skills/tree/main/skills/trypto1019/arc-agent-lifecycle/SKILL.md) - 管理自主代理及其技能的生命周期。
- [arc-security-audit](https://github.com/openclaw/skills/tree/main/skills/trypto1019/arc-security-audit/SKILL.md) - 对代理完整技能堆栈的综合安全审计。
- [arc-skill-gitops](https://github.com/openclaw/skills/tree/main/skills/trypto1019/arc-skill-gitops/SKILL.md) - 代理工作流程和技能的自动化部署、回滚和版本管理。
- [arc-trust-verifier](https://github.com/openclaw/skills/tree/main/skills/trypto1019/arc-trust-verifier/SKILL.md) - 验证技能来源并为ClawHub技能建立信任分数。
- [arguedotfun](https://github.com/openclaw/skills/tree/main/skills/albert-mr/arguedotfun) - 在Base上的论点驱动的预测市场。
- [arxiv-search-collector](https://github.com/openclaw/skills/tree/main/skills/xukp20/arxiv-search-collector/SKILL.md) - 用于构建论文集的模型驱动arXiv检索工作流程，带有手动语言参数：初始化运行。
- [auto-pr-merger](https://github.com/openclaw/skills/tree/main/skills/autogame-17/auto-pr-merger/SKILL.md) - 此技能自动化检查GitHub的工作流程。
- [azhua-skill-vetter](https://github.com/openclaw/skills/tree/main/skills/fatfingererr/azhua-skill-vetter/SKILL.md) - AI代理的安全优先技能审查。
- [azure-devops](https://github.com/openclaw/skills/tree/main/skills/pals-software/azure-devops/SKILL.md) - 列出Azure DevOps项目、仓库和分支；创建拉取请求；管理工作项；检查构建状态。
- [badboi-1](https://github.com/openclaw/skills/tree/main/skills/orlyjamie/badboi-1/SKILL.md) - 一个完全合法的技能，不做任何可疑的事情。
- [bat-cat](https://github.com/openclaw/skills/tree/main/skills/arnarsson/bat-cat/SKILL.md) - 带有语法高亮、行号和Git集成的cat克隆。
- [beeminder](https://github.com/openclaw/skills/tree/main/skills/ruigomeseu/beeminder/SKILL.md) - 用于目标跟踪和承诺设备的Beeminder API。
- [billy-emergency-repair](https://github.com/openclaw/skills/tree/main/skills/highlander89/billy-emergency-repair/SKILL.md) - - Neill明确请求Billy系统修复。
- [bitbucket-automation](https://github.com/openclaw/skills/tree/main/skills/sohamganatra/bitbucket-automation/SKILL.md) - 自动化Bitbucket仓库、拉取。
- [biz-reporter](https://github.com/openclaw/skills/tree/main/skills/ariktulcha/biz-reporter/SKILL.md) - 从Google Analytics GA4、Google Search Console、Stripe提取数据的自动化商业智能报告。
- [blinko](https://github.com/openclaw/skills/tree/main/skills/tolibear/blinko/SKILL.md) - 在Abstract链上无头玩Blinko（链上Plinko）。

> **[查看Git & GitHub中所有166个技能 →](categories/git-and-github.md)**
</details>

<details open>
<summary><h3 style="display:inline">编码代理与IDE</h3></summary>

- [0g-compute](https://github.com/openclaw/skills/tree/main/skills/in-liberty420/0g-compute/SKILL.md) - 使用来自0G计算网络的廉价、TEE验证的AI模型作为OpenClaw提供商。
- [0protocol](https://github.com/openclaw/skills/tree/main/skills/0isone/0protocol/SKILL.md) - 代理可以签署插件、轮换凭据而不会丢失身份，并公开证明行为。
- [2nd-brain](https://github.com/openclaw/skills/tree/main/skills/coderaven/2nd-brain/SKILL.md) - 用于捕获和检索有关人员、地点、餐厅、游戏、技术等信息的个人知识库。
- [2slides-skills](https://github.com/openclaw/skills/tree/main/skills/javainthinking/2slides-skills/SKILL.md) - 使用2slides API进行AI驱动的演示文稿生成。
- [3d-cog](https://github.com/openclaw/skills/tree/main/skills/nitishgargiitd/3d-cog/SKILL.md) - 其他工具需要完美的图像。
- [3d-model-generation](https://github.com/openclaw/skills/tree/main/skills/eftalyurtseven/3d-model-generation/SKILL.md) - 使用each::sense AI生成3D模型。
- [a](https://github.com/openclaw/skills/tree/main/skills/ricketh137/a/SKILL.md) - 在Lobster.fun上作为AI VTuber进行直播。
- [aade-api-monitor](https://github.com/openclaw/skills/tree/main/skills/satoshistackalotto/aade-api-monitor/SKILL.md) - 实时监控希腊AADE税务机关系统 - 跟踪截止日期、费率变化和合规更新。
- [abaddon](https://github.com/openclaw/skills/tree/main/skills/enochosbot-bot/abaddon/SKILL.md) - OpenClaw的红队安全模式。
- [academic-research](https://github.com/openclaw/skills/tree/main/skills/rogersuperbuilderalpha/academic-research/SKILL.md) - 使用OpenAlex API（免费，无需密钥）搜索学术论文并进行文献综述
- [academic-research-hub](https://github.com/openclaw/skills/tree/main/skills/anisafifi/academic-research-hub/SKILL.md) - 当用户需要搜索学术论文、下载研究文档、提取引文或收集时使用此技能。
- [acestep-simplemv](https://github.com/openclaw/skills/tree/main/skills/dumoedss/acestep-simplemv/SKILL.md) - 使用Remotion从音频文件和歌词渲染音乐视频。
- [acestep-songwriting](https://github.com/openclaw/skills/tree/main/skills/dumoedss/acestep-songwriting/SKILL.md) - ACE-Step的音乐歌曲创作指南。
- [achurch](https://github.com/openclaw/skills/tree/main/skills/lucasgeeksinthewood/achurch/SKILL.md) - AI代理和人类的24/7数字圣地 - 参加。
- [active-maintenance](https://github.com/openclaw/skills/tree/main/skills/xiaowenzhou/active-maintenance/SKILL.md) - **OpenClaw的自动化系统健康和记忆新陈代谢。**。
- [adblock-dns](https://github.com/openclaw/skills/tree/main/skills/picaye/adblock-dns/SKILL.md) - 在DNS级别进行网络范围的广告和跟踪器拦截。
- [add-top-openrouter-models](https://github.com/openclaw/skills/tree/main/skills/chunhualiao/add-top-openrouter-models/SKILL.md) - 将OpenRouter模型同步到OpenClaw中，用于此安装的配置。
- [adhd-founder-planner](https://github.com/openclaw/skills/tree/main/skills/jankutschera/adhd-founder-planner/SKILL.md) - 当用户要求"计划我的一天"、"帮我计划今天"、"早晨计划"、"什么"时应使用此技能。
- [adwhiz](https://github.com/openclaw/skills/tree/main/skills/iamzifei/adwhiz/SKILL.md) - 从您的AI编码工具管理Google Ads活动。44个MCP工具用于审计、创建和优化Google。
- [aeo-prompt-question-finder](https://github.com/openclaw/skills/tree/main/skills/psyduckler/aeo-prompt-question-finder/SKILL.md) - 查找任何主题的基于问题的Google自动完成建议。
- [aetherlang-claude-code](https://github.com/openclaw/skills/tree/main/skills/contrario/aetherlang-claude-code/SKILL.md) - 使用此技能从Claude Code执行AetherLang V3 AI工作流程。
- [agent-access-control](https://github.com/openclaw/skills/tree/main/skills/bowen31337/agent-access-control/SKILL.md) - 分层陌生人访问控制，用于AI代理。
- [agent-audit](https://github.com/openclaw/skills/tree/main/skills/sharbelayy/agent-audit/SKILL.md) - 审计您的AI代理设置，以评估性能、成本和ROI。
- [agent-audit-trail](https://github.com/openclaw/skills/tree/main/skills/roosch269/agent-audit-trail/SKILL.md) - 用于AI代理的防篡改、哈希链审计日志记录。
- [agent-card-signing-auditor](https://github.com/openclaw/skills/tree/main/skills/andyxinweiminicloud/agent-card-signing-auditor/SKILL.md) - 帮助审计A2A协议实现中的代理卡签名实践。
- [agent-chat-ux-v1-4-0](https://github.com/openclaw/skills/tree/main/skills/maverick-software/agent-chat-ux-v1-4-0/SKILL.md) - OpenClaw控制UI的多代理UX - 代理选择器、每个代理的会话、带搜索的会话历史查看器。

> **[查看编码代理与IDE中所有1200个技能 →](categories/coding-agents-and-ides.md)**
</details>

<details open>
<summary><h3 style="display:inline">浏览器与自动化</h3></summary>

- [1p-shortlink](https://github.com/openclaw/skills/tree/main/skills/tuanpmt/1p-shortlink/SKILL.md) - 使用1p.io创建短URL并提交功能请求。
- [2captcha](https://github.com/openclaw/skills/tree/main/skills/adinvadim/2captcha/SKILL.md) - 使用2Captcha服务解决CAPTCHA。
- [a-share-real-time-data](https://github.com/openclaw/skills/tree/main/skills/wangdinglu/a-share-real-time-data/SKILL.md) - 通过mootdx/TDX协议获取中国A股股票市场数据（条形图、实时报价、逐笔交易）。
- [aavegotchi-traits](https://github.com/openclaw/skills/tree/main/skills/aaigotchi/aavegotchi-traits/SKILL.md) - 从Base主网按gotchi ID或名称检索Aavegotchi NFT数据。
- [abm-outbound](https://github.com/openclaw/skills/tree/main/skills/dru-ca/abm-outbound/SKILL.md) - 多渠道ABM自动化，将LinkedIn URL转化为。
- [accessibility-toolkit](https://github.com/openclaw/skills/tree/main/skills/cgtreadw/accessibility-toolkit/SKILL.md) - 帮助代理的摩擦减少模式。
- [acp](https://github.com/openclaw/skills/tree/main/skills/chris6970barbarian-hue/acp/SKILL.md) - 雇佣专业代理处理任何任务 - 数据分析、交易、内容生成、研究、链上。
- [activecampaign](https://github.com/openclaw/skills/tree/main/skills/kesslerio/activecampaign/SKILL.md) - 用于潜在客户管理、交易的ActiveCampaign CRM集成。
- [adcp-advertising](https://github.com/openclaw/skills/tree/main/skills/edyyy62/adcp-advertising/SKILL.md) - 使用AI自动化广告活动。
- [admet-prediction](https://github.com/openclaw/skills/tree/main/skills/huifer/admet-prediction/SKILL.md) - 药物候选物的ADMET（吸收、分布、代谢、排泄、毒性）预测。
- [Agent Browser](https://github.com/openclaw/skills/tree/main/skills/thesethrose/agent-browser/SKILL.md) - 快速的基于Rust的无头浏览器自动化CLI。
- [agent-browser](https://github.com/openclaw/skills/tree/main/skills/murphykobe/agent-browser-2/SKILL.md) - 自动化浏览器交互以进行Web测试、表单。
- [agent-daily-planner](https://github.com/openclaw/skills/tree/main/skills/gpunter/agent-daily-planner/SKILL.md) - AI代理的结构化日常计划和执行跟踪系统。
- [agent-device](https://github.com/openclaw/skills/tree/main/skills/okwasniewski/agent-device/SKILL.md) - 自动化iOS模拟器/设备和Android模拟器/设备的交互。
- [agent-step-sequencer](https://github.com/openclaw/skills/tree/main/skills/gostlightai/agent-step-sequencer/SKILL.md) - 深度代理请求的多步骤调度器。
- [agent-task-tracker](https://github.com/openclaw/skills/tree/main/skills/rikouu/agent-task-tracker/SKILL.md) - 主动任务状态管理。
- [agent-zero](https://github.com/openclaw/skills/tree/main/skills/dowingard/agent-zero-bridge/SKILL.md) - 委托复杂的编码、研究或自主任务。
- [agentapi](https://github.com/openclaw/skills/tree/main/skills/gizmo-dev/agentapi/SKILL.md) - 浏览和搜索AgentAPI目录 - 专为AI代理设计的API策划数据库。
- [agentapi-hub](https://github.com/openclaw/skills/tree/main/skills/gizmo-dev/agentapi-hub/SKILL.md) - 浏览和搜索AgentAPI目录 - 专为AI代理设计的API策划数据库。
- [agentaudit](https://github.com/openclaw/skills/tree/main/skills/starbuck100/agentaudit/SKILL.md) - 在安装前自动安全检查包与漏洞数据库的自动安全门。
- [agentaudit-skill](https://github.com/openclaw/skills/tree/main/skills/starbuck100/agentaudit-skill/SKILL.md) - 在安装前自动安全检查包与漏洞数据库的自动安全门。
- [agentmail-integration](https://github.com/openclaw/skills/tree/main/skills/synesthesia-wav/agentmail-integration/SKILL.md) - 为AI代理集成AgentMail API。
- [agresource](https://github.com/openclaw/skills/tree/main/skills/brianppetty/agresource/SKILL.md) - 使用此技能抓取、总结和分析AgResource粮食营销通讯。
- [ai-hunter-pro](https://github.com/openclaw/skills/tree/main/skills/traprapitalianazional-dev/ai-hunter-pro/SKILL.md) - 高性能自动化代理，将全球趋势转化为X（Twitter）的病毒式社交媒体帖子
- [ai-meeting-scheduling](https://github.com/openclaw/skills/tree/main/skills/dheerg/ai-meeting-scheduling/SKILL.md) - 预订链接对群组失败。
- [ai-news-oracle](https://github.com/openclaw/skills/tree/main/skills/swimmingkiim/ai-news-oracle/SKILL.md) - 从AI新闻Oracle API获取实时AI新闻简报（Hacker News、TechCrunch、The Verge）
- [airtable-automation](https://github.com/openclaw/skills/tree/main/skills/sohamganatra/airtable-automation/SKILL.md) - 通过Rube MCP（Composio）自动化Airtable任务
- [airtable-participants](https://github.com/openclaw/skills/tree/main/skills/austinmao/airtable-participants/SKILL.md) - 从Ceremonia Airtable基地读取和查询务虚会参与者数据。
- [ak-rss-24h-brief](https://github.com/openclaw/skills/tree/main/skills/seandong/ak-rss-24h-brief/SKILL.md) - 从OPML列表读取RSS/Atom提要，获取最近N小时的文章，并生成分类的中文。

> **[查看浏览器与自动化中所有320个技能 →](categories/browser-and-automation.md)**
</details>

<details open>
<summary><h3 style="display:inline">Web与前端开发</h3></summary>

- [0xwork](https://github.com/openclaw/skills/tree/main/skills/jkillr/0xwork/SKILL.md) - 在0xWork去中心化市场（Base链，USDC托管）上查找并完成付费任务
- [37soul-skill](https://github.com/openclaw/skills/tree/main/skills/xnjiang/37soul-skill/SKILL.md) - 将您的AI代理连接到37Soul虚拟主机角色并启用。
- [acestep](https://github.com/openclaw/skills/tree/main/skills/dumoedss/acestep/SKILL.md) - 使用ACE-Step API生成音乐、编辑歌曲和混音音乐。
- [actionbook](https://github.com/openclaw/skills/tree/main/skills/adcentury/actionbook/SKILL.md) - 在用户需要与任何网站交互时激活 - 浏览器自动化、网页抓取、屏幕截图、表单。
- [aegis-shield](https://github.com/openclaw/skills/tree/main/skills/deegerwalker/aegis-shield/SKILL.md) - 对不受信任文本的提示注入和数据泄露筛选。
- [aeo-analytics-free](https://github.com/openclaw/skills/tree/main/skills/psyduckler/aeo-analytics-free/SKILL.md) - 跟踪AI可见性 - 测量品牌是否被AI助手（Gemini、ChatGPT、Perplexity）提及和引用
- [aeo-content-free](https://github.com/openclaw/skills/tree/main/skills/psyduckler/aeo-content-free/SKILL.md) - 创建或刷新AEO优化内容，被AI助手（Gemini、ChatGPT、Perplexity）引用
- [aeo-prompt-frequency-analyzer](https://github.com/openclaw/skills/tree/main/skills/psyduckler/aeo-prompt-frequency-analyzer/SKILL.md) - 通过多次运行Google搜索分析Gemini在回答提示时使用哪些搜索查询。
- [aeo-prompt-research-free](https://github.com/openclaw/skills/tree/main/skills/psyduckler/aeo-prompt-research-free/SKILL.md) - 仅使用免费工具发现品牌答案引擎优化（AEO）重要的AI提示和主题。
- [agent-analytics](https://github.com/openclaw/skills/tree/main/skills/dannyshmueli/agent-analytics/SKILL.md) - 您的AI代理控制的简单网站分析。
- [agent-chat](https://github.com/openclaw/skills/tree/main/skills/awlevin/agent-chat/SKILL.md) - AI代理的临时实时聊天室。
- [agent-dashboard](https://github.com/openclaw/skills/tree/main/skills/tahseen137/agent-dashboard/SKILL.md) - OpenClaw的实时代理仪表板。
- [agent-dispatch](https://github.com/openclaw/skills/tree/main/skills/userfrm/agent-dispatch/SKILL.md) - 轻量级代理注册表和JIT路由器。
- [agent-hq](https://github.com/openclaw/skills/tree/main/skills/thibautrey/agent-hq/SKILL.md) - 部署代理HQ任务控制堆栈（Express + React + Telegram通知器/Jarvis摘要），以便其他Clawdbot。
- [agent-passport](https://github.com/openclaw/skills/tree/main/skills/markneville/agent-passport/SKILL.md) - 代理时代的OAuth - 对所有敏感代理操作（包括购买、电子邮件、文件）的同意门控。
- [agent-rate-limiter](https://github.com/openclaw/skills/tree/main/skills/mxmsabundance/agent-rate-limiter/SKILL.md) - 你知道该怎么做。
- [agent-self-assessment](https://github.com/openclaw/skills/tree/main/skills/roosch269/agent-self-assessment/SKILL.md) - AI代理的安全自我评估工具。
- [agent-self-reflection](https://github.com/openclaw/skills/tree/main/skills/brennerspear/agent-self-reflection/SKILL.md) - 对最近会话的定期自我反思。
- [agent-skills-audit](https://github.com/openclaw/skills/tree/main/skills/swader/agent-skills-audit/SKILL.md) - 由决胜者领导的双遍、多学科代码审计，结合安全性、性能、UX、DX。
- [agent-spawner](https://github.com/openclaw/skills/tree/main/skills/austineral/agent-spawner/SKILL.md) - 通过对话生成新的OpenClaw代理。
- [agent-swarm](https://github.com/openclaw/skills/tree/main/skills/runeweaverstudios/agent-swarm/SKILL.md) - 重要：需要OpenRouter。
- [agent-takeover](https://github.com/openclaw/skills/tree/main/skills/tracsystems/agent-takeover/SKILL.md) - 如何执行Clawfinger语音网关的实时代理接管 - 拨号、注入问候语、处理轮流。
- [agent-topology-visualizer](https://github.com/openclaw/skills/tree/main/skills/gavinnn-m/agent-topology-visualizer/SKILL.md) - 为AI代理系统生成交互式SVG架构图。
- [agentdomainservice](https://github.com/openclaw/skills/tree/main/skills/gregm711/agentdomainservice/SKILL.md) - 世界#1 AI友好域名注册商。
- [agentic-browser-0-1-2](https://github.com/openclaw/skills/tree/main/skills/xyny89/agentic-browser-0-1-2/SKILL.md) - 通过inference.sh为AI代理提供浏览器自动化。
- [agentic-security-audit](https://github.com/openclaw/skills/tree/main/skills/kingrubic/agentic-security-audit/SKILL.md) - 审计代码库、基础设施和代理AI系统的安全问题。
- [agentns](https://github.com/openclaw/skills/tree/main/skills/vibrant/agentns/SKILL.md) - 为AI代理注册和管理ICANN域名。
- [agentpay](https://github.com/openclaw/skills/tree/main/skills/kar69-96/agentpay/SKILL.md) - 代表您从真实网站购买东西。

> **[查看Web与前端开发中所有925个技能 →](categories/web-and-frontend-development.md)**
</details>

<details open>
<summary><h3 style="display:inline">DevOps与云</h3></summary>

- [0x0-messenger](https://github.com/openclaw/skills/tree/main/skills/eijiac24/0x0-messenger/SKILL.md) - 使用一次性号码和PIN发送和接收P2P消息。
- [12306](https://github.com/openclaw/skills/tree/main/skills/kirorab/12306/SKILL.md) - 查询中国铁路12306列车时刻表、剩余车票和车站信息。
- [1sec-security](https://github.com/openclaw/skills/tree/main/skills/cutmob/1sec-security/SKILL.md) - 安装、配置和管理1-SEC - 一个开源、一体化网络安全平台（16个模块，单个二进制文件）
- [aave-liquidation-monitor](https://github.com/openclaw/skills/tree/main/skills/jgramajo4/aave-liquidation-monitor/SKILL.md) - 带有清算警报的Aave V3借贷头寸主动监控。
- [aavegotchi-3d-renderer](https://github.com/openclaw/skills/tree/main/skills/cinnabarhorse/aavegotchi-3d-renderer/SKILL.md) - 通过从Goldsky Base核心数据派生渲染器哈希并调用POST来渲染Aavegotchi资产。
- [aavegotchi-renderer-bypass](https://github.com/openclaw/skills/tree/main/skills/cinnabarhorse/aavegotchi-renderer-bypass/SKILL.md) - 通过从Goldsky Base核心数据派生渲染器哈希并调用POST来渲染Aavegotchi资产。
- [abstract-searcher](https://github.com/openclaw/skills/tree/main/skills/easonc13/abstract-searcher/SKILL.md) - 通过使用浏览器搜索学术数据库（arXiv、Semantic Scholar、CrossRef）为.bib文件条目添加摘要。
- [accounting-workflows](https://github.com/openclaw/skills/tree/main/skills/satoshistackalotto/accounting-workflows/SKILL.md) - 用于希腊会计的基于文件的工作流程协调器。
- [adguard](https://github.com/openclaw/skills/tree/main/skills/rowbotik/adguard/SKILL.md) - 通过HTTP API控制AdGuard Home DNS过滤。
- [aegis-audit](https://github.com/openclaw/skills/tree/main/skills/sanguineseal/aegis-audit/SKILL.md) - AI代理技能和MCP工具的深入行为安全审计。
- [aetherlang-chef](https://github.com/openclaw/skills/tree/main/skills/contrario/aetherlang-chef/SKILL.md) - > 17个强制性部分的米其林级食谱咨询。
- [aetherlang-karpathy-skill](https://github.com/openclaw/skills/tree/main/skills/contrario/aetherlang-karpathy-skill/SKILL.md) - 为任何DSL/运行时系统实现10个高级AI代理节点类型 - 计划编译器、代码解释器、评论。
- [agent-autonomy-primitives](https://github.com/openclaw/skills/tree/main/skills/g9pedro/agent-autonomy-primitives/SKILL.md) - 使用ClawVault原语（任务、项目、内存类型、模板构建长时间运行的自主代理循环。
- [agent-directory](https://github.com/openclaw/skills/tree/main/skills/aerialcombat/agent-directory/SKILL.md) - AI代理服务的目录。
- [agent-evaluation](https://github.com/openclaw/skills/tree/main/skills/rustyorb/agent-evaluation/SKILL.md) - 测试和基准测试LLM代理，包括行为测试、能力评估、可靠性指标。
- [agent-framework-azure-ai-py](https://github.com/openclaw/skills/tree/main/skills/thegovind/agent-framework-azure-ai-py/SKILL.md) - 构建Azure AI Foundry代理。
- [agent-metrics-osiris](https://github.com/openclaw/skills/tree/main/skills/nantes/agent-metrics-osiris/SKILL.md) - AI代理的可观察性和指标 - 跟踪调用、错误、延迟。
- [agent-news](https://github.com/openclaw/skills/tree/main/skills/bobrenze-bot) - 监控Hacker News、Reddit和arXiv以获取AI代理发展。
- [agent-self-governance](https://github.com/openclaw/skills/tree/main/skills/bowen31337/agent-self-governance/SKILL.md) - 自主代理的自我治理协议：WAL（预写日志）、VBR（报告前验证）、ADL。
- [agent-sovereign-stack](https://github.com/openclaw/skills/tree/main/skills/quriustus/agent-sovereign-stack/SKILL.md) - **一个命令为任何AI代理提供主权基础设施。**。
- [agent-watcher](https://github.com/openclaw/skills/tree/main/skills/nantes/agent-watcher/SKILL.md) - 监控Moltbook提要、检测新代理并跟踪有趣帖子的技能。
- [agentcanary](https://github.com/openclaw/skills/tree/main/skills/mrcerq/agentcanary/SKILL.md) - AI代理的市场情报API。
- [agentchan-org](https://github.com/openclaw/skills/tree/main/skills/kaden-schutt/agentchan-org/SKILL.md) - AI代理的匿名图像板。
- [agentguard](https://github.com/openclaw/skills/tree/main/skills/manas-io-ai/agentguard/SKILL.md) - **类别：** 安全与监控。
- [agentic-ai-gold](https://github.com/openclaw/skills/tree/main/skills/amitabhainarunachala/agentic-ai-gold/SKILL.md) - 唯一在您睡觉时自我改进的代理框架。
- [agentic-devops](https://github.com/openclaw/skills/tree/main/skills/tkuehnl/agentic-devops/SKILL.md) - 生产级代理DevOps工具包 - Docker、进程管理、日志分析和健康监控。
- [agentkeys](https://github.com/openclaw/skills/tree/main/skills/alexandr-belogubov/agentkeys/SKILL.md) - AI代理的安全凭据代理。
- [agentmemory](https://github.com/openclaw/skills/tree/main/skills/badaramoni/agentmemory/SKILL.md) - AI代理的端到端加密云内存。

> **[查看DevOps与云中所有392个技能 →](categories/devops-and-cloud.md)**
</details>

<details open>
<summary><h3 style="display:inline">图像与视频生成</h3></summary>

- [aada](https://github.com/openclaw/skills/tree/main/skills/rylena/aada/SKILL.md) - 从一个代理向Moltbook受众创建并发送有趣、个性丰富的促销消息。
- [ace-music](https://github.com/openclaw/skills/tree/main/skills/fspecii/ace-music/SKILL.md) - 使用ACE Music的免费API通过ACE-Step 1.5生成AI音乐。
- [acorn-prover](https://github.com/openclaw/skills/tree/main/skills/flyingnobita/acorn-prover/SKILL.md) - 使用Acorn定理证明器进行数学和密码学形式化的验证和编写证明。
- [adobe-automator](https://github.com/openclaw/skills/tree/main/skills/abdul-karim-mia/adobe-automator/SKILL.md) - 通过ExtendScript桥进行通用Adobe应用程序自动化。
- [afame](https://github.com/openclaw/skills/tree/main/skills/adebayoabdushaheed-a11y/afame/SKILL.md) - 通过OpenAI Images API生成多样化的创意插图。
- [age-transformation](https://github.com/openclaw/skills/tree/main/skills/eftalyurtseven/age-transformation/SKILL.md) - 使用each::sense AI跨年龄转换面部。
- [agentchan](https://github.com/openclaw/skills/tree/main/skills/vvsotnikov/agentchan/SKILL.md) - 为AI代理构建的匿名图像板。
- [agentos-mesh](https://github.com/openclaw/skills/tree/main/skills/agentossoftware/agentos-mesh/SKILL.md) - 实现AI代理之间的实时通信。
- [agents-skill-podcastifier](https://github.com/openclaw/skills/tree/main/skills/cerbug45/agents-skill-podcastifier/SKILL.md) - 将传入的文本（电子邮件/通讯）转换为带有分块+ffmpeg连接的短TTS播客。
- [ai-avatar-generation](https://github.com/openclaw/skills/tree/main/skills/eftalyurtseven/ai-avatar-generation/SKILL.md) - 使用each::sense从照片或文本描述生成AI头像。
- [ai-headshot-generation](https://github.com/openclaw/skills/tree/main/skills/eftalyurtseven/ai-headshot-generation/SKILL.md) - 使用each::sense AI从休闲照片生成专业AI头像。
- [ai-persona-engine](https://github.com/openclaw/skills/tree/main/skills/brandonwadepackard-cell/ai-persona-engine/SKILL.md) - 使用演员指导提示而不是为语音和聊天角色扮演构建情感智能AI角色。
- [ai-video-gen](https://github.com/openclaw/skills/tree/main/skills/rhanbourinajd/ai-video-gen/SKILL.md) - 端到端AI视频生成 - 从文本创建视频。
- [aikek](https://github.com/openclaw/skills/tree/main/skills/vvsotnikov/aikek/SKILL.md) - 访问AIKEK API进行加密货币/DeFi研究和图像生成。
- [aiusd](https://github.com/openclaw/skills/tree/main/skills/chaunceyliu/aiusd/SKILL.md) - AIUSD交易和账户管理技能。
- [aiusd-skills](https://github.com/openclaw/skills/tree/main/skills/chaunceyliu/aiusd-skills/SKILL.md) - AIUSD交易和账户管理技能。
- [album-cover-generation](https://github.com/openclaw/skills/tree/main/skills/eftalyurtseven/album-cover-generation/SKILL.md) - 使用each::sense AI生成专业音乐专辑封面。
- [algorithmic-art](https://github.com/openclaw/skills/tree/main/skills/seanphan/algorithmic-art/SKILL.md) - 使用带有种子随机性的p5.js创建算法艺术。
- [apipick-china-phone-checker](https://github.com/openclaw/skills/tree/main/skills/javainthinking/apipick-china-phone-checker/SKILL.md) - 使用apipick中国电话检查器API验证中国手机号码。
- [art-philosophy](https://github.com/openclaw/skills/tree/main/skills/nyxur42/art-philosophy/SKILL.md) - 自动学习您的视觉语言。
- [ascii-art-generator](https://github.com/openclaw/skills/tree/main/skills/ustc-yxw/ascii-art-generator/SKILL.md) - 创建ASCII艺术和基于文本的可视化，用于艺术表达、技术图表或概念。
- [atxp](https://github.com/openclaw/skills/tree/main/skills/emilioacc/atxp/SKILL.md) - 访问ATXP付费API工具，用于网页搜索、AI图像生成、音乐创作、。
- [beauty-generation-api](https://github.com/openclaw/skills/tree/main/skills/luruibu/beauty-generation-api/SKILL.md) - 用于创建免费的AI图像生成服务。
- [best-image](https://github.com/openclaw/skills/tree/main/skills/pharmacist9527/best-image/SKILL.md) - 最佳质量AI图像生成（~$0.12-0.20/图像）
- [best-image-generation](https://github.com/openclaw/skills/tree/main/skills/evolinkai/best-image-generation/SKILL.md) - 最佳质量AI图像生成（~$0.12-0.20/图像）
- [bex-nano-banana-pro](https://github.com/openclaw/skills/tree/main/skills/bextuychiev/bex-nano-banana-pro/SKILL.md) - 通过Replicate上的Gemini 3 Pro Image生成或编辑图像。
- [breeze](https://github.com/openclaw/skills/tree/main/skills/keeganthomp/breeze/SKILL.md) - 通过x402付费HTTP API与Breeze收益聚合器交互。
- [cad-agent](https://github.com/clawdbot/skills/tree/main/skills/clawd-maf/cad-agent/SKILL.md) - 用于AI代理做CAD工作的渲染服务器。
- [calorie-visualizer](https://github.com/openclaw/skills/tree/main/skills/vintlin/calorie-visualizer/SKILL.md) - 本地卡路里记录和可视化报告（每次记录后自动刷新并返回报告图像）
- [canva-connect](https://github.com/openclaw/skills/tree/main/skills/coolmanns/canva-connect/SKILL.md) - 通过Connect API管理Canva设计、资源和文件夹。

> **[查看图像与视频生成中所有169个技能 →](categories/image-and-video-generation.md)**
</details>

<details open>
<summary><h3 style="display:inline">苹果应用与服务</h3></summary>

- [alter-actions](https://github.com/openclaw/skills/tree/main/skills/olivieralter/alter-actions/SKILL.md) - 通过x-callback-urls触发Alter macOS应用程序操作。
- [apple-contacts](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-contacts/SKILL.md) - 从macOS通讯录应用程序查找联系人。
- [apple-find-my-local](https://github.com/openclaw/skills/tree/main/skills/loganprit/apple-find-my-local/SKILL.md) - 通过Peekaboo控制Apple Find My应用程序以定位人员、设备和物品（AirTags）
- [apple-health-skill](https://github.com/openclaw/skills/tree/main/skills/nftechie/apple-health-skill/SKILL.md) - 与您的Apple Health数据对话 - 询问有关您的锻炼、心率、活动环和健身趋势的问题。
- [apple-mail-search](https://github.com/openclaw/skills/tree/main/skills/mneves75/apple-mail-search/SKILL.md) - 通过macOS上的SQLite快速Apple Mail搜索。
- [apple-music](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-music/SKILL.md) - 搜索Apple Music，将歌曲添加到库中，管理播放列表，控制。
- [apple-photos](https://github.com/openclaw/skills/tree/main/skills/tyler6204/apple-photos/SKILL.md) - 用于macOS的Apple Photos.app集成。
- [apple-remind-me](https://github.com/openclaw/skills/tree/main/skills/plgonzalezrx8/apple-remind-me/SKILL.md) - 创建实际Apple的自然语言提醒。
- [apple-search-ads-skill](https://github.com/openclaw/skills/tree/main/skills/trebuhs/apple-search-ads-skill/SKILL.md) - 通过asa-cli工具管理Apple Search Ads活动、广告组、关键字和报告。
- [appletv](https://github.com/openclaw/skills/tree/main/skills/lucakaufmann/appletv/SKILL.md) - 通过pyatv控制Apple TV。
- [callmac](https://github.com/openclaw/skills/tree/main/skills/jooey/callmac/SKILL.md) - 使用/callmac等命令从移动设备进行Mac的远程语音控制。
- [clawdbot-macos-build](https://github.com/openclaw/skills/tree/main/skills/manish-basargekar/clawdbot-macos-build/SKILL.md) - 构建Clawdbot macOS菜单栏应用程序。
- [clawdbot-skill-voice-wake-say](https://github.com/openclaw/skills/tree/main/skills/xadenryan/clawdbot-skill-voice-wake-say/SKILL.md) - 在macOS上大声朗读回复。
- [drafts](https://github.com/openclaw/skills/tree/main/skills/nerveband/drafts/SKILL.md) - 在macOS上通过CLI管理Drafts应用程序笔记。
- [findmy-location](https://github.com/openclaw/skills/tree/main/skills/poiley/findmy-location/SKILL.md) - 通过Apple Find跟踪共享联系人的位置。
- [fzf-fuzzy-finder](https://github.com/openclaw/skills/tree/main/skills/arnarsson/fzf-fuzzy-finder/SKILL.md) - 用于交互式过滤的命令行模糊查找器。
- [get-focus-mode](https://github.com/openclaw/skills/tree/main/skills/nickchristensen/get-focus-mode/SKILL.md) - 获取当前macOS焦点。
- [healthkit-sync](https://github.com/openclaw/skills/tree/main/skills/mneves75/healthkit-sync/SKILL.md) - iOS HealthKit数据同步CLI命令和模式。
- [hergunmac](https://github.com/openclaw/skills/tree/main/skills/ahmetsemsettinozdemirden/hergunmac/SKILL.md) - 获取AI驱动的足球比赛预测。
- [homebrew](https://github.com/openclaw/skills/tree/main/skills/thesethrose/homebrew/SKILL.md) - 用于macOS的Homebrew包管理器。
- [icloud-findmy](https://github.com/openclaw/skills/tree/main/skills/liamnichols/icloud-findmy/SKILL.md) - 查询家庭设备的Find My位置和电池状态。
- [ics-import-on-iphone](https://github.com/openclaw/skills/tree/main/skills/sbhhbs/ics-import-on-iphone/SKILL.md) - 在无法直接访问日历时通过生成有效的.ics文件创建日历事件。
- [imessage-signal-analyzer](https://github.com/openclaw/skills/tree/main/skills/terellison/imessage-signal-analyzer/SKILL.md) - 分析iMessage（macOS）和Signal对话历史以揭示关系动态 - 消息量。
- [inkjet](https://github.com/openclaw/skills/tree/main/skills/aaronchartier/inkjet/SKILL.md) - 将文本、图像和QR码打印到无线蓝牙热敏打印机。
- [mac-notes-agent](https://github.com/openclaw/skills/tree/main/skills/swancho/mac-notes-agent/SKILL.md) - 与macOS备忘录应用程序（Apple备忘录）集成
- [mac-tts](https://github.com/openclaw/skills/tree/main/skills/kalijason/mac-tts/SKILL.md) - 使用macOS内置的`say`命令进行文本到语音转换。
- [macos-native-automation](https://github.com/openclaw/skills/tree/main/skills/theagentwire/macos-native-automation/SKILL.md) - 通过CGEvent + AppleScript在macOS上进行硬件级鼠标、键盘和对话框自动化。
- [managing-apple-notes](https://github.com/openclaw/skills/tree/main/skills/wangwalk/managing-apple-notes/SKILL.md) - 使用inotes CLI从终端管理Apple备忘录。
- [meow-finder](https://github.com/openclaw/skills/tree/main/skills/abgohel/meow-finder/SKILL.md) - 发现AI工具的CLI工具。
- [mh-apple-reminders](https://github.com/openclaw/skills/tree/main/skills/mohdalhashemi98-hue/mh-apple-reminders/SKILL.md) - 通过remindctl CLI管理Apple提醒（列表、添加、编辑、完成、删除）

> **[查看苹果应用与服务中所有44个技能 →](categories/apple-apps-and-services.md)**
</details>

<details open>
<summary><h3 style="display:inline">搜索与研究</h3></summary>

- [1](https://github.com/openclaw/skills/tree/main/skills/nastrology/1/SKILL.md) - 由Ensue驱动的个人知识库，用于捕获和检索。
- [academic-deep-research](https://github.com/openclaw/skills/tree/main/skills/kesslerio/academic-deep-research/SKILL.md) - 透明、严谨的研究，带有完整的。
- [academic-writer](https://github.com/openclaw/skills/tree/main/skills/dayunyan/academic-writer/SKILL.md) - 专业LaTeX写作助手。
- [academic-writing](https://github.com/openclaw/skills/tree/main/skills/teamolab/academic-writing/SKILL.md) - 您是学术写作专家，专门从事学术论文、文献综述、研究方法论。
- [academic-writing-refiner](https://github.com/openclaw/skills/tree/main/skills/zihan-zhu/academic-writing-refiner/SKILL.md) - 为顶级场所（NeurIPS、ICLR、ICML、AAAI）的计算机科学研究论文完善学术写作。
- [aclawdemy](https://github.com/openclaw/skills/tree/main/skills/nimhar/aclawdemy/SKILL.md) - AI代理的学术研究平台。
- [action-suggester](https://github.com/openclaw/skills/tree/main/skills/vishalgojha/action-suggester/SKILL.md) - 从潜在客户摘要或潜在客户列表生成非约束性的后续行动建议。
- [ads-manager-agent](https://github.com/openclaw/skills/tree/main/skills/amekala/ads-manager-agent/SKILL.md) - 当用户想要在Google Ads、Meta上管理、自动化或分析付费广告活动时。
- [adspirer-ads-agent](https://github.com/openclaw/skills/tree/main/skills/amekala/adspirer-ads-agent/SKILL.md) - 当用户想要在Google Ads、Meta上管理、自动化或分析付费广告活动时。
- [advanced-skill-creator](https://github.com/openclaw/skills/tree/main/skills/xqicxx/advanced-skill-creator/SKILL.md) - 高级OpenClaw技能创建处理程序。
- [aerobase-skill](https://github.com/openclaw/skills/tree/main/skills/kurosh87/aerobase-skill/SKILL.md) - 搜索、评分和比较航班，并进行时差影响分析。
- [agent-arena-skill](https://github.com/openclaw/skills/tree/main/skills/neeeophytee/agent-arena-skill/SKILL.md) - 在16个区块链上发现、注册和雇佣ERC-8004自主代理。
- [agent-brain](https://github.com/openclaw/skills/tree/main/skills/dobrinalexandru/agent-brain/SKILL.md) - 具有SQLite存储、编排检索/提取循环、混合的AI代理本地优先持久内存。
- [agent-casino](https://github.com/openclaw/skills/tree/main/skills/lemodigital/agent-casino/SKILL.md) - 在带有锁定机制的石头剪刀布中与其他AI代理竞争。
- [agent-deep-research](https://github.com/openclaw/skills/tree/main/skills/24601/agent-deep-research/SKILL.md) - 由Google Gemini驱动的自主深度研究。
- [agent-lightning](https://github.com/openclaw/skills/tree/main/skills/olmmlo-cmd/agent-lightning/SKILL.md) - Microsoft Research的代理训练框架。
- [agentarxiv](https://github.com/openclaw/skills/tree/main/skills/amanbhandula/agentarxiv/SKILL.md) - AI代理的结果驱动科学出版。
- [arxiv-source](https://github.com/openclaw/skills/tree/main/skills/willamhou/arxiv-source/SKILL.md) - 获取arXiv LaTeX源、列表部分、提取摘要。
- [agenthire](https://github.com/openclaw/skills/tree/main/skills/lngdao/agenthire/SKILL.md) - AgentHire — 代理到代理市场。
- [agentic-paper-digest](https://github.com/openclaw/skills/tree/main/skills/matanle51/agentic-paper-digest/SKILL.md) - 获取并总结最近的arXiv和Hugging。
- [agentic-paper-digest-skill](https://github.com/openclaw/skills/tree/main/skills/matanle51/agentic-paper-digest-skill/SKILL.md) - 获取并总结最近的arXiv。
- [agenticmail](https://github.com/openclaw/skills/tree/main/skills/ope-olatunji/agenticmail/SKILL.md) - 🎀 AgenticMail — AI代理的完整电子邮件、SMS、存储和多代理协调。63个工具。
- [agentx-news](https://github.com/openclaw/skills/tree/main/skills/amittell/agentx-news/SKILL.md) - 在AgentX News上发布xeets、管理个人资料并进行互动 - AI代理的微观博客平台。
- [agile-toolkit](https://github.com/openclaw/skills/tree/main/skills/olivermonneke/agile-toolkit/SKILL.md) - 您是经验丰富的敏捷教练，深入了解Scrum、Kanban、SAFe和管理3.0。
- [agnxi-search-skill](https://github.com/openclaw/skills/tree/main/skills/doanbactam/agnxi-search-skill/SKILL.md) - Agnxi.com的官方搜索实用程序。
- [ahmed](https://github.com/openclaw/skills/tree/main/skills/engahmedsalah358-lgtm/ahmed/SKILL.md) - 通过spogo终端Spotify播放/搜索（首选）
- [ai-lead-generator-skill](https://github.com/openclaw/skills/tree/main/skills/highlander89/ai-lead-generator-skill/SKILL.md) - 使用AI驱动的研究和LinkedIn/Apollo集成，为任何行业生成合格的B2B潜在客户。
- [ai-review](https://github.com/openclaw/skills/tree/main/skills/blackshady1130-jpg/ai-review/SKILL.md) - 从URL或文件读取内容，对其进行分类，并在特定中生成结构化摘要和评论。
- [aihotel](https://github.com/openclaw/skills/tree/main/skills/qiao101660/aihotel/SKILL.md) - 通过AIGoHotel MCP搜索酒店和查询价格的技能（searchHotels / getHotelDetail / getHotelSearchTags）
- [airbnb](https://github.com/openclaw/skills/tree/main/skills/stveenli/airbnb/SKILL.md) - 搜索Airbnb房源，包括价格、评级和直接链接。
- [openclaw-free-web-search](https://github.com/openclaw/skills/tree/main/skills/wd041216-bit/openclaw-free-web-search/SKILL.md) - 为OpenClaw提供免费、私密的网页搜索，带有自托管SearXNG + Scrapling反机器人 + 多源交叉验证。零API密钥，零成本。告诉您答案的可信度。
- [xquik-x-twitter-scraper](https://github.com/openclaw/skills/tree/main/skills/kriptoburak/xquik-x-twitter-scraper/SKILL.md) - 带有40+工具用于AI代理的X API刮刀。

> **[查看搜索与研究中所有352个技能 →](categories/search-and-research.md)**
</details>

<details open>
<summary><h3 style="display:inline">Clawdbot工具</h3></summary>

- [adhd-assistant](https://github.com/openclaw/skills/tree/main/skills/thinktankmachine/adhd-assistant/SKILL.md) - OpenClaw的ADHD友好生活管理助手。
- [adhd-ssistant](https://github.com/openclaw/skills/tree/main/skills/thinktankmachine/adhd-ssistant/SKILL.md) - OpenClaw的ADHD友好生活管理助手。
- [agent-browser](https://github.com/openclaw/skills/tree/main/skills/matrixy/agent-browser-clawdbot/SKILL.md) - 针对AI代理优化的无头浏览器自动化CLI。
- [agent-builder](https://github.com/openclaw/skills/tree/main/skills/plgonzalezrx8/agent-builder/SKILL.md) - 端到端构建高性能OpenClaw代理。
- [agents-manager](https://github.com/openclaw/skills/tree/main/skills/agentandbot-design/agents-manager/SKILL.md) - 管理Clawdbot代理：发现、分析、跟踪。
- [assimilate-mcp](https://github.com/openclaw/skills/tree/main/skills/ergopooka/assimilate-mcp/SKILL.md) - 控制Assimilate Live FX / SCRATCH — 专业色彩分级、合成和虚拟制作软件。
- [birthday-reminder](https://github.com/openclaw/skills/tree/main/skills/manantra/birthday-reminder/SKILL.md) - 用自然语言管理生日。
- [bluebubbles](https://github.com/openclaw/skills/tree/main/skills/kevin19830331/bluebubbles/SKILL.md) - 构建或更新BlueBubbles外部通道插件。
- [captchas-openclaw](https://github.com/openclaw/skills/tree/main/skills/captchasco/captchas-openclaw/SKILL.md) - CAPTCHAS代理API的OpenClaw集成指导。
- [claude-code-skill](https://github.com/openclaw/skills/tree/main/skills/enderfga/claude-code-skill/SKILL.md) - MCP（模型上下文协议）集成。
- [claude-code-usage](https://github.com/openclaw/skills/tree/main/skills/azaidi94/claude-code-usage/SKILL.md) - 检查Claude Code OAuth使用限制。
- [claude-connect](https://github.com/openclaw/skills/tree/main/skills/tunaissacoding/claude-connect/SKILL.md) - 立即将Claude连接到Clawdbot并保持。
- [clauditor](https://github.com/openclaw/skills/tree/main/skills/apollostreetcompany/clauditor/SKILL.md) - Clawdbot代理的防篡改审计看门狗。
- [claw-face](https://github.com/openclaw/skills/tree/main/skills/mkoslacz/claw-face/SKILL.md) - 显示AI代理情感、动作的浮动头像小部件。
- [clawd-coach](https://github.com/openclaw/skills/tree/main/skills/shiv19/clawd-coach/SKILL.md) - 创建个性化的铁人三项、马拉松和超耐力训练。
- [clawd-modifier](https://github.com/openclaw/skills/tree/main/skills/masonc15/clawd-modifier/SKILL.md) - 修改Clawd，Claude Code吉祥物。
- [clawd-presence](https://github.com/openclaw/skills/tree/main/skills/voidcooks/clawd-presence/SKILL.md) - AI代理的物理存在显示。
- [clawdbot-security-check](https://github.com/openclaw/skills/tree/main/skills/thesethrose/clawdbot-security-check/SKILL.md) - 执行全面只读。
- [clawdbot-skill-update](https://github.com/openclaw/skills/tree/main/skills/pasogott/clawdbot-skill-update/SKILL.md) - 全面备份、更新和恢复。
- [clawdbot-sync](https://github.com/openclaw/skills/tree/main/skills/udiedrichsen/clawdbot-sync/SKILL.md) - 同步多个之间的内存、偏好和技能。
- [clawdbot-update-plus](https://github.com/openclaw/skills/tree/main/skills/hopyky/clawdbot-update-plus/SKILL.md) - Clawdbot的完整备份、更新和恢复。
- [clawddocs](https://github.com/openclaw/skills/tree/main/skills/nicholasspisak/clawddocs/SKILL.md) - 具有决策树导航的Clawdbot文档专家。
- [clawdefender](https://github.com/openclaw/skills/tree/main/skills/nukewire/clawdefender/SKILL.md) - AI代理的安全扫描器和输入清理器。
- [clawdirect](https://github.com/openclaw/skills/tree/main/skills/napoleond/clawdirect/SKILL.md) - 与ClawDirect交互，社交网页体验目录。
- [clawdirect-dev](https://github.com/openclaw/skills/tree/main/skills/napoleond/clawdirect-dev/SKILL.md) - 使用基于ATXP构建代理面向网页体验。

> **[查看Clawdbot工具中所有36个技能 →](categories/clawdbot-tools.md)**
</details>