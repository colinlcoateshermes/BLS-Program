# Bigger Leaner Stronger — 12-Week Program

A mobile-friendly, day-by-day workout tracker based on Michael Matthews' *Bigger Leaner Stronger: The Simple Science of Building the Ultimate Male Body*.

Access it on your phone, check off exercises/meals/supplements each day, and your progress persists in your browser (localStorage).

## Quick Start

### Option 1: GitHub Pages (recommended)

1. Create a new repo on GitHub (e.g. `bls-program`)
2. Clone it locally, then copy these files into it:
   ```
   git clone git@github.com:YOUR_USER/bls-program.git
   cd bls-program
   # Copy the bls-program/ folder contents here
   cp -r /path/to/bls-program/* .
   ```
3. Push to GitHub:
   ```
   git add .
   git commit -m "Initial commit"
   git push
   ```
4. Enable GitHub Pages:
   - Go to Settings > Pages
   - Source: **Deploy from a branch**
   - Branch: `main`, folder: `/ (root)`
   - Click Save
5. Wait ~1 minute, then visit `https://YOUR_USER.github.io/bls-program/`
6. Open that URL on your phone — it's mobile-responsive.

### Option 2: Local file (no server)

Open `index.html` directly in your browser. localStorage persistence still works.

## How To Use

### Weekly Schedule

| Day | Workout | Phase 1 (Weeks 1-8) | Phase 2 (Weeks 9-12) |
|-----|---------|---------------------|---------------------|
| **Monday** | Chest & Calves | Heavy 4-6 reps | Add Dips, slight variation |
| **Tuesday** | **REST** | Off | Off |
| **Wednesday** | Back & Abs | Deadlift + rows + abs circuit | Same, heavier |
| **Thursday** | Shoulders & Calves | Military press + raises | Same |
| **Friday** | Upper Body & Abs | Higher-rep chest + arms + abs | Rotation of ab exercises |
| **Saturday** | Legs & Shoulders | Squat + leg press + RDL + calf work | Calf exercise rotation |
| **Sunday** | **REST / Active Recovery** | Off | Off |

### Each Day Shows

- **Exercises** with sets, reps, rest times, and warm-up protocols
- **Nutrition** with dairy-free meal template and macronutrient targets (bulking: 1g protein, 2g carbs, 0.4g fat per lb bodyweight)
- **Supplements** checklist

### Features

- **Check-off persistence** — tap any circle to mark it complete. Taps are saved automatically to your browser (localStorage).
- **Exercise descriptions** — tap "Show description" on any exercise for a full how-to, including links to relevant book screenshots.
- **Image viewer** — tapping a screenshot link opens it full-screen. Tap again to close.
- **Progress stats** — completion percentage, total checkmarks, and weekly streak counter.
- **Week navigation** — jump between weeks. A week button shows green border when all 7 days are marked complete.
- **Reset** — use the red reset button at the bottom to clear all progress.

### Nutrition Notes

This program uses **bulking macros** by default:
- **Protein**: 1g per lb of bodyweight
- **Carbs**: 2g per lb of bodyweight
- **Fat**: 0.4g per lb of bodyweight

**No dairy**: All meal templates are dairy-free. Use whey protein isolate (low lactose), plant-based proteins, nut milks, and coconut/olive oil instead of butter.

To adjust bodyweight, open browser DevTools and run:
```js
let p = JSON.parse(localStorage.getItem("bls_progress"));
p.bw = 200; // your weight in lbs
localStorage.setItem("bls_progress", JSON.stringify(p));
location.reload();
```

Or simply edit the `USER_BW = 180` variable at the top of the `<script>` section in `index.html`.

### If You're Cutting Instead

Replace macros with:
- **Protein**: 1.2g per lb bodyweight
- **Carbs**: 1g per lb bodyweight
- **Fat**: 0.2g per lb bodyweight

### Cardio

Add cardio on rest days or after lifting as needed:
- **LISS**: 30-45 min walking
- **HIIT**: 15-20 min sprints (bike/sprints)
- Frequency: 2-4 sessions per week during cutting, 0-2 during bulking

## File Structure

```
bls-program/
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

This program is distilled from **Bigger Leaner Stronger: The Simple Science of Building the Ultimate Male Body** by Michael Matthews (Second Edition).

Core principles extracted:
- **4-6 rep range** for working sets at 80-85% of 1RM
- **Compound lifts first**: Squat, Deadlift, Bench Press, Military Press
- **Progressive overload**: Add weight or reps every session
- **1-2 muscle groups per workout**, 45-60 minutes
- **3 minutes rest** between heavy sets, 1-2 for accessory
- **Proper warm-up**: 4 warm-up sets before first lift
- **Change accessories every 8-10 weeks**

## License

For personal use. The book content is copyright Michael Matthews. This is a distillation/tracker, not a replacement for the book.