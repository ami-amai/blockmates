Here is the translation of the standard game rules into English with the link updated.

***

# Standard Rules

EN | [RU](/rules/DEFAULT.md)

## Contents

* [Interaction](#interaction)
* [Rarity](#rarity)
* [Terminology](#terminology)
* [List](#list)
* [Blocks](#blocks)

## Interaction
* The radius of any interaction is 1 block (a 3x3 area).
* Interaction applies to both one's own blocks and opponent's blocks, including Break.
* Break counts towards the owner of the destroyed block.

## Rarity
* Depending on the type, points are deducted upon Break:
    * Common: **-3**
    * Rare: **-6**
    * Epic: **-12**
    * Legendary: **-24**
    * Exception: Indicated if present.

## Terminology
* **BLOCK** — any block.

## List

### Common

* [**LEAVES**](#leaves)
* [**WOOD**](#wood)

### Rare

* [**ICE**](#ice)
* [**MAGMA**](#magma)

### Epic

* [**OBSIDIAN**](#obsidian)
* [**GOLD**](#gold)

### Legendary

* [**DIAMOND**](#diamond)

## Blocks

### LEAVES
* **Type:** [Common](#rarity)
* **Action:**
    * +1
* **Break:**

### WOOD
* **Type:** [Common](#rarity)
* **Action:**
    * +2 for Each **LEAVES**
* **Break:**

### ICE
* **Type:** [Rare](#rarity)
* **Action:**
    * If **MAGMA** is present
        * +6
        * Converts **MAGMA** into **OBSIDIAN**
* **Break:**

### MAGMA
* **Type:** [Rare](#rarity)
* **Action:**
    * If **BLOCK** is present
        * Destroys **BLOCK**
        * -1 for Each
* **Break:**

### OBSIDIAN
* **Type:** [Epic](#rarity)
* **Action:**
    * If **BLOCK** is present (except **OBSIDIAN**)
        * Protects **BLOCK** from Break
    * Effect triggers on Placement or **MAGMA** Conversion
* **Break:**

### GOLD
* **Type:** [Epic](#rarity)
* **Action:**
    * +6
    * If **GOLD** is present
        * +2 for Each
* **Break:**

### DIAMOND
* **Type:** [Legendary](#rarity)
* **Action:**
    * +12
    * If **GOLD** is present
        * +12 for Each
* **Break:**