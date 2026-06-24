# DreamBot SDN Submission

1. **Category:** Moneymaking
2. **Name:** APlankMaker
3. **Description:** Creates standard planks through Simple and Advanced sawmill modes, with owned-supply processing, Ironman-safe behavior, runtime editing, breaks, and statistics. Optional BETA workflows include GE restocking and selling plus Lunar Plank Make with rune and staff staging, altar switching, and safe-world hopping. For the most predictable experience, use the primary Simple or Advanced sawmill modes and leave BETA options disabled.
4. **Search tags:** plank maker, sawmill, construction, mahogany plank, teak plank, oak plank, lunar plank make, auburnvale
5. **Thread URL:** Create the script thread in the DreamBot SDN Scripts forum, then paste its full URL.
6. **Image:** `assets/aplankmaker-v3-200.png`
7. **Ironman Supported:** Yes
8. **QuickStart Supported:** No
9. **VIP Features Required:** No
10. **Script Type:** Free
11. **Script Repo:** Enter the exact name of the DreamBot-hosted repository issued through the Scripter Panel. Do not enter this GitHub repository.
12. **Script Module:** APlankMaker
13. **SDN Parameters:** Leave blank
14. **Request Notes:** Java 8-compatible source that also compiles under DreamBot's Java 11 SDN compiler. Simple and Advanced sawmill flows are the primary modes. GE restocking and selling, Woodcutting Guild, Prifddinas, Lunar altar switching, Lunar Plank Make, and Lunar world hopping are marked BETA. BETA capabilities are for users who want to evaluate newer workflows; for the most predictable experience, leave BETA options disabled. Ironman mode disables all GE actions.

## Required SDN Module

The private source module is maintained separately and is intentionally not included in this public release repository. Copy the `APlankMaker` module into the root of the DreamBot-hosted repository. The required layout is:

```text
DreamBotRepository/
+-- APlankMaker/
    +-- src/
        +-- com/
            +-- plankmaker/
                +-- ...
```

The DreamBot form does not accept a jar upload. DreamBot compiles the Java source from its own hosted repository.
