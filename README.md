# FYS Labs Toolbox

**Open the toolbox: https://rbrn-xi.github.io/fys-labs-toolbox/**

A single-page site with two views, behind one toggle:

- **Meet Claude:** tools for getting more out of Claude, explained in plain words, plus a beginner guide: why Claude, Claude chat versus Claude Code, and setup from a free account to a first working job.
- **Meet Muse:** the connectors Muse can connect to, what each service is, what Muse can do with it, and why it would be useful, with use cases from everyday life to running a business.

## Run it

No build step. Open `index.html` in a browser, or use the link above.

The page is self-contained: the FYS logo is inlined, so there are no separate asset files to keep in sync. The link above is served by GitHub Pages from the `main` branch, so it updates a minute or two after each push.

## Polish notes for Claude Code

- Keep the copy in plain words a first-timer can understand. Explain jargon the first time it appears, or remove it.
- Keep the FYS logo to once only, in the masthead.
- Do not mention a total tool count or a total connector count anywhere on the page.
- Keep working: the Claude / Muse toggle, search, group filters, sort, the Start Here toggle, card-jump links, and every Copy button.
- Before calling a polish done, check the page at desktop, tablet, and phone sizes, and check that search, filters, sort, and copy still work on both views.
- Nothing on the page claims a connector is already connected. Connecting a service is a separate step the user does themselves.
- The design rules live in the DESIGN-LOCK comment at the top of the stylesheet in `index.html`.
