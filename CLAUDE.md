# perspective-router 宪法

## 唯一真相源

| 什么 | 真相源 | 规则 |
|------|--------|------|
| 人物思维框架 | `references/perspective-{slug}.md` | 每个文件是单一人物的完整蒸馏，不可拆分到多个文件 |
| 路由索引 | `SKILL.md` §人物索引表 | 新增人物必须同时在此注册，否则路由不到 |
| 文件命名 | `perspective-{slug}.md` | slug 用英文小写+连字符，与索引表中 reference 路径严格一致 |

## 新增人物 checklist

1. `references/perspective-{slug}.md` — 按模板写蒸馏文件
2. `SKILL.md` 人物索引表 — 新增一行，含人物名、触发词、参考文件路径
3. 确认触发词覆盖中英文名+常用别名

**不注册 = 不存在。** references/ 里有文件但索引表没有 → 路由不到，等于没有。

## 文件结构

每个 reference 文件必须含：心智模型、决策启发式、表达DNA、诚实边界

## 禁止

- 索引表指向不存在的文件
- references/ 下有文件但未注册到索引表
- 用中文文件名（shell 编码兼容）
