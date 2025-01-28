---
aliases:
  - _DataView
date: 2025-01-15
tags: 
status:
---
```dataview
TABLE status as Status, aliases as Title, deadline as DL
where status = "raw" and aliases != ""
SORT deadline asc
```


