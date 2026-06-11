# ocean-asset

Serving repo for the animated ocean SVG on [JainAlber/jainalber](https://github.com/JainAlber/jainalber).

GitHub strips CSS animation from SVGs it serves itself, so the
[ocean-sync](https://github.com/JainAlber/jainalber/blob/main/.github/workflows/ocean-sync.yml)
workflow pushes the freshly generated `ocean.svg` here, Vercel auto-deploys on
every push, and the profile README embeds the Vercel URL — animations intact.

Nothing in this repo is edited by hand.
