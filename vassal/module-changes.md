# Vassal Module Changes (wish list)

Changes we'd like to make to the Red Strike module (v1.0, John Rainey). Both players need the same modified module, so share the `.vmod` once it's done.

## Unit state toggles (no markers on top of counters)

| Change | How it shows | Notes |
|---|---|---|
| **Reserve mode** *(first priority)* | Thin colored border or small "R" badge on the counter | Toggle by right-click or hotkey (e.g. Ctrl+R). Toolbar button to clear all Reserve flags at the start of each turn. Reserve is also lost when a unit attacks (15.2.2) or after combat clean-up (15.5.7). |
| **Combat formation** | Small AC / HA / DA / HD / DD badge | Cleared after each combat. |
| **Battle-hardened** | Corner badge | Lost when the stack changes (15.4.1). |
| **Moved this turn** | Subtle dot or tint | Ground units move once per GT (9). Toolbar button to reset each turn. |

## Implementation notes
- A `.vmod` is a zip file. Pieces are defined in `buildFile.xml`.
- Add the toggles as Layer traits on the ground-unit prototypes, with small PNG overlay images.
- Use Global Key Commands for the "reset all" toolbar buttons.
