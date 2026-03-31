---
'@directus/app': patch
---

Fixes a bug where duplicating an item (“Save as Copy”) could move M2M relations defined inside a translations collection
(eg foo_translations) to the new copy, leaving the original empty.
