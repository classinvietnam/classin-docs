---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: Admin Console Tutorials
subcategory: Course Center
batch: 6 of N (Admin Console category, batch 2)
translated_from: zh-CN (consolidated knowledge base)
---

# Admin Console: Course Center (Member Management & Class Management)

<!-- DOC_BOUNDARY -->
```yaml
title: "Head Teacher Management"
source_title_zh: "班主任管理"
```

## Head Teacher Management

### Who this applies to
- The Admin Console primary account
- Sub-accounts with "Course Management" access

### When to use this
When a class needs a new head teacher, academic staff can find the relevant class in the Admin Console and reassign the head teacher role to someone else.

### Related articles
- "Adding Sub-accounts in the Admin Console"

### Steps

**Change the head teacher**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Find the class and click its name to enter.
4. Go to Members.
5. Click "···" next to the current head teacher.
6. Select "Change Head Teacher."

**Bulk change head teachers**
1. Go to Class Management.
2. Select multiple classes.
3. Click Bulk Actions.
4. Select "Bulk Set Head Teacher."

<!-- DOC_BOUNDARY -->
```yaml
title: "Excluded Students Management"
source_title_zh: "调出生管理"
```

## Excluded Students Management

### I. What is an "excluded student"?
An excluded student is a student a teacher has blocked from attending a specific session within a class. The excluded student cannot enter that particular session's classroom, but can still attend the class's other sessions normally.

### II. Setting an excluded student

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Management" access

**Overview**
If a student drops out early or academic staff need to block certain students from a specific session, staff can mark them as excluded for that session. Once excluded, the student can't enter the blocked session, nor watch its recorded playback.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Find and open the class.
4. Go to Schedule.
5. Find the session, then click Add next to "Excluded Students."
6. Add the excluded student(s).

### III. Removing an excluded student
Requires a sub-account with "Course Management" access.

Find the session, hover over "Excluded Students," and click the pencil icon that appears to remove excluded students — supports removing all at once or individually.

<!-- DOC_BOUNDARY -->
```yaml
title: "Auditing Students Management"
source_title_zh: "旁听生管理"
```

## Auditing Students Management

### I. What is an "auditing student"?
An auditing student can sit in on a class without being visible to the teacher or other students — neither the teacher nor other students can see them, and their name doesn't appear in the roster. In effect, they attend invisibly. Even so, if their cumulative attendance reaches 10 minutes, it still counts as a valid attendance record. Auditing students can't use any classroom tools — they can only listen. Once added, they appear in the class's student list but cannot watch the class playback.

### II. Adding an auditing student

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Management" access

**When to use this**
Each class can have up to 20 auditing students. This feature is mainly meant to let academic staff offer trial-listening seats within a class, helping students preview the course. Auditing students can join the class group chat and interact with other students and the teacher, but no one in the classroom can see them — they're effectively invisible while listening in. This is useful for students exploring elective/interest classes, letting them audit a session before deciding whether to formally enroll.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Find and open the class.
4. Go to Members.
5. Go to Auditing Students.
6. Click "Set Auditing Students."

### III. Removing an auditing student
Requires a sub-account with "Course Management" access.

Remove the auditing student from the list.

<!-- DOC_BOUNDARY -->
```yaml
title: "Guest Students Management"
source_title_zh: "插班生管理"
```

## Guest Students Management

### I. What is a "guest student"?
A guest student is a student who isn't formally part of a class, but has been arranged by academic staff to attend one specific session of that class.

### II. Adding a guest student

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Management" access

**When to use this**
When a teacher wants to invite a student to sit in on a particular session — and wants that student to be able to interact with the teacher and other students in the classroom — but doesn't want to formally add them to the class, they can add the student as a guest student for that session.

**Overview**
A "guest student" is a non-enrolled student arranged by academic staff to attend a specific session of a class. Guest students have no class group, so they can't take part in homework, quizzes, or chats assigned in the class group chat. However, within the classroom itself, guest students have the same permissions as regular students — they can speak on stage, be granted tool access by the teacher, and participate in in-classroom chat.

