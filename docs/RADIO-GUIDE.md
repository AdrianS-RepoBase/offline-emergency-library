# Emergency Radio Communications Guide — Germany
### Funk im Notfall: CB, PMR446, Freenet, Amateurfunk, Rundfunk-Empfang (Deutschland)

How to communicate and stay informed by radio when phones and internet are down, **under
German rules** (Bundesnetzagentur, BNetzA). German terms are given in *italics* — handy
with the offline dictionary in this kit (`Deutschland\Woerterbuch`).

> **Rules in normal times:** **CB, PMR446 and Freenet** are license-free
> (*Allgemeinzuteilung*, no registration, no fees) **but only with type-approved
> equipment** (CE mark) and **no modification** of power or antenna. **Amateur radio**
> needs a **license + call sign** from the BNetzA (exam). **Receiving** broadcasts is
> always fine. **Listening to authority/rescue radio (BOS, *Behördenfunk*) or
> commercial traffic is not allowed.**
> In a genuine life-threatening emergency, using any available radio to call for help
> can be justified (*rechtfertigender Notstand*, § 34 StGB) — no guarantee, so learn
> and practice **before** you need it. This guide is not legal advice; rules change —
> check bundesnetzagentur.de when online.

---

## 0. First: official emergency channels (not radio)

| What | How |
|---|---|
| Fire / rescue / ambulance | **112** (also works on any mobile network without SIM/credit; EU-wide) |
| Police | **110** |
| Non-urgent medical help | **116 117** (*ärztlicher Bereitschaftsdienst*) |
| Warnings | **NINA** and **Katwarn** apps, **DWD WarnWetter**, **Cell Broadcast** (*DE-Alert*, pops up on phones), radio, sirens |
| Sirens | **Rising/falling tone for 1 min = *Warnung*** → turn on radio / warning app, follow instructions. **Constant tone for 1 min = *Entwarnung*** (all clear). |

If networks are down, **112 may not work** — then radio and getting to a fire station /
police station / *Anlaufstelle* ("Katastrophenschutz-Leuchtturm", where set up) matter.

---

## 1. The quick version — what to grab and what to know

| Need | Best tool | License | Typical range |
|---|---|---|---|
| Family/group nearby (property, neighborhood, hiking) | **PMR446** or **Freenet** handheld | none | 0.5–3 km |
| Vehicle-to-vehicle, convoys | **CB (27 MHz)** | none | 1–15 km (more in open terrain) |
| Town/region coordination, repeaters | **Amateur radio 2 m / 70 cm** | Class E / A (or N) | 5–50 km via repeater |
| Long distance / outside the affected region | **Amateur radio HF** | Class A (Class E: limited HF) | 100s–1000s km |
| News, warnings, official info | **FM + DAB+ radio** (battery/crank) | none (receive) | regional |
| Hear the world | **Shortwave receiver** | none (receive) | worldwide |

**Three things:**
1. **Listen first.** A cheap receiver tells you what's going on.
2. **Higher antenna = more range**, more than watts.
3. **Agree on channels and check-in times in advance** (card at the end).

---

## 2. How radio works (60 seconds)

- Radios convert voice into **radio waves** at a **frequency** (kHz, MHz). Both radios
  need the **same frequency and mode** (FM, AM, SSB; for digital the same system).
- One person talks at a time (**PTT** = push-to-talk).
- **VHF/UHF** (PMR446, Freenet, ham 2 m/70 cm): mostly line of sight — hills and
  buildings block, **repeaters** (*Relaisfunkstellen*) extend range.
- **HF/shortwave** (CB 27 MHz, ham HF): bounces off the ionosphere ("skip") and can
  travel far; depends on time of day and sun.

---

## 3. CB radio (*CB-Funk*) — license-free, vehicle-friendly

- **27 MHz.** FM: **80 channels** (the German 40 + 40 extra), AM: 40 channels.
  Radios must be type-approved for Germany (**FM + AM, DE channel set**).
- **Power (Germany):** FM **4 W**, AM **1 W**, SSB **12 W PEP**. Do not exceed.
- **Key channels:** **Channel 9 = emergency/help** (*Notrufkanal*, FM and AM);
  **Channel 19 = traffic/highway** (*Verkehrskanal*, FM). Use another free channel for your group.
- Modes: both radios must use the same mode (FM vs AM vs SSB).
- Good for: convoys, local coordination, zero setup, **no registration**.
- Note: some volunteers monitor Channel 9 but there is **no guarantee** anyone does.
  Use it as a last resort, not as a replacement for 112.

---

## 4. PMR446 and Freenet — the walkie-talkie families

