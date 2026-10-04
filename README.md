# PF2e Party Armory

## Purpose and features

Review party loot, see who might use it, and give the chosen amount to a party
member. Party Armory keeps the group from sorting every item by hand.

- Lists items in the Party stash and loot on fallen non-character creatures
  on the active scene.
- Shows useful gear, supplies, possible duplicates and suggested recipients.
- Lets you move part of a stack, give the whole stack, or collect scene loot
  into the Party stash.
- Leaves the final choice to the player. Fit hints are advice, not rules
  checks or a verdict on a character's build.

It does not read the contents of active character inventories. The former
name was Party Armory Audit; its ID remains `pf2e-party-armory-audit`, so old
installs still update normally. No other module is required.

## Setup

Requires Foundry V13 with PF2e 7.12.2 or later on that line, or Foundry V14
with PF2e 8.x.

Install **PF2e Party Armory** with the
[SpazzMods Installer](https://github.com/Spazzletopia-Studios/spazzmods-installer/releases/latest),
or paste this into Foundry's **Install Module → Manifest URL** box:

`https://github.com/Spazzletopia-Studios/pf2e-party-armory-audit/releases/latest/download/module.json`

Enable the module in the world's **Manage Modules** window. Use a PF2e Party
actor with character members and items in its stash. For scene loot, view
the scene containing the fallen creatures. Keep a GM online for native
player loot requests and give users the normal PF2e access they need.

## Quick start

1. Open the **Party actor sheet**, not a character sheet.
2. Click **Armory audit** below the Party sheet's tab row.
3. In **Loot review**, choose **All**, **Stash**, or **Scene loot**, then select
   an item. Search by name if the list is long.
4. Read the suggested recipients and their fit hints. Choose **Amount**, or
   click **All** to select the full stack.
5. Click the chosen recipient's **Give** control, or **Move to stash** for
   scene loot. Check the destination inventory to confirm the transfer.

## Detailed use

### Review the available loot

**Loot review** opens first. It follows **Scan → Compare → Give**. Each item
names its source and shows its quantity and useful gear signals. Expand a
row to see all Party members; suggested matches come first, but other
members remain available when permissions allow.

Use **Open item details** to inspect the native item before moving it. The
search and source filters change only the displayed list; they do not move
or delete anything.

### Choose an amount and destination

For stacks, use the minus/plus controls, enter an amount, or click **All**.
The amount cannot exceed the available stack. A partial transfer leaves the
item selected so you can give more to another member. A full transfer closes
that item row.

Giving an item uses PF2e's native actor-to-actor transfer. A greyed-out control
means the current user cannot make that transfer. Ask the GM to check access
to both the source and destination; this tool does not bypass permissions.

For a fallen creature's item, **Move to stash** puts the selected amount in
the Party inventory instead of a character inventory. Browsing alone never
changes items.

### Read the other panels

- **At a glance** shows available item totals, healing supplies, rations,
  ammunition, new scene loot, strong matches and possible duplicates.
- **Supplies** lists available healing items, ration servings, ammunition,
  and useful skill gear in the scanned pool.

The totals describe the stash and scanned scene loot. They are not a full
audit of what each character already carries.

### Understand fit hints

Hints use member level, abilities, skills and standard weapon/armor
proficiencies. Armor marked **Strong fit** meets its proficiency and Strength
checks and has Dexterity within one point of its cap. **Can use** is a weaker
match. **Player choice** means there is no clear standard fit signal.

Class or ancestry features can grant better proficiency than the hint reads.
Feats, speed changes, armor specialization, worn gear and personal plans are
not fully considered. Check the actual character sheet before deciding.
Missing-gear prompts are not rules failures. Automatic Bonus Progression
does not turn stored runes into a claim that a character is missing bonuses.

## Limits and help

- The scan does not inspect active character inventories or unseen scenes.
- Multiple unlinked dead tokens of one base actor may not all appear as
  separate sources. Check the scene when expected loot is missing.
- A player's **Gave** notice can appear before a GM finishes a native loot
  request. Confirm the receiving inventory before clicking again; a notice
  alone is not proof of completion.
- If items changed elsewhere, close and reopen the Armory to scan again.
- No feat-aware equipment optimizer or complete build audit is provided.

## Get help

[Get Help](https://github.com/Spazzletopia-Studios/spazzmods-support) — report a bug, get install help, ask a question, or suggest an idea.
