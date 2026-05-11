# CS188 Final Review Notes (Lec 01–12)

Mobile-friendly review notes for UC Berkeley CS188 (Spring 2026) midterm-scope material:
Search · CSPs · Adversarial Games · MDPs · Reinforcement Learning.

Built from sp26 lecture slides 01–12, the official textbook (first half), and the past
five final-exam solution sets (sp24, sp25, fa24, fa25, su25). Every section also surfaces
the high-frequency exam patterns we found while reviewing the solutions.

## Deploy to GitHub Pages (so you can read on your phone)

One-time setup:

```bash
cd /Users/sylvia/Desktop/ucb/cs188/final/cs188-notes

# 1) Init repo
git init
git add .
git commit -m "CS188 review notes"
git branch -M main

# 2) Create a new repo on GitHub named e.g. `cs188-notes` (or anything),
#    then push:
git remote add origin git@github.com:<YOUR_USERNAME>/cs188-notes.git
git push -u origin main

# 3) On GitHub: Settings → Pages
#    Source: "Deploy from a branch"
#    Branch: main / (root)
#    Save.
```

In ~1 minute the page will be live at:

```
https://<YOUR_USERNAME>.github.io/cs188-notes/
```

Open it on your phone — it's fully responsive.

## To update later

```bash
# After editing index.html
git add index.html
git commit -m "update notes"
git push
# Page refreshes in ~30s
```

## Files

- `index.html` — the notes (self-contained, no JS/external CSS)
- `.nojekyll` — tells GitHub Pages to skip Jekyll processing
