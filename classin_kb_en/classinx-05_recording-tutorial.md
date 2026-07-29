---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: ClassInX
subcategory: "Class Recording Tutorial"
batch: 58 of N
translated_from: zh-CN (source: ClassInX/ClassInX_录课教程/index.md)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# ClassInX Class Recording Tutorial

<!-- DOC_BOUNDARY -->
```yaml
title: "ClassInX Class Recording Tutorial"
source_title_zh: "ClassInX 录课教程"
```

## ClassInX Class Recording Tutorial

# I. Recording Notes

## 1. Recommended Recording Equipment

Computer or large display requirements are as follows:

| | Minimum Requirements | Recommended Requirements |
| --- | --- | --- |
| Processor | Intel i5 8th gen or higher / AMD Ryzen 5 1st gen or higher | Intel i7 9th gen or higher / AMD Ryzen 7 2nd gen or higher |
| OS | Windows 7 or higher | Windows 10 or higher |
| Memory | Windows: 4GB RAM | Windows: 8GB RAM |
| Display | 1280x720 or higher | 1920x1080 or higher |
| Network | 4Mbps or higher | 6Mbps or higher |

## 2. Recording Area Settings

### Usage Notes
If you checked "Record ClassIn Classroom" when creating the class session, or need local recording, the teacher enters the classroom using ClassInX on a computer/large display.

If you only want to record what's inside the classroom, you can check "Record" for either:

**"Minimum-Size Classroom Window"** (once recording starts, the classroom window shrinks to 1280x720 and cannot be resized)

or **"Current-Size Classroom Window"** (once recording starts, you can drag to resize the classroom window; it can be maximized but not minimized) under "Recording Area" in ClassInX's classroom settings.

Once you're in ClassInX, it defaults to full-screen display with no way to resize the window — so whether you choose the minimum-size or current-size window, the recording captures the classroom's full-screen view either way.

If you'd like to record the entire computer/large display desktop, including pop-up notifications and similar elements, you can check "Record Entire Computer Desktop" under "Recording Area" in ClassInX's classroom settings — once recording starts, everything both inside and outside the classroom will be recorded. Note that a larger display screen demands more from your computer's performance.

### Notes
When "Minimum-Size Classroom Window" or "Current-Size Classroom Window" is selected, if the teacher clicks "Return to Desktop" in ClassInX or uses the toolbox's "Screen Share" feature, the recording captures the entire computer/large display desktop where the ClassInX classroom window is located.

If the teacher is using Windows 7 and wants to record the classroom window, they'll also need to set the system theme to the Aero theme.

This setting only applies to the current computer/large display.

### Steps

#### Current-Size Classroom Window:

#### Entire Computer Desktop:

#### Setting the Aero Theme on Windows 7:

## 3. Recording Video Quality Settings

If you need to improve the recorded video's quality, you can choose the recording quality under "Recorded Video Resolution" in ClassInX's classroom settings.

HD mode records the class video at a resolution of 1280x720; Full HD mode records it at 1920x1080.

When "Recording Area" is set to "Minimum-Size Classroom Window," Full HD resolution is not available under "Recorded Video Resolution."

## 4. Recording Sound Settings

If you want to record all sound from the entire computer/large display, you can select "System Sound" under "Recording Mode" in ClassInX's classroom settings. Once "System Sound" is checked, recording captures all sound on the computer, both inside and outside the classroom — for example, video or music playing outside the classroom, and notification sounds from messaging software, will all be recorded.

If you only want to record sound within the classroom, you can select "Software Sound" instead. Once "Software Sound" is checked, recording only captures sound within the classroom, and sound from outside the classroom won't be recorded.

## 5. Recording FAQ

While recording is in progress, please don't plug or unplug speaker devices like headphones or external speakers — make sure the classroom's speaker sound can be heard normally.

While recording is in progress, please don't proactively exit the classroom.

Make sure the classroom's microphone is working normally while recording.

Make sure your network connection is stable while recording.

While using Record On-Site, make sure the camera feed selected for the on-site recording window displays properly.

## 6. Recording Status

