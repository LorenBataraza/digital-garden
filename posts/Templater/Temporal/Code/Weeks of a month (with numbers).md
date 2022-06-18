
<button class="date_button_today">[[<%moment(tp.file.title).format("YYYY-[W]ww")%>|<%moment(tp.file.title).format("Do,ddd")%>  - <%moment(tp.file.title).day(0).format("Do,ddd")%>]]</button>=>

---

<button class="date_button_today">[[<%moment(tp.file.title).add(1, 'week').format("YYYY-[W]ww")%>\|<%moment(tp.file.title).day(0).add(1, 'day').add(0,'week').format("Do")%> - <%moment(tp.file.title).add(1, 'week').add(0,'week').day(0).format("Do")%>]]</button>=>

--- 

<button class="date_button_today">[[<%moment(tp.file.title).add(2, 'week').format("YYYY-[W]ww")%>\|<%moment(tp.file.title).day(0).add(1, 'day').add(1,'week').format("Do")%> - <%moment(tp.file.title).add(1, 'week').add(1,'week').day(0).format("Do")%>]]</button>=>

---

<button class="date_button_today">[[<%moment(tp.file.title).add(3, 'week').format("YYYY-[W]ww")%>\|<%moment(tp.file.title).day(0).add(1, 'day').add(2,'week').format("Do")%> - <%moment(tp.file.title).add(1, 'week').add(2,'week').day(0).format("Do")%>]]</button>

---

<button class="date_button_today">[[<%moment(tp.file.title).add(4, 'week').format("YYYY-[W]ww")%>\|<%moment(tp.file.title).day(0).add(1, 'day').add(3,'week').format("Do")%> - <%moment(tp.file.title).add(1, 'week').add(3,'week').day(0).format("Do")%>]]</button>

---

<button class="date_button_today">[[<%moment(tp.file.title).add(4, 'week').format("YYYY-[W]ww")%>\|<%moment(tp.file.title).day(0).add(1, 'day').add(4,'week').format("Do,ddd")%> - <%moment(tp.file.title).add(1, 'month').subtract(1, 'day').format("Do,ddd")%>]]</button>

---
