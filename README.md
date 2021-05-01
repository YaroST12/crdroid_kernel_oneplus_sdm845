## Hola amiguitos

This is my attempt to fix up and add a little crDroid customization flavor back into the sdm845 kernel tree for OnePlus 6 & 6T (enchilada & fajita).

Rebased on the official lineage-18.1 branch from LineageOS as of May 2021, with some extra goodies added in like clang-12 support, multiple vibration type support, 
wireguard support, battery-idle-mode-enabled charging switches, and OOS Q source additions to support DC dimming (LOS Anti Flicker).

We're also reverting to CAF tag LA.UM.8.3.r1-08800 for the WiFi driver, as the newer Android 11-based updates have big problems with our Android 10-based kernel 
(hotspot causing soft reboot, and connectivity problems to access points with double-wide channel mode enabled).