### PMR446 (license-free, EU)
- **446.0–446.2 MHz**, **16 analog channels** (plus digital channels on newer radios,
  dPMR/DMR Tier 1).
- **Max 0.5 W**, **fixed antenna** (no external antenna allowed). Range **~0.5–3 km**.
- Use **CTCSS/DCS "privacy codes" only to filter**, they do **not** make a channel private.
- Cheap, works with every brand (analog). Best default for families and groups.

### Freenet (license-free, Germany)
- **149.0125–149.1125 MHz**, **6 channels**, **max 0.5 W**, fixed antenna. VHF
  often reaches farther outdoors than UHF PMR446. Fewer radios in the field — choose
  it **together with** PMR446 only if your group has matching devices.

### Not for Germany
**FRS/GMRS/MURS are US services** — don't buy/use them here (not permitted).
Similarly **LPD433** has very low power (10 mW): fine for short range, not for emergencies.

---

## 5. Amateur radio (*Amateurfunk*) — the serious emergency option

Amateur radio operators relay messages, coordinate help, and often support
authorities (*Notfunk*, e.g. within **DARC** / DLRG / THW / Rescue services' support
groups). Check local groups (*Ortsverband*, "OV") now — they know the area's repeaters.

### Licensing (Germany, by BNetzA)
Exam on two parts: **technology** and **operations/regulations** (*Technik* /
*Betriebstechnik & Vorschriften*). The **question catalogue is public** (BNetzA
website — **download it while you have internet**).

| Class | Typical privileges (summary) |
|---|---|
| **N** (*Einsteigerklasse*, introduced 2024) | 10 m, 2 m, 70 cm; up to ~10 W — entry level |
| **E** | VHF/UHF + parts of HF, up to ~100 W on some VHF/UHF, 10 W on HF |
| **A** | all amateur bands, up to **750 W** |

*Privileges and power limits are summarized from memory — verify in the current AFuV
(Amateurfunkverordnung) / BNetzA tables.* Call signs start with **DL / DK / DJ / DO / DB…**
In a life-threatening emergency, calling for help is justified even without a license
(see top), but you'll be far more effective if trained.

### Main bands
- **2 m (144–146 MHz, VHF)** and **70 cm (430–440 MHz, UHF):** local, **repeaters**.
  - **2 m FM calling frequency (*Anruffrequenz*): 145.500 MHz**
  - **70 cm FM calling frequency: 433.500 MHz**
- **HF:** 80 m (3.5 MHz, regional at night), **40 m (7 MHz, regional day+night, standard
  for regional nets)**, 20 m (14 MHz, long distance by day).

### Repeaters (*Relais*)
Receive on one frequency, re-send on another. Typical shift in Germany: **2 m: −0.6 MHz,
70 cm: −7.6 MHz**; many need a **CTCSS tone** (often 67.0 Hz) or a **1750 Hz tone
burst**. **Print the repeater list for your area** (DARC / local OV) now.

### Simplex
Talk directly (no repeater) on a simplex channel, e.g. 145.500 MHz. Works when repeaters
are down — range is line of sight; go up a hill.

### Digital/text (advanced)
Winlink (email over radio), FT8, APRS — need extra gear and training.

---

## 6. Broadcast radio — warnings and news (the most important in practice)

- **FM (*UKW*) and DAB+** are the main channels for official warnings and information.
  Public broadcasters (ARD state radio, Deutschlandfunk) carry emergency
  announcements. A **battery/crank/solar radio with FM and DAB+** is the single most
  useful radio item.
- **Medium/long wave (AM) broadcasting is largely switched off** in Germany — don't
  rely on it for German stations.
- **Shortwave (SWL)** (≈1.8–30 MHz): hear international broadcasters (BBC, Deutsche
  Welle, etc.), time signals, ham traffic. **No license needed to receive.** A
  receiver with **SSB** hears much more; a long-wire antenna improves reception.
- **No NOAA weather radio in Germany.** Weather warnings: **DWD** (via apps, FM/DAB+
  announcements).
- Don't listen to BOS/authority or commercial radio (not permitted, § TKG).

---

## 7. Antennas, power & range

- **Height beats power.** Roof/tree/mast adds more than any amplifier.
- **PMR446/Freenet/CB:** limited power and (for PMR/Freenet) fixed antenna by law —
  stay legal; improve range by **position** (hills, open ground, outside buildings).
- **Resonant antenna for the band** beats random wire (ham).
- **VHF/UHF:** range ≈ line of sight. **HF:** low bands better at night, high bands by day.
- **Power:** spare batteries, power banks, **12 V battery**, **solar panel**, car charger.
- **Safety:** keep antennas away from power lines; ground equipment against lightning.

