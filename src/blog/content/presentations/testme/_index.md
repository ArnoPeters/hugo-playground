+++
outputs = ["Reveal"]

draft = true
slug = "testme"  # slug property is not working for _index.md, url property is -> https://github.com/gohugoio/hugo/issues/7124
url = "presentations/testme"
author = ["Arno Peters"]
title = "Testme"
summary = "TODO: Write summary"
description = "TODO: Write description"
tags = [] # "string", "string", ...
date = 2022-12-09T17:56:54+01:00
publishdate = 2022-12-09T17:56:54+01:00
showAboutMe = false  #todo: not implemented yet

[reveal_hugo]
#theme = "custom/aps-robot-lung"
#custom_theme = "reveal-hugo/themes/aps-robot-lung.css"
#highlight_theme= "agate"
#custom_css = "custom.css"  # files can be page resource
#custom_js = "custom.js"
+++
# Testme
TODO: Write Slide

{{% reveal-hugo/note %}}
TODO: speaker notes
- wat zeg ik

- wat is de conclusie die ik eruit kan trekken

{{% /reveal-hugo/note %}}
