---
aliases: Benislavsku
date_created: 18-08-2026 09:13
date_modified: 19-08-2026 18:51
publish: true
---
```dataview 
table without id file.link AS Persona, file.inlinks AS Muižas
from "Personu datubāze/Personas" 
where contains(file.etags, "#dzimta/Benislavski")
```
