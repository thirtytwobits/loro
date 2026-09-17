---
"loro-crdt": patch
---

Decode replayed binary history in temporary storage and retain only unseen operations, preventing duplicate and overlapping imports from growing the document arena. Preserve undo selection metadata when the history limit evicts older entries.
