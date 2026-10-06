# Export camera data

> Save a take as camera animation data (.rbxm). This is data, not a video.

**EXPORT** saves your take as **camera animation data**. It is **not a video**. For a video file, use **EXPORT VIDEO (MP4)** (see [MP4 export](mp4-export.md)).

## Steps

1. Record a take (see [Recording](recording.md)).
2. Press **Export Camera Data**.
3. Studio opens its save dialog. Choose where to save the `.rbxm` file.
4. Studio does not tell plugins whether you saved, so check the folder you chose.

## What is in the file

A folder called **CinematicCameraTake** with a header and the camera samples: position, rotation and field of view over time.

## Using the file

Insert the `.rbxm` into a place and read the samples from your own script. **No ready-made player is included** with the plugin.

## Common mistakes

- **The button is disabled:** there is no take. Record first.
- **Expecting a video:** use EXPORT VIDEO (MP4).
