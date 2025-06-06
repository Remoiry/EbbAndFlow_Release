Configuration values:



    configVersion = LATEST_VERSION;                          // DO NOT CHANGE

    // Global strength adjustment
    enableGlobalStrengthReduction = true;                    // Enable global water source strength modifier
    globalStrengthMultiplier = 1.0f;                         // Multiplier for all water sources (1.0 = normal strength)

    // Dynamic fluctuations
    enableDynamicFluctuations = true;                        // Enable random temporary strength changes
    maxAffectedSourcesPerUpdate = 1;                         // Max sources getting new fluctuations per cycle
    chanceToSkipFluctuation = 0.25f;                         // 25% chance to skip starting new fluctuations
    minFluctuationModifier = 0.5f;                           // Minimum strength during fluctuation (50%)
    maxFluctuationModifier = 2f;                             // Maximum strength during fluctuation (200%)
    fluctuationDurationTicks = 6;                            // Duration of fluctuations (in mod cycles)

    // Source toggling (on/off)
    enableSourceToggling = true;                             // Enable temporary source shutdown
    sourcesToConsiderPerToggleCycleDenominator = 3;          // Consider 1/3 of map sources for toggling
    maxSourcesToToggleOffPerCycle = 2;                       // Max sources to turn off per cycle
    chanceToToggleOff = 0.5f;                                // 50% chance each candidate gets toggled off
    toggleOffStrength = 0.15f;                               // Strength when "off" (15%)
    toggleOffDurationTicks = 3;                              // Duration sources stay off (in mod cycles)

    // Contamination
    targetContaminationLingerInGameDays = 1.0f;              // How long contamination persists (~1 game day)

    // Sludge generation
    enableSludgeGeneration = true;                           // Enable sludge block spawning
    sludgeDebrisPrefabName = "Blockage";                     // DO NOT CHANGE
    chanceToSpawnSludgePerCycle = 0.15f;                     // 15% chance to spawn sludge per cycle
    maxSludgePerBadSourceSpawnEvent = 2;                     // Max sludge blocks per badwater event
    sludgeSpawnRadius = 4;                                   // Max spawn distance from contamination source
    minimumWaterDepthForSludgeSpawnInWater = 0.2f;           // Min water depth for underwater sludge (20% block height)
    allowSludgeInWaterFlowChannels = true;                   // Allow sludge in flowing water
    maxTotalActiveSludge = 50;                               // Global limit of sludge blocks on map
    maxAdjacentSludgeToPreventFullBlock = 1;                 // Max adjacent sludge before blocking new spawns

    // Sludge clearing
    enableGoodWaterClearsSludge = true;                      // Clean water can remove sludge
    chanceToClearSludgePerCycle = 0.25f;                     // 25% chance to clear sludge per cycle
    goodWaterClearRadius = 2;                                // Clean water clearing radius
    goodWaterCleanThreshold = 0.05f;                         // Max contamination considered "clean" (5%)
  