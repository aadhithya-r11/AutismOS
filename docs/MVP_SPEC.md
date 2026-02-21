# AutismOS — MVP Spec (v0.1)

## Goal
Turn paper ABA daily sheets into a simple “personal analytics” dashboard:
weekly trends, progress streaks, and exportable summaries for parent + BCBA.

## MVP Scope
### Include
1) Add Daily Log (manual entry)
2) Trends (weekly/monthly charts)
3) Export Weekly Summary (one-page report / PDF)

### Exclude (later)
- OCR/scan automation
- Multiple template support
- Accounts/login
- Clinic integrations

## Users
- Parents/guardians (primary)
- BCBA/therapy team (secondary; receives exported summary)

## Core Workflow
1) Parent enters a daily log (checkboxes + notes)
2) App stores entries locally (privacy-first)
3) Dashboard shows trends over time
4) Parent exports weekly summary for meetings

## Screens
1) Home Dashboard
2) Add Log
3) Trends
4) Export (Weekly Summary)

## Data Model (draft)
- date
- domains (work supports, transitions, behavior, play, meal, bathroom, communication, social, activities)
- notes
- optional tags (sleep, school day, illness)

## Privacy Principles
- Parent-controlled data
- No usernames/handles
- No PII required for MVP
- Simple deletion/export supported
