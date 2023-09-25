---
title: "My First Post"
date: 2023-08-28T17:10:19-04:00
draft: false
---

This is my first post yay!

# Does markdown work?

## It would seem so

``` console
kubectl get all 
```

```html 
<!-- The sidebar -->
<div class="sidebar">
  <a href="#home"><i class="fa fa-fw fa-home"></i> Home</a>
  <a href="#services"><i class="fa fa-fw fa-wrench"></i> Services</a>
  <a href="#clients"><i class="fa fa-fw fa-user"></i> Clients</a>
  <a href="#contact"><i class="fa fa-fw fa-envelope"></i> Contact</a>
</div>
```

```html 
  {{ range .Pages }}
    <li>
      <a href="{{ .Permalink }}">{{ .Title }}</a> - {{ .Date.Format "January 2, 2006" }}
    </li>
  {{ end }}
  ```