---
title: "{{ replace .Name "-" " " | humanize }}"
date: {{ .Date }}
draft: false
category: "Repost"  # Personal reposts
tags: [""]
repostAuthor: ""  # Original author
repostLink: ""  # Link to original post
---

{{< tweet user="UserName@" id="StringOfNumbers" >}}
OR
{{< alert "telegram" >}}
Original post available [here](https://t.me/mindsetmachine/2156)
{{< /alert >}}