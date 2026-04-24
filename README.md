# NO COINCIDENCE — Blog

A two-part blog series exploring the transformation of Formula 1 fandom, built for MKT 447.

## Files

- `index.html` — Homepage with featured articles
- `episode-1.html` — "What Changed in F1"
- `episode-2.html` — "Where F1 Goes From Here"
- `styles.css` — All styling

## Viewing locally

Just double-click `index.html` — it opens in any browser, no setup needed.

Or run a local server:
```
cd blog
python3 -m http.server 8000
```
Then open http://localhost:8000

## Publishing online (for free)

### Option 1: Netlify Drop (fastest, ~1 minute)
1. Go to https://app.netlify.com/drop
2. Drag the `blog` folder onto the page
3. Done — you get a live URL instantly

### Option 2: GitHub Pages
1. Create a new GitHub repo
2. Upload all files to it
3. Settings → Pages → Deploy from main branch
4. Your site goes live at `username.github.io/reponame`

### Option 3: Vercel
1. Go to https://vercel.com
2. Import the folder — deploys automatically

## What to change before submitting

- Update the author name in the footer (currently "Antonia")
- Add your real social links in the footer (currently `#` placeholders)
- If your prof wants a URL, use the Netlify Drop option — takes literally 60 seconds

## Customization

All the colors live at the top of `styles.css` as CSS variables:
- `--paper` (cream background)
- `--ink` (dark text/accents)
- `--accent` (the red)
- `--highlight` (the yellow)

Change those values and the whole site re-themes.
