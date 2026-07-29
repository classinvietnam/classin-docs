---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: FAQ
batch: 4 of N (final batch for FAQ category)
translated_from: zh-CN (consolidated knowledge base)
---

# FAQ: Camera, Playback Video, Download & Installation

<!-- DOC_BOUNDARY -->
```yaml
title: "FAQ: Camera"
source_title_zh: "【摄像头】常见问题"
```

## FAQ: Camera

### 1. Camera shows a "white crossed-out camera" icon
**Issue**: Opening the camera in the classroom shows no video, just a white crossed-out camera icon.

**Try**:
- If you have "PC Manager" software installed, it may block the camera — try closing it temporarily.
- Your laptop's built-in camera may be physically disabled:
  - **Lenovo laptops**: there's a slide switch next to the front camera — slide it to enable.
  - **Other brands**: press FN + the function key with a camera icon.
- If none of the above works, contact your computer's after-sales support to install the latest camera driver.

### 2. Camera shows the "ClassIn avatar"
**Issue**: The camera window shows your round ClassIn avatar instead of live video.

**Fix**: This means you've disabled your own camera. Re-enable it in the classroom to fix this.

### 3. Camera shows a "green camera icon"
**Issue**: The camera window shows a green camera icon instead of live video.

**Computer**, try any of the following:
- **Close antivirus/security software**: e.g. 360 Security Guard, 360 Antivirus, Tencent PC Manager, 2345 Security Guard, Microsoft PC Manager, Lenovo PC Manager.
- **Restart your router**: unplug it, wait a few seconds, then plug it back in.
- **Switch networks**: on a laptop, try a wired connection or a phone hotspot (5G recommended).

**Phone/tablet**, try any of the following:
- **Move closer to your router** for a stronger signal.
- **Switch networks**: temporarily disconnect Wi-Fi and use mobile data instead.
- **Disable hardware video decoding**: on Android, turn off "Enable video hardware decoder" in ClassIn settings.

### 4. Camera window is completely black
**Issue**: The camera window shows solid black instead of video.

**Try**:
- **Check for obstructions** in front of the camera lens.
- **Install the latest driver**: contact your computer's after-sales support.
- **Contact support**: if the above doesn't help, message the ClassIn Assistant in the after-sales support group, or call 400-077-1585.

### 5. "Camera may be in use, please close other software"
**Issue**: The camera window shows: "Camera may be in use, please close other software."

**Try**:
- **Close other software** using the camera — make sure nothing besides ClassIn is accessing it.
- **Close antivirus/security software.**
- **Enable camera access (Windows 10)**: turn on "Allow apps to access your camera" (Settings > Privacy > Camera).
- **Grant camera permission (Mac)**: authorize ClassIn's camera access in system settings, then restart. If already granted, try re-granting and restarting.
- **Adjust ClassIn settings**: switch camera mode to "Default mode" or "Advanced mode."
- **Repair camera (Windows)**: try the "Repair Camera" feature in the ClassIn classroom.

### 6. Camera video is too dark
**Issue**: The video image from your camera looks dim.

**Try**:
- **Improve room lighting** if the environment is dark.
- **Adjust camera settings**: try adjusting brightness settings via QQ's camera settings.

### 7. Camera turns off by itself after being enabled
**Issue**: The camera turns itself off shortly after being enabled.

**Fix**: On Windows, try the "Repair Camera" feature in the classroom. If the issue persists, the camera driver may be corrupted or outdated — contact your computer's after-sales support for the latest driver.

### 8. Camera video is upside-down
**Issue**: Camera video appears flipped upside-down.

**Try**:
- **Computer**: adjust the camera's physical angle.
- **Phone/tablet**: try rotating the device to restore the correct orientation.

### 9. Camera video is glitchy/scrambled
**Issue**: The camera video shows visual artifacts or scrambled pixels.

