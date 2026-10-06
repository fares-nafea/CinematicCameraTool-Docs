# MP4 troubleshooting

> The messages you may see and what to do.

## The encoder is not found

**"The MP4 encoder helper is not running (or the Port is wrong). Start it, then check the Port."**

- Is the helper running and its window still open?
- Did you type the **current** Port and Token? They change every time the helper starts.
- Press **Check Encoder** again.

## FFmpeg

**"FFmpeg is not available to the MP4 encoder helper."**

Install FFmpeg and restart the helper. Or start the helper with `--ffmpeg /path/to/ffmpeg`.

## Old helper

**"This encoder helper is too old to render transitions."**

Download the newest helper and restart it.

## Resolution and size

**"Screenshot pickup can only export the viewport's own size."**

Set Resolution to **Source**.

**"More than one new screenshot appeared"**, or a message about a frame of another size:

A screenshot was taken or Studio was resized during the export. Export again and leave Studio alone.

## Studio

**"This version of Studio does not support viewport capture for plugins yet."**

Neither screenshot route is available in your Studio version. Use [Export camera data](export-camera-data.md) instead.

**"MP4 export requires viewport capture permission."**

Studio refused the permission. Allow it when Studio asks.

## Others

- **"Stop recording before exporting."** Press **Stop Recording** first.
- **"MP4 export is running. Use Cancel Export to stop it."** Other actions are blocked during an export.

## Still stuck?

Post in the Help forum of the Discord server with the **message shown in the plugin** and the **helper's terminal text**.
