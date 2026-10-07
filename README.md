# Star Watch

Star Watch is a Grok Bot assistant that works as your personal sky guide. Twice a day it sends a short briefing you can read aloud, covering what's visible from where you live. It always starts with the sky object you care about most.

## What it does

- **Morning briefing (before dawn):** what's up before sunrise, plus anything notable later in the day.
- **Evening briefing:** what to look for tonight, with rise times and where to look.
- **Priority order:** your top object comes first (for example, Venus), with its visibility, best viewing window, direction, and elevation. Next come your secondary objects (for example, the Moon and Jupiter). Everything else, like stars, meteor showers, and ISS passes, comes last.
- **Real data only:** positions and times are computed, and cloud cover comes from a real forecast. Nothing is guessed.

## Repo contents

| Path | What it is |
| --- | --- |
| `memory/briefing-style.md` | The standing instruction that sets priority order and tone |
| `routines/morning-sky-briefing.md` | Saved prompt for the before-dawn briefing |
| `routines/evening-sky-briefing.md` | Saved prompt for the evening briefing |
| `skills/getting-started.md` | The welcome chat a new owner goes through on day one |

## Setup

1. Create a new Grok Bot assistant (or import the Star Watch template).
2. Run the welcome chat in `skills/getting-started.md`. It asks for your name, your location, your favorite sky objects, and when you want briefings.
3. Create the two routines from `routines/` at the times you picked, with your location and priorities filled in.

## Example schedule

Each briefing runs daily, weekends included, because the sky doesn't take days off.

- Morning: about 5 AM local time
- Evening: about 6 PM local time
