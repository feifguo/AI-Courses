# 课程实施状态 — 2026-09-01

状态：CURRENT IMPLEMENTATION FACT

本文件区分三种状态：

- **LESSON V0.1 DONE / READY**：完整逐课教案已写入仓库，可进入内部走课；
- **CONDITIONAL V0.1 DONE**：逐课脚本已写，可用已验证 M1/M2 或通用机制走课，但完整产品菜单仍受 M3–M5 影响；
- **BLOCKED BY MOTHER VALIDATION**：应先完成对应母版真实账号验证，不提前假装可交付。

## 小学高年级

### LESSON V0.1 DONE / READY

- L1 第一款游戏；
- L2 游戏规则升级；
- L7 学习 App；
- L8 学习反馈/规则升级；
- L15 产品测试与发布；
- L16 AI Creator 嘉年华。

### CONDITIONAL V0.1 DONE

- L6 知识闯关：当前 M2 路径可走，完整兴趣馆组合待 M4；
- L11 用户试玩与改版：通用/M1/M2 路径可走；
- L12 可信内容：M2 路径可走，完整知识产品待 M4；
- L13 最终项目 V1：当前正式支持 M1/M2，完整项目菜单待 M3–M5；
- L14 个性化与升级：通用/M1/M2 路径可走。

入口：`courses/primary-upper/lessons/README.md`

### BLOCKED BY MOTHER VALIDATION

- L3/L4 → M3；
- L5 → M4；
- L9/L10 → M5。

因此小学当前已有 **11 / 16 节**逐课 V0.1，其中6节 Ready、5节 Conditional。

## 初中

### LESSON V0.1 DONE / READY

- L1 第一个数字产品；
- L2 想法→产品要求；
- L3 规则系统；
- L4 版本与回退；
- L7 用户体验；
- L8 用户测试；
- L9 AI评审；
- L11 AI反方；
- L14 功能取舍与V2；
- L15 发布前验收；
- L16 Product Demo Day。

### CONDITIONAL V0.1 DONE

- L10 事实核查：当前 M2 路径可走，完整知识产品待 M4；
- L12 真实问题产品 V1：M1/M2 路径可走，工具类待 M5；
- L13 最终产品定义：当前支持 M1/M2，完整菜单待 M3–M5。

入口：`courses/middle-school/lessons/README.md`

### BLOCKED BY MOTHER VALIDATION

- L5/L6 → M5。

因此初中当前已有 **14 / 16 节**逐课 V0.1，其中11节 Ready、3节 Conditional。

## 共用可交付资产

已经形成：

- `mother-templates/M1-game/`；
- `mother-templates/M2-learning/`；
- `courses/shared/CLASSROOM_CARDS_V0.1.md`；
- `courses/shared/TEACHER_TRAINING_AND_CERTIFICATION_V0.1.md`；
- `courses/shared/REAL_CLASSROOM_ITERATION_FORM_V0.1.md`；
- `courses/shared/SCHOOL_LAUNCH_PACKAGE_V0.1.md`；
- `docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`；
- `docs/CHALLENGE_POOL_SYSTEM_V1.md`。

这些资产用于把“会设计课程”升级为“普通老师能够稳定交付”。

## 母版状态

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

## 当前研发原则

1. 不因 M3–M5 未验证而停止已知部分产品化；
2. 不把依赖未验证母版的课写成正式 Known-Good；
3. Conditional 课可以用当前 M1/M2/通用机制内部走课，并在新母版通过后扩菜单；
4. 母版一旦通过，直接按 `MOTHER_TEMPLATE_PRODUCTIZATION_SPEC_V0.1.md` 产品化并解锁对应课次；
5. 所有正式课仍遵守标准课时：小学25–30分钟锁 BASE，初中30–35分钟锁 BASE；
6. 所有课第一优先保持展示级成功率与学校/家长第一眼效果；
7. 下一真正技术 Gate 只剩 M3/M4/M5 三个最小真实账号验证，不再泛搜其他平台。