**Notes**
- If a student is already formally enrolled in a class, they cannot also be added as a guest student for any session in that same class.
- Guest students share the same class headcount cap as regular enrolled students.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Find and open the class.
4. Go to Schedule.
5. Find the session, then click Add next to "Guest Students."
6. You can add guest students from students/teachers within your school, or from outside your school.

### III. Removing a guest student
Find the session, hover over "Guest Students," and click the pencil icon that appears to remove — supports bulk removal or removing individually.

<!-- DOC_BOUNDARY -->
```yaml
title: "Class Student Management (Admin Console)"
source_title_zh: "班级学生管理（后台）"
```

## Class Student Management (Admin Console)

### I. Adding students to a class

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Management" access

**Overview**
In the Admin Console, academic staff can add any student to a class, whether or not they've registered a ClassIn account. If the student already has a ClassIn account and appears in the console's student list, staff can simply search by name or phone number to find and add them. If the student isn't yet in the console's student list, or hasn't registered a ClassIn account, staff can register an account on their behalf while adding them to the class.

**Related articles**
- "Auditing Students Management"
- "Guest Students Management"
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Find the class and click its name to enter.
4. Go to Members.
5. Click "Set Class Students."

### II. Copying students from another class

**Who this applies to** / **When to use this**
In the Admin Console, when a class's sessions have reached the maximum allowed, teachers who need to add more sessions must create a new class. To avoid manually re-adding every student to the new class, the system lets teachers directly copy all students from the original class into the new one — saving time and improving efficiency.

**Notes**
- If your class already has students, copying a student list from another class will replace all existing students in the current class. Use this feature carefully.

**Steps**
1. Click "Copy Class Students."

### III. Editing class students
When academic staff need to change class membership, they can edit it directly from the class student list.
- Use the top-right corner to add or remove students.

### IV. Removing class students
Remove a single student, or select multiple students and use Bulk Actions > Bulk Remove Students.

<!-- DOC_BOUNDARY -->
```yaml
title: "Create/Edit/Delete Public Classes (Admin Console)"
source_title_zh: "创建修改删除公开课（后台）"
```

## Create/Edit/Delete Public Classes (Admin Console)

### I. Creating a public class

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Public Classes" access

**When to use this**
If a teacher wants to hold a session that isn't tied to any class — such as a class meeting, parent-teacher conference, guest lecture, or teacher workshop — consider creating a public class instead. This better supports a variety of non-standard teaching scenarios.

**Overview**
Creating a public class in the Admin Console automatically generates a matching public class in the ClassIn app, and vice versa — creating one in the app generates a matching entry in the Admin Console. The two are identical; there's no difference between them.

**Steps**
1. Log into the Admin Console.
2. Go to Public Classes in the left navigation.
3. Click Create Public Class.
4. Set the parameters.

### II. Editing a public class
Requires a sub-account with "Class Management" access.
1. Find the public class.
2. Hover over the parameter you want to change; when a pencil icon appears on the right, click it to edit that field.

### III. Deleting a public class
1. Click "Actions" on the right, then select "Delete Public Class."

<!-- DOC_BOUNDARY -->
```yaml
title: "Tag Management"
source_title_zh: "标签管理"
```

## Tag Management

### Who this applies to
- The Admin Console primary account
- Sub-accounts with "Course Management" access

### When to use this
In the Admin Console, tags help academic staff manage courses, sessions, and teacher/student members more conveniently. Using tags, staff can quickly search for and categorize courses, sessions, or members — making management more efficient.

### Overview
The Admin Console supports up to 2,000 tags total. Each course and session, and each teacher and student, can have up to 10 personal tags.

### Related articles
- "Adding Sub-accounts in the Admin Console"

### Steps

**(1) Add/edit course tags**
1. Log into the Admin Console.
2. Go to Course Management in the left navigation.
3. Click "Create Course" on the right.
4. Below, click "Select Course Tags."
5. Create a new tag or choose an existing one.
6. Click Confirm to save.

