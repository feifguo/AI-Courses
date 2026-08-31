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
│   ├── WECHAT_MINIPROGRAM_EDU_5_STUDENT_CLASSROOM_VALIDATION_V1.md
│   ├── WECHAT_MINIPROGRAM_EDU_5_STUDENT_OBSERVATION_FORM.md
│   ├── WECHAT_MINIPROGRAM_EDU_PRECLASS_SETUP_V1.md
│   ├── PLATFORM_DEPENDENCY_AND_CHANNEL_RISK.md
│   └── CHANNEL_MOAT_STRATEGY.md
└── courses/
    ├── demo/
    │   ├── README.md
    │   └── WECHAT_WOW_DEMO_V0.1.md
    ├── primary-upper/README.md
    ├── middle-school/README.md
    └── primary-lower/README.md
```

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

同时，微信小程序教育平台已有真实中小学规模化使用，因此当前也不需要把“5 人会不会同时生成、学校账号体系能不能跑”作为课程研发的核心验证题。进入具体学校实施前，再做该校账号、浏览器、网络、权限和发布的简短 smoke check 即可。

## 当前阶段

当前阶段已经调整为：

> **COURSE CALIBRATION + DEMO PRODUCTIZATION**

当前真正要验证的是：

> **学生 × 教师 × AI 的教学协作模型。**

5 人真实 Pilot 主要用于回答：

- 五/六年级学生能否自己产生想法；
- 能否把想法表达成 AI 可以执行的要求；
- 能否发现 AI 第一次哪里没有做好；
- 能否把复杂想法拆成小修改；
- 会不会实际试玩和验证；
- 能否主动产生“我还想让它……”；
- 普通教师应该在创意、表达、拆解、判断、验证中的哪些节点介入；
- 一节课的合适任务量、自由度和脚手架到底是多少。

平台的登录、限流、作品保存和发布如果现场自然出现异常就记录，但**不再专门把 Pilot 做成软件压力测试**。

## Demo V0.1 当前主任务

采用：

> **同一个稳定小游戏骨架 + 主题自由 + 规则自由 + 一个“我还想让它……”的个人创意。**

不是全班复制同一个 Prompt，也不是让零基础学生完全自由开发完全不同产品。

T2 的英语学习平台作为：

- 开场/结尾能力上限展示；
- 正式学期课程“从好玩到有用”的下一次能力跃迁；
- 校长/家长理解课程长期价值的重要作品。

## 当前下一执行

下一事实门槛：

> **5 STUDENT COURSE CALIBRATION PILOT**

顺序：

1. 用 `courses/demo/WECHAT_WOW_DEMO_V0.1.md` 让 5 名真实小学高年级学生试跑；
2. 用 `WECHAT_MINIPROGRAM_EDU_5_STUDENT_OBSERVATION_FORM.md` 记录学生想法、表达、判断、验证、修改、主动性和教师介入；
3. 用 `WECHAT_MINIPROGRAM_EDU_5_STUDENT_CLASSROOM_VALIDATION_V1.md` 输出学生能力边界、教师介入模型和课程难度标准；
4. 根据真实行为出 Demo V0.2；
5. 形成普通教师追问话术与课程脚手架；
6. 让一名不会编程的代理教师照脚本试教；
7. 随后开始设计完整学期课的能力阶梯；
8. 进入具体学校实施前，再做该校环境 smoke check。

## 商业交付与壁垒

不采用“一次性卖教案”模式。当前方向为：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

核心壁垒不是让代理商看不到课程，而是让正规代理使用我们的最新课程、教师认证、稳定模板、技术救援、作品集、证书和学校成果报告时，比自行复制更省事、更容易成交和续费。

底层创作平台必须保持可替换。

更新时间：2026-08-31
