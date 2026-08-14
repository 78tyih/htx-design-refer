# HTX Design Refer

> 一个可被 Agent 直接调用的 **HTX-inspired Brand Design Reference System**。
>
> 将用户提供的 `htx-brand`、`htx-social-poster`、`htx-huobao-fast` 三套 Skill，重新整理成一套可复用、可路由、可审查的 HTX 视觉系统。

`htx-design-refer` 不是一张固定海报模板，也不是简单把 HTX 蓝色套到任何设计上。

它是一层 **Design Reference / Style Router**：让 Codex、Cursor、Trae、OpenHands 或其他支持 Agent Skills / Rules / Instructions 的 Agent，在设计海报、长图、PPT、PDF、Landing Page、信息图或活动视觉时，先加载统一的 HTX 品牌语法，再完成具体任务。

当前系统包含：

- **6 个 Visual Families**；
- **4 个 Source-grounded Medium Modes**；
- **3 个 Derived Adapters**；
- 结构化 **Brand Tokens**；
- Logo / Safe Area / Typography / Background / Huobao 角色约束；
- 统一 Quality Gate 与 Anti-Identity 规则。

---

## Design Equation

HTX Design Refer 的基础公式是：

```text
clear commercial hierarchy
+ disciplined brand blue
+ high legibility
+ controlled campaign emphasis
+ strict asset placement
```

可以理解为：

> **清晰的商业信息层级 + 克制而明确的 HTX 品牌蓝 + 高可读性 + 受控的 Campaign 强调 + 严格的品牌资产位置纪律。**

它强调的是「信息先到达，品牌随后被记住」，而不是用大量装饰制造所谓的 Crypto 科技感。

核心原则：

- Communication before decoration；
- Hierarchy before visual effects；
- Brand field before generic gradients；
- Copy fidelity before invented slogans；
- Real assets before decorative stand-ins；
- Safe area before filling empty space。

---

## What this Skill can do

适合让 Agent：

- 生成 **HTX Campaign / Social Poster**；
- 设计 **奖励、返佣、交易赛、活动机制**视觉；
- 设计 **产品介绍 / 社群 / 招募 / 公告**视觉；
- 生成 **长图 / 规则说明 / 多模块运营图**；
- 生成 **火宝角色活动海报**；
- 将同一品牌语法延伸到 **PPT / PDF / Landing Page / Infographic**；
- 用 `review-only` 模式检查已有设计是否已经漂移成通用 Crypto 风格。

---

# 6 Visual Families

## 01 — `brand-blue-field`

**品牌蓝场**

```text
HTX Blue Field
+ strong left-aligned title
+ high contrast copy
+ minimal decoration
```

主要特征：

- HTX 品牌蓝或蓝色纵向渐变作为主场域；
- 标题通常左对齐；
- 白字 / 黑字根据实际背景对比选择；
- Campaign 本身是主视觉，而不是额外堆图形；
- 适合保持明确、成熟、商业化的 HTX 品牌识别。

适合：

- 常规 Campaign；
- Event Launch；
- 产品发布；
- 邀请活动；
- 单一利益点活动。

避免：

- Neon Crypto；
- Glassmorphism；
- 随机 Grid；
- 无意义粒子、光线、轨道；
- 没有素材时硬塞插画。

---

## 02 — `blue-grid-reward`

**蓝色栅格奖励**

```text
blue grid / light columns
+ oversized reward value
+ calm text zone
+ commercial emphasis
```

适合：

- 奖励金额；
- 返佣；
- 百分比利益；
- Trading Competition；
- Prize Pool；
- 无人物素材的活动机制海报。

核心原则：**让金额 / 百分比 / 奖励机制成为真正的视觉 Hero。**

不要把正文压到背景右侧高信息的光柱 / 栅格区域，也不要拉伸背景素材。

---

## 03 — `soft-blue-information`

**柔和蓝白信息**

```text
soft white-to-blue field
+ calm information hierarchy
+ upper-left title
+ friendly product tone
```

适合：

- Recruitment；
- Community；
- 产品介绍；
- 温和公告；
- 信息型 Social Poster。

相比 `blue-grid-reward`，它不是在强调一个极大的 Reward Number，而是在建立一个更友好、易读的信息场。

---

## 04 — `blue-white-hero`

**蓝白分区 Hero**

```text
blue hero
+ continuous white information field
+ black body copy
+ restrained section dividers
```

这是 HTX Design Refer 中最适合承载**长内容与结构化信息**的 Family。

适合：

- Long-form Operation Graphic；
- 规则说明；
- 多步骤活动；
- 多模块产品介绍；
- PPT / PDF；
- Landing Page。

Source guidance 中，当内容合适时，可参考：

```text
Hero: 52–58%
Information field: 42–48%
```

重点不是机械执行比例，而是保持 Hero 主导整体视觉节奏。

