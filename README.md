# 🍔 McDonald's Mod for Minecraft 1.16.5

Ba da ba ba baaa — lovin' it!

## Overview
This mod adds 12 McDonald's-inspired food items to Minecraft 1.16.5 (Forge). Each item has unique stats and special potion effects!

## Requirements
- Minecraft 1.16.5
- Forge 36.2.34+
- Java 8

## Building
1. Clone/download this project
2. Run `./gradlew build` (Linux/Mac) or `gradlew.bat build` (Windows)
3. Find the compiled `.jar` in `build/libs/`
4. Drop the jar into your `.minecraft/mods/` folder

## Items & Effects

| Item | Hunger | Saturation | Special Effect |
|------|--------|-----------|----------------|
| 🍔 Big Mac | 8 | 0.8 | 50% chance: Regeneration I (5s) |
| 🍗 McChicken | 6 | 0.6 | None |
| 🍗 McNuggets (6 pc.) | 5 | 0.5 | None |
| 🍟 Large Fries | 5 | 0.4 | 20% chance: Slowness I (3s) |
| 🍦 McFlurry | 4 | 0.6 | Speed I (10s) |
| 🥧 Apple Pie | 4 | 0.5 | None |
| 🐟 Filet-O-Fish | 6 | 0.6 | None |
| 🍔 Quarter Pounder | 10 | 0.9 | 60% chance: Regeneration II (7.5s) |
| 🎁 Happy Meal | 7 | 0.7 | Speed I + Jump Boost I + Regen I (10s each) |
| 🥤 Cola | 2 | 0.2 | 80% chance: Haste I (6s) |
| 🥩 McRib | 9 | 0.85 | 70% chance: Strength I (10s) |
| 🥤 Shamrock Shake | 4 | 0.5 | Speed II + Jump Boost II (20s each) |

## Crafting Recipes

### Big Mac
```
[Bread] [Bread]  [Bread]
[Beef]  [Beef]   [Beef]
[Bread] [Bread]  [Bread]
→ 2x Big Mac
```

### McChicken
```
[Bread]
[Cooked Chicken]
[Bread]
→ 2x McChicken
```

### McNuggets
```
(Shapeless) 2x Cooked Chicken + Wheat → 3x McNuggets
```

### Large Fries
```
(Shapeless) 3x Baked Potato → 2x Large Fries
```

### McFlurry
```
(Shapeless) 2x Snowball + Cake + Glass Bottle → 1x McFlurry
```

### Apple Pie
```
[Wheat] [Wheat] [Wheat]
[Apple] [Apple] [Apple]
[Wheat] [Wheat] [Wheat]
→ 4x Apple Pie
```

### Filet-O-Fish
```
[Bread]
[Cooked Salmon]
[Bread]
→ 2x Filet-O-Fish
```

### Quarter Pounder
```
[Bread] [Bread] [Bread]
[Beef]  [Beef]  [Beef]
[Bread] [Bread] [Bread]
→ 2x Quarter Pounder
```

### Happy Meal
```
(Shapeless) McChicken + Large Fries + Cola → 1x Happy Meal
```

### Cola
```
(Shapeless) Glass Bottle + 2x Sugar → 2x Cola
```

### McRib
```
[Bread]    [Bread]    [Bread]
[Porkchop] [Porkchop] [Porkchop]
[Bread]    [Bread]    [Bread]
→ 2x McRib
```

### Shamrock Shake
```
(Shapeless) 3x Snowball + Glass Bottle + Green Dye + Sugar → 1x Shamrock Shake
```

## Mod Info
- **Mod ID:** `mcdonaldsmod`
- **Version:** 1.0.0
- **Minecraft:** 1.16.5
- **Forge:** 36.2.34+

## Notes
- Textures are placeholder 16x16 pixel art — feel free to replace them with your own in `assets/mcdonaldsmod/textures/item/`
- All items appear in the **Food** creative tab
- The Happy Meal and Shamrock Shake are the most powerful items!
