# Ebb and Flow Mod - Configuration Settings

This document outlines the in-game settings available for the Ebb and Flow mod. All settings can be adjusted from the **Mod Settings** button in the game's options menu.

---

### Global Strength Adjustment

* **Enable Global Strength Reduction**
    * Enable a global multiplier that affects the strength of all water sources.
* **Global Strength Multiplier**
    * A multiplier applied to all water sources (e.g., a value of `1.0` results in normal strength).

### Dynamic Fluctuations

* **Enable Dynamic Fluctuations**
    * Allow random, temporary changes to water source strength.
* **Max Affected Sources Per Update**
    * The maximum number of water sources that can start new fluctuations each mod cycle.
* **Chance to Skip Fluctuation**
    * The probability that the mod will skip starting any new fluctuations in a given cycle (`0.0` = never skip, `1.0` = always skip).
* **Min Fluctuation Modifier**
    * The minimum strength a water source can have during a fluctuation (e.g., `0.5` = 50% of normal strength).
* **Max Fluctuation Modifier**
    * The maximum strength a water source can have during a fluctuation (e.g., `2.0` = 200% of normal strength).
* **Fluctuation Duration Ticks**
    * The duration, in mod cycles, that a fluctuation will last.

### Source Toggling

* **Enable Source Toggling**
    * Allow the mod to temporarily turn water sources on and off.
* **Sources Division Factor**
    * The total number of map sources is divided by this number to determine how many are considered for toggling each cycle (e.g., a value of `3` means 1/3 of sources are checked).
* **Max Sources to Toggle Off**
    * The maximum number of water sources that can be toggled off per cycle.
* **Chance to Toggle Off**
    * The probability that a considered water source will actually be toggled off (`0.0` = never, `1.0` = always).
* **Toggle-Off Strength**
    * The strength of a water source when it is in the "off" state (e.g., `0.15` = 15% of normal strength).
* **Toggle Off Duration Ticks**
    * The duration, in mod cycles, that a source will remain in the "off" state.

### Contamination

* **Target Contamination Linger (in Days)**
    * Controls how long contamination persists in the soil, measured in game days.

### Sludge Generation

* **Enable Sludge Generation**
    * Allow sludge blocks to spawn in contaminated water.
* **Chance to Spawn Sludge**
    * The probability of spawning sludge blocks each mod cycle (`0.0` = never, `1.0` = always).
* **Max Sludge Per Bad Source**
    * The maximum number of sludge blocks that can spawn from a single contamination event.
* **Sludge Spawn Radius**
    * The maximum distance from a contamination source where sludge can spawn.
* **Min Water Depth for Sludge**
    * The minimum water depth required for sludge to form (e.g., `0.2` = 20% of a block's height).
* **Allow Sludge in Flow Channels**
    * Allow sludge blocks to spawn in flowing water channels.
* **Max Adjacent Sludge to Prevent Full Block**
    * The maximum number of adjacent sludge blocks allowed before a tile is considered fully blocked, preventing new sludge from spawning there.

### Sludge Clearing

* **Enable Good Water Clears Sludge**
    * Clean water can remove sludge.
* **Chance to Clear Sludge Per Cycle**
    * The probability of clearing sludge each mod cycle.
* **Good Water Clear Radius**
    * The radius in which clean water will clear sludge.
* **Good Water Clean Threshold**
    * The maximum contamination level (`0.0` to `1.0`) that is still considered "clean" enough to clear sludge.

---
*This README was generated based on the current mod configuration and may be updated as new features are added.*