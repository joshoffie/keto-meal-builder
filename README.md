# Keto Meal Builder

Mobile-first keto meal calculator for hitting daily/per-meal macro targets with a fixed keto-friendly food list (T1D-friendly, no rice).

**Live app:** https://joshoffie.github.io/keto-meal-builder/

## How it works

1. Set your per-meal targets (default: 90g protein, 85g fat, <15g net carbs, ~1,100 cal)
2. Pick 1 protein, 1–3 fats, optional carbs (fruit/veg)
3. The app calculates exactly how much of each to cook

Math approach:
- Scales protein portion to hit protein target
- Subtracts fat contribution from the protein
- Distributes remaining fat target evenly across selected fats
- Carbs stay at base serving size; warns if total carbs exceed target

## Food list

Proteins: ribeye, NY strip, ground beef 80/20, chicken thighs, rotisserie chicken, salmon, cod, shrimp

Fats: eggs, avocado, cheddar, mozzarella, butter, olive oil, mayo, cashews, almonds, peanut butter

Carbs: raspberries, blackberries, strawberries, spinach, broccoli, arugula

## Tech

Pure static HTML/CSS/JS. No build step. Hosted on GitHub Pages.
