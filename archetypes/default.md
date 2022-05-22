---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date | time.Format ":date_long" }}
url: "/"
category: categories
tag: tags
draft: false
hidden: false
---

