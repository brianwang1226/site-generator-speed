[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/brianwang1226/site-generator-speed/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/brianwang1226/site-generator-speed/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

# site-generator-speed

A faster drop-in for makefun-site 1.0.0. `solve.js` returns exactly what
makefun-site's `build` returns for every case, byte for byte, in about half
the CPU time.

- Single-pass Markdown rendering (no token array).
- Batched HTML escaping (plain runs escaped once, not per character).
- Slugify cache for repeated titles and tags.

Built for the make.fun "Build a static site faster" bounty. Node 22 and its
standard library alone; there is no install step.
