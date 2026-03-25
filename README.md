# Triathlon Training Plan

A single-page interactive 16-week Olympic triathlon training plan, designed for printing or daily reference in the browser.

**Live page:** [k1monfared.github.io/triathlon-training-plan](https://k1monfared.github.io/triathlon-training-plan/)

## Overview

Targets the Olympic distance triathlon: **1500 m swim, 40 km bike, 10 km run**. The plan schedules 6 workouts per week (2 swims, 2 bikes, 2 runs) with recovery weeks at weeks 4, 8, and 12, building to race day in week 16.

## Features

- **Configurable rest day** -- choose any day of the week via a dropdown
- **Configurable start date** -- set the Monday of week 1 and all dates update automatically
- **Color / B&W toggle** -- switch to black-and-white mode for printing
- **PDF export** -- download the full plan as a landscape PDF
- **ICS calendar export** -- export all workouts to an `.ics` file you can import into Google Calendar, Apple Calendar, or Outlook
- **Workout detail cards** -- each cell shows the workout type, duration, and structured details (intervals, zones, drills)

## Workout Types

| Color | Type |
|-------|------|
| Blue | Swim |
| Orange | Bike |
| Green | Run |
| Purple | Brick (bike + run) |
| Red | Race day |

## Usage

Open `index.html` in any modern browser. No build step or server required. Everything is self-contained in a single HTML file (CSS, JS, and data are all inline).

To deploy on GitHub Pages, just enable Pages on the `main` branch -- the repo root contains `index.html`.

## License

MIT
