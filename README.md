# Tiny Universe Ascension Planner

A calculator for the Ascension system in **Tiny Universe** (Android). Enter your current and target ascension to see:

- how many **Echoes**, **Big Bang Points (BBP)** and **Shards** to bank before ascending, so you can max Collapse, Big Bang and Rupture right away
- the **lifetime** totals needed to unlock each level
- which level you're **ready to ascend to** based on your banked and lifetime amounts
- a **suggested jump**: how far to ascend in one go

**Live tool:** https://arkay-origin.github.io/tu-calc/

Created by **Arkay**, using data from **Emperor**, **Da6Gaming** and **Bolt**. If you find this tool helpful, please consider giving fame to **Arkay** or **ExoticWratchX20** (Bolt). Not Da6Gaming though. He has enough.

## How the numbers work

**Bank costs (A1–A110)** are the figures published by the game's developer and are used exactly as given. Above A110 they're estimated with:

```
cost at An = factor x (1.1^n - 1)
```

with factors of 101,235 (Echoes), 15,700 (BBP) and 1,670 (Shards). That formula matches the published table to within 0.03% from A20 upward. A1–A6 sit a little above it because the game rounds each upgrade individually, which is why the published values are used rather than calculated ones.

**Lifetime requirements** use the same shape, starting from 10,000 Echoes / 1,000 BBP / 100 Shards at A1, and match the community requirement chart exactly.

**Suggested jump** is based on the Ascension bonuses only: Global +1% per rank, passive core +0.06 per rank for Echoes and BBP and +0.025 for Shards. Since each rank adds a flat amount while costs keep climbing about 10% a level, long jumps generally beat ascending one level at a time. It's a best guess. Paradox Fragment builds, Premium upgrades and other boosts aren't accounted for.

Everything above can be changed under **Data & formula settings** if the game is rebalanced.

This is a fan-made tool, not affiliated with the Tiny Universe developer.

## Privacy

Everything runs in your browser. Your inputs are saved only on your device (browser local storage) and are never sent anywhere.

## Changelog

### v1.1.0
- Bank costs now use the developer's published figures for A1-A110, replacing the community estimate. Shard costs drop about 13%; Echoes and BBP by under 1%.
- Above A110, costs are estimated from the fitted formula.
- Added a suggested-jump line.
- Settings reworked: pick the data source, edit the cost factors, growth and lifetime bases.

### v1.0.2
- Credit line: Da6Gaming added as a contributor to the formula data.

### v1.0.1
- Credit line tweak: fame request now mentions Da6Gaming.

### v1.0.0
- First release: bank and lifetime requirements up to A200, readiness check from your current level, level-by-level table, and editable formula settings.

## License

GPL-3.0
