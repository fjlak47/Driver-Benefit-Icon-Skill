# Driver Benefit Icon Skill

## 1. Skill Name

**Driver Benefit Icon Skill**  
司机端利益牵引图标绘制 Skill

---

## 2. Purpose

This skill is used to generate consistent icon assets for driver-side benefit, incentive, guidance, reward, business-promotion, basic-function, and emotional-care touchpoints.

适用于司机端上的利益点感知、奖励营销、基础功能、情感化关怀、服务宣导、订单标签、状态提示等小尺寸图标绘制。

---

## 3. Core Route ID System

Use a unified ID system for route calling, reference storage, and asset management.

```text
DBI-00 = Shared / 统一母风格
DBI-01 = Benefit Cue / 利益点感知型
DBI-02 = Reward Promo / 奖励营销型
DBI-03 = Basic Function / 基础功能型
DBI-04 = Emotional Care / 情感化关怀型
```

Resource type codes:

```text
REF = style reference / 风格参考
MAT = material reference / 材质参考
APP = approved icon / 已确认图标
NEG = anti-pattern / 反例
EXA = example prompt / 示例
```

Naming rule:

```text
DBI-{route-number}-{resource-type}-{serial}_v{version}_{english-description}.{file-extension}
```

Examples:

```text
DBI-00-MAT-001_v1_bright-clean-3d-material-reference.png
DBI-00-MAT-002_v1_high-purity-bright-clean-color-reference.png
DBI-01-REF-001_v1_benefit-cue-style-reference.png
DBI-01-APP-001_v1_ice-fresh-delivery-approved.png
DBI-02-APP-001_v1_newcomer-reward-approved.png
```

---

## 4. Shared Parent Style / 统一母风格

All routes must inherit the shared parent style:

## **Bright Clean 3D UI Icon Style / 明亮清爽 3D UI 图标风格**

This style replaces the previous “jelly / gummy / semi-transparent soft” direction.

Do **not** use:

- jelly-like material
- gummy / candy-gel material
- strong translucent feeling
- overly soft, sticky, or melted surfaces
- heavy bloom
- dirty gray shadows
- overly complex layered structure

Use:

- bright and clean 3D UI icon finish
- solid but rounded volumes
- crisp and readable silhouette
- clear structural edges
- smooth but controlled highlights
- light soft shadows
- clean surface transitions
- high-purity colors
- high-lightness warm palette
- clear readability at both large and small sizes

中文风格定义：

- 明亮
- 清爽
- 高纯度
- 高明度
- 结构清楚
- 边界清晰
- 体块 solid
- 圆润但不软塌
- 高光干净
- 阴影轻
- 不果冻
- 不糖胶
- 不半透明软糯
- 放大精致，缩小清晰

---

## 5. Color & Brightness Rules / 色彩与明度规则

The current color and material baseline is defined by:

```text
DBI-00-MAT-002_v1_high-purity-bright-clean-color-reference.png
```

Use this as the preferred color reference for warm reward-related icons.

### Color Direction

Use cleaner, purer, brighter warm colors:

- high-purity red-orange
- pure orange
- bright warm yellow
- clean honey yellow
- creamy white / warm white highlights
- shallow warm shadows only

Avoid:

- grayish orange
- muddy red
- brownish orange
- dirty yellow
- dark gold
- pinkish flesh tones
- heavy gray shadows
- complex muddy gradients
- low-brightness dull color blocks

### Brightness Direction

- Increase overall lightness.
- Keep dark areas shallow and controlled.
- Use larger clean bright surfaces.
- Use simple, readable gradients.
- Reduce heavy shading and excessive contrast.
- Keep the icon bright enough for orange/red UI backgrounds.

### Reward / Warm Palette Guide

For Reward Promo and warm Benefit Cue icons:

```text
Main red-orange: pure, vivid, high-lightness red-orange
Orange: clean, high-brightness orange
Yellow: bright honey yellow / creamy yellow
White: warm creamy white, not gray white
Shadow: very light warm shadow, low opacity
Highlight: clean cream-white highlight, not sticky jelly shine
```

---

## 6. Icon Routes / 图标路线

### DBI-01: Benefit Cue / 利益点感知型

