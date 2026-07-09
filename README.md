# Focus Trace

A single-file, offline web tool for planning your week, tracing where your time and focus actually go, and keeping an eye on sleep and exercise. Everything lives in one `focus_trace.html` file — no install, no account, no server. Open it in a browser to get started.

**[中文使用指南 → GUIDE.md](GUIDE.md)**

## What it does

- **Week setup** — plan the week in three areas (Research / Personal / Fun), and mark dated events: meetings, dinners, deadlines.
- **Daily todos & schedule** — break the week down into concrete daily items (e.g. *project A: design, experiments*) and timed appointments. One click turns a scheduled event into a time log entry.
- **Daily trace** — log each block of time with a 1–5 focus score in ~10 seconds. The dashboard shows tracked hours, hours by category, and a focus-by-hour heat strip so you can find your focus peaks.
- **Sleep & exercise check-in** — bed time + wake time (vs. an 8h goal) and an exercise checkbox (vs. a 3+ days/week goal, auto-detected from your logs when possible). Week health view shows the whole week at a glance.
- **AI review** — one button copies the whole week (plan, events, sessions, sleep, exercise) as a ready-made prompt for Claude/ChatGPT to analyze where your time went and what to change next week.

## Data and privacy

All raw data stays in your browser's local storage on the device you use — nothing is uploaded, there's no server. Use **Download XLSX** (Sessions, Week Setup, Daily Todos, Events, Check-ins sheets — readable by pandas/openpyxl) or **Export JSON** to back up or move your data. **Import backup** restores either format.

## Idea

The idea comes from the book [神・時間術](https://www.goodreads.com/zh/book/show/43482621) (The God of Time Management) by Kabasawa Shion: the first step to managing time and energy is learning your own distribution — where your time and attention actually go — then putting your most important work into your focus peaks, and protecting sleep and exercise as productivity, not rest.

## License

[MIT](LICENSE)
