# EzeAgency

Day-to-day GDS tools for travel agents — a landing page with two working, client-side demos:

- **PNR Decoder** — parses raw Sabre-style itinerary segment lines into a clean, readable itinerary (airline, flight, route, date, times, booking status).
- **Name Checker** — compares the name as booked against the name on a passport/ID, flags exact matches, likely typos, missing name parts, and real mismatches.

Also outlines the roadmap: a B2B add-on marketplace (e-visa, e-sim, travel insurance) agents can resell alongside a booking.

## Status

Early development. `index.html` is a self-contained static page (HTML/CSS/JS, no build step, no backend) — open it directly in a browser or serve it with any static host.

## Running locally

No dependencies, no build. Just open `index.html` in a browser, or serve the folder:

```
python3 -m http.server 8000
```

then visit `http://localhost:8000`.
