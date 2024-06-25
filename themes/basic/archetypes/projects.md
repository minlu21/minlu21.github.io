---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
date: {{ .Date }}
draft: false
type: project
summary: "Summary of the {{ replace .Name "-" " " | title }} project"
tags: []
image: '//via.placeholder.com/640x150'
alt_text: "{{ replace .Name '-' ' ' | title }} screenshot"
link: "/"
tech_used: []
---

Description...
