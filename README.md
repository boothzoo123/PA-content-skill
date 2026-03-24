# Amazon PA+ Content Planner

> A table-first skill for planning Amazon PA+ / Premium A+ content with an advanced operator mindset.

## Overview

**Amazon PA+ Content Planner** is a prompt/skill framework designed for Amazon operators, designers, and content teams who need to plan **PA+ / Premium A+** pages in a more structured and execution-friendly way.

Instead of generating long, vague proposals, this skill focuses on:

- **page strategy**
- **asset planning**
- **scene-driven storytelling**
- **buyer psychology**
- **table-based outputs for execution**

It is especially useful for teams who want to turn product information into a **12–16 asset PA+ plan** that can be reviewed, edited, and handed off quickly.

---

## What this skill solves

Many PA+ prompts fail because they:

- repeat the listing instead of extending it
- produce generic “lifestyle” suggestions
- lack a clear page rhythm
- do not map each asset to a conversion goal
- are hard to move into Excel / Sheets / Notion workflows

This skill is built to solve that.

It helps you turn a product into a PA+ plan that answers:

- What should appear first on the page?
- Which assets should be video, hero image, carousel, hotspot, comparison, or closing image?
- What is the buyer thinking at each stage?
- Which scene should be shown, and why does that scene increase conversion?
- Where are the repetition and weak-conversion risks?

---

## Core features

### 1. Table-first output
The skill is designed to output content plans in structured tables rather than long paragraphs.

### 2. Advanced operator logic
It behaves like a senior Amazon operator, not just a copywriter.

### 3. Asset-based planning
It plans around **content assets**, not rigid template blocks.

### 4. Scene-driven briefs
Lifestyle and scene images are written with:
- user identity
- usage moment
- real motivation
- environment
- action
- composition
- emotional tone
- conversion value

### 5. Execution-ready structure
The output is meant to be directly usable by:
- operations teams
- designers
- photographers
- video editors
- content reviewers

---

## Recommended output structure

The skill is designed to return results in the following order:

1. **Page Strategy Table**
2. **Page Structure Table**
3. **Asset Master Table**
4. **Scene Detail Table**
5. **Top 3 Conversion Risk Table**
6. **Compliance Reminder Table**

---

## Best for

This skill works especially well for:

- Amazon operators
- premium A+ planners
- design handoff workflows
- content review teams
- agencies managing multiple product listings
- sellers who want more structured PA+ planning
- teams using Excel / Google Sheets / Notion for production

---

## Supported asset types

The skill is optimized around these asset types:

- Video
- Hero Image
- Full Banner
- Carousel Slide
- Hotspot Image
- Lifestyle Image
- Comparison Chart
- Brand Story Card
- Closing Image

---

## Default page planning logic

If the user does not specify a structure, the skill defaults to a practical 12-asset layout:

| Order | Asset Type |
|---|---|
| 1 | Video |
| 2 | Hero Image |
| 3 | Full Banner |
| 4 | Carousel Slide |
| 5 | Carousel Slide |
| 6 | Carousel Slide |
| 7 | Hotspot Image |
| 8 | Lifestyle Image |
| 9 | Lifestyle Image |
| 10 | Lifestyle Image |
| 11 | Comparison Chart |
| 12 | Closing Image |

This default structure can be expanded or adjusted based on product type, price band, or content goals.

---

## Input fields

For best results, provide as many of the following as possible:

| Field | Description |
|---|---|
| Product Name | Product name |
| Category | Product category |
| Marketplace | US / UK / DE / JP, etc. |
| Price Band | Price range |
| Target Audience | Who the product is for |
| Core Selling Points | 3–5 key benefits |
| Buyer Concerns | 3–5 main objections |
| Usage Scenarios | 3–5 real-life situations |
| Existing Assets | Images / videos / certifications / structure diagrams |
| SKU Info | Whether multiple variants exist |
| Page Goal | Conversion / premium feel / differentiation / objection handling / brand value |

If some data is missing, the skill should continue and clearly mark assumptions as **[Inferred]**.

---

## Why table-based planning matters

A table-based system makes PA+ work easier to manage because it is:

