# Default Rules

[EN](/rules/DEFAULT.md) | RU

## Table of Contents

* [Interaction](#interaction)
* [Rarity](#rarity)
* [Terminology](#terminology)
* [List](#list)
* [Blocks](#blocks)

## Interaction
* The interaction radius for any action is 1 block (a 3x3 area)
* Interaction applies to both your own and other players' blocks, including destruction
* Destruction is credited to the owner of the destroyed block

## Rarity
* Depending on the type, points are subtracted upon destruction:
    * Common: **-3**
    * Rare: **-6**
    * Epic: **-12**
    * Legendary: **-24**
    * Exception: Specified if present

## Terminology
* **BLOCK** - any block

## List

### Common

* [**Leaves**](#leaves)
* [**Wood**](#wood)

### Rare

* [**Ice**](#ice)
* [**Magma**](#magma)

### Epic

* [**Obidian**](#obsidian)
* [**Gold**](#gold)

### Legendary

* [**Diamnd**](#diamond)

## Blocks

### Leaves
* **Type:** [Common](#rarity)
* **Action:**
    * You gain **+1**
* **Destruction:**

### Wood
* **Type:** [Common](#rarity)
* **Action:**
    * IF there is **Leaves**
    * You gain **+2** for **Each**
* **Destruction:** Each

### Ice
* **Type:** [Rare](#rarity)
* **Action:**
    * IF there is **Magma**
        * You gain **+6**
        * **Magma** turns into **Obsidian**
* **Destruction:**

### Magma
* **Type:** [Rare](#rarity)
* **Action:**
    * IF there is **Any block**
        * Destroys the **Block**
        * You lose **-1** for **Each Block**
* **Destruction:**

### Obsidian
* **Type:** [Epic](#rarity)
* **Action:**
    * IF there is **Any block** (except **Obsidian**)
        * The **Block** gains Protection from Destruction
    * Triggers upon **Magma** transformation
* **Destruction:**

### Gold
* **Type:** [Epic](#rarity)
* **Action:**
    * You gain **+6**
    * IF there is **Gold**
        * You gain **+2** for **Each**
* **Destruction:**

### Diamond
* **Type:** [Legendary](#rarity)
* **Action:**
    * You gain **+12**
    * IF **Gold** is present
        * You gain **+12** for **Each**
* **Destruction:**