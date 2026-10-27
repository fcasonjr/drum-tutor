# Drum Tutor user guide

Drum Tutor is a free practice app for electronic drum kits. You play your kit
(or tap the keyboard), and the app shows what to play, scores your timing and
tracks your progress. Everything runs in the browser. There is no account and
no subscription.

## 1. Getting connected

1. Plug your kit into the device with a USB cable, or a USB-to-MIDI adapter.
2. Open the app in a browser that supports Web MIDI:
   - **Windows, Mac, Chromebook, Android:** Chrome or Edge.
   - **iPhone and iPad:** MIDIWeb Browser (Safari does not support MIDI).
3. When the browser asks to use MIDI devices, choose **Allow**. If the red
   "MIDI access denied" message appears, allow it in the site settings and
   reload.
4. Hit a pad. The pad should light up on screen, and the "Last note" label
   shows the note number your kit sent.

No kit handy? The keyboard works too: **A S D F J K L ;** play crash, ride,
hi-hat, tom 1, snare, tom 2, tom 3 and kick, and **G** plays an open hi-hat.

### Pads light up the wrong drum

Press **Learn** on a drum chip under the stage, then hit the pad you want to
assign to it. **Reset mapping** goes back to the default General MIDI layout.

### Sound

- **Pad sounds** plays a drum sample from the device when you hit a pad. Turn
  it off if your kit makes its own sound.
- Browsers keep audio off until you click or tap once, so tap anywhere on the
  page if you hear nothing.

## 2. Practicing

1. Choose a **Pattern** (built-in grooves, imported songs and your own
   sequencer patterns all appear in this list).
2. Set the **Tempo**.
3. Press **Start** (or Space). After a 4-beat count-in, blocks fall toward the
   line in the game view. Hit the matching pad as each block reaches it.

Your hits are graded **Perfect** (within 35 ms), **Good** (70 ms) or **OK**
(120 ms). Accuracy, combo and average timing show beside the stage.

Options in the controls row:

| Option | What it does |
| --- | --- |
| Count-in | Plays four clicks before the song starts. |
| Metronome | Plays a click on every beat while you play. |
| Hear the drums | Plays the pattern's drum part so you can hear what to play. |
| Backing track | Plays the non-drum parts of an imported song. |
| Wait for me | The song stops at each note until you hit it. See below. |
| Loop | Repeats the pattern or chosen bars until you press Stop. |
| Pad sounds | Plays a drum sound when you hit a pad. |
| Latency offset | Shifts timing in milliseconds to match your setup. |

### Game view and notation view

Use **View** to switch between falling blocks and standard drum notation.
Notation shows a percussion staff, with open hi-hats marked by a small circle.
Use ◀ ▶ to change page when the music is longer than the screen.

### Wait for me mode

In this mode, the song freezes at each note until you hit it, so you can learn
a part at your own pace. The backing, metronome and drum playback are turned
off. The score notes how long each note waited.

### Calibrating timing

If your hits always land early or late, press **Calibrate** and tap any pad on
each click once the first four have played. The app sets the latency offset for
you. You can also type a value into **Latency offset**.

## 3. Practicing part of a song (loops)

- Type the first and last bar into **Bars … to …**, or pick them in notation
  view (below). **Loop** repeats the section.
- Leave both boxes blank, or press **All**, to use the whole song.

### Picking bars in notation view

When the song is stopped or paused, the notation view shows the whole song:

- Click a first bar, then click the last bar. Click the same bar twice for one
  bar.
- Or drag across several bars with the mouse.
- Chosen bars are highlighted gold and the others are dimmed.

### Pause

While playing, press **Pause** (or **P**) to freeze the song. The app switches
to notation view and outlines the bar you were in.

- **Resume** with the bars unchanged carries on where you left off.
- **Resume** after choosing different bars starts the new section from its first
  bar. The run you were on is saved first.
- **Stop** ends the run, and the next Start begins at the beginning.

Pad hits do not count while paused.

## 4. Importing songs

Press **Import MIDI…**, or drag a `.mid` file onto the page. The app finds the
drum part (General MIDI channel 10) and shows it as a pattern. Other
instruments become the backing track. Imported songs are remembered on this
device, and **Remove song** deletes the one selected.

Notes:
- Tempo changes inside a file are not followed. The song plays at one steady
  tempo.
- Drum notes that do not match one of the pads are skipped, and the app tells
  you how many.
- Open hi-hat is read from General MIDI note 46.

## 5. Sequencer

Press **Sequencer** to build your own practice patterns.

- Choose the number of bars (1, 2 or 4) and the grid (16th notes or triplets),
  or start from a template.
- Click or tap squares to place hits. Drag across a row with the mouse to paint
  several. An open hi-hat replaces the closed one on the same step.
- **Preview** plays the pattern. Tempo follows the main Tempo slider.
- **Record my playing:** wait out the 4-beat count-in, then play your kit. The
  pattern loops and each pass adds to the last, so you can build a groove in
  layers. Press Stop (or Space) when done. Hits snap to the nearest step.
  **Undo recording** removes what the last recording added.
- **Save** keeps the pattern in your pattern list. **Save & practice** saves it
  and takes you straight to practicing it.
- **Export MIDI** downloads the pattern as a `.mid` file.

## 6. Mixer

Press **Mixer** to set each drum's volume and, for cymbals, how long they ring.
Volume 0% mutes a drum. **Test** plays a drum with its current settings.

**Ride sound** switches between the new Rock kit (velocity-sensitive, brighter)
and the Classic ride. **Reset to defaults** restores everything.

The mixer affects the sounds this app makes, not your kit's own sounds.

## 7. Progress

Press **Progress** to see your history. A run is saved when it finishes, or when
you stop it after at least 8 scored notes.

- Each song and bar range has its own best score, last score and fastest tempo
  at 90% accuracy or better ("Best" and "Fastest at 90%+" count normal play-along
  runs only, not Wait for me).
- The chart shows how your accuracy changes over time.
- **Export CSV** downloads your history, and **Clear history** removes it.

## 8. Installing and offline use

On a computer or Android, use the browser's **Install app** or **Add to Home
screen** option (on desktop, the install icon in the address bar). After the
first visit the app opens without a connection. When you are online, it checks
for a newer version each time it loads.

## 9. Where your data lives

Settings, mixer choices, imported songs, your own patterns and your progress
history are stored in the browser on each device. They do not sync between
devices and are not sent anywhere. Clearing the browser's site data erases them,
so use **Export CSV** and **Export MIDI** for anything you want to keep.

## 10. Troubleshooting

| Problem | What to try |
| --- | --- |
| No pads detected | Check the cable, allow MIDI in the browser, and reload. Use Chrome or Edge, or MIDIWeb Browser on iPhone and iPad. |
| No sound | Click or tap the page once. Check that **Pad sounds** is on, and the device volume. |
| A pad lights the wrong drum | Use **Learn** on that drum, then hit the pad. |
| Hits always look early or late | Run **Calibrate**, or change **Latency offset**. |
| Crackling with many cymbals | Close other tabs and apps. Wireless audio can add delay and glitches too. |
| Nothing happens when I press P | P only works while a song is playing. |

## Credits

Most drum samples come from the GeneralUser GS soundfont by S. Christian
Collins. The ride cymbal samples come from the GMRockKit in the Hydrogen drum
machine project (GPL). This project is not affiliated with Roland.
