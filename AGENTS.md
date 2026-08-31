# AGENTS.md

本文件是 AI-Courses 仓库工作入口。任何新会话、研究 Agent、课程设计或开发任务开始前先读取。

## 1. 事实源顺序

1. 当前 GitHub `main`；
2. `README.md`；
3. `docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`；
4. `docs/CROSS_LESSON_COHERENCE_AUDIT_V0.1.md`；
5. `docs/OUTCOME_FIRST_AND_SCAFFOLDING_POLICY.md`；
6. `docs/STANDARD_PERIOD_AND_EXTENSION_POLICY.md`；
7. `docs/CHALLENGE_POOL_SYSTEM_V1.md`；
8. `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`；
9. `courses/shared/CLASSROOM_CARDS_V0.1.md`；
10. `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`；
11. `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`；
12. `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`；
13. `mother-templates/README.md` 与各正式母版；
14. `docs/MOTHER_TEMPLATE_PRODUCTIZATION_SPEC_V0.1.md`；
15. `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`；
16. `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`；
17. `docs/CURRICULUM_RND_AND_SCHOOL_LAUNCH_STRATEGY.md`；
18. `docs/CURRICULUM_DESIGN_EVIDENCE_SYNTHESIS_V1.md`；
19. `docs/CURRICULUM_REVERSE_ENGINEERING_CASE_MATRIX_V1.md`；
20. `docs/DECISIONS.md`；
21. 微信小程序教育平台 T1/T2 真实账号结果；
22. 各 `courses/<course>/` 最新产物。

聊天记录只能补背景，不能覆盖仓库事实。

## 2. 不可违背的产品约束

### 2.1 第一优先：展示级保底成果

> **先保证绝大多数学生都有第一眼很厉害、可试玩、可分享、可展示的成品，再在这个成果之上拉开能力成长和原创深度。**

基础学生不能拿明显低配版，必须达到 `DISPLAY-SAFE BASELINE`。

允许稳定母版、模板、半成品、功能/主题菜单、一键恢复、统一修复、必要局部代操作。

兜底优先级：

> **课程系统兜底 > 模板兜底 > 全班统一救援 > 小组救援 > 个别教师代操作。**

多人掉队只能靠教师逐个长时间救援，说明课程尚未产品化完成。

### 2.2 标准课时前锁成果

- 小学：40分钟，BASE约25–30分钟；
- 初中：45分钟，BASE约30–35分钟。

剩余标准课时用于试玩、判断、修改、反馈与收口。

额外60/90分钟只用于 Challenge / Open Creation，不得成为 BASE 完成条件。

> **40分钟能完整交付，60分钟不水，90分钟仍然有创造空间。**

### 2.3 不是传统编程课

- 不以 Scratch / Python / C++ / HTML/JS 语法为主线；
- 不要求学生先学编程；
- 不要求老师成为程序员；
- 不浪费大量课堂时间在环境配置和复杂 Debug。

### 2.4 AI 原生创造

> **想法 → 自然语言 → AI 第一版 → 试玩/判断 → 修改 → 验证 → 用户反馈 → 再迭代。**

复杂技术封装在 AI、平台和母版后。

### 2.5 技术难度 2/10，作品观感 8/10

视觉/交互复杂度可以高，学生/教师技术负担必须低。

### 2.6 作品是明线，能力是暗线

暗线：需求表达、拆解、判断、验证、迭代、用户视角、事实核查、审美、合作、负责任使用 AI。

### 2.7 AI 说完成不等于完成

必须真实运行、试玩、触发条件、重新验证。

## 3. 当前 Known-Good 母版

### M1 游戏

T1：`FULL STRONG PASS`。

已验证分钟级生成、自然语言改主题/规则/动画、AI自修故障、二维码发布、家长免登录试玩。

资产：`mother-templates/M1-game/README.md`

### M2 学习平台

T2：`STRONG PASS`。

已验证约2分钟生成完整学习/闯关平台，复杂学习规则修改约1–2分钟。

资产：`mother-templates/M2-learning/README.md`

> **不要重新泛搜秒哒/扣子/WorkBuddy，也不要重复证明微信平台能不能生成应用。**

## 4. 当前待验证母版

只剩：

- M3：互动故事 / 分支世界；
- M4：兴趣馆 / 知识产品；
- M5：工作台 / 记录 / 校园工具。

每个只需：

> **首版 + 两次修改 + 一次 Challenge。**

不手写代码，不人工 Debug；出错先让 AI 自修。

