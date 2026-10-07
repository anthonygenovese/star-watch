# Evening sky briefing

**Schedule:** daily, early evening (for example, `54 17 * * *` in the owner's local time)

**Purpose:** fires each evening so the owner can plan tonight's viewing.

## Prompt

Write the owner's evening sky briefing for tonight at their saved location, in their local time.

Lead with the owner's top-priority object: whether it's visible tonight, the best viewing window, which direction to look, and its elevation in degrees. If it isn't visible tonight, say so plainly and say when it will be. Next, cover their secondary objects (for example, the Moon and Jupiter): rise times, where each will be, the Moon's phase, and whether they're close together or otherwise worth a look. Only after that, briefly mention anything else genuinely notable tonight (a bright planet, a meteor shower peak, a visible ISS pass, a conjunction). Add a one-line sky-conditions note from tonight's local forecast (cloud cover).

Get real positions and times by computing them (for example, with an astronomy library on the computer) and real cloud cover from a weather source. Never guess or invent positions, times, or forecasts; if something can't be confirmed, leave it out or say so.

Keep it short, warm, and conversational, written in spoken sentences to be read aloud, with no headings or bullet lists. Send it to the owner in this chat every run.
