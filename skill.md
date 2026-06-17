# Driver Benefit Icon Skill

## 1. Skill Name

**Driver Benefit Icon Skill**  
司机端利益牵引图标绘制 Skill

---

## 2. Purpose

This skill is used to generate consistent icon assets for driver-side benefit, incentive, guidance, reward, business-promotion, basic-function, and emotional-care touchpoints.

适用于司机端上的利益点感知、奖励营销、基础功能、情感化关怀、服务宣导、订单标签、状态提示等小尺寸图标绘制。

The goal is to keep icons visually consistent, semantically clear, readable at small size, easy to iterate, and suitable for driver app benefit-oriented scenarios.

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
DBI-00-MAT-001_v1_bright-jelly-material-reference.png
DBI-01-REF-001_v1_benefit-cue-style-reference.png
DBI-01-APP-001_v1_ice-fresh-delivery-approved.png
DBI-02-APP-001_v1_newcomer-reward-approved.png
```

---

## 4. When to Use

Use this skill when creating or iterating icons for:

- 司机端利益点感知
- 新人奖励 / 留存奖励 / 听单奖励
- 任务奖励 / 任务牵引
- 加价 / 补贴 / 激励
- 会员 / 权益 / 福利
- 基础功能 / 工具入口 / 操作说明
- 情感化关怀 / 鼓励 / 安全提醒
- 业务宣导 / 服务说明
- 订单标签 / 服务状态提示
- 活动卡片 / banner / 弹层右侧图标

Do not use this skill for large complex illustrations, realistic product photography, full UI page generation, brand logos, detailed marketing posters, or icons that need to be flat-line style instead of bright jelly 3D style.

---

## 5. Shared Parent Style / 统一母风格

All routes must inherit the shared parent style:

**Bright Jelly 3D UI Icon Style**  
**轻透糖胶感 3D 图标风格**

This style is not realistic product rendering and not flat vector illustration. It should feel like a clean, bright, soft, rounded 3D UI component.

Core keywords:

- clean 3D icon
- bright jelly 3D UI icon
- glossy soft 3D illustration
- soft plastic finish
- jelly-like material
- slightly translucent feel
- rounded geometry
- smooth gradients
- soft highlights
- subtle bloom
- compact silhouette
- premium but simple
- driver app benefit icon family
- readable at small size
- no text
- no logo
- transparent PNG-style background

中文原则：

- 明亮干净
- 圆润轻盈
- 浅阴影
- 软高光
- 轻透糖胶感
- 软塑料感
- 不写实
- 不扁平
- 小尺寸清晰
- 主元素约 70%，辅助元素约 30%

---

## 6. Icon Routes / 图标路线

### DBI-01: Benefit Cue / 利益点感知型

**Status:** current mature baseline route.  
当前已沉淀并确认的参考图，主要用于定义此路线。

Used for order benefit perception, service labels, category benefits, special order cues, and lightweight business prompts.

适用于：订单利益点、品类标签、服务标签、专送提示、保障提示、优先派单、高价订单、冰鲜专送、轻提示类业务图标。

Visual direction:

- semantic clarity first
- compact silhouette
- restrained decoration
- clean and readable
- low promotional intensity
- business-meaning-driven color

Ratio:

- main object: about 70%–75%
- supporting elements: about 25%–30%

Prompt add-on:

```text
Route: DBI-01 / Benefit Cue / 利益点感知型

Use the current approved Benefit Cue visual reference as the primary style baseline. Prioritize semantic clarity, compact silhouette, and small-size readability. Keep the design restrained, clean, and not overly promotional. Supporting elements should only reinforce the business meaning and must not compete with the main object.
```

---

### DBI-02: Reward Promo / 奖励营销型

Expansion route based on the shared parent style.

Used for reward, subsidy, bonus, membership benefit, promotion, and conversion-oriented scenarios.

适用于：新人奖励、现金奖励、听单奖励、加价、补贴、任务奖励、抽成卡、会员权益、活动入口。

Visual direction:

- stronger benefit feeling
- warmer and brighter
- more click-attractive
- can use restrained sparkles, coins, red envelopes, gift boxes
- must not become cluttered or realistic

Ratio:

- main object: about 70%
- supporting elements: about 30%

Prompt add-on:

```text
Route: DBI-02 / Reward Promo / 奖励营销型

Inherit the shared Bright Jelly 3D UI Icon Style, but make the icon warmer, brighter, and more benefit-driven. Emphasize reward feeling, instant gain, and positive incentive. Use red, orange, gold, and yellow tones. Keep the main object dominant and use only a small number of supporting elements such as coins or sparkles.
```

---

### DBI-03: Basic Function / 基础功能型

Expansion route based on the shared parent style.

Used for basic driver-side functions, tools, operations, settings, and service capabilities.

适用于：听单设置、拍照上传、路线导航、订单详情、联系客服、异常上报、实名认证、保险说明、装备购买、运力工具。

Visual direction:

- clear and stable
- functional and reliable
- lower marketing feeling
- clean color palette
- clear operation cue
- minimal decoration

Ratio:

- main object: about 70%
- supporting elements: about 30%

Prompt add-on:

```text
Route: DBI-03 / Basic Function / 基础功能型

