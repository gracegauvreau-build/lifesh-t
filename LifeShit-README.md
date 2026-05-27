# Life Shit

A mobile life-management app I designed and built from scratch to solve a problem I had with my own scattered notes: chores, life admin, wedding planning, and one-off to-dos were spread across three notes apps, two reminder lists, and a running text thread with myself.

I built it using AI-assisted coding, owning the full loop end-to-end: user research, problem framing, interaction design, prototype, and iteration.

## The problem I was solving

I kept making "one-off" notes in my phone about things I needed to do — but the act of capturing was so frictionless that organizing them was always *future me*'s problem. Future me never showed up.

Existing tools failed me in specific ways:
- **Apple Notes** — frictionless capture, zero structure. Searching for "that thing about the caterer" is a guessing game.
- **Reminders / Things / Todoist** — too much structure up front. You have to know the category, the date, the project. By the time I'd opened the app, I'd forgotten what I was trying to do.
- **Notion** — beautiful in theory, dies on mobile. The capture step takes too long.

The wedge: **capture should be one tap. Organizing should be optional.**

## Product decisions I made

A few things I deliberately chose, with the tradeoffs spelled out:

**Quick-add lives on the home screen, not behind a button.** Tradeoff: less aesthetic real estate for browsing tasks. Worth it — capture friction was the actual problem.

**Categories are flexible, not required.** Tasks can live uncategorized indefinitely. Tradeoff: power users who want everything sorted will be annoyed. But forcing categorization at capture time recreates the exact problem I was trying to solve.

**Notes nest inside tasks.** Tradeoff: notes-as-first-class-citizens lose visibility. But in practice my "notes" are almost always context for a task ("ask florist about peony alternatives" → the note is the question, the task is asking).

**Today view pulls across categories.** Tradeoff: you can't see "wedding stuff due today" in isolation. Solved by filtering, but the default view is integrated because real life is integrated.

## What I'd build next

Things I scoped out for v1 but would tackle next:

1. **Recurring tasks with smart defaults** — weekly chores shouldn't require manual setup
2. **Quick-add from a widget or shortcut** — even one tap into the app is a tap too many
3. **A "review" rhythm** — surface tasks that have been sitting uncategorized for >7 days, ask if they're still relevant
4. **Sharing on a single task** — for the wedding stuff specifically; not full collaboration, just "here's the florist note, take a look"

## Tech

Web prototype built using AI-assisted coding tools (Claude Opus 4.7). I'm a self-taught builder — design instinct came from years of PM work, code came from pairing with AI and shipping fast.

## Why I'm sharing this publicly

I'm a product manager who builds. Most PMs hand off requirements; I'd rather sketch the thing and have it react. This repo is a worked example of that — a real problem, a real product, real tradeoffs documented, and a working artifact at the end.

---

*If you got here from my resume, hi 👋 — I'm [Grace](https://www.linkedin.com/in/[your-handle]). The most useful thing on this page is probably the "Product decisions I made" section; that's where the PM brain shows up.*
