From Ashley Richmond on Medium

## The 10-Week Sprint Protocol for Maximum Fat Loss
This protocol ramps you up progressively — while keeping total time commitment low.

Start with just 4 short sprints twice a week. By the end, you’ll be doing 4 x 30-second sprints — and be in the best shape of your life.

## Weeks 1–3: 10-Second Sprints

- Week 1: 4x10s sprints, 4 min rest
- Week 2: 6x10s, 3 min rest
- Week 3: 8x10s, 2 min rest

## Weeks 4–6: 20-Second Sprints

- Week 4: 4x20s, 4 min rest
- Week 5: 6x20s, 3 min rest
- Week 6: 8x20s, 2 min rest

## Weeks 7–10: 30-Second Sprints

- Week 7: 4x30s, 4 min rest
- Week 8: 4x30s, 3 min rest
- Week 9: 4x30s, 2 min rest
- Week 10: 4x30s, 4 min rest (now 3x/week)
After week 10, continue with the final protocol (4x30s sprints, 3x/week) for 3–4 weeks.

Then de-load, take a few weeks off — and repeat as needed.

## App

A single self-contained web app (`index.html`) generates the schedule above
and runs a countdown timer with audible alarms (via the Web Audio API) to
mark the start of each sprint and rest interval. Rest time is the total rest
budget for the session, split evenly across sprints (including after the
final sprint).

Just open `index.html` in a browser — no install, no server required.

Alarms: 2 high beeps = sprint starts, 1 low beep = rest starts, 3 beeps = session complete.
Use the Stop button to end a session early.

The original Python CLI (`sit.py`, `timer.py`, `schedule.py`) has been moved to
`archive/` and is no longer maintained.