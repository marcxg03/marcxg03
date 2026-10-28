# Marcus Gao

> Quantitative psychology researcher who builds the systems research runs on. I work in R and Python (causal inference, psychometrics, factor analysis), build LLM/NLP classification pipelines, and run the AI-agent workflows behind the Oishi Lab at the University of Chicago, where I'm the lab manager. M.A. in the Social Sciences (Psychology) at UChicago, expected June 2027; B.A. in Economics & Psychology, UChicago 2026.

## Research engineering

- **Oishi Lab agent fleet** *(private, lab-internal)*: 11 scheduled agents that run the lab's operations. They turn the weekly Zoom meeting into a transcript, a recap and action items in Drive and Slack; keep a running Google Doc ledger and Slack canvas for each project; propose presenter schedules and roster changes for my approval; and check their own health every week. Python on launchd, built on Slack, Google Drive/Docs/Sheets, Zoom and Claude.
- **Housing-assistance classifier** *(private, unpublished; Russell Sage Foundation–funded study)*: a Claude-based classifier that reads a Redditor's full post history and labels whether they obtained or sought subsidized rental housing, against a 17-rule construct codebook. Pure-function pipeline, reproducibility-tested, checked against a 192-case hand-coded blind validation set. It feeds a staggered difference-in-differences / event-study design.
- **[study-abroad-control-scraper](https://github.com/marcxg03/study-abroad-control-scraper)**: Streamlit + ArcticShift tool that built a control corpus of about 1,200 Reddit users and 1M posts and comments.
- **[bot-detector](https://github.com/marcxg03/bot-detector)**: screens open-ended survey responses for LLM-written or low-quality submissions.
- **[web_scraper](https://github.com/marcxg03/web_scraper)**: Claude-powered extraction of narrative passages from Reddit and the web.
- **[epiphany_scraper](https://github.com/marcxg03/epiphany_scraper)**: narrative example-bank retrieval for my first-author project on epiphanies in life stories (poster, UChicago Undergraduate Research Symposium, 2026).
- **Multilingual survey preprocessing** *(private, handed off)*: turned four multilingual survey datasets into one analysis-ready corpus of about 9,000 responses, using LLM translation and reference-free quality estimation.

Full list with status and access: **[research](https://github.com/marcxg03/research)**.

## Apps

- **[training-app](https://github.com/marcxg03/training-app)**: mobile-first PWA that runs my training methodology (block + bank lifting, schedule-anchored nutrition, append-only PR history, hand-rolled SVG analytics). Next.js + Supabase, live on Vercel. A v2 in Expo is in progress.
- **[persona-forge](https://github.com/marcxg03/persona-forge)**: turns a YouTuber into a Claude persona you can talk to. Apify scrape → Claude distill (Haiku video cards → Opus synthesis) → monthly refresh → chat over a filesystem MCP.

## How I build

I work with Claude Code through a set of skills I wrote (private for now): a sliced build loop with tests and adversarial review at every slice, debugging and verification loops, and tutors that make me learn the code I ship.

## Reach me

gaomx9@gmail.com · [LinkedIn](https://www.linkedin.com/in/marcusgao)
