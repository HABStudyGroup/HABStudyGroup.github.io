---
date: '{{ .Date | date: "%B %d, %Y"}}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---
