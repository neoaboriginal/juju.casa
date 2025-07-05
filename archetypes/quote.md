---
title: "{{ replace .Name "-" " " | humanize }}"
date: {{ .Date }}
draft: false
category: "Quote"  # Curated quotes
tags: [""]
quoteText: ""  # The quote itself
quoteAuthor: ""  # Author of the quote
---
{{< typeit 
  tag=h2
  lifeLike=true
>}}
ENTER-QUOTE-ON-THIS-LINE
{{< /typeit >}}

~ ENTER-AUTHOR