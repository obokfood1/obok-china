OBOK video sound fix

Upload and overwrite:
- en/index.html
- cn/index.html
- ru/index.html
- es/index.html
- assets/fermentation-philosophy.mp4
- assets/philosophy-poster.jpg

Why the video was silent:
1. The previous optimized MP4 was exported without an audio track.
2. Browsers block autoplay with sound, especially Safari and mobile browsers.

This version:
- Preserves the original AAC audio.
- Starts muted so autoplay still works.
- Adds a visible sound button and native video controls.
- Sound begins after the visitor taps/clicks the button, which complies with browser autoplay rules.
