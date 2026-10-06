# MP4 export

> Make a real .mp4 video from your shots.

**EXPORT VIDEO (MP4)** turns your shots into a real `.mp4` file, frame by frame at exact times.

## How it works

Roblox plugins cannot encode video, so a small **helper** program on your computer does it. The plugin poses the camera for every frame and takes a screenshot of the viewport. The helper collects the frames and FFmpeg turns them into the video.

## What you need

- **Python 3**
- **FFmpeg**
- **The encoder helper** (a small download)

You set these up once. See [Setup](mp4-setup.md).

## What is exported

- Your **shots** on the timeline, with **FADE and CROSSFADE** transitions.
- The video has the size of the Studio viewport.
- It does **not** include the live tools (Look At, Follow, Rig, Shake, Advanced Shake, Path) or a recording.

## The three pages

1. [Setup](mp4-setup.md): install what you need and start the helper.
2. [Exporting](mp4-exporting.md): settings and the export itself.
3. [Troubleshooting](mp4-troubleshooting.md): common messages and fixes.

## Good to know

MP4 export is tested on macOS (Intel). Apple Silicon, Windows and Linux are not tested yet.
