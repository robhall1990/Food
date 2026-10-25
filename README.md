# 🍽️ Mealio — Family Dinner Planner

A family-first dinner planner: easy meal planning for **two grown-ups,
a 4-year-old, and a 2-year-old**. (Formerly known as Herbi.)

It's a self-contained web app — no build step, no backend, no accounts — and
it's installable on your phone as a PWA, working offline once it's loaded.

## Run it

Open `index.html` in any browser. That's it.

Hosted on GitHub Pages (Settings → Pages → deploy from `main`), it's live at
a URL you can open on your phone. From there:

- **iPhone (Safari):** Share icon → "Add to Home Screen"
- **Android (Chrome):** ⋮ menu → "Install app" (or "Add to Home screen")

It'll then open full-screen like a native app, with its own icon, and keep
working even with a shaky supermarket signal.

## What it does

**📦 A HelloFresh-style weekly box** — "Get my picks" fills a box of meals
(5 by default, use the +/− control to go from 3 to 8) with suggestions that:

- Favour kid-approved meals and your favourites
- Vary the cuisine from one card to the next
- Avoid repeating last week's dinners
- Lean slightly toward quicker meals (≤25 min)

Don't like a suggestion? Tap 🔀 to shuffle just that one card, or 🔒 to lock a
card you love before hitting "Get my picks" again to reshuffle the rest. Add
or remove meals from the box any time, and optionally tag a card with "Cook
on: Tuesday" — purely a label, nothing is scheduled rigidly by day.

**👶 "For the little ones" notes** — every recipe includes serving guidance for
a 4-year-old and a 2-year-old: choking-hazard cuts (halved cherry tomatoes,
half-moon sausage slices, no whole nuts), deconstructed serving ideas for picky
phases, salt awareness, and cooling tips.

**💚 Kid-approval tracker** — after dinner, tap whether each kid ate it. The
planner learns and leans toward proven winners on tired weeknights.

**🛒 Auto shopping list** — every ingredient for the meals in your box, summed
across recipes, grouped by supermarket section, and **scaled to your family**
(2 adults + 0.5 + 0.3 child portions = 2.8×). Tap items off as you shop,
copy the list as text, or print it. Tap a family member's name in the header
to exclude them (date night, kid at grandma's) and portions rescale.

**🍲 71 dinners built in** — 50 veggie, 17 meat and 4 fish, searchable and
filterable (veggie / meat & fish / quick / kid-approved / batch-and-freeze /
fun night / my recipes), each with kid-friendliness ratings.

**👨‍🍳 Full cooking methods** — every recipe has numbered step-by-step
instructions alongside its scaled ingredients, written for real weeknights
(what to get on first, when to blitz for the toddler, food-safety checks for
meat and fish).

**✏️ Your own recipes** — add family favourites with the built-in editor
(name, cook time, veggie/meat/fish type, kid rating, tags, little-ones notes,
method steps, and ingredients with aisle categories). Custom recipes join the
box's suggestion pool and the shopping list automatically, and can be edited
or deleted any time.

**➕ Shopping extras** — add anything else you need (milk, bananas, snacks)
to the bottom of the shopping list.

**💾 Backup & restore** — export everything (plan, custom recipes, approvals,
favourites) as a JSON file and import it on another device or browser.

Everything is saved in your browser (localStorage), so the plan, ticked-off
shopping items, favourites and kid approvals survive between visits.
