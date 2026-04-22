---
{"dg-publish":true,"permalink":"/04-technical/guides/mobile-audio-setup-macbook-neo/","dg-note-properties":{}}
---


| **Module**              | **Parameter**       | **Profile A: Neo Internal Mic** | **Profile B: AirPods Pro 3** |
| ----------------------- | ------------------- | ------------------------------- | ---------------------------- |
| **1. AUHiPass**         | Frequency / Gain    | **80 Hz / 0 dB**                | **100 Hz / 0 dB**            |
| **2. AUSoundIsolation** | Mode / Amount       | **High Quality / 25%**          | **High Quality / 40%**       |
| **3. AUGraphicEQ**      | 32Hz & 64Hz         | **-20 dB**                      | **-20 dB**                   |
| (10-Band)               | 128Hz               | **0 dB**                        | **+1 dB**                    |
|                         | 256Hz               | **+1 dB**                       | **+3 dB**                    |
|                         | 2k & 4k             | **+1.5 dB**                     | **+1.0 dB**                  |
|                         | Others              | **0 dB**                        | **0 dB**                     |
| **4. AUMultiband**      | **Pre / Post Gain** | **0.0 / 0.0**                   | **0.0 / 0.0**                |
| (Details View)          | Attack / Release    | **0.02s / 0.2s**                | **0.02s / 0.1s**             |
|                         | EQ 1                | **-3.0**                        | **-3.0**                     |
|                         | **EQ 2 (Warmth)**   | **+2.0**                        | **+4.0**                     |
|                         | EQ 3 & 4            | **0.0**                         | **0.0**                      |
| **5. AUPeakLimiter**    | **Pre-gain**        | **+3.0 dB**                     | **+5.0 dB**                  |
|                         | Attack / Release    | **0.002s / 0.04s**              | **0.002s / 0.04s**           |
### 🧘 Key Differences at a Glance:

- **The Warmth Nudge:** The AirPods need much more help at **256Hz** and **EQ 2 (+4.0)** because Bluetooth audio naturally strips away the "chest resonance" of a theatre-trained voice.
    
- **The Safety Floor:** The AirPods use a **100Hz HiPass** to cut out the extra clothing rustle and movement noise that ear-mounted mics pick up.
    
- **The Power Lift:** The AirPods are quieter by design, so the Peak Limiter provides a **+5.0dB** lift to ensure your meditation guidance is loud and clear in the listeners' headphones.
    

### 🛠 Practical Application:

In Ecamm, I recommend saving these as two separate "Audio Presets."

1. Name the first one **"Neo Internal - Natural"**.
    
2. Name the second one **"AirPods Pro - Boosted"**.