**(2) Add/edit session tags**
1. Find the course, click its name to enter session details.
2. Click "Add Session."
3. Click "Select Session Tags."

**(3) Add/edit teacher tags**
1. Go to Teacher Management in the left navigation.
2. Find the teacher, click View on the right.
3. Then click Edit.
4. Select tags.

**(4) Add/edit student tags**
1. Go to Student Management in the left navigation.
2. Find the student, click View on the right.

<!-- DOC_BOUNDARY -->
```yaml
title: "Create/Edit/Delete Dual-Teacher Sessions"
source_title_zh: "创建修改删除双师课"
```

## Create/Edit/Delete Dual-Teacher Sessions

### I. Creating a dual-teacher session

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Course Management" access

**Overview**

**Method 1: Create a new class and add a main/satellite session**
If academic staff haven't yet created a main session for a dual-teacher setup in the Admin Console, they can: first create a new class in the Admin Console, then add a session within that class, then bulk-add satellite sessions and set the newly created session as the main session.

**Method 2: Set an existing session as the main session and add satellite sessions**
Alternatively, staff can go directly into a class in the Admin Console, click "Bulk Create Satellite Sessions," designate an existing session as the main session for a dual-teacher setup, then add satellite sessions.

**Notes**
- The dual-teacher feature must be enabled separately by contacting your account manager.
- Each dual-teacher main session supports up to 100 satellite sessions.
- Satellite sessions cannot be created within 5 minutes of the main session's start time, or after it has already started.
- Both the app and the Admin Console support editing/deleting the main session; satellite sessions automatically sync with changes made to the main session.
- Satellite session settings cannot be edited in the app — only in the Admin Console.
- Dual-teacher sessions don't require a dedicated class — an existing class can be used.
- The main session and its satellite sessions cannot belong to the same class.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**

**Create the "main session"**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Find and open the class.
4. Go to Schedule.
5. Click New.
6. Select "Create Session."

**Add "satellite sessions"**
1. Select the session (the selected session will automatically become the main session).
2. Click "Bulk Add Satellite Sessions."
3. Set the satellite sessions' parameters (you'll need to pre-create an empty class to hold the satellite sessions — when creating them, assign them to that pre-created empty class).

### II. Editing a dual-teacher session
When editing a satellite session, you cannot change: start date, start time, session duration, or teacher.
- Satellite sessions can only be edited in the Admin Console.
- The main session can be edited in both the Admin Console and the app.

**Edit the "main session" or a "satellite session"**
1. Find the class containing the main or satellite session and open it.
2. Edit the session.

### III. Deleting a dual-teacher session
Academic staff can delete both main and satellite sessions from the Admin Console. First, find the relevant main session. Delete satellite sessions from the main session's dual-teacher page. Deleting the main session automatically deletes all its satellite sessions. To delete just one satellite session, deleting it alone won't affect the others.

Deleting a main session automatically deletes all associated satellite sessions.

1. Go to Course Management in the left navigation.
2. Find and open the class containing the main session.
3. Click "Actions" next to the main session, then select "Dual-Teacher Online."
4. Delete the main session or a satellite session.

<!-- DOC_BOUNDARY -->
```yaml
title: "Create/Edit/Delete Sessions (Admin Console)"
source_title_zh: "创建修改删除课堂（后台）"
```

## Create/Edit/Delete Sessions (Admin Console)

### I. Creating a session

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Management" access

**Overview**

Parameters available when adding a session:

