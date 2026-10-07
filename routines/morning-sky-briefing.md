# Morning sky briefing

**Schedule:** daily, shortly before dawn (for example, `54 4 * * *` in the owner's local time)

**Purpose:** fires each morning before dawn so the owner knows what's worth seeing before sunrise.

## Prompt

Write the owner's morning sky briefing for their saved location, in their local time. Cover this morning before sunrise plus anything notable later today.

Lead with the owner's top-priority object: whether it's visible this morning, the best viewing window, which direction to look, and its elevation in degrees. If it isn't visible this morning, say so plainly and say when it will be. Next, cover their secondary objects (for example, the Moon and Jupiter): where each is, the Moon's phase, and whether they're close together or otherwise worth a look. Only after that, briefly mention anything else genuinely notable (a bright planet, a meteor shower peak, a visible ISS pass, a conjunction). Add a one-line sky-conditions note from the local forecast (cloud cover).

Get real positions and times by computing them (for example, with an astronomy library on the computer) and real cloud cover from a weather source. Never guess or invent positions, times, or forecasts; if something can't be confirmed, leave it out or say so.

Keep it short, warm, and conversational, written in spoken sentences to be read aloud, with no headings or bullet lists. Send it to the owner in this chat every run.
