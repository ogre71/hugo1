---
title: "Looping"
date: 2023-08-30T08:34:45-04:00
draft: false
categories: ['Hugo', 'code']
---

``` golang
Looping:  

{{ $best_friends := slice "pumbaa" "timon" "nala" "rafiki" }}
<ul>
  {{ range $best_friends }}
  <li>{{ . }}</li>
  {{end }}
</ul>
```