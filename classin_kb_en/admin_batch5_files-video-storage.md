---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: Admin Console Tutorials
subcategory: Files, Video & Storage Management
batch: 9 of N (Admin Console category, batch 5)
translated_from: zh-CN (consolidated knowledge base)
---

# Admin Console: Files, Video & Storage Management

<!-- DOC_BOUNDARY -->
```yaml
title: "Allowing Forwarding, Saving, and Downloading of Org Cloud Drive Resources in the App"
source_title_zh: "允许用户在软件中转发、保存和下载组织云盘资源"
```

## Allowing Forwarding, Saving, and Downloading of Org Cloud Drive Resources in the App

### Who this applies to
- The Admin Console primary account
- Sub-accounts with "Org Cloud Drive" access

### Related articles
- "Saving Courseware"
- "Adding Sub-accounts in the Admin Console"

### Steps
1. Log into the Admin Console.
2. Go to Org Cloud Drive in the left navigation.
3. Open the org folder.
4. Select the courseware you want to allow/restrict forwarding, saving, or downloading for.
5. Click "Allow Forward/Save/Download" or "Disallow Forward/Save/Download" at the top.

<!-- DOC_BOUNDARY -->
```yaml
title: "Expanding Storage Capacity"
source_title_zh: "扩容存储空间"
```

## Expanding Storage Capacity

### Who this applies to
- The Admin Console primary account

### When to use this
When the console's remaining storage is running low, the primary account can expand storage capacity from the Admin Console — ensuring whiteboard notes, courseware, and class files auto-saved during class continue to save normally.

### Overview
Available storage plans: 100GB/year and 1000GB/year. Supported payment methods: WeChat Pay, Alipay, PayPal, Stripe.

### Steps
1. Log into the Admin Console.
2. Go to Data Overview in the left navigation.
3. Click "Expand."
4. Choose a storage plan and complete payment.

<!-- DOC_BOUNDARY -->
```yaml
title: "Storage Data Overview"
source_title_zh: "存储数据概览"
```

## Storage Data Overview

### What is "Data Overview"?
"Data Overview" refers to storage usage across various data types in the ClassIn Admin Console — including school files, class monitoring/recording data, class files, course attachments, and more.

### Who this applies to
- The Admin Console primary account
- Sub-accounts with "Data Overview" access

### Overview
The Admin Console has a "Data Overview" section that lets you see the current storage status across all data types — such as school files, class monitoring/recordings, and class files — including how much storage capacity each occupies and the percentage of total capacity used, helping you better understand your storage usage.

### Related articles
- "Expanding Storage Capacity"
- "Adding Sub-accounts in the Admin Console"

### Steps
1. Log into the Admin Console.
2. Go to Data Overview in the left navigation.

<!-- DOC_BOUNDARY -->
```yaml
title: "Enabling/Disabling Whiteboard & Courseware Retention"
source_title_zh: "开启关闭“板书课件留存”"
```

## Enabling/Disabling Whiteboard & Courseware Retention

### Who this applies to
- The Admin Console primary account
- Sub-accounts with "School Settings" access

### Overview
When Whiteboard & Courseware Retention is enabled, if a certain amount of content is written on the whiteboard or on courseware during class, the resulting whiteboard notes — along with any annotated PPT, PDF, Word (docx/doc), or Epub courseware (including files that org cloud drive settings allow saving/downloading) — are automatically saved as PDFs in the session list. Both teachers and students can see them, and teachers can share them via link outside of ClassIn.

Retained whiteboard/courseware content uses storage space, and enabling this feature may incur charges. Already-generated content can be deleted from the Admin Console.

### Related articles
- "Adding Sub-accounts in the Admin Console"

### Steps
1. Log into the Admin Console.
2. Go to School Settings in the left navigation.
3. Go to Courseware & Whiteboard Retention at the top.
4. Enable or disable "auto-retain whiteboard notes / annotated courseware" under Whiteboard & Courseware Retention.

<!-- DOC_BOUNDARY -->
```yaml
title: "Auto-Deleting Storage Resources"
source_title_zh: "自动删除存储资源"
```

## Auto-Deleting Storage Resources

### Who this applies to
- The Admin Console primary account
- Sub-accounts with "School Settings" access

### Overview
Academic staff can set an auto-deletion time range in the Admin Console. Once enabled, the console will each day delete class recordings (class playback videos), class monitoring screenshots, course recording attachments, assignment attachments, quiz answer sheet attachments, discussion attachments, class files, learning material attachments, and check-in attachments that have just reached the deletion threshold.

