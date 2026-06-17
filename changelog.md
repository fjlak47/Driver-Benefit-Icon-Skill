# Changelog

## 2026-06-16

### Initial version

- 确定 Skill 名称：Driver Benefit Icon Skill
- 明确适用场景：司机端利益点与牵引场景图标绘制
- 确定基础风格：轻 3D、圆润、软高光、小尺寸清晰
- 确定输出要求：透明背景 PNG、主体居中、元素克制
- 新增冰鲜专送示例

### Material & hierarchy update

- 新增风格定义：轻透糖胶感 3D 图标风格 / Bright Jelly 3D UI Icon Style
- 新增主辅元素比例规则：主元素约 70%，辅助元素约 30%
- 新增材质规则：明亮、干净、轻盈、果冻感、软塑料感、轻微半透明
- 新增光影规则：浅阴影、柔和高光、避免厚重写实

### Route & reference ID system update

- 新增路线编号体系：DBI-00 / DBI-01 / DBI-02 / DBI-03 / DBI-04
- 新增资源类型编号：REF / MAT / APP / NEG / EXA
- 新增引用和文件命名规则：DBI-{路线编号}-{资源类型}-{序号}_v{版本}_{英文说明}
- 明确当前已训练参考图主要归属于 DBI-01 Benefit Cue / 利益点感知型
- 新增 routes/ 目录
- 新增 references/index.md
- 重组 references/ 目录为各路线专属文件夹
