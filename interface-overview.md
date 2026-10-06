# Interface overview

> A tour of the Cinematic Camera Tool panel, from top to bottom.

The panel is one scrolling window. Sections fold away when you click their header (`-` is open, `+` is folded). Studio remembers which ones you opened.

## Top of the panel

- **SCENE** (New, Save, Load): start an empty scene, save your shots and transitions, or load the saved scene.
- **TIMELINE:** one block per shot, a ruler and the playhead.
- **Shot actions:** Add, Insert, Duplicate, Delete, Split, Earlier, Later.

## The selected shot

- **Set Start Camera / Set End Camera:** store the cameras for the shot.
- **Duration:** how long the shot takes (0.1 to 600 seconds).
- **Easing:** Linear, SineInOut, QuadInOut, CubicInOut or QuartInOut.
- **Preview / Stop Preview:** play all shots, then restore the camera.

## TRANSITION

Click the small marker between two shots on the timeline to edit its transition: type (CUT, FADE, CROSSFADE), duration, easing and **Apply**.

## RECORDING, EXPORT and EXPORT VIDEO (MP4)

- **RECORDING:** Record, Stop Recording, Record Again, Clear. FPS 24, 30 or 60.
- **EXPORT:** Export Camera Data (a .rbxm of camera animation data, not a video).
- **EXPORT VIDEO (MP4):** Check Encoder, Port, Token, FPS, Resolution, Export MP4, Cancel Export.

## Live camera tools

These move the camera on their own, one at a time. They are not part of the timeline, the recording or the MP4.

- **LOOK AT, FOLLOW, SHAKE, ADVANCED SHAKE, RIG, PATH**

## PRESETS

Save the current camera under a name, apply it later and delete it.

## Good to know

- While a **Preview** or a **recording** runs, editing and the live tools are blocked.
- Folded sections keep their settings.
