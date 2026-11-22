# MOMO LAMA - deploy to Vercel

Static site: no build step, no dependencies.

## Option A: Vercel CLI
1. Install Node.js, then in this folder run: `npx vercel`
2. Log in when asked, accept the defaults (framework "Other", no build command, output = this folder).
3. For the live URL run: `npx vercel --prod`

## Option B: GitHub + Vercel dashboard
1. Put this folder in a new GitHub repository (index.html at the top level).
2. On vercel.com choose Add New > Project, import the repository.
3. Framework preset "Other", leave Build Command and Output Directory empty, then Deploy.

## Editing later
- Menu items and prices: the `MENU` list in index.html (search for `var MENU`).
- Category photos: assets/images/food/menu/. Give one item its own photo with `img:"assets/images/food/menu/name.webp"`.
- Hero/section backgrounds: assets/images/backgrounds/ (set in `:root` as --hero-bg and --section-bg).
- Phone number: search 09954373334 in index.html.
