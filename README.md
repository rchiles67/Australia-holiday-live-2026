# Australia-holiday-live-2026
active plan of SW WA holiday Oct-Nov 2026

A copy of the ChatGPT Site at https://chiles-wa-2026.rchiles.chatgpt.site/, so it can be edited for the rest of the trip.

## What's here

- `index.html`: the whole site in one file (HTML, CSS and a small script). Open it in any browser.

## What was copied (7 Nov 2026)

- Header, dates, intro line and stats (23 days, 18 touring nights)
- The six tab names
- Overview tab: route summary, route map, and the 16 overnight bases with dates
- Footer

The "route at a glance" paragraph is reworded from the original, not word-for-word.

The route map image is still loaded from the chatgpt.site address. If that site goes offline, save `maps/whole-trip-overview.png` into this repo and update the `<img>` path.

## Not copied yet

The other five tabs (Day planner, Beaches & tides, Where to sleep, Bookings, Tickets and Passes) couldn't be read from the original site. Each has an empty `<section>` in `index.html`, marked with a `<!-- ===== NAME (to be added) ===== -->` comment. Replace the `<div class="placeholder">` inside each with the content.

## Editing notes

- Tabs switch by the `data-tab` value on each button, matching the `id` of its `<section>`. A link to `index.html#bookings` opens that tab directly.
- Each overnight stop has `data-from` and `data-to` dates; the stop that covers today's Perth date is highlighted as "tonight".
- Colours and fonts are set as variables at the top of the `<style>` block, with a dark-mode version.
