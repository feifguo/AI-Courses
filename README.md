# AI-Courses

面向中小学生的 AI 原生创造课程研究、产品设计与课程产物仓库。

## 当前产品目标

1. **小学高年级 AI 创造课**；
2. **初中 AI 数字创造课**；
3. **AI Wow Demo / 标准课时体验课**。

小学低年级暂不作为第一优先完整学期产品。

## 核心定位

> **从“问 AI”走向“用 AI 创造”。**

课程不是传统编程课的简化版，也不是 AI 工具说明课。

核心循环：

> **想法 → 自然语言 → AI 第一版 → 试玩/判断 → 修改 → 验证 → 用户反馈 → 再迭代。**

**作品是明线，AI 使用能力是暗线。**

## 产品硬优先级

第一优先不是“最强学生能做到多厉害”，而是：

> **先保证绝大多数学生都有第一眼很厉害、可试玩、可分享、可展示的成品，再在这个成果之上拉开能力成长和原创深度。**

因此课程统一采用：

- DISPLAY-SAFE BASE；
- FALLBACK；
- GUIDED CREATOR；
- CHALLENGE POOL；
- OPEN CREATION。

低能力学生依靠稳定母版、半结构化模板、功能菜单和必要教师协助保住成品；高能力学生完成 BASE 后立即继续自由拓展。

核心政策：
- `docs/OUTCOME_FIRST_AND_SCAFFOLDING_POLICY.md`
- `docs/STANDARD_PERIOD_AND_EXTENSION_POLICY.md`
- `docs/CHALLENGE_POOL_SYSTEM_V1.md`

## 标准课时

依据教育部《义务教育课程方案（2022年版）》：

- 小学：**40分钟**；
- 初中：**45分钟**。

本项目要求 BASE 明显提前完成：

### 小学
- 25–30分钟左右：锁展示级 BASE；
- 30–40分钟：试玩、判断、修改、收口；
- 40分钟以后：Challenge / Open Creation。

### 初中
- 30–35分钟左右：锁展示级 BASE；
- 35–45分钟：用户测试、判断、修改、收口；
- 45分钟以后：更复杂产品挑战。

目标：

> **40分钟能完整交付，60分钟不水，90分钟仍然有创造空间。**

## 微信小程序教育平台 Known-Good

### T1 / M1 游戏母版 — FULL STRONG PASS

真实账号已验证：分钟级生成、主题/规则/动画修改、AI自修真实故障、二维码发布、家长免登录试玩。

### T2 / M2 学习平台 — STRONG PASS

真实账号已验证：约2分钟生成完整五年级学习/闯关平台，后续复杂规则修改约1–2分钟完成。

因此当前不再泛搜秒哒/扣子/WorkBuddy，也不重复证明“AI能不能做应用”。

## 当前课程版本

- Wow Demo：`courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`
- 小学16课时：`courses/primary-upper/SEMESTER_16_LESSONS_V0.2.md`
- 初中16课时：`courses/middle-school/SEMESTER_16_LESSONS_V0.2.md`

旧 V0.1 只保留历史参考。

## 当前逐课实施状态

正式事实源：

`docs/CURRICULUM_IMPLEMENTATION_STATUS_2026-09-01.md`

### 小学高年级

当前已有 **11 / 16 节逐课 V0.1**：

- 6节 Ready：L1、L2、L7、L8、L15、L16；
- 5节 Conditional：L6、L11、L12、L13、L14；
- 5节等待母版：L3/L4→M3，L5→M4，L9/L10→M5。

入口：`courses/primary-upper/lessons/README.md`

### 初中

当前已有 **14 / 16 节逐课 V0.1**：

- 11节 Ready：L1–L4、L7–L9、L11、L14–L16；
- 3节 Conditional：L10、L12、L13；
- 2节等待 M5：L5/L6。

入口：`courses/middle-school/lessons/README.md`

Conditional 表示当前 M1/M2/通用教学路径已经可执行，但未验证母版对应的产品菜单不能写成 Known-Good。

## 核心母版库

入口：`mother-templates/README.md`

### 已产品化

- `mother-templates/M1-game/README.md`
- `mother-templates/M2-learning/README.md`

每套母版已定义：

- DISPLAY-SAFE BASE；
- FALLBACK；
- Theme / Feature / Wow Options；
- Recovery；
- Challenge；
- 教师追问；
- Showcase Standard；
- Known Failure / R&D Notes。

### 待最小真实账号验证

- M3：互动故事 / 分支世界；
- M4：兴趣馆 / 知识产品；
- M5：工作台 / 记录 / 校园工具。

只需各跑：

> **首版 + 两次修改 + 一次 Challenge**

入口：
- `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
- `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`

## 已形成的教师/学校交付资产

### 课堂交付
- `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`
- `courses/shared/CLASSROOM_CARDS_V0.1.md`

### 教师培训/认证
- `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`

### 学校首发
- `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`

### 真实课堂持续迭代
- `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`

教师统一节奏：

> **先看成品 → 快速第一版 → BASE DEADLINE → 能力修改 → Challenge → 稳定收口。**

教师救援统一按：

> **不帮 → 追问 → 给选项 → 给句式 → FALLBACK → 最后才局部代操作。**

如果同类问题多人出现，优先全班统一救援，不逐台处理。

## 当前研发方法

> **逆向真实课堂/成熟课程 → 课程 V0.x → 内部完整走课与教师准备 → 达到可交付标准后直接进学校 → 用真实课堂持续迭代。**

不再把 `1老师+5学生` 作为课程研发强制 Gate。

真实学校和多教师、多班级的长期授课才是后续主要数据来源。

## 当前下一执行

1. 已验证课程继续内部走课/完善展示素材；
2. 不再重复验证 M1/M2；
3. 有空时按 Run Cards 各跑一次 M3/M4/M5；
4. M3/M4/M5 通过后立即产品化并补齐被阻塞课次；
5. 对所有已写教案做跨课重复/节奏/难度审核；
6. 完成教师培训材料、作品模板与内部走课；
7. 达到 `SCHOOL_LAUNCH_PACKAGE_V0.1.md` Gate 后直接进入合作学校；
8. 从真实课堂持续积累完成率、FALLBACK、教师救援、Challenge 和学校/家长反馈。

## 商业交付与壁垒

不采用“一次性卖教案”。当前方向：

> **年度/学期授权 + 教师认证 + 班级激活 + 学生作品/学校成果体系 + 持续课程更新。**

核心壁垒沉淀在：

- 稳定母版；
- 展示级兜底；
- Challenge Pool；
- 教师培训和支架；
- 故障恢复；
- 真实课堂迭代数据；
- 学生作品与学校成果体系；
- 持续更新。

更新时间：2026-09-01
