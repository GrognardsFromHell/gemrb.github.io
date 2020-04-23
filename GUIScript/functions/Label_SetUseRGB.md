---
title: Label_SetUseRGB
module: _GemRB
---

**Prototype:** GemRB.SetLabelUseRGB (WindowIndex, ControlIndex, status)

**Metaclass Prototype:** SetUseRGB (status)

**Description:** Sets a Label control to use the colors coming from the 
Font. If the font has its own color, you must set this. If a label was set 
to not use the Font's colors you can alter its color by SetLabelTextColor().
**Parameters:**
  * WindowIndex, ControlIndex - the control's reference
  * status                    - boolean

**Return value:** N/A

**See also:** [Label_SetTextColor](Label_SetTextColor.md)
