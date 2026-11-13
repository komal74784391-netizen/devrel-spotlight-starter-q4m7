# Open Source Spotlight &mdash; gallery starter

This repository holds the source of the Open Source Spotlight gallery, a static
site served by GitHub Pages.

## Publishing a curation round

1. Rename this repository to `spotlight-gallery-<round-code>`. The round code is
   given in the curation round kickoff note in the team mailbox. Do not create a
   separate repository for a round; rename this one so the site history stays
   together.
2. Append one entry per accepted project to `_data/spotlights.yml`, keeping the
   existing entries.
3. Update `_config.yml` for this repository's address. GitHub Pages serves the
   gallery as a project site under the account's Pages domain, not at the
   domain root.
4. Push the changes to `main`; the Pages workflow publishes the site.

## Layout

- `_config.yml` &mdash; site configuration
- `_data/spotlights.yml` &mdash; gallery entries
- `index.html` &mdash; gallery page
- `assets/css/style.css` &mdash; stylesheet
