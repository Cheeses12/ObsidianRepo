# Continue Working
```dataview
Table where (file.ctime <= date(today) - dur(1 day))
Sort date descending
```

# Upcoming Assignments
```dataview
table from "Remote Sync/Events" and #assignment
sort file.name ascending
```

# Upcoming Events
```dataview
table from "Remote Sync/Events" and !#assignment
sort file.name ascending
```


#housekeeping 