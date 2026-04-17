# 陈之汉视角 Skill

这是一个面向 Codex 的人物视角 Skill 仓库，对应的技能名是 `chen-chih-han-perspective`。

它适合用来做：

- 人物视角分析
- 指定语气改写
- 角色化回答
- 用特定人格风格来判断商业、冲突、忠诚、舆论等问题

这不是陈之汉本人发言。
这是基于整理材料提炼出来的一份可复用 Skill。

## 仓库内容

- `chen-chih-han-perspective/SKILL.md`
  主技能文件

- `chen-chih-han-perspective/references/research/`
  研究资料整理

- `chen-chih-han-perspective/references/sources/`
  原始来源资料预留目录

- `chen-chih-han-perspective/scripts/`
  辅助脚本预留目录

## 快速使用

### 1. 复制技能目录

把下面这个目录复制到你的 Codex skills 目录里：

```text
chen-chih-han-perspective/
```

### 2. 保持目录结构不变

建议不要改文件夹名。
`SKILL.md` 需要保留在 `chen-chih-han-perspective/` 根目录下。

### 3. 新开一个会话

把 Skill 放好后，重新开一个新的 Codex 会话，让环境重新识别技能。

### 4. 在提示词里主动触发

你可以这样用：

- `用陈之汉的视角分析这件事`
- `馆长会怎么看这个合作`
- `切换到馆长模式回答`
- `用 chen-chih-han-perspective 的方式重写这段话`

## 示例提问

- `用陈之汉的视角判断这个人靠不靠谱`
- `馆长会怎么评价这场舆论冲突`
- `把这段太软的回复改成更强硬的风格`
- `分别给我一个中性版本和一个馆长风格版本`
- `用这个 skill 帮我重写成更有压迫感的表达`

## 适合的使用场景

这份 Skill 更适合：

- 要一个鲜明立场
- 要一种判断风格
- 要改语气
- 要角色化表达
- 要把普通说法改成更有个性的说法

这份 Skill 不太适合：

- 查事实真伪
- 做完全中立的百科式说明
- 法律、医疗、金融等需要高准确性的建议

## 仓库结构

```text
chen-chih-han-skill/
|- README.md
|- README.zh-CN.md
|- .gitignore
`- chen-chih-han-perspective/
   |- SKILL.md
   |- references/
   |  |- research/
   |  `- sources/
   `- scripts/
```

## 研究资料结构

当前研究目录按主题拆分，便于维护：

- `01-writings.md`
- `02-conversations.md`
- `03-expression-dna.md`
- `04-external-views.md`
- `05-decisions.md`
- `06-timeline.md`
- `07-recent-year-events.md`

## 如果你想二次改造

你可以按下面的方式复用这套结构：

1. 复制 `chen-chih-han-perspective/`
2. 改成你自己的新人物目录名
3. 替换研究材料
4. 重写 `SKILL.md` 里的角色、语气、边界和触发方式

这样很适合把“临时的人物提示词”整理成“长期可复用的 skill 仓库”。

## 发布前提醒

- 公开前先检查研究资料是否适合公开
- 公开前检查 `SKILL.md` 是否有乱码
- 如果你暂时不想让别人随意复用，可以先不加开源许可证
- 如果后续会持续更新，可以补一个 `CHANGELOG.md`

## 致谢

这份 Skill 仓库的整理方式，参考了 `huashu-nuwa`（女娲 Skill）的思路。

女娲 Skill 的核心方法，是把一个人物、主题，甚至模糊需求，整理成可复用的 Skill，通常包含这样一条链路：

1. 收集资料
2. 提炼思维框架
3. 蒸馏表达风格
4. 打包成可运行 Skill

这份 `chen-chih-han-perspective` 可以看作这种 Skill 工作流的一个具体产物。

## 仓库命名建议

- `chen-chih-han-skill`
- `chen-chih-han-perspective`
- `codex-chen-chih-han-perspective`