- easier to review internally
- easier to move into production spreadsheets
- easier to assign to designers
- easier to spot repeated content
- easier to compare multiple products
- easier to standardize across teams

---

## Example output tables

### Page Strategy Table

| Dimension | Content |
|---|---|
| Page Goal | Conversion-first |
| Decision Type | Functional + risk-sensitive |
| Core Narrative | A faster, easier way to solve the daily problem |
| Content Focus | Video first / hero first / scene first |
| Page Rhythm | Function → trust → scenarios → comparison → close |

### Asset Master Table

| Asset ID | Asset Type | Main Task | Buyer Thought | Headline | One-Line Selling Point | Visual Focus | Tone | Suggested Material | Avoid | Operator Intent |
|---|---|---|---|---|---|---|---|---|---|---|

### Scene Detail Table

| Asset ID | Scene Name | Scene Goal | User Profile | Usage Moment | Real Motivation | Space | Lighting | Background Elements | Human Action | Product Visibility | Composition | Emotion Keywords | Title Suggestion | Subcopy Suggestion | Conversion Value |
|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|

---

## Key operating principles

### Do not repeat the listing
PA+ should extend the listing, not repeat it.

### One asset, one job
Each asset should carry one main job only:
- attention
- value explanation
- objection handling
- scene immersion
- detail proof
- comparison
- brand reinforcement
- closing conversion

### Scene images must be real
A good scene is not just “home scene” or “office scene”.
It should describe:
- who is using the product
- when they use it
- why they use it at that exact moment
- how the scene strengthens the buying reason

### Strategy comes before asset writing
Always decide page rhythm first, then assign content assets.

---

## Good use cases

- “Plan a 12-asset PA+ page for a portable garment steamer on Amazon US.”
- “Create a conversion-first Premium A+ structure for a pet grooming vacuum.”
- “Generate an Excel-field PA+ plan for a premium tumbler.”
- “Rewrite the scene assets to feel more realistic and less generic.”
- “Add more buyer psychology to each asset row.”

---

## Suggested follow-up commands

After initial output, users can continue with commands such as:

- `精简成12张`
- `扩展成16张`
- `视频优先版`
- `大图优先版`
- `轮播优先版`
- `高端感加强`
- `减少空泛场景`
- `场景写得更真实`
- `增加人群代入`
- `增加对比图`
- `去掉品牌故事`
- `只输出资产总表`
- `只输出场景细化表`
- `只输出Excel字段版`
- `改成更适合设计交付`
- `改成更适合运营评审`

---

## Excel-friendly mode

If the user asks for **Excel field format**, the skill should output fields in this order:

| 编号 | 中文标题 | 英文标题 | 资产类型 | 主任务 | 用户心理 | 一句话卖点 | 画面说明 | 建议素材 | 文案风格 | 不要这样做 | 运营意图 | 备注 |
|---|---|---|---|---|---|---|---|---|---|---|---|---|

This makes the output easier to paste into:

- Excel
- Google Sheets
- Feishu Sheets
- Airtable
- Notion databases

---

## Compliance reminder

All final PA+ plans should avoid:

- price / discount / promotion language
- contact details / external links / QR codes
- competitor brand names
- unsupported superlatives
- unsupported claims related to certification, performance, effects, or patents

Always verify final content against Amazon policy before publishing.

---

## Repository purpose

This repository is intended to help teams build a **repeatable PA+ content planning workflow**.

It is not only a writing prompt.  
It is a practical framework for turning product data into:

- content structure
- asset planning
- scene briefs
- design handoff tables
- conversion review checkpoints

---

## Recommended repository structure

```bash
.
├── README.md
├── SKILL.md
├── examples/
│   ├── portable-steamer-example.md
│   ├── tumbler-example.md
│   └── pet-grooming-tool-example.md
└── templates/
    ├── asset-master-table.md
    ├── scene-detail-table.md
    └── excel-field-template.md
```

---

## Notes

- This skill is best used with clear product input.
- It performs better when buyer concerns and real usage moments are provided.
- It is designed for **execution clarity**, not for decorative long-form writing.
- Final policy suitability should always be reviewed before publishing to Amazon.

---

## License

You may add your preferred open-source license here, such as MIT.
