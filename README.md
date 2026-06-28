# drift

Wind-driven particle flow. Pastel particles float along real-time San Francisco wind currents.

**Visual Style:** Light — Breeze (pastel sky blue background, soft blue/pink/lavender/yellow particle trails)

**Data Source:** Open-Meteo San Francisco wind data (realtime)

**How it works:**
- Fetches live wind direction and speed from Open-Meteo
- 100 particles move with wind vectors plus gentle noise perturbation
- Each particle leaves a 60-frame pastel trail
- Wind speed and direction shown in top-right corner
- Tap to reset particles

**Live:** https://parthchandak02.github.io/drift/

**Tech:** Native Canvas 2D, single HTML file, zero dependencies.
