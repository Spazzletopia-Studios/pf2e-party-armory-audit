# Party Armory Audit

Standalone PF2e v14 module. It places one compact **Armory audit** button below the real Party sheet tab row. The button opens a midnight-styled AppV2 window for party-use loot review and distribution.

It reads only the Party actor's stash and the inventories of dead non-character actors on the active scene. It does not inspect active character inventories. It changes an item only after a player explicitly gives an amount to a Party member or moves scene loot into the Party stash; PF2e's native permissions and transfer API remain authoritative.

The audit separates recorded facts from review prompts. Prompts about loot, supplies, duplicate items, and item-bonus coverage are never presented as rules failures. Automatic Bonus Progression reports its active variant and never treats stored runes as character gaps.

Version 0.3.0 makes the loot board explain itself in one view: **Scan → Compare → Give**. It summarizes the available pool, marks runes, supplies, item-bonus skills, and invested gear, then puts suggested users first without hiding other Party members. Clicking any permitted character uses PF2e's native actor-to-actor transfer to move the full stack and reports the result.

Version 0.4.0 replaces the report-like Overview with **At a glance**: available totals, real scene loot, strong matches, and possible duplicates only. Missing skill-item checks and variant diagnostics are not shown to players. Stacks gain a compact amount chooser, partial transfers keep the selected item open, and dead-scene loot can move directly into the Party stash.

Fit hints read only Party-member level, abilities, skills, and standard weapon or armor category proficiency. Armor is split into **Strong fit** and **Can use** by its Strength requirement and Dexterity cap. A Strong fit is proficient, meets Strength, and has Dexterity within one point of the cap. This is a compatibility signal, not a build verdict: feats, speeds, armor specialization, current gear, and player plans remain **Player choice**. The audit never inspects character inventory. Transfers are an explicit player action and PF2e still enforces source and destination permissions.
