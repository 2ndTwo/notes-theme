---
title: {{ replace .Name "-" " " | title }}
dateAdded: {{ dateFormat "2006-01-02" .Date }}
type: note
menu:
  note:
    parent: {{ replace (path.Base .Dir) "-" " " | title }}

sources: []

summary: 
---
