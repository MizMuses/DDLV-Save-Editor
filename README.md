# DDLV-Save-Editor
Disney Dreamlight Save Editor and Tool 

DDLV Save Editor (SAFE BASE) — First Official Release

A friend-friendly Disney Dreamlight Valley Save Editor built in Python + Tkinter with a strict plugin system and a safety-first approach. This release is our SAFE BASE: if future updates break something, we roll back to this version.

Highlights

Add Selected means Add Selected across tabs (no surprise “added everything” chaos).

Collections work:

Recipes correctly register in Collections

Memories correctly register in Collections (no weird cross-category mixups)

Color rules everywhere (fast ownership clarity):

🟩 Green = Not owned

⬜ White = Owned

🟧 Orange + ⚠ = Missing image / unreleased warning (auto-fixes when local assets exist)

Scroll stays put after adding/removing items (no rage-scroll resets).

World Cleanup can remove glitched placed objects safely (scan → identify → remove → save).

Weather is safe: Snow is disabled to prevent the known #102 init crash.

Save sanitizer prevents common “game won’t start” save corruption patterns.

DO NOT SKIP QUESTS DURING REALM/UNLOCK QUESTS!

Download

Get the latest build from Releases on GitHub (Assets).
Always extract the zip before running the editor.

Safety Notes

Always back up your save before editing.

⚠ items are marked for a reason — don’t spam unreleased content.

If something goes wrong, check the included log file and share it when asking for help.

Made with love, stubbornness, and just a tiny bit of Disney chaos. 💙
