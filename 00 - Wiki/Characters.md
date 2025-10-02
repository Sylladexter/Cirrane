---
cssclasses:
  - cards
  - cards-1-1
  - cards-cols-4
---
## Major
```dataview
TABLE WITHOUT ID image as "Cover", file.link
FROM #character 
WHERE contains(relevance,"major") and !contains(file.name, "character")
```

## Secondary

## Minor