**Status:** current mature baseline route.  
当前已沉淀并确认的参考图，主要用于定义此路线。

Used for order benefit perception, service labels, category benefits, special order cues, and lightweight business prompts.

Visual direction:

- semantic clarity first
- compact silhouette
- restrained decoration
- clean and readable
- low promotional intensity
- business-meaning-driven color

Ratio:

- main object: about 70%–75%
- supporting elements: about 20%–30%
- accent elements: 0%–5%

Prompt add-on:

```text
Route: DBI-01 / Benefit Cue / 利益点感知型

Use the current approved Benefit Cue visual reference as the primary route baseline. Prioritize semantic clarity, compact silhouette, and small-size readability. Keep the design restrained, clean, and not overly promotional. Supporting elements should only reinforce the business meaning and must not compete with the main object. Use the Bright Clean 3D UI Icon Style with high-purity colors, high lightness, clean highlights, and light shadows.
```

---

### DBI-02: Reward Promo / 奖励营销型

Used for reward, subsidy, bonus, membership benefit, promotion, and conversion-oriented scenarios.

Visual direction:

- stronger benefit feeling
- warmer and brighter
- more click-attractive
- can use restrained sparkles, coins, red envelopes, gift packs
- must not become cluttered or realistic

Ratio:

- main object: about 65%–70%
- supporting elements: about 25%–30%
- accent elements: about 5%

Prompt add-on:

```text
Route: DBI-02 / Reward Promo / 奖励营销型

Inherit the Bright Clean 3D UI Icon Style. Make the icon warmer, brighter, and more benefit-driven. Emphasize reward feeling, instant gain, and positive incentive. Use high-purity red-orange, pure orange, bright honey yellow, and creamy white highlights. Avoid muddy reds, brownish orange, dirty gold, jelly-like material, and heavy shadows. Keep the main object dominant and use only a small number of supporting elements.
```

---

### DBI-03: Basic Function / 基础功能型

Used for basic driver-side functions, tools, operations, settings, and service capabilities.

Visual direction:

- clear and stable
- functional and reliable
- lower marketing feeling
- clean color palette
- clear operation cue
- minimal decoration

Prompt add-on:

```text
Route: DBI-03 / Basic Function / 基础功能型

Inherit the Bright Clean 3D UI Icon Style, but make the icon more functional, clear, stable, and less promotional. Use clean blue, orange, white, or light color palettes. The icon should explain a basic driver-side capability or tool with simple, readable objects and minimal decoration.
```

---

### DBI-04: Emotional Care / 情感化关怀型

Used for driver care, encouragement, weather reminders, safety reminders, milestone recognition, and emotional service moments.

Visual direction:

- warm
- soft but not gummy
- friendly
- encouraging
- low-pressure
- caring and supportive
- not too promotional
- not childish

Prompt add-on:

```text
Route: DBI-04 / Emotional Care / 情感化关怀型

Inherit the Bright Clean 3D UI Icon Style, but make the icon warmer, softer, and emotionally supportive. Use high-lightness warm orange, pale yellow, soft blue, light green, cream white, or soft coral tones. Keep the icon friendly but not childish, bright but not sticky, and simple enough for small-size readability.
```

---

## 7. Element Hierarchy Control / 元素层级控制

Every icon must define a clear hierarchy of elements.

### Main Object / 主元素

The main object is the first thing users should recognize.

Rules:

- Use only **1 main object**
- Visual weight: about **65%–75%**
- Must be the largest and clearest shape
- Must occupy the visual center
- Must not be blocked by supporting objects
- Must remain readable at 48px

### Supporting Object / 辅助元素

The supporting object reinforces the main meaning.

Rules:

- Use **1 supporting object** by default
- Use **2 supporting objects only when necessary**
- Visual weight: about **20%–30%**
- Must be smaller than the main object
- Must not create a second visual center

### Accent Object / 点缀元素

Accent objects only create atmosphere or polish.

Rules:

- Use **0–1 accent object** by default
- Use **2 accent objects maximum**
- Visual weight: about **0%–10%**
- Must be small and simple
- Must not introduce a new meaning
- If the icon already feels clear, remove accents first

---

## 8. Complexity Limit / 复杂度限制

