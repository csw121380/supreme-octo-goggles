# 女娲.skill · 思维蒸馏机

**女娲帮你蒸馏任何人的思维方式，让乔布斯、马斯克、芒格、费曼都给你打工。**

基于开放的 Agent Skills 协议，可在 Claude Code、Codex、Cursor、OpenClaw、Hermes Agent 等 50+ 兼容运行时使用。

## 核心理念

女娲不是复制人，是**提炼思维框架**。

一个好的人物Skill是一套可运行的认知操作系统：
- **心智模型** — 他用什么镜片看世界？
- **决策启发式** — 他用什么直觉规则做判断？
- **表达DNA** — 他怎么说话？
- **反模式** — 他绝对不会做什么？
- **诚实边界** — 这个框架做不到什么？

不是WHAT they said，是HOW they think。

---

## 效果示例

### 蒸馏 Naval Ravikant，问他「时间管理」：

```
用户    ❯ 我同时想做自媒体、写书、做独立开发，精力完全不够

Naval   ❯ 你列了三个欲望。每个欲望都是你跟不快乐签的一份合同。
        不是精力不够，是合同太多。
        
        问你自己：哪一个做起来你会忘记时间？
        那个就是你的特定知识所在。
        
        不是三选一。是先一，再一，再一。
        串行复利，不是并行内耗。
```

### 蒸馏 Elon Musk，问他「如何降获客成本」：

```
用户      ❯ 我们的SaaS产品获客成本太高了

马斯克    ❯ 先别想怎么降。先算物理极限。
          获客的最小必要动作是什么？用户从知道你到付费，
          信息传递的理论最短路径是什么？
          
          现在你的实际路径是理论路径的几倍？
          如果超过3倍，中间一定有可以砍掉的步骤。
          不是优化漏斗，是质疑漏斗本身该不该存在。
```

### 蒸馏 Jobs，问他「OpenAI vs Anthropic 谁的方向对」：

```
用户    ❯ OpenAI和Anthropic谁的方向是对的？

Jobs   ❯ 你问错了。这不是一场关于方向的竞赛。
        这是一场关于品味的竞赛。
        
        OpenAI像1985年的微软。什么都做，什么都要赢。
        这种策略能赢市场份额。Bill Gates就是这么赢的。
        问题是——当你什么都做的时候，你不可能每件事都做到
        insanely great。
        
        Anthropic更像早期的Apple。聚焦。
        Focus means saying no to a hundred good ideas.
```

---

## 女娲蒸馏什么

女娲从6个维度深度调研：

| 维度 | 来源 | 提取内容 |
|------|------|----------|
| **著作** | 书籍、白皮书、长文 | 系统思考、理论框架 |
| **对话** | 播客、访谈、演讲Q&A | 实时思考、即兴反应 |
| **表达** | 推特/邮件/社交媒体 | 用词、句式、风格 |
| **批评** | 媒体评价、竞争对手、反对声音 | 真实局限、反模式 |
| **行动** | 决策记录、产品发布、失败案例 | 言行一致性、学习模式 |
| **时间线** | 职业发展、关键转折 | 成长轨迹、观点演变 |

---

## 已蒸馏的人物

| 人物 | 领域 | NPX 安装 |
|------|------|----------|
| 🔥 **Paul Graham** | 创业/写作/产品 | `npx skills add alchaincyf/paul-graham-skill` |
| **Elon Musk** | 工程/成本/激进迭代 | `npx skills add alchaincyf/elon-musk-skill` |
| **Charlie Munger** | 投资/决策/逆向思考 | `npx skills add alchaincyf/munger-skill` |
| **Richard Feynman** | 学习/科学/第一性原理 | `npx skills add alchaincyf/feynman-skill` |
| **Steve Jobs** | 设计/产品/完整性 | `npx skills add alchaincyf/jobs-skill` |
| **Naval Ravikant** | 财富/哲学/复利 | `npx skills add alchaincyf/naval-skill` |
| **Andrej Karpathy** | AI工程/学习/可靠性 | `npx skills add alchaincyf/andrej-karpathy-skill` |
| **张小龙** | 产品/微信/克制 | `npx skills add alchaincyf/zhang-xiaolong-skill` |
| 和更多... | | |

---

## 安装与使用

### 一行命令安装

```bash
# 安装女娲（思维蒸馏机）
npx skills add alchaincyf/nuwa-skill

# 或者安装已蒸馏的人物Skill
npx skills add alchaincyf/paul-graham-skill
npx skills add alchaincyf/elon-musk-skill
```

### 在 Claude Code 中使用

#### 蒸馏新人物

```
蒸馏一个保罗·格雷厄姆
造一个张小龙的思维框架
我需要一个关于「如何做更好决策」的Skill，推荐人物
```

#### 激活已有Skill

```
用Paul Graham的视角分析我的创业想法
Feynman会怎么解释量子计算？
切换到芒格，帮我分析这个投资机会
Naval的观点是什么？
```

---

## Skill 的5个层次

| 层次 | 说明 | 示例 |
|------|------|------|
| **怎么说话** | 表达DNA——语气、节奏、用词 | 费曼用比喻，马斯克用数字 |
| **怎么想** | 心智模型、认知框架 | 芒格的格栅模型、马斯克的第一性原理 |
| **怎么判断** | 决策启发式 | Naval的「串行复利」vs「并行内耗」 |
| **什么不做** | 反模式、价值观底线 | Jobs的「不做」和「是什么」一样重要 |
| **知道局限** | 诚实边界——这个框架做不到什么 | Feynman坦承他在社会科学上是新手 |

---

## 核心特色

✅ **真框架不是皮肤**
- 每个Skill都包含可运行的心智模型
- 不是ChatGPT套了个名人面具
- 用的是真实决策启发式和思维方式

✅ **多源调研**
- 6个维度、100+小时的深度调研
- 包括公开表达、私下采访、他者视角、行动记录
- 明确标注信息来源和时间戳

✅ **诚实边界**
- 每个Skill都明确说明做不到什么
- 承认框架的局限和盲区
- 没有万能的思维框架

✅ **跨运行时**
- 基于 Agent Skills 协议
- 可在 Claude Code / Codex / Cursor / OpenClaw / Hermes Agent 等 50+ 运行时使用
- 一次蒸馏，到处可用

✅ **Agentic工作流**
- 每个Skill都包含完整的Agentic Protocol
- 问题分类 → 智能研究 → 框架应用
- 用真实信息而不是凭训练数据编造

---

## 官方仓库

🔗 **主仓库**：https://github.com/alchaincyf/nuwa-skill

所有已蒸馏人物都是独立仓库，可以：
- 独立安装使用
- 二次蒸馏和微调
- 贡献改进和新发现

---

## 触发原则

女娲在这些情况下激活：

- 用户明确要求「蒸馏XX」「造XX的Skill」
- 用户问「XX会怎么看」「XX的思维方式是什么」
- 用户需要诊断建议（告诉女娲需求，她推荐人物）
- 用户明确要求思维顾问而不是事实查询

女娲 **不在**这些情况激活：
- 用户只是问简单事实或常识问题
- 用户要求直接回答而不需要思维框架
- 文本是代码、配置、日志等非思维内容

---

## 许可

MIT License — 欢迎分享、修改、二次蒸馏。

---

**你想要的下一个员工，何必是同事？** 🚀
