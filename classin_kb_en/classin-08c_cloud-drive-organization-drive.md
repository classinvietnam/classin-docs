---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: ClassIn (Client)
subcategory: "8. Cloud Drive Space (Part 3: Organization Cloud Drive)"
batch: 32 of N
translated_from: zh-CN (source: ClassIn/8._云盘空间/组织云盘（文件上传等相关操作）.md)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 8. Cloud Drive Space (Part 3: Organization Cloud Drive)

<!-- DOC_BOUNDARY -->
```yaml
title: "Organization Cloud Drive (File Upload and Related Operations)"
source_title_zh: "组织云盘（文件上传等相关操作）"
```

## Organization Cloud Drive (File Upload and Related Operations)

## I. Creating a New Organization Drive

## Applies to
The school/institution's primary account.

Backend school/institution administrators with "Organization Cloud Drive" permission.

## When to use this
During teaching research, multiple teachers on a research team often need to share materials and collaborate. Using the Organization Cloud Drive meets this need. Beyond what My Cloud Drive offers, the Organization Cloud Drive also provides a space for multiple people to share and build together.

## Usage Notes
The school/institution's primary account, and backend school/institution administrators with "Organization Cloud Drive" permission, can create an organization drive under "Organization Cloud Drive" in the "Space" section of the ClassIn software. Once the organization drive is created, files and subfolders can be added to it.

## Notes
Phone does not support creating an organization drive within the Organization Cloud Drive.

## Steps

#### Computer/Tablet
1. Go to Space in the left navigation.
2. Go to Organization Cloud Drive.
3. Select the school/institution.
4. Create an organization drive.
5. Enter the organization drive's folder name.
6. Click Create.

<!-- DOC_BOUNDARY -->
```yaml
title: "Creating/Uploading Files (Folders)"
source_title_zh: "新建/上传文件(文件夹)"
```

## II. Creating/Uploading Files (Folders)

Teachers with operate/manage permission for a folder.

Teachers, administrators, and primary account holders with the relevant permission can create/upload folders and files under the organization drive, and can also upload files from My Cloud Drive to the organization drive.

The organization drive supports creating new folders, as well as new whiteboards, assignment resources, online PPTs, collaborative documents, and other file types. Tablet does not support creating a new online PPT. Phone only supports creating folders, whiteboards, assignment resources, and collaborative documents. Only computer supports uploading a folder.

The organization drive also supports uploading files, such as PPT, Word, PDF, images, audio, and video.

ClassIn has certain limits on uploaded file size: when uploading from a computer, a single file cannot exceed 500MB; when uploading from a phone or tablet, a single file cannot exceed 100MB. For TXT files, we recommend a size under 1MB to ensure normal use in the classroom. In addition, for video files uploaded from a phone or tablet: videos below 720p resolution cannot exceed 100MB, and videos above 720p resolution cannot exceed 3 minutes in length.

The total folder limit is 2,000, and each folder is limited to 300 files.

On computer, you can drag and drop files and folders to upload them to My Cloud Drive.

Uploaded files need some time to convert — we recommend uploading in advance.

To use a file in the classroom, it must be opened from the cloud drive within the classroom.

Any file format can be uploaded to ClassIn, but only the file formats listed below can be opened and used normally in the classroom.

The file types supported for use in the ClassIn classroom are as follows:

| Type | Formats |
| --- | --- |
| ClassIn Whiteboard | edb |
| ClassIn Files | edt, edu, edx, eda, edv |
| PowerPoint Presentations | pptx, ppt, pptm |
| Word Documents | docx, doc |
| Excel Spreadsheets | xlsx, xls, csv |
| PDF Documents | pdf |
| Images | jpeg, jpg, png, bmp |
| Audio | mp3, wav, wma, aac, flac, m4a, oga |
| Video | mp4, 3gp, mpg, mpeg, 3g2, avi, flv, wmv, h264, m4v, mj2, mov, ogg, ogv, rm, qt, vob, webm |
| Text Documents | txt, html, htm, css, js, as, cpp, c, cc, cxx, h, java, md, matlab, pascal, pl, php, py, r, rb, ru, sql, swift, rbx, rs, go |
| Go (board game) | sgf |
| Chess/Xiangqi | fen, pgn |

1. Go to the organization drive.
2. Click Upload or New at the top to create a folder or file.

#### Phone
1. Go to Space.
2. Go to Organization Space.
3. Click "+".
4. Create a folder/file, or Upload a file.

<!-- DOC_BOUNDARY -->
```yaml
title: "Member Permissions"
source_title_zh: "成员权限"
```

## III. Member Permissions

Backend school/institution administrators with "Organization Cloud Drive — Member Management" permission.

Teachers with manage permission for a folder.

Teachers, administrators, and primary account holders with the relevant permission can add and set members and manage permissions for the organization drive and its subfolders. Members with the appropriate permission can view and use files under the organization drive.

**Member management permission levels for the organization drive and its subfolders:**

| Permission | Description |
| --- | --- |
| Manage | Folder support: setting member management permission (adding, authorizing, and removing members), and uploading, creating, duplicating, moving, renaming, and deleting folders under the organization drive.<br><br>File support: viewing, uploading, creating, forwarding, downloading, deleting, duplicating, moving, saving to cloud drive, renaming, printing, and online-editing PPT/edoc files, plus enabling the file-transfer feature under file permissions. |
| Operate | Folder support: viewing member management permission, and uploading, creating, duplicating, and renaming folders under the organization drive.<br><br>File support: viewing, uploading, creating, duplicating, renaming, printing, and online-editing PPT/edoc files.<br><br>Supports deleting files and folders they uploaded/created themselves. |
| View Only | Only supports viewing the folder and its files. |
| Not Visible | Cannot view the folder or its files. |

