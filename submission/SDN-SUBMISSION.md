# DreamBot SDN Submission

1. **Category:** Moneymaking
2. **Name:** APlankMaker
3. **Description:** Creates standard planks through Simple and Advanced sawmill modes, with owned-supply processing, optional BETA GE restocking and selling, Ironman-safe behavior, runtime editing, breaks, and statistics. A separate BETA Lunar Plank Make mode supports eligible logs, rune and staff staging, optional altar switching, and optional safe-world hopping.
4. **Search tags:** plank maker, sawmill, construction, mahogany plank, teak plank, oak plank, lunar plank make, auburnvale
5. **Thread URL:** Create the script thread in the DreamBot SDN Scripts forum, then paste its full URL.
6. **Image:** `assets/aplankmaker-200.png`
7. **Ironman Supported:** Yes
8. **QuickStart Supported:** No
9. **VIP Features Required:** No
10. **Script Type:** Free
11. **Script Repo:** Enter the exact name of the DreamBot-hosted repository issued through the Scripter Panel. Do not enter this GitHub repository.
12. **Script Module:** APlankMaker
13. **SDN Parameters:** Leave blank
14. **Request Notes:** Java 8-compatible source that also compiles under DreamBot's Java 11 SDN compiler. Simple and Advanced sawmill flows are primary modes. GE restocking and selling, Woodcutting Guild, Prifddinas, Lunar altar switching, Lunar Plank Make, and Lunar world hopping are marked BETA. Ironman mode disables all GE actions.

## Required SDN Module

The private local source module is prepared at:

`C:\Users\nicho\Desktop\AI Plank Maker\target\DreamBot SDN Module\APlankMaker`

Copy the `APlankMaker` module into the root of the DreamBot-hosted repository. The required layout is:

```text
DreamBotRepository/
+-- APlankMaker/
    +-- src/
        +-- com/
            +-- plankmaker/
                +-- ...
```

The DreamBot form does not accept a jar upload. DreamBot compiles the Java source from its own hosted repository.