### 6.1 How the Lead Teacher Checks Record On-Site Status

Once a class session has "Record On-Site" checked, the lead teacher can check the classroom's recording status indicator after entering the classroom to determine whether recording is working normally.

Once the lead teacher's recording starts, on computer/large display they can check the recording status in the dock right below the classroom window. The recording icon is a camera + small cloud; when the small cloud is "green," Record On-Site is recording normally; when the small cloud is "red," Record On-Site has been interrupted.

### 6.2 How the Lead Teacher Checks Record ClassIn Classroom Status

Once a class session has "Record ClassIn Classroom" checked, the lead teacher can check the classroom's recording status indicator after entering the classroom to determine whether recording is working normally.

Once the lead teacher's recording starts, on computer/large display they can check the recording status in the dock right below the classroom window. The recording icon is a camera + small cloud; when the small cloud is "green," Record ClassIn Classroom is recording normally; when the small cloud is "red," Record ClassIn Classroom has been interrupted.

### 6.3 Checking Local Recording Status

After entering the classroom, teachers can check the classroom's recording status indicator to determine whether recording is working normally.

Once local recording starts, on computer/large display you can check the recording status in the dock right below the classroom window. The recording icon is a camera + small circle; when the small circle is "green," local recording is recording normally; when the small circle is "red," local recording has been interrupted.

## 7. Recording-Related Parameters

### 7.1 Bandwidth Requirements by On-Stage Headcount

| On-Stage Headcount | Upload Bandwidth Required | Download Bandwidth Required |
| --- | --- | --- |
| 1v6 | ≥2Mbps | ≥2Mbps |
| 1v12 | ≥4Mbps | ≥4Mbps |
| 1v1 HD | ≥1.5Mbps | ≥1.5Mbps |
| 1v1 Full HD | ≥3Mbps | ≥3Mbps |
| 1v1 Dual Camera Full HD | ≥6Mbps | ≥6Mbps |
| 1v6 HD | ≥8Mbps | ≥8Mbps |
| 1v6 Full HD | ≥15Mbps | ≥15Mbps |

### 7.2 Bandwidth Add-On Rules for Additional Features

