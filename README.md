# Govee (Josh Custom)

Personal fork of the SignalRGB Govee add-on, taken from the official **Development** branch
(gitlab.com/signalrgb/govee). Lives in its own repo so SignalRGB's launch-time re-sync can't
replace it with the official `main` branch.

Install: Win+R → `signalrgb://addon/install?url=https://github.com/jarriaga89/signalrgb-govee-custom`

Changes from upstream Development:
- Add-on renamed to "Govee (Josh Custom)" so it doesn't clash with the official one.
- H618A: plain strip with an adjustable "Segment Count" (default 10, range 1–60) instead of a fixed 10-LED subdevice.
- H618A: Auto protocol now resolves to Dreamview (confirmed working on the strip).
- H618A: Layout setting — Strip, Rectangle (one frame-shaped device) or 4 Strips (each side placed separately), with per-side segment counts, start corner and direction.

Uninstall the official Govee add-on first, or both will discover and fight over the same lights.