For example, with "auto-delete recordings older than 3 months" enabled: on October 11, the system deletes recordings from July 11; on October 12, it deletes recordings from July 12; and so on. At the end of November (the 30th), it will auto-delete recordings from the last few days of August (the 30th and 31st).

Notes:
1. Uploaded "class recordings (playback videos)" have their storage duration calculated based on the session's start date.
2. Resources with protection lock enabled will not be deleted.
3. When auto-deletion is enabled, resources that have already exceeded the selected number of months won't be automatically deleted retroactively. To delete older resources, create a deletion task under "Delete Historical Storage Resources," or delete manually under "Class Monitoring/Recording" or "Course Resources."

### Related articles
- "Deleting Historical Storage Resources"
- "Adding Sub-accounts in the Admin Console"

### Steps
1. Log into the Admin Console.
2. Go to School Settings in the left navigation.
3. Go to Storage Settings at the top.
4. Under "Set Auto-Delete Storage Resources," enable or disable auto-deletion and set the deletion time range.

<!-- DOC_BOUNDARY -->
```yaml
title: "Public / Personal Authorized Resources"
source_title_zh: "公共个人授权资源"
```

## Public / Personal Authorized Resources

### I. Public authorized resources

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Teacher Management" access

**Overview**
In Teacher Management, use the top-right button to enable or disable public authorized resources for all teachers. To manage this individually for one teacher, search for them and toggle the setting on their row — this only affects that teacher's own setting. The top-right corner also offers an option to customize public authorized resources, with up to 40 folders. Once customized and enabled, authorized teachers can view and open files from the public authorized resources in IM, the classroom, the lesson-prep room, and the whiteboard.

**Notes**
- Deactivated teachers cannot view any files in the school's cloud drive.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Teacher Management in the left navigation.
3. Enable or disable public authorized resources.
4. Use the top-right corner to customize public authorized resources.

### II. Personal authorized resources
In Teacher Management, search for a teacher and configure their personal authorized resources on their row — up to 40 folders. A teacher with personal authorized resources set can view and open those files in IM, the classroom, the lesson-prep room, and the whiteboard.

**Steps**
1. Customize personal authorized resources next to the teacher's name.

<!-- DOC_BOUNDARY -->
```yaml
title: "Class Files, Attachments & Co-Creation Management"
source_title_zh: "班级文件、附件、共创管理"
```

## Class Files, Attachments & Co-Creation Management

### I. Preventing course attachments and class files from being deleted

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Resources" access

**When to use this**
Academic staff can enable a protection lock for a class's "course attachments," "class files," and "class co-creation" content in the Admin Console. Once locked, this content cannot be deleted — even via a deletion task or "delete by time range" — protecting against accidental deletion caused by mistakes or mismanagement.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Resources in the left navigation.
3. Find the class.
4. Click "Protection Lock" on the right (green lock = protection enabled; gray lock = protection disabled).

### II. Deleting course attachments and class files
To avoid using unnecessary storage space, you can delete "course attachments," "class files," or "class co-creation" content you no longer need to keep in a class.

**Notes**
- Deleting "course attachments," "class files," or "class co-creation" content in the Admin Console also deletes the corresponding content in the class within the ClassIn app.

**Steps**
1. Select the course(s).
2. Delete the resources.

<!-- DOC_BOUNDARY -->
```yaml
title: "Deleting Historical Storage Resources"
source_title_zh: "删除历史存储资源"
```

## Deleting Historical Storage Resources

### What is "Deleting Historical Storage Resources"?
This feature lets academic staff create a deletion task in the Admin Console for a specific time range. The task will permanently delete class recordings (playback videos), monitoring screenshots, course recording attachments, assignment attachments, quiz answer sheet attachments, discussion attachments, class files, learning material attachments, and check-in attachments from within that time range.

### Who this applies to
- The Admin Console primary account
- Sub-accounts with "School Settings" access

### When to use this
This feature is mainly used to delete the above resource types within a specific date range, to avoid unnecessary storage costs or space usage. It can also help ensure the security and confidentiality of class data.

### Overview
Deletion tasks take effect within 24 hours of creation — you can check task history for the latest status. Tasks that haven't started yet can be canceled.

- Resources with protection lock enabled will not be deleted.
- You cannot create a new deletion task while another one is pending (not started or in progress).
- Deletion tasks cannot be created on the last day of the month (Beijing time).

### Notes
- Deleting "class recordings (playback videos)" affects whether teachers and students can watch the playback for the corresponding session(s).

### Related articles
- "Auto-Deleting Storage Resources"
- "Adding Sub-accounts in the Admin Console"

### Steps
1. Log into the Admin Console.
2. Go to School Settings in the left navigation.
3. Go to Storage Settings at the top.
4. Under "Delete Historical Storage Resources," create a deletion task.