**Cloud recording / livestream (affects only the teacher's side):**

HD video: +1Mbps upload bandwidth

Full HD video: +2Mbps upload bandwidth

**Screen sharing:**

Sender: +2Mbps upload bandwidth

Receiver: +2Mbps download bandwidth

**Video Wall:**

Bandwidth requirement = on-stage headcount bandwidth requirement × 2

### 7.3 Recording Technical Specifications

| Parameter | Specification |
| --- | --- |
| File Format | MP4, FLV |
| Aspect Ratio | 16:9 |
| Video Codec | H.264 @ 15fps |
| Resolution | 1080p/720p |
| Audio Bitrate | 64kbps (customizable/extendable) |

<!-- DOC_BOUNDARY -->
```yaml
title: "Differences Between Record ClassIn Classroom, Record On-Site, and OMO Livestream Broadcast"
source_title_zh: "录制教室、录制现场和OMO站播的区别"
```

## II. Differences Between Record ClassIn Classroom, Record On-Site, and OMO Livestream Broadcast

Cloud recording has two modes: Record ClassIn Classroom, and Record On-Site. These two modes can be enabled individually or together.

**Record ClassIn Classroom:** this mode has two recording area options: the first only records what's inside the lead teacher's classroom window; the second records the lead teacher's entire large display, including the classroom window and everything the user does on the large display's desktop. These two recording area options can be configured in the app settings. If the lead teacher only wants to record what's inside the classroom window, they can check "Current-Size Classroom Window" under recording area settings. If the lead teacher wants to record both what's happening inside the ClassInX classroom and everything on the large display's desktop, they can check "Entire Computer Desktop" under recording area settings.

**Record On-Site:** this mode only records the camera feed the lead teacher selects for on-site recording during the class recording process — anything outside that camera's view is not recorded. Online students in the classroom can open the on-site recording window to view a larger, clearer feed of the teacher's instruction. Users watching class via the web livestream link can also switch directly to viewing the on-site recording feed. In addition, when watching class playback, students can likewise switch to on-site recording mode for a better review and understanding of the teacher's explanation.

**OMO Livestream Broadcast:** when students only need to watch the teacher's livestream feed within the classroom and recording isn't needed, we recommend using OMO Livestream Broadcast. This is a high-definition on-site recording mode where only the camera feed the lead teacher selects in the OMO livestream broadcast settings is recorded within the classroom — anything outside that camera's view is not recorded. Online students in the classroom can open the OMO livestream broadcast window for a clearer view of the teacher's instruction. This mode is especially well suited to teaching scenarios that need high-definition video quality.

When Record On-Site and OMO Livestream Broadcast are both enabled at the same time, they cannot each use a different camera — that is, when the lead teacher selects a camera for Record On-Site, OMO Livestream Broadcast automatically switches to that same camera, and vice versa.

Record On-Site and OMO Livestream Broadcast are only supported when the lead teacher uses a computer or large display (Windows) — other devices (such as phone/tablet) are not supported.

<!-- DOC_BOUNDARY -->
```yaml
title: "ClassInX Record On-Site"
source_title_zh: "ClassInX录制现场"
```

## III. ClassInX Record On-Site

### What Is "Cloud Recording"?
"Cloud recording" includes two recording modes — "Record ClassIn Classroom" and "Record On-Site." Once recording is checked when creating a class session, ClassIn's built-in recording feature can fully capture the entire teaching process from the lead teacher's perspective while they teach. These recorded videos are automatically uploaded and stored on ClassIn's servers. After class ends, the recording is turned into a "class playback video" in about half an hour, for students and teachers to review and watch afterward.

### Applies to
The lead teacher.

### Prerequisites
When creating the class session, you need to check "Record On-Site" under "Cloud Recording" before the lead teacher can use the "Record On-Site" cloud recording feature during class.

Record On-Site means that while the lead teacher uses ClassInX to record class, only the camera feed selected in the on-site recording window is recorded — anything outside that camera's view is not recorded, so make sure the selected camera feed displays properly.

Every time the lead teacher enters the classroom, they'll be shown a recording prompt; once they click Confirm, they'll see the on-site recording window along with a "Recording Countdown" prompt.

In this window, you can view the current on-site recording feed, and switch which camera device is being recorded via the settings in the window's top-right corner — recording only proceeds normally if the on-site recording feed is displaying correctly.

Once the lead teacher has adjusted the on-site recording camera feed, they can manually click "Start Recording Now" on the countdown prompt to begin recording, or wait for the countdown to finish and recording will start automatically. The default recording countdown is 10 minutes; to change this, please contact a teacher with "Backend Management" permission to go into the "Backend Management System" and change the recording countdown time.

Recording cannot be stopped once class is underway — if you don't want to record, you can disable the camera in the on-site recording window, or turn off "Record ClassIn Classroom" the next time you create a class session. Recording automatically stops once the lead teacher exits the classroom; when the lead teacher re-enters the classroom, they'll be prompted to start recording again.

In addition, online students in the classroom can also view the "Live On-Site" feed (i.e., the on-site recording feed) in the bottom-right corner.

Record On-Site is only supported when the lead teacher uses a computer or large display (Windows).

If the lead teacher's network is unstable, recording may fail. The recording icon will turn red, and ClassInX will automatically retry recording after a failure.

If the lead teacher plugs or unplugs a speaker device on their computer/large display, or the speaker becomes disconnected due to an unstable connection, recording will also stop. In this case, the lead teacher will see a "Recording Interrupted" prompt — to continue recording, reconnect the speaker device securely or switch to a more stable speaker device, then click Retry in the classroom's "Recording Interrupted" prompt window.

### Related Articles
"Editing the Recording Countdown"

### Steps
1. Enter the classroom.
2. Read the recording prompt, then click Confirm.
3. View the on-site recording feed, select a camera in the settings in the top-right corner of the on-site recording window, then click Done.
4. Click "Start Recording Now" to the right of the Recording Countdown, or wait for the countdown to finish for recording to start automatically.
5. Check the recording status.

### The Lead Teacher's On-Site Recording Feed Looks Like This:

### Students Viewing the On-Site Recording Feed on Computer in the Classroom:

### Students Viewing the On-Site Recording Feed on Phone or Android Tablet in the Classroom:

### Students Viewing the On-Site Recording Feed on iPad in the Classroom:

<!-- DOC_BOUNDARY -->
```yaml
title: "ClassInX Record ClassIn Classroom"
source_title_zh: "ClassInX录制教室"
```

## IV. ClassInX Record ClassIn Classroom

When creating the class session, you need to check "Record ClassIn Classroom" under "Cloud Recording" before the lead teacher can use this "Record ClassIn Classroom" cloud recording feature during class.

"Record ClassIn Classroom" records what's happening within the classroom itself.

If the lead teacher's recording area setting in ClassInX is set to Current-Size Classroom Window or Minimized Classroom Window, the recording captures the lead teacher's classroom view; however, if the lead teacher uses the "Screen Share" tool or clicks "Return to Desktop," the recording instead captures the computer/large display desktop where the ClassInX classroom window is located.

If the lead teacher's recording area is set to Entire Computer Desktop, the recording captures the computer/large display desktop where the classroom window is located.

Every time the lead teacher enters the classroom, they'll be shown a recording prompt; once they click Confirm, they'll see a "Recording Countdown" prompt, and can manually click "Start Recording Now" to begin recording, or wait for the countdown to finish and recording will start automatically. The default recording countdown is 10 minutes; to change this, please contact a teacher with "Backend Management" permission to go into the "Backend Management System" and change the recording countdown time.

Recording cannot be stopped once class is underway — if you don't want to record, you can only turn off "Record ClassIn Classroom" the next time you create a class session. Recording automatically stops once the lead teacher exits the classroom; when the lead teacher re-enters the classroom, they'll be prompted to start recording again.

If a teacher realizes after starting class that they forgot to enable "Record ClassIn Classroom," they can use the "Local Recording" feature to record and save the class to their computer/large display locally, or create a new class session and check "Record ClassIn Classroom" when creating it.

If the lead teacher's network is unstable, recording may fail.

Once recording fails, ClassInX will automatically retry — if it fails 3 times in a row without successfully starting, a pop-up will appear in the classroom prompting the teacher to switch from cloud recording to local recording; the lead teacher can then manually switch to local recording (this switch is only supported on computer/large display). Once switched to local recording, the recorded file is stored by default in a newly created folder under ClassInX file, in MP4 format by default; local recording can be manually stopped and restarted. If you don't click to switch to local recording, cloud recording continues, and ClassInX keeps retrying — the switch prompt won't reappear, but you can reopen it by clicking the red "recording failed" icon.

Also, if the lead teacher exits and re-enters the classroom, ClassInX will retry cloud recording again.

### Record ClassIn Classroom Feed Looks Like This:

<!-- DOC_BOUNDARY -->
```yaml
title: "ClassInX Local Recording"
source_title_zh: "ClassInX本地录课"
```

## V. ClassInX Local Recording

### What Is "Local Recording"?
"Local Recording" refers to a teacher recording the class using ClassInX's screen recording (recording the classroom window) and saving it to their computer/large display locally.

As long as either Record ClassIn Classroom or Record On-Site is enabled (or both), the class session's co-teacher can use local recording.

If neither Record ClassIn Classroom nor Record On-Site is enabled, the class session's co-teacher can still use the local recording feature.

An "academic teacher" who enters classroom monitoring via the "Classroom Monitoring" module in the "Backend Management System" can use the local recording feature.

Anyone who enters the "Whiteboard" in ClassInX can use the "Local Recording" feature.

You can use "Local Recording" after creating and entering a temporary classroom from a class or friend chat interface.

Teachers who enter the prep room can use the "Local Recording" feature.

### When to Use This
When a classroom has a co-teacher, if the lead teacher's cloud recording of the classroom becomes unstable (for example, recording gets interrupted and the classroom's recording status icon turns "red"), the co-teacher can use local recording in the classroom to make sure the class is fully recorded without gaps; after class, the academic teacher can upload the co-teacher's local recording to the "Backend Management System" to replace the lead teacher's incomplete recording for that session.

