PS4 MERGED AUTO FIRMWARE HOST
=============================

This package keeps the three source hosts isolated and adds only a top-level
auto-router plus the supplied background image.

Top-level files:
- index.html   : detects PS4 firmware and redirects to the matching original host
- icon0.png    : supplied full-screen router background

Original hosts (kept unchanged internally):
- host-9/      : routed for firmware 7.00 through 9.60
- host-713/    : routed for firmware 10.00 through 11.02 and 11.50 through 13.00
- host-raw13g/ : routed only for 13.02, 13.04, 13.50, and 13.52

The top-level router does not modify exploit logic, payloads, offsets, patches,
or firmware support inside any original host.

KAZANOVA 3D UI edition: visual-only CSS depth treatment; exploit/payload logic unchanged.
