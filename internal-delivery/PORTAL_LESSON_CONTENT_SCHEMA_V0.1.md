# Teacher Portal 单课内容结构 V0.1

更新时间：2026-09-25  
状态：CONTENT INTERFACE CANDIDATE  
来源：四节教师整合页样板

本文件不是 Teacher Portal 软件实现方案，而是课程内容与平台之间的固定接口。

目标：

> 一份内部教师源稿可以稳定生成“教师单课页面 + 课堂投屏 + 学生任务页”，而不需要平台开发人员重新理解课程。

## 1. 单课内容对象

每节课固定包含以下内容块。

### lesson_identity

- course_line：小学高年级 / 初中；
- lesson_number；
- lesson_title；
- duration_minutes；
- prerequisite；
- common_start：本节全班共同起点。

### teacher_quick_view

老师一分钟先看：

- today_output：今天学生做成什么；
- finish_line：下课最低要有什么；
- checkpoints：关键时间点；
- likely_problems：最常见问题；
- do_not_do：本节不要做什么。

### preclass

- teacher_account_check；
- demo_asset；
- required_materials；
- projector_check；
- platform_check；
- special_preparation。

### timeline

每一段包含：

- start_minute；
- end_minute；
- stage_title；
- teacher_action；
- teacher_words；
- student_action；
- checkpoint；
- if_behind。

### stuck_help

按“学生看到的现象”组织，而不是按技术原因组织。

每项：

- symptom；
- teacher_first_action；
- student_words_or_prompt；
- stop_condition。

### classwide_recovery

多人出现同类问题时：

- trigger；
- teacher_projection_action；
- unified_instruction；
- student_recheck。

### fast_students

按风险从低到高排列：

- next_1；
- next_2；
- next_3；
- open_extension；
- guardrail。

### closing

- stop_new_work_at；
- final_check；
- save_assets；
- teacher_collects；
- final_words。

### projection_source

只包含学生需要看到的投屏页。

每页：

- title；
- body；
- optional_visual；
- timer_or_checkpoint。

不得显示：

- 教师恢复库；
- 渠道信息；
- 研发历史；
- 未授权后续课；
- 内部母版研发说明。

### student_task_source

只包含学生当节需要：

- today_task；
- step_1...step_n；
- finish_check；
- if_finished_early。

### after_class_record

控制在约1分钟：

- completion_count；
- behind_at_checkpoint；
- top_blockers；
- platform_incident；
- best_examples；
- must_fix_next_version。

---

## 2. 权限边界

### 课程方内部

可以读取全部上述内容以及研发来源。

### 认证教师正常授课

Teacher Portal 在线显示：

- teacher_quick_view；
- preclass；
- timeline；
- stuck_help；
- classwide_recovery；
- fast_students；
- closing；
- projection_source；
- after_class_record。

不提供整课文件自助下载。

### 学生

只显示：

- projection_source 中面向学生的页面；
- student_task_source。

### 代理商管理员

不因为管理班级而获得 teacher_quick_view / timeline / stuck_help 全量内容。

---

## 3. 与研发 Markdown 的关系

研发仍然可以保留：

- 复杂度预算；
- 母版状态；
- 验证证据；
- 内部术语；
- 设计原因。

进入教师源稿时，编译成人话。

例如：

- BASE → 本节最低完成线 / 稳定完成线；
- BASE DEADLINE → 到这个时间全班先停下来检查；
- FALLBACK → 学生卡住时怎么救回来；
- Recovery → 常见问题怎么处理；
- Challenge → 做得快的学生接下来做什么。

---

## 4. 第一批样板映射

当前四份教师源稿已经覆盖所有必需内容块：

- `teacher-source/primary-upper/L01_FIRST_GAME_TEACHER_V0.1.md`
- `teacher-source/primary-upper/L15_PRODUCT_TEST_AND_RELEASE_TEACHER_V0.1.md`
- `teacher-source/middle-school/L03_RULE_LAB_TEACHER_V0.1.md`
- `teacher-source/middle-school/L09_AI_REVIEWER_TEACHER_V0.1.md`

结构 QA 见：

`../docs/FOUR_TEACHER_SAMPLE_QA_2026-09-25.md`

## 5. 冻结条件

在四节目标教师内部走课通过以前，本 schema 标记为 Candidate。

通过后：

1. 冻结 V1；
2. 其余已有课程按同一接口批量教师化；
3. Teacher Portal 按此结构读取内容；
4. PPT / 学生页由同一源内容派生。

避免出现：

> 教案一套事实、PPT另一套事实、Portal再维护第三套事实。