When a classroom has no co-teacher, if the lead teacher's cloud recording becomes unstable (for example, recording gets interrupted and the classroom's recording status icon turns "red"), the academic teacher can log into the "Backend Management System," enter classroom monitoring under "Classroom Monitoring," and perform local recording; after class, the academic teacher can upload their own local recording to the "Backend Management System" to replace the lead teacher's incomplete recording for that session.

If a classroom doesn't have Record ClassIn Classroom or Record On-Site enabled, but the classroom content needs to be recorded during the lesson anyway, the lead teacher or co-teacher can use local recording, and afterward send the local recording's playback video to anyone who needs to watch it.

Once the prerequisites for local recording are met, click the recording icon in the dock below; in the recording video save-path window, choose the save path and the recording's file type (FLV/MP4, defaulting to FLV), and recording will begin. Local recording captures what's inside the classroom.

If the teacher's recording area setting in ClassInX is set to Current-Size Classroom Window or Minimized Classroom Window, the recording captures the lead teacher's classroom view; however, if the teacher uses the "Screen Share" tool or clicks "Return to Desktop," the recording instead captures the computer/large display desktop where the ClassInX classroom window is located.

If the teacher's recording area is set to Entire Computer Desktop, the recording captures the computer desktop/large display where the ClassInX classroom window is located.