入口：
- `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
- `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`

## 5. 当前主课程版本

### Wow Demo

`courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`

### 小学高年级

`courses/primary-upper/SEMESTER_16_LESSONS_V0.3.md`

V0.3 Pair：
- L1/L2 游戏；
- L3/L4 互动世界；
- L5/L6 兴趣馆；
- L7/L8 学习 App；
- L9/L10 校园工具；
- L11/L12 用户+可信；
- L13/L14 Final V1/V2；
- L15/L16 发布+嘉年华。

L6 M2独立闯关仅 Backup；正式默认等 M4 后与 L5 组成兴趣馆 Pair。

### 初中

`courses/middle-school/SEMESTER_16_LESSONS_V0.3.md`

V0.3 Pair：
- L1/L2 第一数字产品；
- L3/L4 Rule Lab；
- L5/L6 真正工具；
- L7/L8 UX→真人测试；
- L9/L10 AI评审→事实核查；
- L11/L12 AI反方→Real Problem Sprint；
- L13/L14 Final V1→V2；
- L15/L16 Release QA→Demo Day。

特别区分：
- L7 = 自己检查体验；L8 = 真人第一次使用；
- L9 = AI评质量；L11 = AI质疑产品假设；
- L12 = 训练赛；L13 = 正式最终项目启动。

旧 V0.1/V0.2 仅历史参考。

## 6. 当前逐课实施事实

事实源：`docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`

### 小学

11/16节已有逐课 V0.1：
- Ready：L1、L2、L7、L8、L15、L16；
- Conditional/Backup：L6、L11、L12、L13、L14；
- Blocked：L3/L4→M3，L5/L6主版→M4，L9/L10→M5。

### 初中

14/16节已有逐课 V0.1/V0.2：
- Ready：L1–L4、L7–L9、L11、L14–L16；
- Conditional：L10、L12、L13；
- Blocked：L5/L6→M5。

## 7. 跨课节奏硬规则

来自 `docs/CROSS_LESSON_COHERENCE_AUDIT_V0.1.md`：

> **方法可以重复，体验不能重复。**

- 每课有一个可截图/试玩变化；
- 每2课一个 Showcase Milestone；
- 每4课至少一次明显作品类型或能力反转；
- 核心“生成→试玩→判断→修改→验证”允许反复练；
- 不允许只是换题目重复同一种表面产品。

认知型课（需求、AI评审、反方、事实核查）原则讲解尽量3–5分钟，能力必须发生在真实作品动作中，不能变成PPT素养课。

## 8. 教师交付标准

教师角色：

> **创意导演 + 节奏控制者 + 支架诊断者 + 成果守门员。**

统一节奏：

> **先看成品 → 快速第一版 → BASE DEADLINE → 能力修改 → Challenge → 稳定收口。**

救援顺序：

> **不帮 → 追问 → 给选项 → 给句式 → FALLBACK → 最后才局部代操作。**

多人同类问题优先全班统一恢复。

教师培训：`courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`

课堂卡：`courses/shared/CLASSROOM_CARDS_V0.1.md`

## 9. 学校首发与迭代

学校首发：`courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`

课堂记录：`courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`

课程达到可交付标准后直接进学校，不再人为增加小样本 Gate。

真实课堂优先记录：完成率、FALLBACK、BASE时间、教师长时间个别救援、共性卡点、Challenge、学校/家长最喜欢的成果。

## 10. 研发方法

> **逆向成熟课程与真实课堂 → 课程结构 → 母版产品化 → 逐课教案 → 教师/学生材料 → 内部走课 → 学校授课 → 真实课堂持续迭代。**

`1老师+5学生` 只保留 Optional Smoke Test，不是强制 Gate。

## 11. 新增文件规则

- 总体研究/政策/共用机制：`docs/`；
- 核心母版：`mother-templates/`；
- 逐课教案/学生材料：对应 `courses/`；
- 跨课程课堂卡、教师培训、学校交付：`courses/shared/`；
- 外部事实保留 URL、核实日期和证据类型；
- 真实账号/真实课堂结果与公开案例严格区分。

## 12. 淘汰测试

出现任一情况默认重新设计：

- BASE接近标准课时才完成；
- 只有拉到60分钟才有完整作品；
- 快学生做完只能等待；
- 保底作品明显像低配版；
- 多人掉队只能逐个技术救援；
- 老师/学生必须大量写代码；
- 大量时间耗在安装、配置、复杂 Debug；
- 一键生成没有学生真实选择；
- AI生成后不试玩、不验证；
- 认知课没有肉眼可见产品升级；
- 连续多课表面作品高度重复；
- 家长/学校10秒内看不懂成果。

## 13. 当前下一执行（必须以此为准）

当前阶段：

> **CURRICULUM V0.3 INTERNAL WALKTHROUGH → M3/M4/M5 MINIMAL VALIDATION → SCHOOL DELIVERY**

1. 不再重复 M1/M2；
2. 对当前已写小学11节、初中14节做内部走课、时间、重复、教师负担审核；
3. 完善 M1/M2 教师演示版、学生卡、展示样例；
4. 有空时按 Run Cards 各跑一次 M3/M4/M5；
5. 通过后立即产品化并补齐被阻塞课次；
6. 完成小学/初中整学期内部走课；
7. 教师完成课程线培训/认证；
8. 达到 School Launch Package Gate 后直接进入合作学校；
9. 用真实课堂数据版本化迭代；
10. 不新增无必要的前置实验门槛。

## 14. 商业与渠道约束

不采用“一次性卖教案”。方向：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

代理商获得当前授权执行层，不默认获得完整研发母版、失败库、内部 Prompt 迭代历史和下一版本计划。

壁垒沉淀在：稳定母版、展示级兜底、Challenge Pool、教师认证、故障恢复、真实课堂数据、学生作品/学校成果和持续更新。

更新时间：2026-09-01
