---
langugue: es
file_creation_date: [[<%tp.file.creation_date("YYYY-MM-DD")%>]]
aliases: 
cssclass: 
---

## <%tp.file.title%>  Files <=> [[}   ]] <=> <button class="date_button_today">[[ - Template]] </button>
### Null Status 
```dataview
list
from [[<%tp.file.title%>]]
where file.name != " Template" AND file.name != "Metadata Structure" AND status = null
```

### Status = 🟥
```dataview
list
from [[<%tp.file.title%>]]
where file.name != " Template" AND file.name != "Metadata Structure" AND status= "🟥" AND status != null
```

### Status = 🟧
```dataview
list
from [[<%tp.file.title%>]]
where file.name != " Template" AND file.name != "Metadata Structure" AND status= "🟧" AND status != null
```

### Status = 🟨
```dataview
list
from [[<%tp.file.title%>]]
where file.name != " Template" AND file.name != "Metadata Structure" AND status= "🟨" AND status != null
```
### Status = 🟩
```dataview
list
from [[<%tp.file.title%>]]
where file.name != " Template" AND file.name != "Metadata Structure" AND status= "🟩" AND status != null
```
### Status = 🟦

```dataview
list
from [[<%tp.file.title%>]]
where file.name != " Template" AND file.name != "Metadata Structure" AND status= "🟦" AND status != null
```