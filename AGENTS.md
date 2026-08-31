# AGENTS.md

本文件是 AI-Courses 仓库工作入口。任何新会话、研究 Agent、课程设计或开发任务开始前先读取。

## 1. 事实源顺序

1. 当前 GitHub `main`；
2. `README.md`；
3. `docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`；
4. `docs/OUTCOME_FIRST_AND_SCAFFOLDING_POLICY.md`；
5. `docs/STANDARD_PERIOD_AND_EXTENSION_POLICY.md`；
6. `docs/CHALLENGE_POOL_SYSTEM_V1.md`；
7. `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`；
8. `courses/shared/CLASSROOM_CARDS_V0.1.md`；
9. `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`；
10. `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`；
11. `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`；
12. `mother-templates/README.md` 与各正式母版；
13. `docs/MOTHER_TEMPLATE_PRODUCTIZATION_SPEC_V0.1.md`；
14. `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`；
15. `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`；
16. `docs/CURRICULUM_RND_AND_SCHOOL_LAUNCH_STRATEGY.md`；
17. `docs/CURRICULUM_DESIGN_EVIDENCE_SYNTHESIS_V1.md`；
18. `docs/CURRICULUM_REVERSE_ENGINEERING_CASE_MATRIX_V1.md`；
19. `docs/DECISIONS.md`；
20. 微信小程序教育平台 T1/T2 真实账号结果；
21. 各 `courses/<course>/` 最新产物。

聊天记录只能补背景，不能覆盖仓库事实。

## 2. 不可违背的产品约束

### 2.1 第一优先：展示级保底成果

> **先保证绝大多数学生都有第一眼很厉害、可试玩、可分享、可展示的成品，再在这个成果之上拉开能力成长和原创深度。**

基础学生不能拿明显低配版，必须达到 `DISPLAY-SAFE BASELINE`。

允许：稳定母版、预设模板、半成品、功能/主题菜单、一键恢复、教师统一修复、必要局部代操作。

兜底优先级：

> **课程系统兜底 > 模板兜底 > 全班统一救援 > 小组救援 > 个别教师代操作。**

如果多人掉队只能靠老师逐个长时间救援，说明课程尚未产品化完成。

### 2.2 标准课时前锁定成果

- 小学标准课时：40分钟；BASE目标约25–30分钟；
- 初中标准课时：45分钟；BASE目标约30–35分钟。

剩余标准课时用于试玩、判断、修改、反馈和收口。

额外50/60/90分钟只用于 Challenge / Open Creation，不得成为完成 BASE 的必要条件。

> **40分钟能完整交付，60分钟不水，90分钟仍然有创造空间。**

### 2.3 不是传统编程课

- 不以 Scratch / Python / C++ / HTML/JS 语法为主线；
- 不要求学生先学编程；
- 不要求老师成为程序员；
- 不把课堂时间浪费在环境配置、语法和复杂 Debug。

### 2.4 AI 原生创造

> **想法 → 自然语言 → AI 第一版 → 试玩/判断 → 修改 → 验证 → 用户反馈 → 再迭代。**

复杂技术封装在 AI、平台和母版后。

### 2.5 技术难度 2/10，作品观感 8/10

作品视觉/交互复杂度可以高，但学生/教师技术负担必须低。

### 2.6 作品是明线，能力是暗线

暗线包括：表达需求、任务拆解、判断、验证、迭代、用户视角、事实核查、审美、合作和负责任使用 AI。

### 2.7 AI 说完成不等于完成

必须真实运行、试玩、触发条件、重新验证。

禁止把“复制 Prompt → AI 完成”当成课程能力。

## 3. 当前工具与母版 Known-Good

### M1 游戏母版

微信小程序教育平台 T1：`FULL STRONG PASS`。

已真实验证：分钟级生成、自然语言改主题/规则/动画、AI自修真实故障、二维码发布、家长免登录试玩。

正式资产：`mother-templates/M1-game/README.md`

### M2 学习平台

微信小程序教育平台 T2：`STRONG PASS`。

已真实验证：约2分钟生成完整学习/闯关平台，复杂学习规则和游戏化修改约1–2分钟。

正式资产：`mother-templates/M2-learning/README.md`

因此：

> **不要重新泛搜秒哒/扣子/WorkBuddy，也不要继续重复证明微信平台能不能生成应用。**

## 4. 当前待验证母版

只剩：

- M3：互动故事 / 分支世界；
- M4：兴趣馆 / 知识产品；
- M5：工作台 / 记录 / 校园工具。

每个只需跑：

> **首版 + 两次修改 + 一次 Challenge**

不手写代码，不人工 Debug；出错先让 AI 自修。

