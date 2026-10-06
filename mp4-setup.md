# MP4 setup

> Install Python, FFmpeg and the helper, then connect the plugin.

## Install once

1. **Python 3:** download it from [python.org/downloads](https://www.python.org/downloads/).
2. **FFmpeg:** download it from [ffmpeg.org/download.html](https://ffmpeg.org/download.html). On macOS with Homebrew: `brew install ffmpeg`.
3. **The encoder helper:** download it from [GitHub](https://github.com/fares-nafea/CinematicCameraTool-Helper/releases/latest) and unzip it anywhere.

## Start the helper (every time you export)

1. Open a terminal in the helper's folder.
2. Run:

```
python3 encoder_helper.py
```

3. The helper prints a **Port** and a **Token**. They change every time you start it. **Leave the window open** while you export.

The helper prints a line like `Shots :` with a folder. That is the folder where Studio stores its temporary screenshots, which the helper uses.

## Connect the plugin

1. In Studio, open **EXPORT VIDEO (MP4)**.
2. Type the **Port** and the **Token** from the terminal.
3. Press **Check Encoder**. It should say **✓ Connected (FFmpeg found)**.

Studio may ask you to allow `localhost`. Allow it.

## Other systems

MP4 export is tested on macOS (Intel). On Windows and Linux the helper may need the option `--captures-dir` pointing at the folder where Studio writes its temporary screenshots. This is not tested.
