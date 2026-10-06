# Camera tools

> Presets and the live tools that move the camera for you.

Besides shots, the plugin has tools that control the camera in other ways.

## Presets

**Presets** save the current viewport camera under a name, so you can return to it later. See [Presets](presets.md).

## Live tools

Live tools take over the camera until you stop them, then give it back.

- [Look At](look-at.md): turn the camera to face a target.
- [Follow](follow.md): follow a target with an offset and a smoothness.
- [Rig](rig.md): track a target in Follow, Orbit or Look At mode.
- [Shake](shake.md) and [Advanced Shake](advanced-shake.md): shake the camera.
- [Path](camera-paths.md): move through points you capture.

## Rules that apply to every live tool

- **One at a time.** Starting one stops the others, and starting a **Preview** stops them all.
- **They give the camera back.** When a tool stops, the camera returns to where it was.
- **They are not part of the timeline.** They are not recorded, not exported as camera data and not in the MP4. They are for working with the camera in Studio.
- **Editing is blocked** while a Preview or a recording runs ("Stop the preview first.").
