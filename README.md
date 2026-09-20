# Tiny Universe Ascension Planner

A calculator for the Ascension system in **Tiny Universe** (Android). Enter your current and target ascension to see:

- how many **Echoes**, **Big Bang Points (BBP)** and **Shards** to bank before ascending, so you can max Collapse, Big Bang and Rupture right away
- the **lifetime** totals needed to unlock each level
- which level you're **ready to ascend to** based on your banked and lifetime amounts

**Live tool:** https://arkay-origin.github.io/tu-calc/

Created by **Arkay**, using data from **Emperor**, **Da6Gaming** and **Bolt**. If you find this tool helpful, please consider giving fame to **Arkay** or **ExoticWratchX20** (Bolt). Not Da6Gaming though. He has enough.

## How the numbers work

Both charts use the same rule, starting from a base cost at A1:

```
next level = (current level × 1.1) + base
```

| | Bank to max (base) | Lifetime to ascend (base) |
|---|---|---|
| Echoes | 10,144 | 10,000 |
| BBP | 1,582 | 1,000 |
| Shards | 190 | 100 |

Bank costs are rounded up each step and match Bolt's pinned chart exactly. Lifetime totals match the community lifetime chart exactly. Bases, growth and rounding can be changed under **Formula settings** if the game is rebalanced.

This is a fan-made tool, not affiliated with the Tiny Universe developer. The numbers come from community data and may not be exact.

## Privacy

Everything runs in your browser. Your inputs are saved only on your device (browser local storage) and are never sent anywhere.

## Changelog

### v1.0.2
- Credit line: Da6Gaming added as a contributor to the formula data.

### v1.0.1
- Credit line tweak: fame request now mentions Da6Gaming.

### v1.0.0
- First release: bank and lifetime requirements up to A200, readiness check from your current level, level-by-level table, and editable formula settings.

## License

GPL-3.0
