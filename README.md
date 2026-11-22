# sterdoc-articles

Article feed for the Sterdoc website (https://new.sterdoc.nl/articles/).

- `AGENT.md` — the instructions the Sterdoc article agent follows every run (every two days).
- `feed.json` — the newest articles in seven languages; the website imports new ones every hour.
- `topics.md` — every topic written so far, so topics are not repeated.

To stop an article from appearing, remove it from `feed.json` before the site imports it; an article that is already on the site is deleted in WordPress (Posts).
