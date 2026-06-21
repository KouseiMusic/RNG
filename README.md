<p align="center"><img width="170" height="66" alt="rsgbannersmall" src="https://github.com/user-attachments/assets/b06d3948-ceb2-4af2-bddb-18bcb4a35fb7" /></p>

**_<p align="center"> Random Sequence Generation / Cellular Automaton Sequencer.</p>_**

---

![Version](https://img.shields.io/badge/Version-1.0.0-brightgreen?style=flat-square)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Intel%20%7C%20Silicon%20%7C%20Universal-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone%20%7C%20AU%20%7C%20VST3-00CED1?style=flat-square&logo=steinberg&logoColor=white)
![DAW](https://img.shields.io/badge/DAW-Ableton%20Live%2012%2B-000000?style=flat-square&logo=bandlab&logoColor=white&labelColor=555555)

---

<p align="center"><img width="1200" height="721" alt="rsgpreview" src="https://github.com/user-attachments/assets/1d69baf4-1c55-44f2-944d-32a76454683b" /></p>

 ---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **Cellular Automaton Engine**: A 16x16 grid based on Conway's Game of Life. With Auto Evolve enabled, the sequence evolves over time, creating evolving generative rhythmic patterns.
- **Customizable Rules**: Independently toggle "Sun" (birth) and "Void" (survival) neighbor counts, from 1 to 8, to alter the genetic behavior of the grid. Edge-wrapping can be toggled on or off for bounded or infinite spatial logic.
- **Analog Samples, Drums directly recorded on hardwares drums machines**:
  - Perkons HD-01 
  - LXR-02
  - TR-808
  - TR-909
- **Advanced Sequencing**: Variable sequence length (1 to 16 steps) and multiple play directions: Forward, Backward, Pendulum and Random. Switching to Forward, Backward or Pendulum while playing waits for the current pattern to finish its cycle before the new direction takes effect; Random applies instantly.
- **Algorithmic Randomizer**: Click the **RSG** button to instantly spawn context-aware patterns across four genre families — Industrial, Hypnotic, Jungle/DnB and IDM — each with multiple structural archetypes and Euclidean-rhythm-based generation for musically coherent results.
- **DSP Engine**: Integrated sample-based drum machine and synth playback. Includes global parameters for Drive, Low-pass Filter Cutoff, Resonance, 3-band EQ (Low/Mid/High), Pitch Modulation, master Delay and Reverb Mix.
- **Preset Library**: Includes a curated set of starting states across Industrial Techno, Hypnotic Techno, Jungle/DnB, IDM and generative Cellular categories.
- **Visual Performance**: Real-time grid rendering of the active pattern, alive cells and playback position, complete with a dark cyan aesthetic and glow animations.
---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia) or 16.0 (Tahoe)
- **Architecture**: Intel (x64), Apple Silicon (Arm64) or Universal (U2B)
- **DAW (Plugin mode)**: Ableton Live 12 or 11, Logic Pro, Reason with the [BlackHole](https://github.com/ExistentialAudio/BlackHole) virtual audio driver for DAW routing in standalone mode.
> Audio Unit (AU) & VST3 plugins formats are currently under development.

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

### 𝐒𝐭𝐚𝐧𝐝𝐚𝐥𝐨𝐧𝐞

1. Download the latest `RSG` release.
2. Extract and drag `RSG` to your Applications folder.
3. If macOS shows a Gatekeeper warning on first launch, right-click the application and choose `Open`, then confirm.

### 𝐀𝐮𝐝𝐢𝐨 𝐔𝐧𝐢𝐭 (𝐀𝐔)

> 𝐔𝐧𝐝𝐞𝐫 𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭

### 𝐕𝐒𝐓𝟑

> 𝐔𝐧𝐝𝐞𝐫 𝐃𝐞𝐯𝐞𝐥𝐨𝐩𝐦𝐞𝐧𝐭

## 𝐃𝐀𝐖 𝐔𝐬𝐚𝐠𝐞

1. Install [`BlackHole`](https://github.com/ExistentialAudio/BlackHole), a free virtual audio driver for macOS.
2. Open `Audio MIDI Setup` (found in `/Applications/Utilities/`).
3. Create a `Multi-Output Device` that includes both your `Audio Interface` and `BlackHole`.
4. Set the `Multi-Output Device` as the system output in `System Settings` > `Sound`.
5. In your `DAW`, create an `Audio Input Track` and set its input source to `BlackHole`.
6. You can now record or monitor `RSG`'s output in real time.

---

## 𝐏𝐫𝐞𝐬𝐞𝐭𝐬

`RSG` includes a variety of presets designed for different aesthetics:

| Preset Group | Character |
| :--- | :--- |
| **Industrial Techno** | *Iron Corridor, Machine Room, Bunker Pulse, Cold Factory*. Driving, syncopated and half-time stompers with heavy drive and saturation. |
| **Hypnotic Techno** | *Trance Loop, Mind Spiral, Void Walker, Locked Groove*. Rolling, loopy and minimal grooves built for long-form repetition. |
| **Jungle / DnB** | *Amen Science, Liquid Steps, Roller, Reese & Roll, Footwork Breaks*. Fast breakbeat patterns and deep sub bass at 150+ BPM. |
| **IDM** | *Acid Dropout, Brain Dance, Math Breaks, Fractal Groove, Neural Pattern*. Uneven syncopations and glitch-leaning triggering. |
| **Cellular** | *Cellular Drift, Phase Garden, Fibonacci Web, Euclidean Cascade, Euclidean Storm, Polymetric, Glider Field*. Generative starting states built from mathematical and Euclidean-rhythm structures. |

---

## 𝐂𝐨𝐧𝐭𝐫𝐨𝐥𝐬

### 𝐒𝐞𝐪𝐮𝐞𝐧𝐜𝐞𝐫 & 𝐀𝐮𝐭𝐨𝐦𝐚𝐭𝐨𝐧
| Parameter | Range | Description |
| :--- | :--- | :--- |
| **Length** | 1 - 16 | The number of steps the sequencer will iterate through before resetting or advancing grid state. |
| **Direction** | Forward, Backward, Pendulum, Random | The order in which the sequencer reads the grid columns. |
| **Sun (Birth)** | 1 - 8 neighbors | The exact number of strict neighbors required to resurrect a dead cell. |
| **Void (Survive)** | 1 - 8 neighbors | The exact number of strict neighbors required for a living cell to stay alive. |
| **Wrap Edges** | On / Off | If enabled, patterns moving off the edge of the grid wrap around to the opposite side. |
| **Auto Evolve** | On / Off | If enabled, the grid advances one generation of the cellular automaton each time the pattern completes a full cycle. |

### 𝐃𝐒𝐏 𝐏𝐚𝐫𝐚𝐦𝐞𝐭𝐞𝐫𝐬

| Parameter | Range | Description |
| :--- | :--- | :--- |
| **Cutoff** | 500 Hz - 10 kHz | Global low-pass filter cutoff frequency. |
| **Resonance** | 0 - 8 | Filter resonance peak at the cutoff point. |
| **Drive** | 0 - 80 | Saturation and overdrive for harsher, more industrial output. |
| **Low / Mid / High EQ** | -12 to +12 dB | 3-band equalizer applied to the master output. |
| **Delay Mix** | 0 - 100% | The amount of the tempo-synced delay signal mixed into the output. |
| **Reverb Mix** | 0 - 100% | The amount of spatial reverberation added to the mix. |
| **Pitch Mod** | -50 to +50 | Global pitch modulation for all triggered samples. |
| **Master Vol** | 0 - 100% (default 80%) | Output amplitude before the final clipping stage. |
| **BPM** | 60 - 240 | Global tempo setting affecting the sequencer speed and delay times. |


---

_This software is free. If you liked the sequencer, don't forget to give it a ⭐️ on GitHub._

---

<p align="center"><code>𝒦𝑜𝓊𝓈𝑒𝒾</code></p>
<p align="center"><code>2026</code></p>
