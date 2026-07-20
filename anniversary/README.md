# ❤️ 3-Year Anniversary Website

A romantic two-page website for your 3-year anniversary:

**Page 1 — `index.html` (the question 💌):** asks her to be your girlfriend
again. The "No" button runs away when she tries to press it, and saying Yes
sets off a heart explosion and leads to page 2. Edit her name and the teasing
"No" button texts in the `ASK` block at the top of the script.

**Page 2 — `anniversary.html` (the anniversary 💘):**

- 💌 A hero screen with your names and a beating heart
- ⏱️ A live counter of days / hours / minutes / seconds together
- ✍️ A love letter section
- 📜 A timeline of your story
- 📸 A photo gallery with a fullscreen lightbox — photos load **automatically**

## 1. Make it personal (5 minutes)

Open `anniversary.html` and find the `CONFIG` block near the top of the `<script>`
section — it's clearly marked with **"💗 EDIT THIS PART"**. Change:

- `names` — your two names
- `anniversaryDate` — the date you got together (**note: month is 1–12**)
- `letter` — your own message to her (each string = one paragraph)
- `milestones` — your real story moments
- `tagline`, `signature`, `footer`

That's the only place you ever need to edit. Everything else updates itself.

## 2. Add photos — without using any AI credits

Just put image files in the `photos/` folder — the gallery finds them
automatically. On github.com: open `anniversary/photos/` → **Add file →
Upload files** → drag in your pictures → commit. Done.

See `photos/README.md` for details (ordering, local viewing, resizing tips).

## 3. Put it online for free (GitHub Pages)

1. On github.com, open the repository → **Settings** → **Pages**
2. Under *Source*, choose **Deploy from a branch**, branch `main`, folder `/ (root)`
3. Save, wait a minute or two
4. Your site is live at:
   `https://<your-username>.github.io/<repo-name>/anniversary/`

Every time you upload new photos or edit the CONFIG, the live site updates
automatically within a minute or two.
