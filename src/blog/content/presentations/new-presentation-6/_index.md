+++
draft = true
slug = "pres6"  # slug property is not working for _index.md, url property is -> https://github.com/gohugoio/hugo/issues/7124
url = "presentations/pres6"
author = ["Arno Peters"]
title = "pres6"
summary = "TODO"
description = "TODO: Write description"
tags = [] # "string", "string", ...
date = 2022-12-04T15:35:54+01:00
publishdate = 2022-12-04T15:35:54+01:00

outputs = ["Reveal"]
[reveal_hugo]
theme = "custom/aps-robot-lung"
#custom_theme = "reveal-hugo/themes/aps-robot-lung.css"
#custom_css = "custom.css"  # files can be page resource
#custom_js = "custom.js"
highlight_theme= "agate"

+++

## Highlight specific lines

`{<line numbers separated by comma>}`

{{< highlight md >}}
```go{1,3-5}
package main
import "fmt"
func main() {
    fmt.Println("Hello world!")
}
```
{{< /highlight >}}
```go{1,3-5}
package main
import "fmt"
func main() {
    fmt.Println("Hello world!")
}
```
---

## Multi step highlight

`{<line numbers separated by pipe>}`

{{< highlight md >}}
```go{1|2|3-5}
package main
import "fmt"
func main() {
    fmt.Println("Hello world!")
}
```
{{< /highlight >}}

<!-- hl_lines=["42"],file="playwright.config.ts",fileLines="38-45",allowdownload=false, -->

```go {linenos=table,allowdownload=false,highlightjs="1,2|1,3-5"}
package main
import "fmt"
func main() {
    fmt.Println("Hello world!")
}
```

---
NIEUWE PAGINA

```yaml {linenos=table,highlightjs="18,20|19,22-25",file="playwrightBuild.yml",fileLines="19-25"}
# /.github/workflows/playwright-onDemand.yml
```