<!-- DOC_BOUNDARY -->
```yaml
title: "Recordings, Monitoring Screenshots & Whiteboard Courseware Management"
source_title_zh: "录课视频、监课图片和板书课件管理"
```

## Recordings, Monitoring Screenshots & Whiteboard Courseware Management

### I. Preventing recordings, monitoring screenshots, and whiteboard courseware from being deleted

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Resources" access

**When to use this**
Academic staff can enable a protection lock for a session's [Monitoring Screenshots], [Recordings], and [Whiteboard Courseware] in the Admin Console. Once locked, these cannot be deleted — even via a deletion task or "delete by time range for playback videos and monitoring screenshots" — protecting important recordings, screenshots, and whiteboard courseware from accidental deletion due to mistakes or mismanagement.

**Overview**
Once locked [Monitoring Screenshots], [Recordings], and [Whiteboard Courseware] exceed the 3-month free storage period, storage fees will automatically be deducted from your Admin Console balance. See "Billing Rules" under "Finance Overview" for details.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Resources in the left navigation.
3. Find the session.
4. Click "Protection Lock" on the right (green lock = protection enabled; gray lock = protection disabled).

### II. Deleting recordings, monitoring screenshots, and whiteboard courseware
Requires a sub-account with "Session Resources" access.

"Recordings (class playback videos)," "monitoring screenshots," and "whiteboard courseware" stored in the Admin Console for more than 3 months incur storage fees. To avoid unnecessary charges, you can delete recordings, screenshots, or whiteboard courseware you don't need to keep.

**Notes**
- Deleting a "recording (class playback video)" in the Admin Console affects whether teachers and students can watch that session's playback. Once deleted, the recording can no longer be watched — neither in the ClassIn app nor via a web playback link.

**Steps**
1. Go to Session Resources in the left navigation.
2. Select the session(s).
3. Click "Delete Screenshots," "Delete Recording," or "Delete Whiteboard Courseware" (or click "Delete Session Resources" to delete all resources for that session at once).

<!-- DOC_BOUNDARY -->
```yaml
title: "Recording Management"
source_title_zh: "录课视频管理"
```

## Recording Management

### I. Uploading a playback video

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Class Resources" access

**When to use this**
If the teaching teacher can't record the class themselves but wants to preserve the session for students to watch later, a co-teacher in the classroom can enable local recording. If there's no co-teacher, academic staff can enter the corresponding classroom via the Class Monitoring page in the Admin Console and enable local recording there. After class ends, the co-teacher's or staff's locally recorded video can be uploaded to the "Class Playback Video" storage location for that session, creating a playback video.

**Notes**
- Videos can't be uploaded for a session that didn't have recording enabled.
- The Admin Console only supports uploading MP4 videos encoded with H.264. Incorrect encoding may result in audio-only playback with no video. Non-MP4 files may fail to play.
- The maximum supported resolution for uploaded videos is 1080p — videos above 1080p may fail to play.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Class Resources in the left navigation.
3. Find the session using filters, then go to Recording on the right.
4. Upload the playback video.

### II. Downloading a playback video

**(1) Downloading a playback video**

Academic staff can download a "class playback video" from the Admin Console to save it locally or share it with others. Staff can also download the video locally first, then delete it from the Admin Console to save on storage costs.

**Steps**
1. Download the playback video.

**(2) Bulk downloading playback videos**

1. Download the browser extension below.
2. Locate the "classin-download-help-2.1.1-chrome" archive on your computer.
3. Right-click the "classin-download-help-2.1.1-chrome" archive and choose "Extract to \"classin-download-help-2.1.1-chrome\" (C)".
4. Open Google Chrome, click the three-dot menu in the top-right corner.
5. Click "Add to Chrome" from the relevant link, then "Add Extension," then go to Extensions > Manage Extensions.
6. Enable "Developer mode" in the top-right, click "Load unpacked" in the top-left, and select the extracted "classin-download-help-2.1.1-chrome" folder.
7. Open the ClassIn recording video data page.
8. Click the Extensions icon in the top-right.
9. Click "classin-download-help-2.1.1," then bulk-download the videos.

### III. Deleting a playback video
If a teacher's recording is repeatedly interrupted or unstable during class, a co-teacher can enable local recording in the classroom, or academic staff can enter the classroom via the Admin Console to monitor and enable local recording. After class ends, staff can upload the locally recorded video to the corresponding session's "Class Playback Video" storage location, then delete the incomplete video that was recorded during the original session.

**Steps**
1. Delete the playback video (once deleted, a playback video cannot be recovered — proceed carefully).

