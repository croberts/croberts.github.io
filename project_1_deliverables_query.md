---
layout: default
share: true
---
  
To export: copy in view mode  
  
```dataview  
TABLE WITHOUT ID  
	subject,  
	type,  
	format,  
	priority as milestone  
FROM "Nausoleum/Docs/Art/Deliverables Data"  
sort priority asc, type asc, subject asc  
```  
