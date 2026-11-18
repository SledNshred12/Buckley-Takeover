# Buckley Takeover

Take over Buckley, WA one building at a time. A GPS map game where you capture real places, battle rival crews, and race to own the whole town.

Play: https://buckley-takeover.pages.dev (deployed to Cloudflare Pages by .github/workflows/deploy.yml)

Map data © OpenStreetMap contributors, tiles © CARTO.

## Multiplayer

Online play runs on Supabase (project "Buckley Takeover"). All game rules (income, battles, seasons) run on the server in Postgres functions; the page only calls them. Player locations never leave the device.
