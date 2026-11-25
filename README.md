# ProX OBD Toolkit (complete)

Personal multi-make OBD diagnostics for **phone** and **Android car stereo**. No local webserver required.

## Run offline (recommended)

1. Download **[ProX-OBD-Toolkit.html](https://github.com/Gerrievt90/prox-obd-toolkit)** from this conversation / project files (single-file app).
2. Copy to your phone or head unit (USB, Drive, email).
3. Open with **Chrome**.
4. Tap **Connect → Demo mode**.
5. Tap **CAR** for head-unit layout, **NIGHT** for low glare.

## Features

| Area | What you get |
|------|----------------|
| Live data | RPM, speed, temps, load, fuel, voltage, more + readiness |
| Codes | Active / pending / stored / **permanent** + clear paths |
| TPMS | Pressures, battery, sensor IDs, relearn |
| Keys | Slot table + GM / Ford / Toyota / generic guided procedures |
| Controls | Body, climate, chassis, service, powertrain routines (vehicle-dependent) |
| ECU | Module scan, package pre-check (flash write blocked for safety) |
| Display | Car mode, night mode, multi-make 2005–2025 profiles |

## Bluetooth

- **Demo** works from a local file with no network.
- **Live ELM327** needs a browser with Web Bluetooth (Chrome/Edge) and ideally **HTTPS**.
- Pair a Bluetooth OBD adapter to the head unit / phone first.

## Limits (by design)

- Permanent DTCs often clear only after monitors pass.
- Key programming on many 2010+ cars needs OEM security.
- Full vehicle control is limited to what the car exposes over OBD/UDS — not manufacturer-level control of every system.
- ECU flash is intentionally blocked without a programming-grade interface.
- **Personal use only** on vehicles you own or are authorized to service.

## Repo status

Styles and shell pages may live in this repo. The **single HTML file** is the complete, self-contained app.
