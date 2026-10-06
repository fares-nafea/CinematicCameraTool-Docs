# Exporting an MP4

> Choose FPS and resolution, export, and find your video.

## Settings

- **FPS:** 24, 30 or 60. The default is 30.
- **Resolution:** **Source** (the default) is the size of the Studio viewport. You can also see 720p, 1080p and 2160p. A larger size is only possible when the viewport is at least that big and has the same shape, and on some Studio versions only **Source** works. Nothing is stretched. If you are unsure, use **Source**.

## Export

1. Make sure every shot has a Start and an End camera.
2. Start the helper and press **Check Encoder** (see [Setup](mp4-setup.md)).
3. Press **Export MP4**.
4. Keep **Studio in front** and **do not resize it** while it exports. Do not take other screenshots during the export.

## Progress

- **EXPORTING MP4**, with **Frame x / N**, **Progress** and **Elapsed**.
- **ENCODING MP4** at the end.
- **MP4 EXPORT COMPLETE** with the path of the file.

## Cancel

Press **Cancel Export**. The export stops safely, the camera goes back exactly where it was, and the helper deletes its temporary frames. If it was already encoding, delete any unfinished `.mp4` in the output folder.

## Where is the video?

In the helper's output folder:

- **macOS:** `~/Movies/CinematicCameraTool`
- **Other systems:** `~/Videos/CinematicCameraTool`

The file is named like `cinematic-20261006-143000.mp4`. Existing files are never overwritten. The plugin shows the path when the export finishes.

## Good to know

- About 0.7 seconds per frame was seen on one Mac. A 10-second clip at 30 FPS takes about 3.5 minutes. A crossfade frame takes two screenshots, so it is slower.
- The longest export is 600 seconds at 60 FPS.
- Studio keeps its temporary screenshots until you close it. A long export can use a few gigabytes (about 0.6 MB per frame was seen). They were cleaned up after Studio was restarted.
