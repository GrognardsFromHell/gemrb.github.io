---
title: GetGameString
module: GemRB
---

**Prototype:** GemRB.GetGameString (Index)

**Description:** Returns a system variable of string type referenced by Index.

**Parameters:** Index
  * 0 - returns the loading picture's name (MOS resref)
  * 1 - returns the current area's name (ARE resref)
  * 2 - returns the table name for the text screen (2DA resref)

**Return value:** string - the referenced system variable

**See also:** [GetSystemVariable](GetSystemVariable.md), [GetToken](GetToken.md)
