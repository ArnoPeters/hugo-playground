---
draft: true
slug: "{{lower (replace .Name " " "-") }}"
author: ["{{ with .Site.Author.firstname }}{{ . }}{{ end }} {{ with .Site.Author.lastname }}{{ . }}{{ end }}"]
title: "{{ replace .Name "-" " " | title }}"
summary: "TODO: Write summary"
tags: [] # "string", "string", ... 
date: {{ .Date }}
publishdate: {{ .Date }}
---

TODO: Write POST contents