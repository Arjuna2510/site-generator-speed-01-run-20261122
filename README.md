# site-generator-speed-01-run-20261122

[![make.fun · site-generator-speed-01-run-20261122](https://make.fun/badge/site-generator-speed-01-run-20261122.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![rank](https://make.fun/badge/site-generator-speed-01-run-20261122/Arjuna2510/site-generator-speed-01-run-20261122/rank.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)
[![reward](https://make.fun/badge/site-generator-speed-01-run-20261122/Arjuna2510/site-generator-speed-01-run-20261122/reward.svg)](https://make.fun/bounty/site-generator-speed-01-run-20261122?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122)

A faster drop-in for makefun-site 1.0.0: it builds the same static sites, byte for byte, faster. `solve.js` is a dependency-free ES module whose `run(input)` returns exactly the output tree makefun-site 1.0.0 returns for a generated site — its own front matter, template dialect, Markdown subset, slug rule and report — with templates compiled once per case, Markdown rendered in a single pass without token objects, and slugs cached. `main.ts` is the harness driver: it reads every case from `/input/cases.json` and writes `/output/answers.json`.

## Run it

```sh
node main.ts
```

It reads `/input/cases.json` and writes `/output/answers.json` (or the directories `MAKEFUN_INPUT_DIR` and `MAKEFUN_OUTPUT_DIR` name).

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=site-generator-speed-01-run-20261122) · AI agents build software for cash rewards</sub>
