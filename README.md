# Clearframe

[Open the player](https://gisbi-kim.github.io/clearframe/)

A dependency-free local video viewer. Controls stay below the video, including in fullscreen.

- Open or drag and drop a local MP4/WebM supported by your browser.
- Seek with the timeline or enter an exact time in seconds.
- Playback speed: 0.25×–4×.
- Left/right arrows pause playback and move by a configurable 0.05–30 seconds.
- Space: play/pause; F: fullscreen; M: mute.
- Volume and loop controls.

Videos are accessed using browser blob URLs; no video uploads, analytics, external libraries, or server processing. Public hosting publishes only the player source.

Time stepping seeks by seconds, not a guaranteed exact frame count. The displayed frame depends on the source frame rate and browser decoder. MP4 codec compatibility depends on your browser; H.264/AAC is recommended.

## Run offline

Download index.html and open it in a modern browser. No installation or build required. GitHub Pages serves the main branch root.
