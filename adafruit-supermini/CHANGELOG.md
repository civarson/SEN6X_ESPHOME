# Firmware builds

Counted from the original doctormord/SEN6X_ESPHOME config. The running build
shows in Home Assistant (device info "Firmware", and the "Firmware Build"
diagnostic entity) and on screen as the last item after a button tap.
Bump `build_number` in `common/aqs-ui.yaml` with every change you flash.

| Build | Date | Changes |
|---|---|---|
| 1 | Nov 14 | Original config with Austin location, US time servers, `last_c` fix; VOC/NOx keys renamed |
| 2 | Nov 14 | °F, arc legend, overall status ring, Wi-Fi icon, Air Quality Level/Status entities |
| 3 | Nov 14 | Split into device / preview / shared UI files; `legacy_wifi` network |
| 4 | Nov 14 | Status ring removed, thicker arcs, arc names at 12 o'clock, loading spinner |
| 5 | Nov 14 | 3×2 metric grid, signal bars, bottom line with clock and printer status |
| 6 | Nov 14 | Status word above the big number, larger clock |
| 7 | Nov 14 | Screen rotated 180° |
| 8 | Nov 15 | Rotation back to 0° (display tab-up, case v2) |
| 9 | Nov 15 | Faded Wi-Fi bars, printer shown only while printing, marquee, button (tap info / hold restart) |
| 10 | Nov 15 | Screen rotated 180° |
| 11 | Nov 15 | Clock brightness, blinking colon, 12/24-hour settings |
| 12 | Nov 15 | 10 color schemes (dark + light) |
| 13 | Nov 15 | Rotation 0° for the alarm-clock case (tab-down) |
| 14 | Nov 16 | Screen rotated 180° (new SuperMini) |
| 15 | Nov 16 | Screen Rotation setting in Home Assistant |
| 16 | Nov 17 | Sleep schedule (screen off at fixed hours) |
| 17 | Nov 17 | Build number: diagnostic entity, firmware version, info page |
| 18 | Nov 17 | Screen Margin setting (default 6 px) pulls the arcs in from the bezel |
| 19 | Nov 17 | Fix: backlight sometimes stuck at 100% until a reboot; brightness fades over 1 s. Printer entities are now substitutions; Bambu/OctoPrint status words recognized |
