---
title    : "{{ replace .Name "-" " " | title }}"
date     : {{ .Date }}
draft    : false
thumbnail: "laptop.jpg"
url      : "/{{ lower .Name | urlize }}"
---

