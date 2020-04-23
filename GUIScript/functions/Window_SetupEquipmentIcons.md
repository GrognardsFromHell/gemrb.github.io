---
title: Window_SetupEquipmentIcons
module: _GemRB
---

**Prototype:** GemRB.SetupEquipmentIcons (WindowIndex, dict, slot[, Start, Offset])

**Metaclass Prototype:** SetupEquipmentIcons (Slot[, Start, Offset])

**Description:** Sets up all 12 action buttons for a player character 
with the usable equipment functions. 
It also sets up the scroll buttons left and right if needed. 
If Start is supplied, it will skip the first few items.

**Parameters:**
  * WindowIndex - the buttons' window index
  * Slot        - the player character's index in the party
  * Start       - start the equipment list from this value
  * Offset      - control ID offset to the first usable button

**Return value:** N/A

**See also:** [Window_SetupControls](Window_SetupControls.md), [UseItem](UseItem.md)
