# Ms Meal

Your meal, water, and gym buddy. A single-page meal and gym planner for people building strength on a budget. It plans meals from what's already in your kitchen, tracks protein and water, and logs workouts — all in one HTML file with no build step and no backend.

## Features

- **Today dashboard** — protein planned today, water intake, gym sessions this week, today's meals and workout, and what to buy.
- **Profile-based targets** — enter weight, height, age, sex, and gym days per week to get:
  - Protein: 1.6–2.0 g per kg body weight
  - Water: ~35 ml per kg (+500 ml on gym days)
  - Calories: Mifflin-St Jeor maintenance estimate, adjusted for training frequency
  - BMI with WHO and Asian cut-off context
- **Pantry** — tick what you have, add your own items. Recipes show "Ready to cook" or what's missing.
- **18 budget recipes** — avoid chicken, egg, shellfish, and fish. Ingredients that may hide allergens are flagged ⚑.
- **Week plan** — breakfast, lunch, snack, and dinner for 7 days, with daily protein totals and one-tap auto-fill.
- **Shopping list** — built automatically from planned meals and missing pantry items.
- **Gym log** — beginner A/B/C full-body routine, per-set weight and reps, "last time" hints, strength progress, weekly streaks, and CSV export.
- **Ask Ms Meal** — an AI chat that knows your pantry, plan, targets, and gym log (available when opened as a Claude artifact).

## Run it

Open `index.html` in any browser, or publish it with GitHub Pages:

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under **Source**, choose **Deploy from a branch**, select `main` and `/ (root)`, then **Save**.
4. Your site will be at https://lykabuilds.github.io/ms.meal/.

## Data and privacy

All data (profile, pantry, plan, water, gym log) is stored in your browser's `localStorage`. Nothing is sent to a server. Clearing site data or switching browsers or devices starts fresh, so use **Download log (CSV)** to back up your workouts.

## Notes

- The Ask Ms Meal assistant uses the Claude artifact runtime and is hidden when the page runs elsewhere, such as GitHub Pages.
- Exercise and recipe "↗" links open YouTube or image search in a new tab.
- Nutrition values are estimates per serving. This is not medical or dietary advice; check with a professional for allergies or health conditions.

## Tech

Plain HTML, CSS, and JavaScript in one file. Fonts from Google Fonts. Light and dark themes follow your system setting.
