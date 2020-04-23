---
title: Window_SetPicture
module: _GemRB
---

**Prototype:** GemRB.SetWindowPicture (WindowIndex, MosResRef)

**Metaclass Prototype:** SetPicture (MosResRef)

**Description:** Changes the background of a Window.

**Parameters:**
  * WindowIndex - the index returned by LoadWindow()
  * MosResRef   - the name of the background image (.mos resref)

**Return value:** N/A

**Example:**

      LoadPic = GemRB.GetGameString (STR_LOADMOS)
      if LoadPic=='':
          LoadPic = 'GUILS0' + str(GemRB.Roll (1,9,0))
      GemRB.SetWindowPicture (LoadScreen, LoadPic)
The above snippet is responsible to generate a random loading screen.

**See also:** [Button_SetPicture](Button_SetPicture.md)
