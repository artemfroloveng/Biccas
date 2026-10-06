# Biccas

Static website. HTML + SCSS, no frameworks.

## Commands
- `npm run sass`: watch and compile SCSS while developing
- `npm run build`: compile minified CSS for production

## Structure
- `index.html`: main page
- `src/styles/styles.scss`: edit styles here
- `src/styles/styles.css`: generated. Never edit by hand.
- And I have fill out styles in folder styles, Fill them in when you layout.

## Rules
- Desktop-first: write base styles for Desktop, then use `min-width` media queries
- Class names use BEM (`block__element--modifier`)
- Don't use JS.I'm Layout only with Html, Scss.
- Run `npm run build` before saying a task is done.