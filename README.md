# Happy Men's Day Card

A cute, interactive Men's Day card (19 November) - one HTML page, no build step.

**Features:** compliment machine, swipe cards, sticky notes, photo scrapbook, mini games, badges.

**Run:** open `mens-day.html`, or `python -m http.server 8000` and visit `http://localhost:8000/mens-day.html`.

**Owner mode:** the card is view-only for everyone by default. To edit (add photos, notes, name), triple-tap the "19 November - Men's Day" badge, enter the PIN set in `OWNER_PIN` (top of `mens-day.js`), then triple-tap again to re-lock. Share with `?view=1`; jump to a section with `?tab=p-photos` (or `p-cards`, `p-notes`, `p-games`).

**Files:** `mens-day.html` (markup), `mens-day.css` (theme and animations), `mens-day.js` (content, photos, games, permissions).

**Note:** the default photos are embedded as base64 in `mens-day.js`, so keep the repo private unless you want them public.
