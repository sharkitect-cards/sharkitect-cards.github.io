# sharkitect-cards.github.io

Landing page for the Sharkitect Cards org. Serves at https://cards.sharkitectdigital.com

## What this is

The organization-level GitHub Pages repo. It does two jobs:

1. Serves the branded landing page at the apex of `cards.sharkitectdigital.com`.
2. Holds the `CNAME` file that anchors the custom domain — every other repo in the `sharkitect-cards` org with Pages enabled automatically serves at `cards.sharkitectdigital.com/{repo-name}/`.

## Do not delete the CNAME file

It is what routes the custom domain at the org level. Every other card repo depends on this.

## Adding new client cards

Don't edit this repo to add cards — each client card is its own repo, spawned from `_template`. See the `_template` repo in this org for the pattern.
