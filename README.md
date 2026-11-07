# Omnis Target v0.2

**One curve. Every world.**

A nature informed target curve for IEMs, headphones, speakers, car cabins and marine systems, by TheBatKing (TBK) of Omnis Audio Lab.

Official home: https://omnisaudiolab.com

## Versions and naming

| Name | What it is |
|---|---|
| **Omnis Target** | **Neutral.** The baseline and reference curve. |
| **Omnis Bass Target** | **Bass Boosted Neutral.** Neutral with +3 dB below 100 Hz, easing back to Neutral by 250 Hz. |
| **Omnis Basshead Target** | **Basshead.** TheBatKing (TBK) personal preference. More bass than Bass Boosted, a deeper 250 Hz clearing, and a brighter top end that stays inside the Neutral tolerance bands. |

![Omnis target curves: Neutral, Bass Boosted Neutral and Basshead, with the Neutral tolerance band shaded](omnis_target_curves.svg)

## Files

| Version | squig.link (`frequency,target`) | AutoEq (`frequency,raw`) |
|---|---|---|
| Neutral | `Omnis Target.txt` | `omnis_target_v0.2.csv` |
| Bass Boosted Neutral | `Omnis Bass Target.txt` | `omnis_bass_target_v0.2.csv` |
| Basshead | `Omnis Basshead Target.txt` | `omnis_basshead_target_v0.2.csv` |

All curves run 20 Hz to 20 kHz at 48 points per octave, set to 0 dB at 1 kHz and defined for a 711 style coupler.

## Target and Tolerance (Neutral)

| Frequency | Target | Tolerance |
|---|---|---|
| 20 Hz | +9.5 dB | ±3 dB |
| 40 Hz | +9.0 dB | ±3 dB |
| 60 Hz | +8.0 dB | ±2 dB |
| 100 Hz | +5.0 dB | ±1.5 dB |
| 150 Hz | +2.5 dB | ±1 dB |
| 250 Hz | −0.5 dB (the tuck) | ±1 dB |
| 400 Hz to 1 kHz | 0 to +0.5 dB | ±1 dB |
| 2 kHz | +4.5 dB | ±1.5 dB |
| 3 kHz | +8.5 dB | ±2 dB |
| 4 kHz | +7.0 dB | ±2 dB |
| 6 to 8 kHz | +4.0 dB | ±2.5 dB |
| 10 kHz | +3.5 dB | ±3 dB |
| 15 kHz | +2.5 dB | ±4 dB |

* The sub bass band is wide (±3 dB) because seal and ear shape change bass a lot from person to person.
* Above about 10 kHz, treat the numbers as guidelines. Coupler readings are unreliable there, and many drivers roll off naturally.
* The data files extend to 20 kHz at +1.5 dB, but that last stretch is a gentle roll off, not a goal products must hit.
* Tolerance bands apply around each version’s own target.

## Status

v0.2 is a draft. It is built on published acoustic research and tuned by ear. Formal measurement and listening test results will be shared as they are completed. Offsets for non IEM systems are draft estimates and are listed on the website.

## Terms of Use and Licensing

The Omnis Target data is free to download for personal use, acoustic measurement comparison and personal parametric equalization.

* **Commercial audio hardware:** You may not manufacture, tune, market or sell commercial audio equipment (including IEMs, headphones or speakers) using this target without an official commercial licensing agreement from Omnis Audio Lab.
* **Adaptations:** You may adjust the curve for personal use and share adjusted versions for non commercial purposes, as long as you credit Omnis Audio Lab / TBK and clearly mark what you changed.
* **Attribution:** If this curve is hosted on a public database or measurement repository (such as squig.link), it must be clearly attributed to Omnis Audio Lab / TBK with a link back to https://omnisaudiolab.com.

© 2026 Omnis Audio Lab. This work is licensed under Creative Commons Attribution NonCommercial 4.0 International (CC BY-NC 4.0): https://creativecommons.org/licenses/by-nc/4.0/

## Contact

Collaboration and licensing inquiries: thebatking@omnisaudiolab.com
