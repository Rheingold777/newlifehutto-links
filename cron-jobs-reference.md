# Cron Jobs Reference
_Last updated: April 13, 2026 — 42 active jobs (post-cleanup)_

---

## ⛪ CHURCH (5 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 8 | Monday Sermon Recap + Breeze Texts | Mon 9:30am | Sends sermon recap SMS to congregation via Breeze (EN + ES). Staleness check: skips if sermon cache >8 days old | ✅ | #church-ops |
| 22 | NLH FB - Monday Sermon Recap | Mon 10am | Posts sermon recap to Facebook (EN + ES). No mockup, pure Spanish | ✅ | #church-updates |
| 20 | NLH FB - Tuesday Bible Study Reminder | Tue 10am | Posts Bible study invite to Facebook | ✅ | #church-updates |
| 21 | NLH FB - Wednesday Scripture | Wed 10am | Posts scripture graphic | ✅ | #church-updates |
| 7 | Friday Weekend Announcement | Fri 5pm | Posts Sunday service reminder to Facebook | ✅ | #church-updates |
| 36 | NLH Social Media Weekly Metrics | Mon 9am | Pulls Facebook/IG stats for the week | ✅ | #church-ops |

---

## 📋 DAILY OPS (7 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 4 | Calendar Change Check | 9/12/3/6pm | Polls Google Calendar for new/changed events | ✅ | #daily-briefing |
| 5 | Tasks Check - Morning | 9am daily | Google Tasks sync + priority review | ✅ | #tasks |
| 6 | Daily Goal-Driven Tasks | 7am daily | Aligns today's tasks with bigger goals | ✅ | #daily-briefing |
| 19 | Daily Signal Check | 6:30am daily | Checks Signal messages for anything urgent | ✅ | #daily-briefing |
| 23 | Daily Channel Summary | 6:45am daily | Summarizes overnight Discord activity | ✅ | #daily-briefing |
| 26 | Auto-Move Incomplete Tasks | 11pm daily | Rolls unfinished tasks to tomorrow | ✅ | #tasks |
| 34 | Personal Agent Morning Brief | 7:30am daily | Personal ops: MBA, health, family | ✅ | #personal |
| 41 | Open Loops Nag | 9am daily | Surfaces items sitting unresolved too long | ✅ | #ops-general |

---

## 📰 DIGESTS (3 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 1 | Weekly Intelligence Digest | Mon 8:30am | Business intel: SermonSync, notary, church growth | ✅ | #daily-briefing |
| 2 | Wednesday Personal Growth Digest | Wed 9:20am | Personal dev, MBA, books, growth summary | ✅ | #growth |
| 3 | Thursday Sermon Digest + Notion | Thu 9:20am | Sermon prep notes, syncs to Notion | ✅ | #church-ops |

---

## 🔧 SYSTEM (10 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 9 | Daily Memory File Update | 9pm daily | Writes today's events/decisions to memory log | ✅ | silent |
| 10 | Compress memory files | Sun 8pm | Compresses old memory files weekly | ✅ | #alerts |
| 11 | Archive old cron outputs | 10pm daily | Cleans up old run logs | ✅ | #alerts |
| 12 | Auto-Update | 4am daily | Updates OpenClaw + system packages nightly | ✅ | #alerts |
| 13 | GitHub Backup | 4:30am daily | Backs up workspace to GitHub | ✅ | #alerts |
| 16 | EOD Sweep & Memory Maintenance | 11pm daily | End-of-day cleanup + memory consolidation | ✅ | #ops-general |
| 25 | Daily Health Check | 6am daily | Checks gateway, disk, services | ✅ | #alerts |
| 27 | Monitor OpenClaw Updates | 9am/3pm/9pm | Checks for new OpenClaw releases | ✅ | #arnold |
| 28 | Check OpenClaw Updates | Mon/Thu 10am | Duplicate of #27 — candidate for deletion | ✅ | #alerts |
| 35 | healthcheck:security-audit | Sun 6am | Server security scan | ✅ | #alerts |
| 42 | Memory Dreaming Promotion | 3am daily | Promotes key memories to long-term storage | ✅ | silent |

---

## 💡 SMART HOME (4 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 39 | Lights White 50% | 7am daily | Gentle morning light | ✅ | silent |
| 40 | Lights White 100% | 8am daily | Full working-mode brightness | ✅ | silent |
| 37 | Lights Indigo 50% | 8pm daily | Evening wind-down lighting | ✅ | silent |
| 38 | Lights Off | 11pm daily | Everything off for sleep | ✅ | silent |

---

## 💼 NOTARY / BUSINESS (2 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 29 | Notary Agent Morning Brief | Mon-Sat 8am | Notary ops: signings, leads, calendar check | ✅ | #notary-ops |
| 30 | Business Agent Morning Brief | Mon-Fri 8:30am | Business ops: SermonSync pipeline, revenue | ✅ | #biz-ops |

---

## 🏗️ SERMONSYNC (1 job)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 15 | SermonSync Waitlist Check | Mon 9am | Checks for new waitlist signups | ✅ | #sermonsync |

> ⚠️ SermonSync social posting DISABLED — Facebook/Instagram tokens expired. Rebuild after token refresh.

---

## 👨‍👩‍👧 FAMILY (4 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 14 | Daily Calendar Email to Shelley | 7pm daily | Emails Shelley tomorrow's schedule | ✅ | #shelley |
| 17 | Weekly Giving Summary | Sun 8pm | Summarizes church giving for the week | ✅ | server |
| 18 | Monthly Calendar PDF for Shelley | End of month | Generates printable PDF calendar | ✅ | silent |
| 24 | Sophie Daily Therapy Email | 7am daily | Daily support/therapy email for Sophie | ✅ | silent |

---

## 📚 CHURCHLAUNCHPAD (3 jobs)

| # | Task | Schedule | What It Does | Status | Channel |
|---|------|----------|-------------|--------|---------|
| 31 | ChurchLaunchpad Newsletter | Tue 9am | Auto-writes + publishes newsletter | ⚠️ fixed (runs Tue) | #biz-ops |
| 32 | Launchpad Welcome Emails | 10am daily | Sends welcome emails to new subscribers | ✅ | #realtor-collab |
| 33 | Newsletter Review Reminder | Tue 9:30am | Reminds to review the newsletter | ✅ | silent |

---

## ⚠️ NEEDS ACTION (token refresh required)

| System | Problem | Fix |
|--------|---------|-----|
| SermonSync FB + IG | Token expired — 0 posts since April 1 | Regenerate in Meta Business Suite → SermonSync page |
| NotaryHub365 FB + IG | Token expired — failing since April | Regenerate in Meta Business Suite → NotaryHub365 page |
