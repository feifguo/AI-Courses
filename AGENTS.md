# AGENTS.md

本文件是 AI-Courses 仓库的工作入口。任何新会话、研究 Agent、课程设计或开发任务开始前先读取。

## 1. 事实源顺序

1. 当前 GitHub `main`；
2. `README.md`；
3. `docs/OUTCOME_FIRST_AND_SCAFFOLDING_POLICY.md`；
4. `docs/STANDARD_PERIOD_AND_EXTENSION_POLICY.md`；
5. `docs/CHALLENGE_POOL_SYSTEM_V1.md`；
6. `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`；
7. `mother-templates/README.md` 与各正式母版；
8. `docs/MOTHER_TEMPLATE_PRODUCTIZATION_SPEC_V0.1.md`；
9. `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`；
10. `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`；
11. `docs/CURRICULUM_RND_AND_SCHOOL_LAUNCH_STRATEGY.md`；
12. `docs/CURRICULUM_DESIGN_EVIDENCE_SYNTHESIS_V1.md`；
13. `docs/CURRICULUM_REVERSE_ENGINEERING_CASE_MATRIX_V1.md`；
14. `docs/DECISIONS.md`；
15. 微信小程序教育平台 T1/T2 真实账号结果；
16. `docs/PRODUCT_STRATEGY.md`；
17. `docs/COMPETITIVE_RESEARCH.md`；
18. 各 `courses/<course>/` 最新产物。

聊天记录只能补背景，不能覆盖仓库事实。

## 2. 不可违背的产品约束

### 2.1 第一优先：展示级保底成果

课程设计硬排序：

> **先保证绝大多数学生都有第一眼很厉害、可试玩、可分享、可展示的成品，再在这个成果之上拉开能力成长和原创深度。**

基础学生的保底版本不能是明显低配版，必须达到 `DISPLAY-SAFE BASELINE`。

必要时允许：

- 预设模板；
- 预制稳定母版；
- 半成品；
- 功能/主题菜单；
- 一键恢复；
- 教师统一修复提示；
- 教师局部操作协助。

兜底优先级：

> **课程系统兜底 > 模板兜底 > 全班统一救援 > 小组救援 > 个别教师代操作。**

如果全班同时有 8 个学生掉队，而老师只能逐个坐过去帮 5–10 分钟，说明课程还没有产品化完成。

### 2.2 标准课时之前必须锁定成果

默认适配：

- 小学：40 分钟；
- 初中：45 分钟。

但正式课不能按“刚好40/45分钟完成”设计。

硬要求：

> **BASE / FALLBACK 展示级成品必须在标准课时结束前明显完成，并留出试玩、修复、收口和展示缓冲。**

时间预算：

- 小学 BASE：约 25–30 分钟；
- 初中 BASE：约 30–35 分钟；
- 剩余标准课时用于试玩、判断、修改、反馈与收口；
- 50/60/90 分钟或双课时的额外时间只用于 Challenge / Open Creation。

目标：

> **40 分钟能完整交付，60 分钟不水，90 分钟仍然有创造空间。**

### 2.3 不是传统编程课

- 不以 Scratch / Python / C++ 语法为主线；
- 不要求学生先学编程；
- 不要求老师成为程序员；
- 不把课堂时间浪费在环境配置、语法和复杂 Debug。

### 2.4 AI 原生创造

核心循环：

> **想法 → 自然语言 → AI 第一版 → 试玩/判断 → 修改 → 验证 → 用户反馈 → 再迭代。**

复杂技术尽量封装在 AI、模板和平台之后。

### 2.5 技术难度 2/10，作品观感 8/10

如果一个项目只有掌握大量技术细节才能稳定完成，即使很酷也不符合当前方向。

### 2.6 作品是明线，能力是暗线

暗线包括：表达需求、提问、任务拆解、判断、验证、迭代、审美、信息甄别、合作和负责任使用 AI。

### 2.7 AI 说完成不等于完成

必须坚持：

> **生成 → 实际试玩/使用 → 发现问题 → 再描述 → 验证修复。**

禁止把“复制 Prompt → AI 完成”当成课程能力。

## 3. 当前工具与母版 Known-Good

### 微信小程序教育平台 T1 — FULL STRONG PASS

已真实验证：分钟级小游戏、自然语言改规则/动画、AI 自修故障、二维码发布、家长免登录体验。

对应正式母版：

`mother-templates/M1-game/README.md`

状态：KNOWN-GOOD / PRODUCTIZATION V0.1。

### 微信小程序教育平台 T2 — STRONG PASS

已真实验证：约 2 分钟生成五年级英语学习/闯关平台，并在 1–2 分钟内完成复杂学习规则、游戏化和自定义内容修改。

对应正式母版：

`mother-templates/M2-learning/README.md`

状态：KNOWN-GOOD / PRODUCTIZATION V0.1。

因此：

> **不要继续把主要时间用于证明微信平台能不能生成应用，也不要重新泛搜秒哒/扣子/WorkBuddy。**

## 4. 当前待验证母版

只剩三类会覆盖大量课次、但尚未成为项目 Known-Good 的核心母版：

- M3：互动故事 / 分支世界；
- M4：兴趣馆 / 知识产品；
- M5：工作台 / 记录 / 校园工具。

实测使用：

- 详细协议：`docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`；
- 速查卡：`docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`。

每个只跑：

> **首版 + 两次修改 + 一次 Challenge。**

