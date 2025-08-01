# CG Calculator

A simple, modern CGPA calculator for BRAC University (BRACU) students. Calculate your updated CGPA based on your current CGPA, completed credits, and this semester's courses. Works offline as a Progressive Web App (PWA).

## Features

- Clean, responsive UI
- Real-time input validation
- Supports up to 10 courses per semester
- Editable course credits (default: 3)
- Grade selection with BRACU grading scale
- Instant calculation with rounding logic
- Offline support (PWA)
- Caches your last input for convenience

## Usage

1. Enter your current CGPA and completed credits (optional).
2. Enter the number of courses for this semester.
3. Click **Generate** to create input fields for each course.
4. Enter the credits and select the grade for each course.
5. Click **Calculate** to see your new CGPA.

## Development

- All logic is in [`script.js`](script.js)
- Styles are in [`style.css`](style.css)
- Service worker for offline support: [`service-worker.js`](service-worker.js)
- Manifest for PWA: [`manifest.json`](manifest.json)
- Static site, ready for GitHub Pages deployment

## Deployment

This project is set up for deployment to GitHub Pages using the workflow in [`.github/workflows/static.yml`](.github/workflows/static.yml).

## License

MIT License

---

Made for
