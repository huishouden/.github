# Huishouden

Small installable web apps for running a household together: one shared tablet in the living room,
everyone's phones, the same live data. *Huishouden* is Dutch for "household".

| App | What it does | Repo |
|---|---|---|
| **Huishouden** | The portal: every app in one place, who's in the household, invites | [portal](https://github.com/huishouden/portal) |
| **Spending** | Card spending by month, category and card, synced from card alerts | [spending](https://github.com/huishouden/spending) |
| **Tasks** | Groceries, chores and shared lists, sorted by store aisle | [tasks](https://github.com/huishouden/tasks) |
| **Baby** | Feeds, sleep and diapers at a glance, appointments, checklists, the care team | [baby](https://github.com/huishouden/baby) |

**How they're built.** Every app sits on [pwa-kit](https://github.com/huishouden/pwa-kit): one design
language, one household and sign-in model, shared building blocks (calendar search, contacts, place
lookup, invitations), and one CI pipeline that leak-scans, tests, deploys and smoke-tests every change,
with before/after screenshots on each pull request. Everything runs on free tiers.

Members sign in with Google; a household's data is visible only to its members. The repos hold code
and invented sample data, never a household's own.
