# PokerBasics

A 30-minute beginner poker lesson for No Limit Texas Hold'em. Covers rules, game flow, and the combinatorial math behind hand rankings. Built for Columbia Business School.

## Files

| File | What it is |
|------|------------|
| `slides.html` | reveal.js slide deck (25 slides) |
| `speaker-notes.md` | Per-slide script with timing cues and audience Q&A |

## How to present

1. Open `slides.html` in Chrome or Firefox
2. Press **F** for fullscreen
3. Press **S** for speaker view (notes + timer + next slide)
4. Arrow keys or spacebar to advance
5. Some slides have fragment reveals (click multiple times)

## Lesson flow (30 min)

| Time | Section | Slides |
|------|---------|--------|
| 0:00-2:30 | Goal, card setup | 1-3 |
| 2:30-6:30 | The deck, hand rankings | 4-6 |
| 6:30-10:00 | The math (7C5, probabilities, 5-of-7 example) | 7-9 |
| 10:00-14:00 | Table, dealer button, blinds, rotation, actions | 10-14 |
| 14:00-22:00 | Full hand walkthrough (preflop through showdown) | 15-20 |
| 22:00-28:30 | Practice hands + odds context | 21-24 |
| 28:30-30:00 | Recap + cheat sheet | 25-26 |

## No build step

Single HTML file. Loads reveal.js + Inter font from CDNs. No npm, no images, no dependencies to install. All card visuals are CSS + Unicode.

For offline use, download [reveal.js](https://revealjs.com/) and swap the CDN links to local paths.