| Setting | Description |
| --- | --- |
| Session Name | Up to 50 characters. |
| Start Date | Can be today or any other date. |
| Start Time | Earliest allowed is 5 minutes from now. |
| Session Duration | Minimum 15 minutes, maximum 23 hours 55 minutes. |
| Teacher | Add the main teacher — only one per session. |
| Co-Teachers | Up to 6 co-teachers per session, or none at all. |
| Teaching Mode | "Online Classroom" suits pure online teaching; "Smart Classroom" suits hybrid online/offline teaching. |
| Auto Stage | When enabled, students' camera feeds automatically appear on stage upon entering the classroom (regardless of whether their camera is on). When disabled, students enter "off-stage" and their camera won't automatically appear on stage. |
| On-Stage Capacity | From 1v0 to 1v12. 1v0 means only the teacher's camera shows on stage (no student cameras). 1v12 means the teacher's camera plus up to 12 students' cameras can be shown simultaneously. |
| Session Cloud Drive Resources | Public courseware resources that can only be opened within this specific session's classroom. |
| Cloud Recording | Supports enabling "Record Classroom" and "Record On-site" simultaneously, or either individually, or neither. |
| Live/Playback | Supports enabling "Web Live Stream" and "Web Playback" simultaneously. With "Web Live Stream" enabled, viewers can watch the real-time class broadcast via a link shared by the teacher. With "Web Playback" enabled, viewers can watch the recorded playback via a shared link. |

**Notes**
- If "Session-Authorized Resources" is set when creating a session, the teacher can only use courseware authorized under "Session Cloud Drive Resources" or their own personal cloud drive during that session — not courseware authorized under "Class Cloud Drive Resources."

**Related articles**
- "Adding Students to a Class"
- "Adding Sub-accounts in the Admin Console"
- "Editing a Session"
- "Deleting a Session"

**Steps**

**(1) Create a single session**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Find the class and click its name to enter.
4. Click Schedule.
5. Click New > Create Session.
6. Set the relevant parameters.

**(2) Bulk-create sessions**
1. Click New > Bulk Create Sessions.

### II. Editing a session

**Who this applies to** / **Overview**

When editing session info and settings, note the following time restrictions:

**(1) Session name, start date, start time, duration:**
Editable window: any time more than 20 minutes before the session's start time.
Restriction: cannot be edited within 20 minutes of the start time, during the session, or after it ends.

**(2) Teacher and co-teachers:**
Editable window: can be added or edited before or after the start time.
Restriction: cannot be edited once the session has ended.

**(3) On-stage capacity (e.g. changing 1v1 to 1v6):**
Editable window: any time more than 20 minutes before the session's start time.

**(4) Cloud recording and web live stream:**

**(5) Web playback:**
Editable window: can be changed anytime — before, during, or after the session — including viewing permission for web playback.

**(6) Deleting a session:**
Editable window: can be deleted at any time before the session officially starts.
Restriction: cannot be deleted once the session has officially started.

**Steps**

**(1) Edit a single session**
1. Find the session you want to edit, click "Actions" on the right, then select "Edit Session."

**(2) Bulk-edit sessions**
1. Select the sessions to edit, click Bulk Actions, then choose the setting to bulk-edit; or hover over a session and click the pencil icon to open Bulk Edit.

### III. Deleting a session
Sessions that have already started or already ended cannot be deleted — only sessions that haven't started yet can be deleted.

**(1) Delete a single session**
1. Find the session to delete, click "Actions" on the right, then select "Delete Session."

**(2) Bulk-delete sessions**
1. Select the sessions to delete, click Bulk Actions, then select "Bulk Delete Sessions."

<!-- DOC_BOUNDARY -->
```yaml
title: "Create/Edit Class / End Class (Admin Console)"
source_title_zh: "创建修改班级结课（后台）"
```

## Create/Edit Class / End Class (Admin Console)

### I. Creating a class

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Management" access

**Overview**
Classes created in the Admin Console support more advanced configuration — such as adding guest students, excluded students, and auditing students. The Admin Console also supports features like reassigning the head teacher. For this reason, we recommend creating and managing classes in the Admin Console whenever complex management is needed.

Parameters available when creating a class:

