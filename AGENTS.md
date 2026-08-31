# AGENTS.md

本文件是 AI-Courses 仓库工作入口。任何新会话、研究 Agent、课程设计或开发任务开始前先读取。

更新时间：2026-09-01

## 1. 事实源顺序

1. 当前 GitHub `main`；
2. `README.md`；
3. `docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`；
4. `docs/INTERNAL_WALKTHROUGH_AUDIT_V0.1.md`；
5. `docs/CROSS_LESSON_COHERENCE_AUDIT_V0.1.md`；
6. `docs/OUTCOME_FIRST_AND_SCAFFOLDING_POLICY.md`；
7. `docs/STANDARD_PERIOD_AND_EXTENSION_POLICY.md`；
8. `docs/CHALLENGE_POOL_SYSTEM_V1.md`；
9. `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`；
10. `courses/shared/M1_M2_INTERNAL_WALKTHROUGH_PACK_V0.1.md`；
11. `courses/shared/CLASSROOM_CARDS_V0.1.md`；
12. `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`；
13. `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`；
14. `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`；
15. `mother-templates/README.md` 与各正式母版；
16. `mother-templates/M1-game/RULE_LAB_PRESET_COMBINATIONS_V0.1.md`；
17. `docs/MOTHER_TEMPLATE_PRODUCTIZATION_SPEC_V0.1.md`；
18. `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`；
19. `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`；
20. `docs/CURRICULUM_RND_AND_SCHOOL_LAUNCH_STRATEGY.md`；
21. `docs/CURRICULUM_DESIGN_EVIDENCE_SYNTHESIS_V1.md`；
22. `docs/CURRICULUM_REVERSE_ENGINEERING_CASE_MATRIX_V1.md`；
23. `docs/DECISIONS.md`；
24. 微信小程序教育平台 T1/T2 真实账号结果；
25. 各 `courses/<course>/` 最新产物。

聊天记录只能补背景，不能覆盖仓库事实。

---

## 2. 产品第一优先级

> **先保证绝大多数学生都有第一眼很厉害、可试玩、可分享、可展示的成品，再在这个成果之上拉开能力成长和原创深度。**

基础学生不能拿明显低配版，必须达到 `DISPLAY-SAFE BASELINE`。

允许：
- 稳定母版；
- 半成品；
- 主题/规则/功能菜单；
- 一键恢复；
- 全班统一修复；
- 必要的教师局部代操作。

兜底优先级：

> **课程系统兜底 > 模板兜底 > 全班统一救援 > 小组救援 > 个别教师代操作。**

如果多人掉队只能靠老师逐个长时间技术救火，说明课程还没有产品化完成。

---

## 3. 标准课时与时间预算

- 小学标准课时：40分钟；BASE目标约25–30分钟；
- 初中标准课时：45分钟；BASE目标约30–35分钟。

剩余标准课时用于：
- 试玩；
- 判断；
- 修复；
- 同伴/用户反馈；
- 稳定收口。

额外60/90分钟只用于 Challenge / Open Creation，不得成为 BASE 完成条件。

> **40分钟能完整交付，60分钟不水，90分钟仍然有创造空间。**

### BASE Complexity Budget

2026-09-01 内部走课审核确认：

> **标准 BASE 原则上只承担 1 个主要复杂修改 + 1 个低风险可见增强。**

主要复杂修改包括：多条件、多状态、跨页面同步、本地数据、多阶段反馈、复杂计分/升级、结构性改动。

低风险增强包括：动画、徽章、状态变色、文案、进度提示、单一视觉反馈。

第二个主要复杂修改默认进入 Guided / Challenge / 延长课时。

例外：Rule Lab 这类“规则联动本身就是唯一教学目标”的课，但必须使用课程方预设组合。

---

## 4. 课程不是传统编程课

禁止把主线重新变成：
- Scratch / Python / C++ / HTML/JS 语法；
- 大量手写代码；
- 老师逐行 Debug；
- 环境配置课；
- 为了“高级”提高技术负担。

目标：

> **技术难度 2/10，作品观感 8/10。**

核心循环：

> **想法 → 自然语言 → AI第一版 → 试玩/判断 → 修改 → 验证 → 用户反馈 → 再迭代。**

作品是明线，AI使用能力是暗线。

---

## 5. 认知型课硬规则

需求表达、AI评审、事实核查、AI反方、用户测试等课程：

> **单次原则讲解尽量3–5分钟；连续10分钟没有学生操作真实作品，视为设计预警。**

优先：

> 看一个反例 → 马上在自己的作品上做 → 结果以后再总结。

同时必须保留可见 Before/After：
- 前后截图；
- 来源卡；
- 用户反馈+修复；
- 删除/合并前后；
- V1/V2；
- 规则触发画面。

不能只留下隐形“我学会了判断”。

---

## 6. 当前 Known-Good

### M1 游戏

T1：`FULL STRONG PASS`

已真实验证：
- 分钟级生成；
- 自然语言改主题/规则/动画；
- AI自修真实故障；
- 二维码发布；
- 家长免登录试玩。

资产：`mother-templates/M1-game/README.md`

### M2 学习平台

T2：`STRONG PASS`

已真实验证：
- 约2分钟完整学习/闯关平台；
- 1–2分钟复杂学习规则修改；
- 游戏化与自定义内容。

资产：`mother-templates/M2-learning/README.md`

> **不要重新泛搜秒哒/扣子/WorkBuddy，也不要重复证明微信平台能不能生成应用。**

---

## 7. Rule Lab 当前安全路径

