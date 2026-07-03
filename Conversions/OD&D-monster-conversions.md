# Manually Converting OSE Monsters to Dragonbane

This guide explains how to convert an Old-School Essentials (OSE) monster into a Dragonbane monster

Most statistics can be converted mechanically. **Ferocity should always be assigned by the GM** based on the monster's intended role in combat (see `ferocity-conversion-notes.md`).

---

## Step 1. Armor Value

Convert descending OSE Armor Class to Dragonbane Armor Value.

| OSE AC | Dragonbane AV |
|-------:|--------------:|
| 9 | 0 |
| 8 | 1 |
| 7 | 2 |
| 5–6 | 3 |
| 3–4 | 4 |
| 1–2 | 5 |
| 0 to -1 | 6 |
| -2 to -3 | 7 |
| -4 or better | 8 |

---

## Step 2. Hit Points

Convert Hit Dice to Dragonbane HP.

### Less than 2 HD

| OSE HD | Dragonbane HP |
|--------|--------------:|
| ½ | 5 |
| 1−1 | 8 |
| 1 | 10 |
| 1+1 | 12 |
| 1+2 | 14 |
| 1+3 | 16 |

### 2 HD or More

Use the following formula:

```
HP = (Whole HD × 7) + Static Bonus
```

Examples:

| OSE HD | Dragonbane HP |
|--------|--------------:|
| 2 | 14 |
| 2+2 | 16 |
| 3 | 21 |
| 4 | 28 |
| 5+1 | 36 |

---

## Step 3. Typical Skill

Assign a Typical Skill value based on the monster's Hit Dice.

| OSE HD | Typical Skill |
|--------|--------------:|
| ½ | 8 |
| 1−1 | 10 |
| 1 | 12 |
| 1+1 to 2 | 13 |
| 3 | 14 |
| 4–5 | 15 |
| 6–7 | 16 |
| 8–9 | 17 |
| 10+ | 18 |

---

## Step 4. Evade

Unless the monster is exceptionally agile or clumsy:

```
Evade = Typical Skill − 2
```

Never reduce Evade below **8**.

Adjust this value if the creature is notably nimble, sluggish, or supernatural.

---

## Step 5. Movement

OSE movement is normally listed as:

```
120' (40')
```

Use the value in parentheses (the dungeon movement), then divide by 10.

Examples:

| OSE Movement | Dragonbane |
|-------------|-----------:|
| 30' (10') | 1 |
| 60' (20') | 2 |
| 90' (30') | 3 |
| 120' (40') | 4 |
| 150' (50') | 5 |

If no parenthetical value exists, divide the listed movement by 10.

---

## Step 6. Damage

Dragonbane monsters generally hit harder than their OSE counterparts.

Double the number of damage dice, to a maximum of four dice.

| OSE Damage | Dragonbane Damage |
|-----------|------------------|
| 1d4 | 2d4 |
| 1d6 | 2d6 |
| 1d8 | 2d8 |
| 2d6 | 4d6 |
| 3d6 | 4d6 |

Keep any special wording such as "or by weapon."

---

## Step 7. Multiple Attacks

If an OSE monster has multiple attacks (such as **2 claws and 1 bite**), keep those attacks in Dragonbane.

List each attack separately using the monster's Typical Skill.

---

## Step 8. Ferocity

Do **not** calculate Ferocity from Hit Dice.

Instead, assign Ferocity based on the monster's intended battlefield role and how it is expected to be encountered.

See **`ferocity-conversion-notes.md`** for guidance.

---

## Step 9. Special Abilities

Most OSE special abilities can be carried over with minimal changes.

When necessary:

- Replace saving throws with Dragonbane skill rolls or opposed rolls.
- Convert percentage chances into a d20 or skill roll where appropriate.
- Rewrite abilities to use Dragonbane terminology while preserving their original intent.

---

## Step 10. Monster Attacks Table

Finally, create a Dragonbane **d6 Monster Attack Table**.

Whenever possible, convert the creature's signature attacks and special abilities into cinematic Dragonbane monster attacks rather than simply copying the OSE attack routine. A good Monster Attack Table should make the creature feel unique and encourage dynamic combat.
