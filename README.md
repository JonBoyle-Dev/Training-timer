# Training Timer 🏋️

A dead-simple, **free**, offline workout timer. One self-contained HTML file — no install, no accounts, no server. Build up your session, hit start, and a bell rings at the end of each timed interval and each rest period so you never have to watch the clock.

## Features

- **Phone-first** — big tap targets, screen stays awake during a workout. Works on desktop too.
- **Runs offline** — everything is in one `.html` file. The bell is synthesised in-browser (Web Audio), so there are no sound files to download.
- **Saves automatically** — your programs and edits live in the browser (`localStorage`) on each device.
- **Smart run engine** — for timed moves (planks, boxing rounds) it counts down the work interval; for rep-based moves you tap **Set Done ✓** and the rest timer starts. Bell + 3-count warning ticks, then it auto-advances to the next set/exercise.
- **Full editing** — add / edit / delete exercises and whole workout days, with per-exercise photos and per-day poster images.
- **Backup & Restore** — export/import a `.json` to move everything between devices.

## Pre-loaded programs

- **Day 1 · Upper Body** — Chest · Back · Shoulders · Arms
- **Day 2 · Lower Body** — Legs · Glutes · Calves · Core
- **Day 3 · Full Body** — Strength · Muscle · Fat loss
- **Boxing Day** — ~90 min of rounds & conditioning (rounds mapped to sets × work/rest)
- **Core Finisher** — stomach & core circuit

## Usage

1. Open `workout-timer.html` in any browser (double-click it).
2. Tap a day → review the exercises → **Start Workout**.
3. To use it at the gym, put the file on your phone and "Add to Home Screen" so it launches like an app.

### Adding poster images

Drop the program poster images into the same folder as the HTML file, named `day1`, `day2`, `day3`, `boxing`, `core` (`.jpg`, `.png`, `.jpeg` or `.webp`). Each day will show its poster at the top — tap it to view full-screen. You can also upload a poster from inside the app (day editor), which is handy on mobile.

## Tech

Plain HTML + CSS + vanilla JavaScript. No dependencies, no build step.
