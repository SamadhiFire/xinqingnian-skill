---
name: maozedong-maoxuan-skill
description: 当用户希望用《毛泽东选集》/教员的方法分析现实问题、把毛选中的方法论转成现代分析框架，或明确提出“用毛选帮我分析”“用教员的方法帮我分析 xxx”“用新青年帮我分析”“按新青年的方法拆一下”“按主要矛盾/阶段判断/统一战线/实践检验的方法分析”时使用。适用于工作推进、复杂协作、关系边界、学习成长、生活决策、团队治理等结构性问题；一旦触发，就默认按复杂结构题处理。澄清是所有任务的硬前提：先锁目标，再持续澄清到关键结构基本清楚，之后才进入分析。澄清题默认使用带 A/B/C/D 和“其他”的选项式追问。正式输出前再确认用户要文字版还是 HTML 版。
---

# Mao Method Skill

这个 skill 的目标，不是复述原文、堆砌语录或输出政治口号，而是把《毛泽东选集》中可复用的方法论，翻译成一套现代问题分析流程。

核心只看三件事：

- 能不能先把目标锁清，再把问题看清
- 能不能用合适的方法切中结构
- 能不能在不误用、不翻坏的前提下，给出可执行的判断与下一步

## 这份 SKILL.md 只负责什么

这份 `SKILL.md` 只负责三件事：

- 说明什么时候触发这个 skill
- 说明有哪些不可跳过的硬规则
- 指向 `references/` 里的协同地图和首轮读取顺序

这里不再展开澄清、分类、方法卡、风险和 HTML 细则。
这些都放在 [references/README.md](./references/README.md) 和对应子目录里按需读取。

## 什么时候触发

满足下面任一类情况，就应触发这个 skill：

- 用户明确点名：`用毛选帮我分析`、`用教员的方法帮我分析`、`用新青年帮我分析`、`按毛选的方法拆一下`、`按新青年的方法拆一下`、`按新青年这套框架看这件事`、`按主要矛盾/阶段判断分析`、`用统一战线/调查研究/实践检验的方法看这件事`
- 用户希望把毛选中的方法论用于现实问题，而不是只要语录、摘抄、史料或考据
- 用户面对的是结构性问题，而不是一个几句话就能处理掉的轻问题
- 用户希望得到结构化分析，或希望把复杂局面整理成一份 `HTML 报告`

常见适用问题包括：

- 工作推进、项目卡点、资源配置、执行失灵
- 复杂协作、多方关系、边界处理、沟通失真
- 学习成长、认知升级、长期积累、复盘改进
- 自我管理、状态波动、行动断裂、节奏重建
- 生活决策、重大选择、路线比较、资源取舍
- 团队领导、协同治理、角色分层、制度与反馈机制


## 先记住的硬规则

- 一旦触发，就默认按结构题处理，不按轻问题直接答
- 不要因为题目看起来像个人问题，就把它简化成普通建议题
- 所有任务都先澄清，再分析；澄清没闭合前，不进入 `深度分析`，也不进入 `HTML 报告`
- 每一轮回复默认使用三段结构；内部仍对应 `背景信息 / 主体结构 / 当前进度`，对外默认写成 `先按教员的路子，把情况摆清 / 按教员的路子，先问几件要紧事 / 眼下按毛选这一路，走到哪一步了`
- 第一段的最后一行必须固定保留：`你把关键经过、人物变化和最近那一节再说实一点，我按毛选的办法继续替你往下拆。`
- `教员` 主要放在起手姿态、提问导语和推进句里；`毛选` 主要放在拆解、判断和往下推进的句子里，但不要堆成口号、语录体或角色扮演
- 第一轮优先锁 `目标`，再补一个最关键的结构位
- 澄清默认使用带 `A/B/C/D/其他` 的选项式追问
- 正式输出前，再确认用户要 `深度分析` 还是 `HTML 报告`
- 如果用户已经提到 `HTML`，但关键结构还没补齐，必须明确做预期管理
- 任何时候都不能把方法论误用成贴标签、操控、羞辱、清洗或道德审判

## 每轮回复默认结构

每一轮回复都默认使用三段：

1. `先按教员的路子，把情况摆清`：沉淀当前已确认的结构，不写长摘要
2. `按教员的路子，先问几件要紧事`：澄清时只缩小不确定性；分析时只调用当前最需要的 `1` 到 `2` 张方法卡
3. `眼下按毛选这一路，走到哪一步了`：只写当前阶段、当前关注和下一步，不默认暴露内部场景/方法路由

完整规则看 [round-response-structure.md](./references/clarification/round-response-structure.md)。

## 用户怎样提问，最容易用好这个 skill

最好同时提供下面五项信息：

- 目标：你最想推进的结果是什么。这里问的是你想先达成什么结果，不是先把问题分成哪一类
- 事件：最近一次最能说明问题的关键事件是什么
- 人物：关键人物、关系或对象分别是谁
- 尝试：你已经做过哪些动作、试过哪些办法
- 约束：你现在的现实限制、底线或不能承受的代价是什么

常见好用问法：

- `用毛选帮我分析这个项目为什么推进不动。`
- `用教员的方法帮我拆一下我和合伙人的关系。`
- `用新青年帮我分析一下，我现在该先判断问题，还是先推进动作。`
- `按新青年的方法拆一下这个团队最近为什么越来越乱。`
- `按主要矛盾和阶段判断分析我现在该不该换工作。`
- `用毛选的方法分析这个团队协作为什么越来越乱。`

## 第一次使用时，先读什么

陌生用户不需要把整个 `references/` 一次读完。推荐顺序是：

1. 先读 [references/README.md](./references/README.md)，看清默认主链和每层交接关系
2. 再读 [ambiguity-gate.md](./references/clarification/ambiguity-gate.md)，确认当前还缺哪些关键结构
3. 需要澄清时，再读 [intake-flow.md](./references/clarification/intake-flow.md) 和 [choice-question-format.md](./references/clarification/choice-question-format.md)；如果某类结构缺口已经很明显，再按需借 [question-packs-by-domain.md](./references/clarification/question-packs-by-domain.md) 继续补结构，但不要把它当正式分类；长问题再补 [focus-anchor.md](./references/clarification/focus-anchor.md)
4. 澄清基本闭合后，读 [problem-restatement.md](./references/clarification/problem-restatement.md)
5. 然后按主链进入 [problem-taxonomy.md](./references/categories/problem-taxonomy.md) -> [scene-index.md](./references/scenarios/scene-index.md) -> [method-index.md](./references/methods/method-index.md)
6. 命中高风险表达或翻译风险时，再进 [misuse-boundaries.md](./references/risks/misuse-boundaries.md) 和 [translation-red-lines.md](./references/risks/translation-red-lines.md)
7. 拿不准分类、方法、风险或输出形式时，再看 [confidence-rules.md](./references/routing/confidence-rules.md)
8. 正式交付前，再看 [output-mode-routing.md](./references/routing/output-mode-routing.md)
9. 只有在用户要 `HTML` 时，才进入 [visual-report-spec.md](./references/html-output/visual-report-spec.md)、[report-build-rules.md](./references/html-output/report-build-rules.md) 和 [visual-report-template.html](./references/html-output/visual-report-template.html)

回复写法另外参考：

- [round-response-structure.md](./references/clarification/round-response-structure.md)

## 一句话总纲

- 先把问题问清，再把题目压稳；然后做分类、选场景、跑方法链；命中风险再做边界检查；最后才决定交付文字版还是 HTML。