---

## 05 — `vip-gold`

**VIP 金色**

```text
restrained gold gradient
+ institutional hierarchy
+ black copy on light field
+ premium without luxury cliché
```

适合：

- VIP；
- Institutional；
- OTC / Premium Service；
- 高价值客户权益；
- Partnership / Institutional Materials。

这里的 Gold 不是“黑金奢华风”。

应避免：

- 大量金属 3D；
- 黑金 Casino 视觉；
- 复杂装饰边框；
- 为了“高端”强行使用古典 Serif。

---

## 06 — `huobao-character`

**火宝角色活动**

```text
blue campaign field
+ left text-safe zone
+ Huobao as narrative carrier
+ reward yellow only where meaningful
```

火宝不是通用装饰 Mascot，而是一套独立的角色视觉系统。

适合：

- Consumer Campaign；
- Referral；
- Reward Activity；
- Social Campaign；
- 需要角色动作 / 道具承担叙事的活动。

核心奖励数字可使用：

```text
#FFC800
```

但黄色应集中在金额、百分比、货币符号或紧邻单位上，而不是扩散成第二套品牌主色。

不要在机构资料、规则长图或高密度信息页里无意义加入火宝。

---

# Brand Tokens

## Brand Blue

```text
#0066FF
```

Primary blue gradient：

```text
#0066FF
↓
#2692FF
```

默认方向：top → bottom。

## VIP Gold

Core：

```text
#C9A84C
```

Gradient：

```text
#DEC48A
↓
#F5ECD7
```

## Huobao Reward Yellow

```text
#FFC800
```

只用于真正需要强化的 Reward Number / Percentage / Currency / Attached Unit。

## Neutral

```text
Text Black     #000000
White          #FFFFFF
Divider        #E8E8E8
VIP Divider    #E0D5C0
```

---

# Typography

Source Skills 指定的字体意图：

```text
Latin / Numbers: Urbanist
Chinese: HarmonyOS Sans SC
```

Weight system：

```text
Regular   400
Medium    500
Bold      700
```

### Hard rule

```text
Do not use 800 / 900 / Black.
Do not use italic as a default brand treatment.
```

层级应该优先通过：

```text
size
+ spacing
+ position
+ contrast
```

建立，而不是不断增加字重。

> Font binaries are intentionally not redistributed in this repository. Use licensed/local font copies in production.

---

# Logo Discipline

Source poster rule at `1080 × 1080`：

```text
Logo size: 100 × 100
Top: 60 px
Right: 60 px
```

其他尺寸应按比例继承 Safe Area，而不是机械复制绝对像素。

Logo 应：

- 使用提供的 SVG / Approved Asset；
- 不重绘；
- 不拉伸；
- 不滤镜；
- 不自行改色；
- 不与其他主视觉抢占同一区域。

---

# Supported Mediums

## Source-grounded

```text
poster-social
longform-operation
huobao-fast
review-only
```

这些媒介直接来自三套源 Skill 的生产逻辑。

## Derived Adapters

```text
web-ui
ppt-pdf
infographic
```

这些是根据现有品牌规则推导出的适配器，**不是声称来自官方 HTX Web / PPT Brand Manual**。

### `web-ui`

推荐：

- Hero → `brand-blue-field`
- Service / Information → `blue-white-hero`
- Premium / Institutional → `vip-gold`
- Friendly onboarding → `soft-blue-information`

Web UI 必须优先保证真实产品可用性，不要把 Poster 的超大标题机械复制到界面中。

### `ppt-pdf`

推荐节奏：

```text
Title / Section
→ Brand Blue or VIP Gold

Content / Evidence
→ White field + black copy + blue accent

Multi-module
→ Blue-white hero logic
```

### `infographic`

优先：

- 白 / 浅色场；
- 黑色正文；
- HTX Blue 作为结构强调；
- 语义图表优先于装饰 Icon；
- 不使用无意义阴影和 Crypto 光效。

---

# Installation

## Codex / Compatible Agent Skills

```bash
git clone https://github.com/78tyih/htx-design-refer.git \
  ~/.codex/skills/htx-design-refer
```

如果 Skill 没有立即出现，重启 Agent 环境。

对于 Cursor、Trae、OpenHands 等环境，也可以把仓库放进其 Skill / Rules / Instructions 可读取目录，并让 Agent 加载 `SKILL.md`。

---

# Basic Usage

## 让 Agent 自动选择 Family

```text
Use $htx-design-refer.

Medium: poster-social
Family: auto

Read the supplied copy and assets.
Choose the most appropriate HTX visual family.
Preserve the copy exactly unless rewriting is explicitly requested.
Explain the family choice, then create the design.
```

## Reward Campaign

