# Main Block Set

EN | [RU](./ru/BLOCKS.md)

## Interaction
* Any interaction radius is 1 block (3x3 area)
* Interaction extends to both own and foreign blocks, including destruction

## Rarity
* Depending on the type, points are subtracted upon destruction:
    * Common: **-1**
    * Special: **-3**
    * Unique: **-6**
    * Legendary: **-12**
    * Exception: Indicated if any

## Categories
* Depending on importance, blocks are sorted into the following categories:
    * Simple - give points without any conditions
    * Dependent - give points depending on other blocks
    * Active - directly affect other blocks

## Terminology
* **BLOCK** - any block

### Simple

* [**LEAVES**](#leaves)
* [**GOLD**](#gold)

### Dependent

* [**WOOD**](#wood)
* [**STONE**](#stone)
* [**DIAMOND**](#diamond)

### Active

* [**ICE**](#ice)
* [**MAGMA**](#magma)

## Blocks

### LEAVES
* **Type:** [Common](#rarity)
* **Action:**
    * +1
* **Destruction:**

### WOOD
* **Type:** [Special](#rarity)
* **Action:**
    * +2 per Each **LEAVES**
* **Destruction:**

### STONE
* **Type:** [Unique](#rarity)
* **Action:**
    * -1 for Absence of **WOOD**
    * +2 per Each **WOOD**
* **Destruction:**

### ICE
* **Type:** [Unique](#rarity)
* **Action:**
    * +6 for **MAGMA**
    * Destruction of **MAGMA**
* **Destruction:**

### MAGMA
* **Type:** [Unique](#rarity)
* **Action:**
    * Destruction of **BLOCK**
    * -1 per Each **BLOCK**
* **Destruction:**
    * 0 for Destruction by **ICE**

### GOLD
* **Type:** [Legendary](#rarity)
* **Action:**
    * +6
* **Destruction:**

### DIAMOND
* **Type:** [Legendary](#rarity)
* **Action:**
    * +12
    * +6 per Each **GOLD**
* **Destruction:**