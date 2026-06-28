# DAG — Daily Runtime

> Given your current state, this tells you what to do next.
> Not a schedule. A decision tree you run every time you switch contexts.

---

## Step 1 — Read Your State

Ask yourself three questions:

```
Energy?      [High / Medium / Low / Idle]
Time block?  [Deep (90min+) / Shallow (30-60min) / Fragment (<30min)]
Mode?        [Morning / Afternoon / Evening / Recovery]
```

---

## Step 2 — Route to Action

```
High Energy
├── Deep block      → CREATE or SEARCH (code, writing, research, Blender)
├── Shallow block   → EXPLORE (new domain, design critique, reading)
└── Fragment        → CAPTURE (log insight, update a file, quick review)

Medium Energy
├── Deep block      → UPGRADE (study, deliberate practice, investment analysis)
├── Shallow block   → ALIGN (plan, respond, organize, update notes)
└── Fragment        → CONNECT (message someone, light reading)

Low Energy
├── Any block       → RECOVER (physical — climb, basketball, walk) or CACHE (passive input — podcast, video)
└── If stuck        → GC: close everything, rest, do nothing productive

Idle / Sleep
└── REBUILD — no decisions, no input, just rest
```

---

## Step 3 — Pick the Domain

Once you know the action type, pick which domain to apply it to.
Use the **50/30/20 rule** from `mind_exercise.md`:

| Allocation | What |
|------------|------|
| 50% | Core career domain (AI infra / distributed systems) |
| 30% | Adjacent compounding (investment, design, writing) |
| 20% | Exploration rotation (current: biology/cognitive) |

If you haven't done your 50% work today → go there first, always.

---

## Step 4 — Execute with the Right Mental Mode

Match the task to the right mental set (`Input_agents.md`):

| Task type | Mental mode |
|-----------|------------|
| Algorithm, debugging, math | 🔍 Reductionist |
| System design, architecture | 🧱 Abstractionist |
| New domain, skill practice, market sense | 🧬 Empiricist |
| Creative work, cross-domain ideas | 🌀 Generative |
| Stuck, overwhelmed, switching contexts | 🧭 Orchestrator (this mode — zoom out) |

---

## Daily Cognitive Order
> 认知资源是有限的，顺序错了效率减半。

```
早上（前额叶最活跃）
→ 大提琴 30min（flow priming）
   不看手机，不开邮件
   用已熟悉的技能把大脑带进专注状态

→ Design 30min（趁专注状态未散）
   今日唯一的核心问题，AI Infra、kids community 的关键决策
   output = 今日唯一那一行字

上午中段（认知成本中等）
→ 输入（30min investment / 30min design）
   学习前：「我今天想搞清楚什么问题？」
   学习后：「搞清楚了吗？还有什么没懂？」
→ Ambiguity Handling
   处理 iOS ship、kids community 的具体 ambiguity
   Design 先想清楚，Ambiguity 才有边界

下午（执行为主）
→ Execution
   写代码、记录、整理、routine 任务

晚上（前额叶耗尽）
→ Recovery / 被动输入
   攀岩、阅读、音乐，不做需要深度思考的事
```

**原则：Design 给 Ambiguity 划边界，没有 Design 的 Ambiguity 是无限的。**

---

## Step 5 — Close the Loop

At the end of each session (not each day — each session):

```
1. Did I do what I intended?          Y / N
2. What was the actual output?        [one line]
3. What's the next open question?     [one line — this seeds tomorrow]
```

Log to the relevant Reality/ folder: `Create/`, `Search/`, `Align/`, or `Upgrade/`.

---

## Weekly Maintenance (Sunday)

Run `Review.md` protocol:

```
1. What did Reality/ actually contain this week?
2. Does it match the Model's 50/30/20 allocation?
3. What parameter is drifting? Adjust ONE thing.
4. What goes into Wisdom/?
```

Halt condition: if you're adjusting more than one parameter per week, stop — the system is unstable. Rest first.

---

## Cascade Failure Warning Signs

| Signal | Meaning | Response |
|--------|---------|----------|
| Can't enter deep work for 2+ days | Sleep or stress degradation | Fix Layer 1 (sleep, physical) first |
| Spending more time on Model than Reality | Over-engineering | Freeze Model, run Reality for 1 week |
| Skipping Review for 2+ weeks | System drift | Emergency review, not normal review |
| All energy going to one domain | Portfolio collapse | Force 20% exploration block |
