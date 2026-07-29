---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: ClassIn (Client)
subcategory: "8. Cloud Drive Space (Part 5: ClassIn File Formats and Types)"
batch: 34 of N
translated_from: zh-CN (source: ClassIn/8._云盘空间/ClassIn_文件格式与类型.md)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 8. Cloud Drive Space (Part 5: ClassIn File Formats and Types)

<!-- DOC_BOUNDARY -->
```yaml
title: "ClassIn File Formats and Types"
source_title_zh: "ClassIn_文件格式与类型"
```

## ClassIn File Formats and Types

## I. ClassIn File Format Overview

| File Format | Purpose | Can Users Create/Develop It? | How to Get Existing Resources |
| --- | --- | --- | --- |
| edb | A whiteboard file made up of images and text | Yes | Space → Resource Center → Featured Zone → EDB Courseware |
| edoc | Collaborative document | Yes | Must be created by the user |
| edoc | Online PPT | Yes | Must be created by the user |
| eda | Classroom extension tool | No | Space → My Cloud Drive → "?" → ClassIn User Guide → Other Classroom Extension Tools |
| edlink | Web link | Yes | Space → Resource Center → Elementary Math → Math Mini-Tools |
| edu | Interactive classroom widget | Can be developed, but not recommended | Not recommended |
| edx | Interactive classroom widget | Yes | Must be created by the user |
| edv | A file opened in the classroom that's visible to the teacher's side but not visible to students | Can be developed, but not recommended | Not recommended |
| edt | Classroom skin | Yes | Must be created by the user |

## II. Files Supported for Opening in the Classroom

All the file formats listed below can be uploaded to your ClassIn cloud drive, and all can be opened in the classroom.

| File Type | Formats |
| --- | --- |
| ClassIn Whiteboard | edb |
| ClassIn Files | edt, edu, eda, edv, edx |
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

## III. Introduction to ClassIn File Types

### 1. EDB Files

#### (1) EDB Overview

An EDB whiteboard file is a ClassIn-exclusive format made up of images and text, on which you can drag, draw, and otherwise mark up courseware content.

#### (2) Creating an EDB Whiteboard File

**Method 1 (create a new EDB whiteboard file):** Space → My Cloud Drive → New Whiteboard.

**Method 2 (edit an EDB whiteboard file):** Space → My Cloud Drive → open the EDB whiteboard file → Edit.

**Method 3:** enter the Whiteboard (no scheduling needed) or the classroom → create/edit the EDB whiteboard file → Save Whiteboard.

**a. Creating an EDB file inside the Whiteboard or classroom**

Use the classroom's mini-tools: select Move/Pen/Text/Eraser/Screenshot/Load Local Image, and so on.

Use standard shortcuts to quickly copy and paste an image: Copy: Ctrl+C; Paste: Ctrl+V.

**b. Saving an EDB file inside the Whiteboard or classroom**

When a teacher needs to save whiteboard content they just edited, click the toolbox's "Save/Share Whiteboard" to save it, or share it with a friend.

When saving a whiteboard, you can change the background color (transparent is supported).

When saving a whiteboard, you can choose from three file formats — edb/png/pdf. Multiple formats can be selected when saving locally; only one format can be selected when saving to the cloud drive.

### 2. EDOC Files

#### (1) EDOC Overview

EDOC is a document format ClassIn provides for collaborative editing within ClassIn. It can be used for teaching-research lesson prep, or for collecting information. Opening an EDOC document in the classroom does not support marking it up with the pen or text tools.

#### (2) Ways to Create an EDOC

**Method 1 (create a new collaborative document):** Space → My Cloud Drive → New → Collaborative Document. You can find it in My Cloud Drive, and share it with a ClassIn friend or class.

**Method 2 (create a new collaborative document):** Inside the classroom → Toolbox → Collaboration → Document. This also creates an EDOC, and you can authorize students, temporarily granting them collaborative editing permission.

**Method 3 (edit a collaborative document online):** Space → My Cloud Drive → open a Word file → click Online Edit.

#### (3) Adding Comments Within an EDOC

Within an EDOC, click the "+" in the document to add a comment.

### 3. EPPT Files

#### (1) EPPT Overview

EPPT is a PPT format ClassIn provides for editing within ClassIn. It can be used during teaching-research lesson prep.

#### (2) Ways to Create an EPPT

**Method 1 (create a new online PPT):** Space → My Cloud Drive → New → Online PPT. You can find it in My Cloud Drive, and share it with a ClassIn friend or class.

**Method 2 (edit an uploaded PPT):** Space → My Cloud Drive → open the PPT → click Online Edit.

### 4. EDA Files

#### (1) EDA Overview

EDA files are a category of classroom extension tools developed by ClassIn and provided as a shared resource for users. There are currently four: Go, Minesweeper, Tug of War, and Sudoku. Once authorized, students can operate them.

#### (2) Where to Find EDA Files

Space → My Cloud Drive → "?" in the bottom-right corner → ClassIn User Guide → Other Classroom Extension Tools.

