# AI-Courses 内部走课审核 V0.1

更新时间：2026-09-01
状态：P0 FIXES COMPLETE / P1 WALKTHROUGH ACTIVE
范围：小学高年级与初中当前已完成逐课教案

## 1. 审核目标

本审核不增加新课型，只检查：

1. **时间盒**：BASE 是否真的能在标准课时前明显完成；
2. **教师讲授量**：认知型课是否会滑成 AI 素养 PPT 课；
3. **跨课重复**：相邻课学生体验是否重复；
4. **展示强度**：教育动作后，家长/学校是否能第一眼看到产品变化。

产品优先级不变：

> **先保证展示级成果与课堂成功率，再在稳定成果上叠加能力训练。**

---

## 2. 核心结论

当前 V0.3 结构方向正确，Pair 节奏、BASE/FALLBACK/Challenge、标准课时和最终展示链均保留。

本轮最重要的新发现：

> **AI生成很快，但课堂真正不确定的时间主要花在试玩、触发、冲突、修复和再次验证。**

因此新增全课程硬规则：

# BASE COMPLEXITY BUDGET

标准课时 DISPLAY-SAFE BASE 原则上只承担：

> **1 个主要复杂修改 + 1 个低风险可见增强。**

主要复杂修改包括：
- 多条件规则；
- 多状态联动；
- 跨页面同步；
- 本地数据持久化；
- 多阶段反馈；
- 复杂计分/升级；
- 可能破坏原流程的结构改动。

低风险可见增强包括：
- 动画；
- 徽章；
- 状态变色；
- 文案；
- 进度提示；
- 单一视觉反馈。

第二个主要复杂修改默认进入 GUIDED / Challenge / 延长课时。

### 例外

初中 L3 Rule Lab 的教学目标本身就是规则联动，因此允许一个完整“多条件规则系统”；但基础学生使用课程方已验证预设，不从空白自由拼两套未知逻辑。

当前预设：
- RL-01 连击系统 — T1 Known-Good；
- RL-02 倒计时系统 — T1 Known-Good；
- RL-03/04/05 — 候选，未验证前只做 Challenge / 内部走课。

---

## 3. 认知型课讲授上限

需求表达、AI评审、事实核查、AI反方、用户测试等课程必须保持 action-first。

硬规则：

> **单次原则讲解尽量3–5分钟；连续10分钟没有学生操作真实作品，视为设计预警。**

优先：

> 看一个反例 → 立即在自己的作品上做 → 结果出来后再总结。

不采用：

> 先讲完整理论 → 填表 → 讨论很久 → 最后才碰作品。

---

## 4. 认知课必须有可见 Before / After

事实核查、AI评审、用户测试、AI反方等课必须留下至少一种肉眼可见证据：

- 修改前/后截图；
- 首页结构变化；
- 来源/已核查卡；
- 删除/合并前后对比；
- 用户反馈卡 + 修复结果；
- V1/V2；
- 规则触发前后画面。

> **教育价值发生在学生脑中，但学校和家长必须能看见它在作品上的痕迹。**

---

# 5. 小学审核结论

## L1 — PASS

快速第一版 + 个性化 + 1条规则/Wow，保留。

## L2 — FIXED

原 BASE：两条复杂规则 + 可见反馈，修复风险偏高。

现 BASE：

> **1条主要玩法规则 + 1个低风险可见反馈。**

第二复杂规则进入 Guided/Challenge。

文件：`courses/primary-upper/lessons/L02_GAME_RULES_V0.1.md`，内容已升 V0.2。

## L6 — BACKUP ONLY

M4 未通过前不作为正式默认 L6，避免与 L7 表面重复。

## L7 — PASS

完整学习产品 + 一条学习规则，保留。

## L8 — FIXED

原 BASE 同时要求多阶段提示、计分、连胜、超级模式、最高连胜，验证链过长。

现 BASE：

> **1条聪明反馈复杂规则 + 1个低风险可见奖励。**

超级模式等进入 Guided/Challenge。

文件：`courses/primary-upper/lessons/L08_LEARNING_RULES_V0.1.md`，内容已升 V0.2。

## L11 — PASS

真人用户测试与 L15 发布验收职责清楚。

## L12 — FIXED

原 BASE 强制核查3条事实。

现 BASE：
- 核查2条关键事实；
- 至少处理1个错误/澄清/来源问题；
- 必须增加明显可信模块；
- 第3条进入 Challenge。

文件：`courses/primary-upper/lessons/L12_TRUSTWORTHY_CONTENT_V0.1.md`，内容已升 V0.2。

## L13/L14 — PASS WITH GLOBAL RULE

