# 实事求是.skill

<img width="852" height="429" alt="image" src="https://github.com/user-attachments/assets/38b0acb7-52a4-4449-8dfb-311b97874f89" />


[English](README_EN.md)

基于"**解放思想、实事求是、与时俱进**"方法论的 AI 分析技能，结合矛盾论与实践论，帮助 AI 对问题进行独立、客观、辩证的可行性分析，拒绝无节制迎合与空洞发散。

## 核心思想

| 原则 | 作用 |
|------|------|
| **解放思想** | 打破惯性认知，识别并悬置先入为主的假设 |
| **实事求是** | 基于客观事实评估，结论由事实推导，不由期望倒推 |
| **与时俱进** | 动态发展视角，识别当前阶段的特殊性与时间窗口 |
| **矛盾论** | 找主要矛盾，定矛盾性质，分析转化条件 |
| **实践论** | 验证认识，制定可落地、有验证节点的行动路径 |

## 安装

### Claude Code / Cursor

两者使用相同的 skill 格式，一条命令同时生效。

安装到当前项目（在 git 仓库根目录执行）：

```bash
mkdir -p .claude/skills
git clone https://github.com/BiscuitCoder/seek-truth-from-facts-skill .claude/skills/seek-truth-from-facts
```

或安装到全局（所有项目都能用）：

```bash
git clone https://github.com/BiscuitCoder/seek-truth-from-facts-skill ~/.claude/skills/seek-truth-from-facts
```

### OpenClaw

```bash
git clone https://github.com/BiscuitCoder/seek-truth-from-facts-skill ~/.openclaw/workspace/skills/seek-truth-from-facts
```

## 适用场景

- 评估某个想法或计划是否可行
- 分析某个复杂问题的核心矛盾
- 制定有验证节点的行动路径
- 需要防止 AI 无节制迎合或过度乐观的场合

## 语言版本

`SKILL.md` 为**单一入口**，内含中英文完整说明与语言匹配规则；代理会按用户首条消息语言选用对应章节，无需再维护两个文件。

## 目录结构

```
seek-truth-from-facts/
├── SKILL.md                          # 双语技能入口（YAML frontmatter + 中/英正文）
└── references/
    ├── contradiction-theory.md       # 矛盾论分析工具
    └── practice-theory.md            # 实践论与行动路径指南
```

## License

MIT
