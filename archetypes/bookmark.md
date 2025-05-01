---
title: "{{ replace .Name "-" " " | humanize }}"
date: {{ .Date }}
draft: false
category: "Bookmark"  # Curated links
tags: [""]
sources: ""  # URL of the linked site
summary: ""  # Short description, the same as 'description' in the OpenGraph preview
---

{{< alert "link" >}}
Check out the link below.
{{< /alert >}}
<br>
{{< opengraph_preview url="" title="" description="" image="" >}}