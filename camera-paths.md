# Camera paths

> Move the camera through points you capture from the viewport.

**PATH** moves the camera through several positions that you capture from the viewport. It is useful for planning a route.

## Steps

1. Move the viewport camera to the first position and press **Add Point**.
2. Move and press **Add Point** again for each position. The field of view is stored with each point.
3. Choose **Linear** (straight segments) or **Smooth**.
4. Set the **duration**. The default is 5 seconds (0.1 to 600).
5. Press **Preview Path**. Press **Stop Path** to end it early.

## Edit the points

The **POINTS** list shows every point.

- **Earlier / Later:** reorder the selected point.
- **Delete Point:** remove the selected point.

Point markers also appear in the viewport.

## What Path is, and is not

Path is a **live tool**, like [Follow](follow.md) and [Shake](shake.md).

- It is a quick way to try a route through several positions.
- It is **not** part of the timeline or the shots.
- Its points are **not saved**: they are lost when the plugin reloads.
- It is **not recorded or exported**: it does not appear in a take or in an MP4.

To put a path in a video, create the same positions as Start and End cameras of shots on the [timeline](timeline-and-shots.md), then Preview, Record or Export MP4.

## Common mistakes

- **Nothing moves:** add at least two points.
- **The path stops by itself:** starting a Preview or another live tool stops it.
