# Bigger Leaner Stronger 4.0 — 54-Week Annual Program

A mobile-friendly, day-by-day workout tracker based on Michael Matthews' *Bigger Leaner Stronger 4.0* (Fourth Edition).

Access it on your phone, check off exercises/meals/supplements each day, and your progress persists in your browser (localStorage).

## Quick Start

### Option 1: GitHub Pages (recommended)

1. This repo is already live at **https://colinlcoateshermes.github.io/BLS-Program/**
2. Open that URL on your phone — it's mobile-responsive.

### Option 2: Local file (no server)

Open `index.html` directly in your browser. localStorage persistence still works.

## Program Structure

### 54 Weeks — 6 Phases (each 9 weeks: 8 training + 1 deload)

| Phase | Weeks | Goal | Emphasis |
|-------|-------|------|----------|
| **Phase 1** | 1-9 (Cut) | Foundation | Bench Press, Deadlift, Dumbbell Press, Chin-ups |
| **Phase 2** | 10-18 (Cut) | Rotation | Incline Bench, Rows, OHP, Dips, Bulgarian Split Squats |
| **Phase 3** | 19-27 (Bulk) | Strength | Standing OHP, Barbell Row, Chin-ups |
| **Phase 4** | 28-36 (Bulk) | Intensity | Arnold Press, Front Squats, Machine Reverse Fly, Split Squats |
| **Phase 5** | 37-45 (Bulk) | Foundation Return | Same rotation as Phase 1 — Bench/Deadlift focus |
| **Phase 6** | 46-54 (Bulk) | Rotation Return | Same rotation as Phase 2 — Front Squats, Dips, Pull-ups |

Weeks 9, 18, 27, 36, 45, 54 are **deload weeks** — 2 sets of 2 reps on compounds, 2 sets of 4 on accessories.

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

### Morning Workout Routine

All training sessions follow this morning schedule:

1. **Pre-Workout Shake**: 1 scoop whey isolate + 5g creatine + pre-workout (caffeine)
2. **WORKOUT** (60-75 min)
3. **Post-Workout Breakfast**: Soy yogurt, whey, berries, granola (or bulk equivalent)

The app's meal plans are ordered accordingly — Pre-Workout first, then Post-Workout Breakfast after the workout.

### Dairy-Free Notes

All meal plans are **100% dairy-free**:
- Yogurt replaced with soy-based protein yogurt
- Cow's milk replaced with **soy milk** throughout
- Cheese removed from meals
- Half-and-half replaced with black coffee or soy creamer
- Whey isolate (≤0.5% lactose) retained as it's well-tolerated
- Casein protein retained for the pre-bed shake (can substitute with soy protein isolate if needed)

## Meal Plans

The app automatically serves the correct meal plan based on the current phase:

| Phase | Meal Plan | Macros |
|-------|-----------|--------|
| **Cut (Phases 1-2, Wks 1-18)** | Official BLS 4.0 210lb Cut (dairy-free, soy milk) | 2,305 cal — 233P / 236C / 52F (5 meals) |
| **Bulk (Phases 3-6, Wks 19-54)** | Official BLS 4.0 210lb Lean Gain (dairy-free, soy milk) | 3,351 cal — 210P / 470C / 77F (6 meals) |

### Cut Meals (2,305 cal) — Morning Workout Schedule
1. **Pre-Workout**: Whey isolate, creatine, pre-workout (caffeine)
2. **Post-Workout Breakfast**: Soy yogurt, whey isolate, berries, granola
3. **Lunch**: Shrimp, white rice, sweet corn, bell pepper
4. **Snack**: Double whey shake (soy milk), rice cakes, PBfit
5. **Dinner**: Lean beef burger bun, tomato/lettuce

### Bulk Meals (3,351 cal) — Morning Workout Schedule
1. **Pre-Workout**: Whey isolate, creatine, pre-workout (caffeine)
2. **Post-Workout Breakfast**: Soy yogurt, mixed berries, granola
3. **Lunch**: Chicken burrito bowl (no cheese), avocado
4. **Snack**: Whey shake (soy milk), PB&J sandwiches
5. **Dinner**: Sirloin steak, sweet potato, green beans
6. **Pre-Bed**: Casein shake (soy milk), banana

