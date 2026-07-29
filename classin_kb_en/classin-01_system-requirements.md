---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: ClassIn (Client)
subcategory: "1. System Requirements & Device Info Lookup"
batch: 10 of N
translated_from: zh-CN (source: ClassIn/1._配置要求与查询)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# 1. System Requirements & Device Info Lookup

<!-- DOC_BOUNDARY -->
```yaml
title: "Looking Up Device Info: Specs, Benchmark Score, Network Speed, Chip Model"
source_title_zh: "设备信息查询：配置，跑分，网速，芯片型号"
```

## Looking Up Device Info: Specs, Benchmark Score, Network Speed, Chip Model

## I. Checking Your Computer's Specs

### When to use this
Checking your computer's specs means reviewing its hardware and system details to confirm it meets the requirements for a specific piece of software. If you use a computer, you can refer to the hardware parameters in "System Requirements" and compare them against your own computer's specs to confirm whether it can run ClassIn.

### Steps

**(1) Windows computer**
1. Right-click "This PC" on the desktop.
2. Select Properties.
3. Under Device Specifications, check the RAM capacity and CPU model.

![](https://cofile.eeo.cn/res-store%2F207d74d5f0e039ef1498ace4e289f42cb4e480653d840eb3c47df6733319d61b_254401?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=82c2969925bd7134ba35e3fb67c100d9ed687e63)

**(2) Mac computer**
1. Open Launchpad.
2. Type "Terminal" in the search field, then open the Terminal app.
3. In the Terminal window, next to the prompt (e.g. `LeondeMacbook-Air:~ shouhouzhichi$`), type `sysctl machdep.cpu.brand_string`.
4. Press Enter.
5. The output will show your computer's CPU model.

![](https://cofile.eeo.cn/res-store%2Fd8e2f7bd40c5df5a8612c7bb3e852b5d2fe0243d74dcf5560cb1859dd34fcea5_361026?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=24d5c2fa2a2f9e340e6f51170e22071a2f610772)

## II. Checking Your Network Speed

To ensure a stable connection while using ClassIn for online teaching or learning, please check your network before you start. Testing and optimizing your network settings in advance helps ClassIn run smoothly and supports your online teaching.

### Usage Notes
The key metrics to look at in your test results are: upload speed, download speed, latency, jitter, and packet loss rate. If your network doesn't meet all of the following requirements at once, you may experience connection instability or frequent disconnects while using ClassIn, which can affect the quality of your class.

| Minimum Network Requirements |
| --- |
| Upload speed: at least 2Mbps |
| Download speed: at least 2Mbps |
| Latency: within mainland China, no more than 50ms; outside mainland China, no more than 300ms |
| Packet loss: must be 0% |

1. Open your browser.
2. Enter the following in the address bar: https://www.speedtest.cn
3. Click Test Speed.

![](https://cofile.eeo.cn/res-store%2F46e397fb953659ed33b6119718556f27b879769eae8acb042399cad96d359215_366221?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=1c368b8a4de4a408039fe6447a6a79dccd3d22eb)

## III. Checking Your Device's Benchmark Score

### When to use this
Based on your computer's CPU model, you can look up its performance benchmark score on a dedicated CPU benchmark site to determine whether it can support ClassIn running normally.

### Usage Notes
Teachers' computers need a CPU benchmark score of 6000 or higher.

Students' computers need a CPU benchmark score of 4000 or higher.

### Steps
1. Go to https://www.cpubenchmark.net/cpu_list.php in your browser's address bar.
2. Enter your computer's CPU model in the search box.
3. Click Find CPU to search.
4. In the highlighted area on the left, find the option that exactly matches your computer's CPU model.
5. Check the value in the CPU Mark column on the right — that's your CPU's performance benchmark score.

![](https://cofile.eeo.cn/res-store%2F57ebd37b9391dcc022dca39ec54aa02be8efe5a589e51f54dec7efb985ed1179_379263?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a6179c425172f8f5c7289fccf95558b10e6f3f36)

## IV. Checking Your Mac's Chip Model

ClassIn offers two installer packages for Mac: one for Intel-based Macs, and one for Apple silicon Macs (M1, M2, and so on). Before downloading an installer, you need to confirm your computer's processor type so you can pick the right one.

1. Hover over the Apple icon in the top-left corner of your screen.
2. Click About This Mac in the menu.
3. In the About This Mac window, check the CPU chip model next to Processor.

![](https://cofile.eeo.cn/res-store%2Fa123ab72dc9c959fe87db4f2f7e97e2c25cae4e4e015a92b5a98d9815a6cfc25_461854?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=9a884733f148e07102c7b71df32b6837e017f04e)

<!-- DOC_BOUNDARY -->
```yaml
title: "System Requirements"
source_title_zh: "配置要求"
```

## System Requirements

## I. What Are System Requirements?

System requirements refer to the specific hardware and software conditions a device needs to meet in order to run the ClassIn software. These requirements typically cover key elements such as the processor, memory, and operating system, which are the basic conditions for the software to run properly. Hardware requirements also vary depending on class size: as the number of on-stage participants in ClassIn increases, so do the hardware requirements needed to keep the software running stably and smoothly.

## II. Computer Requirements

| | Minimum requirements (students / teachers not recording) | Minimum requirements (teachers recording) | Recommended requirements (teachers / students) |
| --- | --- | --- | --- |
| Processor | Intel 8th-gen i3 or higher; AMD Ryzen 3 2nd-gen or higher | Intel 8th-gen i5 or higher; AMD Ryzen 5 1st-gen or higher | Intel 9th-gen i7 or higher; AMD Ryzen 7 2nd-gen or higher |
| Memory | Windows: 8GB RAM or higher; Mac: 4GB RAM or higher | Windows: 16GB RAM or higher; Mac: 4GB RAM or higher | Windows: 16GB RAM or higher; Mac: 8GB RAM or higher |
| OS | Windows 7 or higher; macOS 10.13 or higher | Windows 7 or higher; macOS 10.13 or higher | Windows 10 or higher; macOS 12 or higher |
| Display resolution | At least 1280 x 720 | At least 1280 x 720 | At least 1920 x 1080 |
| Network bandwidth | At least 2Mbps | At least 4Mbps | At least 6Mbps |

## III. Phone/Tablet Requirements

| | Minimum requirements (students / teachers not recording) | Minimum requirements (teachers recording) | Recommended requirements (teachers / students) |
| --- | --- | --- | --- |
| OS | iOS 11 or higher; Android 7.0 or higher; HarmonyOS 1.0 or higher | iOS 11 or higher; Android 10.0 or higher; HarmonyOS 2.0 or higher | iOS 14 or higher; Android 10.0 or higher; HarmonyOS 2.0 or higher |
| Memory | Android: 4GB or higher; iPad/iPhone: 2GB or higher | Android: 8GB or higher; iPad/iPhone: 2GB or higher | Android: 8GB or higher; iPad/iPhone: 3GB or higher |
| Processor | iPad/iPhone: A9 or higher. Android: Qualcomm Snapdragon 7-series 730G or higher; Snapdragon 8-series 835 or higher; Kirin 8-series 810 or higher; Kirin 9-series 970 or higher; MediaTek Dimensity 720 or higher; MediaTek Helio G90T or higher. | iPad/iPhone: A11 or higher. Android: Snapdragon 8-series 855 or higher; Kirin 9-series 980 or higher; MediaTek Dimensity 1000 or higher. | iPad/iPhone: A12 or higher. Android: Snapdragon 8-series 865 or higher; Kirin 9-series 9000 or higher; MediaTek Dimensity 1100 or higher. |
| iPad/iPhone models | iPhone 6 or later; iPad 5 or later; iPad mini 4 or later; iPad Air 3 or later; iPad Pro or later. | iPhone 8 or later; iPad 6 or later; iPad Pro or later. | iPhone XS or later; iPad 8 or later; iPad Pro 2 or later; iPad mini 5 or later; iPad Air 3 or later. |
| Network bandwidth | At least 2Mbps | At least 4Mbps | At least 6Mbps |

## IV. Recommended Devices for ClassIn X

Recommended device performance varies by teaching scenario:

**Dual-teacher classroom**

![](https://cofile.eeo.cn/res-store%2F17766803a0c8c5cd1f6c361665599b60b57c960ecb9b915fcbb19071f3a640fd_100043?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=329f9adba452c88a144b07c0f7ec43fd3ac41910)

**Standard in-person teaching**

![](https://cofile.eeo.cn/res-store%2Fb8f0fd78dc217d592076750452affe93afff5f6def42a2f944e1047a904446df_119426?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=8c223e25fd4fb3ac83c68d1295ae42eee76c9cb6)

With minimum specs, supported features include: pen tool, courseware (PPT/PDF/audio-video, etc.), scan-to-share images, auxiliary camera, and other basic teaching tools.

With minimum specs, Nobook and Video Wall are not recommended.

With recommended specs, all features can be used.

## V. Recommended Devices for Dual-Teacher Teaching

The dual-teacher classroom model — a new exploration combining online and in-person teaching — became mainstream in 2015. By splitting the roles between an online lead teacher and an in-person homeroom/facilitation teacher, the dual-teacher classroom lets excellent teachers teach across regions.

![](https://cofile.eeo.cn/res-store%2F7cd38a3d4277c24347b109ecad3e542b9e0224e85e797599f5d990e83e919dd0_885358?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=a1c3b82b8bbb05039045350426d371e43dfc79a4)

An increasing number of partners are choosing ClassIn as their interaction tool for dual-teacher classrooms. To help users get the best teaching experience, we recommend the following hardware procurement plan:

![](https://cofile.eeo.cn/res-store%2F6ef3fbf38d682224d94a4f0f45a0fec73d64e410cda3072a5a13883bf3ebeba4_138418?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ee9c1339eb20a8b7f5866e5e316484816f6d3223)

## VI. Recommended Devices for Remote Meetings

EEO is committed to building the most professional online classroom product. In practice, ClassIn is also a very stable and convenient remote meeting system.

To help ClassIn users get a better remote meeting experience, we recommend the following hardware based on our own usage experience.

![](https://cofile.eeo.cn/res-store%2Fdbd247b10b9b7e07ce4cf454f8b05bbcb1171ec9932abbf8821dc1f6cda00f58_279364?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=ea97775d29e905af9a38f5fbd29b6bdcc69745c3)

![](https://cofile.eeo.cn/res-store%2F786974847dfd91a935b2103049e4c3db4af2bffee859539e13be64d9c1e84aa9_265608?q-sign-algorithm=sha1&q-ak=AKIDJQGsEOK2TfbFdEZifMnxrWx85mpdHj6H&q-sign-time=1773936000;1774540800&q-key-time=1773936000;1774540800&q-header-list=host&q-url-param-list=&q-signature=41dda5ec9a238fdc43a21bdc9cd0f65f04c659aa)

*Disclaimer: The information here is a summary of practical experience from EEO's own pilot schools. It does not cover every product on the market and is not a formal product review — for reference only.*
