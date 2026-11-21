# Realm of Ashgrove: An EER Demo

A one-page interactive demo of the Enhanced Entity-Relationship (EER) model, built for a Database Management Systems presentation.

**Live:** https://mahammadakiff.github.io/database-management-eer/

## Screens
1. **The Constraint Switchboard**: toggle Disjoint/Overlapping and Partial/Total, then cast heroes (Aria, Bram, Cole) into the `CHARACTER → WARRIOR / MAGE / ROGUE` specialization and watch each one get validated.
2. **AND vs OR**: shared subclass (`SPELLBLADE` under `WARRIOR` and `MAGE`) vs. category (`QUEST_GIVER` over `NPC ∪ GUILD ∪ ANCIENT_ARTIFACT`).
3. **From Diagram to Tables**: map the diagram to relations (subclass PK = superclass PK + FK), compare it with the single-table version and its NULLs, and view the `CREATE TABLE` SQL.

## Presenter keys
`→` / `←` / `Space` next/previous · `1` `2` `3` jump · `R` reset · `F` fullscreen · `M` sound

## Run
Single self-contained `index.html`: no build step, no dependencies. Double-click it to open it offline.