## Supplements

### Workout Days
- **Pre-workout (caffeine)**: 200-400mg 30-45 min before training
- **Whey protein**: 30-40g in pre-workout shake + 30-40g post-workout
- **Creatine monohydrate**: 5g daily (in pre-workout shake)
- **Fish oil**: 2-3g EPA/DHA daily
- **Multivitamin**: 1 serving daily

### Rest Days
- **Creatine monohydrate**: 5g daily with a meal
- **Fish oil**: 2-3g EPA/DHA daily
- **Multivitamin**: 1 serving daily

Vitamin D3 is covered by the multivitamin — no standalone supplement needed.

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
- **Week navigation** — 54 week buttons. Deload weeks are highlighted in orange.
- **Reset** — use the red reset button at the bottom to clear all progress.
- **Import/Export** — download and restore your progress as JSON files.

## Exercise Rotation

Each phase rotates exercises to prevent adaptation and target muscles from different angles:

**Push (Mon)**: Phase 1 — Barbell Bench, Incline Bench, DB Bench, Triceps Pushdown → Phase 2 — Incline Bench, DB Bench, Incline DB Bench, Skullcrushers → Phase 3 — DB Bench, Incline Bench, Barbell Bench, Triceps Pushdown → Phase 4 — Incline DB Bench, Barbell Bench, Incline Bench, Skullcrushers → Phase 5 — Barbell Bench, Incline Bench, DB Bench, Triceps Pushdown (Phase 1 return) → Phase 6 — Incline Bench, DB Bench, Incline DB Bench, Skullcrushers (Phase 2 return)

**Pull (Wed)**: Phase 1 — Deadlift, One-Arm DB Row, Lat Pulldown (Medium), Alt DB Curl → Phase 2 — Deadlift, Cable Row (Wide), Lat Pulldown (Close), Hammer Curl → Phase 3 — Deadlift, Barbell Row, Lat Pulldown (Medium), Alt DB Curl → Phase 4 — Deadlift, One-Arm DB Row, Lat Pulldown (Close), Hammer Curl → Phase 5 — Deadlift, Cable Row (Close-Grip), Lat Pulldown (Medium), Alt DB Curl → Phase 6 — Deadlift, Barbell Row, Lat Pulldown (Close), Hammer Curl

**Upper Body A (Thu)**: Phase 1 — Seated DB Press → Phase 2 — Seated Barbell OHP → Phase 3 — Standing Barbell OHP → Phase 4 — Arnold Press → Phase 5 — Seated Barbell OHP (Phase 1 return) → Phase 6 — Standing Barbell OHP (Phase 2 return)

**Legs (Fri)**: Phase 1 — Squat, Leg Curl, Leg Press, DB Lunges → Phase 2 — Squat, RDL, Front Squat, Bulgarian Split Squats → Phase 3 — Squat, Leg Curl, Leg Press, DB Lunges (Phase 1 same) → Phase 4 — Squat, RDL, Front Squat, Bulgarian Split Squats (Phase 2 same) → Phase 5 — Phase 1 pattern → Phase 6 — Phase 2 pattern

**Upper Body B (Sat)**: Phase 1 — Close-Grip Bench, Chin-ups, Cable Row (Close), Barbell Curl → Phase 2 — Dips, Pull-ups, One-Arm DB Row, EZ Bar Curl → Phase 3 — Close-Grip Bench, Chin-ups, Cable Row (Wide), Barbell Curl → Phase 4 — Dips, Pull-ups, Cable Row (Close), EZ Bar Curl → Phase 5 — Close-Grip Bench, Chin-ups, One-Arm DB Row, Barbell Curl → Phase 6 — Dips, Pull-ups, Cable Row (Wide), EZ Bar Curl

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
- **Exercise rotation**: Change primary exercises every phase (9 weeks)
- **Deload weeks**: Every 9th week — reduce volume, maintain form
- **3 minutes rest** between heavy sets, 2 for accessory
- **Proper warm-up**: 4 warm-up sets before first compound lift

## License

For personal use. The book content is copyright Michael Matthews. This is a distillation/tracker, not a replacement for the book.
