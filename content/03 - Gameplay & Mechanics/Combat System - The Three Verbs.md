---
title: Combat System – The Three Verbs
draft: false
tags:
  - combat
  - core-loop
---
# Combat System – The Three Verbs

The Dissonant is a flashy playboy. Every fight is a dance of evasion, precision, and style, powered by a **Stamina Bar** that makes every move a choice.

## The Three Verbs

### Dodge (Resonance Slide)
- **Input:** Dedicated button (e.g., Circle / Shift).
- **Stamina Cost:** Low (15–20% of bar).
- **Effect:** Quick, low-profile slide in the held direction with full i-frames for the duration. Leaves a faint blue trail. Can be chained, but spamming empties stamina fast.
- **Use Case:** Avoiding perilous attacks, quick repositioning, escaping swarms. Your "oh shit" button—but it has a price.

### Flash Step (Resonance Blink)
- **Input:** Dedicated button (e.g., Triangle / Right Mouse).
- **Stamina Cost:** High (40–50% of bar).
- **Effect:** Instant teleport directly behind the targeted enemy, or a fixed distance forward if no target locked. **No i-frames during the blink.** Leaves a vivid afterimage and a sharp musical sting. Has a short cooldown (1 second) in addition to the stamina cost.
- **Use Case:** Aggressively breaking an enemy's guard. Teleporting behind an enemy immediately sets them to the **Exposed** state, allowing a non-lethal **Attune** (Harmony) or a lethal **Riposte** (Power). High risk: if you blink into an active hitbox, you take damage.

### Return Gift (Parry)
- **Input:** Timed press (e.g., L1 / Ctrl) just before an attack lands.
- **Stamina Cost:** None.
- **Effect (vs. Mobs):** The attacking enemy is instantly **Exposed**—staggered, weapon lowered, open for a Takedown or Riposte. A shockwave of light erupts from the Dissonant, dealing zero damage but looking devastating.
- **Effect (vs. Bosses):** The boss's hidden **Super Armor** bar builds by one segment. The boss does not stagger. +1 Flow. You gain a brief moment of safety and a **Flash Step charge** (or just the opportunity to Flash Step if you have stamina).
- **Use Case:** The backbone of defense. Rewards precise timing without draining resources. Against mobs, it's an instant non-lethal opening; against bosses, it's how you wear them down.

## The Stamina Bar

- **Capacity:** Enough for roughly 5 dodges or 2 Flash Steps from full.
- **Regen:** Rapid when idle, slower when moving, paused during actions.
- **Empty Stamina:** Cannot Dodge or Flash Step. You can still walk and Return Gift. A clear visual and audio cue (heavy breathing, greyed-out bar) indicates exhaustion.
- **Flow Bonus:** At high Flow (see below), stamina regen is slightly accelerated and Flash Step costs slightly less.

## The Flow Meter

- **What It Is:** A style meter (0–30) that rewards flawless play.
- **Gain Flow On:**
  - Successful Return Gift (+1, +2 for perfect parry against heavy attacks).
  - Successful Takedown/Attune/Riposte (+2).
  - Perfect Dodge (dodging at the last frame) (+1).
- **Lose Flow On:** Taking damage (resets to zero).
- **Decay:** Slowly drains after 3 seconds of inaction or spamming the same move.
- **Effects of High Flow:**
  - **10 Flow:** Takedowns/Attunes fill 20% more of the boss's Resonance Bar (Harmony) or deal bonus stagger (Power).
  - **20 Flow:** Slightly increased movement speed and dash distance.
  - **30 Flow (MAX):** Flash Step stamina cost reduced by 25%. Afterimages last twice as long. The music swells with an added melody layer.

## Enemy States

- **Guarded (Front):** Enemy is alert, can attack, block, or shield. Cannot be Attuned or Riposted from the front.
- **Exposed (Back/Side):** Enemy is staggered, weapon lowered, briefly vulnerable. Triggered by:
  - Flash Stepping behind them.
  - A successful Return Gift (mobs only).
  - An environmental trigger or AoE spell effect.
  - Visual indicator: faint glow on their back, subtle audio cue.

## Non-Lethal Takedown: Attune (Harmony Path)

- **Trigger:** Press the Interact button (e.g., Square / E) while next to an Exposed enemy.
- **Animation:** Your Dissonant places a palm on the enemy's back, or taps them with the Hilt. A burst of harmonic light and a deep, resonant chime erupt. The enemy's eyes flutter, their weapon drops, and they collapse into a peaceful, dormant state.
- **Effect:** Enemy is permanently pacified. Grants +2 Flow. Against bosses (during a Break), this triggers the **Re-Attune** that cracks their Super Armor and opens the Inner Sanctum.

## Lethal Takedown: Riposte (Power Path)

- **Trigger:** Press the Heavy Attack button while next to an Exposed enemy.
- **Animation:** A brutal, point-blank critical strike. Crimson light, a screaming dissonance chord, the enemy is killed instantly.
- **Effect:** Enemy is dead. Grants +2 Flow. Against bosses, this delivers a massive damage critical hit during a stagger window.

## The Mob Loop (Harmony Example)

1. Enter room with 3 Chorus soldiers.
2. First soldier swings. **Return Gift.** Free parry → he's Exposed.
3. **Attune.** Pacified. +2 Flow. No stamina used.
4. Second soldier lunges. You're out of position. **Dodge** sideways (stamina cost). You're now at his flank. **Flash Step** behind him (high stamina cost) to guarantee exposure. **Attune.** Pacified.
5. Third soldier does a flurry. Dodge twice to survive. Stamina low. Wait for his heavy overhead. **Return Gift.** Free exposure. **Attune.** Room cleared.
6. Stamina refills. Flow is high. You feel like a god.

## The Boss Loop (Harmony Example)

1. Boss swings from the right. **Return Gift.** Boss's hidden Super Armor fills by 1/3. +1 Flow. +1 Flash Step charge (or stamina is saved for the Step).
2. Boss uses a perilous AoE. **Dodge** through it with i-frames.
3. Boss attacks again. **Return Gift.** 2/3 Super Armor.
4. Boss attacks again. **Return Gift.** 3/3 Super Armor.
5. You have stamina. **Flash Step** into the boss's face. Time slows. **Attune** (Re-Attune). A resonant pulse cracks their Super Armor. Screen ripples. You enter the **Inner Sanctum**.

## The Power Path Mirror

- **Return Gift** still builds Super Armor vs. bosses, but provides no free exposure vs. mobs (you must Flash Step or break their guard). Power path relies slightly more on stamina for aggressive takedowns.
- **Riposte** replaces Attune as the follow-up to an exposed enemy, dealing lethal damage.
- **Flow** bonuses are identical, just visualised with red/crimson effects instead of blue/light.

See also: [[Combat Flow]], [[Paths - Harmony and Power]], [[Echo Weaving System]], [[Inner Sanctum]]