Clicking the recording icon again ends local recording. You can start local recording again afterward if needed.

If the teacher's network is unstable, recording may fail — you can manually try restarting recording if it fails.

If the teacher plugs or unplugs a speaker device on their computer/large display, or the speaker becomes disconnected due to an unstable connection, recording will also stop. In this case, the lead teacher will see a "Recording Interrupted" prompt — to continue recording, reconnect the speaker device securely or switch to a more stable speaker device, then click Retry in the classroom's "Recording Interrupted" prompt window.

### Steps
1. Enter the Whiteboard or classroom.
2. Click the recording icon in the dock right below.
3. Read the recording prompt, then click Start Recording.
4. Choose the local recording video's save path and save type, then click Save.
5. Check the recording status. Click the recording icon again to end local recording.

### Local Recording Feed Looks Like This:

<!-- DOC_BOUNDARY -->
```yaml
title: "Switching to Local Recording When ClassInX's Record ClassIn Classroom Fails"
source_title_zh: "ClassInX录制教室失败时切换本地录课"
```

## VI. Switching to Local Recording When ClassInX's Record ClassIn Classroom Fails

If the lead teacher's network is unstable and causes Record ClassIn Classroom to fail, ClassInX will automatically retry recording — if it fails 3 times in a row without successfully starting, a pop-up will appear in the classroom prompting the teacher to switch from cloud recording to local recording; the lead teacher can then manually switch to local recording (this switch is only supported on computer/large display). Once switched to local recording, the recorded file is stored by default in a newly created folder under ClassInX file, in MP4 format by default; local recording can be manually stopped and restarted. If you don't click to switch to local recording, cloud recording continues, and ClassInX keeps retrying — the switch prompt won't reappear, but you can reopen it by clicking the red "recording failed" icon.

After class ends, when the teacher views the playback from "Schedule" or "Class," the playback button will show a small red dot; clicking it shows the teacher a message: "A local recording file is pending upload — please contact your administrator to upload the recorded video." Clicking "Local Recording File" opens the folder where the recording is stored. You can send the local recording to your academic teacher, who can then log into the Backend Management System and upload it to the corresponding class session's playback slot. If there's no local recording file (for example, if it was deleted), no such prompt will appear.

### Steps
1. Read the recording error prompt, then click Switch Now.
2. When viewing the class playback afterward, find the video and provide it to your academic teacher.

### Finding the Playback Video After the Lead Teacher Switches from Record ClassIn Classroom to Local Recording:
