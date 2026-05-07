# 💝 Our Love Story — Anniversary Game

A cozy Stardew Valley-style adventure game built with love.

## Files
- `index.html` — Main map/board
- `wordle.html` — Stop 1: Wordle (word: JAPAN)
- `connections.html` — Stop 2: Connections (4 personal categories)
- `strands.html` — Stop 3: Strands (why I love you words)
- `photomatch.html` — Stop 4: Photo matching game
- `mouserace.html` — Stop 5: Mouse racing game
- `finale.html` — Final love letter page

## How to Host on GitHub Pages

1. Create a new **public** GitHub repo (name it something cute like `our-adventure`)
2. Upload all HTML files to the repo root
3. Go to **Settings → Pages**
4. Under "Source" select **Deploy from a branch → main → / (root)**
5. Click Save — your site will be live at `https://yourusername.github.io/our-adventure`

## Customizing Photos (photomatch.html)

To swap in real photos:
1. Upload your photos to the repo (e.g. `/photos/japan.jpg`)
2. In `photomatch.html`, find the `PAIRS` array
3. Replace the `.bg` gradient with an `img` tag in the `.photo-placeholder` div

## Personalizing Further

- Edit the love letter in `finale.html` → `.letter-body` section
- Change the opening message in `index.html` → `.intro-card`
- Update Wordle word in `wordle.html` → `const WORD = 'JAPAN'`