<!-- DOC_BOUNDARY -->
```yaml
title: "Org Cloud Drive Management in the Admin Console"
source_title_zh: "后台组织云盘管理"
```

## Org Cloud Drive Management in the Admin Console

### I. Creating folders / uploading courseware

**What is the Org Cloud Drive?**
The Org Cloud Drive feature in the Admin Console and the ClassIn app are synced with each other. When a user creates an org cloud drive folder and uploads courseware in ClassIn, it automatically syncs to the school's Org Cloud Drive in the Admin Console. Conversely, when academic staff upload courseware and add org members via the Admin Console, those members can see the courseware after logging into ClassIn and opening the school's Org Cloud Drive.

Admins can create various folders and subfolders in the Org Cloud Drive, add members, and set member permissions. This turns each folder into a small shared collaboration space — for example, an "English Department" or "Grade 1" folder. This makes file sharing and management easier, and improves efficiency for file authorization and management at the school or organization level.

Through the Org Cloud Drive, teachers can more easily share, collaborate on, and manage teaching materials, fully supporting collaborative teaching needs. This significantly improves both file management convenience and teaching efficiency.

**Who this applies to**
- The Admin Console primary account
- Sub-accounts with "Org Cloud Drive" access

**Overview**

(1) Supported file formats that can be opened in the classroom:

- ClassIn whiteboard format: edb
- ClassIn file formats: edt, edu, eda, edv
- Presentation formats: pptx, ppt, pptm, pptippt
- Document formats: docx, doc
- Spreadsheet formats: xlsx, xls, csv
- PDF format: pdf
- Epub format: epub
- Image formats: jpeg, jpg, png, bmp
- Audio formats: mp3, wav, wma, aac, flac, m4a, oga, opus
- Video formats: mp4, 3gp, mpg, mpeg, 3g2, avi, flv, wmv, h264, m4v, mj2, mov, ogg, ogv, rm, qt, vob, webm
- Text document formats: txt, html, htm, css, js, as, cpp, c, cc, cxx, h, java, md, matlab, pascal, pl, php, py, r, rb, ru, sql, swift, rbx, rs, go
- Go (weiqi) format: sgf
- Chess/Xiangqi formats: fen, pgn

**Notes**
- The Org Cloud Drive feature is only available on the "Enterprise Edition" and "School Edition" of the ClassIn Admin Console.

**Related articles**
- "Adding Sub-accounts in the Admin Console"

**Steps**
1. Log into the Admin Console.
2. Go to Org Cloud Drive in the left navigation.
3. Click "Create Folder" in the top-left.
4. Name the folder and click Confirm.
5. Open the newly created folder.
6. Use the top-left to upload local courseware or folders.

### II. Adding members / editing member permissions
Requires a sub-account with "Org Cloud Drive - Member Management" access.

| Permission | Description |
| --- | --- |
| Can Manage | Can add, authorize, and remove members; can upload, delete, rename, forward, and use files. |
| Can Operate | Can upload, create, and use files, but cannot delete them. |
| View Only | Can preview files and use them in the classroom, but cannot upload, create, or delete them. |
| No Access | Cannot view files. |

- "Enterprise Edition" Admin Console can only add teachers from within the organization.
- "School Edition" Admin Console can add both teachers and students from the school as org folder members (students currently only support "View Only" permission).
- In the Admin Console, deactivating a teacher automatically revokes their Org Cloud Drive permissions. If a deactivated teacher is later reactivated, they'll need to be added again following the new-member permission process to regain access.

**Steps**
1. Find the folder you want to add members to, click "···" on the right, then select "Member Management."
2. Click "Add Member."
3. After adding members, adjust their permissions from the member management window.

### III. Downloading courseware
Requires a sub-account with "Org Cloud Drive - Download" access.

Supports bulk downloading of courseware.

**Steps**
1. Open the org folder.
2. Select the courseware to download.
3. Click "Download" at the top.

### IV. Copying courseware
Supports bulk copying of courseware.

**Steps**
1. Select the courseware to copy.
2. Click "Copy" at the top.
3. Choose the destination path.

### V. Moving courseware
Supports bulk moving of courseware.

**Steps**
1. Select the courseware to move.
2. Click "Move" at the top.
3. Choose the destination folder.

### VI. Enabling/disabling forward/save/download for courseware in the app
Supports bulk enabling or disabling of "forward/save/download" permission.

**Steps**
1. Select the courseware.
2. Click "Allow Forward/Save/Download" or "Disallow Forward/Save/Download" at the top.

### VII. Deleting courseware
Requires a sub-account with "Org Cloud Drive - Delete" access.

Supports bulk deletion of courseware.

**Steps**
1. Select the courseware to delete.
2. Click "Delete" at the top.