This is a strict rule.

```text
Main object: 1
Supporting object: 1 by default, 2 maximum
Accent object: 0–1 by default, 2 maximum
Total semantic objects: no more than 3
Structural layers: no more than 3
```

Avoid:

- too many cards
- too many coins
- multiple gifts
- helmet + box + coin + gift + sparkle together
- excessive ribbons, badges, inserts, panels
- deep nested layers
- complicated small details
- unclear main subject

If the icon feels crowded, simplify in this order:

```text
1. Remove accent objects
2. Reduce supporting objects
3. Enlarge the main object
4. Simplify internal structure
5. Strengthen the silhouette
```

Purpose:

- The icon must work when enlarged.
- The icon must work when reduced.
- The icon must be visually clear in UI preview and production export.
- Do not optimize only for large-size render preview.

---

## 9. Standard Input Fields / 标准输入字段

```text
风格路线：
参考资源编号：
业务场景：
业务语义：
主元素：
主元素占比：
辅助元素：
辅助元素占比：
点缀元素：
点缀元素占比：
主色方向：
使用位置：
输出要求：
复杂度限制：
必须保留：
必须避免：
```

---

## 10. Standard Generation Prompt Template

```text
调用 Driver Benefit Icon Skill

风格路线：{DBI route ID / route name}
参考资源编号：{DBI reference IDs}

业务场景：
{business scenario}

业务语义：
{business meaning}

主元素：
{main object}
主元素占比：
{65%–75%}

辅助元素：
{supporting object}
辅助元素占比：
{20%–30%}

点缀元素：
{accent object}
点缀元素占比：
{0%–10%}

主色方向：
{primary color direction}

使用位置：
{usage position}

输出要求：
{output requirement}

复杂度限制：
总语义元素不超过3个，结构层级不超过3层。切忌元素和分层结构过多过复杂。

风格要求：
使用 Bright Clean 3D UI Icon Style / 明亮清爽 3D UI 图标风格。
材质要明亮、清爽、solid、结构清楚、边界清晰、轻阴影、干净高光。
去掉果冻感、糖胶感、半透明软糯感。
图标必须兼顾放大和缩小两类场景。

颜色要求：
使用高纯度、高明度的干净色彩。红橘更纯，黄色更亮，奶白高光更干净。
减少灰感、脏感、褐橙、脏黄、暗金和浑浊渐变。
阴影更轻，暗部更浅，整体更亮更清爽。

必须保留：
{must keep}

必须避免：
{must avoid}
```

---

## 11. Iteration Prompt Template / 迭代提示词模板

```text
基于上一版继续调整。

仅调整：
{specific adjustment}

保持不变：
元素组合、前后关系、构图结构、主辅比例、业务语义。

质感要求：
统一为 Bright Clean 3D UI Icon Style / 明亮清爽 3D UI 图标风格。
去掉果冻感、糖胶感、半透明软糯感。
让体块更 solid，结构更清楚，边界更清晰，高光更干净，阴影更轻。

颜色要求：
提升色彩纯度与整体明度。
主色使用更纯净的红、橘、黄关系，减少灰感、脏感和浑浊渐变。
橘红更鲜明，黄色更明亮，奶白高光更干净。
不要偏灰、不要发脏、不要发闷。

复杂度要求：
不新增物件，不增加结构层级。
总语义元素不超过3个，结构层级不超过3层。
如果画面拥挤，优先删除点缀元素。
```

---

## 12. Quality Checklist

Before accepting an icon, check:

1. Does it remain readable at 48px?
2. Does it still look refined when enlarged?
3. Can the business meaning be understood within 1 second?
4. Is the route selected correctly?
5. Is the main object about 65%–75% of visual weight?
6. Are supporting objects about 20%–30% and not competing with the main object?
7. Is there only one main object?
8. Are total semantic objects no more than 3?
9. Are structural layers no more than 3?
10. Is the icon free of text, logo, watermark, and brand labels?
11. Is the style bright, clean, solid, and clear?
12. Is there no jelly / gummy / over-translucent material?
13. Are colors pure, bright, and clean?
14. Are shadows light and not muddy?
15. Does it work on orange/red promotional UI backgrounds?

If the answer is no, simplify first.
