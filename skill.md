# Driver Benefit Icon Skill

## 1. Skill Name

**Driver Benefit Icon Skill**  
司机端利益牵引图标绘制 Skill

---

## 2. Purpose

This skill is used to generate consistent icon assets for driver-side benefit, incentive, guidance, and business-promotion touchpoints.

适用于司机端上的利益点感知、任务牵引、权益入口、服务宣导、订单标签、状态提示等小尺寸图标绘制。

The goal is to keep icons:

- visually consistent
- semantically clear
- readable at small size
- easy to iterate
- suitable for driver app promotional and benefit-oriented scenarios

---

## 3. When to Use

Use this skill when the user needs to create or iterate icons for:

- 司机端利益点感知
- 任务奖励 / 任务牵引
- 加价 / 补贴 / 激励
- 会员 / 权益 / 福利
- 业务宣导 / 服务说明
- 订单标签 / 服务状态提示
- 活动卡片 / banner / 弹层右侧图标

Do not use this skill for:

- large complex illustrations
- realistic product photography
- full UI page generation
- brand logos
- detailed marketing posters
- icons that need to be flat-line style instead of light 3D style

---

## 4. Visual Language

The icon style should follow a **light 3D promotional app icon style**.

Core style keywords:

- clean 3D icon
- glossy soft 3D illustration
- rounded geometry
- smooth gradients
- soft highlights
- compact silhouette
- premium but simple
- driver app visual style
- readable at small size
- no text
- no logo
- transparent PNG-style background

中文风格定义：

- 轻 3D
- 圆润体块
- 柔和高光
- 干净边缘
- 主体居中
- 元素克制
- 小尺寸清晰
- 适合司机端红橙渐变利益触点承载

---

## 5. Composition Rules

The icon must be easy to understand when displayed at **40px–120px**.

Composition rules:

1. Center the main object.
2. Use front-facing or slight top-down perspective.
3. Keep the silhouette strong and readable.
4. Keep the object count low.
5. Use transparent or very clean plain background.
6. Avoid real environment backgrounds.
7. Avoid excessive texture.
8. Avoid tiny decorative details.
9. Avoid text, watermark, and brand logos.

Recommended element structure:

- 1 main object
- 1 core supporting object
- 0–1 semantic cue object

Example for ice-fresh delivery:

- Main object: open blue insulated cooler
- Core supporting object: lobster
- Semantic cue object: ice cubes
- Optional weak accent: one unbranded beer bottle

---

## 6. Color Rules

The icons often appear on driver-side red/orange promotional cards, so the icon itself should have enough contrast.

Recommended color directions by scenario:

### Ice-fresh / cold chain

- main color: fresh blue
- highlights: light blue and white
- semantic accent: orange-red seafood
- optional accent: amber bottle

### Reward / subsidy / income

- main color: gold, orange, red
- highlights: warm yellow and white
- semantic accent: coin, envelope, badge, gift

### Membership / benefit / privilege

- main color: gold, orange, purple
- highlights: cream white
- semantic accent: crown, card, shield, badge

### Task / guidance / action

- main color: orange, blue, cyan
- highlights: white
- semantic accent: checklist, arrow, route, order card

---

## 7. Semantic Input Fields

Before generating an icon, clarify the following fields:

```text
Business scenario:
Business meaning:
Main object:
Supporting object:
Optional semantic cue:
Primary color:
Usage position:
Required output:
Must keep:
Must avoid:
```

中文填写模板：

```text
业务场景：
业务语义：
主物件：
辅助物件：
语义强化物件：
主色方向：
使用位置：
输出要求：
必须保留：
必须避免：
```

---

## 8. Standard Generation Prompt Template

Use this prompt structure for first-time generation:

