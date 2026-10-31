# What We Know

An interactive prototype exploring how colleagues discover and apply one another’s experiences during everyday work.

## Run locally

No installation or build is required. Serve the `dist` folder with any static web server, for example:

```sh
python3 -m http.server 4173 --directory dist
```

Open http://localhost:4173.

## Refined challenge flow

The first conversation is Alex’s laboratory-navigation challenge. Maya can post a saved draft by name or anonymously, continue through a prepared owner follow-up, accept collaboration without revealing identity, and optionally identify herself after confirmation. The owner update links to a revised interactive navigation comparison.

See [the demo walkthrough](docs/demo-walkthrough.md) for the recording route, state behavior and implementation limits. Open `/demo.html` to reset only the laboratory case before rehearsing.

Anonymity and collaboration are browser-local simulations. Prepared follow-up stages do not interpret or respond to arbitrary visitor input.

## Prototype features

- Open a work-in-progress conversation with context and review materials
- Review fictional portal pages and draft/revised research tasks
- Reply across teams and connect previous experiences
- Start a new conversation with a clear request for input
- Follow an illustrative author update showing what changed


- Search and filter team experiences
- Read context, interpretation, and limitations
- Save experiences for later
- Connect an experience to the current project with a reflection
- Add a perspective and explore colleague profiles

All people, company details, and study results are fictional. Contributions, saved items, and project notes are stored only in the visitor’s browser using localStorage. There is no backend, messaging, or real company integration.

## Files

- `dist/index.html` — application shell
- `dist/style.css` — responsive interface
- `dist/app.js` — shared experience content and interactions
- `dist/conversations.js` — open conversations, discussion, and review materials
- `dist/conversations.css` — conversation and challenge layouts
- `dist/challenges.js` — laboratory case, participation choices, reveal confirmation and revised prototype
- `dist/demo.html` — scoped rehearsal reset, separate from the workspace
- `.openai/hosting.json` — existing private Sites deployment identity

The interface loads DM Sans and Manrope from Google Fonts, with system-font fallbacks.
