# Transitions

> Cut, fade or crossfade between two shots.

A transition controls how one shot changes into the next. It is set on the **marker between two shots** on the timeline.

## Edit a transition

1. Click the small marker where two shots meet on the timeline.
2. Choose the **type**: CUT, FADE or CROSSFADE.
3. Set the **duration** and the **easing**.
4. Press **Apply**. The change is not kept until you press Apply.

## Types

- **CUT:** an instant change (the default).
- **FADE:** the picture goes to black and comes back with the next shot.
- **CROSSFADE:** one view dissolves into the next.

## Settings

- **Duration:** 0.05 to 10 seconds. The default is 1.
- **Easing:** the same list as shots. The default is SineInOut.

## How it works

A transition is **centered on the cut**: half of it happens in each shot, and it does not add extra time to the cinematic. Because of this, each shot must be long enough for the halves of every transition that touches it. If a shot is too short, the plugin tells you to shorten a transition or lengthen the shot.

## In the Preview and in the MP4

- The **Preview** draws FADE and CROSSFADE on screen.
- **Export MP4** includes FADE and CROSSFADE too. The helper mixes them into the video, so you need an up-to-date helper. A crossfade frame takes two screenshots, so exports with long crossfades take longer.

## Common mistakes

- **The transition is too long for a short shot:** shorten it or lengthen the shot.
- **Forgetting Apply:** the changes are lost if you do not press it.
- **An old helper:** it refuses cinematics that have transitions. Download the newest helper.
