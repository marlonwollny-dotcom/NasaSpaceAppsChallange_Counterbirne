# Mission Architect — Space Mission Design Game

**NASA Space Apps Challenge 2026 · Challenge: “Space Mission Design Game” · Team Counterbirne**

▶ **Play in your browser:** https://marlonwollny-dotcom.github.io/NasaSpaceAppsChallange_Counterbirne/

📄 **Demo slides (PDF, 7 slides):** https://marlonwollny-dotcom.github.io/NasaSpaceAppsChallange_Counterbirne/demo/Mission_Architect_Counterbirne.pdf

No installation, no login, no external dependencies. The whole game is a single file (`index.html`).

## The problem

Designing a space mission means balancing science goals, spacecraft design, instruments, launch vehicles, budget, power, mass, communications and orbital constraints. Students rarely get to try a whole mission from concept to operations, so these trade-offs stay abstract.

## Our solution

*Mission Architect* lets 1–4 players design, fly and evaluate a complete space mission:

1. **Choose a mission** — each one asks a real science question:
   - 🌍 *Blue Marble Watch* — spot wildfires and crop stress from low Earth orbit
   - 🌙 *Lunar Ice Hunter* — map water ice in the Moon’s permanently shadowed craters
   - 🔴 *Red Planet Climate* — track Mars’ seasons, dust and atmospheric loss
2. **Design the spacecraft** — orbit, launch vehicle, ground stations, up to four instruments, solar arrays, battery, pointing system, propulsion and propellant load, antenna and flight computer. A live dashboard shows budget, launch mass, power, eclipse energy, Δv, data flow and a science forecast.
3. **Flight readiness review** — blockers and warnings explained, then a **Go/No-Go poll** in which every crew role votes.
4. **Fly the mission** day by day — launch, cruise, orbit insertion and operations, with anomalies (solar storms, reaction-wheel failures, debris conjunctions, solar conjunction, budget cuts…) that the responsible role must decide on.
5. **Debrief** — a score across five criteria (mission performance, science value, resource efficiency, decision quality, teamwork), a cause-and-effect explanation of *why* the mission went the way it did, and a table to compare designs. Re-fly under identical conditions to compare designs fairly.

### Team play
Four roles with deliberately conflicting goals: **Mission Lead** (stay under budget), **Payload Scientist** (maximise science), **Systems Engineer** (keep power and mass margins), **Comms & Data Lead** (get every bit home). The best crews negotiate designs where everyone wins.

### Real physics, honestly labelled
- Orbital period (Kepler’s 3rd law), eclipse duration, Tsiolkovsky rocket equation, link budget (rate ∝ antenna diameter² × power ÷ distance²), battery depth of discharge, solar-array degradation.
- Planet radii, gravitational parameters, solar irradiance and distances from the [NASA Planetary Fact Sheets](https://nssdc.gsfc.nasa.gov/planetary/factsheet/).
- Component masses, costs and science values are simplified game values; the in-game “Data & sources” panel separates real data from game-model values.

## Tech
Plain HTML, CSS and JavaScript with Canvas graphics. No frameworks, no build step, works offline. Designs can be shared as links, and a leaderboard is stored locally in the browser.

## AI disclosure
The game’s source code was developed with the help of an AI assistant (Claude, Anthropic) and reviewed and tested by our team. No AI-generated images, audio or video and no NASA logos or insignia are used. This is an independent educational project, not affiliated with or endorsed by NASA.
