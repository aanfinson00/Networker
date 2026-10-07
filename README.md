# Networker

A personal relationship tracker for learning the real estate business from every seat: lenders, brokers, developers, lawyers, other asset managers and recruiters. A promotion track is kept in the background.

The app is a single page, `tracker/index.html`, published as a private claude.ai Artifact. Data lives in the artifact's database, readable and writable only by its owner. Nothing personal is stored in this repo.

## What it does

- **This week**: conversations against a weekly target (1 internal + 2 external by default), a 10-week trend, who is overdue, what you owe people, and which parts of the market you've heard from this month.
- **People**: every contact with tier, function, internal/external side, promotion role (sponsor, decision-maker, calibration voice), notes and a log of each touch.
- **Triage**: sort imported LinkedIn connections into tiers. Inner circle = every 30 days, core = 90, wide = 180.
- **Learning**: questions you want answered in each part of the market. Lessons logged after each conversation can be filed under a question, building notes by topic.
- **Projects**: deals and decisions you want hands-on experience with, with the people helping on each.
- **Plan**: a quarterly learning plan (debt, leasing, development, transactions), with the promotion track one tap away.
- **Import & setup**: drop LinkedIn's `Connections.csv`. Functions (lenders, capital markets, investment sales, leasing, development, acquisitions, legal, AM, investors, recruiters, property ops) are auto-tagged from title and company. Re-importing only adds new people and refreshes titles.

## Getting Connections.csv

LinkedIn → Settings & Privacy → Data privacy → Get a copy of your data → "Want something in particular?" → tick **Connections** → request archive.
