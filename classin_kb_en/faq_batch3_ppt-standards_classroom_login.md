---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: FAQ
batch: 3 of N
translated_from: zh-CN (consolidated knowledge base)
---

# FAQ: PPT Courseware Production Standards, Classroom, Login

<!-- DOC_BOUNDARY -->
```yaml
title: "PPT Courseware Production Standards"
source_title_zh: "PPT课件制作标准"
```

## PPT Courseware Production Standards

### Recommended tools
Use PowerPoint 2013 or later. PPTs made with WPS, Keynote, or other third-party tools may fail to convert after uploading to ClassIn, or may display incorrectly in the classroom.

### File size limit
Each PPT file must not exceed 500MB.

### Content that isn't supported or isn't recommended
- **Flash is not supported**: SWF-format Flash animations are no longer supported by any modern system.
- **Long audio is not supported**: long audio clips are more likely to fail to load or fail to end correctly, disrupting class. Keep audio clips under 10 minutes.
- **Large GIFs are not supported**: a GIF over 1MB (or especially 5MB+) uses a lot of memory and can cause the classroom to lag or crash during playback.
- **Unusual image formats are not supported**: use PNG or JPG. Other formats aren't guaranteed to display consistently across devices — e.g. SVG may render at the wrong scale on iOS.

### Fonts supported in ClassIn
See the attached document for the supported font list.

### Text editing guidelines
1. For fill-in-the-blank underlines, use the underscore character sequence "_ _ _ _ _" (Shift + hyphen) — underlines created by applying an underline style to spaces will convert to blank space with no visible line.
2. Avoid "Distributed" text alignment to space out text evenly — after conversion it reverts to left-aligned, which won't look as intended.
3. Use the default line height of 1.0 — text or text boxes with a non-1.0 line height may not align horizontally with other elements and can shift slightly out of vertical alignment. If you don't need custom line height, the default works fine.

### Supported video formats for PPT
MP4, 3GP, MPG, 3G2, AVI, WMV, MOV, MPEG, M4V, QT

### Image editing
1. Avoid using PowerPoint's built-in image editing tools (e.g. border effects) on GIFs — any editing applied to a GIF will cause it to stop animating after conversion.
2. **Page borders**: if you insert a shape as a border, send it to the back layer — otherwise it can block click-triggered animations elsewhere on the page (the transparent center of the converted shape can still interfere with click layering).
3. Invisible elements are not supported — delete any element you don't want visible rather than hiding it, or it will reappear after conversion and disrupt the layout.

### Notes on adding animations
1. Animations with a transition effect convert more reliably in the correct order. (Currently, only "Appear" and "Disappear" have no transition effect — shown as green or red triangle icons in the Animation Pane.)
2. Avoid selecting a text range with the cursor to apply an animation — this can cause unexpected animation behavior. Instead, click the edge of the text box to select the whole box, then animate the box.
3. Avoid grouping an element after giving it a click trigger — this will prevent the click trigger from working.
4. Infinite-loop animations are not supported — after conversion they'll only play once. If you need multiple repeats, set the loop count to 999 instead of infinite.

### Screen size and clarity settings

**1. How do I make the PPT fill the whiteboard completely in the ClassIn classroom?**
- Standard full-screen PPT size: width 31.75cm × height 13.851cm
- Sharper full-screen PPT size: width 63.5cm × height 27.7cm
- Full-screen size with the roster hidden: width 63.5cm × height 32.1cm, or width 63.5cm × height 33.4cm

Note: a larger PPT size gives a sharper image, but also requires a better network connection for both teacher and students to load it smoothly.

**2. Adjust the PPT size locally on your computer** using PowerPoint's slide size settings.

### Common playback issues

**Issue 1**: In the classroom, the PPT can only be advanced with the on-screen button — clicking the slide itself doesn't turn the page.
**Fix**: In the Transitions tab, check "On Mouse Click."

**Issue 2**: The PPT auto-plays and automatically jumps to the next slide.
**Fix**: In the Transitions tab, uncheck "Set Automatically After [time]."

