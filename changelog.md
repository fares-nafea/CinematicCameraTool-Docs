# Changelog

## Version 1.0.0 · 2026-10-06

First public version.

**Added**

- Shots with Start/End cameras, duration and easing; Preview that restores the camera exactly
- Timeline: reorder, resize, Split, Insert, Duplicate
- Transitions: CUT, FADE, CROSSFADE
- Scenes and camera presets
- Live camera tools: Look At, Follow, Shake, Advanced Shake, Rig, Path
- Recording and Export Camera Data (.rbxm)
- Export MP4 through a local helper (FADE and CROSSFADE included)
- Panel sections that fold away and remember their state

**Known issues**

- MP4 export is tested on macOS (Intel) only
- MP4 export needs Python 3, FFmpeg and the helper
- An older helper cannot render cinematics that have transitions
