# Reference Index

This file is the resource map for Driver Benefit Icon Skill references.

## Route IDs

| ID | Route | 中文 | Status |
|---|---|---|---|
| DBI-00 | Shared | 统一母风格 | Active |
| DBI-01 | Benefit Cue | 利益点感知型 | Mature baseline |
| DBI-02 | Reward Promo | 奖励营销型 | Expansion |
| DBI-03 | Basic Function | 基础功能型 | Expansion |
| DBI-04 | Emotional Care | 情感化关怀型 | Expansion |

## Resource Type Codes

| Code | Type | 中文 |
|---|---|---|
| REF | Style reference | 风格参考 |
| MAT | Material reference | 材质参考 |
| APP | Approved icon | 已确认图标 |
| NEG | Anti-pattern | 反例 |
| EXA | Example prompt | 示例 |

## Naming Rule

```text
DBI-{route-number}-{resource-type}-{serial}_v{version}_{english-description}.{file-extension}
```

## Recommended Resources

| ID | Folder | File | Purpose | Status |
|---|---|---|---|---|
| DBI-00-REF-001 | DBI-00-shared | DBI-00-REF-001_v1_style-family-reference.png | Defines the shared icon family look | To add |
| DBI-00-MAT-001 | DBI-00-shared | DBI-00-MAT-001_v1_bright-jelly-material-reference.png | Defines bright jelly 3D material | To add |
| DBI-00-NEG-001 | DBI-00-shared | DBI-00-NEG-001_v1_common-anti-patterns.png | Common anti-patterns | Optional |
| DBI-01-REF-001 | DBI-01-benefit-cue | DBI-01-REF-001_v1_benefit-cue-style-reference.png | Defines current mature Benefit Cue route | To add |
| DBI-01-APP-001 | DBI-01-benefit-cue | DBI-01-APP-001_v1_ice-fresh-delivery-approved.png | Approved ice-fresh icon | To add |
| DBI-02-REF-001 | DBI-02-reward-promo | DBI-02-REF-001_v1_reward-promo-style-reference.png | Reward Promo route style reference | To add later |
| DBI-02-APP-001 | DBI-02-reward-promo | DBI-02-APP-001_v1_newcomer-reward-approved.png | Approved newcomer reward icon | To add after confirmation |

## Placement Rule

- Put shared material / family references under `DBI-00-shared/`.
- Put route-specific references under the matching route folder.
- Put approved final icons as `APP`.
- Put style references as `REF`.
- Put material references as `MAT`.
- Put anti-patterns as `NEG`.
- Do not mix drafts, failed outputs, and approved images.
