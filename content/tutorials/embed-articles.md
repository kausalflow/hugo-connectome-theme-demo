---
type: project
title: "Embed Articles"
date: 2021-05-08
authors:
  - KausalFlow
tags:
  - Tutorial
links:
  - tutorials/_index.md
  - tutorials/link-articles.md
weight: 6
---

Embed an article using the shortcode


```go
{{</* e "tutorials/graph-of-connected-articles.md" */>}}
```

Here is the result:


{{< e "tutorials/graph-of-connected-articles.md" >}}

The shortcode can take two arguments:


```go
{{</* e ref="tutorials/graph-of-connected-articles.md" title="This is a custom title" */>}}
```


{{< e ref="tutorials/graph-of-connected-articles.md" title="This is a custom title" >}}