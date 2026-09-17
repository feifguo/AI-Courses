# AI-Courses

面向中小学生的 AI 原生创造课程研究、产品设计与课程交付仓库。

更新时间：2026-09-17

## 新会话 / 新工具从这里开始

如果是 ChatGPT、WorkBuddy、Hermes、Codex 或新的人工协作者接手：

1. 先读 `HANDOFF.md`；
2. 再读 `AGENTS.md`；
3. 再读 `docs/PROJECT_EVOLUTION_AND_RATIONALE_2026-09-17.md`；
4. 然后按任务进入课程、平台、Demo 或交付专题文件。

> **不要依赖某一个聊天工具的历史记忆。Repo 是项目事实和决策脉络的长期载体。**

---

## 核心定位

> **从“问 AI”走向“用 AI 创造”。**

课程不是传统编程课的简化版，也不是 AI 工具说明课。

核心循环：

> **想法 → 自然语言 → AI 第一版 → 试玩/判断 → 修改 → 验证 → 用户反馈 → 再迭代。**

> **作品是明线，AI 使用能力是暗线。**

项目从早期“AI使用能力/学习助手/暑期营”一路演化到当前 AI 原生创造课的完整原因、被否定方向和关键转折，见：

`docs/PROJECT_EVOLUTION_AND_RATIONALE_2026-09-17.md`

---

## 产品硬优先级

> **先保证绝大多数学生都有第一眼很厉害、可试玩、可分享、可展示的成品，再在这个成果之上拉开能力成长和原创深度。**

采用：

- DISPLAY-SAFE BASE；
- FALLBACK；
- GUIDED CREATOR；
- CHALLENGE POOL；
- OPEN CREATION。

低能力学生有展示级兜底，高能力学生完成 BASE 后继续向上，不等待全班。

核心政策：

- `docs/OUTCOME_FIRST_AND_SCAFFOLDING_POLICY.md`
- `docs/STANDARD_PERIOD_AND_EXTENSION_POLICY.md`
- `docs/CHALLENGE_POOL_SYSTEM_V1.md`
- `docs/INTERNAL_WALKTHROUGH_AUDIT_V0.1.md`

---

## 标准课时与复杂度预算

- 小学：40分钟，BASE目标约25–30分钟；
- 初中：45分钟，BASE目标约30–35分钟。

> **40分钟能完整交付，60分钟不水，90分钟仍然有创造空间。**

内部走课审核确认：

> **BASE Complexity Budget = 1个主要复杂修改 + 1个低风险可见增强。**

原因：AI生成很快，但真实课堂的不确定时间主要发生在：

> **试玩 → 触发 → 发现冲突 → AI修复 → 再验证。**

---

## 当前主课程

### 小学高年级 V0.3

`courses/primary-upper/SEMESTER_16_LESSONS_V0.3.md`

主线：

> 游戏 → 互动世界 → 兴趣馆 → 学习 App → 校园工具 → 用户/可信 → Final V1/V2 → 发布/嘉年华

### 初中 V0.3

`courses/middle-school/SEMESTER_16_LESSONS_V0.3.md`

主线：

> 第一数字产品 → Rule Lab → 真正工具 → UX/真人测试 → AI评审/事实核查 → AI反方/真实问题Sprint → Final V1/V2 → Release QA/Demo Day

逐课 Ready / Conditional / Blocked 状态：

`docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`

跨课审核：

- `docs/CROSS_LESSON_COHERENCE_AUDIT_V0.1.md`
- `docs/INTERNAL_WALKTHROUGH_AUDIT_V0.1.md`

---

## 微信小程序教育平台 Known-Good

### M1 游戏母版 — FULL STRONG PASS

真实 T1 已验证：

- 分钟级生成；
- 主题/规则/动画自然语言修改；
- AI自修真实故障；
- 二维码发布；
- 家长免登录试玩。

资产：`mother-templates/M1-game/README.md`

### M2 学习平台 — STRONG PASS

真实 T2 已验证：

- 多功能学习/闯关平台；
- 进度、积分、反馈等状态；
- 复杂学习规则修改；
- 游戏化；
- 自定义内容。

