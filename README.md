# Benchmark Slope releases

`version.json` tells the Benchmark Slope app which version is current on each store. The app reads it at most once a day and shows a small "update available" note in Settings; if the installed version is below `minimum`, it shows a banner instead.

Bump `latest` when a release goes live on the store. Raise `minimum` only when an older version must stop being used. Keep versions as `major.minor.patch`.

Raw URL used by the app:
https://raw.githubusercontent.com/dive-in-digital-marketing-llc/benchmark-slope-releases/release/version.json