**Issue 3**: In a WPS-created file, even transitions set to "None" show a 2-second duration.
**Fix**: Select all slides, set the transition to any other effect, then set it back to "None." The duration should now show "Automatic," meaning it's fixed.

**Issue 4**: Animations play in the classroom, but not when playing the PPT locally.
**Fix**: In Slide Show settings, uncheck "Show without animation."

### PPT display glitches
See the reference screenshot for common visual glitches and how to identify them.

### PPT watermark issue
**Issue**: The PPT has no watermark when played locally, but a watermark appears after uploading to ClassIn.
**Fix**: Open the PPT locally, go to View > Slide Master, find the slide containing the watermark, and delete the watermark element from the top layer.

<!-- DOC_BOUNDARY -->
```yaml
title: "FAQ: Classroom"
source_title_zh: "【教室】常见问题"
```

## FAQ: Classroom

### 1. Clicking "Start Class" does nothing — can't enter the classroom
**Issue**: Finding the class in the message list and clicking "Start Class" has no effect — the classroom won't open.

**Computer**, try any of the following:
- **Log back into ClassIn**: quit ClassIn, then restart and log in again.
- **Close antivirus/security software**: e.g. 360 Security Guard, 360 Antivirus, Tencent PC Manager, 2345 Security Guard, Microsoft PC Manager, Lenovo PC Manager, etc.
- **Disable the firewall** in your computer's settings.

**Phone/tablet**, try any of the following:
- **Restart the device**, then log back into ClassIn.
- **Check your device specs**: lower-end phones/tablets may fail to enter the classroom — confirm your device meets ClassIn's minimum requirements.

### 2. Class is very laggy
**Issue**: Video playback in the classroom is choppy or freezes frame-by-frame, and other people's audio may be choppy or cut out intermittently.

**Computer**:
- **Close other programs**: run only ClassIn.
- **Close antivirus/security software**: e.g. 360 Security Guard, 360 Antivirus, Tencent PC Manager, 2345 Security Guard, Microsoft PC Manager, Lenovo PC Manager, etc.
- **Restart your computer.**
- **Plug in power**: for laptop users — low battery can trigger automatic power-saving that causes lag.
- **Improve cooling**: for laptop users — add a cooling pad/stand.

**Phone/tablet**:
- **Restart the device.**
- **Close other apps**: close all background apps, run only ClassIn.
- **Try a different device** if the issue persists after the above — the current device may not have enough performance.

### 3. Stuck on "Syncing classroom info" after entering
**Issue**: After entering the classroom, the system keeps showing "Syncing classroom info" and you can't proceed.

**Try**:
- **Log back into ClassIn**: close the classroom and the app, then log in again.
- **Close antivirus/security software.**
- **Disable the firewall** temporarily.
- **Restart your router**: unplug it, wait a few seconds, then plug it back in.
- **Switch networks**: on a laptop, try a wired connection or a phone's 5G hotspot.
- **Simplify the classroom whiteboard**: if there's a lot of content on the whiteboard, have the teacher delete or save-and-clear the board, then have students re-enter.
- **Move closer to the router** (phone/tablet) for a stronger signal.
- **Switch networks** (phone/tablet): disconnect Wi-Fi and try mobile data instead.
- **Restart the device** (phone/tablet).

### 4. "Syncing classroom info" appears repeatedly during class
**Issue**: While in class, "Syncing classroom info" appears repeatedly.

**Try**:
- **Close antivirus/security software.**
- **Disable the firewall** to ensure smooth network communication.
- **Restart your router.**
- **Improve your network connection**: on a laptop, try a wired connection or a phone's 5G hotspot.
- **Move closer to the router** (phone/tablet).
- **Switch networks**: e.g. disconnect Wi-Fi and use mobile data instead.

### 5. Classroom screen completely freezes during class
**Issue**: On computer, the classroom screen suddenly freezes completely and stays frozen.

**Try**:
- **Run only ClassIn**: close all other programs to free up system resources.
- **Close antivirus/security software.**
- **Disable the firewall** temporarily.
- **Plug in power** (laptop) — low battery can cause power-saving lag.
- **Improve cooling** (laptop) — add a cooling pad to prevent thermal throttling.