最终作品指标是**累计状态**，每节新增加的主要复杂度仍不超过1个。

## L15/L16 — PASS

继续坚持停止扩张、锁稳定版、发布与展示。

---

# 6. 初中审核结论

## L1/L2 — PASS

L2 继续观察四格需求卡真实耗时；若普遍超过5分钟，改选择式卡片。

## L3/L4 — FIXED / GUARDED

V0.3 已切成独立 Rule Lab Pair。

L3 当前基础路径直接使用：
- RL-01 连击系统；
- RL-02 倒计时系统。

其他组合未验证前不能作为基础路径。

文件：
- `courses/middle-school/lessons/L03_RULE_SYSTEM_V0.1.md`，内容已升 V0.3；
- `mother-templates/M1-game/RULE_LAB_PRESET_COMBINATIONS_V0.1.md`。

## L7/L8 — PASS

继续明确：
- L7 = 作者自己看 UX；
- L8 = 真人第一次使用。

L8 体验者优先只走2–3分钟核心流程，不要求探索所有功能。

## L9 — FIXED

原版前置评审/分类/解释偏长。

现标准：
- 3分钟反例；
- AI只给3条最重要建议；
- 学生只强制选1条修改；
- 13分钟左右进入产品动作；
- 必须有 Before/After；
- 至少保留1条未采纳AI建议。

文件：`courses/middle-school/lessons/L09_AI_REVIEWER_V0.1.md`，内容已升 V0.2。

## L10 — FIXED

现 BASE：
- 核查2条；
- 教师预置来源包；
- 至少处理1个问题；
- 可信模块可见；
- 第3条及多来源冲突进入 Challenge。

文件：`courses/middle-school/lessons/L10_FACT_CHECKING_V0.1.md`，内容已升 V0.2。

## L11 — FIXED

现标准：
- AI只给3条关键质疑；
- BASE只处理1条；
- 13分钟左右进入删减/重构；
- 强制 Before/After；
- 第二意见进入 Challenge。

文件：`courses/middle-school/lessons/L11_AI_DEVILS_ADVOCATE_V0.1.md`，内容已升 V0.2。

## L12 — PASS

Real Problem Sprint 已与 L13 Final Launch 分离，保持。

## L13 — PASS

正式最终项目启动。

## L14 — FIXED

“核心流程 + 状态/数据 + Wow + 原创功能”明确为 V2 **累计状态**。

本节标准 BASE：

> **只新增1个最重要复杂升级 + 低风险展示增强 + 1次删减/弱化决策。**

文件：`courses/middle-school/lessons/L14_FEATURE_PRIORITIZATION_V0.1.md`，内容已升 V0.2。

## L15/L16 — PASS

发布前继续禁止疯狂加功能。

---

# 7. 教师负担结论

教师现在统一看两个指标：

## BASE DEADLINE

到了时间，未达展示线全部停止新增，进入 FALLBACK。

## COMPLEXITY COUNT

问：

> **“这个学生现在同时在改几个高风险逻辑？”**

基础路径原则上答案是：

> **1个。**

如果是2–3个，先缩范围。

上述规则已经写入：

`docs/TEACHER_DELIVERY_PLAYBOOK_V0.1.md`

---

# 8. P0 执行状态

- [x] Teacher Delivery Playbook 加入 BASE Complexity Budget；
- [x] 小学 L2 降为1复杂规则 + 1低风险反馈；
- [x] 小学 L8 降为1复杂反馈规则 + 1低风险奖励；
- [x] 小学 L12 BASE核查3→2；
- [x] 初中 L9 压缩前置认知时间并只强制改1条建议；
- [x] 初中 L10 BASE核查3→2并预置来源包；
- [x] 初中 L11 压缩前置讨论并强化 Before/After；
- [x] 初中 L14 明确累计状态；
- [x] 初中 L3 接入 Known-Good Rule Lab 预设。

P0：**COMPLETE**。

---

# 9. P1 当前状态

已完成：
- [x] `courses/shared/M1_M2_INTERNAL_WALKTHROUGH_PACK_V0.1.md`；
- [x] `mother-templates/M1-game/RULE_LAB_PRESET_COMBINATIONS_V0.1.md`；

待真实内部走课：
- [ ] 用 M1/M2 走课包记录 BASE 实际时间；
- [ ] RL-03/04/05 候选组合若要进入 BASE，分别做一次真实验证；
- [ ] 继续记录 Fallback 和教师长时间个别救援触发点。

---

# 10. 一句话结论

> **AI快，不代表课堂应该塞得满；AI省下来的时间，应该留给试玩、判断、修复和创造，而不是继续堆第二、第三个复杂功能。**
