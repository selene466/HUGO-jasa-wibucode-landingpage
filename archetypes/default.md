---
title   : "{{ replace .Name "-" " " | title }}"
date    : {{ .Date }}
draft   : false
url     : "/{{ lower .Name | urlize }}"
---

