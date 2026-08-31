# AI-Courses

面向中小学生的 AI 原生创造课程研究、产品设计与课程交付仓库。

## 核心定位

> **从“问 AI”走向“用 AI 创造”。**

课程不是传统编程课的简化版，也不是 AI 工具说明课。

核心循环：

> **想法 → 自然语言 → AI 第一版 → 试玩/判断 → 修改 → 验证 → 用户反馈 → 再迭代。**

**作品是明线，AI 使用能力是暗线。**

## 产品硬优先级

> **先保证绝大多数学生都有第一眼很厉害、可试玩、可分享、可展示的成品，再在这个成果之上拉开能力成长和原创深度。**

因此统一采用：

- DISPLAY-SAFE BASE；
- FALLBACK；
- GUIDED CREATOR；
- CHALLENGE POOL；
- OPEN CREATION。

低能力学生有展示级兜底，高能力学生完成 BASE 后立即继续，不等待全班。

核心政策：
- `docs/OUTCOME_FIRST_AND_SCAFFOLDING_POLICY.md`
- `docs/STANDARD_PERIOD_AND_EXTENSION_POLICY.md`
- `docs/CHALLENGE_POOL_SYSTEM_V1.md`

## 标准课时

- 小学：40分钟，BASE目标约25–30分钟；
- 初中：45分钟，BASE目标约30–35分钟。

剩余标准课时用于试玩、判断、修改、反馈和收口；额外60/90分钟只用于 Challenge / Open Creation。

> **40分钟能完整交付，60分钟不水，90分钟仍然有创造空间。**

## 当前主课程版本

跨课审核后，当前结构已升级为 V0.3：

- Wow Demo：`courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`
- 小学16课时：`courses/primary-upper/SEMESTER_16_LESSONS_V0.3.md`
- 初中16课时：`courses/middle-school/SEMESTER_16_LESSONS_V0.3.md`

V0.1/V0.2 保留历史参考，不再作为总课表事实源。

V0.3 新增核心原则：

> **方法可以重复，体验不能重复；每两课一个明显 Showcase Pair，每四课至少一次作品类型/能力跃迁。**

跨课审核：`docs/CROSS_LESSON_COHERENCE_AUDIT_V0.1.md`

## 微信小程序教育平台 Known-Good

### M1 游戏母版 — FULL STRONG PASS

真实 T1 已验证：分钟级生成、主题/规则/动画修改、AI自修故障、二维码发布、家长免登录试玩。

正式资产：`mother-templates/M1-game/README.md`

### M2 学习平台 — STRONG PASS

真实 T2 已验证：约2分钟生成完整学习/闯关平台，后续复杂规则修改约1–2分钟。

正式资产：`mother-templates/M2-learning/README.md`

因此不再泛搜秒哒/扣子/WorkBuddy，也不重复证明微信平台能不能生成应用。

## 当前逐课实施状态

正式事实源：`docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`

### 小学高年级

当前已有 **11/16 节逐课 V0.1**：

- Ready：L1、L2、L7、L8、L15、L16；
- Conditional/Backup：L6、L11、L12、L13、L14；
- 等 M3：L3/L4；
- 等 M4：L5，以及 L6 正式主版；
- 等 M5：L9/L10。

入口：`courses/primary-upper/lessons/README.md`

### 初中

当前已有 **14/16 节逐课 V0.1/V0.2**：

- Ready：L1–L4、L7–L9、L11、L14–L16；
- Conditional：L10、L12、L13；
- 等 M5：L5/L6。

入口：`courses/middle-school/lessons/README.md`

## V0.3 关键节奏修正

### 小学

- L5/L6 正式应成为“兴趣馆 → 可玩兴趣馆”，不默认用 M2 独立闯关后紧接 M2 学习 App；
- L12 可信内容必须有肉眼可见的“已核查/来源/纠错”产品升级；
- L13–L16 固定为 V1 → V2 → Release QA → 嘉年华。

### 初中

- L1/L2 为第一产品 Pair；
- L3/L4 改为新的 **Rule Lab Pair**，避免四周连续修改同一个作品；
- L7 是“自己检查UX”，L8 是“真人用户测试”；
- L9 是“AI评质量”，L11 是“AI质疑产品假设”；
- L12 改为 **Real Problem Sprint 训练赛**，L13 才正式启动 Final Product。

## 当前母版待验证

只剩三个最小真实账号验证：

- M3：互动故事 / 分支世界；
- M4：兴趣馆 / 知识产品；
- M5：工作台 / 记录 / 校园工具。

每个只需：

> **首版 + 两次修改 + 一次 Challenge。**

入口：
- `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
- `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`

## 已形成的教师/学校交付资产

- `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`
- `courses/shared/CLASSROOM_CARDS_V0.1.md`
- `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`
- `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`
- `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`

教师统一节奏：

> **先看成品 → 快速第一版 → BASE DEADLINE → 能力修改 → Challenge → 稳定收口。**

教师救援：

> **不帮 → 追问 → 给选项 → 给句式 → FALLBACK → 最后才局部代操作。**

## 当前研发/上线方法

> **逆向真实课堂 → 课程设计 → 母版产品化 → 教师/学生材料 → 内部走课 → 达到可交付标准后直接进学校 → 用真实课堂持续迭代。**

不再把 `1老师+5学生` 当作强制研发 Gate。

## 当前下一执行

1. 对当前已写课次做内部走课与时间/重复/教师负担检查；
2. 不再重复 M1/M2；
3. 有空时各跑一次 M3/M4/M5；
4. 通过后立即产品化并补齐被阻塞课次；
5. 完善教师演示版、学生卡、作品展示样例；
6. 教师完成当前课程线培训/认证；
7. 达到 `SCHOOL_LAUNCH_PACKAGE_V0.1.md` Gate 后直接进入合作学校；
8. 用真实课堂的完成率、FALLBACK、救援负担、Challenge 和学校/家长反馈持续迭代。

## 商业交付与壁垒

不采用“一次性卖教案”。方向：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

壁垒沉淀在稳定母版、展示级兜底、Challenge Pool、教师认证、故障恢复、真实课堂数据、学生作品/学校成果和持续更新，而不是绑定某一个外部 AI 工具。

更新时间：2026-09-01
