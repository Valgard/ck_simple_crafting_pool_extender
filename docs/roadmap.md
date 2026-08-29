# Simple Crafting Pool Extender — Roadmap

Points that are **deliberately cut to stand alone**, not a shopping list for a
release. The useful question is "which point next?", never "what goes into
version X" — a version collects whatever happened to be finished by then.

Each entry records what is already settled and what still has to be decided, so
picking one up does not mean re-deriving the groundwork.

## New screenshots — the current ones show the macOS title bar

Both pictures this mod ships — `simple-crafting-pool-extender-iron-workbench.png`
and `-carpenter-workbench.png` in `sources/` — were taken as window captures
rather than as full-screen frames, and each carries the macOS title bar with its
three traffic-light buttons and the window title above the game. They need
retaking.

**Settled: it is both of them, and it is measurable.** Both are 4336×2804 —
not 16:9 — with the bar at the top edge, captured in the same session as the
sibling mod's set, so neither is worth keeping. Both are also in use:
`CK_DISCORD_MEDIA` in `.envrc` names them in order, and they are what the
mod.io and Workshop galleries show — those galleries are filled in by hand,
since the publish pipeline uploads the logo and nothing else.

**Settled: cropping is not the fix, and the repo's crop helper is the wrong
tool for it.** `../utils/crop-center-169.sh` takes the centre 16:9 slice at
*full height* — it narrows the width and leaves the bar exactly where it is.
Cutting the bar off by hand would work but leaves a window-sized frame of a
game that was running windowed, so the letterboxing inside it stays.

**To decide.** Whether the two workbenches stay the subject. They show the
pool at a station, which is the point of the mod, but neither picture can show
what is *not* there without them — so it is open whether a before/after pair at
one station reads better than the same after-state at two. And whether the
Discord thread gets the new pictures as a comment, since it already carries the
old ones.