### 6. Classroom display is cut off / incomplete
**Issue**: On computer, the classroom interface displays incompletely — the toolbar doesn't show, and sometimes the left or right side of the screen is missing.

**Fix**: Set your screen resolution to 1280×720 or higher.

### 7. Tablet won't go full screen
**Issue**: On a tablet, the classroom doesn't fill the screen and stays centered in a smaller box.

**Fix**:
1. Open your tablet's Settings.
2. Go to Apps.
3. Find and open ClassIn in the app list.
4. Check for a "Landscape mode" option. If present, set it to "Adaptive."
5. If there's no such option, pull down the notification shade and enable "Auto-rotate."

### 8. How much mobile data does one class use?
**Q**: About how much data does one class use over mobile data?

**A**: Roughly 100–200MB per class. With higher video quality or multiple participants using HD video, this can rise to several hundred MB or more. This data comes from the mobile plan of whichever teacher or student is using mobile data.

### 9. Can a "co-teacher" start class early?
**Q**: If the main teacher hasn't entered the classroom yet, can a co-teacher enter and start teaching early?

**A**: Yes, a co-teacher can enter early and start teaching. However, a co-teacher cannot start cloud recording. If the class has cloud recording and live streaming enabled, viewers using the live-stream link can only watch once the main teacher has entered the classroom and started recording.

### 10. Can teachers hold class from the website without downloading ClassIn?
**Q**: Can a teacher teach directly from the website without downloading ClassIn?

**A**: No — teachers must download and install the ClassIn client to enter the classroom and teach.

### 11. A tool's window disappears the instant it's opened
**Issue**: Opening certain tools in the classroom — especially ones with a popup prompt — causes the tool window to disappear immediately.

**Fix**: This is usually caused by 360 Security Guard's popup-blocking feature. Try temporarily exiting 360 Security Guard.

### 12. Sharing one account among multiple students
**Q**: Can one account be used by multiple students for class?

**A**: Whether this works depends on scheduling. If multiple students' class times overlap, one account cannot serve multiple classrooms at once, since an account can only be in one classroom at a time. If their class times don't overlap, it's technically possible to share an account.

That said, sharing an account among multiple students is not recommended — it can cause teaching data and student information (such as names) to become mixed up, affecting teaching quality and each student's personalized learning experience.

<!-- DOC_BOUNDARY -->
```yaml
title: "FAQ: Login"
source_title_zh: "【登录】常见问题"
```

## FAQ: Login

### 1. "Login" button is grayed out
**Issue**: After entering your username and password, the "Login" button stays grayed out and can't be clicked.

**Try**:
- **Wait a moment** — this can be caused by a slow network connection.
- **Close antivirus/security software**: e.g. 360 Security Guard, 360 Antivirus, Tencent PC Manager, 2345 Security Guard, Microsoft PC Manager, Lenovo PC Manager, etc.
- **Disable the firewall** temporarily.
- **Restart your router.**
- **Try a different network**: on a laptop, try a wired connection or a phone's 5G hotspot.

### 2. Stuck showing "Logging in..."
**Issue**: After clicking "Login," the app is stuck showing "Logging in..." and never completes.

**Try**:
- **Wait a moment** — this can be a slow network connection.
- **Close antivirus/security software.**
- **Disable the firewall** temporarily.
- **Restart your router**, then reconnect.
- **Try a different network**: wired connection or a phone's 5G hotspot.
- **Switch server**: in the bottom-right of the login screen, click "More settings" and try logging in with one of the first three servers under AUTO.

### 3. Login window is unresponsive (Mac)
**Issue**: On Mac, the ClassIn login window freezes — no buttons respond and text can't be entered.

**Fix**:
1. Open System Preferences.
2. Go to Accessibility.
3. Click "VoiceOver" in the left sidebar.
4. Uncheck "Enable VoiceOver."

### 4. Error: "Weak network, please check your network settings"
**Issue**: Opening the ClassIn login screen shows "Weak network, please check your network settings."

**Try**:
- **Close antivirus/security software.**
- **Disable the firewall** temporarily.
- **Restart your router.**
- **Switch networks**: on a laptop, try a wired connection or a phone's 5G hotspot.

