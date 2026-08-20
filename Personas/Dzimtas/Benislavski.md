---
aliases: [Benislavsku]
date_created: 2026-08-18
date_modified: 2026-08-19
publish: true
---
```dataview 
table without id file.link AS Persona, file.inlinks AS Muižas
from "Personu datubāze/Personas" 
where contains(file.etags, "#dzimta/Benislavski")
```