入口：
- `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
- `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`

## 5. 当前课程实施事实

正式事实源：

`docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`

### 小学高年级

当前 **11 / 16 节逐课 V0.1**：

- Ready：L1、L2、L7、L8、L15、L16；
- Conditional：L6、L11、L12、L13、L14；
- Blocked：L3/L4→M3，L5→M4，L9/L10→M5。

入口：`courses/primary-upper/lessons/README.md`

### 初中

当前 **14 / 16 节逐课 V0.1**：

- Ready：L1–L4、L7–L9、L11、L14–L16；
- Conditional：L10、L12、L13；
- Blocked：L5/L6→M5。

入口：`courses/middle-school/lessons/README.md`

Conditional 表示当前 M1/M2/通用路径可走，但未验证产品类型不得宣称 Known-Good。

## 6. 当前课程版本

- Wow Demo：`courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`
- 小学16课时：`courses/primary-upper/SEMESTER_16_LESSONS_V0.2.md`
- 初中16课时：`courses/middle-school/SEMESTER_16_LESSONS_V0.2.md`

旧 V0.1 只保留历史参考。

## 7. 教师交付标准

教师核心角色：

> **创意导演 + 节奏控制者 + 支架诊断者 + 成果守门员。**

统一节奏：

> **先看成品 → 快速第一版 → BASE DEADLINE → 能力修改 → Challenge → 稳定收口。**

统一救援：

> **不帮 → 追问 → 给选项 → 给句式 → FALLBACK → 最后才局部代操作。**

多人同类问题优先全班统一恢复。

教师培训/认证：`courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`

## 8. 学校首发与真实课堂迭代

课程达到可交付标准后直接进入学校，不再人为增加小样本 Gate。

学校首发：`courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`

真实课堂记录：`courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`

真实课堂优先记录：
- 展示级完成率；
- FALLBACK人数；
- BASE实际时间；
- 教师长时间个别救援；
- 共性卡点；
- Challenge；
- 学校/家长最喜欢的成果。

单个班级不直接定义课程规律；多教师、多班级重复问题优先进入版本迭代。

## 9. 研发方法

> **逆向成熟课程与真实课堂 → 课程 V0.x → 母版产品化 → 教师/学生材料 → 内部完整走课 → 直接学校授课 → 真实课堂持续迭代。**

`1老师+5学生` 只保留 OPTIONAL USABILITY SMOKE TEST，不是强制 Gate。

## 10. 新增文件规则

- 总体研究/政策/共用机制：`docs/`；
- 核心母版：`mother-templates/`；
- 逐课教案/学生材料/展示材料：对应 `courses/`；
- 跨课程课堂卡、教师培训、学校交付：`courses/shared/`；
- 外部事实保留 URL、核实日期和证据类型；
- 真实账号/真实课堂结果与公开案例严格区分。

## 11. 课程淘汰测试

出现以下任一情况，默认重新设计：

- 基础学生即使用模板仍难在 BASE DEADLINE 前拿到展示级成品；
- 只有拉到60分钟才有完整作品；
- 快学生完成后只能等待；
- 保底作品明显像“低配版”；
- 多人掉队只能逐个技术救援；
- 老师/学生必须大量写代码；
- 大量时间消耗在安装、配置、复杂 Debug；
- 作品只是“一键生成”没有学生真实选择；
- AI生成后不试玩、不验证；
- 家长/学校看不到明显成果；
- 平台一变化整门课就失效。

## 12. 当前下一执行（必须以此为准）

当前阶段：

> **CURRICULUM PRODUCTIZATION → M3/M4/M5 MINIMAL VALIDATION → SCHOOL DELIVERY**

1. 不再重复 M1/M2；
2. 对已写逐课 V0.1 做跨课重复、时间、难度和展示审核；
3. 完善 M1/M2 教师演示版、学生卡和展示样例；
4. 有空时按 Run Cards 各跑一次 M3/M4/M5；
5. M3/M4/M5 通过后立即产品化并补齐被阻塞课次；
6. 做小学/初中内部完整走课；
7. 教师完成当前课程线培训/认证；
8. 达到 School Launch Package Gate 后直接进入合作学校；
9. 用真实课堂数据版本化迭代；
10. 不新增无必要的前置实验门槛。

## 13. 商业与渠道约束

不采用“一次性卖教案”。当前方向：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

代理商获得当前授权执行层，不默认获得完整研发母版、失败库、内部 Prompt 迭代历史和下一版本计划。

壁垒沉淀在：母版、展示级兜底、Challenge Pool、教师认证、故障恢复、真实课堂数据、学生作品/学校成果和持续更新。

更新时间：2026-09-01
