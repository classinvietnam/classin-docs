---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: Backend Management System
subcategory: "12. SMS Alerts, Add-on Features, Task Center"
batch: 9 of N
translated_from: zh-CN (source: 管理后台/12._短信提醒、附加功能、任务中心)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 12. SMS Alerts, Add-on Features, Task Center

<!-- DOC_BOUNDARY -->
```yaml
title: "OMO Livestream Broadcast"
source_title_zh: "OMO站播"
```

## OMO Livestream Broadcast

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Once teaching staff enable the OMO livestream broadcast feature in the Backend Management System, teachers can enable OMO livestream broadcast under recording settings when creating a class session, whether in the backend or in the app.

### Related Articles
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Value-Added Services at the top.
4. Under Value-Added Services, turn OMO Livestream Broadcast on or off.

![](https://cofile.eeo.cn/res-store%2Fae5c86a6746b9203c39aca76e7ca410a5a2cc501a71cdc879524e498263d7565_635580?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=fc6201cc89e7ca58fc0f80c79936925cbb187316)

<!-- DOC_BOUNDARY -->
```yaml
title: "Task Center"
source_title_zh: "任务中心"
```

## Task Center

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
You can create multiple download tasks at once without waiting on the current page.

Previously downloaded data can be viewed, so the same data doesn't need to be downloaded again.

You can view each administrator's download activity, which helps protect data security.

1. **View download progress and results.** Completed download tasks can be downloaded as files. Each file supports exporting up to 100,000 rows of data; if this is exceeded, the export is split across multiple files. If there is only one file, it downloads directly; if there are multiple files, they download as a zip archive (named the same as the download task, following the same naming logic), with each file inside numbered "_1," "_2," and so on.

2. **Task naming convention:** task type + data date range — for example, a task named "Lesson Attendance 20240301-20240331" generates a file containing lesson attendance data for March 1–31, 2024.

3. You can look up historical download tasks by task name, task type, or operation time, so the same data doesn't need to be downloaded again.

4. The organization's primary account can see every administrator's downloads in the Task Center; organization sub-accounts can only see their own downloads. Every task records the operation time and the person who performed it, so system administrators can review each administrator's actions, quickly spot and prevent unauthorized activity, and improve system security.

### Notes
There is some delay in data downloads — for example, if you download data at 19:00, the earliest available data will be up to 18:40 that day. Workaround: wait 10–20 minutes after a lesson ends before downloading its data.

### Related Articles
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to Task Center in the left navigation.
3. Find or download a generated task.

![](https://cofile.eeo.cn/res-store%2F5f75a94a438862f4306ef255da2d2bb35ad5a1b1383303e1e4f13f1a4f887402_107220?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=8a3cbbe398f3f3b0a514962211f4df6a8a85b66a)

<!-- DOC_BOUNDARY -->
```yaml
title: "Balance/Contract Expiration SMS Alerts"
source_title_zh: "余额/合同到期短信提醒"
```

## Balance/Contract Expiration SMS Alerts

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can enable or disable SMS and phone alerts for account balance and contract expiration in the Backend Management System. Once enabled, teaching staff can set alert thresholds — up to six thresholds. When the balance falls below a threshold, or 30 days before the contract expires, the system will notify the user via SMS and phone call.

### Related Articles
"Storage Balance Alerts"
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Account Balance/Contract Expiration Alert at the top.
4. Under Account Balance/Contract Expiration Alert, turn "Account balance/contract expiration SMS alert" on or off (this feature is free — no SMS charges apply), and add multiple phone numbers below to receive the alerts.

![](https://cofile.eeo.cn/res-store%2F3c5f5e4c9fde034ff21a510e7aabc7a4feadd989a20b83d7851caaa78df2fc46_315051?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=3538c270bfcc9c2618a627357747ff65576813a4)

<!-- DOC_BOUNDARY -->
```yaml
title: "Storage Balance Alerts"
source_title_zh: "存储余量提醒"
```

## Storage Balance Alerts

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
After setting a phone number and alert threshold for storage balance alerts, when remaining storage falls below the threshold, the designated phone number will promptly receive an SMS alert, helping avoid disruptions to normal usage. In addition to the set threshold, an SMS alert is also sent when storage reaches its cap. This alert feature is free — no SMS charges apply.

### Related Articles
"Balance/Contract Expiration SMS Alerts"
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Balance Alerts at the top.
4. Under Balance Alerts, set the alert threshold and add multiple phone numbers to receive the alerts.

![](https://cofile.eeo.cn/res-store%2F6ffb3ded27455d55d44816a9b89cec86280eff00a558e9390b976766b2cb3cba_156247?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=d95fdbd19c7df240551c50a32d95c1632f679499)

<!-- DOC_BOUNDARY -->
```yaml
title: "AI Agents"
source_title_zh: "智能体"
```

## AI Agents

### I. Basic AI Agent

#### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

#### Usage Notes
Once teaching staff enable the "Basic AI Agent" feature in the Backend Management System, teachers in a class can use AI apps and LMS AI-related features in the ClassIn class group (lesson summaries, generating/grading assignments, generating quizzes, analyzing answer sheets, and adding to the AI Speaking Card — the last of these can only be added, not generated).

#### Related Articles
"Adding Sub-accounts in the Backend Management System"

#### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Value-Added Services at the top.
4. Under Value-Added Services, turn Basic AI Agent on or off.

![](https://cofile.eeo.cn/res-store%2F05883899922cdaa546e933961f69f83f02eec3c1528b81695bd124f0964ee4b1_667355?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=50d409caaf7b1ad1dcbbff1c146f5bcdfe5cffcb)

### II. AI Teaching Analysis

Teaching staff must first enable the AI Teaching Analysis feature in the Backend Management System before this option can be checked when creating a class session in a backend class.

Under Value-Added Services, turn AI Teaching Analysis on or off.

![](https://cofile.eeo.cn/res-store%2Fcc1209d4b0e86e12f79945bd707c6a2f7b674c569f60a2e27d374fa041d741ca_657666?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a40b19f8005d01207c92eadcfb1a2464b36a4e00)

<!-- DOC_BOUNDARY -->
```yaml
title: "Smart Homeroom Teacher"
source_title_zh: "智能班主任"
```

## Smart Homeroom Teacher

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can enable or disable the Smart Homeroom Teacher feature through the school's Backend Management System. Once enabled, teaching staff can use it for two types of alerts: reminding students to prepare for class via SMS or phone call before class starts, and reminding students who haven't shown up within 3 minutes of class starting.

In the Backend Management System, teaching staff can configure the specific behavior of Smart Homeroom Teacher, which includes the following options:

- Remind students by phone or SMS the day before class that they have a class the next day.
- Remind students again by phone or SMS 1 hour before class starts.
- If a student still hasn't shown up 3 minutes after class starts, remind them by phone or SMS to join immediately.
- Remind teachers by phone or SMS the day before class that they have a class the next day.
- Remind teachers again by phone or SMS 1 hour before class starts.
- If a teacher still hasn't shown up 3 minutes after class starts, remind them by phone or SMS to join immediately.

These six reminder features can be enabled or disabled all together, and for each reminder type, you can choose either phone call or SMS (not both).

### Related Articles
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Value-Added Services at the top.
4. Under Smart Homeroom Teacher, turn the feature on or off and configure its settings.

![](https://cofile.eeo.cn/res-store%2F8a2439f210504bbb7f92d3bad4fa46ccc1550fc505cfe84742e7f9ad6374389d_374548?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=d7323114974f51271b0a86165954036aef9b385b)

<!-- DOC_BOUNDARY -->
```yaml
title: "Super Customer Service"
source_title_zh: "超级客服"
```

## Super Customer Service

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can enable or disable the Super Customer Service feature in the Backend Management System. Once enabled, teaching staff can use voice callback on the Class Monitoring Management page in the Backend Management System to directly contact teachers, co-teachers, and students — quickly resolving issues in the classroom.

If there are many teaching staff members in the Backend Management System, the school can enable "Phone Number Masking" to protect teacher and student privacy. Once enabled, 4 digits of student and teacher phone numbers will be masked on the Class Monitoring Management and Account Lookup pages, preventing contact information from leaking.

Note: this feature only supports mainland China phone numbers, excluding Xinjiang, Tibet, and Inner Mongolia. The caller ID shown to both the caller and the callee is a Hangzhou, China number: 0571-57184557.

### Related Articles
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Value-Added Services at the top.
4. Under Super Customer Service, turn "Super Customer Service" and "Phone Number Masking" on or off.

![](https://cofile.eeo.cn/res-store%2Fa44e826f3aba6f609cee16ae1c297fee83f69dd98d1e73d7b8269a93ad7b2854_529003?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ea76e7588eba0a8b73cade53f76aa2eae203ab69)
