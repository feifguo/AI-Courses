# M3 真实账号并行验证任务

日期：2026-09-25  
状态：READY TO EXECUTE / REAL ACCOUNT REQUIRED  
对象：M3 互动故事 / 分支世界  
事实基线：main @ 92600cf9c4bb8fa0172e77fca36d0471341bfd0b

## 任务目标

使用真实微信小程序教育平台账号，完成 M3 的最小产品验证。

本任务与 M4、M5 完全独立，可以并行执行。

## 必须读取

1. `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
2. `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`
3. `docs/CONTROLLED_DIVERGENCE_POLICY_V0.1.md`（执行分支）

## 执行范围

严格只跑：

1. 首版；
2. 修改1：勇气值 + 补给；
3. 修改2：玩家名字 + 三种身份；
4. Challenge：两个线索触发隐藏结局。

不要额外扩功能。

## 硬规则

- 不手写代码；
- 不人工 Debug；
- 出错先用自然语言要求 AI 自修；
- 不因为“能生成页面”就判通过，必须真实点击所有关键分支；
- 必须测试重新开始；
- 必须证明状态真的影响条件；
- 必须证明身份至少影响一次选择；
- Challenge 不能破坏原三种结局。

## 结果只记录

- 首版耗时；
- 修改1耗时；
- 修改2耗时；
- Challenge耗时；
- 是否出现故障；
- AI是否自修成功；
- 是否需要人工代码；
- 首版第一眼效果：强 / 中 / 弱；
- 最终试玩：通过 / 部分 / 失败；
- 发布/二维码：通过 / 未测 / 失败；
- Verdict：Strong Pass / Pass with Guardrails / Fail。

## Strong Pass 释放内容

通过后立即允许：

- 小学 L3 正式逐课教案；
- 小学 L4 正式逐课教案；
- 小学 Final 项目菜单加入 M3；
- 对应教师示例作品与课堂物料生产。

## Fail 时

不要提高教师技术门槛硬救。

只做：

- 缩小母版；
- 降低状态/分支复杂度；
- 固定更稳定的统一起点；
- 重新跑最小验证。

## 结果落库

建议结果文件：

`docs/M3_REAL_ACCOUNT_RESULT_2026-09-25.md`

没有真实账号执行证据前，不得把 M3 写成 Known-Good。
