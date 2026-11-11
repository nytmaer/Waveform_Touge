<div align="center">

<img src="media/hero.jpg" alt="A white cel-shaded car drifting down a neon road at dusk, trailing tyre smoke" width="100%">

# Waveform Touge

**Your track is the road.**<br>
An audio-driven anime night drive that runs in the browser.

[![Play it](https://img.shields.io/badge/PLAY_IT-ff7a59?style=for-the-badge)](https://nytmaer.github.io/Waveform_Touge/)
[![Support on Ko-fi](https://img.shields.io/badge/Ko--fi-Support-ff4fd8?style=for-the-badge&logo=kofi&logoColor=white)](https://ko-fi.com/nytmaer)

![three.js r128](https://img.shields.io/badge/three.js-r128-3df2ff?style=flat-square)
![No build step](https://img.shields.io/badge/build-none-3a2b80?style=flat-square)
[![MIT license](https://img.shields.io/badge/license-MIT-f4f1ff?style=flat-square)](LICENSE)

</div>

---

A track's loudness and tone become the road a cel-shaded car drifts down, with cinematic cameras and VHS-style effects. It opens on a demo loop synthesised in the browser, so there is a road the moment the page loads.

## The player

<img src="media/player.jpg" alt="The full player: song title and speed at the top, the 3D road in the middle, and the transport, seek bar and mode buttons along the bottom" width="100%">

Song title and live speed up top; play, seek and the camera, drift and effect buttons along the bottom. The controls fade away after a few seconds of playback so the drive fills the screen.

## How the audio becomes the road

| In the music | On the road |
|---|---|
| Loudness, smoothed | **Hills.** Quiet passages are valleys, loud ones are peaks. |
| Bass against treble | **Curves.** The balance steers the road left and right. |
| Energy | **Speed.** The car covers more road in the big sections. |
| Loudness, frame by frame | **Skyline.** The bars lining both sides of the road. |
| The hardest hits | **Neon gates** to drive through. |

## Effects

<table>
  <tr>
    <td width="50%"><img src="media/fx-vhs.jpg" alt="VHS effect"><br><div align="center"><b>VHS</b></div></td>
    <td width="50%"><img src="media/fx-crt.jpg" alt="CRT effect"><br><div align="center"><b>CRT</b></div></td>
  </tr>
  <tr>
    <td><img src="media/fx-manga.jpg" alt="Manga halftone effect"><br><div align="center"><b>Manga</b></div></td>
    <td><img src="media/fx-pixel.jpg" alt="Pixel effect"><br><div align="center"><b>Pixel</b></div></td>
  </tr>
</table>

## Cameras

Ten angles, plus a **Cinematic** mode that cuts between them on strong bass hits.

<table>
  <tr>
    <td width="50%"><img src="media/cam-chase.jpg" alt="Chase camera"><br><div align="center"><b>Chase</b></div></td>
    <td width="50%"><img src="media/cam-low-rear.jpg" alt="Low rear camera"><br><div align="center"><b>Low rear</b></div></td>
  </tr>
  <tr>
    <td><img src="media/cam-trackside.jpg" alt="Trackside camera"><br><div align="center"><b>Trackside</b></div></td>
    <td><img src="media/cam-heli.jpg" alt="Heli camera"><br><div align="center"><b>Heli</b></div></td>
  </tr>
</table>

Also: Low side, High, Bumper, Wheel, Front and Orbit.

## Drift

Three modes: **Off**, **On**, and **Auto**. Auto decides corner by corner whether to slide, and whether to link into the next corner or straighten up. Drifting counter-steers the front wheels and throws cel-shaded tyre smoke.

## Controls

| Key | Action |
|---|---|
| `Space` | Play / pause |
| `C` | Next camera |
| `V` | Next effect |
| `D` (hold) | Drift |
| `F` | Fullscreen |
| `←` `→` on the seek bar | Skip 5 seconds |

The seek bar is the road's elevation profile, so you can see the drops coming.

## Running it

It is a single `index.html` with no build step. Use the link above, or serve the folder with any static file server. Three.js r128 loads from a CDN, so it needs a network connection.

## Support

If you enjoy this, you can support the work on Ko-fi: **https://ko-fi.com/nytmaer**

## License

[MIT](LICENSE)
