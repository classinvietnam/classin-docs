---
kb_name: ClassIn Help Center Knowledge Base
language: en-US
category: More Usage Guides
subcategory: "OBS Usage Guide"
batch: 46 of N
translated_from: zh-CN (source: 更多使用说明/OBS_使用说明.md)
glossary_ref: classin_glossary_zh-ja-ko-en.json
---

# OBS Usage Guide

<!-- DOC_BOUNDARY -->
```yaml
title: "OBS Usage Guide"
source_title_zh: "OBS 使用说明"
```

## OBS Usage Guide

# I. Streaming a Livestream Using OBS

Streaming with OBS means the user first gets ClassIn's class session stream-push URL and adds it to OBS. Once the corresponding ClassIn class session starts, the user can use OBS to capture their computer desktop or a specific app's window and start streaming. This way, students watching the livestream via the ClassIn web link will see the content captured in OBS. When streaming with OBS, the user doesn't need to enter the ClassIn classroom.

## (1) Downloading OBS

In your browser, go to obsproject.com, then download the installer for your operating system.

## (2) Adding Video in OBS

### 2.1 Creating a Scene

Create a new scene in the Scenes panel in the bottom-left corner.

### 2.2 Adding Video to the Scene

Add a media source under Sources at the bottom.

Set a name for the source, then click OK.

Add a local video.

### 2.3 Resizing the Video

Select the video, then drag its edges to resize it.

## (3) Adding the Stream URL

Open OBS Settings.

Go to the Stream tab and change the service type to Custom.

Add the server address and stream key.

Full stream URL format: rtmp://livepush.eeo.cn/classlive/3786113a1b9e9ed9d1aa_406b449dd48bccac?txSecret=e7dd199f9e005588e3402cd33a97d2c4&txTime=7d8d37cd&record=mp4&record_interval=7200

Tip: in the format above, the first part goes into the "Server" field, and the second part goes into the "Stream Key" field.

## (4) Starting the Stream

Once you click Start Streaming, users can see the feed using the viewing link.

## (5) Playing a Video

Select the video you want to play, then click Play.

## (6) Stopping

When you need to stop the livestream, click Stop Streaming.

<!-- DOC_BOUNDARY -->
```yaml
title: "Virtual Classroom Livestream"
source_title_zh: "教室虚拟直播"
```

## Virtual Classroom Livestream

### 2.2 Adding a Local Video to the Scene

### 2.4 Enabling Local Sound for the Media Source

Switch the media source's monitoring mode to "Monitor and Output."

## (3) Enabling the Virtual Camera Feature

Turn on the virtual camera feature in OBS.

## (4) Installing Virtual Microphone Software

Install the virtual microphone software → click to download and install.

Tip: after installing, you must restart your computer to complete the installation.

## (5) Hiding the Classroom's On-Stage Seats

Go to Classroom Settings, and under the General tab, check "Hide" for the on-stage seats area.

## (6) Setting the Camera and Microphone in the Classroom

In the classroom, turn on your camera and microphone, then set the microphone to the device starting with "VoiceMeeter," and set the camera to the device starting with "OBS." Then double-click the now-open camera to maximize it.

## (7) Playing the Video

Switch back to OBS, select the video, and start playback.

Tip: don't play any other sound on your computer desktop, since the virtual microphone picks up all sound currently playing on the computer desktop.