入口：`mother-templates/M1-game/RULE_LAB_PRESET_COMBINATIONS_V0.1.md`

已有 T1 真实证据：

- **RL-01 连击系统**：成功→连击增加；三连击奖励；失败清零；
- **RL-02 倒计时系统**：60秒；超时失败；提前完成停止；最后10秒警告。

候选、未成为 Known-Good：
- RL-03 三条生命；
- RL-04 能量升级；
- RL-05 收集解锁。

候选在真实内部走课前只进入 Challenge，不作为弱学生 BASE。

---

## 8. 当前待验证母版

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

---

## 9. 当前课程主版本

### Wow Demo

`courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`

### 小学高年级

`courses/primary-upper/SEMESTER_16_LESSONS_V0.3.md`

Pair：
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

Pair：
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

旧 V0.1/V0.2 总课表只做历史参考。

---

## 10. 当前逐课实施事实

事实源：`docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`

### 小学

11/16节已有逐课脚本：
- Ready：L1、L2、L7、L8、L15、L16；
- Conditional/Backup：L6、L11、L12、L13、L14；
- Blocked：L3/L4→M3，L5/L6主版→M4，L9/L10→M5。

审核后重点：
- L2 内容V0.2：1复杂规则 + 1低风险反馈；
- L8 内容V0.2：1聪明反馈 + 1低风险奖励；
- L12 内容V0.2：BASE核查2条。

### 初中

14/16节已有逐课脚本：
- Ready：L1–L4、L7–L9、L11、L14–L16；
- Conditional：L10、L12、L13；
- Blocked：L5/L6→M5。

审核后重点：
- L3 内容V0.3：Known-Good Rule Lab预设；
- L9 内容V0.2：action-first，只改1条AI建议；
- L10 内容V0.2：BASE核查2条；
- L11 内容V0.2：action-first + Before/After；
- L14 内容V0.2：V2指标为累计状态，本节只加1个主要复杂升级。

---

## 11. 跨课节奏硬规则

> **方法可以重复，体验不能重复。**

- 每课至少一个可截图/试玩变化；
- 每2课一个 Showcase Milestone；
- 每4课至少一次明显作品类型或能力反转；
- “生成→试玩→判断→修改→验证”允许重复练；
- 不允许只是换题目重复同一种表面产品。

---

## 12. 教师交付标准

教师角色：

> **创意导演 + 节奏控制者 + 支架诊断者 + 成果守门员。**

统一节奏：

> **先看成品 → 快速第一版 → BASE DEADLINE → 能力修改 → Challenge → 稳定收口。**

救援顺序：

> **不帮 → 追问 → 给选项 → 给句式 → FALLBACK → 最后才局部代操作。**

多人同类问题优先全班统一恢复。

内部走课包：`courses/shared/M1_M2_INTERNAL_WALKTHROUGH_PACK_V0.1.md`

教师培训：`courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`

课堂卡：`courses/shared/CLASSROOM_CARDS_V0.1.md`

---

## 13. 学校首发与迭代

学校首发：`courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`

课堂记录：`courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`

课程达到可交付标准后直接进学校，不再人为增加小样本 Gate。

真实课堂优先记录：
- 完成率；
- FALLBACK；
- BASE真实时间；
- 教师长时间个别救援；
- 共性卡点；
- Challenge；
- 学校/家长最喜欢的成果。

---

## 14. 淘汰测试

出现任一情况默认重新设计：

- BASE接近标准课时才完成；
- 只有60分钟才有完整作品；
- BASE同时要求多个尚未稳定的复杂修改；
- 快学生只能等待；
- 保底作品像明显低配版；
- 多人掉队只能逐个技术救援；
- 老师/学生必须大量写代码；
- 大量时间耗在安装、配置、复杂 Debug；
- 一键生成没有学生真实选择；
- AI生成后不试玩、不验证；
- 认知课连续10分钟没有真实作品动作；
- 认知课没有肉眼可见 Before/After；
- 连续多课表面作品高度重复；
- 家长/学校10秒内看不懂成果。

---

## 15. 当前下一执行（必须以此为准）

当前阶段：

> **P0 INTERNAL AUDIT COMPLETE → M1/M2 REAL WALKTHROUGH → M3/M4/M5 MINIMAL VALIDATION → SCHOOL DELIVERY**

1. **不要再做新的泛研究或平台横评。**
2. P0 内部走课审核修正已完成，不重新打开已关闭问题。
3. 使用 `courses/shared/M1_M2_INTERNAL_WALKTHROUGH_PACK_V0.1.md` 做教师真实内部走课，记录：第一版时间、BASE时间、Fallback、AI修复、教师负担。
4. RL-03/04/05 若要进入基础路径，先分别做一次真实账号验证；否则保持 Challenge 候选。
5. 有空时按 `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md` 各跑一次 M3/M4/M5。
6. M3/M4/M5 通过后立即产品化并补齐被阻塞课次。
7. 完成小学/初中整学期内部走课。
8. 教师完成课程线培训/认证。
9. 达到 School Launch Package Gate 后直接进入合作学校。
10. 用真实课堂数据版本化迭代。
11. 不新增无必要的前置实验门槛。

---

## 16. 商业与渠道约束

不采用“一次性卖教案”。方向：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

代理商获得当前授权执行层，不默认获得完整研发母版、失败库、内部 Prompt 迭代历史和下一版本计划。

壁垒沉淀在：
- 稳定母版；
- 展示级兜底；
- Challenge Pool；
- 教师认证；
- 故障恢复；
- 真实课堂数据；
- 学生作品/学校成果；
- 持续更新。
