---
draft: true
author: ["{{ with .Site.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Author.lastname }}{{ . }}{{ end }}"]
title: "{{ replace .Name "-" " " | title }}"
tags: [] # "string", "string", ... 
date: {{ dateFormat "2006-01-02" .Date }}
publishdate:  {{ dateFormat "2006-01-02" .Date }}
---

TODO: Write SERIES intro