不手写代码，不人工 Debug；出错先让 AI 自修。

结果只需要记录耗时、故障、自修、是否碰代码、最终试玩/展示结果。

## 5. 当前研发方法

正式研发方法：

> **真实课堂/成熟课程逆向研究 → 课程 V0.x → 母版产品化 → 教师/学生材料 → 内部完整走课 → 直接进入学校真实授课 → 用真实课堂持续迭代。**

不再把 `1 老师 + 5 学生` Pilot 当作课程研发强制 Gate。

原因：教师与学生差异大、小样本外部效度低、微信平台已有真实学校规模化使用证据。

现有 5 人协议只保留为：

> **OPTIONAL USABILITY SMOKE TEST**

不得用单一老师 + 5 名学生推断整个年龄段、普通教师总体能力或正式课程标准。

平台进入具体学校前只做该校账号/浏览器/网络/权限/发布 smoke check。

## 6. 当前课程设计基线

### 6.1 不规定统一 Prompt 数量

规定必须经历的认知动作：

> **目标 → 第一版 → 找问题 → 修改 → 试玩验证 → 同伴/用户反馈 → 再迭代。**

### 6.2 采用支架梯度

同一个核心任务优先设计：

- **基础路径**：具体示例、半结构化模板、功能菜单，并保证保底成品仍有强展示效果；
- **进阶路径**：只给目标与约束，让学生自己组织需求；
- **开放挑战**：学生自行定义产品、用户和功能。

低经验学生需要更多具体扶手；高能力学生应逐步撤掉模板。

### 6.3 教师是支架诊断者，不是技术救火队

教师统一方法见：

`docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`

救援顺序：

> **不帮 → 追问 → 给选项 → 给句式 → FALLBACK → 最后才局部代操作。**

多人出现同一问题时优先全班统一救援。

### 6.4 年龄不是唯一分级标准

课程真正要分级的是：

> **目标清晰度、表达能力、任务拆解、判断、验证、AI 协作成熟度。**

## 7. 当前课程产品线与版本

- `courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`：当前 Wow Demo 主版本；
- `courses/primary-upper/SEMESTER_16_LESSONS_V0.2.md`：当前小学高年级16课时主版本；
- `courses/middle-school/SEMESTER_16_LESSONS_V0.2.md`：当前初中16课时主版本；
- `courses/primary-lower/`：小学低年级候选方向，暂不优先开发完整学期课。

旧 V0.1 文件只保留历史参考，不再作为默认课程版本。

## 8. 新增文件规则

- 总体研究、竞品、共用原则：放 `docs/`；
- 核心母版：放 `mother-templates/`；
- 具体课程教案、学生材料、展示材料：放对应 `courses/`；
- 外部事实保留来源 URL、核实日期和证据类型；
- 不把营销口径写成独立验证事实；
- 真实账号/真实课堂结果单独保留，区分公开案例与本项目 Known-Good。

## 9. 设计每节课前的淘汰测试

出现以下任一情况，默认重新设计：

- 基础学生即使用模板和支架，仍难以在标准课时结束前明显提前拿到展示级成品；
- 小学 BASE 通常需要接近 40 分钟、初中 BASE 通常需要接近 45 分钟；
- 只有拉长到 60 分钟才有完整作品；
- 快学生做完只能等待，没有 Challenge / Open Creation；
- 保底作品明显廉价、简陋或像“差生版”；
- 多名学生掉队时只能靠老师逐个长时间救援；
- 老师必须会写或解释大量代码；
- 学生必须手敲大量代码；
- 大量时间花在安装、账号、环境和复杂 Debug；
- 作品只是“一键生成”，缺少学生自己的选择、规则与迭代；
- AI 生成后学生不试玩、不验证；
- 家长看不到明显成果；
- 学校难以做成果展示；
- 一旦某个工具失效，整门课就无法替换。

## 10. 当前下一执行（必须以此为准）

当前正式阶段：

> **MOTHER TEMPLATE VALIDATION → PRODUCTIZATION → SCHOOL DELIVERY**

1. M1/M2 不再重复验证，继续产品化与映射课次；
2. 按 `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md` 真实测试 M3/M4/M5；
3. 将结果记录为 Strong Pass / Pass with Guardrails / Fail；
4. 只对通过的 M3/M4/M5 建立正式 `mother-templates/` 资产；
5. 把 M1–M5 映射回小学/初中16课时 V0.2；
6. 形成逐课教师手册、学生任务卡、FALLBACK、Recovery 与 Showcase；
7. 做内部完整走课；
8. 达到 `CURRICULUM_RND_AND_SCHOOL_LAUNCH_STRATEGY.md` 内部发布 Gate 后直接进入学校授课；
9. 从真实授课持续收集教师/学生/学校反馈，版本化迭代；
10. 不新增无必要的前置实验门槛。

## 11. 商业与渠道约束

商业交付不采用“一次性卖教案”。当前方向：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

代理商主要擅长销售与教学，不应默认获得完整研发母版、失败数据、核心 Prompt 库和下一版本规划。

完整母版、失败库、稳定 Prompt 组合和恢复策略属于内部核心资产。

底层平台必须可替换；壁垒沉淀在课程设计、稳定母版、教师认证、故障恢复、学生作品、学校成果报告和持续更新中。

详见：`docs/CHANNEL_MOAT_STRATEGY.md`。

更新时间：2026-09-01
