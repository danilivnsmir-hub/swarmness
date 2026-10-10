# Third-party notices

Swarmness includes or links the following third-party components.

| Component | Use | License |
|---|---|---|
| [JUCE](https://juce.com) 8 | Plug-in framework (VST3 / AU / Standalone, GUI, DSP) | JUCE licence — a commercial / Starter licence is required for closed-source distribution |
| [VST3 SDK](https://github.com/steinbergmedia/vst3sdk) (via JUCE) | VST3 wrapper | MIT |
| Barlow Condensed font (The Barlow Project Authors) | GUI labels and values | SIL Open Font License 1.1 — `Source/Assets/Fonts/OFL-Barlow.txt` |
| [NeuralAmpModelerCore](https://github.com/sdatkinson/NeuralAmpModelerCore) (fetched at build time, unmodified) | AMP and WASP blocks: playing `.nam` captures | MIT — Copyright (c) 2023 Steven Atkinson |
| [nlohmann/json](https://github.com/nlohmann/json) (bundled with NeuralAmpModelerCore) | reading `.nam` files | MIT — Copyright (c) 2013-2022 Niels Lohmann |
| [Eigen](https://eigen.tuxfamily.org) (fetched at build time, unmodified, built with `EIGEN_MPL2_ONLY`) | linear algebra for NAM | Mozilla Public License 2.0 — source: https://gitlab.com/libeigen/eigen |

All DSP (pitch shifting, fuzz, amp and cabinet models, chorus, gate, EQs, reverb) is original code written for Swarmness;
only `.nam` captures run on NeuralAmpModelerCore.
No GPL-licensed code is included.
