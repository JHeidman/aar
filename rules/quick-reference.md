# Quick Reference (our notes)

Our own summary, with rule numbers so you can look things up. **The rulebook wins** if anything here disagrees with it. Focused on the ground game, which is what the first scenario teaches.

## Scale & basics
- **RE (regiment equivalent)** = one brigade/regiment. Division = 3 RE, HQ = 1 RE, battalion = 0.5 RE. *(1.2.3, 10.1)*
- **Stacking:** max 6 RE per hex; 9 RE if attacking in Deliberate Assault. Overstacking is only checked at combat; an overstacked stack drops to Advance to Contact and the excess units don't add strength but still take losses. *(10.1)*

## Turn structure
Each Game Turn (GT): **Strategic Stage** (initiative, reinforcements) → **Administrative Stage** (assign modes, supply) → **3 Action Stages** → **End Stage**. *(6–9)*

| Action Stage | Who moves | Who can attack |
|---|---|---|
| **1st — "Frontline Offensive"** | Initiative player's **Frontline** units; then Reaction player's **Reserve** units | Initiative player (Frontline units only) |
| **2nd — "Reserve Exploitation"** | Initiative player's **Reserve** units; then Reaction player's **Reserve** units | Initiative player (any units) |
| **3rd — "Counteroffensive"** | Reaction player's **Frontline + unmoved Reserve**; then Initiative player's **Reserve** | Reaction player (any units) |

- Each ground unit moves **at most once per GT**. *(9)*
- Ground combat only happens in Combat Phases, never during movement. *(9)*
- The Initiative player has the upper hand: the Reaction player mostly responds and can only attack in the 3rd Action Stage. *(9)*

## Initiative
- The scenario says who has it on GT 1. After that: whoever won more battles last turn (the **Battles Won** marker) takes it; if it's at 0, it stays put. Reset the marker after checking. *(6.2)*
- You **lose a battle** if you take more hits than the other side (retreats count as hits). Ties don't count. *(15.5.6)*

## Modes (set every turn in the Unit Assignment Phase)
- **Frontline** (no marker) or **Reserve** (Reserve marker on the stack). *(15.2)*
- Reserve needs an HQ of the same formation in command range, up to the HQ's **Reserve Capacity, counted in REs**. *(15.1.3, 15.2.2)*
- A unit in Reserve that **declares an attack goes back to Frontline** immediately. *(15.2.2)*

## Zones of Control
- Only a stack with **3+ REs** of assault units has a ZOC (the six surrounding hexes). *(2.6)*
- **Entering** an enemy ZOC: stop. **Leaving** costs +2 MP. If you start in an enemy ZOC and haven't moved, you may move straight into another enemy ZOC (then stop). *(2.6)*
- Friendly units in a hex **don't** cancel enemy ZOC for movement or retreat. *(2.6)*
- Retreating through enemy ZOC: 1 hit per hex. Advancing after combat ignores enemy ZOC. *(2.6)*

## Ground combat, step by step *(15.5)*
1. **Declare** one combat at a time (marker on defender + attacking hexes). Each hex is attacked once per phase; each unit fights once per phase. Units must be adjacent and able to cross the hexside.
2. **Tactical Withdrawal (defender's option):** roll on the TW table; on a success, the defender slips up to 2 hexes away and the attacker must move into the vacated hex. *(15.5.2.1)*
3. **Close Air Support:** defender declares first, then attacker. *(9)*
4. **Pick Combat Formations** secretly, then reveal. They cost **supply points (SP) per unit**: *(15.3)*

| Formation | SP/unit | Effect | Artillery bonus (HQ in range) |
|---|---|---|---|
| AC — Advance to Contact | 0 | Printed strength | Attacker +1 DRM |
| HA — Hasty Assault | 2 | Strength ×2 | +2 DRM |
| DA — Deliberate Assault | 4 | Strength ×3, 9 RE stacking; needs HQ in range | +3 DRM |
| HD — Hasty Defense | 2 | 1 column shift to defender | 1 more shift left |
| DD — Deliberate Defense | 4 | 2 column shifts to defender; **can't retreat**, takes +1 hit instead; needs HQ in range | 1 more shift left |

5. **Ratio:** attacker strength ÷ defender strength, rounded (15÷6 = 2.5 → 3:1). Then apply column shifts (terrain, defense formation, Battle-hardened). Final column gives a DRM. *(15.5.4)*
6. **Roll 1d10** + DRM on the CRT. Results are hits and/or "R" (retreat 1 hex). Big stacks (5+ or 9+ RE in total) take extra hits. *(15.5.5)*
7. **Retreat:** all units on that side, 1 hex, avoiding enemy ZOC; defenders can't end adjacent to the attackers (1 hit if forced to). A retreating attacker gets no advance. *(15.6.1)*
8. **Clean-up:** remove markers; winners become **Battle-hardened** (1 column shift in their favour; can be given up to cancel a hit; lost if the stack changes). *(15.4.1, 15.5.7)*

## Supply effects in combat
Out of supply: no Hasty/Deliberate formations, strength halved, HQ gives no support. *(15.5.1.4)*
