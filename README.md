# 🏡 15 Greenleaf Ave — Countdown

A giant, cute, full-page countdown to **Thursday, September 17, 2026 at 12:00 PM** (Medford, MA time)
for 15 Greenleaf Ave, Medford, Massachusetts.

When the clock hits zero it throws a party: confetti, a rainbow banner, a hopping house and a wiggling title.

**Live:** https://ssalbdivad.github.io/greenleaf-countdown/

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole page — markup, styles, countdown and confetti, no dependencies |
| `house.svg` | Hand-drawn illustration of the house, used as the fallback image |

## Using a real photo

The page loads `house.jpg` first and falls back to `house.svg` if it isn't there.
Drop a photo named `house.jpg` next to `index.html`, commit, and it appears automatically.

## Previewing the finale

Add `?party` to the URL to trigger the celebration on demand:
https://ssalbdivad.github.io/greenleaf-countdown/?party

## Running locally

Just open `index.html` — or `python3 -m http.server` in this directory.
