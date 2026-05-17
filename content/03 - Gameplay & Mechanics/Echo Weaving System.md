---
title: Echo Weaving System
draft: false
tags:
  - magic
  - echo-weaving
---
# Echo Weaving System

Magic in *The Verse of Silence* is not a spellbook. It is the act of **weaving Echoes** – elemental shards found in the environment – into temporary spells. This system is designed to feel like **conducting a fragile, dangerous song**: every spell is a choice, every element has a cost, and the environment is your arsenal.

## Core Principles

- **No mana bar.** Instead, a short **resonance cooldown** prevents spamming. After casting, the player glows faintly for a second – they are “ringing” and cannot weave again until the resonance settles.
- **No infinite inventory.** The player can hold **up to 2 shards** by default (upgradeable to 3 later in the game). Picking up a third automatically drops the oldest.
- **Combination, not selection.** A spell is not chosen from a list. It is created by selecting two held shards (Lead and Echo) and releasing the Weave button. Order matters: `Water + Light` ≠ `Light + Water`.
- **Context sensitivity.** The same combination may behave differently when targeted at an enemy, at the ground, or at an ally. (Simpler to implement with an aim‑state check: if target is enemy → sleep; if target is self/ally → heal; if ground → mist zone.)

## The Weaving Wheel (UI)

When the player holds the Weave button (e.g., Right Mouse / RT on controller), time slows slightly (optional) and a radial **Weaving Wheel** appears. The two held shards are shown as icons connected by a thread. The player can press the corresponding shard button to toggle which one is Lead (the primary note) and which is Echo (the harmonic). Releasing the Weave button casts the spell.

- **Lead shard** determines the spell’s **element** (e.g., Water = pacify/flow, Fire = damage/passion, Stone = solidity/defence, Light = reveal/heal).
- **Echo shard** modifies the **effect** (e.g., Water as Echo softens the spell; Fire as Echo makes it aggressive; Light as Echo makes it purifying; Stone as Echo makes it a barrier).
- The game will not provide a full recipe book. Players are meant to **experiment** and discover combinations. The Journal will record discovered spells in‑character.

## Shard Sources (see also [[Shard Types]])

Shards are found in the world:
- **Natural:** Puddles (Water), sunbeams/crystals (Light), rock formations (Stone), volcanic vents (Fire).
- **Creatures:** Glimmerkin shed shards peacefully if befriended, or drop tainted Fire shards if killed.
- **Slain enemies:** Fallen Dissonants or constructs may drop Agony shards (corrupted, powerful, addictive).
- **Boss arenas:** Memory Motes (special shards) appear during Pillar fights; they fill the Resonance Bar.

## Spell Examples (for design)

| Lead + Echo | Harmony Effect | Power Equivalent |
|-------------|----------------|------------------|
| Water + Light | **Sleeping Mist** – Pacifies a target, non‑lethal. | **Drowning Haze** – Slows and damages over time (tainted). |
| Light + Water | **Healing Dew** – Restores a small amount of health / cleanses corruption. | **Burning Revelation** – Reveals hidden things but hurts the player slightly. |
| Stone + Fire | **Molten Spike** – A slow, heavy projectile that shatters on impact. | **Magma Burst** – Faster, wider, but can stagger the player on miss. |
| Fire + Stone | **Raging Tremor** – Point‑blank AoE knockback. | **Cracking Howl** – Larger AoE, damages the player if too close. |
| Water + Stone | **Mud Slick** – Creates a slowing zone. | **Quicksand Pit** – Immobilises smaller enemies but has a chance to trap the player. |
| Light + Fire | **Blinding Flash** – Short stun in front of the player. | **Searing Scream** – Cone damage, deafens the player briefly. |

**Agony Shards** (Power‑path only) always produce destructive, unstable spells. When used as Lead, they create high‑damage but feedback‑prone attacks. As Echo, they amplify damage but apply a stacking “deafening” debuff (see [[Resonance Drowning]]).

See also: [[Shard Types]], [[Combat Flow]], [[Paths - Harmony and Power]]