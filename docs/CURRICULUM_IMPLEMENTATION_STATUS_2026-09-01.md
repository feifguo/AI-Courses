# 课程实施状态 — 2026-09-01

状态：CURRENT IMPLEMENTATION FACT

本文件区分三种状态：

- **LESSON DONE / READY**：完整逐课教案已写入仓库，可进入内部走课；
- **CONDITIONAL DONE**：逐课脚本已写，可用已验证 M1/M2 或通用机制走课，但完整产品菜单仍受 M3–M5 影响；
- **BLOCKED BY MOTHER VALIDATION**：应先完成对应母版真实账号验证，不提前假装可交付。

---

## 1. 当前课程主版本

- 小学高年级：`courses/primary-upper/SEMESTER_16_LESSONS_V0.3.md`
- 初中：`courses/middle-school/SEMESTER_16_LESSONS_V0.3.md`
- Wow Demo：`courses/demo/WECHAT_WOW_DEMO_V0.2_STANDARD_PERIOD.md`

V0.3 已解决主要跨课重复：
- 两课一个成果 Pair；
- 每四课至少一次明显作品/能力跃迁；
- 初中 L3/L4 改为独立 Rule Lab Pair；
- 初中 L12 改为 Real Problem Sprint，与 L13 Final Launch 分离；
- 小学 L6 的 M2 独立闯关降为 Backup，正式默认等待 M4 与 L5 组成兴趣馆 Pair。

---

## 2. 小学高年级

### LESSON DONE / READY

- L1 第一款游戏；
- L2 游戏规则升级 — **V0.2 complexity-budget revised**；
- L7 学习 App；
- L8 学习反馈/规则升级 — **V0.2 complexity-budget revised**；
- L15 产品测试与发布；
- L16 AI Creator 嘉年华。

### CONDITIONAL DONE

- L6 知识闯关：仅 Backup；正式兴趣馆 Pair 等 M4；
- L11 用户试玩与改版：通用/M1/M2 路径可走；
- L12 可信内容 — **V0.2，BASE核查2条关键事实 + 可见可信模块**；
- L13 最终项目 V1：当前正式支持 M1/M2，完整项目菜单待 M3–M5；
- L14 个性化与升级：通用/M1/M2 路径可走。

入口：`courses/primary-upper/lessons/README.md`

### BLOCKED BY MOTHER VALIDATION

- L3/L4 → M3；
- L5/L6主版 → M4；
- L9/L10 → M5。

因此小学当前已有 **11 / 16 节**逐课脚本，其中6节 Ready、5节 Conditional/Backup。

---

## 3. 初中

### LESSON DONE / READY

- L1 第一个数字产品；
- L2 想法→产品要求；
- L3 Rule Lab — **V0.3，BASE优先RL-01/RL-02 Known-Good预设**；
- L4 版本与回退；
- L7 用户体验；
- L8 用户测试；
- L9 AI评审 — **V0.2 action-first / BASE只改1条建议**；
- L11 AI反方 — **V0.2 action-first / Before-After**；
- L14 功能取舍与V2 — **V0.2，明确累计状态，不要求本节新建多个复杂功能**；
- L15 发布前验收；
- L16 Product Demo Day。

### CONDITIONAL DONE

- L10 事实核查 — **V0.2，BASE核查2条 + 教师来源包 + 可见可信模块**；
- L12 Real Problem Sprint V0.2：M1/M2 路径可走，工具类待 M5；
- L13 最终产品定义：当前支持 M1/M2，完整菜单待 M3–M5。

入口：`courses/middle-school/lessons/README.md`

### BLOCKED BY MOTHER VALIDATION

- L5/L6 → M5。

因此初中当前已有 **14 / 16 节**逐课脚本，其中11节 Ready、3节 Conditional。

---

## 4. 内部走课审核状态

`docs/INTERNAL_WALKTHROUGH_AUDIT_V0.1.md` 已完成 P0 修正。

本轮新增课程硬规则：

> **BASE Complexity Budget = 1个主要复杂修改 + 1个低风险可见增强。**

原因：AI生成快，但真实课堂的不确定耗时主要发生在试玩、触发、冲突、修复和再验证。

认知型课同时新增：

> **单次原则讲解尽量3–5分钟；连续10分钟没有学生操作真实作品视为设计预警。**

以及：

> **事实核查、AI评审、用户测试、AI反方等课必须保留肉眼可见的 Before/After。**

已同步修改：
- `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`；
- 小学 L2 / L8 / L12；
- 初中 L9 / L10 / L11 / L14；
- 初中 L3 Rule Lab。

---

## 5. 共用可交付资产

已经形成：

- `mother-templates/M1-game/`；
- `mother-templates/M2-learning/`；
- `mother-templates/M1-game/RULE_LAB_PRESET_COMBINATIONS_V0.1.md`；
- `courses/shared/M1_M2_INTERNAL_WALKTHROUGH_PACK_V0.1.md`；
- `courses/shared/CLASSROOM_CARDS_V0.1.md`；
- `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`；
- `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`；
- `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`；
- `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`；
- `docs/CHALLENGE_POOL_SYSTEM_V1.md`。

这些资产用于把“会设计课程”升级为“普通老师能够稳定交付”。

---

## 6. Rule Lab 预设状态

### 已有真实 T1 证据

- RL-01 连击系统：连续成功→连击增加；三连击奖励；失败清零；
- RL-02 倒计时系统：60秒倒计时；超时失败；提前完成停止；最后10秒警告。

### 候选 / 未成为 Known-Good

- RL-03 三条生命；
- RL-04 能量升级；
- RL-05 收集解锁。

候选只能先用于内部走课/Challenge，完成真实验证后才能升级为基础路径。

---

## 7. 母版状态

### Known-Good / 已产品化

- M1 游戏母版：真实 T1 FULL STRONG PASS；
- M2 学习平台：真实 T2 STRONG PASS。

### 待真实账号最小验证

- M3 互动故事/分支世界；
- M4 兴趣馆/知识产品；
- M5 工作台/记录/校园工具。

测试入口：
- `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
- `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`

---

## 8. 当前下一执行

1. M1/M2 不再重复做平台能力验证；
2. 用 `M1_M2_INTERNAL_WALKTHROUGH_PACK_V0.1.md` 做教师内部走课，记录真实 BASE 时间、Fallback和教师负担；
3. 有空时按 Run Cards 各跑一次 M3/M4/M5；
4. M3/M4/M5 通过后立即产品化并补齐被阻塞课次；
5. 完成小学/初中整学期内部走课；
6. 教师完成培训/认证；
7. 达到 School Launch Package Gate 后直接进入合作学校；
8. 用真实课堂数据版本化迭代；
9. 不新增无必要的前置实验门槛。

---

## 9. 当前研发原则

1. 不因 M3–M5 未验证而停止已知部分产品化；
2. 不把依赖未验证母版的课写成正式 Known-Good；
3. Conditional 课可以用当前 M1/M2/通用机制内部走课，并在新母版通过后扩菜单；
4. 所有正式课仍遵守标准课时：小学25–30分钟锁 BASE，初中30–35分钟锁 BASE；
5. BASE原则上只承担1个主要复杂修改；
6. 所有课第一优先保持展示级成功率与学校/家长第一眼效果；
7. 下一真正技术 Gate 只剩 M3/M4/M5 三个最小真实账号验证，不再泛搜其他平台。
