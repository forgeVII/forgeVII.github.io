# forgeVII.github.io

Personal portfolio hub — systems integration, hardware test and physical prototyping.

## Live

- **GitHub Pages:** https://forgevii.github.io
- **Custom Domain (after is-a.dev approval):** https://forgevii.is-a.dev

## Positioning

Public-facing maker narrative stays intact: scrap wood, zero budget, real photos, working hardware.
The formal ATS resume is separate (`D:\part D\JOLT\Engeenring\Systems_Integration\RESUME_ATS.md`).
Firmware for these builds is AI-assisted — this site shows integration, bench diagnostics and
field testing, not code authorship.

## Features

- Terminal boot sequence
- Animated radar hero
- Project cards with real photos
- Embedded YouTube demo cards (newest short first)
- Skills grouped as Integration & Test / Electrical & Power / Tools & Platforms
- Scroll reveal animations and stat counters

## Projects

| Project | Description | Links |
|---|---|---|
| **Laser Turret** | STM32 + 2 servos + laser, ESP32 Wi-Fi bridge, PC vision, 2 s link-loss watchdog | [Turret](https://github.com/forgeVII/laser_turret) · [PSU](https://github.com/forgeVII/laser_turret_psu) · [Demo](https://youtube.com/shorts/UFWoeOp6Qgk) |
| **TBAS** | Tactical Battlefield Awareness Suite — TDOA acoustics + rolling-code IFF + browser radar | [GitHub](https://github.com/forgeVII/TBAS) |
| **HOTAS_Joystick** | DIY HOTAS sidestick from furniture scrap — STM32 USB HID | [GitHub](https://github.com/forgeVII/HOTAS_Joystick) |
| **DIY-Rough-Gamepad** | Handmade USB HID gamepad — STM32, MPU6050, 12 buttons | [GitHub](https://github.com/forgeVII/DIY-Rough-Gamepad) |

## Media

- `media/turret/` — turret overview photo
- `media/hotas/` — HOTAS photos (hero, front, side, electronics)
- `media/tbas/` — TBAS photos (hero, electronics, circuit)
- `media/gamepad/` — Gamepad photos (design, electronics, rough)

## Development

Edit `index.html` and push to `master`. GitHub Pages serves it automatically.

To add a project: duplicate a `.project` block in `index.html` and add photos to `media/`.
Keep demo videos before photos in the page order.

## Custom Domain Setup

See `docs/DOMAIN_SETUP.md` for the is-a.dev registration procedure.
