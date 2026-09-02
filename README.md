# 🏡 15 Greenleaf Ave — Countdown

A giant, cute, full-page countdown to **Thursday, September 17, 2026 at 12:00 PM** (Medford, MA time)
for 15 Greenleaf Ave, Medford, Massachusetts.

The countdown is one giant number of seconds, with the days / hours / minutes / seconds
breakdown small underneath. When it hits zero the page throws a party: confetti, a rainbow
banner, a hopping house and a wiggling title.

**Live:** https://ssalbdivad.github.io/greenleaf-countdown/

## Files

| File | What it is |
| --- | --- |
| `index.html` | The whole page — markup, styles, countdown and confetti, no dependencies |
| `house.jpg` | Photo of the house (MLS #73553230 listing photo) |
| `house.svg` | Hand-drawn illustration of the house, used if `house.jpg` is missing |

## Swapping the photo

The page loads `house.jpg` and falls back to `house.svg` if it's missing.
Replace `house.jpg` with any other photo and it appears automatically — no code change.

## Previewing the finale

Add `?party` to the URL to trigger the celebration on demand:
https://ssalbdivad.github.io/greenleaf-countdown/?party

## Running locally

Just open `index.html` — or `python3 -m http.server` in this directory.
