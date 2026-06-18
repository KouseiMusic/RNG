<p align="center"><img width="170" height="66" alt="rsgbannersmall" src="https://github.com/user-attachments/assets/b06d3948-ceb2-4af2-bddb-18bcb4a35fb7" /></p>

**_<p align="center">Cellular Automaton Sequencer / Random Sequence Generation.</p>_**

---

![Status](https://img.shields.io/badge/Status-Under%20Development-orange?style=flat-square&logo=githubactions&logoColor=white&labelColor=grey)
![macOS Support](https://img.shields.io/badge/macOS-Sonoma%20%7C%20Sequoia%20%7C%20Tahoe-000000?style=flat-square&logo=apple&logoColor=white)
![Architecture](https://img.shields.io/badge/Architecture-Intel%20%7C%20Silicon%20%7C%20Universal-black?labelColor=606060&style=flat-square&logo=apple&logoColor=white)
![Format](https://img.shields.io/badge/Format-Standalone%20%7C%20AU%20%7C%20VST3-00CED1?style=flat-square&logo=steinberg&logoColor=white)
![DAW](https://img.shields.io/badge/DAW-Ableton%20Live%2012%2B-000000?style=flat-square&logo=bandlab&logoColor=white&labelColor=555555)

---

<p align="center"><img width="1201" height="724" alt="rsgpreview" src="https://github.com/user-attachments/assets/55005a75-532b-449e-a1da-725be620ca08" /></p>

---

## 𝐅𝐞𝐚𝐭𝐮𝐫𝐞𝐬

- **Cellular Automaton Engine**: A 16x16 grid based on Conway's Game of Life. The sequence evolves over time, creating evolving generative rhythmic patterns.
- **Customizable Rules**: Independently toggle "Sun" and "Void" conditions to alter the genetic behavior of the grid. Edge-wrapping can be toggled on or off for bounded or infinite spatial logic.
- **Analog Samples, Drums directly recorded on hardwares drums machines**:
  - Perkons HD-01 
  - LXR-02
  - TR-808
  - TR-909
- **Advanced Sequencing**: Variable sequence length (up to 16 steps) and multiple play directions: Forward, Backward, Pendulum and Random.
- **Algorithmic Randomizer**: Click 'Random' to instantly spawn context-aware patterns from algorithmic archetypes such as Industrial Techno, Hypnotic Techno, Minimal Techno and Jungle DNB.
- **DSP Engine**: Integrated sample-based drum machine and synth playback. Includes global parameters for Drive, Low-pass Filter Cutoff, Resonance, Pitch Modulation, master Delay and Reverb Mix.
- **Vast Preset Library**: Includes meticulously crafted starting states such as *Techno Seed*, *Polyrhythm*, *Binary Rain*, *Cybernetic*, *Quantum State*, *IDM Glitch*.
- **Visual Performance**: Real-time canvas rendering of the active grid, alive cells and playback position, complete with a dark teal aesthetic and dynamic pulse animations.

---

## 𝐒𝐲𝐬𝐭𝐞𝐦 𝐑𝐞𝐪𝐮𝐢𝐫𝐞𝐦𝐞𝐧𝐭𝐬

- **macOS**: 14.0 (Sonoma), 15.0 (Sequoia) or 16.0 (Tahoe)
- **Architecture**: Intel (x64), Apple Silicon (Arm64) or Universal (U2B)
- **DAW (Plugin mode)**: Ableton Live 12 or 11, Logic Pro, Reason with the [BlackHole](https://github.com/ExistentialAudio/BlackHole) virtual audio driver for DAW routing in standalone mode.
> Audio Unit (AU) & VST3 plugins formats are currently under development.

---

## 𝐈𝐧𝐬𝐭𝐚𝐥𝐥𝐚𝐭𝐢𝐨𝐧

1. Download the latest `RSG` release.
2. Extract and drag `RSG` to your Applications folder.
3. If macOS shows a Gatekeeper warning on first launch, right-click the application and choose `Open`, then confirm.

---

## 𝐏𝐫𝐞𝐬𝐞𝐭𝐬

`RSG` includes a variety of presets designed for different aesthetics:

| Preset Group | Character |
| :--- | :--- |
| **Techno & House** | *Techno Seed, Dense Groove, Minimalist, Deep House*. Sturdy four-on-the-floor foundations. |
| **Generative Math** | *Symmetric, Orbital, Matrix Pattern, Sine Wave, Fractal*. Highly structured, geometric starting conditions. |
| **IDM & Glitch** | *IDM Glitch, IDM Complex, IDM Micro, IDM Ambient*. Uneven syncopations, complex time signatures and sparse triggering. |
| **Jungle & Breaks** | *Breakbeat, Jungle Drill, Jungle Roller, Jungle Amen*. Dense 160+ BPM amen break slices and deep sub basses. |
| **Abstract Contexts** | *Data Stream, Ghost Grid, Neutrino, Quantum State, Reactor Core, Chaos, Cellular*. Experimental soundscapes. |

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

### 𝐃𝐒𝐏 𝐏𝐚𝐫𝐚𝐦𝐞𝐭𝐞𝐫𝐬

| Parameter | Range | Description |
| :--- | :--- | :--- |
| **Cutoff** | 500 Hz - 10 kHz | Global low-pass filter cutoff frequency. |
| **Resonance** | 0 - 10 | Filter resonance peak at the cutoff point. |
| **Drive** | 0 - 100 | Saturation and overdrive for harsher, more industrial output. |
| **Delay Mix** | 0 - 100% | The amount of the tempo-synced delay signal mixed into the output. |
| **Reverb Mix** | 0 - 100% | The amount of spatial reverberation added to the mix. |
| **Pitch Mod** | -50 to +50 | Global pitch modulation for all triggered samples. |
| **Master Vol** | 0 - 100% | Output amplitude before the final clipping stage. |
| **BPM** | 60 - 240 | Global tempo setting affecting the sequencer speed and delay times. |

---

_This software is free. If you liked the sequencer, don't forget to give it a ⭐️ on GitHub._

---

<p align="center"><code>𝒦𝑜𝓊𝓈𝑒𝒾</code></p>
<p align="center"><code>2026</code></p>