```text
Create a single polished app icon asset for Didi KuaiSong driver app benefit and guidance touchpoints.

Style:
clean 3D icon, glossy soft 3D illustration, rounded geometry, smooth gradients, soft highlights, compact silhouette, premium but simple, suitable for small-size display, consistent with driver app promotional icon family.

Composition:
centered standalone icon, front-facing or slight top-down view, strong readable silhouette, minimal details, no environment background, transparent PNG-style background.

Business meaning:
{business meaning}

Subject:
{main object description}

Objects:
- Main object: {main object}
- Supporting object: {supporting object}
- Optional semantic cue: {semantic cue}

Color:
{primary color direction} with clean highlights and soft shadows.

Detail control:
Keep the icon simple and refined. Use only a few large readable shapes. Avoid tiny details that become unclear at small size. No text, no watermark, no brand logo, no realistic photo texture, no clutter.

Output:
a standalone PNG-style icon asset, transparent background, high resolution, centered with enough breathing room.
```

---

## 9. Iteration Prompt Template

Use this prompt structure when modifying an existing icon:

```text
Edit Image A.

Keep:
the same overall Driver Benefit Icon Skill style, light 3D app icon look, rounded geometry, soft gradients, glossy highlights, centered composition, transparent PNG-style background, and small-size readability.

Only change:
{specific change}

Preserve:
{elements that must stay unchanged}

Avoid:
changing the overall style, adding new objects, adding text, adding logos, making details too realistic, increasing visual clutter, or changing the icon family style.
```

---

## 10. Ice-fresh Delivery Example Prompt

```text
Create a single polished app icon asset for Didi KuaiSong driver app benefit and guidance touchpoints.

Style:
clean 3D icon, glossy soft 3D illustration, rounded geometry, smooth gradients, soft highlights, compact silhouette, premium but simple, suitable for small-size display, consistent with driver app promotional icon family.

Composition:
a centered standalone icon, front-facing open cooler box, slight top-down view, strong readable silhouette, minimal details, transparent PNG-style background.

Business meaning:
ice-fresh dedicated delivery, cold-chain freshness, insulated transport, professional delivery.

Subject:
an open blue insulated cooler box facing the viewer, with white trim and a simple cold-chain feeling.

Objects:
- Main object: open blue insulated cooler box
- Supporting object: bright orange-red lobster
- Optional semantic cue: a few large blue ice cubes and one simple amber beer bottle with a blank label

Color:
fresh blue cooler, white trim, light blue ice, orange-red lobster, small amber bottle accent.

Detail control:
Keep the element count low. Do not add extra bottles, extra seafood, complex background, text, logo, watermark, or tiny realistic texture. The lobster should have a clear segmented body and two similarly sized claws, occupying enough area to be readable, but not making the icon crowded.

Output:
standalone PNG-style icon asset, transparent background, high resolution, centered with enough breathing room.
```

---

## 11. Quality Checklist

Before accepting an icon, check:

1. Does it remain readable at 48px?
2. Can the business meaning be understood within 1 second?
3. Is there only one main object plus one or two supporting objects?
4. Is the icon free of text, logo, watermark, and brand labels?
5. Does it match the existing driver-side light 3D icon family?
6. Is the silhouette clear and compact?
7. Does it work on red/orange promotional cards?
8. Is it not too realistic, too flat, or too complex?
9. Are there no obvious AI distortions?
10. Can it be iterated locally without regenerating the whole style?

If the answer is no, simplify first. Do not add more elements.

---

## 12. Anti-patterns

Avoid:

- too many objects
- too many bottles or ice cubes
- overly realistic photo texture
- detailed real background
- text on objects
- brand logos
- thin lines that disappear at small size
- messy shadows
- inconsistent perspective
- overly flat line icon style
- overly cartoonish or childish rendering
- complicated seafood anatomy
- large decorative elements unrelated to the business meaning

---

## 13. Output Requirements

Preferred output:

- transparent PNG
- square canvas
- high resolution
- centered composition
- enough breathing room
- icon can be exported for 1x / 2x / 3x usage

Recommended production size:

- master generation: 1024px or above
- app usage: export according to product design requirement
- preview check: 48px and 80px
