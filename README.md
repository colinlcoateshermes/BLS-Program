# Bigger Leaner Stronger 4.0 — 20-Week Cut & Bulk Program

A mobile-friendly, day-by-day workout tracker based on Michael Matthews' *Bigger Leaner Stronger 4.0* (Fourth Edition).

Access it on your phone, check off exercises/meals/supplements each day, and your progress persists in your browser (localStorage).

## Quick Start

### Option 1: GitHub Pages (recommended)

1. This repo is already live at **https://colinlcoateshermes.github.io/BLS-Program/**
2. Open that URL on your phone — it's mobile-responsive.

### Option 2: Local file (no server)

Open `index.html` directly in your browser. localStorage persistence still works.

## Program Structure

### 20 Weeks — 4 Phases (each 5 weeks: 4 training + 1 deload)

| Phase | Weeks | Goal | Emphasis |
|-------|-------|------|----------|
| **Phase 1** | 1-5 (Cut) | Foundation | Bench Press, Deadlift, Dumbbell Press, Chin-ups |
| **Phase 2** | 6-10 (Cut) | Rotation | Incline Bench, Rows, OHP, Dips, Bulgarian Split Squats |
| **Phase 3** | 11-15 (Bulk) | Strength | Dumbbell Bench, Rows, Standing OHP, Chin-ups |
| **Phase 4** | 16-20 (Bulk) | Intensity | Arnold Press, Front Squats, Machine Reverse Fly, Split Squats |

Weeks 5, 10, 15, 20 are **deload weeks** — 2 sets of 2 reps on compounds, 2 sets of 4 on accessories.

### Weekly Schedule (BLS 4.0 5-Day Routine)

| Day | Workout | 
|-----|---------|
| **Monday** | **Push** — Bench press variations + triceps |
| **Tuesday** | **REST** |
| **Wednesday** | **Pull** — Deadlift + rows + pulldowns + biceps |
| **Thursday** | **Upper Body A** — Shoulder press + raises + triceps |
| **Friday** | **Legs** — Squat + RDL + leg press + lunges |
| **Saturday** | **Upper Body B** — Close-grip bench + chins + rows + curls |
| **Sunday** | **REST / Active Recovery** |

## Meal Plans

The app automatically serves the correct meal plan based on the current week:

| Phase | Meal Plan | Macros |
|-------|-----------|--------|
| **Cut (Weeks 1-10)** | Official BLS 4.0 210lb Cut | 2,305 cal — 233P / 236C / 52F (4 meals) |
| **Bulk (Weeks 11-20)** | Official BLS 4.0 210lb Lean Gain | 3,351 cal — 210P / 470C / 77F (5 meals) |

### Cut Meals (2,305 cal)
1. **Breakfast**: Greek yogurt, whey isolate, berries, granola
2. **Lunch**: Shrimp, white rice, sweet corn, bell pepper
3. **Snack**: Double whey shake, rice cakes, PBfit
4. **Dinner**: Lean beef burger bun, cheese, chocolate

### Bulk Meals (3,351 cal)
1. **Breakfast**: Greek yogurt, mixed berries, granola
2. **Lunch**: Chicken burrito bowl with tortilla, refried beans, avocado
3. **Snack**: Whey shake, PB&J sandwiches
4. **Dinner**: Sirloin steak, sweet potato, green beans
5. **Pre-Bed**: Casein shake, banana

## Each Day Shows

- **Exercises** with sets, reps, rest times, and warm-up protocols
- **Deload weeks** with reduced volume (2×2 compounds, 2×4 accessories)
- **Nutrition** with official BLS 4.0 meal plans and macronutrient targets
- **Supplements** checklist

## Features

- **Check-off persistence** — tap any circle to mark it complete. Taps are saved automatically to your browser (localStorage).
- **Exercise descriptions** — tap "Show description" on any exercise for a full how-to, including links to relevant book screenshots.
- **Set logging** — log weight and reps per set for every exercise. Data persists in the browser.
- **RPE traffic light** — rate each exercise as Easy / OK / Hard.
- **Image viewer** — tapping a screenshot link opens it full-screen. Tap again to close.
- **Progress stats** — completion percentage, total checkmarks, and weekly streak counter.
- **Week navigation** — jump between weeks. Deload weeks are highlighted in orange.
- **Reset** — use the red reset button at the bottom to clear all progress.
- **Import/Export** — download and restore your progress as JSON files.

## Exercise Rotation

Each phase rotates exercises to prevent adaptation and target muscles from different angles:

**Push (Mon)**: Phase 1 — Barbell Bench, Incline Bench, DB Bench, Triceps Pushdown → Phase 2 — Incline Bench, DB Bench, Incline DB Bench, Skullcrushers → Phase 3 — DB Bench, Incline Bench, Barbell Bench, Triceps Pushdown → Phase 4 — Incline DB Bench, Barbell Bench, Incline Bench, Skullcrushers

**Legs (Fri)**: Phase 1 — Squat, Leg Curl, Leg Press, DB Lunges → Phase 2 — Squat, RDL, Front Squat, Bulgarian Split Squats → Phase 3 — Same as Phase 1 → Phase 4 — Squat, RDL, Front Squat, Bulgarian Split Squats

**Upper Body A (Thu)**: Phase 1 — Seated DB Press → Phase 2 — Seated Barbell OHP → Phase 3 — Standing Barbell OHP → Phase 4 — Arnold Press (new!)

## File Structure

```
BLS-Program/
├── index.html          # Main app — open this in browser
├── README.md           # This file
└── images/
    ├── squat-setup.jpeg
    ├── squat-bottom.jpeg
    ├── squat-ascent.jpeg
    ├── squat-bar-position.jpeg
    ├── front-squat-grip.jpeg
    ├── front-squat-position.jpeg
    ├── bench-arm-angles.jpeg
    ├── deadlift-start.jpeg
    ├── deadlift-top.jpeg
    ├── sumo-deadlift.jpeg
    ├── hex-bar-deadlift.jpeg
    ├── rdl.jpeg
    ├── military-press-station.jpeg
    ├── military-press-top.jpeg
    ├── back-anatomy.jpeg
    ├── deltoid-anatomy.jpeg
    ├── quad-anatomy.jpeg
    ├── hamstring-anatomy.jpeg
    ├── calf-anatomy.jpeg
    ├── biceps-anatomy.jpeg
    ├── triceps-anatomy.jpeg
    └── abs-anatomy.jpeg
```

## Book Source

This program is based on **Bigger Leaner Stronger 4.0: The Simple Science of Building the Ultimate Male Body** by Michael Matthews (Fourth Edition).

Core principles:
- **4-6 rep range** for working sets at 80-85% of 1RM
- **Compound lifts first**: Squat, Deadlift, Bench Press, Overhead Press
- **Progressive overload**: Add weight or reps every session
- **Exercise rotation**: Change primary exercises every phase (5 weeks)
- **Deload weeks**: Every 5th week — reduce volume, maintain form
- **3 minutes rest** between heavy sets, 2 for accessory
- **Proper warm-up**: 4 warm-up sets before first compound lift

## License

For personal use. The book content is copyright Michael Matthews. This is a distillation/tracker, not a replacement for the book.