---

## 8. How to call for help

1. **Listen first** for ongoing emergency traffic.
2. **Use the distress call:** **"MAYDAY, MAYDAY, MAYDAY"** (life in danger) or
   **"PAN-PAN"** (urgent). In German, **"Notruf, Notruf, Notruf"** is understood too.
   - **CB: Channel 9.** Ham: local emergency net, repeater, or **145.500 MHz** calling frequency.
3. **Give the essentials slowly, then repeat:**
   - **Who** (name/call sign) — **Where** (address, street, GPS, landmarks, *Rettungspunkt* / forest rescue point number) — **What** (injury, fire…) — **What you need**.
4. **Spell hard words** (alphabets below). Say numbers digit by digit.
5. **Stay on frequency**, repeat at intervals if no answer.

### German spelling alphabet (DIN 5009)
Anton, Ärger, Berta, Cäsar, Dora, Emil, Friedrich, Gustav, Heinrich, Ida, Julius,
Kaufmann, Ludwig, Martha, Nordpol, Otto, Ökonom, Paula, Quelle, Richard, Samuel,
Schule, Tanja, Ulrich, Übermut, Viktor, Wilhelm, Xanthippe, Ypsilon, Zacharias.
For international contacts use **NATO**: Alpha Bravo Charlie Delta Echo Foxtrot Golf
Hotel India Juliet Kilo Lima Mike November Oscar Papa Quebec Romeo Sierra Tango
Uniform Victor Whiskey X-ray Yankee Zulu.

### Pro-words (German / English)
| German | English | Meaning |
|---|---|---|
| **Kommen** | Over | your turn |
| **Ende** | Out | finished (not "Kommen und Ende") |
| **Verstanden** | Roger / Copy | understood |
| **Bitte wiederholen** | Say again | repeat |
| **Positiv / Negativ** | Affirmative / Negative | yes / no |
| **Warten** | Stand by | wait |

---

## 9. A sensible emergency radio kit

- [ ] **FM/DAB+ crank/solar radio** — warnings & forecasts (top priority).
- [ ] **Shortwave receiver with SSB** — international news (RX only).
- [ ] **2+ PMR446 handhelds** (and spare batteries) — family/group, license-free.
- [ ] **CB radio (FM/AM, DE-approved)** if you travel by vehicle.
- [ ] **A dual-band 2 m/70 cm ham handheld** and Class E/N license — repeater access.
- [ ] **(Advanced) HF ham radio** + Class A.
- [ ] **Power:** spare batteries, power banks, 12 V battery, solar panel, car charger.
- [ ] **Printed repeater list, this card, notebook & pencil.** Phones may be dead.

---

## 10. Print-and-keep frequency card

```
=====================  EMERGENCY RADIO CARD (DE)  =====================
 Our group PRIMARY channel : _______________   Mode: _______
 Our group BACKUP channel  : _______________   Mode: _______
 Check-in times (daily)    : _______  _______  _______

 Emergency number (phone)... 112 (fire/rescue)   110 (police)
 CB emergency / help ....... Channel 9 (FM and AM)
 CB traffic / travel ....... Channel 19 (FM)
 PMR446 .................... 446.000 - 446.200 MHz, channels 1-16
 Freenet ................... 149.0125 - 149.1125 MHz, channels 1-6
 Ham 2 m calling ........... 145.500 MHz  (FM)
 Ham 70 cm calling ......... 433.500 MHz  (FM)
 Sirens: rising/falling 1 min = WARNING -> radio on; steady 1 min = ALL CLEAR

 Local repeaters (output / shift / tone):
   1) ________ MHz  /  ____  /  tone ______  (____________)
   2) ________ MHz  /  ____  /  tone ______  (____________)
   3) ________ MHz  /  ____  /  tone ______  (____________)

 Distress voice: "MAYDAY x3" (life threat) or "PAN-PAN x3" (urgent)
 Say: WHO you are - WHERE you are - WHAT's wrong - WHAT you need
=======================================================================
```

---

## 11. Where to learn more offline (in this kit)

- `Deutschland\BBK-Ratgeber\` — official German preparedness guides.
- `Deutschland\ZIM-Deutsch\` — German Wikipedia/Wikibooks/Wikivoyage (Kiwix).
- `Deutschland\Woerterbuch\` — offline dictionary (see `HOW-TO-USE-DICTIONARY`).
- **Appropedia / iFixit** (via Kiwix) for antenna/electronics articles.
- Download the **Amateurfunk question catalogue** (BNetzA) while online.

> Practice now: program channels, test check-ins with your group, learn the menus.
