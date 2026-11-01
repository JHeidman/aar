# Playing by Email with Vassal Logfiles

Menu names are from Vassal 3.7; other versions may differ slightly.

## Before you start
- Both players use the **same Vassal version** and the **same Red Strike module version**.
- Set a password in **Preferences → Personal**. Vassal uses it to remember which side you're playing.

## Starting a game (one player)
1. **File → New Game**, pick the scenario setup, choose your side.
2. **File → Begin Logfile**. Name it like `CS-T1-AS1-WP-Jeff.vlog` (scenario, turn, action stage, side, player).
3. Make your moves.
4. **File → End Logfile** to save, then send the file.

## Receiving a file
1. **File → Load Game**, open the `.vlog`.
2. Step through it with the **step-forward button** on the toolbar (or Page Down). Each click replays one action, including dice rolls.
3. **Step all the way to the end before touching anything.** Moving a piece mid-replay puts the game out of sync.
4. Start a new logfile (Vassal often offers to; otherwise File → Begin Logfile), make your moves, end the log, send it back.

## Tips
- **Roll dice with the module's dice buttons**, not real dice, so the rolls are recorded.
- **Type notes in the chat box.** They're saved in the log ("attacking 0402 in Hasty Assault").
- **Undo is recorded too.** Fine for honest fixes; just say so in chat.
- **Save every log to `saves/`** in this repo, so Claude can read the chat lines for the write-up.

## Proposed procedure for Red Strike (draft)
- **Standing orders:** at the end of each file, the player about to defend posts in chat, for every stack adjacent to the enemy, the combat formation and whether to try a tactical withdrawal (e.g. "0405: HD, no TW"). The attacker resolves all combats in one file using those orders.
- About one file per Action Stage (4–6 files per turn).
- Once air units are in play (Reforger onward), consider moving by email and doing combat phases live.
