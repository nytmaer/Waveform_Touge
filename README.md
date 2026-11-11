# Waveform Touge

Audio-driven anime night drive in the browser. A track's loudness and tone become the road a cel-shaded car drifts down, with cinematic cameras and VHS-style effects. Built with Three.js.

**Play it:** https://nytmaer.github.io/Waveform_Touge/

## How the audio becomes the road

- **Hills** follow smoothed loudness, stretched to the song's own range.
- **Curves** follow the balance of bass against treble.
- **Speed** rises with the track's energy.
- **Roadside bars** are the loudness, frame by frame, drawn as a skyline.
- **Neon gates** stand where the track hits hardest.

## What's in it

- A built-in demo loop, synthesised in the browser, so there is a road as soon as the page opens.
- Transport: play, pause, and a seek bar drawn as the road's elevation profile.
- Ten camera angles (Chase, Low side, High, Bumper, Wheel, Front, Low rear, Orbit, Trackside, Heli) plus a Cinematic mode that cuts between them on strong bass hits.
- Drift: Off, On, or Auto. Auto decides corner by corner whether to slide and whether to link into the next one. Drifting counter-steers the front wheels and throws tyre smoke.
- Screen effects: VHS, CRT, Manga and Pixel, plus a glow toggle.

## Controls

| Key | Action |
|---|---|
| Space | Play / pause |
| C | Next camera |
| V | Next effect |
| D (hold) | Drift |
| F | Fullscreen |
| Left / Right (seek bar focused) | Skip 5 seconds |

## Running it

It is a single `index.html` with no build step. Open the GitHub Pages link above, or serve the folder with any static file server. Three.js r128 loads from a CDN, so it needs a network connection.

## Support

If you enjoy this, you can support the work on Ko-fi: https://ko-fi.com/nytmaer
