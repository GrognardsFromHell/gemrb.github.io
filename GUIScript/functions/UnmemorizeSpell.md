---
title: UnmemorizeSpell
module: GemRB
---

**Prototype:** GemRB.UnmemorizeSpell (PartyID, SpellType, Level, Index[, onlydepleted])

**Description:** Unmemorizes specified memorized spell. If onlydepleted is 
set, it will only remove an already depleted spell (with the same resref as 
the provided spell).

**Parameters:**
  * PartyID      - the PC's position in the party
  * SpellType    - 0 - priest, 1 - wizard, 2 - innate
  * Level        - the memorized spell's level
  * Index        - the memorized spell's index
  * onlydepleted - remove only an already depleted spell with the same resref as the specified spell

**Return value:** boolean, 1 on success

**See also:** [MemorizeSpell](MemorizeSpell.md), [GetMemorizedSpellsCount](GetMemorizedSpellsCount.md), [GetMemorizedSpell](GetMemorizedSpell.md)
