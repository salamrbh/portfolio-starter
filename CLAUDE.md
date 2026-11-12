# CLAUDE.md

This is a beginner's portfolio website built with Astro and plain CSS. No UI library.

## Rules

1. Read everything in `/content` and `/references` before you design anything.
2. Make one change at a time.
3. Check every change in the browser before you move on.
4. Commit after every working step.
5. No third party fonts or trackers. Fonts live in `/public/fonts`, nothing loads from other servers.
6. Write all site text in English.

## Project map

- `src/pages/index.astro`: the page
- `src/layouts/Layout.astro`: the HTML frame around the page
- `src/styles/global.css`: all styles and the local font setup
- `content/about.md`: the trainee's answers about themselves
- `references/`: inspiration screenshots
- `public/images/`: photos for the site
- `public/fonts/`: local font files

## Commands

- `npm install`: install
- `npm start`: start the dev server and open the browser at http://localhost:4321
- `npm run build`: build the site into `dist/`
