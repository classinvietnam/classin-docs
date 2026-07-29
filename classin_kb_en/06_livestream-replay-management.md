---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: Backend Management System
subcategory: "6. Live Stream & Playback Management"
batch: 3 of N
translated_from: zh-CN (source: 管理后台/6._直播回放管理)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 6. Live Stream & Playback Management

<!-- DOC_BOUNDARY -->
```yaml
title: "Interaction Settings"
source_title_zh: "互动设置"
group: true
```

## Interaction Settings

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream/Playback Settings: Allow Likes from Unregistered Users"
source_title_zh: "网页直播回放设置：未登录用户也可点赞"
```

## Web Live Stream/Playback Settings: Allow Likes from Unregistered Users

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Live Stream & Playback" permission

### When to use this
To prevent inappropriate remarks from viewers of the web live stream, the Backend Management System disables "Allow unregistered users to chat and like during the live stream" by default. If teaching staff want everyone watching the web live stream to be able to chat and like freely, they can enable "Allow unregistered users to chat and like during the live stream" in the Backend Management System. Once enabled, all users watching the web live stream can chat and like freely, whether or not they are logged into a ClassIn account.

### Usage Notes
This setting only takes effect for the web live stream of the specific lesson (class session) that was modified.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to Live Stream & Playback in the left navigation.
3. Find the lesson and click Manage on the right.
4. Go to Live Stream Settings.
5. Turn "Allow unregistered users to chat and like" on or off.
6. Click Save.

![](https://cofile.eeo.cn/res-store%2Fdffe194d68fb8402ecfa41589a9666b6c7ac48061ab6eb4d091fff27619c2b50_335538?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=533c55c1e9daa24d9688f651933d7a55d7312ba6)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream Mute"
source_title_zh: "网页直播禁言"
```

## Web Live Stream Mute

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Live Stream & Playback" permission

### When to use this
When teaching staff notice that a particular user has posted inappropriate remarks in the web live stream, they can enable "Mute All" in the web live stream settings of the Backend Management System to stop that user from continuing to post inappropriate content.

### Usage Notes
Enabling or disabling the web live stream chat mute feature only takes effect for the specific class session (lesson) it was set on.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to Live Stream & Playback in the left navigation.
3. Find the lesson.
4. Turn "Mute All" on or off.

