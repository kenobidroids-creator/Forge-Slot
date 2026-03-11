# ForgeSlot — Player Guide
*A Reel Roguelike*

---

## What Is ForgeSlot?

ForgeSlot is a slot machine with a roguelike progression layer on top. You're not just pulling a lever — you're building a deck of symbols, equipping modifiers, and making decisions every spin. Each run ends at game over; when you start fresh you keep permanent meta-upgrades bought with shards.

The goal each round is to hit a score target before you run out of spins. Hit it, collect gold, visit the shop, and advance. Miss it, and the run ends.

---

## How Scoring Works

Every spin produces a **Score = Chips × Multiplier**.

- **Chips** come from winning paylines. Each symbol has a base chip value, and each combo type adds bonus chips on top.
- **Multiplier** starts at 1× each spin and stacks from combo bonuses, modifiers, and scatter hits.
- **Consolation** — if no payline wins, you still earn a small chip sum from all visible symbols divided by 6. Modifiers like Fortune Teller can triple this.

The spin score is added to your **Round Score**. Hit the round target and you win. Your Round Score carries no penalty into the next round — each round starts fresh.

---

## The Reels

Five reels, three rows, 20 paylines. Paylines run left-to-right across the rows in patterns shown by the coloured dots on the sides of the reel frame.

**Symbols and base chip values:**
| Symbol | Name | Base Chips | Notes |
|--------|------|-----------|-------|
| 💎 | Diamond | 8 | Rare, high value |
| 7️⃣ | Seven | 7 | Rare |
| ⭐ | Star | 5 | Triggers scatter bonus |
| 🔔 | Bell | 4 | |
| 🍀 | Clover | 4 | Starter |
| 🪙 | Coin | 4 | Starter |
| 🍒 | Cherry | 3 | Starter |
| 🍋 | Lemon | 3 | Starter (×2 in pool) |
| 🍎 | Apple | 2 | Starter |
| 💀 | Skull | 0 | Breaks paylines, −4 chips penalty |

**Combo bonuses (chips + multiplier added per winning line):**
| Combo | Chips | Mult |
|-------|-------|------|
| JACKPOT (5× 💎 or 7️⃣) | +250 | ×12 |
| Five of a Kind | +120 | ×6 |
| Four in a Row | +55 | ×3.5 |
| Three in a Row | +22 | ×2 |

---

## The Three Actions

After every spin you have three tools. Each costs a token. Tokens reset each round.

### ⚡ Forge (1 charge/round)
Click **⚡ FORGE** in the token bar, then click any visible symbol on any reel. A modal appears with symbols you can swap in. The cell changes, paylines recalculate, and your score updates immediately. Use forge to fix a near-miss — turn a skull on a winning line into something useful, or complete a four-of-a-kind into five.

### ↕ Nudge (1 token/round)
After spinning, cyan triangle arrows appear at the top and bottom of each reel. Click one to shift that reel one row up or down. A ghost symbol peeking out above/below tells you what's coming. Score recalculates live. Use nudge to slide a winning symbol into a payline, or to push a skull off a line. You can also buy extra nudges mid-round for 5 gold.

### 🔒 Hold (1 token/round)
Click **🔒 HOLD** in the token bar, then click a reel to lock it. That reel won't spin next turn — it stays exactly where it is. Use hold to lock a reel showing a high-value symbol in a scoring position, so you can try to build around it on your next spin.

---

## Skulls 💀

Skulls break paylines — any line passing through a skull cell stops before the skull. They also apply a −4 chip penalty per skull visible on the board. They have no chip value themselves. With the right modifiers (Skull Pact, Void Walker) skulls can be turned into a source of multiplier or chips instead.

---

## The Star Bonus ⭐

If three or more Stars land anywhere on the board during a normal spin, a bonus round triggers:

| Stars | Chips | Mult | Bonus Spins |
|-------|-------|------|-------------|
| 3★ | +22 | ×0.6 | 2 spins |
| 4★ | +55 | ×1.2 | 3 spins |
| 5★ | +120 | ×2.5 | 4 spins |

You then choose one symbol from your deck — it pins to the middle row of the first four reels for all bonus spins. The fifth reel spins freely. All bonus score adds to your round total. Use bonus rounds to burst through a target you were falling short of.

---

## Last Chance

If your spins run out before hitting the target, the round fails — but if you still have forge or nudge tokens, a hint banner appears. You can use those tokens to try one final score push. If you hit the target, the round saves you. If tokens run out without a win, the run ends.

---

## The Shop

After each successful round you visit The Forge Shop. Four items appear: typically two symbols, one modifier, and a Remove Symbol card. You spend gold earned from round rewards.

**Buying a symbol** adds a copy of it to your reel pool. More copies = higher probability that symbol lands on the reels. Symbol counts are shown in the sidebar.

**Buying a modifier** gives you a passive ability active every round from that point forward. You can hold up to 5 modifier slots (upgradeable via meta).

**Remove Symbol** lets you strip one copy of any symbol from your pool for 3G. Use this to thin out weak symbols (🍎, extra 💀) and increase the density of better ones.

**Reroll** costs 1G and refreshes the shop offers.

**Skip** earns +2G if you don't want anything this visit.

**Hold** — any item can be held over to your next shop visit. One held item at a time.

