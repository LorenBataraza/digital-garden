---
type: [[¡]]
tag: daily
langugue: en-US
aliases: []

file_creation_date: [[<%tp.file.creation_date("YYYY-MM-DD")%>]]
week:  <%moment(tp.file.title).format("YYYY-WW")%>
weekday: <%moment(tp.file.title).format("dddd")%>
---

# [[<%tp.file.title%>]]
<< [[<%moment(tp.file.title).subtract(1, 'days').format("YYYY-MM-DD")%>]] <== <button class="date_button_today">Today</button> ==> [[<%(moment(tp.file.title).add(1, 'days')).format("YYYY-MM-DD")%>]] >>

---
### Big 3
- [ ] <%tp.file.cursor(1)%>
- [ ] <%tp.file.cursor(2)%>
- [ ] <%tp.file.cursor(3)%>

---
### Week Objetives 
![[<%moment(tp.file.title).subtract(1, 'week').format("YYYY-[W]ww")%>#Next Week Objetive|no-h+clean]]
## Today's Tasks
> Refer to [[To Do's (Tq)]]

**ONE 1-2+ Hours Task:**
- [ ] <%tp.file.cursor(4)%>
<%* if (moment(tp.file.title).format("ddd") == "Sun") { %>
- [ ] Make Weekly Note
<%* } %>
<%* if (moment(tp.file.title).format("D")== 1) { %>
- [ ] Make Monthly Note
<%* } %>
<%* if (moment(tp.file.title).format("D-M") == "1-1") { %>
- [ ] Make Yearly Note
<%* } %>


**THREE 30-60 Minute Tasks**:
- [ ] <% tp.file.cursor(5) %>
- [ ] Leer 

**FIVE 10-30 Minute Tasks**:
- [ ] <% tp.file.cursor(6) %>
- [ ] Meditar
- [ ] [[Status Search|Subir un nivel de una nota]] 


### Habit Tracker


<button class="date_button_today">Sleep :: <% tp.file.cursor(7) %></button><button class="date_button_today">Writing:: </button><button class="date_button_today">Meditation:: </button>

<button class="date_button_today">Workout:: <% tp.file.cursor(8) %></button><button class="date_button_today">Reading:: </button><button class="date_button_today">Chinese:: </button>

<button class="date_button_today">Typing_speed:: 
<% tp.file.cursor(9) %></button>
[Test](https://10fastfingers.com/typing-test/english)

<button class="date_button_today"> Teeth:: </button>
<button class="date_button_today"> alcohol:: </button>

Add to metadata


## Yesterday's Roll Overs

## Events 

## Reminders
- Check Google Calendar for any events
- [[My Daily Laws]]
- [ ] ![[<%tp.date.now("YYYY-MM-DD", -1)%>#Improvement for Tomorrow]]
## Journals
### Gratitude
#### Life
>  Life_journal :: <% tp.file.cursor(9) %>
#### Personal
>  Personal_journal :: <% tp.file.cursor(10) %>


<%* if (tp.date.now("ddd") != "Sun" && tp.date.now("ddd") != "Sat") { %>

### Stocks
**How is the portoflio doing? Did you do any management?**
- 

**What is the daily reddit thread talking about today?**
- 

**What did I learn or should keep in mind?**
- 
<%* } %>
### Schedule

## Reflection
### Lingering Feelings, Observations, Thoughts
- 
### Productivity
#### Book Implementation
**What was today's event? What do I feel about my behavior? Is there something I can work on?**
- 
**Was I personal with my conversations, or was I generic? How did other people respond?**
- 
#### Previous Improvement Effectiveness 
- 
#### Good
- 
#### Bad
**What's one point of pain from today? How did it feel? How can I learn from it?**
- 
#### Improvement for Tomorrow
- 


### What you Created today
```dataview
list
from ""
where file.ctime.year = date(<%tp.file.title%>).year AND file.ctime.month = date(<%tp.file.title%>).month  AND file.ctime.day = date(<%tp.file.title%>).day 
```

### What you only Modify today
```dataview
list
from ""
where file.mtime.year = date(<%tp.file.title%>).year AND file.mtime.month = date(<%tp.file.title%>).month  AND file.mtime.day = date(<%tp.file.title%>).day AND file.ctime.day != file.mtime.day
```