**Super Admin:** refers to a backend school/institution administrator with "Organization Cloud Drive" permission. In the Backend Management System, an administrator who only has "Organization Cloud Drive" checked can view, create, and rename organization drives, and view member management, in both the backend and the organization cloud drive in the ClassIn software — but cannot delete folders, nor set folder member permissions. For files, they can view, upload, create, forward, duplicate, move, save to cloud drive, rename, print, and online-edit PPT/edoc files, but cannot download or delete files, nor enable the file-transfer feature.

Additional permissions must be checked separately to: delete files/folders and enable file transfer ("Organization Cloud Drive — Delete"); download files ("Organization Cloud Drive — Download"); set member permissions for the organization drive/folders ("Organization Cloud Drive — Member Management").

Phone does not support viewing or setting member management permission (adding, authorizing, removing members) in the Organization Cloud Drive.

"Enterprise Edition ClassIn" can only add teachers within the same organization.

"School Edition ClassIn" can add both teachers and students from the school as organization folder members (students currently only support being set to "View Only" or "Not Visible" permission).

In the "Backend Management System," a deactivated teacher automatically has their organization cloud drive permission revoked; once reactivated, they must go through the new-member process again to regain access.

For schools using the "K-12 Backend Management System," when a teacher leaves/is deleted, or a student graduates/is deleted, the system automatically revokes their organization cloud drive permission; if a former teacher returns, or a student re-enrolls, they must go through the new-member process again to regain organization cloud drive access.

1. Find the folder you want to grant permission for, then click "···" on the right.
2. Go to Member Management.
3. Add a member, or edit member permissions.

<!-- DOC_BOUNDARY -->
```yaml
title: "File Permissions"
source_title_zh: "文件权限"
```

## IV. File Permissions

Backend school/institution administrators with "Organization Cloud Drive — Delete" permission.

If a teacher, administrator, or primary account holder with the relevant permission enables "Allow Operate/View-Only Members to Forward/Download/Save to Personal Cloud Drive" (transfer permission) for a file, members with "Operate" or "View Only" permission can also transfer that file out.

Collaborative documents (edoc), edu, edx, assignment resources, and similar files do not support setting transfer permission.

Phone does not support viewing or setting the file-transfer feature in the Organization Cloud Drive.

1. Go into the folder.
2. Find the file, click "···," then go to File Permissions.
3. Edit the file permissions.

<!-- DOC_BOUNDARY -->
```yaml
title: "Forwarding a File"
source_title_zh: "转发文件"
```

## V. Forwarding a File

Requires file permission set to allow transfer, and requires the teacher to have view/operate permission for the folder the file is in.

Teachers, administrators, and primary account holders with the relevant permission can find a file in the ClassIn software's Organization Cloud Drive and forward it to a ClassIn class or friend.

1. Check the file, then click Forward.

<!-- DOC_BOUNDARY -->
```yaml
title: "Saving to Cloud Drive"
source_title_zh: "保存至云盘"
```

## VI. Saving to Cloud Drive

Teachers, administrators, and primary account holders with the relevant permission can find a file in the ClassIn software's Organization Cloud Drive and save it to My Cloud Drive.

1. Find the file, click "···," then click Save to Cloud Drive.
2. Choose a save path, then click Confirm.

Select the file.
Click Save to Cloud Drive.
Choose a save path, then click Save.

<!-- DOC_BOUNDARY -->
```yaml
title: "Downloading a File"
source_title_zh: "下载文件"
```

## VII. Downloading a File

Backend school/institution administrators with "Organization Cloud Drive — Download" permission.

Computer supports downloading files from the Organization Cloud Drive, such as images, whiteboards, PPTs, PDFs, and Word documents. However, ClassIn's proprietary file formats — such as online slides (eppt format) and documents (edoc format) — cannot be downloaded or opened in other apps.

Phone and tablet support saving images to the local photo album, but for files like PPT and PDF, there's no download feature — you can open them in the Organization Cloud Drive, then tap the share feature to open and view them in another app.

#### Computer
1. Check the file(s) you want to download.
2. Click Download below.

#### Tablet
1. Open the image or file.
2. Press and hold the image to save it, or tap the share button on the file page and choose to open it with another app.

Open the image or file in My Cloud Drive.

<!-- DOC_BOUNDARY -->
```yaml
title: "Printing a File"
source_title_zh: "打印文件"
```

## VIII. Printing a File

When you need to turn a teaching file stored in the "Organization Cloud Drive" into a physical printed document, teachers can use ClassIn's print feature; computer supports printing images, PPTs, PDFs, and similar files.

Phone and tablet do not have a "Print" feature.

1. Open the file.
2. Click Print in the top-right corner of the file.

<!-- DOC_BOUNDARY -->
```yaml
title: "Deleting a File (Folder)"
source_title_zh: "删除文件（文件夹）"
```

## IX. Deleting a File (Folder)

Teachers, administrators, and primary account holders with the relevant permission can find a file (or folder) in the ClassIn software's Organization Cloud Drive and delete it. In addition, a teacher with "Operate" permission can delete a folder they created themselves, and can also delete files they uploaded themselves.

Files and folders cannot be recovered once deleted.

1. Find the file or folder you want to delete.
2. Click Delete.
