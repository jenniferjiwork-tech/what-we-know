# What We Know

An interactive prototype exploring how colleagues discover and apply one another’s experiences during everyday work.

## Run locally

No installation or build is required. Serve the `dist` folder with any static web server, for example:

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173.

## Prototype features

- Search and filter team experiences
- Read context, interpretation, and limitations
- Save experiences for later
- Connect an experience to the current project with a reflection
- Add a perspective and explore colleague profiles

All people, company details, and study results are fictional. Contributions, saved items, and project notes are stored only in the visitor’s browser using localStorage. There is no backend, messaging, or real company integration.

## Files

- `dist/index.html` — application shell
- `dist/style.css` — responsive interface
- `dist/app.js` — fictional content and interactions
- `.openai/hosting.json` — existing private Sites deployment identity

The interface loads DM Sans and Manrope from Google Fonts, with system-font fallbacks.
