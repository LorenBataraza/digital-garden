```dataview
table tags , elink(string(Url), default(string(Host), "No se ") ) AS Link, striptime(file.mtime) As Time
from outgoing([[<%tp.file.title%>]])
```