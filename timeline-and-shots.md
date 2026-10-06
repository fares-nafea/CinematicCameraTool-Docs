# Timeline and shots

> Build a sequence of shots: reorder, resize, split and save them.

A cinematic is a list of **shots** played one after another. The **TIMELINE** shows one block per shot; a block's width is its duration.

## The timeline

- **Click a block** to select it and move the playhead there.
- **Drag a block** to reorder it.
- **Drag a block's right edge** to change its duration.
- **Click or drag the ruler** to move the playhead.
- A small marker where two blocks meet is a **transition**. Click it to edit the [transition](transitions.md).

## Shot actions

- **Add:** a new shot at the end.
- **Insert:** a new shot right after the selected shot.
- **Duplicate:** a copy of the selected shot.
- **Delete:** remove the selected shot.
- **Split:** cut the selected shot in two at the playhead. The two halves follow the original camera path.
- **< Earlier / Later >:** move the selected shot in the order.

## Settings for each shot

- **Start and End camera** (position, rotation and field of view).
- **Duration:** 0.1 to 600 seconds. The default is 3.
- **Easing:** Linear, SineInOut, QuadInOut, CubicInOut or QuartInOut. The default is SineInOut.

## Scenes

- **New** starts an empty scene.
- **Save** saves your shots and transitions.
- **Load** loads the saved scene.

Scenes are stored in Studio's plugin settings, one saved scene at a time. They are **not stored inside the place file**, so they do not travel with the place.

## Example workflow

1. Set Start and End for shot 1.
2. **Add** shot 2 and set its cameras.
3. Click the marker between them and choose a FADE (see [Transitions](transitions.md)).
4. **Preview**, then drag the block edges to adjust the timing.
5. **Save** the scene.

## Common mistakes

- **Preview says a camera is missing:** every shot needs both a Start and an End camera.
- **Split is refused:** move the playhead inside the shot, at least 0.1 s from each edge, and not inside a transition.
- **Buttons do nothing:** editing is blocked while a Preview or a recording runs.
