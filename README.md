# Sweat Pact

A two-person workout accountability tracker: animated characters, weekly goals, streaks, notes, and a loser's dare deck.

- Static site, no build step. GitHub Pages serves the repo root.
- Data lives in Supabase (tables `sweatpact_pacts` / `sweatpact_docs`), reached only through the `sweatpact_get` / `sweatpact_put` functions.
- Access is by invite link: `https://thimith.github.io/sweat-pact/#<pact-code>`. The pact code is never committed here.
