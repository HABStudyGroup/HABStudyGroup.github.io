---
date: '{{ .Date.Format }}'
draft: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---