### 5. Error: "Incorrect password"
**Issue**: Entering your username and password and clicking "Login" returns "Incorrect password."

**Try**:
- **Double-check your password**, paying attention to letter case.
- **Double-check your username**, especially for accidental leading/trailing spaces.
- **Reset your password**: click "Forgot password" on the login screen and follow the steps.

### 6. Error: "Account does not exist"
**Issue**: Entering your username and password returns "Account does not exist."

**Try**:
- **Double-check the username**, and check for extra spaces before/after it.
- **Check whether the account is registered** — if not, click "Register now" on the login screen.
- **Check the country/region code**: e.g. Mainland China is +86 — refer to a country code list for others.

### 7. Error: "Not enough space on drive C, please clean up and reopen ClassIn"
**Issue**: Launching ClassIn shows: "Not enough space on drive C, please clean up disk space and restart ClassIn."

**Try**:
- **Free up space on drive C**: remove unnecessary files and applications.
- **Reinstall ClassIn**: uninstall the current copy, then download the installer from the official site and install ClassIn on a drive other than C.

### 8. Error: "ClassIn.exe - System Error"
**Issue**: On Windows, launching ClassIn shows: "ClassIn.exe - System Error."

**Try**:
- **Install the wlanapi.dll file**: download it from a trusted source, copy it to the specified system folder per the guide, then open Run (Win+R) and register it with the appropriate command.
- **Reinstall Windows**: back up your data, then do a clean reinstall of Windows if the above doesn't resolve it.

### 9. Login window shows garbled text
**Issue**: All text in the login window displays as garbled characters.

**Fix**: Right-click the ClassIn icon and choose "Run as administrator."

### 10. Error: "No permission" (QR code login)
**Issue**: Using the QR code login option and scanning it with your phone shows "No permission."

**Fix**: Update the ClassIn client to the latest version:
1. Log into the ClassIn client using your username and password.
2. Update the client after logging in.
3. If the update fails, uninstall the current version and download the latest installer from www.eeo.cn.

### 11. ClassIn opens but shows nothing
**Issue**: On phone or tablet, launching ClassIn shows a blank white screen with nothing loading.

**Fix**: Restart your device, then relaunch ClassIn.

### 12. Error: "Failed to get web server"
**Issue**: On phone or tablet, logging in shows "Failed to get web server."

**Try**:
- **Check your network connection** — try opening any website to confirm.
- **Restart the device.**
- **Move closer to the router.**
- **Restart your router**: power it off, wait a few seconds, then power it back on.
- **Switch networks**: disconnect Wi-Fi and try mobile data (or a phone's 5G hotspot on tablet).
- **Check network permissions**: make sure ClassIn is allowed to access the network on your device.

### 13. Error: "Unable to get server address"
**Issue**: On phone or tablet, logging in shows "Unable to get server address."

**Try**:
- **Check your network connection.**
- **Restart the device.**
- **Move closer to the router.**
- **Restart your router.**
- **Switch networks**: disconnect Wi-Fi and try mobile data (or a phone's 5G hotspot on tablet).

### 15. Error: "Currently unable to log in, please try again later"
**Issue**: On phone or tablet, logging in shows this message.

**Try**:
- **Check your network connection** by opening any website.
- **Switch networks**: disconnect Wi-Fi and use mobile data instead (or a phone's 5G hotspot on tablet).

### 16. Error: "Please disable your proxy and try again"
**Issue**: On phone or tablet, logging in shows "Please disable your proxy and try again."

**Try**:
- Check whether VPN is enabled on your device.
- If enabled, turn it off and try logging in again.
- If the issue persists after disabling VPN, contact ClassIn support for further help.

### 19. Error: "Time limit"
**Issue**: On an iPhone or iPad, opening ClassIn shows "Time limit."

**Fix**: This appears when Screen Time app limits have been set for ClassIn. Try either of the following:
- On the limit screen, tap "Ignore Limit" at the bottom, then choose "Ignore Limit For Today" to open ClassIn normally.
- To remove the limit entirely: open Settings > Screen Time > App Limits, find ClassIn, and turn off its limit.
