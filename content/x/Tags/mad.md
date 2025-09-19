# Dreams
```dataview
TABLE date as "Date"
WHERE contains(tags, [[mad]]) AND contains(tags, [[dreams]])
SORT date DESC
```
# Realizations
```dataview
TABLE date as "Date"
WHERE contains(tags, [[mad]]) AND contains(tags, [[realizations]])
SORT date DESC
```
# Thoughts
```dataview
TABLE date as "Date" FROM [[mad]] and [[thoughts]]
SORT date DESC
```
# Encounters
```dataview
TABLE date as "Date"
WHERE contains(tags, [[mad]]) AND contains(tags, [[encounters]])
SORT date DESC
```