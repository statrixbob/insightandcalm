---
{"dg-publish":true,"permalink":"/04-technical/guides/nomadic-sangha-sound-table/","dg-note-properties":{}}
---

### 🎭 Nomadic Master Table: RODE Wireless Pro vs. AirPods Pro 3

**Ecamm Signal Flow:** Top to Bottom (1 → 5)

|Module|Parameter|**Profile C: RODE (USB + Fur)**|**Profile D: AirPods Pro 3**|
|---|---|---|---|
|**System**|**Echo Cancellation**|**OFF**|**OFF**|
|**1. AUHiPass**|**Frequency**|**100 Hz**|**120 Hz**|
||**Gain**|**0 dB**|**0 dB**|
|**2. Sound Isolation**|**Mode / Amount**|**High Quality / 35%**|**High Quality / 45%**|
|**3. AUGraphicEQ**|**32Hz & 64Hz**|**-20 dB**|**-20 dB**|
|(10-Band)|**128Hz / 256Hz**|**0 dB / +2.0 dB**|**+2.0 dB / +3.0 dB**|
||**2k & 4k**|**+2.0 dB** (restore fur loss)|**+1.5 dB**|
||**Others**|**0 dB**|**0 dB**|
|**4. AUMultiband**|**Pre-gain**|**0.0**|**0.0**|
|(Details View)|**Post-gain**|**0.0**|**0.0**|
||**Attack Time**|**0.02** (seconds)|**0.02** (seconds)|
||**Release Time**|**0.1** (seconds)|**0.1** (seconds)|
||**EQ 1 (Lows)**|**-3.0**|**-3.0**|
||**EQ 2 (Warmth)**|**+3.5**|**+4.5**|
||**EQ 3 / EQ 4**|**0.0 / 0.0**|**0.0 / 0.0**|
|**5. AUPeakLimiter**|**Pre-gain**|**+2.0 dB**|**+5.0 dB**|
||**Attack**|**0.002** (seconds)|**0.002** (seconds)|
||**Release**|**0.04** (seconds)|**0.04** (seconds)|

---

### 🧘 The "Picnic Table" Logic

- **Why 120Hz for AirPods?** Since you don't have "cat hair" for your ears, the AirPods are more vulnerable to low-frequency wind "thumps." 120Hz creates a safer floor for the AI to work with.
    
- **Why +2.0dB at 2k/4k for RODE?** Furry windshields are great for wind, but they act as a "low-pass filter," slightly muffling your high-end clarity. This EQ boost "pokes" your theatre-trained voice back through the fur.
    
- **Why 0.1s Release?** Outdoors, background noises (dogs, cars, wind gusts) are unpredictable. A faster release ensures the compressor doesn't "hang" on a loud noise and accidentally quiet your voice right after.
    

### 🛠 Pro Habit for the M4 Air

When you sit down at that picnic table, I recommend doing a **5-second recording** in Ecamm using the RODE first. If you hear a "pumping" sound in the background, it means the wind is hitting the 35% isolation threshold. You can either nudge the Isolation up to **40%** or move the RODE mic slightly closer to your throat under a collar to give it more "shielding."

This completes your 2026 Mobile Technical Rider. You now have a side-by-side reference for every environment you guide in.