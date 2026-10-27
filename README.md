# Drum Tutor

A free, browser-based drum practice app for electronic kits. It works with any
MIDI-capable kit or pad through a USB-to-MIDI adapter. I built it as a
replacement for Roland's discontinued DT-1 V-Drums Tutor, and I use it with a
Roland V-Drums Lite HD-3.

**Live app:** https://drum-tutor.netlify.app/
**How to use it:** see the [user guide](USER-GUIDE.md).

## Features

- Falling-note game view with timing scoring (Perfect, Good, OK)
- Notation view
- "Wait for me" mode, where the song pauses until you play the right note
- Loop any bars: click or drag bars in the notation view, and pause to change them
- Import MIDI songs, with an optional backing track
- Step sequencer to build your own practice patterns, with MIDI export
- Record your own playing into the sequencer
- Progress tracker with a chart and CSV export
- Per-drum mixer for volume and cymbal ring length
- Real drum samples, with a velocity-sensitive ride and open hi-hat
- Installable as an app, and works offline

## Use it

Open the app in a browser that supports Web MIDI, such as Chrome or Edge on a
computer or Android. On iPhone and iPad, use a Web MIDI browser such as
MIDIWeb Browser. Plug in your kit, press **Start**, and play. The app is a
static website with no account and no subscription. Your settings and progress
stay in your browser.

## Files

| File | Purpose |
| --- | --- |
| `index.html` | The whole app |
| `sw.js`, `manifest.webmanifest` | Install and offline support |
| `icon-*.png`, `apple-touch-icon.png` | App icons |
| `USER-GUIDE.md` | Documentation |

## Credits and licenses

- Most drum samples come from the GeneralUser GS soundfont by S. Christian
  Collins.
- The ride cymbal samples come from the GMRockKit in the Hydrogen drum machine
  project, which is licensed under the GPL.
- This project is licensed under the GNU General Public License, which also
  matches the GPL-licensed ride samples. See the `LICENSE` file.

This is a personal project and is not affiliated with Roland.