**Try**:
- **Repair camera (Windows)**: try the "Repair Camera" feature in the classroom.
- **Replace the device**: for external cameras, try re-plugging or switching USB ports.
- **Update the driver**: if the camera isn't physically damaged, contact your computer's after-sales support to update the driver. (To check if the camera itself is damaged, test it in another app like WeChat or QQ video call — if it's also glitchy there, the camera hardware may be faulty.)

### 10. Camera video is entirely gray
**Issue**: The camera window shows solid gray.

**Fix**: This is usually because the laptop's built-in camera has been physically disabled.
- **Lenovo laptops**: slide the physical camera switch next to the front camera to enable it.
- **Other brands**: press FN + the function key with a camera icon.

### 11. Black bars around the camera video
**Issue**: The camera window shows black bars around the edges of the video.

**Fix**: The teacher (or co-teacher) can go to Classroom Settings, hide the "Camera area," then show it again to restore normal display.

### 12. Camera shows a "laptop" icon
**Issue**: The camera window displays a laptop-shaped icon instead of video.

**Fix**: This is usually because the camera is disabled at the system level on the laptop, blocking all software from accessing it.

### 13. Camera shows a "lock" icon
**Issue**: The camera window displays a padlock icon instead of video.

**Fix**: This usually means the operating system has disabled camera access system-wide, blocking all software from using it.

### 15. Camera video is partially cut off
**Issue**: On a Huawei phone or tablet, opening the camera in the classroom shows a partially cropped/incomplete image.

**Fix**: Disable Split View / parallel windows mode for ClassIn: Settings > Display & Multitasking > Parallel Windows > More Settings, find ClassIn and turn it off, then re-enter the classroom.

### 16. Camera shows "ClassIn avatar + disabled icon"
**Issue**: The camera window shows only your ClassIn avatar plus a "disabled" icon.

**Fix**: This happens on lower-performance Android devices that can't support full video during class. To keep class running smoothly, the system reduces video streams — so you can only see yourself and the teacher, not other students.

### 17. Virtual background is unavailable for the camera
**Issue**: Using the camera's virtual background feature shows "unavailable."

**Try**:
1. **Check your OS version**: Mac needs 10.15 or later; Windows needs Windows 10 or later.
2. Once your OS version is confirmed, **update your graphics driver**.
3. If updating the driver doesn't fix it, contact ClassIn support for further troubleshooting.

Driver download links: NVIDIA, AMD, and Intel official driver support pages.

### 19. Can the teacher force students' cameras to default on?
**Q**: Can a teacher set students' cameras to be on by default, and prevent students from turning off their own cameras?

**A**: No — teachers cannot set a default-on camera for students, nor prevent students from turning off their own cameras.

<!-- DOC_BOUNDARY -->
```yaml
title: "FAQ: Playback Video"
source_title_zh: "【回放视频】常见问题"
```

## FAQ: Playback Video

### 1. Playback video is split into segments
**Issue**: A class playback is split into multiple segments, each covering part of the class, requiring the viewer to watch them in sequence.

**To avoid this in future recordings**:
- **Avoid leaving the classroom mid-session**: if a teacher leaves and re-enters the classroom during class, the recording restarts, splitting the playback.
- **Ensure a stable network**: an unstable connection can interrupt recording, which similarly causes splitting when the recorder has to restart.
- **Manage recording length**: recordings automatically split into a new segment after reaching 2 hours — plan your class segments accordingly.

Existing recordings can't be modified after the fact — the above tips apply to future recordings.

### 2. "This session is not public and cannot be viewed"
**Issue**: Watching a class playback via a web link shows "This session is not public and cannot be viewed."

**Fix**: This is usually because web playback permission hasn't been enabled. In the Admin Console (www.eeo.cn):
1. Go to "Session Management."
2. Find and enable the "Web Live Stream Permission" option.

### 3. "No playback video, please contact your school"
**Issue**: Watching a class playback in the client shows "No playback video, please contact your school."

**Try**:
- **Recording failure**: if the teacher's session failed to record (network or other issue), contact ClassIn support in the after-sales group, or call 400-077-1585.
- **Backend permission**: if the teacher did record but playback still isn't available, check whether the Admin Console allows client playback: log into the Admin Console (www.eeo.cn) > School Settings > enable "Class Playback."
- **Class never happened**: if the teacher didn't hold class as scheduled, contact the teacher directly to confirm.

### 4. "This video is being transcoded"
**Issue**: Watching a playback shows "This video is being transcoded, please try again later."

**Fix**: After class ends, the video needs to be processed before playback is available — typically around 30 minutes. Just wait and try again.

### 5. Overlapping PPT text in the playback
**Issue**: PPT text displayed in the classroom appears overlapping in the playback.

**Fix**: This usually happens when the teacher drags courseware partially outside the classroom's visible boundary during class. Avoid dragging courseware beyond the classroom edges while teaching.

### 6. Error 17: "Invalid data found when processing input"
**Issue**: Watching a playback shows "Error: 17, Invalid data found when processing input."

**Fix**: This can be caused by an unstable network connection. Improve your network connection and try again.

### 7. No playback button in the app
**Issue**: A finished class shows no playback button on the schedule.

**Fix**: This happens when cloud recording wasn't enabled for that session, so no playback video was generated. When scheduling future classes, make sure to enable "Cloud Recording" and select a recording mode — the playback video and its button will be generated automatically once class ends.

### 8. Playback video is only partially visible
**Issue**: The playback video shows only half of the classroom screen.

**Fix**: When recording, make sure the classroom window fully fits within the primary monitor's screen area, without extending beyond it. If the teacher uses multiple monitors, keep the classroom window on the primary monitor throughout — don't drag it to a secondary display.

### 9. Playback video is completely black, but audio plays
**Issue**: The playback shows a black screen, but you can hear recorded audio.

**Try**:
- If using multiple monitors, make sure the classroom window wasn't dragged to a secondary display.
- Avoid playing a local PPT while using screen sharing during recording — this combination can cause a black screen.

### 10. The playback video shows desktop content
**Issue**: The recorded playback includes not just the classroom, but also parts of the computer desktop.

**To avoid this**:
1. Open the ClassIn client and click Settings (bottom-left).
2. Go to System Settings > Classroom Settings.
3. Under "Recording area," check "Current-size classroom window."

Note: if screen sharing is used during recording, the recording will include the entire desktop regardless of this setting.

### 11. The playback video includes other software's sound
**Issue**: The playback includes sounds unrelated to class, such as sounds from video sites or chat app notification tones.

**To avoid this**:
1. Open the ClassIn client and click Settings (bottom-left).
2. Go to Advanced Settings.
3. Under "Recording mode," select "App sound only."

### 12. Playback video looks blurry
**Issue**: The recorded playback video quality is poor and looks blurry.

**Fix**: Before recording, open ClassIn Settings > System Settings > Advanced Settings, and under "Recording resolution," select "Full HD." This significantly improves the quality of future recordings.

### 13. "Sorry, video interrupted"
**Issue**: Watching the playback shows "Sorry, video interrupted, please wait..."

**Try**:
- Avoid minimizing the classroom window during recording, and avoid letting other windows fully cover it.
- If the teacher can't avoid minimizing, temporarily check "Entire desktop" under "Recording area" in app settings instead — note this will record everything on the desktop during class.

### 15. Playback video flickers
**Issue**: The playback video occasionally flickers.

**Try**:
- Avoid dragging the classroom window outside the screen boundary while recording.
- On Mac with a touchscreen, avoid the three-finger screen-switch gesture; on Windows, avoid switching virtual desktops during recording.

### 16. Playback has teacher's voice but not students' voices
**Issue**: The playback clearly has the teacher's voice, but student voices are missing or very faint — even though students were audible clearly during the live class.

**Fix**: This happens when recording used "System sound" as the audio source — if the teacher's system speaker volume was low, student voices captured through it will be very quiet or missing. Before recording, go to app settings and switch the recording audio source to "App sound" instead — this captures audio from all participants directly, improving playback quality.

### 17. Playback audio cuts in and out
**Issue**: The playback occasionally has no sound, even though audio was fine throughout the actual class.

**Fix**: This happens when the recording mode is "System sound," and the teacher temporarily muted their system speaker during class — this also mutes the recording. Before entering the classroom to record, go to ClassIn Settings (bottom-left) > System Settings > Advanced Settings, and under "Recording mode," switch to "App sound." This makes the recording independent of the system speaker's mute state.

### 18. Playback video is entirely gray
**Issue**: The playback shows a solid gray screen instead of the classroom.

**Fix**: This usually happens when macOS prompts for screen-recording permission during a screen/window switch, and the teacher didn't respond to it in time. Before recording, pre-authorize ClassIn for screen recording:
1. Open System Preferences.
2. Go to Security & Privacy.
3. Click "Screen Recording" in the left sidebar.
4. Find ClassIn in the app list on the right and check it.

### 19. "Failed to load, please try refreshing"
**Issue**: Watching a playback in the client shows "Failed to load, please try refreshing."

**Fix**: This is usually because some Android devices don't support viewing ClassIn's playback file format. Try watching on a computer or another compatible device instead.

### 20. Playback video is entirely green
**Issue**: On iPad or iPhone, the playback shows a green screen.

**Fix**: This is a compatibility issue specific to iOS 16.1. Update your device to the latest iOS version to resolve it.

### 21. Playback video is incomplete
**Issue**: The class playback video is incomplete.

**Try**:
- **Unstable network**: the teacher's connection may have been unstable, interrupting the recording. Check and improve the network before the next class.
- **Plugging/unplugging devices**: plugging or unplugging headphones/headsets during recording can interrupt it — avoid this while recording.
- **Other causes**: if the above doesn't resolve it, the teacher can report the issue to the ClassIn Assistant in the after-sales support group for further investigation.

<!-- DOC_BOUNDARY -->
```yaml
title: "FAQ: Download & Installation"
source_title_zh: "【下载安装】常见问题"
```

## FAQ: Download & Installation

### I. Computer

#### (1) Download issues

**1. Can't open the website**
**Issue**: The browser shows "This site can't be reached" when visiting the ClassIn website.

**Try**:
- **Check the URL**: make sure you're using the correct address: www.eeo.cn
- **Check your network connection**: try another website to confirm your network is working. If other sites also fail, your network connection may be the issue — try another network or contact your ISP.

**2. Can't find ClassIn in the App Store**
**Issue**: Searching the Mac App Store doesn't find ClassIn.

**Fix**: Download from the official website (www.eeo.cn) in your browser instead — ClassIn's desktop app isn't distributed via the Mac App Store.

**3. Download stalls or stops**
**Issue**: The ClassIn download stays at 0% or suddenly stops partway through.

**Try**:
- **Check your network connection**: try another site to confirm your network works. If not, switch networks.
- **Use the official source**: make sure you're downloading from www.eeo.cn — third-party download sites can cause issues. Re-download from the official site if needed.

#### (2) Windows installation issues

**1. "Windows cannot open this file"**
**Fix**: This is usually because the installer hasn't finished downloading. Wait for the download to complete, then run the installer again.

**2. "Another program is using this file"**
**Try**:
- Confirm the installer finished downloading before installing.
- If the issue persists, delete the existing installer, restart your computer, and re-download the latest installer from www.eeo.cn.

**3. "This program isn't supported on this platform"**
**Fix**:
1. Delete the downloaded installer.
2. Go to www.eeo.cn.
3. Re-download the Windows installer.
4. Follow the installation wizard again.

**4. Clicking the installer does nothing**
**Fix**: Right-click the installer and choose "Run as administrator."

**5. Installation progress stuck**
**Fix**:
1. Close the ClassIn installer window.
2. Go to the ClassIn install directory (default: C:\Program Files\ClassIn, unless you chose a custom path).
3. Find and delete the file named "2574." If deletion fails, restart your computer and try again.
4. Run the ClassIn installer again.

**6. "Setup cannot create the directory"**
**Try**:
- Right-click the installer and choose "Run as administrator."
- Don't use "Quick Install" — instead, click "Custom Install" in the bottom-right of the installer, then "Browse," and choose a drive other than C for installation.

**7. "The drive or UNC share you selected does not exist or cannot be accessed"**
**Fix**: This usually happens when trying to install to a network drive. Reinstall ClassIn:
1. Click "Custom Install" in the bottom-right of the installer.
2. Click "Custom Install."
3. Choose a local drive (e.g. C: or D:) as the install location.

**8. "Unable to write to the registry"**
**Try**:
1. Restart your computer.
2. Close all antivirus/security software (e.g. 360 Security Guard, 360 Antivirus, Tencent PC Manager, Microsoft PC Manager, 2345 Security Guard, Lenovo PC Manager).
3. Run the ClassIn installer again.

**9. "Unable to run the file, please check file association"**
**Fix**: Right-click the installer and choose "Run as administrator."

**10. "Windows protected your PC"**
**Fix**: In the popup, click "Run anyway."

**11. Blue screen**
**Fix**: ClassIn itself does not modify any system settings. If you experience a blue screen during installation, contact your computer's after-sales support for further diagnosis.

**12. "The setup files are corrupted. Please obtain a new copy of the program."**
**Fix**: The installer you downloaded may be corrupted. Delete it and re-download the latest installer from www.eeo.cn.

#### (3) Mac installation issues

**1. Clicking ClassIn does nothing**
**Fix**: After running the installer, drag the ClassIn icon into the Applications folder in the installer window, then continue with installation.

**2. "'ClassIn.app' cannot be opened because the developer cannot be verified"**
**Fix**:
1. Open System Preferences.
2. Go to Security & Privacy.
3. Click the lock icon in the bottom-left and enter your admin password.
4. Under "Allow apps downloaded from," select "Anywhere."
5. Reinstall ClassIn.

### II. Mobile

#### (1) iPad & iPhone

**1. Can't find ClassIn in the App Store**
**Try**:
- Make sure you're in the App Store (not a third-party "Apple Store") and search again.
- If your device is jailbroken, restore it to a non-jailbroken state via after-sales support, then search the App Store again.

**2. "This app requires iOS 11.0 or later"**
**Fix**: Update your device to iOS 11.0 or later. If your current version is below 11.0, first check ClassIn's system requirements to confirm your device is eligible — if not, temporarily use a device that meets the requirements.

**3. "Unable to download app"**
**Try**:
- Try a different network and re-download.
- Change your device's DNS settings: Settings > Wi-Fi > tap your connected network > DNS, and set it to "114.114.114.114" or "199.91.73.222," then retry the download.

**4. "Unable to update app"**
**Fix**: Uninstall the currently installed ClassIn app, then re-download and reinstall it from the App Store.

**5. "The iTunes Store is unable to process purchases at this time"**
**Try**:
- Try downloading a different app — if that also fails, refer to Apple's troubleshooting steps for this error.
- If the issue persists after troubleshooting, contact Apple Support: 400-666-8800.

#### (2) Android & HarmonyOS

**1. "Package appears to be corrupt"**
**Fix**: This usually means your device's Android version is below 7.0, which ClassIn doesn't support. Use a device running Android 7.0 or later. Check ClassIn's system requirements if you're unsure whether your device qualifies.

**2. "There was a problem parsing the package"**
**Fix**: Same cause and fix as above — usually an Android version below 7.0.

**3. "This app is currently unavailable for download"**
**Fix**: Same cause and fix — usually an Android version below 7.0.

**4. "ClassIn installation failed, please retry"**
**Fix**: Same cause and fix — usually an Android version below 7.0.

**5. "System restriction"**
**Fix**: Same cause and fix — usually an Android version below 7.0.

**6. "App not installed"**
**Fix**: Same cause and fix — usually an Android version below 7.0.

**7. Download button shows "Retry"**
**Fix**: Same cause and fix — usually an Android version below 7.0.
