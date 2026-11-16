# Voice Recording Guide — Episode 1

Goal: a clean, calm, easy-to-understand voice track of about 10 minutes, recorded scene by scene.

## 1. Equipment (use what you have)

| Level | Microphone | Notes |
|-------|-----------|-------|
| Minimum | Phone (voice recorder app) | Hold it 15–20 cm from your mouth, slightly to the side. Turn on airplane mode. |
| Good | Wired lavalier (clip-on) mic for the phone | Clip it 15–20 cm below your chin. Cheap and very effective. |
| Best | USB microphone (e.g. a cardioid condenser or dynamic mic) + laptop | Use a pop filter or a sock over the mic. |

Headphones are useful for checking takes, but you do not need them while you speak.

## 2. Room

- Record in the **smallest, softest room** you have: a bedroom with a bed, carpet and curtains is better than a kitchen.
- A wardrobe full of clothes is a great "vocal booth": stand facing the clothes.
- Turn off fans, air conditioner, fridge (if close) and notifications on all devices.
- Hang a thick blanket behind you if the room sounds echoey (clap once — if you hear a "ring", add soft things).
- Best time: early morning or late evening, when the street is quiet.

## 3. Settings

- Format: **WAV**, 48 kHz, 24-bit (or 16-bit). If your phone app only records M4A/AAC, choose the highest quality.
- Input level: your loudest words should peak around **−12 to −6 dB**. Never in the red (0 dB = clipping = ruined take).
- Record 10 seconds of **silence (room tone)** at the start of each session. Do not move or breathe loudly. It is used for noise reduction later.

## 4. How to record

1. Print or open the clean scene files: `script/scenes/s1.txt` … `s6.txt`, `extra.txt`. Use a tablet or second screen so paper does not rustle.
2. Warm up for 3 minutes: hum, yawn, say "red lorry, yellow lorry", read the vocabulary list from `vocabulary.md` out loud twice.
3. Drink water (room temperature). Avoid milk and sweet drinks before recording.
4. **One file per scene.** Record each scene 2–3 times. Name the files:
   ```
   ep1_s1_take1.wav   ep1_s1_take2.wav
   ep1_s2_take1.wav   ...
   ep1_extra_take1.wav
   ```
5. If you make a mistake, **do not stop**. Pause for 2 seconds, clap once (it makes a visible spike in the waveform), and read the sentence again from the beginning. You will cut it in the edit.
6. After each scene, listen to the best take with headphones. Mark the best one in a note.

## 5. How to speak

- **Pace:** slow and clear, about **115 words per minute**. The audience is learning English. Each scene file shows how long it should take:

  | File | Words | Target time |
  |------|-------|-------------|
  | s1.txt | 124 | ~1:10 |
  | s2.txt | 146 | ~1:25 |
  | s3.txt | 257 | ~2:30 |
  | s4.txt | 215 | ~2:05 |
  | s5.txt | 175 | ~1:40 |
  | s6.txt | 143 | ~1:20 |
  | extra.txt | 102 | ~1:15 (with repeat pauses) |

- **Pauses:** a blank line in the scene file = a 1-second pause. In the review list in scene 6 ("Matter. Atom. Nucleus …"), leave **2 seconds after each word** so viewers can repeat.
- **New words:** the first time you say a vocabulary word (bold in `narration.md`), slow down, say it clearly, and pause for a moment after it.
- **Smile** while you talk — people can hear it. Imagine you are explaining to one friend, not to a crowd.
- **Questions** go up at the end ("Two protons?"). **Answers** go down ("That is helium.").
- Stand up if you can. Your voice has more energy.

## 6. Pronunciation check (before you record)

Practise these words until they feel natural. See `vocabulary.md` for IPA.

| Word | Say it like | Watch out |
|------|-------------|-----------|
| nucleus | NEW-klee-us | not "nuk-le-us" |
| molecule | MOL-uh-kyool | stress on **MOL** |
| electron | ih-LEK-tron | stress on **LEK** |
| neutron | NEW-tron | short ending |
| atomic | uh-TOM-ik | stress on **TOM** (but **AT**-om) |
| element | EL-uh-ment | stress on **EL** |
| charge | CHARJ | "ch" as in *chair* |
| hydrogen | HY-dro-jen | |
| oxygen | OK-si-jen | not "ok-si-GEN" |
| nitrogen | NY-tro-jen | |
| helium | HEE-lee-um | |
| atomos | AT-o-mos | Greek word |

## 7. Clean-up in Audacity (free)

Do this for each chosen take, in this order:

1. **Cut** the mistakes (look for the clap spikes) and long silences. Keep natural pauses.
2. **Noise Reduction:** select the room tone → Effect → Noise Removal and Repair → Noise Reduction → *Get Noise Profile*. Then select all (Ctrl+A) → Noise Reduction again → 6–10 dB → OK. Do not overdo it (the voice becomes "robotic").
3. **High-pass filter:** Effect → EQ and Filters → High-Pass Filter → 80 Hz. Removes rumble.
4. **Compressor:** Effect → Volume and Compression → Compressor → Threshold −18 dB, Ratio 3:1. Makes quiet and loud parts more even.
5. **Loudness Normalization:** Effect → Volume and Compression → Loudness Normalization → **−16 LUFS** (CapCut and YouTube will handle the rest).
6. Export → WAV, 48 kHz. Name: `ep1_s1_final.wav` … `ep1_s6_final.wav`, `ep1_extra_final.wav`.

## 8. Before you finish the session

- [ ] Every scene has at least one take with no clipping.
- [ ] You listened to the best take of each scene with headphones.
- [ ] Files are copied to a second place (cloud drive or USB) before you delete anything on the phone.
