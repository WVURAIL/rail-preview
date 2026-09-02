# rail-preview

Staging copy of the lab website's `wvu` branch (the WVU Design System build),
published at <https://wvurail.org/rail-preview/> for the Strategic
Communications review. Not the real site, and not indexed: every page carries
`noindex`.

There is no content here. The one workflow in `.github/workflows/` checks out
[`WVURAIL/wvurail.github.io@wvu`](https://github.com/WVURAIL/wvurail.github.io/tree/wvu),
builds it under `/rail-preview/` with the same gems GitHub Pages uses, and
deploys the result. It runs every half hour and on demand (Actions → *Stage
the wvu branch* → *Run workflow*).

When the branch has been merged and the site is live on rail.wvu.edu, delete
this repository.
