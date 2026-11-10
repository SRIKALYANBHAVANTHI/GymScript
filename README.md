# GymScript 🏋️

A lightweight workout-plan website built with HTML and Tailwind CSS. GymScript presents a weekly training split and provides separate pages for individual workout days.

## Overview

The home page displays a weekly Push / Pull / Legs + Abs schedule:

- **Sunday:** Legs, forearms, and abs
- **Monday:** Push — chest, shoulders, and triceps
- **Tuesday:** Pull — back and biceps
- **Wednesday:** Active recovery / abs

The homepage automatically highlights the scheduled workout for the current day (Sunday through Wednesday).

## Workout Pages

- [Legs](pages/legs.html)
- [Push](pages/push.html)
- [Pull](pages/pull.html)
- [Abs](pages/abs.html)

## Built With

- HTML5
- Tailwind CSS 2.2.19 (CDN)
- Vanilla JavaScript

## Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/SRIKALYANBHAVANTHI/GymScript.git
   ```
2. Open the project folder.
3. Open `index.html` in a web browser.

No build step is required. An internet connection is needed to load the Tailwind CSS stylesheet from its CDN.

## Project Structure

```text
GymScript/
├── index.html
└── pages/
    ├── abs.html
    ├── legs.html
    ├── pull.html
    └── push.html
```

## Notes

This repository contains a simple static website. Workout schedules and page content are defined in the HTML files.

---

Created by [Srikalyan Bhavanthi](https://github.com/SRIKALYANBHAVANTHI).