资产：`mother-templates/M2-learning/README.md`

注意：T1/T2 是成人用户真实账号验证，不得写成真实五年级学生已经完成。

平台研究/真实结果：

- `docs/SCHOOL_NATIVE_PLATFORM_SCAN_2026-08-31.md`
- `docs/CLASSROOM_PLATFORM_ECONOMICS_AND_RISKS_2026-08-31.md`
- `docs/WECHAT_MINIPROGRAM_EDU_T1_REAL_ACCOUNT_RESULT_2026-08-31.md`
- `docs/WECHAT_MINIPROGRAM_EDU_T2_REAL_ACCOUNT_RESULT_2026-08-31.md`

当前不再泛搜秒哒/扣子/WorkBuddy来重复证明“AI能不能生成应用”。

仍未完全确认：微信教育平台的学校/机构认证、创建班级权限、非学校主体认证路径、多校代理交付权限。

---

## 当前待验证母版

只剩：

- M3：互动故事 / 分支世界；
- M4：兴趣馆 / 知识产品；
- M5：工作台 / 记录 / 校园工具。

每个只需：

> **首版 + 两次修改 + 一次 Challenge。**

入口：

- `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
- `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`

---

## Demo 现在分成两个不同产品

### 1. 现场学生 Wow Demo

`courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`

这是学生真的上、真的做、真的试玩的一堂标准课时 Demo。

当前稳定主任务优先 M1 游戏；M2及后续学习/工具产品用于展示课程上限。

### 2. 校长采购销售 Demo 视频

`courses/demo/PRINCIPAL_SALES_DEMO_VIDEO_V0.1.md`

它**不是课堂录像**。

本质：

> **2分30秒—3分30秒的动态PPT式讲解 + 少量真实成果录屏。**

原则：

> **录制结果，讲解过程，抽象方法，保护配方。**

视频主视觉更多使用学习平台、知识产品、真实工具等“像真正软件”的成果，而不是只展示小游戏。

第一版专业表达只重点保留：

- 需求定义；
- 系统逻辑；
- 测试与调试；
- AI能力边界/人的判断。

权威背书只短暂使用世界经济论坛2025未来技能与联合国教科文组织学生AI能力框架，不把短视频做成理论白皮书。

Demo 产品线说明：`courses/demo/README.md`

---

## 教师/学校交付资产

- `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`
- `courses/shared/M1_M2_INTERNAL_WALKTHROUGH_PACK_V0.1.md`
- `courses/shared/CLASSROOM_CARDS_V0.1.md`
- `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`
- `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`
- `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`

教师统一节奏：

> **先看成品 → 快速第一版 → BASE DEADLINE → 能力修改 → Challenge → 稳定收口。**

救援：

> **不帮 → 追问 → 给选项 → 给句式 → FALLBACK → 最后才局部代操作。**

---

## 商业交付

当前链路：

> **课程开发方 → 代理商/区域伙伴 → 学校 → 代理商受训教师到校上课 → 学生。**

不采用“一次性卖教案”。方向：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

因此校长销售材料不需要重点证明学校自己的老师能否马上授课；这一点属于代理商后台教师培训与认证能力。

---

## 当前研发/上线方法

> **逆向真实课堂 → 课程设计 → 母版产品化 → 逐课教案 → 教师/学生材料 → 内部走课 → 达到可交付标准后直接进学校 → 用真实课堂持续迭代。**

不再把 `1老师+5学生` 当作强制研发 Gate。

---

## 当前执行基线

工程/课程阶段仍为：

> **P0 INTERNAL AUDIT COMPLETE → M1/M2 REAL WALKTHROUGH → M3/M4/M5 MINIMAL VALIDATION → SCHOOL DELIVERY**

但用户已说明下一会话会带来一些新的情况变化。

因此下一会话应：

> **先恢复 Repo → 听取变化 → 判断受影响层 → 在原方案上定向修改。**

不要在不知道新变化的情况下机械执行旧 TODO，也不要从零重做已确认设计。
