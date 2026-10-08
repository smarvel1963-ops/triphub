# Trip Hub
Save path: C:\MarvelApps\triphub\README.md

Live: https://smarvel1963-ops.github.io/triphub/ - app #3 of the Marvel Corp Hub family (Scott 2026-10-07, Trip Hub
blueprint: C:\MarvelDesktop\docs\TRIP_HUB_PLANS_FROM_OUTSIDE_CHAT_2026-10-04.md, paste 4).

This repo is Trip Hub's OWN shell: `index.html`, `manifest.json`, icons and `sw.js`. The app itself is the shared Hub
engine in the Day Hub repo run with `window.DH_MODE = "trip"` - the same engine Cruise Hub runs with "cruise", so a fix
reaches all three apps.

- Own data on the phone (`triphub.v1`) and own Google Drive backup (`triphub.json`).
- Hub family: linked with Day Hub (read only both ways), like Cruise Hub.
- Pro: no product of its own yet - Day Hub Pro unlocks Trip Hub.
- Tests + release steps: the Day Hub repo (`python tests/run_tests.py`).