```text
Use $htx-design-refer.

Medium: poster-social
Family: blue-grid-reward

Create an HTX reward campaign poster.
Make the reward value the primary visual hero.
Preserve the supplied blue-grid background geometry.
Keep long copy away from the right-side visual structure.
```

## Institutional / OTC

```text
Use $htx-design-refer.

Medium: ppt-pdf
Family: vip-gold

Create an institutional OTC / VIP partnership deck.
Keep the tone professional, restrained and premium.
Do not turn it into a black-gold luxury presentation.
```

## Long-form Rules

```text
Use $htx-design-refer.

Medium: longform-operation
Family: blue-white-hero

Create a long-form campaign explainer.
Use a blue Hero followed by one continuous white information field.
Prioritize copy readability and section hierarchy.
```

## Huobao Campaign

```text
Use $htx-design-refer.

Medium: huobao-fast
Family: huobao-character

Create a Huobao-led consumer campaign poster.
Keep the left side text-safe.
Place Huobao in the middle-right or lower-right visual region.
Reserve #FFC800 for the core reward expression only.
```

## Review Existing Design

```text
Use $htx-design-refer.

Medium: review-only

Review this design for:
- family fidelity;
- HTX blue discipline;
- copy fidelity;
- logo placement;
- typography hierarchy;
- asset distortion;
- generic crypto / neon drift.

Return the top 3 highest-impact repairs.
```

---

# Quality Gate

一个强的 HTX Design Refer 输出应通过：

1. Brand-token fidelity；
2. Semantic hierarchy；
3. Copy fidelity；
4. Readable typography；
5. Logo / safe-area discipline；
6. Correct family selection；
7. Correct background treatment；
8. No unsupported decoration；
9. Correct asset geometry / crop；
10. No generic Crypto / Neon drift。

### Fast rejection conditions

出现以下问题应优先返工：

- 把 HTX Blue 变成常见蓝紫 SaaS Gradient；
- 无理由使用深黑赛博背景；
- Logo 被重绘、变形、滤镜或任意改色；
- 原始 Copy 被模型自行改写；
- 使用 800 / 900 Black 字重；
- 空白区域因为“怕空”而被随意塞满；
- Huobao 身份、服装或角色特征被无依据修改；
- 机构材料被做成夸张促销海报。

---

# Anti-Identity

HTX Design Refer 刻意避免：

```text
generic blue-purple SaaS
neon crypto
cyberpunk
heavy shadow
random glowing lines
glassmorphism
invented marketing badges
arbitrary 3D coins
visual noise added only to fill space
```

原则是：

> **HTX blue should behave like brand architecture, not atmosphere.**

---

# Project Structure

```text
htx-design-refer/
├── SKILL.md
├── README.md
├── SOURCE_NOTICES.md
│
├── agents/
│   └── openai.yaml
│
├── references/
│   ├── brand-dna.md
│   ├── visual-families.md
│   ├── medium-router.md
│   ├── huobao-character.md
│   ├── quality-gate.md
│   └── source-notes.md
│
├── tokens/
│   └── htx.tokens.json
│
├── examples/
│   └── prompts.md
│
└── assets/
    ├── brand/
    ├── backgrounds/
    └── huobao/
```

---

# Source & Rights Boundary

v0.1.0 只基于本项目创建时用户提供的三套 HTX Skill：

```text
htx-brand.skill
htx-social-poster.skill
htx-huobao-fast.skill
```

它们被重新抽象为一个可复用 Design Reference，而不是原文件的简单拼接。

当前 6 个 Visual Families 属于对源规则的系统化整理；`web-ui`、`ppt-pdf`、`infographic` 属于 Derived Adapters。

这个仓库**不应被描述为 HTX 官方公开 Brand Manual**，除非资产权利人与项目所有者另行确认这一身份。

Brand / mascot / logo / background assets retain their original ownership and usage constraints. Do not assume that their presence in this repository grants unrestricted redistribution rights.

详见：[`SOURCE_NOTICES.md`](./SOURCE_NOTICES.md)

---

# Design Rules Router

`htx-design-refer` 可以作为更上层 Design Router 的一个注册系统。

当你已经知道需要 HTX 风格时：

```text
Use $htx-design-refer.
```

当你希望 Agent 在多个审美系统之间自动选择时：

```text
Use $design-rules-router.

Preferred system: auto
```

Router 可以根据任务内容在 Kimi / HTX / 后续新增 Design Refer 之间选择最合适的 Primary System。

---

# Roadmap

下一步建议完成：

- [ ] 6-Family HTX Benchmark Set
- [ ] Visual Benchmark Grid
- [ ] README Family Gallery
- [ ] PPT / PDF benchmark
- [ ] Web UI benchmark
- [ ] Institutional OTC benchmark
- [ ] Huobao campaign benchmark
- [ ] Register as `benchmark-backed` in Design Rules Router
