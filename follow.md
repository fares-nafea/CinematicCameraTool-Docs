# Follow

> Keep the camera following a target with an offset and a smoothness.

**FOLLOW** keeps the camera following a target while it runs.

## Steps

1. Select a **part, model or attachment** in Studio and press **Pick Target**.
2. Set the **Offset** (X, Y, Z): where the camera sits relative to the target. The default is 0, 5, 12.
3. Set the **Smoothness**: how much of the gap closes each frame. The default is 0.15.
4. Press **Start Follow**. Press it again (it becomes stop) to end it.

## Settings

- **Offset:** up to 1000 studs on each axis.
- **Smoothness:** a lower number is smoother and slower to catch up. A higher number follows tightly.

You can change the offset and smoothness while Follow is running.

## Good to know

- Follow is a **live tool**. Only one live tool runs at a time, and starting a Preview stops it.
- When Follow stops, the camera returns to where it was.
- It is not part of the timeline, a recording or the MP4.
- If the target is deleted, Follow stops by itself.

## Common mistakes

- **Nothing happens:** pick a target first.
- **"Offset too small":** the offset needs some distance from the target.
- **Camera jumps back:** it is the normal restore when Follow stops.