![](https://cofile.eeo.cn/res-store%2F6924eed6228f7080b88b97966def6ada83b664de1893acf28c12cd023e7013a0_458073?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=de27222e5786a3f4856f4507ece2def12de97171)

<!-- DOC_BOUNDARY -->
```yaml
title: "Data & Display"
source_title_zh: "数据与展示"
group: true
```

## Data & Display

<!-- DOC_BOUNDARY -->
```yaml
title: "Live Stream/Playback \"Prompt Message\""
source_title_zh: "直播回放“提示语”"
```

## Live Stream/Playback "Prompt Message"

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can set custom prompt messages for the web live stream in the Backend Management System. There are three modes: the first is the prompt shown before the teacher has entered the classroom or started recording; the second is the prompt shown if the teacher exits the classroom partway through; and the third is the prompt shown when web live stream permission has not been enabled for the lesson. Each type of prompt has a default message and a custom message. To set a custom message, click "Edit" under the relevant prompt type, enter the new text, save it, and then check the box to activate the newly added custom prompt.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Web Live Stream & Playback at the top.
4. Set the custom prompt in "Web Live Stream & Playback Prompt Customization."

![](https://cofile.eeo.cn/res-store%2F3afc7d0854a018b7d7058cf0d71208076de122f0da6303c490acbd9b82cc932a_919445?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a8b0f1d32c7dbd5662f64b81710d2ee7f8d22f34)

<!-- DOC_BOUNDARY -->
```yaml
title: "Live Stream/Playback Data"
source_title_zh: "直播回放数据"
```

## Live Stream/Playback Data

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Lesson Management" and "Live Stream & Playback" permissions

### When to use this
Teaching staff can view or download the web live stream and web playback data for a class session on the "Live Stream Management & Data" page of the Backend Management System.

The upper part of the page shows the overall web live stream data for the class session, including: total number of viewers, total number of views, current number of concurrent viewers, peak concurrent viewers, number of RSVPs for the live stream, number of RSVPed users who actually watched, number of viewers who watched while logged in, number of viewers who liked, number of chat participants, total number of chat messages, average number of chat messages per viewer, number of muted viewers, and total number of viewers who clicked on livestream shopping products.

The bottom of the page shows detailed information for each user who watched the web live stream or playback, including: the viewer's account (shown as a garbled string if not logged in), the viewer's nickname (also garbled if not logged in), whether the user RSVPed for the web live stream, whether the user was logged into a ClassIn account while watching, how many times the user watched, the total watch duration, whether the user watched live or watched the playback after the stream ended, the time of each viewing session, the entry time for each viewing session, the watch duration for each session, the IP address used for each session, the device type used for each session, whether the user liked during the live stream, how many chat messages the user sent, the content of those chat messages, whether the user was ever muted, whether the user clicked to view any shopping products, and if so, which specific product(s) were clicked.

### Notes
If "Web Live Stream" or "Web Playback" was not selected when the lesson was created, the lesson will not appear under "Live Stream & Playback" in the Backend Management System.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to Live Stream & Playback in the left navigation.
3. Find the lesson and click Manage on the right.
4. Go to Live Stream Management & Data to view the data (click Download Spreadsheet on the right to download the data locally).

![](https://cofile.eeo.cn/res-store%2Fe0fdff86bc135d98ea17134a394b351cb3f7f2aa2515149f60d9ae38000aaeaa_704837?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=647baf6618a4e2527750f18dc17a4cd61836417a)

<!-- DOC_BOUNDARY -->
```yaml
title: "Live Stream Data Display"
source_title_zh: "直播数据展示"
```

## Live Stream Data Display

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can modify which types of data are shown in the web live stream from the Backend Management System. The data types that can be displayed in the web live stream are: view count, number of viewers currently online, and number of likes. Teaching staff can decide whether to display this data, or display only certain items, based on actual needs.

### Related Articles
"Adding Sub-accounts in the Backend"
"Setting Simulated RSVP, View, and Like Counts"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Web Live Stream & Playback at the top.
4. Check the data to display in "Live Stream Data Display Settings."

![](https://cofile.eeo.cn/res-store%2F8711e7b4917f08748e48d703b467b96c02991a2e8cbc29b6cf212cffb597fec9_797032?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a68a6e536892d80b16713aabff42f6c467da167d)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream/Playback Settings: Cover, Introduction, Announcement, Products"
source_title_zh: "网页直播回放设置：封面介绍公告商品"
```

## Web Live Stream/Playback Settings: Cover, Introduction, Announcement, Products

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Live Stream & Playback" permission

### Usage Notes
**Cover settings:**
- Uploaded images support fixed-ratio cropping; the recommended image ratio is 1920px x 1080px.
- Uploaded images must not exceed 500KB, to avoid slowing down page loading.
- A replaced cover image only takes effect for the specific class session (lesson) it was set on.

**Announcement:**
- The web live stream/playback announcement in the Backend Management System supports adding images, links, and text content.

**Products:**
- If the school has merchandise related to the class (such as books), the product feature in the web live stream/playback can be used to promote and sell these items.

### Notes
Changes to the "Web Live Stream/Playback" cover, introduction, announcement, and products only take effect for the specific class session (lesson) they were set on.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps

**(1) Change the live stream/playback cover**
1. Log in to the Backend Management System.
2. Go to Live Stream & Playback in the left navigation.
3. Find the lesson and click Manage on the right.
4. Go to Live Stream Settings.
5. Click the cover image to change it.
6. Click Save.

![](https://cofile.eeo.cn/res-store%2Fc153fd33ce9f3dba4b29e65f80c8f702f7d9e8690dfe1a6470f6527effa277af_321416?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=1c97f777654c91ee875755931beb4d00874f8d4b)

**(2) Change the live stream/playback introduction**

Add a text and image introduction.

![](https://cofile.eeo.cn/res-store%2F5c3be6dbe415ddacfca8a75ff36e06c536ff684aa156223698a0da719adf44b0_506335?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=5bb5ba944eb622ea3acb94c3bf0af73b00111637)

**(3) Add an announcement to the live stream/playback**
1. Find the lesson.
2. In the Announcement/Products area, click the speaker icon to add or edit an announcement or image.

![](https://cofile.eeo.cn/res-store%2F0214e45462d50a2f3d05e178725483b11e211205596f3dc9919c064febcf4da7_408244?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=3c3fda96446b20282da016eadd7218e769a6aeca)

**(4) Add a product to the live stream/playback**

In the Announcement/Products area, click the shopping bag icon to add or edit a product.

![](https://cofile.eeo.cn/res-store%2F23a6014d64cd66e3fcf7e68fd46099c87e36659b0412aba2c053c1fe2eea8c9e_623827?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=7eb3cd44701584d4a920d83d7cd8d75c429c67a9)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream/Playback Settings: Simulated RSVP, View, and Like Counts"
source_title_zh: "网页直播回放设置：虚拟预约、观看、点赞人次"
```

## Web Live Stream/Playback Settings: Simulated RSVP, View, and Like Counts

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Live Stream & Playback" permission

### When to use this
If teaching staff want to display a higher RSVP count on the web live stream, they can add a "simulated RSVP count" in the web settings. Viewers will then see a higher RSVP count without being able to tell which figures are genuine — they will simply see a large total. Similarly, to make it appear that many viewers are watching, a "simulated view count" can be added; viewers will see a higher view count without being able to distinguish real views from simulated ones. Likewise, to make the live stream appear to have received a large number of likes, a "simulated like count" can be added; viewers will see a high like count without being able to tell which likes are real and which are simulated.

### Usage Notes
Simulated RSVP, view, and like counts set for the "Web Live Stream" in the Backend Management System only take effect for the specific class session (lesson) they were set on.

### Steps

**(1) Simulated RSVP count**
1. Log in to the Backend Management System.
2. Go to Live Stream/Playback in the left navigation.
3. Find the lesson and click the number under **RSVP Count (+ simulated value)** on the right to set the simulated value.

![](https://cofile.eeo.cn/res-store%2F232797087a4d258b61df1dc3ebd59304eddd36948687ccc64c465cf057e4cf88_480988?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=2a978a9e6ffea9079f14403f74b2f97cd35c4551)

**(2) Simulated view count**
1. Go to Live Stream & Playback in the left navigation.
2. Find the lesson.
3. Click the number under **View Count (+ simulated value)** to set or change the simulated view count.

![](https://cofile.eeo.cn/res-store%2F3b567f279f9b4b2b302b45109dc140ebcde8af7fd4e7ad8a1c895cf9373e24fa_493108?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=5160a2314c2ef2c605e4d568ab56d2a6006ea425)

**(3) Simulated like count**

Click the number under **Like Count (+ simulated value)** to set or change the simulated like count.

![](https://cofile.eeo.cn/res-store%2Ffd678fd335ecdc6c3010d979397debecd89d6d685d3072d7cc0781284bc72420_487199?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a224b28b3f9a6b9cc587ed5fd4435949126c0e4a)

<!-- DOC_BOUNDARY -->
```yaml
title: "Default Web Live Stream Cover"
source_title_zh: "网页直播默认封面"
```

## Default Web Live Stream Cover

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can set a default cover image for the web live stream in the Backend Management System. The default live stream cover applies to the web live stream of every class session under the school. To change the web live stream cover for a specific class session only, it can be edited individually in the "Live Stream & Playback" section. A cover set individually for a class session does not conflict with the default cover — if a class session has no individually set cover, the default cover is used.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Web Live Stream & Playback at the top.
4. Change the default web live stream cover in "Default Web Live Stream & Playback Cover Settings."

![](https://cofile.eeo.cn/res-store%2F51f2f17c408bcd1edcf657b515f6d88a76b20e8df2f4517e2aeba665c58afa81_880995?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=bfdad8c4d1afe5851943e309b72b3bc8196da81b)

<!-- DOC_BOUNDARY -->
```yaml
title: "Getting Links"
source_title_zh: "获取链接"
group: true
```

## Getting Links

<!-- DOC_BOUNDARY -->
```yaml
title: "Allow Teachers to Get the Web Live Stream/Playback Link from the Client"
source_title_zh: "允许老师在客户端获取网页直播回放链接"
```

## Allow Teachers to Get the Web Live Stream/Playback Link from the Client

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
When "Allow teachers to get the web live stream/playback link from the client" is enabled, a class's head teacher and a class session's teacher/co-teacher can find the class session in the ClassIn app and get the web live stream/playback link for that session directly.

When "Allow teachers to get the class live stream/playback link from the client" is enabled, a class's head teacher and a class session's teacher/co-teacher can find the class session in the ClassIn app and get the web live stream/playback link for the whole class.

### Related Articles
"Getting the Class Session/Class Web Live Stream/Playback Link from the Client"
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Web Live Stream & Playback at the top.
4. In "Client Live Stream/Playback Link Settings," turn "Allow teachers to get the web live stream/playback link from the client" on or off.
5. In "Client Class Live Stream/Playback Link Settings," turn "Allow teachers to get the class live stream/playback link from the client" on or off.

![](https://cofile.eeo.cn/res-store%2F765ae9e01640051ebe654500a42ec5e8824451f6fa4c2e64da42c48079782374_1249312?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=7a4382a91728da220f7bcb531b80bedba7b4ac4c)

<!-- DOC_BOUNDARY -->
```yaml
title: "Getting the \"Live Stream & Playback\" Link from the Backend"
source_title_zh: "后台获取“直播回放”链接"
```

## Getting the "Live Stream & Playback" Link from the Backend

### I. Getting the Class Session Link

#### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Class Management" and "Live Stream & Playback" permissions

#### When to use this
In large classes, the number of students may run into the thousands or tens of thousands, exceeding the class member limit. Teaching staff can share the "Web Live Stream/Playback" link with these students so they can watch. If a teacher wants to sit in on a class but doesn't have monitoring permission, teaching staff can share the link so the teacher can watch the live broadcast. When parents want to watch how their child is performing in class, teaching staff can share the link with them as well. Teaching staff can also share the "Web Live Stream/Playback" link with anyone else so they can watch the class recording at any time.

#### Related Articles
"Setting Viewing Permissions"
"Live Stream/Playback Data"
"Adding Sub-accounts in the Backend"

#### Steps
1. Log in to the Backend Management System.
2. Go to Class Management in the left navigation.
3. Find and enter the class.
4. Go to the Schedule.
5. Find the class session, click Actions on the right, and go to Live Stream & Playback Management.
6. Get the class session's live stream/playback link in the upper-right corner.

![](https://cofile.eeo.cn/res-store%2F6606266e8e2bdd079be191dc715d061c3c7d75acaaeda1e5a091e3c9fe54b3c7_802520?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=472e53d4e7c578e10388f0d09a38adeda7180964)

### II. Getting the Class Link

Sub-accounts with the "Class Management" permission.

In large classes, the number of students may run into the thousands or tens of thousands, exceeding the class member limit. Teaching staff can share the "Web Live Stream/Playback" link with these students so they can watch. If a teacher wants to sit in on a class but doesn't have monitoring permission, teaching staff can share the link so the teacher can watch the live broadcast. When parents want to watch how their child is performing in class, teaching staff can share the link with them as well. Teaching staff can also share the "Web Live Stream/Playback" link with anyone else so they can watch all recordings for that class at any time, without needing to add them to the class.

1. Find and enter the class.
2. Click "Class Live Stream & Playback Platform" in the upper-right corner.

![](https://cofile.eeo.cn/res-store%2Fc147c20517ae70cbeb4c30bb6c9578c0ead22a084e4bdd67e2089e97685fbbcb_533805?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=51103b6423e8d7bc656c7da6e288d0b14a33afca)

<!-- DOC_BOUNDARY -->
```yaml
title: "Allow Newly Added Students to Watch Historical Playbacks"
source_title_zh: "允许新加入学生观看历史回放"
```

## Allow Newly Added Students to Watch Historical Playbacks

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can turn on or off, in the Backend Management System, whether students newly added to a course (class) can watch recorded playbacks of past class sessions in that course (class). When enabled, students newly added to the course can watch playback videos of class sessions that took place before they joined.

| Status | Description |
| --- | --- |
| Disabled | Students newly added to the course become "transferred-out students" for historical class sessions: historical class sessions are not shown on the student side, and playback videos of them cannot be watched. |
| Enabled | Students newly added to the course become official students (marked absent) for historical class sessions: historical class sessions are shown on the student side, and playback videos can be watched. |

### Notes
The change in a student's status for historical class sessions caused by this action is irreversible — proceed with caution. If you have questions about using this setting, please consult your account manager or customer support first.

This setting does not support the scenario of converting a course auditor into an official student — an auditor of the course will never be able to watch playbacks of historical class sessions.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Course Playback at the top.
4. In "Advanced Course Playback Viewing Permission Settings," turn on or off "Allow students newly added to the course to watch playbacks of historical class sessions."

![](https://cofile.eeo.cn/res-store%2Fbfb73e01e12dc65d56323f16beb2103a26f52067f5e91edeb9d55084febc325b_409861?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=12bbea7253369e36a0221248ef439e2da4a5c097)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream RSVP"
source_title_zh: "网页直播预约"
```

## Web Live Stream RSVP

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
Teaching staff can enable or disable the web live stream RSVP feature in the Backend Management System. When enabled, viewers can open the web live stream link before the class starts and proactively RSVP for an SMS notification. One minute before the live class session begins, the system sends an SMS to notify the user that class is starting. (Note: only real phone numbers are supported; virtual accounts or non-genuine phone numbers are not supported.)

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Web Live Stream & Playback at the top.
4. In "Web Live Stream RSVP Settings," turn the web live stream RSVP feature on or off.

![](https://cofile.eeo.cn/res-store%2F15371e1f064ae738864425e4b25829ac30533c964f884389a39fe72b2be58989_672713?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=5dea6fc8f5ce3f3964dc150c79111cd17a0c947b)

<!-- DOC_BOUNDARY -->
```yaml
title: "Viewing Permissions"
source_title_zh: "观看权限"
group: true
```

## Viewing Permissions

<!-- DOC_BOUNDARY -->
```yaml
title: "Client Playback Viewing Permission"
source_title_zh: "客户端观看回放权限"
```

## Client Playback Viewing Permission

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### When to use this
Teaching staff can enable or disable, in the Backend Management System, whether users can watch class session playbacks in the ClassIn app. If enabled, teachers and students can watch playback videos of class sessions they attended (provided the teacher recorded that class). If disabled, neither teachers nor students can watch playback videos of attended class sessions in the ClassIn app, regardless of whether the class was recorded.

### Related Articles
"Adding Sub-accounts in the Backend"
"Watching Recorded Class Playback Videos on the Client"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Course Playback at the top.
4. In "Official Student and Teacher Course Playback Viewing Settings," turn on or off "Allow official students and teachers to watch the course playback after class ends."

![](https://cofile.eeo.cn/res-store%2Fbc940f7cc829e1c91368aa4fc0498ed7c42652680adc5ce44a3c00313a8de771_427489?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=df2aa167373584b2cf075245fadf3d969e4d29d3)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream/Playback Settings: Viewing Permissions"
source_title_zh: "网页直播回放设置：观看权限"
```

## Web Live Stream/Playback Settings: Viewing Permissions

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Live Stream & Playback" permission

### When to use this

**Anyone with the link can watch**

When a teacher wants anyone who receives the "Web Live Stream/Playback" link to be able to open it and watch the live stream or playback directly, they can check "Anyone with the link can watch" in "Live Stream Settings" in the Backend Management System. Viewers can then watch the content without any extra steps.

**Only members of this class session can watch**

When a teacher shares the "Web Live Stream/Playback" link, they may not want non-members of that class session to be able to watch. In this case, teaching staff can select "Only selected members can watch" in the "Viewing Permission Settings" of the Live Stream Settings, and check "Members of this class session can watch." Only members of that class session who log into their ClassIn account can then watch the live stream — non-members cannot watch even if they are logged into ClassIn. This protects the security of course content and ensures the benefit of watching the web live stream/playback is limited to specific members.

**Only selected students can watch**

When a teacher shares the "Web Live Stream/Playback" link but only wants specific students to be able to watch, teaching staff can configure this in the Backend Management System. By selecting "Only selected members can watch" in the Live Stream Settings, checking "Selected students can watch," and then choosing the students to be granted access, only those specific students will be able to view the content. This setup not only protects the security of course content but also ensures that only specific members enjoy the benefit of watching the live stream and playback.

### Notes
When enabling "Members of this class session can watch" or "Selected students can watch," the feature "Require login to a ClassIn account to watch the web live stream and playback" must also be checked.

"Members of this class session can watch" and "Selected students can watch" can be enabled at the same time.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps

**(1) Anyone with the link can watch**
1. Log in to the Backend Management System.
2. Go to Live Stream & Playback in the left navigation.
3. Find the lesson and click Manage on the right.
4. Go to Live Stream Settings.
5. Check "Anyone with the link can watch."
6. Click Save.

![](https://cofile.eeo.cn/res-store%2F874c26b573b24325e8150911f5261d964afb08b3dd8e6cf3751e5870d375be2f_332151?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=f9e4b3046d23a14d8ff255ee3270251b98fd5bfb)

**(2) Only members of this class session can watch**
1. Check "Only selected members can watch."
2. Check "Members of this class session can watch."

![](https://cofile.eeo.cn/res-store%2F8791cb8394aacca5036cad076cc2df6a2cdd4c5c671f011fc7ae7b9fb3035e3b_353930?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=d049b3497ca927abc0a90e138f6e9faa5a60f934)

**(3) Only selected students can watch**
1. Check "Selected students can watch."
2. Click Select Students.
3. On the left, **search for students** and check the students found.

![](https://cofile.eeo.cn/res-store%2F520ac104bfd263a7f92216274f9520df5c945ec46ade06987d2ab77809c703c6_420892?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=c95c1bf2a657843e009ceecdbcfae496a278a0e0)

**(4) Both class session students and selected students can watch**
1. Turn "Only selected members can watch" on or off.
2. Check both "Anyone with the link can watch" and "Selected students can watch" at the same time.

![](https://cofile.eeo.cn/res-store%2Fd5fce4f124dac3e94376fa84ccea1a2efe18f5e185b29654a64bf44de8250a6c_422143?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=49a48e5e22c8507160cb2897df221a907d6f0159)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream/Playback Settings: Password-Protected Viewing"
source_title_zh: "网页直播回放设置：通过密码才可观看"
```

## Web Live Stream/Playback Settings: Password-Protected Viewing

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Live Stream & Playback" permission

### When to use this
To protect the security and confidentiality of the "Web Live Stream/Playback," teaching staff can enable "Password-protected viewing" in the settings. Once enabled, even users who have the "Web Live Stream/Playback" link will need to enter the password set in advance by teaching staff in order to watch.

### Usage Notes
Turning "Require a password to watch the web live stream/playback of the class session" on or off only takes effect for the specific class session (lesson) it was set on.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to Live Stream & Playback in the left navigation.
3. Find the lesson and click Manage on the right.
4. Go to Live Stream Settings.
5. Turn "Password-protected viewing" on or off.
6. Click Save.

![](https://cofile.eeo.cn/res-store%2Fcb079be85abfb3df2c655fd0f704b45be438af671ed908413b4344bce56ebc6b_336517?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=3d05a7687038d8dd7e61c8d2a6c7927fb133ce5c)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream/Playback Settings: Login Required to Watch"
source_title_zh: "网页直播回放设置：需要登录账号才可观看"
```

## Web Live Stream/Playback Settings: Login Required to Watch

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "Live Stream & Playback" permission

### When to use this
When teaching staff want to use "Web Live Stream/Playback" to promote a course, they can share the link with potential viewers. Teaching staff can then enable "Require login to a ClassIn account to watch the web live stream and playback" in the "Web Live Stream/Playback" permission settings in the Backend Management System. Once enabled, every viewer must log into a ClassIn account before they can watch the "Web Live Stream/Playback" content. After a user logs in, teaching staff can retrieve that user's account from the "Web Live Stream/Playback" data in the Backend Management System, making it easier to follow up with them later.

### Usage Notes
Turning "Require login to a ClassIn account to watch the web live stream and playback" on or off only takes effect for the specific class session (lesson) it was set on.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to Live Stream & Playback in the left navigation.
3. Find the lesson and click Manage on the right.
4. Go to Live Stream Settings.
5. Turn "Require login to a ClassIn account to watch the web live stream and playback" on or off.
6. Click Save.

![](https://cofile.eeo.cn/res-store%2F4703cc8760c762cddcec836e9b3bcb1e3ee1e70ff54de4344b6ee1feb4e60d9b_340781?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=3131ff2d9bd979a578523760dd608f204251ed84)

<!-- DOC_BOUNDARY -->
```yaml
title: "Anti-Recording Protection"
source_title_zh: "防盗录"
group: true
```

## Anti-Recording Protection

<!-- DOC_BOUNDARY -->
```yaml
title: "Client Playback Anti-Recording (Scrolling Watermark)"
source_title_zh: "客户端回放视频防录屏（跑马灯）"
```

## Client Playback Anti-Recording (Scrolling Watermark)

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### When to use this
When "Anti-recording protection for class playback videos" is enabled in the Backend Management System, the nickname and phone number of each student or teacher will move around the video area as a scrolling watermark while they watch a class playback in the ClassIn app (each user only sees their own phone number and nickname, and cannot see anyone else's), appearing in different positions across the video. If a student or teacher illegally records the video, the recorder's identity can be traced through the phone number, helping prevent the unauthorized distribution and use of video content.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation, then go to Course Playback at the top.
3. In "Anti-Recording Scrolling Watermark Settings," turn on or off "Show anti-recording scrolling watermark on course playback."

![](https://cofile.eeo.cn/res-store%2F9a5dfe377ddcc8ff9a518e1a8febaf449cbb02b6b54f49211b3adf4666b5a5f7_434697?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=d11f85b613246d0d6a3bc080c3453ff82de65605)

<!-- DOC_BOUNDARY -->
```yaml
title: "Client Playback Anti-Recording Protection"
source_title_zh: "客户端回放视频防盗录"
```

## Client Playback Anti-Recording Protection

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### When to use this
If "Anti-recording protection for class playback videos" is enabled in the Backend Management System, students and teachers using the ClassIn app on a computer, phone, or tablet to watch a class playback will be unable to use screen-recording software to record the playback video. In addition, phones and tablets will be unable to mirror/cast the class playback video to another device for viewing.

### Notes
With this feature enabled, screen mirroring is not available on mobile devices.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation, then go to Course Playback at the top.
3. In "Anti-Recording Protection Settings," turn on or off "Anti-recording protection for course playback."

![](https://cofile.eeo.cn/res-store%2F9a34f7497d750844d7f7842c58f11a3eb0c472eac715dcd07ef919f4b8517262_467989?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=5a3802f83239eb2e264cef8413b4eb3d17f4f151)

<!-- DOC_BOUNDARY -->
```yaml
title: "Web Live Stream/Playback Anti-Recording (Scrolling Watermark)"
source_title_zh: "网页直播回放防录屏（跑马灯）"
```

## Web Live Stream/Playback Anti-Recording (Scrolling Watermark)

### Applies to
- Primary account of the Backend Management System
- Sub-accounts with the "School Settings" permission

### Usage Notes
When "Show anti-recording scrolling watermark on web live stream/playback" is enabled, the nickname and phone number of each student or teacher watching the web live stream/playback will move randomly around the video area. If a student or teacher illegally records the video, the recorder can be traced through the phone number.

### Notes
For the scrolling watermark feature to work correctly, students and teachers need to be logged into a ClassIn account while watching the web live stream or playback. Please make sure "Require a ClassIn account login to watch the web live stream/playback" is enabled for every lesson's live stream and playback. If this setting is not enabled, the scrolling watermark feature will not display correctly.

### Related Articles
"Adding Sub-accounts in the Backend"

### Steps
1. Log in to the Backend Management System.
2. Go to School Settings in the left navigation.
3. Go to Web Live Stream & Playback at the top.
4. In "Anti-Recording Scrolling Watermark Settings," turn "Anti-recording protection" on or off.

![](https://cofile.eeo.cn/res-store%2F96763cb4afeda5ec5fb2dc0574a4298a36c18342a250c2437425783867f086a4_589544?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=caa3a860244e0377bb8fad3907609a797cbb7866)
