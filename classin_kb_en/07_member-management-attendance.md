---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: Backend Management System
subcategory: "7. Member Management & Attendance"
batch: 4 of N
translated_from: zh-CN (source: 管理后台/7._成员管理与考勤)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 7. Member Management & Attendance

<!-- DOC_BOUNDARY -->
```yaml
title: "Editing Teacher or Student Information in the Backend"
source_title_zh: "后台修改教师或学生信息"
```

## Editing Teacher or Student Information in the Backend

### I. Editing Teacher Information in the Backend

#### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Teacher Management" permission

#### Usage Notes
Teaching staff can edit the profile of a teacher who has already been added to the Backend Management System. Editable fields include: teacher name, teacher photo, teacher tags, and teacher bio.

Note: the teacher's phone number and email cannot be changed here. To change the phone number, use the "Change ClassIn Phone Number" feature within the app.

#### Related Articles
"Adding Sub-accounts in the Backend Management System"

#### Steps
1. Log in to the Backend Management System.
2. Go to Teacher Management in the left navigation.
3. Find the teacher.
4. Click View on the right.
5. Click Edit in the upper-left corner.

![](https://cofile.eeo.cn/res-store%2Fe01f1494462e6ac77be6e158eb361bfd5fe5cdb357e3e5c9cd338bb285543394_664267?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=16a95f44645f25bbe82e1bbead497e8b83e5eb54)

### II. Editing Student Information in the Backend

In the ClassIn Backend Management System, only the primary account and sub-accounts with the "Student Management" permission can edit student information there.

Teaching staff can edit the profile of a student who has already been added to the Backend Management System. Editable fields include: student name and student tags.

Note: the student's phone number and email cannot be changed here. To change the phone number, use the "Change ClassIn Phone Number" feature within the app.

1. Log in to the ClassIn Backend Management System.
2. Go to the "Student Management" page in the left navigation.
3. Find the student to edit by name, phone number, or email.
4. Click "View" next to the student.
5. On the student details page, click "Edit."
6. After making changes, click "Confirm."

![](https://cofile.eeo.cn/res-store%2Fcf182a34ede76a20dec14ab601930e17de06586e17445ec1a29514513a1f8220_718332?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=b8fab60e5c2b41a8dd541f18c3b196ed79fd1692)

<!-- DOC_BOUNDARY -->
```yaml
title: "Adding Teachers and Students in the Backend"
source_title_zh: "后台添加教师与学生"
```

## Adding Teachers and Students in the Backend

### I. Adding a Teacher in the Backend

#### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Teacher Management" permission

#### Usage Notes
To add a teacher to the Backend Management System, provide the following basic information: the teacher's phone number or email (either one is fine) and the teacher's name. Optionally, you can also upload the teacher's photo, add tags, decide whether the teacher may use shared courseware resources, and write a bio (this is optional too). Finally, click "Confirm" to complete the addition.

Note: if the teacher being added has not yet registered a ClassIn account, check "Register a new teacher on their behalf" when adding them. The system will then automatically register an account for the teacher and send an SMS with a random password, so the teacher can log in with their phone number and password.

#### Related Articles
"Editing Teacher Information"
"Deactivating a Teacher"
"Adding Sub-accounts in the Backend Management System"

#### Steps
1. Log in to the Backend Management System.
2. Go to Teacher Management in the left navigation.
3. Click Add Teacher in the upper-right corner.

![](https://cofile.eeo.cn/res-store%2Fb48d220ae57c1656eba34acfb88ffab997a0587891f74aba4f45035396ce76f2_387172?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=408f06e7ae87c0fdc924120e0095bb3ff29da1d5)

### II. Adding a Student in the Backend

Sub-accounts with the "Student Management" permission.

#### When to use this
When teaching staff want to add students to a course, they can only choose from students already present in the current Backend Management System. If the student to be added is not yet in the current Backend Management System, teaching staff must first add that student under "Student Management," and give them a student identity in the current Backend Management System, before they can be added to the course.

To add a student to the Backend Management System, provide the following basic information: the student's phone number or email (either one is fine) and the student's name. Note: if the student being added has not yet registered a ClassIn account, check "Register a new student on their behalf" when adding them. The system will then automatically register an account for the student and send an SMS with a random password, so the student can log in with their phone number or email and password.

"Hiding a Student"

#### Steps
1. Go to Student Management in the left navigation.
2. Click Add Student in the upper-left corner.

![](https://cofile.eeo.cn/res-store%2Fd2f4e4580c0ee3cf3dc5fd9530b84ac58174da83db8775de57b0aff7e64dbf99_410743?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=dc48eb0eda69d72275d6b477ff6d224cef9ddf79)

<!-- DOC_BOUNDARY -->
```yaml
title: "Deactivating, Hiding, and Restoring Teachers/Students"
source_title_zh: "教师/学生停用、隐藏及恢复"
```

## Deactivating, Hiding, and Restoring Teachers/Students

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Teacher Management" or "Student Management" permission

### When to use this
**Deactivating a teacher:** When a teacher leaves, teaching staff can deactivate that teacher under "Teacher Management" in the Backend Management System. Once deactivated, that teacher will no longer appear in the list of available teachers when scheduling classes.

**Restoring a deactivated teacher:** If teaching staff want a deactivated teacher to be selectable again when scheduling classes, they can log in to the Backend Management System, go to "Teacher Management," find the deactivated teacher, and remove their deactivated status. The teacher will then reappear in the list of available teachers when scheduling classes. This is typically used when a teacher returns to work and needs to be made available for scheduling again.

**Hiding a student:** Teaching staff can hide a student under "Student Management" in the Backend Management System. Once hidden, that student will no longer appear in the list of available students when scheduling classes.

**Restoring a hidden student:** If teaching staff want a hidden student to appear again when scheduling classes, they can log in to the Backend Management System, go to "Student Management," find the hidden student, and remove their hidden status. The student will then reappear in the list of available students when scheduling classes.

### Notes
If the teacher to be deactivated holds a sub-account identity in the Backend Management System, they cannot be deactivated — the teacher's sub-account identity must first be removed under "Permission Management" before they can be deactivated.

A teacher who still has unfinished or ongoing classes cannot be deactivated.

### Related Articles
"Adding Sub-accounts in the Backend Management System"

### Steps

**(1) Deactivating a teacher in the backend**
1. Log in to the Backend Management System.
2. Go to Teacher Management in the left navigation.
3. Find the teacher.
4. Click Deactivate on the right.

![](https://cofile.eeo.cn/res-store%2F74f6417c8627a5d07140e84d455523209b1b98b4ee89d6d1d7bd90e2559c0be7_448382?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=fb5c4e9d50adc55ccbb8f7f18049b25cbe47c032)

**(2) Restoring a deactivated teacher**
1. Select "Deactivated" in the teacher status filter.
2. Click Activate on the right.

![](https://cofile.eeo.cn/res-store%2F7df88351fbb355858bde0532592b5cdf9f97fda52475c7103d012f17ade41213_277300?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=e26978d3ae6293cb2ee0337d3e2c70a75bcebcdb)

**(3) Hiding a student in the backend**
1. Go to Student Management in the left navigation.
2. Find the student.
3. Click Hide on the right.

![](https://cofile.eeo.cn/res-store%2F6ba7d6bcdfc84152a1607800d3dbfcdf3654347bd67f7d16b15c683c3c6ad5cc_410871?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=3058c96e6c7579f9151515c670ee585e465f2b1a)

**(4) Restoring a hidden student**
1. Select "Hidden from Scheduling" in the student status filter.
2. Click Show on the right.

![](https://cofile.eeo.cn/res-store%2Fb2323aad40963f8ecb1800bd5444539cb42e0f3f5b48a123a6d8a6fe34974d37_568506?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ed47e69c89d59c1ac83d2adc2a8100ecce6f1a7b)

<!-- DOC_BOUNDARY -->
```yaml
title: "Full Attendance for Teachers/Students"
source_title_zh: "教师/学生全部考勤"
```

## Full Attendance for Teachers/Students

### I. Full Teacher Attendance

#### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Teacher Management" permission

#### Usage Notes
On the "Teacher Details" page in the Backend Management System, teaching staff can view a given teacher's "teaching course progress" and "teaching lesson progress" across all courses at the school, as well as their attendance status for every class session at the school (including present, absent, late, and left early). The bottom of the "Teacher Details" page also supports viewing, via "Lesson List" mode or "Calendar Schedule" mode, the attendance status, actual class duration, average student rating, and teaching report for every class session the teacher has taught.

#### Related Articles
"Adding Sub-accounts in the Backend Management System"

#### Steps
1. Log in to the Backend Management System.
2. Go to Teacher Management in the left navigation.
3. Find the teacher and click View on the right.

![](https://cofile.eeo.cn/res-store%2F0e3b82436ed432f059be34d58a8679f0bc9272490c742ab2e7198b28879a6f47_686156?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a70beb5b070847cac0d5f0128170d4b87d6a58d7)

### II. Full Student Attendance

Sub-accounts with the "Student Management" permission.

On the "Student Details" page in the Backend Management System, teaching staff can view a given student's "course participation progress" and "lesson participation progress" across all courses they've taken at the school, as well as their attendance status for every class session at the school (including present, absent, late, and left early). The bottom of the "Student Details" page also supports viewing, via "Lesson List" mode or "Calendar Schedule" mode, the attendance status, actual class duration, teacher's rating, and learning report for every class session the student has attended.

1. Go to Student Management in the left navigation.
2. Find the student.
3. Click View on the right.

![](https://cofile.eeo.cn/res-store%2F6130b42b420051cb1f622357fdffc701e16c093317f7b4159a154c27a0643eb8_689254?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=da61bb572d3e3efa1c892367ce69cbf042b296af)

<!-- DOC_BOUNDARY -->
```yaml
title: "Viewing Attendance"
source_title_zh: "查看出勤情况"
```

## Viewing Attendance

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Class Monitoring Management" permission

### When to use this
If teaching staff want to quickly check the attendance of everyone in a particular classroom without downloading an attendance record, they can find the corresponding classroom under "Class Monitoring Management" and open that classroom's monitoring details page. On this page, teaching staff can see attendance records for all students and teachers in that classroom.

### Usage Notes
On the monitoring details page, teaching staff can see attendance information for every teacher and student in the classroom, including: name, nickname, phone number, their role in the classroom, whether they were absent, whether they were late, whether they left early, actual class duration, and each time they entered and exited the classroom. This information helps teaching staff better understand attendance in each classroom and quickly identify and address issues.

### Related Articles
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to Class Monitoring Management in the left navigation.
3. Find the lesson.
4. Click the lesson to open Monitoring Details and view teacher and student attendance.

![](https://cofile.eeo.cn/res-store%2F6b1393d3ca913a517502095b9651d2cdec959d87b4371b767752739927e545ec_977313?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a2b7ec08ba7d5b0faff51451ea254faeebfc32b3)

<!-- DOC_BOUNDARY -->
```yaml
title: "Class Attendance"
source_title_zh: "课堂考勤"
```

## Class Attendance

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Finance Center" permission

### When to use this
When teaching staff want to view a detailed class attendance record for a given time period, they can download it as a spreadsheet from the "Statistics & Downloads" module in the Backend Management System. The spreadsheet includes: attendance date range, class ID, class name, class session ID, class session name, start time, end time, duration (minutes), number of people on stage, number of students in the class, teaching teacher, teaching teacher's nickname, teaching teacher's phone number, teaching teacher's email, lesson tags, role, name, nickname, phone number, email, attendance, actual class duration (minutes), late, left early, first entry into the classroom, last exit from the classroom, class tags, teacher tags, student tags, head teacher's name, head teacher's phone number, and head teacher's email.

### Usage Notes
Up to 6 months of data can be downloaded at a time.

Multiple download tasks can be run simultaneously.

Requested downloads appear in the "Task Center." Users can go to the Task Center to complete the download.

### Related Articles
"Adding Sub-accounts in the Backend Management System"

### Steps
1. Log in to the Backend Management System.
2. Go to Statistics & Downloads in the left navigation.
3. Filter by date.
4. Click Download next to Class Attendance, wait for the download task to be generated, and click "View" in the new pop-up window.

![](https://cofile.eeo.cn/res-store%2F560a669e759b5d7ae7a91bb179fc56977211580efe2ab7822477dc3a688bdb92_256268?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=4094d2c6aac62ea5023ad6edca7fd20cf7e70cea)