Inherit the shared Bright Jelly 3D UI Icon Style, but make the icon more functional, clear, stable, and less promotional. Use clean blue, orange, white, or light color palettes. The icon should explain a basic driver-side capability or tool with simple, readable objects and minimal decoration.
```

---

### DBI-04: Emotional Care / 情感化关怀型

Expansion route based on the shared parent style.

Used for driver care, encouragement, weather reminders, safety reminders, milestone recognition, and emotional service moments.

适用于：高温关怀、雨天提醒、夜间安全、节日祝福、休息提醒、健康提示、新手鼓励、完单鼓励、服务认可、里程碑成就。

Visual direction:

- warm
- soft
- friendly
- encouraging
- low-pressure
- caring and supportive
- not too promotional
- not childish

Ratio:

- main object: about 65%–70%
- supporting elements: about 30%–35%

Prompt add-on:

```text
Route: DBI-04 / Emotional Care / 情感化关怀型

Inherit the shared Bright Jelly 3D UI Icon Style, but make the icon warmer, softer, and more emotionally supportive. Emphasize care, encouragement, companionship, and low-pressure communication. Use warm orange, pale yellow, soft blue, light green, cream white, or soft coral tones. Keep the icon friendly but not childish.
```

---

## 7. Reference Scope / 参考图归属说明

The currently approved visual references belong primarily to the **DBI-01 / Benefit Cue / 利益点感知型** route.

这些参考图可作为利益点感知型的直接视觉依据。  
其他路线在扩展时，应继承统一母风格，但不应机械复用利益点感知型的具体语义表现方式。

Reference placement rule:

- If an image defines the shared material or overall family feel, place it under `DBI-00-shared/`.
- If an image defines a route-specific style, place it under the route folder.
- If an image is an approved final icon, use `APP`.
- If an image is an anti-pattern, use `NEG`.
- Do not mix draft images, failed attempts, and approved references in the same folder.

---

## 8. Composition Rules

The icon must be easy to understand when displayed at **40px–120px**.

Rules:

1. Center the main object.
2. Use front-facing or slight top-down perspective.
3. Keep the silhouette strong and readable.
4. Keep the object count low.
5. Use transparent or very clean plain background.
6. Avoid real environment backgrounds.
7. Avoid excessive texture.
8. Avoid tiny decorative details.
9. Avoid text, watermark, and brand logos.
10. Keep the composition vertically compact when used in a small top-right decoration area.

Recommended element structure:

- 1 main object
- 1 core supporting object
- 0–1 semantic cue object

---

## 9. Main vs Supporting Object Ratio

Use a clear visual hierarchy.

Rules:

- Main object: about **70%** of the visual weight
- Supporting object(s): about **30%** of the visual weight
- The main object must be the first recognizable shape
- Supporting objects should reinforce meaning but not compete with the main object
- In small-size use cases, always enlarge the main object before adding more secondary elements
- Auxiliary elements should be placed around the main object, not cover the main object
- Do not use supporting elements to create visual clutter

---

## 10. Material & Finish Style

The icon material should feel bright, clean, lightweight, and premium.

Target finish:

- glossy soft 3D
- jelly-like material
- soft plastic texture
- slightly translucent feel
- rounded volumes
- subtle bloom
- gentle edge highlights
- minimal shadow
- clean and bright appearance
- airy and polished UI component feeling

Avoid:

- heavy realistic texture
- strong metallic reflection
- dark shadows
- dirty gray tones
- hard-edged rendering
- flat vector look
- overly realistic object rendering
- thick and heavy contact shadows
- complex surface patterns

---

## 11. Lighting & Shadow Rules

- Use bright overall lighting
- Keep shadows light, soft, and minimal
- Avoid strong contact shadows
- Avoid heavy internal dark shading
- Highlights should be broad and soft
- Use gentle edge highlights to make shapes clean and separated
- The icon should remain visually clean when placed on colored UI backgrounds
- Avoid black, dark gray, or muddy shadow tones

---

## 12. Semantic Input Fields

Before generating an icon, clarify:

```text
风格路线：
业务场景：
业务语义：
主物件：
辅助物件：
语义强化物件：
主色方向：
使用位置：
输出要求：
参考资源编号：
必须保留：
必须避免：
```

---

## 13. Standard Generation Prompt Template

```text
调用 Driver Benefit Icon Skill

风格路线：{DBI route ID / route name}
参考资源编号：{DBI reference IDs if available}

业务场景：
{business scenario}

业务语义：
{business meaning}

主物件：
{main object}

辅助物件：
{supporting object}

语义强化物件：
{semantic cue}

主色方向：
{primary color direction}

使用位置：
{usage position}

输出要求：
{output requirement}

构图要求：
主体集中，主元素约 70%，辅助元素约 30%，适合小尺寸展示。

风格要求：
遵循 Bright Jelly 3D UI Icon Style / 轻透糖胶感 3D 图标风格。明亮、干净、轻盈、圆润、软高光、浅阴影、透明背景 PNG。不写实、不扁平。

必须保留：
{must keep}

必须避免：
{must avoid}
```

---

## 14. Quality Checklist

Before accepting an icon, check:

1. Does it remain readable at 48px?
2. Can the business meaning be understood within 1 second?
3. Is the route selected correctly?
4. Is the main object about 70% of visual weight?
5. Are supporting objects about 30% and not competing with the main object?
6. Is there only one main object plus one or two supporting objects?
7. Is the icon free of text, logo, watermark, and brand labels?
8. Does it match the bright jelly 3D driver-side icon family?
9. Is the silhouette clear and compact?
10. Is it bright, clean, lightweight, and not too realistic?
11. Are shadows light and soft?
12. Are reference IDs and asset files recorded in `references/index.md` when approved?

If the answer is no, simplify first. Do not add more elements.
