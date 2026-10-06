# FAQ

> Quick answers to the most common questions.

## Installation

**How do I install the plugin?**
Install it from the Roblox Creator Store, then restart Roblox Studio. See [Installation](installation.md).

**Why isn't the plugin appearing?**
Restart Studio after installing. Open the **Plugins** tab and click **Camera Tool**. Make sure the plugin is not turned off in the plugin manager.

## Getting started

**How do I create my first shot?**
Move the viewport camera and press **Set Start Camera**, move it again and press **Set End Camera**. See [Your first shot](your-first-shot.md).

**How do I preview?**
Press **Preview**. **Stop Preview** ends it. The camera is restored exactly afterwards.

**Why can't I edit during a Preview?**
Editing and the live tools are blocked while a Preview or a recording runs ("Stop the preview first." / "Stop recording first.").

**Where are my scenes stored?**
In Studio's plugin settings, one saved scene at a time. They are not stored in the place file.

**Are Shake, Follow, Rig and Path recorded or exported?**
No. They are live tools, not part of the timeline, the recording or the MP4.

## Recording and export

**How do I record?**
Press **Record** in RECORDING. It plays the Preview and records the camera at 24, 30 or 60 FPS.

**How do I export?**
**Export Camera Data** saves the take as an `.rbxm` of camera data. It is not a video.

**How do I export an MP4?**
Use EXPORT VIDEO (MP4): start the helper, type its Port and Token, press **Check Encoder**, choose **Source**, and press **Export MP4**. See [MP4 export](mp4-export.md).

**Why does MP4 export need a helper?**
Roblox Studio plugins cannot encode video. The helper runs FFmpeg on your computer.

**What do I need for the helper?**
Python 3, FFmpeg and the helper file.

**What are the supported FPS and resolutions?**
FPS: 24, 30 and 60. Resolution: Source, 720p, 1080p and 2160p. Larger sizes only work if your viewport is at least that big and has the same shape. If unsure, use Source.

**Where is my exported video?**
In the helper's output folder: `~/Movies/CinematicCameraTool` on macOS, `~/Videos/CinematicCameraTool` on other systems. The plugin shows the path when it finishes.

**Does the export include transitions?**
Yes, FADE and CROSSFADE, with an up-to-date helper.

**Can I export a path or a shake to MP4?**
No. Only the shots on the timeline are exported.

## Problems

**The encoder is not detected. What do I do?**
Check that the helper is running, that you typed the **current** Port and Token, and press **Check Encoder** again. Allow `localhost` if Studio asks.

**What happens if I cancel an export?**
The camera goes back exactly, the helper stops and deletes its temporary frames. If it was already encoding, delete any unfinished `.mp4` in the output folder.

**Does MP4 export work on Windows or Linux?**
It is not tested. It is tested on macOS (Intel).

**Something is broken.**
See [MP4 troubleshooting](mp4-troubleshooting.md), then ask in the Help forum on Discord.
