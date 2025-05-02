---
title: "{{ replace .Name "-" " " | humanize }}"  # Auto-generate title from filename
date: {{ .Date }}
draft: false
category: "Music" 
tags: [""]
---

{{< icon "youtube" >}} **ARTIST – «SONG»**

{{< icon "music" >}} **ARTIST – «SONG)»**

{{< youtube YT-ID >}}