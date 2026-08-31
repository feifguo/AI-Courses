# AI-Courses

面向中小学生的 AI 兴趣课程研究、产品设计与课程产物仓库。

## 当前产品目标

本仓库当前优先研发两条正式课程线，并配套一个快速展示 AI 创造力的入门演示课：

1. **小学高年级 AI 创造课**：低技术门槛，以角色、故事、互动作品、小游戏、轻量应用等为载体。
2. **初中 AI 数字创造课**：不以传统编程为前置，充分借助 AI，让学生通过自然语言、选择、修改、试玩和迭代完成可运行的游戏/应用/AI 作品。
3. **AI Wow Demo / 入门演示课**：在很短时间内让学生、家长和学校看到“原来孩子现在可以用 AI 做到这个”的成果，用于体验、招生活动、开放日及正式学期课导入。

小学低年级暂不作为第一优先正式学期产品；保留教师主导、低文字负担的启蒙工作坊方向，待高年级和初中产品跑通后验证。

## 核心定位

> 从“问 AI”走向“用 AI 创造”。

课程不是传统编程课的简化版，也不是 AI 工具功能说明课。目标是利用 AI 把复杂技术封装在背后，让学生用很简单的操作和自然语言获得过去通常需要较高技术门槛才能实现的创造能力。

**作品是明线，AI 使用能力是暗线。**

学生感受到的是：做游戏、做互动故事、做网站/轻应用、做会对话的角色、做自己的数字产品。

课程实际培养的是：表达需求、任务拆解、提问、判断、验证、迭代、审美、逻辑、信息甄别、合作与负责任使用 AI。

## 仓库结构

```text
AI-Courses/
├── AGENTS.md
├── README.md
├── docs/
│   ├── PRODUCT_STRATEGY.md
│   ├── COMPETITIVE_RESEARCH.md
│   ├── PRODUCT_COMPARISON.md
│   ├── DECISIONS.md
│   ├── TOOL_AND_WOW_SCAN_2026-08-31.md
│   ├── TOOL_CANDIDATE_MATRIX_2026-08-31.md
│   ├── CLASSROOM_PLATFORM_ECONOMICS_AND_RISKS_2026-08-31.md
│   ├── SCHOOL_NATIVE_PLATFORM_SCAN_2026-08-31.md
│   ├── P0_HANDS_ON_BENCHMARK_PROTOCOL_V1.md
│   ├── WECHAT_MINIPROGRAM_EDU_HANDS_ON_TEST_V1.md
│   ├── WECHAT_MINIPROGRAM_EDU_T1_REAL_ACCOUNT_RESULT_2026-08-31.md
│   ├── WECHAT_MINIPROGRAM_EDU_T2_ENGLISH_PLATFORM_TEST_V1.md
│   ├── WECHAT_MINIPROGRAM_EDU_T2_REAL_ACCOUNT_RESULT_2026-08-31.md
│   ├── PLATFORM_DEPENDENCY_AND_CHANNEL_RISK.md
│   └── CHANNEL_MOAT_STRATEGY.md
└── courses/
    ├── demo/README.md
    ├── primary-upper/README.md
    ├── middle-school/README.md
    └── primary-lower/README.md
```

后续每条课程线自己的教案、教师手册、学生材料、作品模板、Demo Day 方案、工具配置、试课记录等，应继续放入对应课程目录，不要把所有课程产物混放在 `docs/` 或仓库根目录。

## 当前工具 Known-Good

### 微信小程序教育平台 T1 — FULL STRONG PASS

真实账号完成：

- 记忆力翻牌小游戏；
- 主题个性化；
- 倒计时、失败、连击、加分等程序规则修改；
- 通关火箭动画；
- 真实“加载中”故障由 AI 自己修复；
- 每次生成/修改均在 1 分钟以内；
- 发布二维码成功；
- 家长端无需登录直接试玩。

### 微信小程序教育平台 T2 — STRONG PASS

真实账号完成五年级英语单词学习/闯关平台及后续规则修改。

实测耗时：

- 首次开发约 2 分钟；
- 第一次修改约 2 分钟；
- 后两次修改约 1 分钟。

这已经真实验证：

> **小学五年级水平的学生，不需要先学传统编程，就能够借助 AI 在分钟级做出一个完整、可使用、可继续迭代的学习产品。**

因此当前不再把主要研发时间用于证明“AI 能不能做出产品”。

## 当前阶段

当前阶段已经从：

> **TOOL CAPABILITY VALIDATION**

转入：

> **CLASSROOM DELIVERY VALIDATION + DEMO PRODUCTIZATION**

下一步重点：

1. 5 个学生账号小规模真实测试；
2. 教师分发任务、查看和收集学生作品；
3. 多人同时使用 AI 时的并发与额度；
4. 设计 45–60 分钟 Wow Demo V0.1；
5. 让一个普通、不会编程的代理教师照脚本试教；
6. 通过后再决定是否需要 30 人课堂模拟。

当前原则仍然是：如果微信平台本身能稳定满足主要课程需求，就优先采用单平台课堂体验；只有出现明确能力缺口时，才重新引入秒哒、扣子等第二创作引擎。

## 商业交付与壁垒

不采用“一次性卖教案”模式。当前方向为：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

核心壁垒不是让代理商看不到课程，而是让正规代理使用我们的最新课程、教师认证、稳定模板、技术救援、作品集、证书和学校成果报告时，比自行复制更省事、更容易成交和续费。

底层创作平台必须保持可替换。平台供应商若本身也直接销售“平台 + 课程 + 师训 + 到校服务”，还要额外评估渠道冲突，避免我们的学校关系和课程品牌被底层平台吞没。

更新时间：2026-08-31