**Sell Modifiers** — your currently equipped modifiers appear below the shop grid. You can sell any modifier for half its original cost (minimum 1G), freeing a slot for something better.

---

## Stages and Progression

The run has 4 stages, each with 3 rounds. Targets escalate sharply:

| Stage | Round 1 | Round 2 | Round 3 |
|-------|---------|---------|---------|
| 1 | 500 | 1,200 | 2,500 |
| 2 | 6,000 | 14,000 | 32,000 |
| 3 | 70,000 | 160,000 | 350,000 |
| 4 | 750,000 | 2,000,000 | — |

The jump from Stage 1 to Stage 2 is dramatic. Your symbol pool and modifiers from the first three rounds are the foundation that has to carry you into the thousands.

---

## Meta Upgrades (Shards ✧)

At the end of every run you earn shards based on your total score (1 shard per 2,000 points). Shards persist between runs and buy permanent meta upgrades on the game over screen:

- **Modifier Slot** — +1 modifier slot (base is 5)
- **Starter Gold** — extra gold at the start of each run
- **Lucky Breaks** — reduces round targets by 10% per level

---

## Strategies

### Early Run (Stage 1)
- **Don't thin your deck too aggressively yet.** Your pool is small; removing symbols makes early spins unpredictable.
- **Prioritise modifier slots early.** A modifier bought in Round 1 applies to every round after. Early-buy modifiers compound the most.
- **Save gold for Round 2 shop.** Stage 2 targets are brutal — you want your strongest deck built before you hit them.
- **Hold is underrated early.** If you land a strong position on a reel, holding it lets you spin around it rather than hoping to replicate it.

### Mid Run (Stage 2–3)
- **Specialise your deck.** If you have Gold Fever (bonus per 🪙), buy more coins. If you have Lucky Lemon, stack lemons. Synergy between modifiers and symbols compounds fast.
- **Remove weak symbols.** Once you have a theme, strip out low-chip symbols that dilute your pool. An 🍎 taking up pool space costs you odds on something better.
- **Watch multiplier stacking.** High mult spins with medium chips beat high chip spins with low mult. Modifiers that give mult per symbol visible (Diamond Dealer, Seven Stars) can snowball a single good spin into thousands.
- **Nudge is more powerful than it looks.** One nudge at the right moment can complete a five-of-a-kind from a four-of-a-kind — that's the difference between ×3.5 and ×6.

### Forge Usage
- **Don't waste forge on marginal improvements.** Swapping a 🍎 for a 🍀 on a line gives you +1 chip. Swapping a 💀 on an otherwise winning five-symbol line can turn 0 into a four-of-a-kind.
- **Forge is best used to rescue a near-miss.** Look for paylines where everything aligns except one cell.
- **With Forge Master (+2 charges), forge becomes a primary tool.** You can adjust multiple cells each round and treat the spin as a starting point rather than the result.

### Skull Management
- **Without skull modifiers, keep skulls to 1 in your pool maximum.** The penalty and payline breaking stack fast if you land 2–3 skulls visible.
- **Skull Pact and Void Walker flip the skull dynamic entirely.** If you have both, skulls become free mult and free chips — you want MORE skulls, not fewer. Build around it.

### Star Bonus Strategy
- **Choose your bonus pin symbol based on remaining round target.** If you need 5,000 and have 2 bonus spins, a high-mult symbol matters more than high chips.
- **Stars are a multiplier amplifier at 4–5 count (×1.2 and ×2.5).** A deck heavy in stars with Seven Stars modifier can self-combo — stars give mult per star visible, which amplifies the scatter mult.

### Nudge Peek
- **Always look at the peek ghost before nudging.** It tells you exactly what you're getting. A ghost skull above tells you not to nudge up even if the current board looks tempting.

---

## Testing & Feedback Tips

When testing ForgeSlot, useful things to note:

**Balance signals:**
- Did you feel stuck at any particular target with no path forward? Note the stage and round.
- Did any modifier feel useless or overpowered relative to its cost?
- Did bonus rounds feel like a meaningful moment, or did they feel unreliable?
- Did the gold economy feel tight, comfortable, or too easy?

**Mechanic clarity:**
- Was it obvious when a payline was winning or not?
- Did you always understand why a score changed after a nudge or forge?
- Were modifier effects visible in the result breakdown?

**Pacing:**
- How far did you typically get before losing? Stage 1 losses are normal early; Stage 2 Round 2 or 3 is where strategy starts mattering.
- Did the shop feel like it had meaningful choices, or were the options often unexciting?

**Edge cases worth testing:**
- What happens if you forge a bonus-pinned symbol?
- What happens if skulls appear on every reel on the same spin?
- What does the last-chance mechanic feel like when you actually save yourself with it?
- Does selling a modifier in the shop feel impactful enough to be worth it?

---

## Quick Reference

| Action | When | Cost |
|--------|------|------|
| Forge | Post-spin | 1 charge/round |
| Nudge | Post-spin | 1 token/round |
| Hold | Post-spin | 1 token/round |
| Buy Nudge | During round | 5G |
| Reroll Shop | In shop | 1G |
| Skip Shop | In shop | +2G earned |
| Remove Symbol | In shop | 3G |
| Sell Modifier | In shop | Half cost |

---

*ForgeSlot is in active development. Mechanics, balance, and content are subject to change.*