### 5. EDLINK Files

#### (1) EDLINK Overview

EDLINK is a web link. Compared to saving a link in a browser, EDLINK can be uploaded to the cloud drive and forwarded; in the classroom, only the teacher role can operate it, while the teaching assistant role and student role can watch it being used.

#### (2) How to Create an EDLINK

Create a new TXT text file locally on Windows (Notepad file format).

Open the TXT file and paste in the URL (just enter the URL itself).

Save the TXT file as a different name, choosing "All Files" as the save type, and enter ".edlink" as the file extension.

After locating the file locally, right-click it and check Properties to confirm the file type shows as EDLINK.

Upload the local EDLINK file to Space → My Cloud Drive in ClassIn — it can then be opened.

### 6. EDU Files

#### (1) EDU Overview

An EDU file is a special file that contains a website address. When a teacher opens an EDU file during class, both the teacher and every student in the classroom will independently open that website address through their own browser. This way, every student can browse and use the website on their own, without interfering with each other. EDU files are typically used in scenarios such as:

**Surveys/questionnaires:** the teacher can distribute a survey or exam to each student and collect each student's responses.

**Self-paced practice:** students can use a self-testing practice website to practice independently. EDU files support audio, allowing students to do speaking and listening practice.

#### (2) How to Create an EDU

**Step 1:**

Get the URL of the website you'll need during class.

Using NoBook as an example of how to get the URL:

a. Visit the "NoBook" official website: https://www.nobook.com/index.html, and register a new account or log into an existing one.

b. From Premium Experiments, select one that requires students to do hands-on operation during class.

Note: if some students don't have a paid NoBook account, choose a free experiment so students aren't blocked by permission restrictions.

c. Click the selected experiment, then use the share button to get that NoBook experiment's share URL.

d. Open the share URL in a browser — it will redirect, giving you the experiment's actual website address.

Note: if the URL doesn't open properly in an EDU file, try removing the trailing "=" character from the address, then try opening it in EDU again.

Using Wenjuanxing (a survey tool) as an example of how to get the URL:

a. Visit the "Wenjuanxing" official website at www.wjx.cn, and register a new account or log into an existing one.

b. After logging in, start creating a survey.

c. Click the option you need to add questions, or click "Bulk Add Exam Questions" on the right.

d. Once you've finished editing the exam paper, click Finish Editing.

e. Once the paper is edited, click Distribute Survey.

f. Click the "Copy" button to copy the link — this gives you the Wenjuanxing website address.

**Step 2:**

Create a new EDU file, and fill in the file's name and website address.

Note: once created, open the file within "ClassIn Classroom → Space → My Cloud Drive" to check whether the website address is correct.

**Step 3:**

During a formal class, the teacher can open this EDU file from the cloud drive; each student's device will then independently open that website address for self-paced practice.

Note: if the website requires login before students can practice, we recommend scheduling a trial session first so students have enough time to log in — once logged in on a device, they won't need to log in again afterward.

**Step 4:**

While students practice independently, they won't affect one another and can complete their own tasks on their own.

Teachers cannot see students' progress within the ClassIn classroom. If the website has its own data-tracking feature (such as survey statistics), you can view the data directly in that website's backend.

Teacher-side view.

Student A's view.

Student B's view.

### 7. EDV Files

#### (1) EDV Overview

EDV is a courseware format opened within the classroom. Unlike other courseware formats, EDV is only visible to the teacher — it's not visible on the student side (neither the window nor its content).

#### (2) EDV Usage Notes

Teachers upload the EDV file to Space → My Cloud Drive, then open it to view it there.

### 8. EDX Files

An EDX file is a special file that contains a website address. When a teacher opens an EDX file during class, it launches the Multi-Directional Browser to open the URL inside the file; the way students and the teacher interact with it is the same as when the teacher opens the Multi-Directional Browser tool directly.

#### (2) How to Create an EDX

Get the URL of the website you'll need during class — for example, www.eeo.cn.

Create a new EDX file, and fill in the file's name and the website address.

Note: once created, you can open it directly for a preview to check whether the webpage displays correctly.

During a formal class, the teacher can open this EDX file from Space → My Cloud Drive; once opened, class can proceed exactly as with the Multi-Directional Browser.

Note: within the classroom, this file type can only be opened by the teacher — no other role has permission to open it. Outside the classroom, there's no such restriction, and it can be previewed normally.

Student-side view is as follows.

### 9. EDT Files

#### (1) EDT Overview

EDT is used for the skin background of the ClassIn classroom; only 1280 x 720 pixel JPG or JPEG images with no transparency channel are supported, saved in EDT format.

#### (2) How to Create an EDT

Open a 1280 x 720 pixel JPG or JPEG image with no transparency channel in an image-editing tool.

Save it as a different name, choosing JPEG as the save type, and enter ".edt" as the file extension.

After locating the file locally, right-click it and check Properties to confirm the file type shows as EDT.

Upload the local EDT file to Space → My Cloud Drive in ClassIn — it can then be opened in the classroom.
