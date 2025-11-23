# Ayurvedic Meal Planner

A simple web application that provides random daily meal suggestions following Ayurvedic sattvic principles.

## Features

- 40 days of balanced meal plans (breakfast, lunch, dinner)
- Random meal selection with a single click
- Clean, responsive interface
- Follows Ayurvedic principles:
  - Proper balance of augmenting and extractive foods
  - Sattvic ingredients only (no garlic, onion, tomato, etc.)
  - Seasonal vegetables and pantry staples

## Local Testing

To test locally:

```bash
cd ~/Projects/meal-planner
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

## Deploying to GitHub Pages

1. **Create a new GitHub repository:**
   - Go to https://github.com/new
   - Name it something like `meal-planner`
   - Don't initialize with README (we already have files)

2. **Initialize git and push:**
   ```bash
   cd ~/Projects/meal-planner
   git init
   git add .
   git commit -m "Initial commit: Ayurvedic meal planner"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/meal-planner.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
   - Your site will be published at: `https://YOUR-USERNAME.github.io/meal-planner/`

## Files

- `index.html` - Main web interface
- `meal-plans.json` - 40 days of meal plans
- `README.md` - This file

## Expanding the Meal Plans

Currently includes 40 days of meals. To add more days, edit `meal-plans.json` and add more entries following the same structure.

## Principles

All meals follow Ayurvedic sattvic principles:
- Each lunch/dinner includes: grain + legume/protein + augmenting vegetable + extractive vegetable + oils + spices
- Breakfasts are gentle and augmenting (porridge or sauteed fruit)
- No rajasic or tamasic foods (garlic, onion, bell pepper, tomato, eggplant, potato)
- Variety of grains, legumes, and seasonal vegetables
