# Editing in CapCut — Episode 1

Result: a 16:9, 1080p video of about 10–11 minutes. The visuals come from Atom Studio (`atom-studio/index.html`), the voice comes from your cleaned WAV files (see `recording-guide.md`).

These steps are written for **CapCut Desktop** (Windows/Mac). The mobile app has the same tools with slightly different menus.

---

## Step 1 — Capture the Atom Studio visuals

The easiest way to get perfect sync is the **play-along method**: you play your finished voice track in your headphones and press the keys at each cue, while a screen recorder captures the browser.

### Prepare
1. Install **OBS Studio** (free). Settings → Video: Base and Output resolution **1920×1080**, **30 FPS** (or 60). Settings → Output: Recording format **MP4** (or MKV, then *File → Remux* to MP4), quality "High".
2. Add a source: **Window Capture** (or Display Capture) of your browser.
3. Open `atom-studio/index.html` in Chrome or Edge.
4. Press **F** (fullscreen), then **H** (hide the panel; the mouse cursor is also hidden). Press **U** if you want to hide the Uzbek lines.

### Record, one scene at a time
1. Open `script/narration.md` next to you (on a phone or printed). The cues look like `[3.2]` = scene 3, step 2.
2. In Atom Studio press the scene number (`1` … `6`). You are now at step 0.
3. Start OBS recording. Start playing `ep1_s1_final.wav` in your headphones.
4. Every time the voice reaches a new cue in `narration.md`, press **→** (or Space, or click).
5. When the scene's audio ends, wait 3 seconds, stop OBS. Name the file `ep1_vis_s1.mp4`.
6. Repeat for scenes 2–6.

Tips:
- Made a mistake? Press **←** to go back, or **R** to replay the current step. It is easier to just record the scene again.
- You can open a step directly with the URL: `index.html#4.6clean` opens scene 4 step 6 with the panel hidden (good for re-takes of one moment).
- **Scene 6, step [6.2]** (the 12-word review) needs about 14 seconds to show all words. Press → for [6.3] only when the voice says "Great job!".
- For the **extra / pronunciation corner**, use scene 6 step [6.2] (review grid) or free mode (`0`, then ↑/↓ to change the element).

Alternative without OBS: Windows **Win+Alt+R** (Xbox Game Bar) or Mac **Cmd+Shift+5** also record the screen.

---

## Step 2 — New project

1. CapCut → **Create project**.
2. Project settings (gear icon at the right of the timeline): Ratio **16:9**, Resolution **1080p**, Frame rate **30 fps**.
3. **Import** all files: `ep1_s1_final.wav` … `ep1_s6_final.wav`, `ep1_vis_s1.mp4` … `ep1_vis_s6.mp4`, music, and a logo if you have one.

## Step 3 — Build the timeline

Put the scenes in order: s1, s2, s3, s4, s5, s6.

For each scene:
1. Drag the video `ep1_vis_sN.mp4` to the main track.
2. Drag the voice `ep1_sN_final.wav` to an audio track below it.
3. If you used the play-along method and OBS captured no audio, line up the start of the voice with the moment you started the audio (it is usually within 0.5 s). Check one cue in the middle (for example, the word "nucleus" with the nucleus card) and nudge until it matches.
4. If you recorded video without the play-along: **Split** (Ctrl+B) the video at each step change and stretch or trim pieces to match the voice. Use **Freeze frame** (right-click → Freeze) to hold a step longer.
5. Mute the video track's own sound (speaker icon) if it recorded system noise.

Between scenes, add a short **Cross dissolve** transition (0.3–0.5 s) — only between scenes, not between steps.

## Step 4 — Quiz cards (after cue [6.3])

After "You can check your answers in the description.", insert **5 quiz cards** (questions 1–5 from `quiz.md`):

1. Text → Default text. Background: dark navy `#0B1020` (add a solid color layer or a screenshot of Atom Studio [6.3] blurred).
2. Question in white, 64 px, bold. Answer options a/b/c below in 48 px.
3. Each card stays **6 seconds**. Add a simple countdown: Text "5 … 4 … 3 …" or a progress bar from the Elements → Stickers library.
4. Do **not** show the answers in the video (they are in the description). Optional: show them as a quick 2-second flash after each card instead — choose one style and keep it for all episodes.

## Step 5 — Captions

1. Select all voice clips → **Text → Auto captions** → Language: **English** → Generate.
2. Read through every caption and fix mistakes. Auto captions often get these wrong: *nucleus, neutron, atomos, H two O, neon*. Use the scene text files to check.
3. Style: white text, black outline or semi-transparent black box, size large enough to read on a phone, position **top center** — the bottom-left is where Atom Studio shows the vocabulary cards.
4. Make the vocabulary words stand out: select a caption → highlight the word → color **#FFCF5A** (the Atom Studio yellow).
5. Optional: second caption track in Uzbek for the vocabulary moments only (the Atom Studio cards already show Uzbek, so this is not required).

## Step 6 — Music and sound effects

- Music: a calm lo-fi / ambient track from CapCut **Audio → Music** (check it is allowed for YouTube) or from the YouTube Audio Library.
- Volume: **−25 to −30 dB** under the voice. It should be barely noticeable. Right-click music → **Audio ducking**, or lower it by hand.
- Fade the music in over 2 s at the start and out over 3 s at the end.
- Sound effects (Audio → Sound effects), very quiet (−20 dB):
  - soft "pop" when a vocabulary card appears,
  - "whoosh" at the zoom tunnel [1.3] and the hair zoom [2.1],
  - small "ding" when carbon becomes nitrogen [4.6] and when the shells are full [5.2], [5.5].
- No music during the pronunciation corner — viewers need to hear clearly.

## Step 7 — Intro, outro, extras

- **Intro:** scene 1 step [1.0] already works as a title card. Keep the first 5 seconds strong: you can move the line "Today we will answer this question…" to start over the title.
- **End screen:** leave the last **20 seconds** on [6.4] ("Next episode…"). YouTube's end-screen elements go on top of this.
- **Pronunciation corner:** add after the end screen as a bonus, or export it separately as a **YouTube Short** (9:16): duplicate the project, change ratio to 9:16, scale the Atom Studio video to fit, put big captions in the middle. Keep it under 60 seconds.

## Step 8 — Export

- Export → Resolution **1080p**, Frame rate **30 fps**, Codec **H.264**, Bitrate **Recommended** or **Higher**, Format **MP4**.
- Audio: AAC, 48 kHz.
- File name: `chemistry-in-english-ep1.mp4`.
- Watch the exported file once **on a phone**: can you read every caption and card? Is the voice clearly louder than the music?

## Timeline overview

```
| s1 Hook | s2 How small | s3 Inside the atom | s4 Elements | s5 Shells | s6 Molecules + review | quiz cards | end screen | (bonus) |
  ~1:10     ~1:25          ~2:30                ~2:05         ~1:40       ~1:20                   ~0:30        ~0:20
```
