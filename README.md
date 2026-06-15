# Manuel's Training App 2026

A culinary training web app for recipes and plate presentations.

## Live Site

Hosted on GitHub Pages: `https://mrsalazaraz.github.io/manuelstraining`

## How to add recipes

Edit `recipes.json` and add a new entry following this structure:

```json
{
  "id": 5,
  "name": "Dish Name",
  "category": "Beef",
  "difficulty": "Beginner | Intermediate | Advanced",
  "prepTime": "10 min",
  "cookTime": "20 min",
  "servings": 2,
  "image": "",
  "description": "Short description.",
  "ingredients": ["item 1", "item 2"],
  "steps": ["Step 1", "Step 2"],
  "plating": {
    "description": "How to plate the dish.",
    "tips": ["Tip 1", "Tip 2"]
  },
  "tags": ["beef", "quick"]
}
```

## Deploying to GitHub Pages

1. Push all files to `main` branch
2. Go to repo **Settings → Pages**
3. Set source to **Deploy from branch → main → / (root)**
4. Site will be live at `https://mrsalazaraz.github.io/manuelstraining`