| Setting | Description |
| --- | --- |
| Class Name | Required. Give the class an easily recognizable name, up to 40 characters. |
| Head Teacher | Assign a head teacher for the class. The head teacher can manage class members and create/delete sessions from within the ClassIn app. |
| Class Teachers | Teachers who can teach or assist with management. Can also be set later via Members after the class is created. |
| Class Students | Students who participate in class activities. Can also be set later via Members after the class is created. |
| Class Cover | Upload a cover image from the system library or your local computer. |
| Class Description | Write an appealing, concise description for the class — shown within the ClassIn app and on live/playback links. |
| Class Cloud Drive Resources | Set the class-level cloud drive resources. All sessions in the class can use courseware authorized here, unless a session has its own "Session Cloud Drive Resources" set, in which case the teacher can only use resources authorized at the session level during that session. |
| Class Classroom Settings | Choose a custom classroom configuration for the class, applied to all its sessions. If not selected, the school's default custom classroom configuration is used. |
| Class Tags | Add tags for easier management and searching. |
| Class Expiration | Set an expiration date. If the class has no upcoming or ongoing sessions after this date, the system automatically ends the class.<br><br>Note: classes default to never expiring. To enable auto-ending, set the expiration to a certain number of days after the last session ends (minimum 1 day, maximum 365 days). |
| Playback View Limit | Set how many times students can watch the class recording playback, from 1 to 20 (a view counts as valid once the student has watched at least 75% of the total video duration). |
| Advanced Settings | Enable or disable: "Allow students to join the class on their own," "Allow class members to add each other as friends," "Allow teachers to add sessions," "Allow students to edit their class nickname," "Allow content to remain viewable for students who've left the class or after the class ends," "Allow class members to start temporary classrooms." The head teacher can also configure these from within the ClassIn app. |

**Notes**
- The Admin Console doesn't support sharing a QR code to join the class. To share one, go to the corresponding class's settings within the ClassIn app and use "View/Share Join QR Code."

**Related articles**
- "Adding Students to a Class"
- "Adding a Session"
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Management in the left navigation.
3. Click "Create Class."
4. Fill in the class parameters.
5. Click Confirm.

### II. Editing a class

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Management" access

**Overview**
Existing classes can be edited in the Admin Console. Editable fields include: class name, cover, description, head teacher, class cloud drive resources, classroom settings, tags, expiration, playback view limit, and advanced settings. Advanced settings include toggles for: allowing students to join independently, allowing members to add each other as friends, allowing teachers to add sessions, allowing students to edit their nickname, allowing content access after leaving/dissolution, and allowing temporary classrooms. The head teacher can also edit these options from within the ClassIn app.

See also: "Ending a Class"

**Steps**
1. Log into the Admin Console.
2. Go to Class Management.
3. Find and open the class.
4. Go to Settings to edit the class.

### III. Ending a class

**What does "ending a class" mean?**
"Ending a class" refers to academic staff ending a class in the Admin Console, which simultaneously dissolves the corresponding class in the ClassIn app. Conversely, when a class is dissolved in the ClassIn app, the system automatically ends the corresponding class in the Admin Console. So "ending a class" and "dissolving a class" refer to the same action — one performed from the Admin Console, the other from the ClassIn app.

**When to use this**
If academic staff want to dissolve a class in the ClassIn app but aren't the head teacher of that class, they can't do so from within the app. In that case, they can log into the Admin Console, find the class, and end it there. Once a class is ended, its corresponding class in the ClassIn app is also dissolved.

"Ending" a class in the Admin Console and "dissolving" it in the app refer to the same action — doing one automatically does the other. However, a class can't be ended if it still has sessions that haven't started or haven't ended yet. Once a class is ended, students and teachers can no longer communicate via the class group chat, but this doesn't affect their ability to watch the class's recorded playback videos.

After ending a class, if you want students to keep watching historical playback videos from the class, enable the "Allow content to remain viewable for students who've left the class or after the class ends" setting.

Classes cannot be deleted — only ended.

**(1) End a single class**
1. Go to Class Management in the left navigation.
2. Find the class and click "End Class" on the right.

**(2) Bulk-end classes**
1. Select multiple classes, click Bulk Actions, then select "Bulk End Class."
