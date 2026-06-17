# Driver Benefit Icon Skill

**Driver Benefit Icon Skill** 是一套用于司机端利益点、奖励营销、基础功能、情感化关怀等场景图标绘制的本地 Skill。

它的目标不是单次生成一张图，而是帮助团队长期保持图标风格统一、语义明确、小尺寸可读。

---

## 1. 核心风格

统一使用：

**Bright Jelly 3D UI Icon Style**  
**轻透糖胶感 3D 图标风格**

关键词：

```text
bright jelly 3D UI icon
glossy soft 3D illustration
soft plastic finish
slightly translucent feel
rounded geometry
smooth gradients
subtle bloom
gentle edge highlights
minimal soft shadow
clean and bright appearance
```

中文理解：

```text
明亮 / 干净 / 轻盈 / 圆润 / 软高光 / 浅阴影 / 果冻感 / 糖胶感 / 轻微半透明 / 不写实 / 不扁平 / 小尺寸清晰
```

---

## 2. 路线编号

```text
DBI-00 = Shared / 统一母风格
DBI-01 = Benefit Cue / 利益点感知型
DBI-02 = Reward Promo / 奖励营销型
DBI-03 = Basic Function / 基础功能型
DBI-04 = Emotional Care / 情感化关怀型
```

当前已训练和确认的参考图主要属于：

```text
DBI-01 = Benefit Cue / 利益点感知型
```

其他路线后续基于统一母风格继续拓展。

---

## 3. 资源类型编号

```text
REF = 风格参考 / style reference
MAT = 材质参考 / material reference
APP = 已确认图标 / approved icon
NEG = 反例 / anti-pattern
EXA = 示例 / example prompt
```

文件命名规则：

```text
DBI-{路线编号}-{资源类型}-{序号}_v{版本}_{英文说明}.{后缀}
```

示例：

```text
DBI-00-MAT-001_v1_bright-jelly-material-reference.png
DBI-01-REF-001_v1_benefit-cue-style-reference.png
DBI-01-APP-001_v1_ice-fresh-delivery-approved.png
DBI-02-APP-001_v1_newcomer-reward-approved.png
```

---

## 4. Reference 存放规则

```text
references/
├─ DBI-00-shared/
├─ DBI-01-benefit-cue/
├─ DBI-02-reward-promo/
├─ DBI-03-basic-function/
├─ DBI-04-emotional-care/
└─ index.md
```

放置原则：

- 如果图片定义整体材质或家族感，放 `DBI-00-shared/`
- 如果图片定义某一路线的专属风格，放对应路线文件夹
- 当前成熟的利益点感知型参考图，放 `DBI-01-benefit-cue/`
- 已确认最终图标用 `APP`
- 风格参考用 `REF`
- 材质参考用 `MAT`
- 反例用 `NEG`

---

## 5. 主辅比例

```text
主元素：约 70%
辅助元素：约 30%
```

原则：

- 主元素必须第一眼识别
- 辅助元素只做语义补充
- 小尺寸场景优先放大主元素，不要增加元素数量

---

## 6. 推荐调用格式

```text
调用 Driver Benefit Icon Skill

风格路线：
参考资源编号：
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

示例：

```text
调用 Driver Benefit Icon Skill

风格路线：DBI-01 / Benefit Cue / 利益点感知型
参考资源编号：DBI-00-MAT-001、DBI-01-REF-001、DBI-01-APP-001
业务场景：冰鲜专送
业务语义：冷链、保温、冰鲜商品、配送专业
主物件：打开的蓝色保温箱
辅助物件：龙虾
语义强化物件：冰块、1瓶无品牌啤酒
主色方向：蓝色为主，橙红点缀
使用位置：司机端订单标签、配送中提示、服务宣导卡片
输出要求：透明背景 PNG，1000×1000
必须保留：轻透糖胶感3D、圆润、软高光、小尺寸清晰
必须避免：文字、品牌 logo、真实背景、复杂纹理、过多元素
```

---

## 7. 质量检查

1. 缩小到 48px 是否还能看懂？
2. 是否 1 秒内能判断业务语义？
3. 路线是否选择正确？
4. 主元素是否约占 70% 视觉权重？
5. 辅助元素是否约占 30% 且不抢主元素？
6. 是否没有文字、logo、水印？
7. 是否和已有图标高光、圆角、体积感一致？
8. 是否明亮、干净、轻盈，而不是过度写实？
9. 是否适合当前 UI 承载区域？
10. 是否可以直接导出透明 PNG 使用？
