# M4 真实账号并行验证任务

日期：2026-09-25  
状态：READY TO EXECUTE / REAL ACCOUNT REQUIRED  
对象：M4 兴趣馆 / 知识产品  
事实基线：main @ 92600cf9c4bb8fa0172e77fca36d0471341bfd0b

## 任务目标

使用真实微信小程序教育平台账号，完成 M4 的最小产品验证。

本任务与 M3、M5 完全独立，可以并行执行。

## 必须读取

1. `docs/MOTHER_TEMPLATE_VALIDATION_PROTOCOL_V1.md`
2. `docs/MOTHER_TEMPLATE_M3_M4_M5_RUN_CARDS.md`
3. `docs/CONTROLLED_DIVERGENCE_POLICY_V0.1.md`（执行分支）

## 执行范围

严格只跑：

1. 首版：恐龙探索博物馆；
2. 修改1：探索进度；
3. 修改2：自定义新展区；
4. Challenge：隐藏展品 + 探索大师徽章。

不要额外扩功能。

## 硬规则

- 不手写代码；
- 不人工 Debug；
- 出错先用自然语言要求 AI 自修；
- 首版不能只是文字列表；
- 4个展区、详情、收藏、挑战必须真实工作；
- 看过展品必须真实进入探索进度；
- 自定义展区必须能保存并参与进度；
- Challenge 条件必须真实生效；
- 不接登录、服务器和外部 API。

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

- 小学 L5 正式逐课教案；
- 小学 L6 正式主线教案；
- 小学 Final 项目菜单加入 M4；
- 对应教师示例作品与课堂物料生产。

## Fail 时

不要通过增加教师技术操作救回。

只做：

- 缩小自定义展区或进度要求；
- 降低状态联动复杂度；
- 固定更稳定的统一博物馆起点；
- 重新跑最小验证。

## 结果落库

建议结果文件：

`docs/M4_REAL_ACCOUNT_RESULT_2026-09-25.md`

没有真实账号执行证据前，不得把 M4 写成 Known-Good。
