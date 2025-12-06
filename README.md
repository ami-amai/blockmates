# Blockmates

EN | [RU](./ru/README.md)

## Description

*   A desktop vanilla Minecraft game about turn-based block placement. The player with the highest score after the last placed block wins.

## Contents

*   [**Description**](#description)
*   [**Essentials**](#essentials)
*   [**Blocks**](/blocks/DEFAULT.md) - main set of block actions
*   [**Rules**](/sets/DEFAULT_MIDDLE.md) - basic game rules

## Essentials

*   [**Blocks**](./BLOCKS.md) (2 sets)
*   Wool (2 colors)
*   Board
*   Signs with name and score
*   Item Frames

## Gameplay

### Game Setup

Before the start of the game, each player receives a **set of blocks** according to the selected rule variant. Players choose a wool color — this will be the marker for their blocks on the board.

> **Important:** the sets of both players are identical

### Player Turn

Each turn consists of the following stages:

#### 1. Placing a marker
The player chooses a **free cell** on the game board and places there:
-   Wool of their color (as a marker)
-   An Item Frame on top of the wool for subsequent block placement

#### 2. Placing a block
The player chooses **one block** from their set and places it into the installed item frame.

> **Important:** changing the block and place is allowed before scoring

#### 3. Scoring the turn
After placing the block, it is necessary to:
-   Check which blocks are **destroyed**
-   Calculate **points** gained or lost this turn
-   Remove **destroyed** blocks from the board
-   Write the **updated score** on the sign

> **Important:** destroyed blocks subtract points from the **owners of the destroyed blocks**

> **Important:** destroyed blocks are **eliminated** from the game

### Turn Alternation

Players move **in turns**, without the option to skip a turn.

### End of Game

The game **ends** when the **last block of the last player** is placed.

### Determining the Winner

**The winner is the player** who has scored the **highest number of points** by the moment the game ends.