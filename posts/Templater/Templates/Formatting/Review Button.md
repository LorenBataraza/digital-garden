
```button
name Review Update
type line(5) text
action <% tp.date.now("YYYY-MM-DD") %> 
color blue
templater true
```
^button-k17d

```button  
name Add Current Time  
type line(1) text  
action <% tp.date.now("HH:mm:ss") %>  
replace [1,1]  
templater true  
```


```javascript
<script type="text/javascript>"
  $( function() {
      $( "#datepicker" ).datepicker({
          showOn: "button",
          buttonImage: "https://jqueryui.com/resources/demos/datepicker/images/calendar.gif",
          buttonImageOnly: true,
          buttonText: "Select date"
      });
    });
    </script>
```