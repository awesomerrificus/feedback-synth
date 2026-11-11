# Electric Mountain Synths

`index.html` lists all three instruments. Each has a desktop and a phone version.

## Feedback Synth (root of the site)

An audio synth and a video synth wired into each other, running entirely in the browser.
The synth plays the picture (a scan line turns brightness, colour, detail and motion into notes, chords and drums),
and the visuals listen to the synth (cuts, effects, feedback and generative art driven by the sound).

- `index.html` opens the right version for your device
- `desktop.html` is the full desktop app (Chrome or Edge recommended; MIDI works there)
- `mobile.html` is the phone and tablet version (touch layout, same features where the browser allows)

Everything runs on your device; files, camera and microphone never leave it.

## Audio Synth (`audio-synth/`)

Pictures, video or the camera turned into music: a scan line reads the picture as a score.
`audio-synth/desktop.html` (MIDI out, WAV + clip recording) and `audio-synth/mobile.html` (touch layout, front/back camera).

## Video Synth (`video-synth/`)

A track turned into visuals that cut and move with the sound, with effect modules and generative sources.
`video-synth/desktop.html` (also offline MP4 render, output window, MIDI learn) and `video-synth/mobile.html` (touch layout, record video).
